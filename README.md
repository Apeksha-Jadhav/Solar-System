<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solar System</title>
</head>
<style>
   


   html, body {
    width: 90%;
    height: 90%;
    }

.body {
    position: absolute;
    
}

#sun {
    top: 50%;
    left: 50%;
    
    
    border-width: 3px;
    border-style: solid;
    border-radius: 100%;
    box-shadow: 0 0 100px red;
    
    
    height: 70px;
    width: 70px;
    margin-top: -40.5px; 
    margin-left: -45.5px;
}

#earth {
    top: 0%;
    left: 50%;
    
    border-radius:100%;
    height: 37.5px;
    width: 37.5px;
    margin-top: -18.75px;
    margin-left: -18.75px;
    box-shadow: 0 0 100px blue;
}

#earth-orbit {
    top: 50%;
    left: 50%;

    width: 500px;
    height: 500px;
    margin-left: -250px;
    margin-top: -250px;
   
    
    -webkit-animation: spin-right 10s linear infinite;
    -moz-animation: spin-right 10s linear infinite;
    animation: spin-right 10s linear infinite;
}

#moon {
    border-radius:100%;
    height: 12px;
    width: 12px;
    margin-top: -5px;
    margin-left: -5px;
    
    box-shadow: 0 0 100px white;
}

#moon-orbit {
    top: 0%;
    left: 50%;

    width: 40px;
    height: 40px;
    margin-top: -20px;
    margin-left: -20px;

    
    -webkit-animation: spin-right 4s linear infinite;
    -moz-animation: spin-right 4s linear infinite;
    animation: spin-right 4s linear infinite;
  }
  
#mercury {
    top: 0%;
    left: 50%;
    
    
    border-radius:100%;
    height: 21px;
    width: 21px;
    margin-top: -11.25px;
    margin-left: -11.25px;
    box-shadow: 0 0 10px red;
}

#mercury-orbit {
    top: 50%;
    left: 50%;

    width: 200px;
    height: 200px;
    margin-top: -100px;
    margin-left: -100px;

    -webkit-animation: spin-right 3.5s linear infinite;
    -moz-animation: spin-right 3.5s linear infinite;
    animation: spin-right 3.5s linear infinite;
  }

#venus {
    top: 0%;
    left: 50%;
    
    border-radius:100%;
    height: 35px;
    width: 35px;
    margin-top: -18.75px;
    margin-left: -18.75px;
    background-color: red;
    box-shadow: 0 0 10px red;
    
    }

#venus-orbit {
    top: 50%;
    left: 50%;

    width: 350px;
    height: 350px;
    margin-left: -175px;
    margin-top: -175px;
    
    -webkit-animation: spin-right 7s linear infinite;
    -moz-animation: spin-right 7s linear infinite;
    animation: spin-right 7s linear infinite;
}

#mars {
    
    top: 0%;
    left: 50%;
    
    border-radius:100%;
    height: 26.25px;
    width: 26.25px;
    margin-top: -13.13px;
    margin-left: -13.13px;
    
    box-shadow: 0 0 100px green;
}

#mars-orbit {
    top: 50%;
    left: 50%;

    width: 750px;
    height: 750px;
    margin-left: -375px;
    margin-top: -375px;
   
-webkit-animation: spin-right 14s linear infinite;
    -moz-animation: spin-right 14s linear infinite;
    animation: spin-right 14s linear infinite;
}

#jupiter {
    top: 0%;
    left: 50%;
    
    border-radius:100%;
    height: 70px;
    width: 70px;
    margin-top: -35px;
    margin-left: -35px;
    
}

#jupiter-orbit {
    top: 50%;
    left: 50%;

    width: 1200px;
    height: 1200px;
    margin-left: -600px;
    margin-top: -600px;
   
    
    -webkit-animation: spin-right 18s linear infinite;
    -moz-animation: spin-right 18s linear infinite;
    animation: spin-right 18s linear infinite;
}

#saturn {
    top: 0%;
    left: 50%;
    
    border-radius:100%;
    height: 65px;
    width: 65px;
    margin-top: -32.5px;
    margin-left: -32.5px;
    box-shadow: 0 0 100px black;
}

#saturn-orbit {
    top: 50%;
    left: 50%;

    width: 1400px;
    height: 1400px;
    margin-left: -700px;
    margin-top: -700px;
   
    
    -webkit-animation: spin-right 20s linear infinite;
    -moz-animation: spin-right 20s linear infinite;
    animation: spin-right 20s linear infinite;
}

#uranus {
    top: 0%;
    left: 50%;

    border-radius:100%;    
    height: 50px;
    width: 50px;
    margin-top: -25px;
    margin-left: -25px;
    box-shadow: 0 0 50px white;
}

#uranus-orbit {
    top: 50%;
    left: 50%;
    
    width: 1600px;
    height: 1600px;
    margin-left: -800px;
    margin-top: -800px;
   
    
    -webkit-animation: spin-right 22s linear infinite;
    -moz-animation: spin-right 22s linear infinite;
    animation: spin-right 22s linear infinite;
}

#neptune {
    top: 0%;
    left: 50%;
    
    border-radius:100%;
    height: 45px;
    width: 45px;
    margin-top: -22.5px;
    margin-left: -22.5px;
}

#neptune-orbit {
    top: 50%;
    left: 50%;

    width: 1800px;
    height: 1800px;
    margin-left: -900px;
    margin-top: -900px;
   
    
    -webkit-animation: spin-right 27s linear infinite;
    -moz-animation: spin-right 27s linear infinite;
    animation: spin-right 27s linear infinite;
}


@-webkit-keyframes spin-right {
  100% {
      -webkit-transform: rotate(360deg);
  }
}

@-moz-keyframes spin-right {
    100% {
        -webkit-transform: rotate(360deg);
    }
}
</style>
<body>
    <body background="sky">
        
        <img class ="body" id="sun" src="sun">
        
        <div class ="body" id="mercury-orbit">
            <img class ="body" id="mercury" src="mercury">
        </div>
        
        <div class ="body" id="venus-orbit">
            <img class ="body" id="venus" src="ura">
        </div>
        
        <div class ="body" id="earth-orbit">        
            <img class ="body" id="earth" src="earth">
        
            <div class ="body" id="moon-orbit">
                <img class ="body" id="moon" src="mercury">
            </div>
        </div>
        
         <div class ="body" id="mars-orbit">
            <img class ="body" id="mars" src="mars">
        </div>
        
        <div class ="body" id="jupiter-orbit">
            <img class ="body" id="jupiter" src="jupiter">
        </div>
        
        <div class ="body" id="saturn-orbit">
            <img class ="body" id="saturn" src="sat.jpg">
        </div>
        
        <div class ="body" id="uranus-orbit">
            <img class ="body" id="uranus" src="ura">
        </div>
        
        <div class ="body" id="neptune-orbit">
            <img class ="body" id="neptune" src="mars">
        </div>
    </body>
</html>  
</body>
</html>
