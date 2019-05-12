# dotcreate
---
Apply dot picture with javascript.

### DEMO
Pleas see "demo.html".

### Usage
``` html
    <!-- index.html -->
    <html>
    <head>
        ...
        <script src="main.js"></script>
    </head>
    <body>
        ...
        <canvas id="canvas" width="60" height="60"></canvas>
        ...
        <script>
        var createdot = new Dot();
        var width = 60;
        var height = 60;
        var content = [
            ["#ff0000","#00ff00","#0000ff","#ffff00","#ff00ff","#00ffff"],
            ["#00ff00","#0000ff","#ffff00","#ff00ff","#00ffff","#ff0000"],
            ["#0000ff","#ffff00","#ff00ff","#00ffff","#ff0000","#00ff00"],
            ["#ffff00","#ff00ff","#00ffff","#ff0000","#00ff00","#0000ff"],
            ["#ff00ff","#00ffff","#ff0000","#00ff00","#0000ff","#ffff00"],
            ["#00ffff","#ff0000","#00ff00","#0000ff","#ffff00","#ff00ff"]
        ];
        createdot.set(document.getElementById("canvas"), width, height, content);
        createdot.create();
        </script>
    </body>
    </html>
```

### Install
```
git clone https://github.com/Progwan/Createdot.git
```

### License
MIT
