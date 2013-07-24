# EventSource for Go [![Build Status](https://travis-ci.org/msgehard/goEventSource.png?branch=master)](https://travis-ci.org/msgehard/goEventSource)

This library is an initial implementation of Server Sent Events(SSE)/EventSource for Go.
It is patterned after the [Go Websockets](https://code.google.com/p/go/source/browse/?repo=net#hg%2Fwebsocket) library.
It is very much a work in progress. Pull requests welcome.

## Development

1. Make sure your GOPATH is set to the root of the project.

```
  export GOPATH=`pwd`
```
  
1. Please write tests for any code that you add. To run existing tests:

```
  bin/test
```

## References

See `src/main.go` for an example of how to use this library.

For more information about SSE/EventSource, see:

[http://en.wikipedia.org/wiki/Server-sent_events](http://en.wikipedia.org/wiki/Server-sent_events)

[http://www.html5rocks.com/en/tutorials/eventsource/basics/](http://www.html5rocks.com/en/tutorials/eventsource/basics/)
