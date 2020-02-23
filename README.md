# education
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
<script>
    let globalDiv = document.createElement('div');
    globalDiv.style = "background: rgba(205, 214, 219, 0.9); width: 300px; height: 60px;";
    document.body.append(globalDiv);
    globalDiv.id="external";

    
    let myButton1 = document.createElement('button');
    // myButto1.innerText = 'FB';
    globalDiv.prepend(myButton1);
    myButton1.id="first";
    myButton1.style ="background: #1DBD8A; width: 100px; height: 60px;"

    let myButton2 = document.createElement('button');
    myButton2.innerText= 'SB';
    globalDiv.append(myButton2);
    myButton2.id="second";
    myButton2.style ="background: #1DBD8A; width: 100px; height: 60px;";

    let myButton3 = document.createElement('button');
    myButton3.innerText= 'TB';
    globalDiv.append(myButton3);
    myButton3.id="third";
    myButton3.style ="background: #1DBD8A; width: 100px; height: 60px;";
            

    
</script>
