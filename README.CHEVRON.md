# @atom/nsfw (Chevron fork)

Fork of the Atom-era native at `nsfw` version `1.0.28`.

Folded Electron 43 / V8 15 compile fixes that used to live in `script/lib/patch-*.js`:

- `NODE_MODULE` → `NODE_MODULE_CONTEXT_AWARE`
- V8 15 API removals (`GetIsolate`, `String::Write`, `WriteUtf8` capacity)
- `nan@2.28.0`
- oniguruma GCC 14 `gnu89` / spellchecker MSVC wstring bind, where applicable
