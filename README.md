<!-- # dom
DATE AND TIME CALL BY GET ELEMENT -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="demo"></p>
    <script>
         var d= new Date();
         day= d.getDay(); 
        
         if(day=5){
           document.getElementById("demo").innerHTML= "weekend";
         }
        else{
            document.getElementById("demo").innerHTML= "weekdays";
        }
       
    </script>
</body>
</html>
