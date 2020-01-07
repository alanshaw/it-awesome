# it-awesome

Useful modules for working with async iterables:

* [`abortable-iterator`](https://github.com/alanshaw/abortable-iterator) - Make any iterator or iterable abortable via an AbortSignal
* [`async-iterator-to-pull-stream`](https://github.com/alanshaw/async-iterator-to-pull-stream) - Convert a (async) iterator to a pull stream
* [`emitterator`](https://github.com/alanshaw/emitterator) - Convert async iterator to event emitter
* [`event-iterator`](https://github.com/rolftimmermans/event-iterator) - Convert event emitter to async iterator
* [`get-iterator`](https://github.com/alanshaw/get-iterator) - Get the default iterator or async iterator for an Iterable
* [`it-all`](https://github.com/achingbrain/it/blob/master/packages/it-all) - Collect the contents of an iterable into an array
* [`it-concat`](https://github.com/alanshaw/it-concat) - Concat all buffers/strings yielded from an async iterable into a single BufferList/string
* [`it-batch`](https://github.com/achingbrain/it/blob/master/packages/it-batch) - Batch up the contents of an iterable into arrays
* [`it-block`](https://github.com/alanshaw/it-block) - Transform input into equally-sized blocks of output
* [`it-buffer`](https://github.com/mkg20001/it-buffer) - Is it a string? Is it a `BufferList`? Or just a `Buffer`? Worry no more with it-buffer! It exposes a transform stream that converts all buffer-like objects into true buffers
* [`it-buffer-stream`](https://github.com/achingbrain/it/blob/master/packages/it-buffer-stream) - An async iterator that emits buffers containing bytes up to a certain length
* [`it-first`](https://github.com/achingbrain/it/blob/master/packages/it-first) - Returns the first item from an async iterable
* [`it-flat-batch`](https://github.com/achingbrain/it/blob/master/packages/it-flat-batch) Take an iterable of variable length arrays and make them all the same length
* [`it-glob`](https://github.com/achingbrain/it/blob/master/packages/it-glob) - Async iterable filename pattern matcher
* [`it-goodbye`](https://github.com/alanshaw/it-goodbye) - Add a goodbye handshake to a [duplex async iterable](https://gist.github.com/alanshaw/591dc7dd54e4f99338a347ef568d6ee9#duplex-it)
* [`it-handshake`](https://github.com/jacobheun/it-handshake) - Create handshakes for binary protocols with [duplex async iterable](https://gist.github.com/alanshaw/591dc7dd54e4f99338a347ef568d6ee9#duplex-it)
* [`it-keepalive`](https://github.com/alanshaw/it-keepalive) - Keep an async iterable alive by yielding a value if it doesn't yield a value before the timeout
* [`it-last`](https://github.com/achingbrain/it/blob/master/packages/it-last) - Returns the last item from an async iterable
* [`it-length-prefixed`](https://github.com/alanshaw/it-length-prefixed) - Streaming length prefixed buffers with async iterables
* [`it-multipart`](https://github.com/achingbrain/it/blob/master/packages/it-multipart) - HTTP multipart message parser
* [`it-pair`](https://github.com/alanshaw/it-pair) - A pair of {source, sink} streams that are internally connected (what goes into the sink comes out the source)
* [`it-parallel-batch`](https://github.com/achingbrain/it/blob/master/packages/it-parallel-batch) Take an iterable of functions that return promises and run them in parallel in batches
* [`it-pipe`](https://github.com/alanshaw/it-pipe) - Utility to "pipe" async iterables together
* [`it-pushable`](https://github.com/alanshaw/it-pushable) - Pushable iterable
* [`it-reader`](https://github.com/alanshaw/it-reader) - Read an exact number of bytes from a binary (async) iterable
* [`it-tar`](https://github.com/alanshaw/it-tar) - Streaming tar parser (and maybe a generator in the future) and nothing else
* [`it-to-stream`](https://github.com/alanshaw/it-to-stream) - Convert streaming iterables to Node.js streams
* [`it-ws`](https://github.com/alanshaw/it-ws) - Simple async iterators for websocket client and server connections
* [`iterable-ndjson`](https://github.com/alanshaw/iterable-ndjson) - NDJSON parsing/encoding
* [`paramap-it`](https://github.com/alanshaw/paramap-it) - Parallel mapping for async iterables
* [`pull-stream-to-async-iterator`](https://github.com/alanshaw/pull-stream-to-async-iterator) - Convert a pull stream to an async iterator
* [`recoverable-iterator`](https://github.com/alanshaw/recoverable-iterator) - If an iterator errors, restart and continue
* [`stream-to-it`](https://github.com/alanshaw/stream-to-it) - Convert Node.js streams to streaming iterables
* [`streaming-iterables`](https://github.com/bustle/streaming-iterables) - A Swiss army knife for async iterables
* [`iter-tools`](https://github.com/iter-tools/iter-tools) - The iterable toolbox
