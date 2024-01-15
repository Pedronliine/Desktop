<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta content="width=device-width,initial-scale=1,maximum-scale=1.0,user-scalable=no" name="viewport">
    <link rel="stylesheet" type="text/css" href="assets/index.css">
    <link rel="stylesheet" type="text/css" href="assets/desktop.css">
</head>

<body>
    <div class="desktop">
        <div class="icon faisal-akhtar">
            <img src="assets/documents.png">
            <div class="icon-name">Faisal Akhtar</div>
        </div>
        <div class="icon my-computer">
            <img src="assets/computer.png">
            <div class="icon-name">My Computer</div>
        </div>
        <div class="icon my-network">
            <img src="assets/network.png">
            <div class="icon-name">My Network</div>
        </div>
        <div class="icon note-pad">
            <img src="assets/notepad.png">
            <div class="icon-name">ReadME.txt</div>
        </div>
        <div class="icon recycle-bin">
            <img src="assets/recycle.png">
            <div class="icon-name">Recycle Bin</div>
        </div>
    </div>

    <div class="window">
        <div class="title-bar">
            <div><img src="assets/notepad.png"> ReadME.txt</div>
            <div class="controls">
                <button class="cls"></button>
                <button class="max"></button>
                <button class="min"></button>
            </div>
        </div>
        <div class="menu-bar">
            <span>File</span>
            <span>Edit</span>
            <span>Format</span>
            <span>View</span>
            <span>Help</span>
        </div>
        <textarea></textarea>
    </div>

    <div class="taskbar">
        <div class="start-button"><img src="assets/logo.svg"> start</div>

        <div class="opened-tabs">
            <div class="open-tab" onclick="window.open('https://faisalakhtar.github.io/')"><img src="assets/documents.png"> Faisal Akhtar</div>
            <div class="open-tab" onclick="window.open('https://github.com/faisalAkhtar/')"><img src="assets/computer.png"> My Computer</div>
            <div class="open-tab" onclick="window.open('https://twitter.com/faisallakhtarr/')"><img src="assets/network.png"> My Network</div>
            <div class="open-tab readme active"><img src="assets/notepad.png"> ReadME.txt</div>
        </div>

        <div class="time">11:20 PM</div>
    </div>

    <script src="assets/desktop.js"></script>
</body>
</html>
