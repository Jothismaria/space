# space
body {
    margin:0;
    padding:0;
    background-color:#00002a;
    }
.shuttle{
    position:absolute ;
    top:265px;
    left:5px;
    animation:getdown 5s linear;
    z-index:100;
}
@keyframes getdown{
    0%{
        transform:translate(0,-100px);
    }
}

.stand-left{
    position:absolute ;
    top:96px;
    left:145px;
    width:3px;
    height:20px;
    background-color:#fefcf6;
    transform:rotate(30deg);
}
.stand-right{
    position:absolute ;
    top:96px;
    left:185px;
    width:3px;
    height:20px;
    background-color:#fefcf6;
    transform:rotate(-30deg);
}
.shuttle-box{
    position:absolute ;
    top:80px;
    left:141px;
    width:50px;
    height:20px;
    background-color:#F3B431;
    border-radius:5px 5px 0 0;
    z-index:100;
}
.shuttle-box-up{
    position:absolute ;
    top:60px;
    left:150px;
    width:30px;
    height:30px;
    background-color:#F3CC79;
    border-radius:10px 10px 0 0;
}
.satellite{
    position:absolute ;
    top:30px;
    left:160px;
    width: 10px; 
    height: 20px;
    border-bottom-left-radius: 20px;
    border-top-left-radius:20px;
    background: #586776; 
    transform:rotate(-38deg);
    z-index:-100;
    animation:display 6s,up 11s linear;
    } 
    
@keyframes up{
    0%{
        transform:translate(0,50px);
    }
}

.antenna{
    position:absolute ;
    top:8px;
    left:11px;
    border-top: 2px solid transparent; 
    border-bottom:2px solid transparent;
    border-left: 20px solid #2F363F;
    
}
.stick{
    position:absolute ;
    top:8px;
    left:-2px;
    width:2px;
    height:20px;
    background-color:#586776;
    transform:rotate(38deg);
}
.circle{
    position:absolute ;
    top:8px;
    left:30px;
    width:5px;
    height:5px;
    border-radius:50%;
    transform:rotate(-38deg);
    background-color:#E83350;
}
.solar{
    position:absolute ;
    top:80px;
    left:120px;
    animation:display 6.5s linear;
  
}
@keyframes display{
    0%{
        opacity:0
    }
    98%{
        opacity:0;
    }
    100%{
        opacity:1;
    }
}
.plate-left{
    position:absolute ;
    left:-12px;
    width:20px;
    height:10px;
    border:2px solid #F5C469;
      animation:turn 3s infinite;
}
.plate-right{
    position:absolute ;
    left:80px;
    width:20px;
    height:10px;
    border:2px solid #F5C469;
      animation:turn 3s infinite;
}
.s-stick{
    position:absolute ;
    top:5px;
    left:10px;
    width:70px;
    background-color:#F5C469;
    height:2px;
     animation:turn 3s infinite; 
}
@keyframes turn{
    0%{
        transform:rotateX(-360deg);
    }
    100%{
        transform:rotateX(360deg);
    }
}
.signal{
    position:absolute ;
    top:270px;
    left:198px;
    width:10px;
    height:10px;
    border-radius:50%;
    border:0.5px solid #DAE0E2;
    animation:signals 1s infinite ;
    animation-delay:11s;
    opacity:0;
}
@keyframes signals{
    0%{
        border:0.2px solid #fefcf6;
        opacity:1;
    }
    100%{
        transform:scale(18);
        opacity:0;
        color:#DAE0E2;
        
    }
}
.surface{
    position:absolute ;
    top:100px;
    left:0;
}
.land{
    position:absolute ;
    top:270px;
    width:360px;
    height:110px;
    background-color:#333945;
    border-top:40px solid #586776;
    z-index:10;
}
.rock-1{
    position:absolute;
    top:200px;
    left:0px;
    width:140px;
    height:70px;
    border-top-left-radius:140px;
    border-top-right-radius:140px;
    background-color:#47535e;
    z-index:-10;
    box-shadow:220px 0px #535C68;
}
.rock-2{
    position:absolute;
    top:230px;
    left:60px;
    width:100px;
    height:50px;
    border-top-left-radius:100px;
    border-top-right-radius:100px;
    background-color:#47535e;
    z-index:10;
    box-shadow:120px 0px #535C68,
               10px -5px 10px #00002a,
               110px -5px 10px #00002a;
}
.rock-3{
    position:absolute;
    top:275px;
    left:140px;
    width:20px;
    height:10px;
    border-top-left-radius:20px;
    border-top-right-radius:20px;
    background-color:#777E8B;
    z-index:100;
    box-shadow:40px 0px #47535E;
}
.hover-up{
    position:absolute ;
    top:-100px;
    left:0px;
    width:360px;
    height:120px;
    background:linear-gradient(135deg,#E5B143, #fefcf6,#218F76);
    border-radius:0 0 5px 5px;
    text-align:center;
    font-size:20px;
    font-family:courier new;
    color:#192A56;
    transition:.5s;
}
.hover-up:hover{
    position:absolute ;
    top:0px; 
}
a{
    position:absolute ;
    text-decoration:none;
    font-size:20px;
    top:100px;
    left:120px;
    color:#00002a;
}
.image-1{
    position:absolute ;
    top:340px;
    left:30px;
    width:60px;
    height:auto;
    animation:alien 2.5s infinite;
    animation-delay:11s;
}
.image-2{
    position:absolute ;
    top:340px;
    left:235px;
    width:50px;
    height:auto;
    animation:alien 2.5s infinite ;
    animation-delay:10s ;
}
@keyframes alien{
    50%{
        transform:translate(0, -50px);
    }
}

