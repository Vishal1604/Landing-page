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
       
        background-color: rgb(224, 221, 221);
    }
    
    .circle2{
        position: relative;
  height:1000px;
  width: 1000px;
  border-radius: 1000px;
   background-color: rgb(253, 174, 174);
  opacity: 0.8;
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
   background-color: rgb(253, 174, 174);
  opacity: 0.8;
  float: right;
  margin-right: -600px;
  margin-top: -120px;
  z-index: -1;

}
.flexbox{
    overflow: hidden;
    box-shadow: 0px 2px 10px rgba(133, 132, 132, 0.918);
    height: 750px;
    border: 2px solid rgba(200,200,200,0.2);
    width: 60%;
    margin: auto;
    background: rgba(200,200,200,0.2);
   
   
}
.login{
    display: flex;
    position: absolute;
    width: 400px;
    height: 500px;
    flex-direction: column;
    border: 0.5px solid rgba(200, 200, 200, 0.2) ;
    background-color: rgba(240, 255, 255, 0.603);
    margin-left: 250px;
   align-items: center;
    margin-top: 130px;
    
}


h3{
    margin-top: 50px;
    text-align: center;
    font-size: 40px;
}
input{
    margin-top: 20px;
    height: 30px;
    width: 300px;
    text-align: center;
    border: 1px solid black;
    border-left: none;
    
}
.nm{
    background-color: rgb(252, 71, 164);
    margin-top: 40px;
    height: 35px;
    width: 300px;
    font-size: 15px;
    font-weight: bold;
   border: none;
   border-radius: 2px;
    color: white;   
}
a{
    text-decoration: none;
    color: blue;
}
p{
    color: green;
}
.iframe1{
    background: rgba(200,200,200,0.2);
    
   margin-left: -300px;
    display: flex;
    position:relative;
    flex-direction: column;
    height: 750px;
    width: 300px;
    float: right;
  overflow-y: hidden;
align-items: center;
    
}

.iframe2{
    background: rgba(200,200,200,0.2);
    
    display: flex;
    position:absolute;
   overflow-y: hidden;
    height: 750px;
    width: 300px;
}

.slide-track{
display: flex;
position: absolute;
flex-direction: column;
overflow-y: auto;
align-items: center;
height: calc(200px*18);
animation: scrollUp 200s  linear infinite normal;



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
    width: 200px;
    display: flex;
    align-items: center;
    padding: 15px;
    background: rgba(86, 85, 85, 0.073);
    margin-top: 10px;
    margin-left: 25px;
    box-shadow: 2px 2px 2px rgba(74, 74, 74, 0.892);
    
}
.mm{
    padding: 8px;
    margin-right: -5px;
    border: 1px solid black;
    border-right: none;
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
        <div class="login">
            <h3>Sign in</h3>
            <br>
            <div class="email">
               <button class="mm"> <i class="fa-solid fa-envelope" ></i></button>
                <input type="email" name="email" placeholder="Enter Your Email">
            </div><br>
            <div class="pass">
                <button class="mm"><i class="fa-solid fa-lock"></i></button>
                <input type="password" name="password" placeholder="Enter Your Password">
            </div>
            <button class="nm">Log in</button><br><br>
           <p>Don't have account?<a href="">sign up</a></p>
            


        </div>
       
    


   
    </div>
</body>
</html>
