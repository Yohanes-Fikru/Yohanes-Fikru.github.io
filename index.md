<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="materialize/css/materialize.css">
    <title>Resume</title>

    <style>
        @font-face {
            font-family: 'Material Icons';
            font-style: normal;
            font-weight: 400;
            src: url(iconfont/MaterialIcons-Regular.eot);
            /* For IE6-8 */
            src: local('Material Icons'),
                local('MaterialIcons-Regular'),
                url(iconfont/MaterialIcons-Regular.woff2) format('woff2'),
                url(iconfont/MaterialIcons-Regular.woff) format('woff'),
                url(iconfont/MaterialIcons-Regular.ttf) format('truetype');
        }

        .material-icons {
            font-family: 'Material Icons';
            font-weight: normal;
            font-style: normal;
            font-size: 24px;
            /* Preferred icon size */
            display: inline-block;
            line-height: 1;
            text-transform: none;
            letter-spacing: normal;
            word-wrap: normal;
            white-space: nowrap;
            direction: ltr;

            /* Support for all WebKit browsers. */
            -webkit-font-smoothing: antialiased;
            /* Support for Safari and Chrome. */
            text-rendering: optimizeLegibility;

            /* Support for Firefox. */
            -moz-osx-font-smoothing: grayscale;

            /* Support for IE. */
            font-feature-settings: 'liga';
        }

        /* fit images to containers/grids */
        .img-responsive {
            max-width: 100%;
            height: auto;
            object-fit: cover;
        }

        /* right-left padding for centering content (alternative to container) */
        .pad {
            padding-left: 4.5vw;
            padding-right: 4.5vw;
        }

        /* top-bottom padding for pictures */
        .pad-img {
            padding-top: 0.3vw;
            padding-bottom: 0.3vw;
        }

        /* Padding of the content for the side-nav */
        header,
        main,
        footer {
            padding-left: 300px;
        }


        @media only screen and (max-width : 992px) {

            header,
            main,
            footer {
                padding-left: 0;
            }
        }

        /* For the footer to stick to the bottom */
        body {
            display: flex;
            min-height: 100vh;
            flex-direction: column;
        }

        main {
            flex: 1 0 auto;
        }
    </style>

</head>

