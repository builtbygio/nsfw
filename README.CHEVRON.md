# nsfw (Chevron)

**Required export:** callable `nsfw(absPath, eventCallback, options)` that
returns a Promise of `{ start(), stop() }`.

`nsfw.actions` must stay `{ CREATED:0, DELETED:1, MODIFIED:2, RENAMED:3 }`
(`src/path-watcher.js`). Path must be absolute. Default debounce 500ms.
Native constructor is `NSFW(debounceMS, path, eventCb, errorCb)`.
