# Времена года в VR при помощи A-Frame

[A-Frame](https://aframe.io/) это фреймворк для легкого создания VR контента для браузера при помощи специального синтаксиса HTML от команды [Mozilla VR](http://mozvr.com/). Полученные VR-сцены можно смотреть просто в браузере на компьютере, на телефоне (в том числе в [Cardboard](https://www.google.com/get/cardboard/)-подобных гарнитурах) и в шлеме [Oculus Rift](https://www.oculus.com/en-us/rift/).
Чтобы попробовать в деле опишу процесс создания сцены с 4 сезонами.

## Старт
Чтобы создать минимальную сцену с одним кубиком в центре.
Для этого подключим js-файл фреймворка `https://aframe.io/releases/latest/aframe.min.js`, добавим в документ сцену, в которой будет происходить дальнейшее творчество: `<a-scene></a-scene>` и  поместим в сцену куб: `<a-cube></a-cube>`. Уже можно проверить результат в браузере. Поскольку мы не указали цвет куба, он будет серым.
```
<!doctype html>
<html>
  <head>
    <title>4 seasons in VR with A-Frame</title>
    <script src="https://aframe.io/releases/latest/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-cube></a-cube>
    </a-scene>
  </body>
</html>
```
