<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body id="parent">
  <h1 >hello</h1>
  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Veritatis, tenetur rem voluptatibus delectus voluptas ad illo beatae, modi officia fugiat aliquid veniam molestiae. Illum, recusandae placeat accusamus eveniet veniam laudantium?</p>
  <button onclick="dark()">dark mood</button>
  <button onclick="light()">Light mood</button>
  <script>
   function dark(){
    document.getElementById("parent").style.backgroundColor="black"
    document.getElementById("parent").style.color="White"
   }
   function light(){
    document.getElementById("parent").style.backgroundColor="lightblue"
    document.getElementById("parent").style.color="black"
   }
  </script>
</body>
</html>
