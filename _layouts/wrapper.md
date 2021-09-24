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
                <script src="./js/scripts.js"></script>
        </head>
        <body>
                <header id="Header_Main">
                        <a id="Logo_Main" href="index.html"><img src="./img/logo.png"></a>
                        <nav id="Nav_Main">
                                <a href="community.html">Community</a>
                                <a href="about.html">About</a>
                                <a href="faq.html">Support</a>
                                <a href="profile.html">Login / Sign Up</a>
                        </nav>
                </header>
                <div class="content">
                        {{content}}
                </div>
                <footer>
                </footer>
        </body>
</html>