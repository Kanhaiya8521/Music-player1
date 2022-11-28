# Music-player1
This is the website which made by me and totaly new. I motivated by ganna.com music website and try to implement similar like this and added some new features in my website. This website responsible to all size of device and it's challenges for me and I gave lots of time on it and learnt many things for it.
The Hosted link of this website: https://kanhaiya8521.github.io/Music-player1/index.html
What I feature added in it I commented in every line of code in my website source file and source files has opened for all of you so go on them and explore if u have any suggestion for me please give me that 's why I will in future as well.


University Institute of Engineering and Technology, Panjab University Hoshiarpur

                                            
	
Mid Term Industrial Training

                                                               ________________________________

                                                                     CREATORS

Name: Kanhaiya Kumar
IT - (SG19820)




TABLE OF CONTENTS:
1) Introduction
2) Purpose
3) Target Audience
4) Scope
5) Project Objectives
5.1) Goals
5.2) Tasks
5.2.1) Proper Environment Setup
5.2.2) Frame Work Building
5.2.3) Designing
5.2.4) Coding
5.2.5) Testing
5.2.6) Bug Fixing
5.2.7) Final Documentation
5.3) Resources
5.4) Budget
6) Milestone
7) Abbrevations
8) Project Client
9) Project Manager
10) Project Group
11) Steering Group
12) Requirements
13) Requirement Summary
14) Project Specifications
15) Pages
16) Project Experience



1.	INTRODUCTION:-

The Web Music Player is a music platform designed to play music from across the web by utilizing a simple chrome browser. The intent is to designate a machine to present a simple frontend web page of music playe website and play music for other devices to control through a Web Interface.


2.	PURPOSE:-

They are portable digital music players that play music as audio files, such as MP3. In addition, most of these devices allow to store video, pictures, and to receive radio and TV programs (podcasting). Earphones and external speakers are the typical output devices delivering sound to the listener.


3.	SCOPE:-

The music player allows a user to play various media file formats. It can be used to play audio as well as video files. The music player is a software project supporting all known media files and has the ability to play them with ease.


4. GOALS:-
The primary purpose of the music streaming application is to play music available in the databases of the service, compose custom playlists and suggest similar songs. The main elements of music streaming apps are: Discovery.

5. RESOURCES:-
They are portable digital music players that play music as audio files, such as MP3. In addition, most of these devices allow to store video, pictures, and to receive radio and TV programs (podcasting). Earphones and external speakers are the typical output devices delivering sound to the listener.






6. MILESTONE:-

			
Description 	Fixed date
Kick off	Project start date – 05 july 2022
Design	Design and layout must be completed till 25 july 2022
Basic structure	Basic structure of the website must be completed till 25 july 2022
Functionalities	All the functionalities must be completed till 25july 2022
Testing	Testing should be done till 30july 2022
Bug fixing	Till 30july 2022
Finishing	                                                       	Design finishing should be done till 30july 2022

7. STEERING GROUP:-
Kanhaiya Kumar	HEAD

13. REQUIREMENT:-
API	No
Environment setup
(1)VS - code & (2)bracket	Yes
Bootstrap framework	Yes
JQuery plugin 	No
Basic
(1)HTML(2)CSS(3)JS	Yes
Photoshop	Yes
Illustrator	Yes
Internet	Yes
TeamViewer	Yes
NPM	No
Preloaded	No
Nodejs	No
GitHub	Yes
Server	No


14. Project experience:-
(i) Positive and excellent experience during doing this project.
(ii) Time management and get to know how to tackle problem.
(iii) Group coordination improvement.
(iv) Improved mistakes.
(v) Learned about these technologies more while working on them in the project.


 
 
 
Code:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Home Page</title>
    <link rel="stylesheet" type="text/css" href="index.css">
    <link rel="stylesheet" type="text/css" href="index_responsive.css">
    <script src="https://kit.fontawesome.com/3857ed317d.js" crossorigin="anonymous"></script>
