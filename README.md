<!DOCTYPE html>
<html>

<head>
    <title>Layout</title>
    <link rel="stylesheet" type="text/css" href="Mystyle.css" />
    <style type="text/css">
        @font-face {
            font-family: 'QuicksandBook';
            src: url('fonts/Quicksand_Book-webfont_eot');
            src: url('fonts/Quicksand_Book-webfont.eot?iefix') format('embedded-opentype'),
            url('fonts/Quicksand_Book-webfont.woff') format('woff'),
            url('fonts/Quicksand_Book-webfont.ttf') format('truetype'),
            url('fonts/Quicksand_Book-webfont.svg#QuicksandBook') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        body {
            color: #ffffff;
            background: #413f3b url('bg.jpg');
            font-family: Georgia, "Times New Roman", Times, serif;
            font-size: 90%;
            margin: 0px;
            text-align: center;
        }

        a {
            color: #b5c1ad;
            text-decoration: none;
        }

        a:hover {
            color: #ffffff;
        }
        .header {
            background-image: url("bgheader.jpg");
            padding: 0px 0px 0px 0px;
            height: 100px;
            position: fixed;
            top: 0px;
            width: 100%;
            z-index: 50;
        }

        .nav {
            float: right;
            font-family: QuicksandBook, Helvetica, Arial, sans-serif;
            padding: 45px 0px 0px 0px;
            text-align: right;
        }
        a {
            color: #b5c1ad;
            text-decoration: none;
        }
        a:hover {
            color: #ffffff;
        }

        .header {
            background-image: url("bg-header.jpg");
            padding: 0px 0px 0px 0px;
            height: 100px;
            position: fixed;
            top: 0px;
            width: 100%;
            z-index: 50;
        }

        .nav {
            float: right;
            font-family: QuicksandBook, Helvetica, Arial, sans-serif;
            padding: 45px 0px 0px 0px;
            text-align: right;
        }

        .wrapper {
            width: 960px;
            margin: 0px auto;
            background-image: url("bg-triangle.png");
            background-repeat: no-repeat;
            background-position: 0px 0px;
            text-align: left;
        }

        .logo {
            margin-bottom: 20px;
        }

        h1,
        h2 {
            font-family: QuicksandBook, Helvetica, Arial, sans-serif;
            font-weight: normal;
            text-transform: uppercase;
        }

        h1 {
            font-size: 240%;
            margin-top: 140px;
        }

        .date {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 75%;
            color: #b5c1ad;
        }

        .intro {
            clear: left;
            font-size: 90%;
            line-height: 1.4em;
        }

        .main-story {
            background-image: url("triangles.png");
            background-repeat: no-repeat;
            background-position: 122px 142px;
            height: 570px;
        }

        .more-articles {
            border-top: 1px solid #ffffff;
            padding: 10px;
        }

        .more-articles p {
            border-bottom: 1px solid #807c72;
            padding: 5px 0px 15px 0px;
            font-size: 80%;
        }

        .more-articles p:last-child {
            border-bottom: none;
        }

        .footer {
            clear: both;
            background: rgba(0, 0, 0, 0.2);
            padding: 5px 10px;
        }

        .footer p {
            font-family: Helvetica, Arial, sans-serif;
            font-size: 75%;
            text-align: right;
        }

        .footer a {
            color: #807c72;
        }
    </style>
</head>

<body>
    <div class="header">
        <div class="container_12">
            <div class="grid_5">
                <img src="logo.png" alt="Pedal Faster - The mordern bicycle magazine" width="216" height="37" class="logo" />
                <img src="header-triangle.png" alt="" width="116" height="100" />
            </div>
            <div class="nav grid_7">
                <a href="">home</a> / <a href="">news</a> / <a href="">archives</a> / <a href="">contact</a>
            </div>
        </div>
    </div>
    <div class="wrapper">
        <div class="main-story container_12">
            <div class="grid_6 push_6">
                <h1><a href="">Fixed Gear Forever</a></h1>
            </div>
            <div class="intro grid_3 push_9">
                <p>16 APRIL 2011</p>
                <p>The veloheld combines minimalist design with superb quality. Devoid of excessive graphics and hear shift components,
                    The veloheld product range delights us with its beauty and simplicity. The black and white (yin and yang?) bicycles
                    feature a short wheelbase, a single gear and a narrow handlebar... All you need to explore the city streets</p>
                    <p>For those who want to create their bike themselves, the veloheld frames come in three sizes and two colours and are
                        the perfect starting point. <a href="">Continue reading...</a></p>
            </div>
        </div>
    </div>

    <div class="more-articles container_12">
        <h2 class="grid_12"><a href="">More <Article></Article></a></h2>
        <div class="grid_3">
            <img src="more1.jpg" alt="The road ahead" width="220" height="125" />
            <p><a href="">On the Road: From the fixed gear fanatic's point of view</a></p>
            <p><a href="">Brand History: Pashley Cycles - hand-built in England</a></p>
            <p><a href="">Fremes Wars: Innovations in cycle manufacture and repair</a></p>
        </div>
        <div class="grid_3">
            <img src="more2.jpg" alt="Sketchbook" width="220" height="125" />
            <p><a href="">Touring Diary: A sketchbook in your basket</a></p>
            <p><a href="">Top Ten Newcomers for 2012: A peek at what's to come</a></p>
            <p><a href="">InnerTube: The best cycling videos on the web</a></p>
        </div>
        <div class="grid_3">
            <img src="more3.jpg" alt="Repair shop sign" width="220" height="125" />
            <p><a href="">Product Review: All baskets were not created equal</a></p>
            <p><a href="">Going Public: Out & about with the founder of Public</a></p>
            <p><a href="">Cycle Lane Defence: Know your rights</a></p>
        </div>
        <div class="grid_3">
            <img src="more4.jpg" alt="Schwinn Spitfire" width="220" height="125" />
            <p><a href="">Bicycle Hall of Fame: The 1958 Schwinn Spitfire</a></p>
            <p><a href="">Reader Survey: Share Your Thoughts with us!</a></p>
            <p><a href="">Chain Gang: The evolution of the humble bike chain</a></p>
        </div>
    </div>
    
    <div class="footer clearfix">
        <div class="container_12">
            <p> class="grid_12"><a href="">Legal Information</a> | <a href="">Privacy Policy</a> | <a href="">Copyright &copy; Fpt Aptech 2022</a></p>
        </div>
    </div>
</body>
</html>