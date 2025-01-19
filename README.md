<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF=8">
    <meta http-equiv="x-ua-compatible" content="IE=edge">
    <Meta name="VIEWPORT" CONTENT="width=device width,internal scale=1.0">
    <title>document</title>
    <link rel="stylesheet" href="main.css">
</head>
</head>


<head>

    <meta charset="utf-8">

    <title>Friday Night Funkin': Vs Sonic.exe 2</title>

    <link rel="canonical" href="https://kbhgames.com/game/friday-night-funkin-vs-sonic-exe-2-0" />

    <meta id="viewport" name="viewport"
        content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <meta name="apple-mobile-web-app-capable" content="yes">


    <link rel="shortcut icon" type="image/png" href="https://fnf.kdata1.com/sonic.exe/2.6/favicon.png">


    <script type="text/javascript" src="Sonic.js"></script>

    <script>
        window.addEventListener("touchmove", function (event) { event.preventDefault(); }, { capture: false, passive: false });
        if (typeof window.devicePixelRatio != 'undefined' && window.devicePixelRatio > 2) {
            var meta = document.getElementById("viewport");
            meta.setAttribute('content', 'width=device-width, initial-scale=' + (2 / window.devicePixelRatio) + ', user-scalable=no');
        }
    </script>

    <style>
        html,
        body {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
        }

        #openfl-content {
            background: #000000;
            width: 100%;
            height: 100%;
        }

        @font-face {
            font-family: 'EurostileTBla';
            src: url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/EurostileTBla.eot?') format('embedded-opentype'),
                url('assets/fonts/EurostileTBla.woff') format('woff'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/EurostileTBla.ttf') format('truetype'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/EurostileTBla.svg') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'Impact';
            src: url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/impact.eot?') format('embedded-opentype'),
                url('assets/fonts/impact.woff') format('woff'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/impact.ttf') format('truetype'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/impact.svg') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'Pixel Arial 11 Bold';
            src: url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/pixel.eot?') format('embedded-opentype'),
                url('assets/fonts/pixel.woff') format('woff'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/pixel.otf') format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'Sonic CD Menu Font Regular';
            src: url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/sonic-cd-menu-font.eot?') format('embedded-opentype'),
                url('assets/fonts/sonic-cd-menu-font.woff') format('woff'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/sonic-cd-menu-font.ttf') format('truetype'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/sonic-cd-menu-font.svg') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'Tahoma Bold';
            src: url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/tahoma-bold.eot?') format('embedded-opentype'),
                url('assets/fonts/tahoma-bold.woff') format('woff'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/tahoma-bold.ttf') format('truetype'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/tahoma-bold.svg') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'VCR OSD Mono';
            src: url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/vcr.eot?') format('embedded-opentype'),
                url('assets/fonts/vcr.woff') format('woff'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/vcr.ttf') format('truetype'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/assets/fonts/vcr.svg') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'Nokia Cellphone FC Small';
            src: url('https://fnf.kdata1.com/sonic.exe/2.6/flixel/fonts/nokiafc22.eot?') format('embedded-opentype'),
                url('flixel/fonts/nokiafc22.woff') format('woff'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/flixel/fonts/nokiafc22.ttf') format('truetype'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/flixel/fonts/nokiafc22.svg') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'Monsterrat';
            src: url('https://fnf.kdata1.com/sonic.exe/2.6/flixel/fonts/monsterrat.eot?') format('embedded-opentype'),
                url('flixel/fonts/monsterrat.woff') format('woff'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/flixel/fonts/monsterrat.ttf') format('truetype'),
                url('https://fnf.kdata1.com/sonic.exe/2.6/flixel/fonts/monsterrat.svg') format('svg');
            font-weight: normal;
            font-style: normal;
        }
    </style>

</head>

<body>

    <noscript>This webpage makes extensive use of JavaScript. Please enable JavaScript in your web browser to view this
        page.</noscript>

    <div id="openfl-content"></div>

    <script type="text/javascript">
        lime.embed("Sonic", "openfl-content", 1280, 720, { parameters: {} });
    </script>


    <link rel="stylesheet" href="../../assets/css.css" type="text/css" media="all" />
    <script type="text/javascript" src="../../assets/js.js"></script>
</body>

</html>
