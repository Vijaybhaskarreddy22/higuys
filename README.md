
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram clone </title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <link rel="stylesheet" href="instagramclone2.css">
    <script>
        function myfun(){
    var dark = document.getElementById("clicked");
    var white = document.getElementById("white-color");
    var lol = document.getElementById("white-2color");
    dark.onclick = function ()
    {
    document.body.classList.toggle("dark-mode");
    if(document.body.classList.contains("dark-mode")){
        white.style.filter = "brightness(5)";
        lol.style.filter = "brightness(5)";
    }
    else{
        white.style.filter = "none";
        lol.style.filter = "none";
    }
    }
}
</script>
    <style>
      /* font-family: 'Archivo', sans-serif;
font-family: 'Inconsolata', monospace;
font-family: 'Merriweather', serif;
font-family: 'Poppins', sans-serif;
font-family: 'Roboto', sans-serif;
font-family: 'Signika', sans-serif; */
:root{
    --background-color:rgb(252, 251, 251);
    --font-color:rgb(0, 0, 0);
    --secod-font-color:rgb(101, 101, 101);
    --secondary-font-color : rgb(179, 179, 179);
    --background-on-hover:rgb(215, 214, 214);
}
.dark-mode{
    --background-color:rgb(15, 15, 15);
    --font-color:rgb(254, 252, 252);
    --secod-font-color:rgb(197, 195, 195);
    --secondary-font-color : rgb(108, 106, 106);
    --background-on-hover:rgba(52, 51, 51, 0.834);
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    
}
p{
  font-family: 'Roboto', sans-serif; 
}
.container{
    display: flex;
    /* gap: 10px; */
   /* overflow-x: hidden; */
}
.middle-section{
    display: flex;
    justify-content: space-evenly;
    /* width: 100%; */
}
a{
    text-decoration: none;
    color: var(--font-color);
    font-family: 'Signika', sans-serif;
    font-size: 0.9rem;
    font-weight: 550;
}
body{
    background-color: var(--background-color);
    overflow-x: hidden;
    /* border: 1px solid red; */
    min-height: 100vh;
    width: 100vw;
    overflow-x: hidden;
}
/* styling navbar section  */
.navbar{
    display: flex;
    flex-direction: column;
    gap: 10px;
    height: 100vh;  
    width: 245px;
    /* justify-content: space-between; */
    background-color: var(--background-color);
    padding-top: 20px;
    padding-bottom: 10px;
    padding-inline:  10px;
    border-right: 0.1px solid rgba(76, 75, 75, 0.737);
    position: sticky; 
    top: 0px;
   
   
}
@media (max-width:750px) {
    .container .navbar{
        flex-direction: row;
        background-color: var(--background-color);
        position: fixed;
        z-index: 1000;
        height: 60px;
        bottom: -1px;
        top: auto;
        gap: 0;
        border-right:none;
        width: 100vw;
        justify-content: space-around;
        align-items: center;
        padding: 0;
        box-shadow: -1px 14px 20px 4px black;
    }
    .middle-section .post-section{
        padding: 40px 5px;
    }
    .navbar a{
        display: none;
    }
    .navbar .sub-section{
        padding: 10px 10px;
    } 
   
    #hidden{
        display: none;
    }
    #hidden1{
        display: none;
    }
    #hidden2{
        display: none;
    }
  .instagram-text-logo{
        display: none;
       
    }


}
@media (max-width:1198px) {
    .navbar .sub-section a{
        display: none;
    }
    .navbar .menu-section a{
        display: none;
    }
    .navbar .sub-section{
        gap: 0;
    }
    .instagram-text-logo{
        display: none;
        /* position: absolute; */
    }
    .navbar{
        width: 79px;
    }
}
@media (max-width:1003px) {
    .follow-section{
        display: none;
    }
    .middle-section .post-area{
        padding-inline: 0;
    }
}
@media (max-width:690px) {

  .post-section .story-section{
        justify-content: space-evenly;
    }
    .story-section #story-7{
        display: none;
    }

}
@media (max-width:562px){
    .story-section #story-6{
        display: none;
    }
}
@media (max-width:482px){
    .story-section #story-5{
        display: none;
    }
}
@media (max-width:402px){
    .story-section #story-4{
        display: none;
    }
}
@media (max-width:323px){
    #story-3{
        display: none;
    }
}
@media (max-width:259px){
    #story-2{
        display: none;
    }
}
.instagram-text-logo{
    width: 150px;
    margin: 5px 30px;
    cursor: pointer;
}
.instagram-text-logo img{
    width: 100%;
    /* filter: brightness(5); */
}

