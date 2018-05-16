###纯css实现圆环六等分，每个等分做点击事件处理
```
-webkit-mask: radial-gradient(transparent, transparent 20px, #000 20px);
-moz-mask: radial-gradient(transparent, transparent 20px, #000 20px);
-ms-mask: radial-gradient(transparent, transparent 20px, #000 20px);
-o-mask: radial-gradient(transparent, transparent 20px, #000 20px);
mask: radial-gradient(transparent 20px, #000 20px);
```

```
clip: rect(0 51px 21px 27px);
```