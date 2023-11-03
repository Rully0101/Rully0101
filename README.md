<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
    <div style="text-align:center;"><h1>Rully路漓</h1></div>
    <style type="text/css">
        .test_1 {
        text-align: center;
        }
        .test_2 {
        text-align: center;
        color: #F00;
        }
        </style>
        <style type="text/css">
            #menu {
            /* 選單大小 */
            width: 1920px;
            height: 135px;
            }
            #menu ul {
            /* 取消ul樣式符號 */
            list-style-type: none;
            /* 重設ul邊界與留白為零 */
            margin: 0;
            padding: 0;
            /* 內有浮動元件時，需設overflow才會自動調整大小 */
            overflow: auto;
            }
            #menu ul li {
            /* 利用float讓第一層li水平排列 */
            float: left;
            }
            /* 解決IE6條列式餘白問題*/
            * html #menu ul li {
            display: inline;
            }
            #menu ul li a {
            /* 將a改為區塊元件，以便指定寬高 */
            display: block;
            /* 這邊也要設float，否則IE6會以100%寬度顯示 */
            float: left;
            /* 固定高度 */
            height: 33px;
            width: 100px;
            text-align: center;
            }
            #menu ul li ul {
            /* 讓第二層ul跳脫文件流以利定位 */
            position: absolute;
            /* 固定寬度 */
            width: 100px;
            /* 避免出現捲軸 */
            overflow: visible;
            /* 讓ul與母階層li相同位置 */
            clear: left;
            margin-top: 30px;
            margin-right: 0;
            margin-bottom: 0;
            margin-left: 0;
            }
            /* 修正IE7絕對定位差異 */
            *:first-child+html #menu ul li ul {
            margin-top: 0;
            }
            /* 修正IE6絕對定位差異 */
            * html #menu ul li ul {
            margin-top: 0;
            }
            #menu ul li ul li {
            /* 覆寫繼承自第一層的浮動設定 */
            float: none;
            text-align: center;
            }
            #menu ul li ul li a {
            /* 覆寫繼承自第一層的浮動設定 */
            float: none;
            width: 100%;
            /* 註：display、height、padding繼承第一層的設定 */
            }
            #menu ul li ul li ul {
            margin-top: -30px;
            margin-right: 0;
            margin-bottom: 0;
            margin-left: 100px;
            width: 100%;
            }
            /* 修正IE7絕對定位差異 */
            *:first-child+html #menu ul li ul li ul {
            margin-top: -30px;
            }
            #menu ul li ul li ul li {
            /* width、float繼承第二層，免設定 */
            }
            #menu ul li ul li ul li a {
            /* width、float繼承第二層，免設定 */
            }
            /* ---------- 隱藏與顯示階層 ---------- */
            #menu ul li ul {
            /* 預先隱藏第二層 */
            visibility: hidden;
            }
            #menu ul li:hover ul {
            /* 觸動第一層時，顯示第二層 */
            visibility: visible;
            }
            #menu ul li:hover ul li ul {
            /* 顯示第二層時，隱藏第三層，避免同時彈出 */
            visibility: hidden;
            }
            #menu ul li ul li:hover ul {
            /* 觸動第二層時，顯示第三層 */
            visibility: visible;
            }
            #menu ul li ul li:hover ul li ul {
            /* 顯示第三層時，隱藏第四層，避免同時彈出 */
            visibility: hidden;
            }
            #menu ul li ul li ul li:hover ul {
            /* 觸動第三層時，顯示第四層 */
            visibility: visible;
            }
            /* ---------- 以下為美化用，非必需 ---------- */
            /* 預設字體 */
            #menu {
            font-size: 12px;
            }
            /* 第一層ul背景色彩與邊框 */
            #menu ul {
            background: #b267f0;
            }
            /* 第一層a字型 */
            #menu ul li a {
            color: #FFF;
            text-decoration: none;
            line-height: 35px;
            }
            /*第二層ul背景色彩與邊框 */
            #menu ul li ul {
            background: #C6C;
            }
            /* 第二層a字型 */
            #menu ul li ul li a {
            font-size: 12px;
            color: #F66;
            text-decoration: none;
            }
            /* 觸動第一層li時，改變背景色 */
            #menu ul li:hover,
            #menu ul li a:hover {
            background: rgb(72, 255, 0);
            }
            #menu ul li:hover a {
            color: rgb(0, 0, 0);
            }
            /* 觸動第二層以上li時改變背景色 */
            #menu ul li ul li:hover,
            #menu ul li ul li a:hover {
            background: #099;
            }
            </style>
            <style>
                div{
                    position: relative;
                }
                h1{font-size: 32px;
                    color: rgb(0, 0, 0);
                    position:absolute;
                    top:10px;
                    left:10px;}
                    h2{font-size: 32px;
                    color: rgb(0, 0, 0);
                    position:absolute;
                    top:0px;
                    left:310px;}
                    h3{font-size: 32px;
                    color: rgb(0, 0, 0);
                    position:absolute;
                    top:500px;
                    left:0px;}
                    h4{font-size: 32px;
                    color: rgb(0, 0, 0);
                    position:absolute;
                    top:489px;
                    left:960px;}
                </style>
        <div class="test_1"><img src="C:\Users\a4862\Desktop\web\斗內.gif" width="200" height="200" /><br /><b>歡迎來到本兔的網站</b></div>
        <body>
            <div id="menu">
            <ul>
            <li> <a href="#">個人網站</a>
            <ul>
            <li><a href="https://twitter.com/RuLuDo0101">路漓的X</a></li>
            <li><a href="https://vrchat.com/home/user/usr_8b6fa9b8-85ed-45e6-a7fd-741006c83c8d">路漓的VRCHAT</a></li>
            <li><a href="https://www.facebook.com/nitanokou">路漓的A芙逼</a></li>
            </ul>
            </li>
            <li> <a href="#">個人介紹</a>
            <ul>
            <li><a href="#">人物設定</a></li>
            <li><a href="#">Rully路漓的推</a></li>
            </ul>
            </li>
            <li> <a href="https://www.youtube.com/channel/UCbhfyYyihYCujpG55YAqzFA">Youtuber頻道</a>
            <div></div>
            </div>
            </body> 
            <body>
                <div>
                    <img src="C:\Users\a4862\Desktop\web\12.png" alt="">
                    <h1><img src="C:\Users\a4862\Desktop\web\Tifiy&Rully.png" width="300" height="300"></h1>
                    <h2>
                    <br>從兔窩誕生的兔子史萊姆 名叫Rully路漓也可以叫酪梨</br>
                    <br>喜歡在VR的世界玩著槍戰</br>
                    <br>下面是Rully路漓大推的Vtuber Serafina & Kyou 他們唱的歌好好聽</br>
                    </h2>
                    <h3><video width="960" height="480" controls>
                        <source src="C:\Users\a4862\Desktop\web\Thirsty.mp4" type="video/mp4">
                    </video>
                    </h3>
                    <h4><video width="960" height="480" controls>
                        <source src="C:\Users\a4862\Desktop\web\Iwillshowyou.mp4" type="video/mp4">
                    </video>
                    </h4>
                </div>
            </body>
        <div class="test_2">本網站授權自Rully路漓 本魔獸所有</div>
        </body>
</head>
