# speedbump

Quick project to speedbump URLs I click on through other apps, so that they don't automatically open. I used this [OpenIn script](https://loshadki.app/openin4/080-javascript-for-rule) to do so:

```js
ctx.url.href =
  "https://speedbump.mikeylab.com/?url=" + encodeURIComponent(ctx.url.href);
```
