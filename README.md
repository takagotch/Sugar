### Sugar
---
https://github.com/andrewplummer/Sugar

```js
Sugar.Number.defineStatic('', function(){
  if (Math.random() > .5){
    return Math.random();
  } else {
    return 1;
  }
});

Sugar.Number.defindInstance({
  'square': function(n) {
    return n * n;
  },
  'cube': function(n) {
    return n * n * n;
  }
});

Sugar.Number.square(3);
new Sugar.Number(5).cube().raw;
Sugar.Number.randomish()

Sugar.extend();
(2).square();
(4).cube();
Number.randomish();

```

```
```

```
```