</head>
<body>
    <!-- top navigation bar -->
    <nav class="navigation-bar">
        <!-- this div contains the logo and title os the page -->
        <div class="title-combo">
            <div class="website-logo">
                <img src="media/website_logo.png">
            </div>
            <div class="website-name">
                <h2>
                    <a href="index2.html">
                        Kanhaiya
                    </a>
                </h2>
                <h6 style="color: magenta;">
                    <a href="index2.html">Music Player</a>
                </h6>
            </div>
        </div>
        <!-- this is the animated favourites text -->
        <div class="favs">
            <h4>
                <a href="index2.html">Favourites</a>
                
            </h4>
        </div>
        <div class="search-bar">
            <div>
                <!-- magnifying glass- search icon -->
                <i class="fas fa-search search-ico"></i>
            </div>
            <input type="text" name="search" placeholder="Search">
            <div>
                <!-- mic icon -->
                <i class="fas fa-microphone mic-ico"></i>
            </div>
        </div>
        <!-- this is for notification bell -->
        <div class="notification-bell">
            <a href="index2.html">
            <img src="media/bell_icon.png"> Notifications
            </a>
        </div>
        <!-- this is for profile picture -->
        <div class="profile-picture">
            <a href="index2.html">
            <img src="media/profile_picture.png">
            </a>
        </div>
    </nav>
    <!-- this is the main center part of the page and it is divided into two sections, namely section 1 and section 2-->
    <!-- I have separated these sections using the aside tag for each section -->
    <main>
        <!-- aside section 1 -->
        <aside class="aside section-1">
            <!-- this is for the jumbotron -->
            <div class="jumbotron">
                <div class=jumbotron-image>
                    <!-- there is nothing in this div because all the images and all are added by css -->
                </div>
                <!-- jumbotron details -->
                <div class="jumbotron-detail">
                    <!-- descriptive part of the jumbotron this will contain name , number of followers and all -->
                    <div class="descriptive-part">
                        <div class="song-name-main">
                            <h1>ColdPlay</h1>
                        </div>
                        <div class="followers">
                            21m Followers
                        </div>
                        <p class="author">British Band</p>
                        <!-- short description of the current author -->
                        <p class="desc">
                            Coldplay are a British rock band formed in London in 1996. Vocalist, rhythm guitarist and pianist Chris Martin, lead guitarist Jonny Buckland, bassist Guy Berryman, and drummer Will Champion met at University College London and began playing music together from 1996 to 1998, first calling themselves Pectoralz and then Starfish before finally changing their name to Coldplay
                        </p>
                    </div>
                    <!-- action part -->
                    <div class="action-part">
                        <!-- action buttons -->
                        <div class="btns">
                            
                            <button>Play All</button>
                            <button>Follow</button>
                        </div>
                        <p>
                            247 Tracks | 128 Albums
                        </p>
                    </div>
                </div>
            </div>
            <!-- now the playlist part begins -->
            <div class="playlist-items">
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            01
                        </div>
                        <div>
                            <img src="media/playlist/austin-neill-kKlVSrFbjYY-unsplash.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Alone
                            </h5>
                            <p>
                                Alan Walker
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        3:14
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            02
                        </div>
                        <div>
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                White Iverson
                            </h5>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        3:44
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            03
                        </div>
                        <div>
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Go Flex
                            </h5>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        2:55
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            04
                        </div>
                        <div>
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Better Now
                            </h5>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        3:37
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            05
                        </div>
                        <div>
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Big lie
                            </h5>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        3:27
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            06
                        </div>
                        <div>
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Deja Vu
                            </h5>
                            <p>
                                Post Malone & Justin Beiber
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        4:31
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            07
                        </div>
                        <div>
                            <img src="media/playlist/beer.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Pysco
                            </h5>
                            <p>
                                Post Malone 
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        3:28
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            08
                        </div>
                        <div>
                            <img src="media/playlist/beer.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Rockstar
                            </h5>
                            <p>
                                Post Malone & 21 Savage
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        3:48
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            09
                        </div>
                        <div>
                            <img src="media/playlist/after.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Blinding Lights
                            </h5>
                            <p>
                                Weeknd
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        3:20
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            10
                        </div>
                        <div>
                            <img src="media/playlist/after.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Alone Again
                            </h5>
                            <p>
                                Weeknd
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        4:10
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            11
                        </div>
                        <div>
                            <img src="media/playlist/after.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Too Late
                            </h5>
                            <p>
                                Weeknd
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        4:00
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
                <!-- playlist item -->
                <div class="playlist-item">
                    <div class="left">
                        <div>
                            12
                        </div>
                        <div>
                            <img src="media/playlist/after.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div>
                            <h5>
                                Hardest To Love
                            </h5>
                            <p>
                                Weeknd
                            </p>
                        </div>
                    </div>
                    <div class="center">
                        3:31
                    </div>
                    <div class="right">
                        <div>
                            <i class="far fa-heart"></i>
                        </div>
                        <div>
                            <i class="fas fa-plus"></i>
                        </div>
                    </div>
                </div>
            </div>
        </aside>
        <!-- one aside section is complete -->
        <!-- now the second aside section will start from here -->
        <!-- the page is responsive. please try reducing the width of the page -->
        <!-- the aside section will collapse and a "more button will be shown to you." -->
        <!-- clicking on this more button, you will be shown the aside section 2  -->
        <!-- its position will be absolute at lower resolutions -->
        <!-- this is the label for that more button -->
        <label for="more"><i class="fas fa-angle-double-left"></i>More</label>
        <!-- this is that more button -->
        <!-- and this is the check box. this will always be hidden -->
        <!-- check the stylesheet_main.css when the label is clicked, this checkbox will be checked -->
        <!-- which will invoke the aside section 2 on lower resolutions -->
        <input type="checkbox" id="more">
        <!-- </div> -->
        <aside class="aside section-2">
            <!-- similar class will be applicable to both similar artists and recently played -->
            <div class="similar">
                <!-- section heading, which also contains the view all button -->
                <div class="section-heading">
                    <h1>Similar Artists</h1>
                    <div class="view-all-button">
                        View All
                    </div>
                </div>
                <!-- list is the container for the contents of similar artists -->
                <div class="list">
                    <!-- item -->
                    <div class="list-item">
                        <div>
                            <img src="media/music themes/love.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div style="position: absolute; left:120px;">
                            <h5>
                                Love me
                            </h5>
                            <p class="author-name">
                                Justin Beiber
                            </p>
                        </div>
                        <div class="extra">
                            <div>
                                <i class="fas fa-ellipsis-h"></i>
                            </div>
                            <p class="author-name">
                                2:14
                            </p>
                        </div>
                    </div>
                    <!-- item -->
                    <div class="list-item">
                        <div>
                            <img src="media/popular artists/sixnine.jpg">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div style="position: absolute; left:120px;">
                            <h5>
                                Gotti
                            </h5>
                            <p class="author-name">
                                6ix9ine
                            </p>
                        </div>
                        <div class="extra">
                            <div>
                                <i class="fas fa-ellipsis-h"></i>
                            </div>
                            <p class="author-name">
                                4:00
                            </p>
                        </div>
                    </div>
                    <!-- item -->
                    <div class="list-item">
                        <div>
                            <img src="media/songs/shit.png">
                            <div class="play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                        </div>
                        <div style="position: absolute; left:120px;">
                            <h5>
                                WAP
                            </h5>
                            <p class="author-name">
                                Cardi B
                            </p>
                        </div>
                        <div class="extra">
                            <div>
                                <i class="fas fa-ellipsis-h"></i>
                            </div>
                            <p class="author-name">
                                4:44
                            </p>
                        </div>
                    </div>
                </div>


                <!-- recently played section -->
                <div class="similar">
                    <!-- section headings, which also contains the view all button -->
                    <div class="section-heading">
                        <h1>Recently Played</h1>
                        <div class="view-all-button">
                            View All
                        </div>
                    </div>
                    <!-- again list is a container for all the contents of recently played section -->
                    <div class="list">
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    01
                                </div>
                                <div>
                                    <img src="media/latest english/I'll Wait.jpg">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        I'll wait
                                    </h5>
                                    <p>
                                        Kygo
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    02
                                </div>
                                <div>
                                    <img src="media/latest english/let me go.jpg">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        Let Me Go
                                    </h5>
                                    <p>
                                        NoMethod
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    03
                                </div>
                                <div>
                                    <img src="media/latest english/ily.jpg">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        ILY
                                    </h5>
                                    <p>
                                        Surf Mesa
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    04
                                </div>
                                <div>
                                    <img src="media/latest english/roar.jpg">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        Roar
                                    </h5>
                                    <p>
                                        Ketty Perry
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    05
                                </div>
                                <div>
                                    <img src="media/latest english/toosie slide.jpg">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        Toosie Slide
                                    </h5>
                                    <p>
                                        Drake
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    06
                                </div>
                                <div>
                                    <img src="media/latest english/uptown funk.png">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        Uptwon Funk
                                    </h5>
                                    <p>
                                        Bruno
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    07
                                </div>
                                <div>
                                    <img src="media/latest hindi/baarish.jpeg">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        Baarish
                                    </h5>
                                    <p>
                                        Half Girlfriend
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    08
                                </div>
                                <div>
                                    <img src="media/latest hindi/galiyaan.jpg">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        Gulliyon
                                    </h5>
                                    <p>
                                        Ek Villan
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                        <!-- item -->
                        <div class="playlist-item">
                            <div class="left">
                                <div>
                                    09
                                </div>
                                <div>
                                    <img src="media/latest hindi/giveme some sunshine.jpg">
                                    <div class="play-btn">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div>
                                    <h5>
                                        All-is-well
                                    </h5>
                                    <p>
                                        3idiots
                                    </p>
                                </div>
                            </div>
                            <div class="right">
                                <div>
                                    <i class="far fa-heart"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </aside>
    </main>



    <!-- main part of the page is over. -->
    <!-- this is the footer part. -->
    <!-- its position will be fixed to the screen bottom. -->
    <footer>
        <div class="active-song-description">
            <!-- song image -->
            <div id="song-image">
                <img src="media/playlist/stoney.jpg">
            </div>
            <!-- song name and author -->
            <div class="song-desc">
                <div>
                    White Iverson
                </div>
                <div>
                    Post Malone
                </div>
            </div>
                <!-- heart icon and ban icon -->
            <div class="heart-and-ban-icon">
                <span>
                    <i class="far fa-heart"></i>
                </span>
                <span>
                    <i class="fas fa-ban"></i>
                </span>
            </div>
        </div>
        <!-- these are the main player controls -->
        <div class="player">
            <div class="controls">
                <div><i class="fas fa-random"></i></div>
                <div><i class="fas fa-step-backward"></i></div>
                <div><i class="fas fa-pause-circle"></i></div>
                <div><i class="fas fa-step-forward"></i></div>
                <div><i class="fas fa-redo"></i></div>
            </div>
            <!-- this is the slider -->
            <div id="slider">
                <!-- current time -->
                <div class="time">
                    1:39
                </div>
                <div class="slidecontainer">
                    <input type="range" min="0" max="100" value="0" class="slider" id="myRange">
                </div>
                <!-- total time -->
                <div class="time">
                    4:44
                </div>
            </div>
        </div>
        <!-- other icons including the volume slider and all -->
        <div class="extras">
            <div>
                <i class="fas fa-list-ul"></i>
            </div>
            <div>
                <i class="fas fa-laptop"></i>
            </div>
            <div>
                <i class="fas fa-volume-up"></i>
            </div>
            <div class="slidecontainer" style="width:30%;">
                <input type="range" min="0" max="100" value="0" class="slider" id="myRange" style="margin-top:0px;">
            </div>
            <div>
                <i class="fas fa-expand-alt"></i>
            </div>
        </div>
    </footer>
