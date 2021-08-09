<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hackerr</title>
    <style>
        body{
            display: flex;
           justify-content: center;
           align-items: center;
        }
        body::before{
            content: "";
            position: absolute;
            background-image: url('https://images.pexels.com/photos/5380590/pexels-photo-5380590.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
            background-repeat: no-repeat;
            background-size: cover;
            z-index: -1;
            width: 100%;
            height: 142%;
            opacity:1;
        }
        
        .list{
            display: inline-block;
        
          padding:20px;
        }
        .l{
            color: white;
        
           display:inline-block;   
        }
    
        a{
            font-size: 21px;
            text-decoration: none;
            color:rgb(211, 233, 227)
        }
        a:hover{
            color:rgb(10, 15, 20);
            
            background-color: rgb(131,140,150);
        }
        .btn{
            background-color: black;
            color:white;
            margin:6px;
            cursor: pointer;
        }
        .f{
            border: rgb(165, 165, 159) 2px solid;
            border-radius: 23%;
            width: 182px;
            height: 115px;
           padding: 85px;
          margin-top: 284px;
           margin-left: 835px;

        }
        .e{
            border:rgb(131,140,150) 2px solid;
        text-align: center;
        width:200px;
        }
        .s{
            display:block;
            border:white 2px solid;
            background-color: rgb(37, 35, 35);
            color:white;
            margin: auto;
        }
        .s:hover{
            color:blue;
        }
      
    </style>
</head>
<body>
    
    
    <div class="f">
        <form>
            <div><input type="text" placeholder="Enter Name" class="e"></div><br>
            <div ><input type="text" placeholder="Enter Number" class="e"></div><br>
            <div ><input type="text" placeholder="Enter Email" class="e"></div><br>
            <div ><a href="http://127.0.0.1:5500/hacker2.html"class="e">Submit</a></div>
        </form>
        
    </div>
    
</body>
</html>
