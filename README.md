<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> login page</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<style>
    body{
        margin: 0%;
        padding: 0%;
      overflow: hidden;
      background-image: linear-gradient(-20deg, #e9defa 0%, #fbfcdb 100%);
    }
    
    .circle2{
        position: relative;
  height:1000px;
  width: 1000px;
  border-radius: 1000px;
  box-shadow: 0px 2px 8px rgba(133, 132, 132, 0.918);
  background-image: linear-gradient(to right, #ffecd2 0%, #fcb69f 100%);
  opacity: 0.6;
  float: left;
  margin-left: -600px;
  margin-top: -120px;
  z-index: -1;
    }
.circle{
   position: relative;
  height:1000px;
  width: 1000px;
  border-radius: 1000px;
  box-shadow: 0px 2px 8px rgba(133, 132, 132, 0.918);
  background-image: linear-gradient(to left, #ffecd2 0%, #fcb69f 100%);
  opacity: 0.6;
  float: right;
  margin-right: -600px;
  margin-top: -120px;
  z-index: -1;

}
.flexbox{
    overflow: hidden;
    box-shadow: 0px 2px 10px rgba(133, 132, 132, 0.918);
    height: 750px;
    border: 1px solid rgba(200,200,200,0.2);
    width: 65%;
    margin: auto;
   
    background: rgba(200,200,200,0.2);
   
   
}
#login{
    
    position: absolute;
    width: 400px;
    height: 500px;
  text-align: center;
    border: 0.5px solid rgba(200, 200, 200, 0.2) ;
    background-color: rgba(240, 255, 255, 0.711);
    margin-left: 300px;
   
    margin-top: 130px;
    z-index: 1;
    display: none;
    
}


h3{
    margin-top: 40px;
    text-align: center;
    font-size: 40px;
}
input{
    position: relative;
    margin-top: 20px;
    height: 30px;
    width: 270px;
   z-index: 2;
    border: 1px solid black;
    padding-left: 25px;
    margin-left: 15px;
    font-size: 15px;
   
    
}
i{
    position: relative;
    z-index: 3;
    margin-right: -40px;
    
   
}
.nm{
    background-color: rgb(252, 71, 164);
    margin-top: 40px;
    height: 35px;
    width: 298px;
    font-size: 15px;
    font-weight: bold;
   border: none;
   border-radius: 2px;
    color: white; 
    margin-right: 8px;  
}
.nm:hover{
background-color: rgb(255, 147, 165);
}
a{
    text-decoration: none;
    color: blue;
}
a:hover{
    text-decoration: underline;
}
p{
    color: green;
    font-size: 20px;
}
#bb{
    font-size: 16px;
    color: black;
}

.iframe1{
    background: rgba(200,200,200,0.2);
   margin-left: -260px;
    display: flex;
    position:relative;
    height: 750px;
    width: 260px;
    float: right;
  overflow-y: hidden;
text-align: center;
z-index: -1;
    
}

.iframe2{
    background: rgba(200,200,200,0.2);
    
    display: flex;
    position:absolute;
   overflow-y: hidden;
    height: 750px;
    width: 260px;
    z-index: -1;
}

.slide-track{
display: flex;
position: absolute;
flex-direction: column;
overflow-y: auto;
align-items: center;
height: calc(200px*18);
animation: scrollUp 200s  linear infinite normal;
z-index: 1;



}
.slide-track::-webkit-scrollbar{
    height: 0;
}
@keyframes scrollUp{
    0%{
        transform: translateY(0);
    }
    100%{
        transform: translateY(calc(-200px*18));
    }
}
.item{
    height: 200px;
    width: 230px;
    display: flex;
    align-items: center;
    padding: 15px;
    background-image: linear-gradient(-225deg, #E3FDF5 0%, #FFE6FA 100%);
    margin-top: 15px;
    box-shadow: 2px 2px 2px rgba(74, 74, 74, 0.892);
    
}

#account{
    position: absolute;
    width: 400px;
    height: 500px;
  text-align: center;
    border: 0.5px solid rgba(200, 200, 200, 0.2) ;
    background-color: rgba(240, 255, 255, 0.711);
    margin-left: 300px;
    margin-top: 130px;
    z-index: 2;
   

}


</style>
</head>
<body>
   

       
    <span class="iframe2">
        <div class="slide-track">

           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           

        </div>

    </span>
    <span class="iframe1">
        <div class="slide-track">
            <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           <iframe src="" frameborder="0" class="item"></iframe>
           
           

        </div>

    </span>
   
    <div class="flexbox">
        <dic class="circle2">

        </dic>
        <div class="circle">
    
        </div>
        <div id="login">
            <h3>Sign in</h3>
            <br>
            <div class="email">
                <i class="fa-solid fa-envelope" ></i>
                <input type="email" name="email" placeholder="Enter Your Email">
            </div>
            <div class="pass">
                <i class="fa-solid fa-lock"></i>
                <input type="password" name="password" placeholder="Enter Your Password" id="my input2">
            </div>
            <button class="nm">Log in</button>
            <p id="bb">OR</p>
           <p>Don't have account?<a href="##" id="kk" onclick="hh()">Sign Up</a></p>
            


        </div>
        <div id="account">
            <h3>Sign Up</h3>
            <div class="name">
                <i class="fa-solid fa-user"></i> 
                <input type="name" name="name" placeholder="Enter Your Name">
            </div>
            <div class="email">
                <i class="fa-solid fa-envelope" ></i>
                <input type="email" name="email" placeholder="Enter Your Email">
            </div>
            <div class="pass">
                <i class="fa-solid fa-lock"></i>
                <input type="password" name="password" placeholder="Enter Your Password" id="my input1">
               
            </div>
            <button class="nm">Apply Now</button>
            <p id="bb">OR</p>
           <p>Already have an account?<a href="##" id="ll" onclick="tooglehide()">Log In</a></p>
            


        </div>
    </div>
    <script>
        function tooglehide(){
            var ll=document.getElementById('ll');
            var account=document.getElementById('account');
            var login=document.getElementById('login');
            if(account.style.display='block'){
                account.style.display='none';
                login.style.display='block';
            }
        }
        function hh(){
        var kk=document.getElementById('kk');
        var account=document.getElementById('account');
        var login=document.getElementById('login');
        if(login.style.display='block'){
            login.style.display='none';
            account.style.display='block';
        }
    }
    </script>
</body>
</html>
