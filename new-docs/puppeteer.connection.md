<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Connection](./puppeteer.connection.md)

## Connection class

<b>Signature:</b>

```typescript
export declare class Connection extends EventEmitter 
```
<b>Extends:</b> [EventEmitter](./puppeteer.eventemitter.md)

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(url, transport, delay)](./puppeteer.connection._constructor_.md) |  | Constructs a new instance of the <code>Connection</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [\_callbacks](./puppeteer.connection._callbacks.md) |  | Map&lt;number, ConnectionCallback&gt; |  |
|  [\_closed](./puppeteer.connection._closed.md) |  | boolean |  |
|  [\_delay](./puppeteer.connection._delay.md) |  | number |  |
|  [\_lastId](./puppeteer.connection._lastid.md) |  | number |  |
|  [\_sessions](./puppeteer.connection._sessions.md) |  | Map&lt;string, [CDPSession](./puppeteer.cdpsession.md)<!-- -->&gt; |  |
|  [\_transport](./puppeteer.connection._transport.md) |  | ConnectionTransport |  |
|  [\_url](./puppeteer.connection._url.md) |  | string |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [\_onClose()](./puppeteer.connection._onclose.md) |  |  |
|  [\_onMessage(message)](./puppeteer.connection._onmessage.md) |  |  |
|  [\_rawSend(message)](./puppeteer.connection._rawsend.md) |  |  |
|  [createSession(targetInfo)](./puppeteer.connection.createsession.md) |  |  |
|  [dispose()](./puppeteer.connection.dispose.md) |  |  |
|  [fromSession(session)](./puppeteer.connection.fromsession.md) | <code>static</code> |  |
|  [send(method, params)](./puppeteer.connection.send.md) |  |  |
|  [session(sessionId)](./puppeteer.connection.session.md) |  |  |
|  [url()](./puppeteer.connection.url.md) |  |  |