</body>
</html>

 
 
 
<!-- Codes -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kanhaiya Music Player</title>
    <!-- it is connected to two stylesheets -->
    <link rel="stylesheet" type="text/css" href="index2.css"><!-- this is the main stylesheet -->
    <!-- desktop first approach is used for the same. -->
    <link rel="stylesheet" type="text/css" href="index2_responsive.css"><!-- this is the style sheet with all the media queries -->
    <!-- this script is just for font awesome fonts -->
    <script src="https://kit.fontawesome.com/2d9b67a497.js" crossorigin="anonymous"></script>
</head>
<!-- body -->

<body>
    <!-- top navigation bar -->
    <nav class="navigation-bar">
        <!--This div contains the logo and title of the page-->
        <div class="title-combo">
            <div class="website-logo">
                <img src="media/website_logo.png">
            </div>
            <div class="website-name">
                 <h2>
                    <a href="index.html">
                        Kanhaiya
                    </a>
                </h2>
                 <h6 style="color: magenta;">
                    <a href="index.html">Music Player</a>
                </h6>
            </div>
        </div>
        <!-- this is the animated favourites text -->
        <div class="favs">
            <h4>
                <a href="index.html">
                    Favourites
                </a>
                
            </h4>
        </div>
        <!-- this is for search bar -->
        <div class="search-bar">
            <div>
                <!-- magnifying glass- search icon -->
                <i class="fas fa-search search-ico"></i>
            </div>
            <input type="text" name="search" placeholder="Search">
            <div>
                <!-- mic icon -->
                <i class="fas fa-microphone mic-ico"></i>
            </div>
        </div>
        <!-- this is for notification bell -->
        <div class="notification-bell">
            <img src="media/bell_icon.png"> Notifications

        </div>
        <!-- this is for profile picture -->
        <div class="profile-picture">
            <a href="index.html">
                <img src="media/profile_picture.png">
            </a>
            
        </div>
    </nav>
    <!-- this is the main center part of the page and it is divided into two sections, namely section 1 and section 2-->
    <!-- I have separated these sections using the aside tag for each section -->
    <main>
        <!-- aside section 1 -->
        <aside class="aside section-1">
            <!-- this is for the carousel -->
            <div class="outer-carousel">
                <div class="carousel">
                    <!-- these are the 3 images in the carousel -->
                    <img src="media/crousel/carousel1.jpg">
                    <img src="media/crousel/carousel2.jpg">
                    <img src="media/crousel/carousel3.jpg">
                </div>
            </div>
            <!-- this is the latest release section -->
            <div class="latest-release">
                <h1 style="margin-bottom: 12px;">
                    Latest Release
                </h1>
                <!-- this is the content of the latest release section -->
                <!-- it will contain the "cards" -->
                <div class="latest-release-content">
                    <!-- first card -->
                    <div class="card">
                        <div>
                            <!-- image corresponding to the card -->
                            <img src="media/songs/willow.jpeg">
                            <!-- play button, which will be shown on hover on the card image -->
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <!-- it will contain the name and date of release of the song -->
                        <div class="song-description">
                            <h3>
                                Willow
                            </h3>
                            <p>
                                Dec , 2020
                            </p>
                        </div>
                        <!-- if someone clicks on the three dots, options will be shown to the user for further action -->
                        <div class="options">
                            <label for="latest-release-checkbox"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <!-- if user clicks on play now button, he/she will be taken to the single playlist page -->
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <!-- duration of the song -->
                            <p>
                                3:35
                            </p>
                        </div>
                    </div>
                    <!-- second card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/Weeknd.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                               Blinding Lights
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <label for="latest-release-checkbox2"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox2">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                                3:20
                            </p>
                        </div>
                    </div>
                    <!-- third card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/DaBaby.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                                ROCKSTAR
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <label for="latest-release-checkbox3"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox3">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                                3:02
                            </p>
                        </div>
                    </div>
                    <!-- fourth card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/dynamite.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                                Dynamite
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <!-- NOTE THAT POSITION OF OPTIONS DIV IS RELATIVE -->
                            <label for="latest-release-checkbox4"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox4">
                            <div class="latest-release-dropdown">
                                <!-- POSITION OF LATEST RELEASE DROPDOWN IS ABSOLUTE TO THE RELATIVE OPTIONS. THIS IS VERY IMPORTANT AS THE DROPDOWN BOX SHOULD BE PLACED RELATIVE TO THE PARTICULAR ITEM IN THE LATEST RELEASE SECTION. IT SHOULD NOT BE ABSAOLUTE TO THE WHOLE LATEST RELEASE SECTION. THROUGH THIS PROJECT i UNDERSTOOD THE NEED OF POSITION:ABSOLUTE. ABSOLUTE POSITION AND RELATIVE ARE GENERALLY USED TOGETHER-->
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                                3:19
                            </p>
                        </div>
                    </div>
                    <!-- fifth card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/shit.png">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                                WAP
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <label for="latest-release-checkbox5"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox5">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                                4:44
                            </p>
                        </div>
                    </div>
                    <!-- sixth card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/falling.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                                Falling
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <label for="latest-release-checkbox6"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox6">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                              2:39
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- this is the popular artists section -->
            <div class="popular-artists">
                <!-- this is the heading of popular artists section -->
                <h1 style="margin-bottom: 12px;">
                    Popular Artists
                </h1>
                <!-- this contains the content of the popular artists section -->
                <div class="popular-artist-content">
                    <!-- if user clicks on any one artist, it will redirect the user to the second page -->
                    <!-- following is the list of artists -->
                    <!-- first artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/adele.jpg">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Adele
                            </p>
                        </div>
                    </a>
                    <!-- second artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/billie eilish.jpg">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Billie Eilish
                            </p>
                        </div>
                    </a>
                    <!-- third artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/bruno mars.jpg" width="15vw" height="10vw">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Bruno Mars
                            </p>
                        </div>
                    </a>
                    <!-- fourth artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/Camila Cabello.jpg">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Camila Cabello
                            </p>
                        </div>
                    </a>
                    <!-- fifth artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/drake.jpg">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Drake
                            </p>
                        </div>
                    </a>
                    <!-- 6th artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/ed sheeran.jpg">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Ed Sheeran
                            </p>
                        </div>
                    </a><!-- 7th artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/eminem.jpg">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Eminem
                            </p>
                        </div>
                    </a><!-- 8th artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/Katy perry.jpg">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Katy Perry
                            </p>
                        </div>
                    </a>
                    <!-- 9th artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/sixnine.jpg">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                6ix9ine
                            </p>
                        </div>
                    </a>
                    <!-- 10th artist -->
                    <a href="Single Playlist Screen.html">
                        <div>
                            <img src="media/popular artists/posty.png">
                            <div><i class="fas fa-play"></i></div>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </a>
                </div>
            </div>
            <!-- this is the music themes part, the one with the tri-gradient background -->
            <div class="music-themes">
                <!-- this div will be the logo of music themes, see the output, the one with 3 squares/rects  -->
                <!-- the logo with orange, green and yellow color -->
                <div class="stations">
                    <div id="div1">
                        <div id="div2">
                            <div id="div3">
                                <img src="media/website_logo.png">
                                <p>Stations</p>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- this is the content part of them themes -->
                <!-- the one which changes colors on hover -->
                <div class="theme-main">
                    <div class="theme-content">
                        <img src="media/music themes/chill.jpg">
                        <p>Vibe</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/rock.jpg">
                        <p>Rock</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/love.jpg">
                        <p>Love</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/pop.jpg">
                        <p>Pop</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/retro.jpg">
                        <p>Retro</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/workout.jpg">
                        <p>GYM</p>
                    </div>
                </div>
            </div>
            <!-- this is another themes portion, that electronic, party and road theme -->
            <div class="music-themes-2">
                <!-- 3 divs content -->
                <div class="outer-div">
                    <div class="inner-div">
                        <span>party</span>
                    </div>
                </div>
                <div class="outer-div">
                    <div class="inner-div">
                        <span>Electronic</span>
                    </div>
                </div>
                <div class="outer-div">
                    <div class="inner-div">
                        <span>Travel</span>
                    </div>
                </div>
            </div>
            <!-- div over -->
            <!-- this div contains the language section of the page -->
            <!-- "language class is common to both hindi and english sections" -->
            <!-- in this way redundancy is handled. considering the re-usability of the code -->
            <div class="language english">
                <!-- latest english section -->
                <h1 class="language-heading">
                    Latest English
                </h1>
                <!-- contents of latest english -->
                <div class="language-content">
                    <div>
                        <img src="media/latest english/I'll Wait.jpg">
                        <p>I'll Wait</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest english/let me go.jpg">
                        <p>Let me Go!</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest english/qurantine clean.jpg">
                        <p>Qurantine Clean</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest english/roar.jpg">
                        <p>Roar</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest english/toosie slide.jpg">
                        <p>Toosie Slide</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest english/uptown funk.png">
                        <p>Uptown Funk</p>
                        <p>Aug 11, 2017</p>
                    </div>
                </div>
            </div>
            <!-- this is the hindi section -->
            <div class="language hindi">
                <!-- hindi section heading -->
                <h1 class="language-heading">
                    Latest Hindi
                </h1>
                <!-- hindi section contents -->
                <div class="language-content">

                    <div>
                        <img src="media/latest hindi/baarish.jpeg">
                        <p>Baarish</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/galiyaan.jpg">
                        <p>Galiyaan</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/giveme some sunshine.jpg">
                        <p>Give me Some Sunshine</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/kaun tujhe.jpg">
                        <p>Kaun Tujhe</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/tera ban jaunga.jpg">
                        <p>Tera Ban Jaunga</p>
                        <p>Aug 11, 2017</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/tere sang yara.jpg">
                        <p>Tere Sang Yaara</p>
                        <p>Aug 11, 2017</p>
                    </div>
                </div>
            </div>
        </aside>
        <!-- one aside section is complete -->
        <!-- now the second aside section will start from here -->
        <!-- the page is responsive. please try reducing the width of the page -->
        <!-- the aside section will collapse and a "more button will be shown to you." -->
        <!-- clicking on this more button, you will be shown the aside section 2  -->
        <!-- its position will be absolute at lower resolutions -->
        <!-- this is the label for that more button -->
        <label for="more"><i class="fas fa-angle-double-left"></i>More</label>
        <!-- this is that more button -->
        <!-- and this is the check box. this will always be hidden -->
        <!-- check the stylesheet_main.css when the label is clicked, this checkbox will be checked -->
        <!-- which will invoke the aside section 2 on lower resolutions -->
        <input type="checkbox" id="more">
        <!-- here starts the section 2 of our page -->
        <aside class="aside section-2">
            <!-- this is the section heading part. the heading will be static -->
            <div class="heading">
                <h1>Playlist</h1>
                <h4>
                    <a href="#queue-option-box">Queue <i class="fas fa-chevron-circle-down"></i></a>
                </h4>
            </div>
            <!-- this is the queue box which will be shown when the user clicks on the Queue button -->
            <!-- it will have 3 options, playlists, favourite songs and Close button. it will close when one clicks on the close button. -->
            <div class="queue-options" id="queue-option-box">
                <p><a href style="color:#007bff; font-weight:bolder;">Playlists</a></p>
                <hr>
                <p><a href style="color:#007bff; font-weight:bolder;">Favourite songs</a></p>
                <hr>
                <p><a href="#" style="color:red; font-weight:bolder;">Close</a></p>
            </div>
            <!-- this is the content of the playlist. it will be dynamic. -->
            <div class="playlist-content">
                <!-- first playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <!-- index -->
                        <div style="margin-right:4px;">
                            01
                        </div>
                        <div class="coverer">
                            <!-- coverer class is for those items which when hovered will show an effect -->
                            <!-- in this effect, when the user hovers on the item, it will show black background -->
                            <!-- with opacity value less than 1 and a play button icon at the center -->
                            <img src="media/playlist/austin-neill-kKlVSrFbjYY-unsplash.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <!-- name and author of the song -->
                        <div>
                            <div>
                                Alone
                            </div>
                            <p>
                                Alan Walker
                            </p>
                        </div>
                    </div>
                    <!-- like button -->
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- second playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            02
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/after.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Alone Again
                            </div>
                            <p>
                                Weeknd
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- third playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            03
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                White Iverson
                            </div>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- fourth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            04
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Go Flex
                            </div>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- fifth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            05
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Better Now
                            </div>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- sixth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            06
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/after.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Hardest To Love
                            </div>
                            <p>
                                Weeknd
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- seventh playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            07
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/beer.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Pysco
                            </div>
                            <p>
                                Post Malone
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- eighth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            08
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/beer.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Rockstar
                            </div>
                            <p>
                               Post Malone & 21 Savage
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- ninth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            09
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Deja Vu
                            </div>
                            <p>
                                Post Malone & Justin Beiber
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- tenth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            10
                        </div>
                        <div class="coverer">
                            <img src="media/popular artists/billie eilish.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Bad Guy
                            </div>
                            <p>
                                Billie Eilish
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- eleventh playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            11
                        </div>
                        <div class="coverer">
                            <img src="media/songs/sorry.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Sorry
                            </div>
                            <p>
                                Justin Bieber
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- twelfth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            12
                        </div>
                        <div class="coverer">
                            <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/166e992b-4534-4bd8-bb41-3be395f82cde/daojfrr-facc1540-40b8-455f-b8b6-ba4f14738b32.png/v1/fill/w_894,h_894,q_75,strp/bts___wings_by_goldendesigncover-daojfrr.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwic3ViIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl0sIm9iaiI6W1t7InBhdGgiOiIvZi8xNjZlOTkyYi00NTM0LTRiZDgtYmI0MS0zYmUzOTVmODJjZGUvZGFvamZyci1mYWNjMTU0MC00MGI4LTQ1NWYtYjhiNi1iYTRmMTQ3MzhiMzIucG5nIiwid2lkdGgiOiI8PTg5NCIsImhlaWdodCI6Ijw9ODk0In1dXX0.VXwplpd8rbngUYyW306GbKo_PdH8B_g3gw3fr1V0Mes">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Golden
                            </div>
                            <p>
                                BTS
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
            </div>
        </aside>
    </main>
    <!-- main part of the page is over. -->
    <!-- this is the footer part. -->
    <!-- its position will be fixed to the screen bottom. -->
    <footer>
        <div class="active-song-description">
            <!-- song image -->
            <div id="song-image">
                <img src="media/latest english/roar.jpg">
            </div>
            <!-- song name and author -->
            <div class="song-desc">
                <div>
                    Imagine by John
                </div>
                <div>
                    John Lenon
                </div>
                <!-- heart icon and ban icon -->
            </div>
            <div class="heart-and-ban-icon">
                <span>
                    <i class="far fa-heart"></i>
                </span>
                <span>
                    <i class="fas fa-ban"></i>
                </span>
            </div>
        </div>
        <!-- these are the main player controls -->
        <div class="player">
            <div class="controls">
                <div><i class="fas fa-random"></i></div>
                <div><i class="fas fa-step-backward"></i></div>
                <div><i class="fas fa-pause-circle"></i></div>
                <div><i class="fas fa-step-forward"></i></div>
                <div><i class="fas fa-redo"></i></div>
            </div>
            <!-- this is the slider -->
            <div id="slider">
                <!-- current time -->
                <div class="time">
                    1:39
                </div>
                <div class="slidecontainer">
                    <input type="range" min="0" max="100" value="0" class="slider" id="myRange">
                </div>
                <!-- total time -->
                <div class="time">
                    4:44
                </div>
            </div>
        </div>
        <!-- other icons including the volume slider and all -->
        <div class="extras">
            <div>
                <i class="fas fa-list-ul"></i>
            </div>
            <div>
                <i class="fas fa-laptop"></i>
            </div>
            <div>
                <i class="fas fa-volume-up"></i>
            </div>
            <div class="slidecontainer" style="width:30%;">
                <input type="range" min="0" max="100" value="0" class="slider" id="myRange" style="margin-top:0px;">
            </div>
            <div>
                <i class="fas fa-expand-alt"></i>
            </div>
        </div>
    </footer>
</body>

</html>
 


