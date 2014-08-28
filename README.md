# redis-tools

Tools. For doing stuff with Redis.

## bin

### info

	$> info <key1> <key2> ...

Print information about Redis's current state to STDOUT. If no keys are specificed then all keys(and their values) are displayed.

### publish

	$> publish <channel> <msg1> <msg2> ...

Publish one or more messages to a PubSub channel.

_This should be taught to read from STDIN._

### subscribe

	$> subscribe <channel>

Subscribe to a PubSub channel and print each message received to STDOUT.

## See also

* http://redis.io/
* https://pypi.python.org/pypi/redis