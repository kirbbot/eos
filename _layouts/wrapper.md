<!DOCTYPE html>
<html lang="en">
        <head>
                <!-- Global site tag (gtag.js) - Google Analytics -->
                <script async src="https://www.googletagmanager.com/gtag/js?id=UA-172226953-1"></script>
                <script>
                    window.dataLayer = window.dataLayer || [];
                    function gtag(){dataLayer.push(arguments);}
                    gtag('js', new Date());
                    gtag('config', 'UA-172226953-1');
                </script>
                <meta charset="utf-8">
                <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=yes">
                <title>EOS</title>
                <link rel="stylesheet" type="text/css" href="./styles.css">
                <script src="./js/jquery.v3.4.1.min.js"></script>
                <script src="./js/topics.js"></script>
                <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
                <script type="text/javascript" src="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>
                <script src="./js/fitvid.js"></script> 
                <script src="./js/scripts.js"></script> 
        </head>
        <body>
                <header id="Header_Main">
                        <a id="Logo_Main" href="index.html"><img src="./img/logo.png"></a>
                        <ul id="Nav_Main">
                                <li>
                                        <a href="demo.html">Demo</a>
                                </li>
                                <li>
                                        <a href="community.html">Community</a>
                                        <ul>
                                                <li>
                                                        <p>Sample Community Pages</p>
                                                </li>
                                                <li>
                                                        <a href="community-abuse.html">Abuse</a>
                                                </li>
                                                <li>
                                                        <a href="community-healthcrisis.html">Health Crisis</a>
                                                </li>
                                                <li>
                                                        <a href="community-human_trafficking.html">Human Trafficking</a>
                                                </li>
                                        </ul>
                                </li>
                                <li>
                                        <a href="about.html">About</a>
                                </li>
                                <li>
                                        <a href="faq.html">FAQ</a>
                                </li>
                                <li>
                                        <a id="Nav_Main-Profile" href="form-signup.html">Login / Sign Up</a>
                                        <ul>
                                                <li>
                                                        <p>Sample Profiles</p>
                                                </li>
                                                <li>
                                                        <a href="profile.html">Amanda</a>
                                                </li>
                                                <li>
                                                        <a href="profile-andrew.html">Andrew</a>
                                                </li>
                                                <li>
                                                        <a href="profile-newdawn.html">New Dawn</a>
                                                </li>
                                        </ul>
                                </li>
                        </ul>
                </header>
                <div class="content">
                        {{content}}
                </div>
                {% include footer.html %}
        </body>
</html>