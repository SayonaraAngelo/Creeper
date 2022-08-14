# Creeper
Esse exercicio foi proposto para fazermos uma replica do Creeper do jogo Minecraft - Usando Html e Javascript
![image](https://user-images.githubusercontent.com/104407938/184545070-d0c536b1-f4da-43ae-8da0-b58e5bbc3d9d.png)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>creepe</title>
</head>
<body>
    <canvas width="600" height="400"></canvas>

    <script>
    var tela = document.querySelector('canvas');
    var pincel = tela.getContext('2d');

    pincel.fillStyle = 'lightgrey';
    pincel.fillRect(0, 0, 600, 400);

    pincel.fillStyle = 'darkgreen'
    pincel.fillRect(125, 50, 350, 300,)
    
    
    pincel.fillStyle = 'black'
    pincel.fillRect (175, 100, 90, 90)
    pincel.fillRect (335, 100, 90, 90)

    
    pincel.fillRect (265, 190, 70, 100)

    
    pincel.fillRect (225, 240, 40, 110)
    pincel.fillRect (335, 240, 40, 110)



    
    
    


</script>

</body>
</html>
