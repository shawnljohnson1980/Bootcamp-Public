<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <title>Document</title>
</head>
<body>

    <!-- NavBar -->
    <nav style="justify-content: center;"
    class="navbar navbar-expand-lg navbar-light bg-info">
        <h1 class="navbar-brand text-warning " >Do You Qualify? </h1> 
      </nav>
    <!-- End NavBar -->
    <div>
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
        </button>
      </div>
    
    <!-- Form -->
    <div style="justify-content: center; align-content: center; display: grid;" class="container mt-5">
    <p>
        Age
        <br>
        <input type="number" id="age" min="1" required="true">
        <h6 style="display: none; color:rgb(81, 255, 0)" id="success" sucess> Get on that Ride kiddo!</h6>
        <h6 style="display: none; color:rgb(209, 10, 10)" id="error" error>Sorry kiddo, maybe next year.</h6>
    </p>
    <p>
        Height
        <br>
        <input type="number" id="height" min="1" required="true">
        <h6 style="display: none; color:rgb(10, 209, 10)" id="success">Get on that ride kiddo! </h6>
        <h6 style="display: none; color:rgb(209, 10, 10)" id="error"> Sorry kiddo, maybe next year.</h6>
    </p>
    

    <button onclick="doThis()"> Can you ride?</button>  
</div>
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
    <script src="./Johnson_Shawn_JS_Createvariables.js"></script>
</body>
</html>
