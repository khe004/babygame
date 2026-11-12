# Hanzi Writer

`hanzi.html` 用它画笔顺动画和让孩子跟着写。

- `hanzi-writer.min.js`：[Hanzi Writer](https://github.com/chanind/hanzi-writer) 3.7.3，MIT 许可（`LICENSE`）。
- `strokes.js`：页面用到的汉字的笔画数据，取自 `hanzi-writer-data` 2.0.1（来自 [Make Me a Hanzi](https://github.com/skishore/makemeahanzi)），Arphic Public License（`ARPHICPL.TXT`）。

加新字时，从 npm 包 `hanzi-writer-data` 里拿 `<字>.json`，加进 `strokes.js` 的 `HANZI_STROKES`。
