<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dunks</title>
    <link rel="stylesheet" href="Dee.css">
    <link href="https://fonts.googleapis.com/css2?family=Carattere&family=Gideon+Roman&display=swap" rel="stylesheet">
    <script src="Dee.js"></script>
    <style>
        
   html{
    background-color: black;
    width: 100%;
    height: 100%;
}

body{
    font-family: 'Gideon Roman', cursive;
    display: flex;
    background-repeat: no-repeat;
    background-image: linear-gradient(65deg,black,#010101   , lightgrey);
   padding-bottom: 100%;
  
}

.nav-link-wrapper {
    width: 150px;
    height: 250px;
    margin: 0px;
    padding: 0px;
    z-index: 3;
}

.nav-link {
    position: fixed;
    top: 0px; 
    text-align: left;
    z-index: 3;
    left: 0px;
  
}

ul {
    justify-content: center;
    position: fixed;
    list-style: none;
    margin: 0px;
    padding-top: 150px ;
    z-index: 3;

}

a {
    position: relative;
    color: white;
    font-size: 19px;
    text-decoration-line: none;
    padding: auto;;
}

a:hover {
    position:relative;
    background-color: black;
    color: black;
    border-radius: 45px;
    font-size: 25px;
    font-weight: bolder;
    background-image: linear-gradient(45deg, black, #8d5b63, transparent);
}

.nav-link:hover {
    position:fixed;
    color: black;
    background-color: black;
    font-weight: bolder;
    height: 100%;
    background-image: linear-gradient(45deg, black, #8d5b63, transparent);
}


/*suit container-*/

.image3{
    display:inline;
    position: fixed;
    background-repeat: no-repeat;
    right: 0px;
    z-index: 2;
    background-image: linear-gradient(180deg,black,maroon, grey);
}


/** Drawing analog clock**/ 


.sugar {
    position: absolute;
    align-items: center;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    min-width: 100%;
    padding-top: 5%;

}

.clock {
    position: relative;
    width: 150px;
    height: 150px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url(clock2.jpg);
    background-size: cover;
    border: transparent;
    background-repeat: no-repeat;
    border-radius: 50%;

}

.clock::before {
    content: '';
    margin-top: 2px;
    margin-left: 4px;
    position: absolute;
    width: 7px;
    height: 7px;
    background: #fff;
    border-radius: 50%;
    z-index: 1;

}
        
    </style>
    
    </head>
<body>
    
     <div class="container">
        
        <div class="image3">
            <div class="suit-contaner">
                <img src="/suit 3.jpg" alt="suit" srcset="">
            </div>
         </div>


        <div class="nav-link">

            <div class="nav-link-wrapper">
                <ul>
                    <li><a href="Duncan.html">Home</a></li> <br>

                    <li><a href="About.html">About</a></li> <br>

                    <li><a href="Contacts.html">Contacts</a></li> <br>

                    <li><a href="User.html">User</a></li> <br>

                    <li><a href="Search.html">Search</a></li> 
                </ul>

            </div>
        </div>


        <div class="sugar">
            <div class="clock">
                <div class="hour">
                    <div class="hr" id="hr"></div>
                </div>
        
                <div class="min">
                    <div class="mn" id="mn"></div>
                </div>
        
                <div class="sec">
                    <div class="sc" id="sc"></div>
                </div>
        
            </div>
        </div>

    </div>


</body> 
</html>
