

##### ddddd

`
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title></title>
    <style type="text/css">
        .rect {
            width: 400px;
            height: 50px;
            margin: 10px 0;
        }
        .c {
            border: 1px solid red;
        }
        .c1 { border: 1px solid green; }
        .c2 { border: 1px solid blue; }
    </style>
    <script>
        // 最终我要的只是一个函数

    </script>
    <script src="SelectorRickH.js"></script>
</head>
<body>
<div class="c3">
    <div class="c1 rect">
        <div class="c" style="border: 1px dashed green;">123</div>
    </div>
    <div class="c2 rect"></div>
    <div class="c rect"></div>
    <div class="c1 rect"></div>
</div>
<hr />
<p>我是一个段落</p>
<div>
    <div class="c rect"></div>
    <div class="c1 rect"></div>
</div>
<hr />
<div class="c3">
    <div class="c rect"></div>
</div>
</body>
<script type="text/javascript">
    var list = select( '.c3 .c, p' );
    for ( var i = 0; i < list.length; i++ ) {
        list[ i ].style.backgroundColor = 'green';
    }
</script>
</html>
`
