<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Piano Digital</title>
    <style>
        #piano {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 50px;
        }
        .tecla {
            border: 1.2px solid black;
            height: 200px;
            cursor: pointer;
            user-select: none;
            position: relative;
        }
        .blanca {
            background-color: white;
            width: 80px;
            margin: 0 1px;
            border-bottom-left-radius: 5px;
            border-bottom-right-radius: 5px;
        }
        .negra {
            background-color: black;
            width: 50px;
            margin-left: -20px;
            margin-right: -20px;
            z-index: 1;
            height: 120px;
        }
    </style>
</head>
<body>

<div id="piano">
    <div class="tecla blanca" id="C"></div>
    <div class="tecla negra" id="Cs"></div>
    <div class="tecla blanca" id="D"></div>
    <div class="tecla negra" id="Ds"></div>
    <div class="tecla blanca" id="E"></div>
    <div class="tecla blanca" id="F"></div>
    <div class="tecla negra" id="Fs"></div>
    <div class="tecla blanca" id="G"></div>
    <div class="tecla negra" id="Gs"></div>
    <div class="tecla blanca" id="A"></div>
    <div class="tecla negra" id="As"></div>
    <div class="tecla blanca" id="B"></div>
</div>

</body>
</html>