.sub-section{
    display: flex;
    align-items: center;
    gap: 25px;
    border-radius: 5px;
    cursor: pointer;
    padding: 10px 20px;
    transition: all 0.2s ease;
}
.sub-section:hover{
    background-color: var(--background-on-hover);
}
.sub-section:hover i{
    transform: scale(1.07);
    transition: all 0.2s ease;
}
.sub-section:hover a{
    font-weight: 600;
}
.sub-section:hover .profile-img{
    transform: scale(1.07);
    transition: all 0.2s ease;
}
.sub-section i{
    font-size: 1.3rem;
    color: var(--font-color);
    transition: all 0.2s ease;
    
}
.profile-img{
    width: 22px;
    transition: all 0.2s ease;
    cursor: pointer;
}
.profile-img img{
    width: 100%;
    border-radius: 50%;
}
.menu-section{
    display: flex;
    gap: 25px;
    align-items: center;
    /* position: absolute;
    bottom: 10px; */
    margin-top: 23px;
    border-radius: 5px;
    cursor: pointer;
    padding: 10px 20px;
    transition: all 0.3s ease;
}
.menu-section:hover{
    background-color: var(--background-on-hover);
}
.menu-section:hover i{
   transform: scale(1.07);
   transition: all 0.2s ease;
}
.menu-section i{
    color: var(--font-color);
    font-size: 1.2rem;
    transition: all 0.2s ease;
}
/* post section started frome here */
.post-section{
    padding:20px 20px;
    /* border: 2px solid pink; */
    background-color: var(--background-color);
    max-width: 660px;
   
}
.story-section{
    display: flex;
    gap: 10px;
    justify-content: center;
    /* flex-wrap: wrap; */
    /* width: 100%;
    overflow:scroll; */
    /* overflow-x: auto; */
}
.story{
    overflow: hidden;
    display: flex;
    gap: 10px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.story-image{
    /* height: 60px; 
    width: 55px; */
    background-color: #4158D0;
    background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 65px;
    width: 65px;
    background-image: cover;
}
.story-image img{
    width: 90%;
    height: 90%;
    border: 2px solid var(--background-color);
    border-radius: 50%;
    background-image: cover;
    background-position: center;
    background-size: cover;
}
.story span{
    font-family: 'Roboto', sans-serif;
    color: var(--font-color);
    font-size: 0.8rem;
    font-weight: 500;
    
}




.post-area{
    margin-top: 50px;
    padding-inline: 80px;
    margin-bottom: 50px;
}
.post-main{
    color: var(--font-color);
}
.post-image{
    width: 40px;
    height: 40px;
    background-color: #4158D0;
    background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
    
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.post-image img{
    width: 90%;
    height: 90%;
    border: 2px solid var(--background-color);
    border-radius: 50%;
}
.post-username{
    color: var(--font-color);
    font-size: 1rem;

}
.one-day{
    font-size: 0.8rem;
    color: var(--secod-font-color);
}
.post-header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 30px;
    padding-inline: 5px;
}
.post-header i{
    color: var(--font-color);
    cursor: pointer;
    transition: all 0.2s ease;
}
.post-header i:hover{
    color: var(--secondary-font-color);
}
.post-left-header{
    display: flex;
    align-items: center;
    gap: 5px;
    cursor: pointer;
}
.post-left-header i{
    color: rgb(85, 85, 250);
}
.post-left-header i:hover{
    color: rgb(30, 30, 150);
}
.post-main-image{
    margin-top: 10px;
    width: 100%;
}
.post-main-image img{
    width: 100%;
    border-radius: 1px;
}
.post-fotter{
    display: flex;
    justify-content: space-between;
    margin-top: 7px;
    padding-inline: 5px;
    
}
.post-fotter i{
    font-size: 1.2rem;
    cursor: pointer;
    /* font-weight: 2000; */
    transition: all 0.2s ease;
}
.post-fotter i:hover{
    color: var(--secondary-font-color);
}
.post-fotter-left{
    display: flex;
    gap: 20px;
}
.post-description{
    margin-block: 3px;
    padding-inline: 5px;
}
.post-liked{
    margin-block: 7px;
    font-size: 0.8rem;
    color: black;
    cursor: pointer;
}
.title{
    font-size: 0.9rem;
    color: var(--secod-font-color);
    cursor: pointer;
}
.title span{
    color: var(--font-color);
    font-weight: bold;
}
.comments{
    margin-block: 5px;
    font-size: 0.8rem;
    color: var(--secod-font-color);
    cursor: pointer;
}
/* profile follow section startted fome here */

.profile-follow-image{
    width: 40px;
    height: 40px;
}
.profile-follow-image img{
    width: 100%;
    border-radius: 50%;
    height: 100%;
}
.profile-follow-content{
    color: var(--font-color)
}
.profile-follow-left{
    display: flex;
    gap: 20px;
    cursor: pointer;
}
.profile-follow{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-block: 7px;
}
.profile-follow-content{
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.follow{
    color: rgb(19, 85, 240);
    font-weight: 20;
    font-size: 0.7rem;
    font-weight: 550;
    line-height: 0.1;
    transition: all 0.1s ease;
}
.follow:hover{
    color: var(--font-color);
}
.profile-id{
    color: var(--font-color);
    font-size: 0.8rem;
    font-weight: 550;
}
.profile-name{
    color: var(--secod-font-color);
    font-size: 0.7rem;
    margin-top: 5px;
    font-weight: 100;
}
.suggestion{
    color: var(--secod-font-color);
    font-size: 0.9rem;
    font-weight: 500;
}
.see-all{
    color: var(--secod-font-color);
    font-size: 0.8rem;
    transition: all 0.1s ease;
}
.see-all:hover{
    color: var(--secondary-font-color);
}
.follow-section{
    margin-top: 46px;
    width: 320px;
    padding: 10px 20px;
}
.suggestion-follow{
    display: flex;
    justify-content: space-between;
    color: var(--font-color);
    margin-block: 10px;
}
.copyrights{
    color: var(--secod-font-color);
    font-size: 0.9rem;
    margin-top: 50px;
    text-align: center;
}
.profile-foolow-hovering{
    padding: 5px;
    cursor: pointer;
    border-radius: 5px;
    transition: all 0.1s ease-in-out;
}
.profile-foolow-hovering:hover{
    background-color: var(--background-on-hover);
}



.nav-hidden{
    display: none;
}
.nav-hidden i{
    font-size: 1.4rem;
    cursor: pointer;
    color: var(--font-color);
    transition: all 0.2s ease;
}
.nav-hidden i:hover{
    color: var(--secondary-font-color);
}
.nav-hidden-logo{
    width: 136px;
    cursor: pointer;
}
.nav-hidden-logo img{
    width: 100%;
}
.nav-hide-2{
    display: flex;
    gap: 30px;
}
@media (max-width:750px){
    .nav-hidden{
        width: 100%;
        display: flex;
        justify-content: space-between;
        padding-inline: 10px;
        align-items: center;
    }
     .middle-section .post-section{
        padding: 0;
        padding-bottom: 20px;
    }
}
    </style>
    
</head>
<body>
<div class="container">
        <!-- starting nav section of instagram -->
        <nav>
            <div class="navbar">
                <div class="instagram-text-logo">
                    <img src="https://i.postimg.cc/qMFTcDw1/instagram-text.png" id="white-color" alt="">
                </div>
                <div class="sub-section" id="clicked" onclick=myfun()>
                    <i class="fa-solid fa-house" ></i>
                    <a href="#">Dark-mode</a>
                </div>
                <div class="sub-section" >
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <a href="#" >Search</a>
                </div>
                <div class="sub-section" >
                    <i class="fa-regular fa-compass"></i>
                    <a href="#">Explore</a>
                </div>
                <div class="sub-section">
                    <i class="fa-solid fa-clapperboard"></i>
                    <a href="#">Reels</a>
                </div>
                <div class="sub-section">
                    <i class="fa-regular fa-message"></i>
                    <a href="#">Messages</a>
                </div>
                <div class="sub-section" id="hidden2">
                    <i class="fa-regular fa-heart"></i>
                    <a href="#">Notification</a>
                </div>
                <div class="sub-section" id="hidden1">
                    <i class="fa-solid fa-square-plus"></i>
                    <a href="#">Create</a>
                </div>
                <div class="sub-section">
                    <div class="profile-img">
                        <img src="img2.jpeg" alt="">
                    </div>
                    <a href="#">Profile</a>
                </div>
                <div class="menu-section " id="hidden">
                    <i class="fa-solid fa-bars"></i>
                    <a href="#">More</a>
                </div>
            </div>
            
        </nav>
        <div class="middle-section">
            <div class="post-section">
                <div class="nav-hidden">
                    <div class="nav-hidden-logo" id="white-2color">
                        <img src="img2.jpeg" alt="">
                    </div>
                   <div class="nav-hide-2">
                     <i class="fa-regular fa-heart"></i>
                     <i class="fa-regular fa-paper-plane"></i>
                   </div>
                </div>
                <div class="story-section">
                    <div class="story">
                        <div class="story-image">
                            <img src="img1.jpeg" alt="">
                        </div>
                        <span>Lavanya04</span>
                    </div>
                    <div class="story">
                        <div class="story-image">
                            <img src="img3.jpg" alt="">
                        </div>
                        <span>Dharani100</span>
                    </div>
                    <div class="story" id="story-2">
                        <div class="story-image">
                            <img src="img4.jpg" alt="">
                        </div>
                        <span>MR.dhanush</span>
                    </div>
                    <div class="story" id="story-3">
                        <div class="story-image"  >
                            <img src="img5.jpeg" alt="">
                        </div>
                        <span>Vijaya_bhaska</span>
                    </div>
                    <div class="story" id="story-4">
                        <div class="story-image">
                            <img src="img6.jpeg" alt="">
                        </div>
                        <span>Varunkumar</span>
                    </div>
                    <div class="story" id="story-5">
                        <div class="story-image">
                            <img src="img11.jpg" alt="">
                        </div>
                        <span>Mrunalthakur</span>
                    </div>
                    <div class="story" id="story-6">
                        <div class="story-image">
                            <img src="img10.jpg" alt="">
                        </div>
                        <span>NameisNani</span>
                    </div>
                    <div class="story" id="story-7">
                        <div class="story-image">
                            <img src="img9.jpg" alt="">
                        </div>
                        <span>actorprabhas</span>
                    </div>
                </div>
                <div class="post-area">
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img4.jpg" alt="">
                             </div>
                             <p class="post-username">
                                Mr.dhanush09</p>
                            
                             <span class="one-day"> . 1h </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img4.jpg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by venkatalakshmi and others</p>
                                <p class="title"><span>Mr.dhanush09 </span>VIBES.....<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img1.jpeg" alt="">
                             </div>
                             <p class="post-username">
                                Lavanya04</p>
                             
                             <span class="one-day"> . 1d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img1.jpeg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by Rajesh04 and others</p>
                                <p class="title"><span>
                                    Lavanya04 </span>Self-love is the best love ,Own your magic......<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img3.jpg" alt="">
                             </div>
                             <p class="post-username">
                                Dharani100</p>
                            
                             <span class="one-day"> . 5h </span>
                            </div>
                        
                         </div>
                         <div class="post-main-image">
                            <img src="img3.jpg" alt=""> 
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by Raghava and others</p>
                                <p class="title"><span>
                                    Dharani1000 </span>A Day Out...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img2.jpeg" alt="">
                             </div>
                             <p class="post-username">
                                Divyaa004</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img2.jpeg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by Vijaya_bhaskar_reddy_22 and others</p>
                                <p class="title"><span>
                                    Divyaa004</span>Hello peeps...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img5.jpeg" alt="">
                             </div>
                             <p class="post-username">
                                Vijaya_bhaskar_reddy_22</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 1w </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img5.jpeg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by Divya004 and others</p>
                                <p class="title"><span>
                                    Vijaya_bhaskar_reddy_22 </span>Recently clicked......<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img6.jpeg" alt="">
                             </div>
                             <p class="post-username">
                                Varunkumar08</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img6.jpeg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by Hyma and others</p>
                                <p class="title"><span>
                                    Varunkumar08 </span>Beach vibes...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img10.jpg" alt="">
                             </div>
                             <p class="post-username">
                                NameisNani</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img10.jpg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by Divyaa004 and others</p>
                                <p class="title"><span>
                                    NameisNani</span>HI chennai ...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img9.jpg" alt="">
                             </div>
                             <p class="post-username">
                                actorprabhas</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img9.jpg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by anushka04 and others</p>
                                <p class="title"><span>
                                    actorprabhas </span>The Battle Begins Now...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img11.jpg" alt="">
                             </div>
                             <p class="post-username">
                                 Mrunalthakur</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img11.jpg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by dulquersalman and others</p>
                                <p class="title"><span>
                                    Mrunal Thakur</span>Make your mark...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img12.jpg" alt="">
                             </div>
                             <p class="post-username">
                                urstrulymahesh</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img12.jpg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by namrata and others</p>
                                <p class="title"><span>
                                    urstrulymahesh </span>With the legend...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img13.jpg" alt="">
                             </div>
                             <p class="post-username">
                                Viratkohli</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img13.jpg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by anushkasharma and others</p>
                                <p class="title"><span>
                                    Viratkohli </span>Paris Love...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img8.jpg" alt="">
                             </div>
                             <p class="post-username">
                                Rampothineni</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img8.jpg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by kritishetty and others</p>
                                <p class="title"><span>
                                    Rampothineni </span>Missed carrying you...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                    <div class="post-main">
                        <div class="post-header">
                            <div class="post-left-header">
                             <div class="post-image">
                                 <img src="img7.jpg" alt="">
                             </div>
                             <p class="post-username">
                                Rohitsharma</p>
                             <i class="fa-solid fa-certificate"></i>
                             <span class="one-day"> . 5d </span>
                            </div>
                            <i class="fa-solid fa-grip-lines"></i>
                         </div>
                         <div class="post-main-image">
                            <img src="img7.jpg" alt="">
                         </div>
                         <div class="post-fotter">
                            <div class="post-fotter-left">
                                <i class="fa-regular fa-heart"></i>
                                <i class="fa-regular fa-message"></i>
                                <i class="fa-regular fa-paper-plane"></i>
                            </div>
                                <i class="fa-regular fa-bookmark"></i>
                         </div>
                         <div class="post-description">
                                <p class="post-liked">Liked by ritika and others</p>
                                <p class="title"><span>
                                    Rohitsharma </span>finally    ...<br> more</p>
                                <p class="comments"> view all comments</p>
                         </div>
                    </div>
                </div>
           </div>
           <div class="follow-section">
                <div class="profile-follow profile-foolow-hovering">
                    <div class="profile-follow-left">
                        <div class="profile-follow-image">
                            <img src="https://i.postimg.cc/zB3mRnhs/apy-logo.png" alt="">
                        </div>
                        <div class="profile-follow-content">
                            <p class="profile-id">mahendrasinghdhoni</p>
                            <p class="profile-name">dhoni07</p>
                        </div>
                    </div>
                    <a href="#" class="follow">switch</a>
                </div>
                 <div class="suggestion-follow">
                    <p class="suggestion">Suggested for you</p>
                    <a href="#" class="see-all">see all</a>
                 </div>
                 <div class="profile-follow profile-foolow-hovering">
                    <div class="profile-follow-left">
                        <div class="profile-follow-image">
                            <img src="WhatsApp Image 2024-07-30 at 22.06.10.jpeg" alt="">
                        </div>
                        <div class="profile-follow-content">
                            <p class="profile-id">rohit_@13</p>
                            <p class="profile-name">Followed by shivarama77</p>
                        </div>
                    </div>
                    <a href="#" class="follow">follow</a>
                </div>
                <div class="profile-follow profile-foolow-hovering">
                    <div class="profile-follow-left">
                        <div class="profile-follow-image">
                            <img src="WhatsApp Image 2024-07-30 at 22.06.10.jpeg" alt="">
                        </div>
                        <div class="profile-follow-content">
                            <p class="profile-id">udaybhaskar</p>
                            <p class="profile-name">Followed by vijaybhaskar_ + 2 more
                            </p>
                        </div>
                    </div>
                    <a href="#" class="follow">follow</a>
                </div>
                <div class="profile-follow profile-foolow-hovering">
                    <div class="profile-follow-left">
                        <div class="profile-follow-image">
                            <img src="WhatsApp Image 2024-07-30 at 22.06.10.jpeg" alt="">
                        </div>
                        <div class="profile-follow-content">
                            <p class="profile-id">Rajesh04</p>
                            <p class="profile-name">Followed by Lavanya04 +....
                            </p>
                        </div>
                    </div>
                    <a href="#" class="follow">follow</a>
                </div>
                <div class="profile-follow profile-foolow-hovering">
                    <div class="profile-follow-left">
                        <div class="profile-follow-image">
                            <img src="WhatsApp Image 2024-07-30 at 22.06.10.jpeg" alt="">
                        </div>
                        <div class="profile-follow-content">
                            <p class="profile-id">dulquersalman</p>
                            <p class="profile-name">Followed by mrunal_thakur
                            </p>
                        </div>
                    </div>
                    <a href="#" class="follow">follow</a>
                </div>
                <div class="profile-follow profile-foolow-hovering">
                    <div class="profile-follow-left">
                        <div class="profile-follow-image">
                            <img src="WhatsApp Image 2024-07-30 at 22.06.10.jpeg" alt="">
                        </div>
                        <div class="profile-follow-content">
                            <p class="profile-id">ramcharan</p>
                            <p class="profile-name">New to Instagram</p>
                        </div>
                    </div>
                    <a href="#" class="follow">follow</a>
                </div>
                <p class="copyrights"> @All rights reserved by DIVYAJYOTHI</p>
           </div>
        </div>

</div>
    <script src="script.js"></script>
</body>
</html>
