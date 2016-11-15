# fireworks
A beautiful fireworks by canvas.

[demo](https://songjinzhong.github.io/fireworks/).

## how to use?

**Browser**

Download the `fireworks.js` script and use it `<script src="fireworks.js"></script>`.

Example like this:

```
<div class="demo"></div>

<script type="text/javascript">
  var demo = document.getElementsByClassName("demo")[0];
  demo.fireworks({ 
    opacity: 0.6, // opactiy for fireworks
    width: '80%', // width for canvas
    height: '100%', // height for canvas
    interval: 2000, // interval for firework
    speed: 40 // speed for firework
  });
</script>
```

**And there has some problems with other Explores but Chrome.**