---
layout: doc
title: AMQP - Codeception - Documentation
---



<div class="btn-group" role="group" style="float: right" aria-label="..."><a class="btn btn-default" href="https://github.com/Codeception/module-AMQP/releases">Releases</a><a class="btn btn-default" href="https://github.com/Codeception/module-amqp/tree/master/src/Codeception/Module/AMQP.php"><strong>source</strong></a></div>

# AMQP
### Installation

{% highlight yaml %}
composer require --dev codeception/module-amqp

{% endhighlight %}

### Description



This module interacts with message broker software that implements
the Advanced Message Queuing Protocol (AMQP) standard. For example, RabbitMQ (tested).

<div class="alert alert-info">
To use this module with Composer you need <em>"php-amqplib/php-amqplib": "~2.4"</em> package.
</div>

### Config

* host: localhost - host to connect
* username: guest - username to connect
* password: guest - password to connect
* vhost: '/' - vhost to connect
* cleanup: true - defined queues will be purged before running every test.
* queues: [mail, twitter] - queues to cleanup
* single_channel - create and use only one channel during test execution

#### Example

    modules:
        enabled:
            - AMQP:
                host: 'localhost'
                port: '5672'
                username: 'guest'
                password: 'guest'
                vhost: '/'
                queues: [queue1, queue2]
                single_channel: false

### Public Properties

* connection - AMQPStreamConnection - current connection

### Actions

#### bindQueueToExchange

* `param string` $queue
* `param string` $exchange
* `param string` $routing_key
* `param bool` $nowait
* `param ?array` $arguments
* `param ?int` $ticket
* `return mixed`

Binds a queue to an exchange

This is an alias of method `queue_bind` of `PhpAmqpLib\Channel\AMQPChannel`.

{% highlight php %}

<?php
$I->bindQueueToExchange(
    'nameOfMyQueueToBind', // name of the queue
    'transactionTracking.transaction', // exchange name to bind to
    'your.routing.key' // Optionally, provide a binding key
)

{% endhighlight %}


#### declareExchange

* `param string` $exchange
* `param string` $type
* `param bool` $passive
* `param bool` $durable
* `param bool` $auto_delete
* `param bool` $internal
* `param bool` $nowait
* `param ?array` $arguments
* `param ?int` $ticket
* `return mixed`

Declares an exchange

This is an alias of method `exchange_declare` of `PhpAmqpLib\Channel\AMQPChannel`.

{% highlight php %}

<?php
$I->declareExchange(
    'nameOfMyExchange', // exchange name
    'topic' // exchange type
)

{% endhighlight %}


#### declareQueue

* `param string` $queue
* `param bool` $passive
* `param bool` $durable
* `param bool` $exclusive
* `param bool` $auto_delete
* `param bool` $nowait
* `param ?array` $arguments
* `param ?int` $ticket
* `return mixed`

Declares queue, creates if needed

This is an alias of method `queue_declare` of `PhpAmqpLib\Channel\AMQPChannel`.

{% highlight php %}

<?php
$I->declareQueue(
    'nameOfMyQueue', // exchange name
)

{% endhighlight %}


#### dontSeeQueueIsEmpty

* `param string` $queue
* `return void`

Checks if queue is not empty.

{% highlight php %}

<?php
$I->pushToQueue('queue.emails', 'Hello, davert');
$I->dontSeeQueueIsEmpty('queue.emails');

{% endhighlight %}


#### grabMessageFromQueue

* `param string` $queue
* `return ?\PhpAmqpLib\Message\AMQPMessage`

Takes last message from queue.

{% highlight php %}

<?php
$message = $I->grabMessageFromQueue('queue.emails');

{% endhighlight %}


#### purgeAllQueues

* `return void`

Purge all queues defined in config.

{% highlight php %}

<?php
$I->purgeAllQueues();

{% endhighlight %}


#### purgeQueue

* `param string` $queueName
* `return void`

Purge a specific queue defined in config.

{% highlight php %}

<?php
$I->purgeQueue('queue.emails');

{% endhighlight %}


#### pushToExchange

* `param string` $exchange
* `param \PhpAmqpLib\Message\AMQPMessage|string` $message
* `param ?string` $routing_key
* `return void`

Sends message to exchange by sending exchange name, message
and (optionally) a routing key

{% highlight php %}

<?php
$I->pushToExchange('exchange.emails', 'thanks');
$I->pushToExchange('exchange.emails', new AMQPMessage('Thanks!'));
$I->pushToExchange('exchange.emails', new AMQPMessage('Thanks!'), 'severity');

{% endhighlight %}


#### pushToQueue

* `param string` $queue
* `param \PhpAmqpLib\Message\AMQPMessage|string` $message
* `return void`

Sends message to queue

{% highlight php %}

<?php
$I->pushToQueue('queue.jobs', 'create user');
$I->pushToQueue('queue.jobs', new AMQPMessage('create'));

{% endhighlight %}


#### scheduleQueueCleanup

* `param string` $queue
* `return void`

Add a queue to purge list


#### seeMessageInQueueContainsText

* `param string` $queue
* `param string` $text
* `return void`

Checks if message containing text received.

**This method drops message from queue**
**This method will wait for message. If none is sent the script will stuck**.

{% highlight php %}

<?php
$I->pushToQueue('queue.emails', 'Hello, davert');
$I->seeMessageInQueueContainsText('queue.emails','davert');

{% endhighlight %}


#### seeNumberOfMessagesInQueue

* `param string` $queue
* `param int` $expected
* `return void`

Checks that queue have expected number of message

{% highlight php %}

<?php
$I->pushToQueue('queue.emails', 'Hello, davert');
$I->seeNumberOfMessagesInQueue('queue.emails',1);

{% endhighlight %}


#### seeQueueIsEmpty

* `param string` $queue
* `return void`

Checks that queue is empty

{% highlight php %}

<?php
$I->pushToQueue('queue.emails', 'Hello, davert');
$I->purgeQueue('queue.emails');
$I->seeQueueIsEmpty('queue.emails');

{% endhighlight %}

<p>&nbsp;</p><div class="alert alert-warning">Module reference is taken from the source code. <a href="https://github.com/Codeception/module-amqp/tree/master/src/Codeception/Module/AMQP.php">Help us to improve documentation. Edit module reference</a></div>
