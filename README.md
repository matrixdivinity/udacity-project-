# udacity-project-
html for a udacity project
<head>
    <title>Pixel Art Maker!</title>
    <link href="https://fonts.googleapis.com/css?family=Cabin+Sketch" rel="stylesheet">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
</head>
<body>
  <div class = "grid">
    <h1>Pixel Art Maker</h1>

    <h2>Choose Grid Size</h2>
    <form id="sizePicker">
        Grid Height:
        <input type="number" id="input_height" name="height" min="1" value="1">
        Grid Width:
        <input type="number" id="input_width" name="width" min="1" value="1">
        <input type="submit">
    </form>

    <h2>Pick A Color</h2>
    <input type="color" id="colorPicker">
    
    <h2>Design Canvas</h2>
    <button>Clear Grid</button>
    <table id="pixel_canvas"></table>

    <script src="design.js"></script>
</body>