<body>

    <header>
        <!-- Side-nav (large screens) -->
        <ul id="slide-out" class="sidenav sidenav-fixed grey lighten-2">
            <div class="row center">
                <img src="img/profile/epic.jpg" class="responsive-img">
            </div>

            </li>
            <h4 class="center">Yohanes Fikru</h4>
            <li><a class="waves-effect waves-light" href="index.html"><i
                        class="material-icons">format_align_center</i>Resume</a></li>
            <li><a class="waves-effect waves-light" href="activities.html"><i
                        class="material-icons">assistant_photo</i>Clubs and Activities</a></li>
            <li><a class="waves-effect waves-light" href="portfolio.html"><i class="material-icons">code</i>Projects</a>
            </li>

            <li><a class="waves-effect waves-light" href="contact.html"><i
                        class="material-icons">contacts</i>Contact</a></li>
            <!-- a row of social media icons -->
            <div class="row">

            </div>
            <li><a href="#"></a></li>

        </ul>
        <!-- for large screens: page indicator -->
        <div class="navbar hide-on-med-and-down">
            <nav class="nav-wrapper grey darken-4 z-depth-4">
                <div class="pad">
                    <a href="home.html" class="brand-logo">Resume</a>
                </div>
            </nav>
        </div>
        <!-- for med and small screens -->
        <div class="navbar hide-on-large-only">
            <nav class="nav-wrapper grey darken-4 z-depth-4">
                <div class="container">
                    <a href="home.html" class="brand-logo" style="padding-left: 1vw">Yohanes Fikru</a>
                    <a href="" class="sidenav-trigger" data-target="mobile-menu">
                        <i class="material-icons">menu</i>
                    </a>
                    <ul class="sidenav grey lighten-2" id="mobile-menu">
                        <div class="row center">
                            <img src="img/profile/epic.jpg" class="responsive-img">
                        </div>
                        </li>
                        <h4 class="center black-text">Yohanes Fikru</h4>
                        <li><a class="waves-effect waves-light" href="index.html"><i
                                    class="material-icons">format_align_center</i>
                                Resume</a></li>
                        <li><a class="waves-effect waves-light" href="activities.html"><i
                                    class="material-icons">assistant_photo</i>Clubs and Activities</a></li>
                        <li><a class="waves-effect waves-light" href="portfolio.html"><i class="material-icons">code</i>
                                Projects</a></li>
                        <li><a class="waves-effect waves-light" href="contact.html"><i
                                    class="material-icons">contacts</i>
                                Contact</a></li>
                        <!-- a row of social media icons -->
                        <div class="row">

                        </div>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                    </ul>
                </div>
            </nav>
        </div>
    </header>

    <main class="grey darken-4">

        <div class="row">
            <div class="col l6 m6">
                <!-- Education -->
                <div class="card transparent white-text z-depth-0">
                    <div class="card-content">
                        <h3 class="blue-text"><i class="material-icons">school</i> Education</h1>
                            <div class="card-title">Bole Preparatory School</div>
                            <p>11 & 12 </p>
                            <div class="card-title">Adama Science and Technology University</div>
                            <p>Bachelor of Computer Science and Engineering (since 2016)</p>
                    </div>
                </div>
                <!-- Certifications -->
                <div class="card transparent white-text z-depth-0">
                    <div class="card-content">
                        <h3 class="green-text"><i class="material-icons">beenhere</i> Certifications</h1>
                            <div class="card-title">Mobile Maintanance, SATCOM</div>
                            <p> 2012</p>
                            <div class="card-title">Chess Coach, Addis Ababa Chess Federation</div>
                            <p>1st Level (2015)</p>
                    </div>
                </div>
                <!-- Achivements -->
                <div class="card transparent white-text z-depth-0">
                    <div class="card-content">
                        <h3 class="yellow-text text-darken-2"><i class="material-icons">grade</i> Achivements</h3>
                        <div class="card-title">National Champion, 3rd Ethiopian Colligite Programming Contest</div>
                        <p> Hosted by Adama Science and Technology University</p>
                        <p>September, 2018</p>
                        <div class="card-title">Best Delegate, Ethio-MUN Conference</div>
                        <p>Hosted by Mekele University</p>
                        <p>May, 2017</p>
                    </div>
                </div>
            </div>
            <!-- Work Summery -->
            <div class="col l6 m6">
                <div class="card transparent white-text z-depth-0">
                    <div class="card-content">
                        <h3 class="amber-text text-darken-4"><i class="material-icons">subject</i> Work
                            Summery</h1>
                            <div class="card-title">Freelance Market Research</div>
                            <p> Orange Switch, 2017-2018</p>
                            <p class="grey-text">
                                Worked in Adama going to Sales points of the client and collecting overall
                                information.
                            </p>
                            <div class="card-title">Intern - Unity Developer</div>
                            <p>Eternal Media and Communication, 2019</p>
                            <p class="grey-text">
                                Using Unity Game Engine to create games and content for Virtual Reality devices
                            </p>
                    </div>
                </div>
                <!-- Proffesional Skills -->
                <div style="padding-left: 2vw">
                    <h3 class="cyan-text text-darken-2"><i class="material-icons">work</i> Professional Skills</h3>
                    <div class="row white-text">
                        <div class="col l6 m6">
                            <p>Leadership</p>
                            <p>Web Design</p>
                            <p>HTML, CSS3 & JavaScript</p>
                            <p>Materiallize CSS framework</p>
                        </div>
                        <div class="col l6 m6">
                            <p>Photography</p>
                            <p>Chess Coaching</p>
                            <p>Game Development (Unity)</p>
                            <p>C++ programming</p>
                        </div>
                    </div>
                </div>
                <!-- Leadership Positions -->
                <div class="white-text" style="padding-left: 2vw">
                    <h3 class="purple-text text-lighten-1">
                        <i class="material-icons">golf_course</i> Leadership Positions
                    </h3>
                    <p>
                        <div class="purple-text text-lighten-2">
                            Vice-President,
                        </div>
                        Computer Science and Engineering Club (CSEC-ASTU)
                    </p>
                    <p>
                        <div class="purple-text text-lighten-2">
                            Cheif of Staff,
                        </div>
                        Model United Nations (MUN-ASTU)
                    </p>
                    <div class="row">
                        <div class="col l6 m6">
                            <p>
                                <div class="purple-text text-lighten-2">
                                    Student Representative,
                                </div>
                                Student Councel, High School
                            </p>
                        </div>
                        <div class="col l6 m6">
                            <p>
                                <div class="purple-text text-lighten-2">
                                    President,
                                </div>
                                Mini Media, High School
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <footer>
        <!-- Bottom Footer -->
        <div class="footer-copyright black">
            <div class="container center white-text">
                Developed in Sep 2019 by Yohanes Fikru.
                <a class="waves-effect waves-light btn-flat modal-trigger black" href="#dev_info">Click Here for
                    More</a>
            </div>
        </div>

        <!-- Developer Modal -->
        <div id="dev_info" class="modal bottom-sheet">
            <div class="modal-content white-text grey darken-4 center">
                <h4>Made with: <a href="#">Materialize CSS</a></h4>
            </div>
        </div>
    </footer>


    <!-- js scripts -->
    <script src="https://code.jquery.com/jquery-3.4.1.js"></script>
    <script src="materialize/js/materialize.js"></script>

    <script>
        $('.sidenav').sidenav();
        $('.materialboxed').materialbox();
        $('.modal').modal();


    </script>
</body>

</html>