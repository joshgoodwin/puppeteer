<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Browser](./puppeteer.browser.md)

## Browser class

<b>Signature:</b>

```typescript
export declare class Browser extends EventEmitter 
```
<b>Extends:</b> [EventEmitter](./puppeteer.eventemitter.md)

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(connection, contextIds, ignoreHTTPSErrors, defaultViewport, process, closeCallback)](./puppeteer.browser._constructor_.md) |  | Constructs a new instance of the <code>Browser</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [\_closeCallback](./puppeteer.browser._closecallback.md) |  | BrowserCloseCallback |  |
|  [\_connection](./puppeteer.browser._connection.md) |  | [Connection](./puppeteer.connection.md) |  |
|  [\_contexts](./puppeteer.browser._contexts.md) |  | Map&lt;string, [BrowserContext](./puppeteer.browsercontext.md)<!-- -->&gt; |  |
|  [\_defaultContext](./puppeteer.browser._defaultcontext.md) |  | [BrowserContext](./puppeteer.browsercontext.md) |  |
|  [\_defaultViewport](./puppeteer.browser._defaultviewport.md) |  | Viewport |  |
|  [\_ignoreHTTPSErrors](./puppeteer.browser._ignorehttpserrors.md) |  | boolean |  |
|  [\_process](./puppeteer.browser._process.md) |  | ChildProcess |  |
|  [\_targets](./puppeteer.browser._targets.md) |  | Map&lt;string, [Target](./puppeteer.target.md)<!-- -->&gt; |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [\_createPageInContext(contextId)](./puppeteer.browser._createpageincontext.md) |  |  |
|  [\_disposeContext(contextId)](./puppeteer.browser._disposecontext.md) |  |  |
|  [\_getVersion()](./puppeteer.browser._getversion.md) |  |  |
|  [\_targetCreated(event)](./puppeteer.browser._targetcreated.md) |  |  |
|  [\_targetDestroyed(event)](./puppeteer.browser._targetdestroyed.md) |  |  |
|  [\_targetInfoChanged(event)](./puppeteer.browser._targetinfochanged.md) |  |  |
|  [browserContexts()](./puppeteer.browser.browsercontexts.md) |  |  |
|  [close()](./puppeteer.browser.close.md) |  |  |
|  [create(connection, contextIds, ignoreHTTPSErrors, defaultViewport, process, closeCallback)](./puppeteer.browser.create.md) | <code>static</code> |  |
|  [createIncognitoBrowserContext()](./puppeteer.browser.createincognitobrowsercontext.md) |  |  |
|  [defaultBrowserContext()](./puppeteer.browser.defaultbrowsercontext.md) |  |  |
|  [disconnect()](./puppeteer.browser.disconnect.md) |  |  |
|  [isConnected()](./puppeteer.browser.isconnected.md) |  |  |
|  [newPage()](./puppeteer.browser.newpage.md) |  |  |
|  [pages()](./puppeteer.browser.pages.md) |  |  |
|  [process()](./puppeteer.browser.process.md) |  |  |
|  [target()](./puppeteer.browser.target.md) |  |  |
|  [targets()](./puppeteer.browser.targets.md) |  |  |
|  [userAgent()](./puppeteer.browser.useragent.md) |  |  |
|  [version()](./puppeteer.browser.version.md) |  |  |
|  [waitForTarget(predicate, options)](./puppeteer.browser.waitfortarget.md) |  |  |
|  [wsEndpoint()](./puppeteer.browser.wsendpoint.md) |  |  |
