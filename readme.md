# Reactive Programming
- Reactive Programming = Concept
- RxJava = JAVA Framework/Tool

## What is it?

* '**Reactive Programming means you are doing all your IO bound
tasks such as network calls asynchronously**' OR
'**Reactive Programming Is Programming With Asynchronous Data Streams**'

* For an instance say your application calls an external REST API or a database,
you can do that invocation asynchronously. If you do so your current thread does not block.
You can serve lots of requests by merely spawning one or few threads.
If you follow blocking approach you need to have one thread to handle each and every request.

* Other than that you may use callbacks to do the same.
You can do asynchronous invocation using callbacks.
But if you do so sometimes you may ended up with callback hell. Having one callback
inside another leads to very complex codes which are very hard to maintain.

## RxJava

* RxJava lends you write asynchronous code which is much more simple,
composable and readable. Also RxJava provides you a lots of powerful operators
such as Map, Zip etc which makes your code much more simple while boosting the
performance due to parallel executions of different tasks
which are not dependent on each other.

* When it comes to RxJava it offers two main facilities to a programmer.
First it offers a nice composable API using a rich set of operators such as zip,
concat, map etc. This yields more simple and readable code.
When it comes to code, readability and simplicity are the uttermost important properties.
Second, it provides excellent abstractions, that enable concurrency to become declarative.

* RxJava is not another Observer implementation with set of operators rather
it gives you good error handling and retry mechanisms which are really handy.
