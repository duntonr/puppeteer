<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Debugger](./puppeteer.protocol.debugger.md) &gt; [ScriptParsedEvent](./puppeteer.protocol.debugger.scriptparsedevent.md)

## Protocol.Debugger.ScriptParsedEvent interface

Fired when virtual machine parses script. This event is also fired for all known and uncollected scripts upon enabling debugger.

<b>Signature:</b>

```typescript
export interface ScriptParsedEvent 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [codeOffset](./puppeteer.protocol.debugger.scriptparsedevent.codeoffset.md) | [integer](./puppeteer.protocol.integer.md) | If the scriptLanguage is WebAssembly, the code section offset in the module. |
|  [debugSymbols](./puppeteer.protocol.debugger.scriptparsedevent.debugsymbols.md) | [Debugger.DebugSymbols](./puppeteer.protocol.debugger.debugsymbols.md) | If the scriptLanguage is WebASsembly, the source of debug symbols for the module. |
|  [embedderName](./puppeteer.protocol.debugger.scriptparsedevent.embeddername.md) | string | The name the embedder supplied for this script. |
|  [endColumn](./puppeteer.protocol.debugger.scriptparsedevent.endcolumn.md) | [integer](./puppeteer.protocol.integer.md) | Length of the last line of the script. |
|  [endLine](./puppeteer.protocol.debugger.scriptparsedevent.endline.md) | [integer](./puppeteer.protocol.integer.md) | Last line of the script. |
|  [executionContextAuxData](./puppeteer.protocol.debugger.scriptparsedevent.executioncontextauxdata.md) | any | Embedder-specific auxiliary data. |
|  [executionContextId](./puppeteer.protocol.debugger.scriptparsedevent.executioncontextid.md) | [Runtime.ExecutionContextId](./puppeteer.protocol.runtime.executioncontextid.md) | Specifies script creation context. |
|  [hash](./puppeteer.protocol.debugger.scriptparsedevent.hash.md) | string | Content hash of the script. |
|  [hasSourceURL](./puppeteer.protocol.debugger.scriptparsedevent.hassourceurl.md) | boolean | True, if this script has sourceURL. |
|  [isLiveEdit](./puppeteer.protocol.debugger.scriptparsedevent.isliveedit.md) | boolean | True, if this script is generated as a result of the live edit operation. |
|  [isModule](./puppeteer.protocol.debugger.scriptparsedevent.ismodule.md) | boolean | True, if this script is ES6 module. |
|  [length](./puppeteer.protocol.debugger.scriptparsedevent.length.md) | [integer](./puppeteer.protocol.integer.md) | This script length. |
|  [scriptId](./puppeteer.protocol.debugger.scriptparsedevent.scriptid.md) | [Runtime.ScriptId](./puppeteer.protocol.runtime.scriptid.md) | Identifier of the script parsed. |
|  [scriptLanguage](./puppeteer.protocol.debugger.scriptparsedevent.scriptlanguage.md) | [Debugger.ScriptLanguage](./puppeteer.protocol.debugger.scriptlanguage.md) | The language of the script. |
|  [sourceMapURL](./puppeteer.protocol.debugger.scriptparsedevent.sourcemapurl.md) | string | URL of source map associated with script (if any). |
|  [stackTrace](./puppeteer.protocol.debugger.scriptparsedevent.stacktrace.md) | [Runtime.StackTrace](./puppeteer.protocol.runtime.stacktrace.md) | JavaScript top stack frame of where the script parsed event was triggered if available. |
|  [startColumn](./puppeteer.protocol.debugger.scriptparsedevent.startcolumn.md) | [integer](./puppeteer.protocol.integer.md) | Column offset of the script within the resource with given URL. |
|  [startLine](./puppeteer.protocol.debugger.scriptparsedevent.startline.md) | [integer](./puppeteer.protocol.integer.md) | Line offset of the script within the resource with given URL (for script tags). |
|  [url](./puppeteer.protocol.debugger.scriptparsedevent.url.md) | string | URL or name of the script parsed (if any). |

