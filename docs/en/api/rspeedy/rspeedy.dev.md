<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@lynx-js/rspeedy](./rspeedy.md) &gt; [Dev](./rspeedy.dev.md)

## Dev interface

The [Dev](./rspeedy.dev.md) option is used to control the behavior related with development. Including: HMR, DevServer, etc.

**Signature:**

```typescript
export interface Dev 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [assetPrefix?](./rspeedy.dev.assetprefix.md) |  | string \| boolean \| undefined | _(Optional)_ The [Dev.assetPrefix](./rspeedy.dev.assetprefix.md) is used to set the URL prefix for static assets during development. |
|  [client?](./rspeedy.dev.client.md) |  | [Client](./rspeedy.devclient.md) \| undefined | _(Optional)_ Configuration of the development client. |
|  [hmr?](./rspeedy.dev.hmr.md) |  | boolean \| undefined | _(Optional)_ Whether to enable Hot Module Replacement (HMR). |
|  [liveReload?](./rspeedy.dev.livereload.md) |  | boolean \| undefined | <p>_(Optional)_ Whether to enable live reload functionality.</p><p>Defaults to <code>true</code>.</p><p>Live reload is used as a fallback when [Dev.hmr](./rspeedy.dev.hmr.md) is disabled or cannot be used in certain scenarios. When enabled, the page will automatically refresh when source files are changed.</p><p>To completely disable both HMR and live reload, set both <code>dev.hmr</code> and <code>dev.liveReload</code> to <code>false</code>. Then, no WebSocket requests will be made to the dev server on the page, and the page will not automatically refresh when file changes.</p> |
|  [progressBar?](./rspeedy.dev.progressbar.md) |  | boolean \| { id?: string; } \| undefined | <p>_(Optional)_ Whether to display progress bar during compilation.</p><p>Defaults to <code>true</code>.</p> |
|  [watchFiles?](./rspeedy.dev.watchfiles.md) |  | WatchFiles \| WatchFiles\[\] \| undefined | _(Optional)_ Watch specified files and directories for changes. When a file change is detected, it can trigger a page reload or restart the dev server. |
|  [writeToDisk?](./rspeedy.dev.writetodisk.md) |  | boolean \| ((filename: string) =&gt; boolean) \| undefined | _(Optional)_ Used to control whether the build artifacts of the development environment are written to the disk. |

