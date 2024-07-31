
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
<<<<<<< HEAD
</html>
=======
</html>
>>>>>>> 69d00050aabb75d1bfac912751bf9a9d3fc090e0
