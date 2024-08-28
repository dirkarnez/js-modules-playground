[js-modules-playground](https://dirkarnez.github.io/js-modules-playground)
==========================================================================

### Tutorials
- [Module 的載入實現 · 阮一峰：ECMAScript 6 入門（OpenCC 繁體中文版）](https://yucj.gitbooks.io/ecmascript-6/content/docs/module-loader.html)
- [模块 (Module) 简介](https://zh.javascript.info/modules-intro)

### Notes
- `<script type="module">` is by default defer (aka non-blocking)
- Code inside `<script type="module">` has own scope. Multiple of them cannot communicate
- module as separate js file uses `import` `export`, and only works in HTTPS
- CommonJS modules exports copies. ESM exports reference
    - [Module 的載入實現 · 阮一峰：ECMAScript 6 入門（OpenCC 繁體中文版）](https://yucj.gitbooks.io/ecmascript-6/content/docs/module-loader.html)
- Lazy load is supported officially
