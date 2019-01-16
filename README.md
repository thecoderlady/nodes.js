# nodes.js
nodes.js is a nodes/particles animation useable for backgrounds

Visit [project page](https://oguzhaneroglu.com/projects/nodes.js/) for example.

### Init

```html
<!-- <nodes.js embedding> -->
<script type="text/javascript" src="js/nodes.js"></script>
<script type="text/javascript">
    var nodesjs = new NodesJs({
        id: 'nodes',
        width: window.innerWidth,
        height: window.innerHeight,
        backgroundFrom: [10, 25, 100],
        backgroundTo: [25, 50, 150],
        backgroundDuration: 4000,
        number: window.hasOwnProperty('orientation') ? 30: 100,
        speed: 20
    });
</script>
<canvas id="nodes"></canvas>
<!-- </nodes.js embedding> -->
```

## License
MIT
