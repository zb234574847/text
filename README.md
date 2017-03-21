<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>小薇作业6</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: #cccccc;
        }

        .main {
            width: 980px;
            height: 1386px;
            background-color: #fff;
        }

        .one {
            width: 892px;
            height: 61px;
            background-color: #ffffff;
            margin: 0 auto 10px auto;
            border-bottom: 2px solid #938e8c;
            box-sizing: border-box;
        }

        .one_1 {
            background-color: #d45d5c;
            width: 110px;
            height: 59px;
            float: left;
        }

        .one_2 {
            width: 782px;
            height: 61px;
            text-align: right;
            float: right;
        }

        .one_p {
            display: inline-block;
            margin-top: 40px;
            font-size: 12px;
            color: #d45d5c;
            font-family: 黑体;
        }

        .one_1 p {
            display: inline-block;
            margin-top: 40px;
            color: #ffffff;
            font-size: 12px;
            font-family: 黑体;
        }

        .two {
            width: 892px;
            height: 301px;
            margin: 0 auto 10px auto;
        }

        .two_1 {
            width: 641px;
            height: 301px;
            background-image: url(imges/1.jpg);
            float: left;
        }

        .two_1_1 {
            width: 191px;
            height: 301px;
            background-color: #75b86b;
            float: left;
            opacity: 0.6;
        }

        .two_1_2 {
            width: 191px;
            height: 301px;
            float: right;
            background-color: #d45d5c;
            opacity: 0.6;
        }

        .two_2 {
            width: 231px;
            height: 301px;
            float: right;
            border-top: 2px solid #cc8091;
            box-sizing: border-box;
        }

        .two_2_1 {
            width: 203px;
            height: 246px;
        }

        .two_2_2 {
            width: 203px;
            height: 55px;
        }

        .two_2_2_1 {
            width: 65px;
            height: 55px;
            float: left;
        }

        .two_2_2_2 {
            width: 138px;
            height: 55px;
            float: right;
        }

        .two_2_2_3 {
            width: 118px;
            height: 21px;
            float: right;
            margin-top: 10px;
        }

        .two_2_2_4 {
            width: 118px;
            height: 12px;
            float: right;

        }

        .two_2_p1 {
            font-size: 24px;
            font-family: "微软雅黑";
            text-decoration: underline;
            display: inline-block;
            margin-top: 20px;
        }

        .two_2_p2 {
            font-size: 12px;
            font-family: "楷体";
            color: #676767;
            display: inline-block;
        }

        .two_2_p3 {
            font-size: 96px;
            font-family: "微软雅黑";
            color: #75b86b;
            font-style: italic;
        }

        .two_2_p4 {
            font-size: 45px;
            color: #cc8091;
            font-family: "微软雅黑";
            display: inline-block;
            margin-left: 15px;
        }

        .two_2_p5 {
            font-size: 21px;
            font-family: "微软雅黑";
            color: #cc8091;
        }

        .two_2_p6 {
            font-size: 12px;
            font-family: "微软雅黑";
            color: #cc8091;
        }

        .three {
            width: 892px;
            height: 275px;
            margin: 0 auto 10px auto;
        }

        .three_1 {
            width: 210px;
            height: 275px;
            float: left;
        }

        .three_1_p1 {
            text-decoration: underline;
            font-size: 16px;
            color: #418c59;
            font-family: "微软雅黑";
            font-weight: bold;
        }

        .three_1_p2 {
            font-size: 12px;
            color: #767777;
            font-family: "宋体";
            margin-top: 10px;
        }

        .three_2 {
            width: 210px;
            height: 275px;
            float: left;
            margin-left: 20px;
        }

        .three_2_p1 {
            text-decoration: underline;
            font-size: 16px;
            color: #d2994f;
            font-family: "微软雅黑";
            font-weight: bold;
        }

        .three_2_p2 {
            font-size: 12px;
            color: #231815;
            font-family: "微软雅黑";
            margin-top: 10px;
            opacity: 0.7;
        }

        .three_3 {
            width: 180px;
            height: 275px;
            float: left;
            margin-left: 20px;
        }

        .three_3_1 {
            width: 180px;
            height: 100px;
            float: left;
        }

        .three_3_2 {
            width: 180px;
            height: 135px;
            float: left;

        }

        .three_3_3 {
            width: 60px;
            height: 135px;
            float: left;
            margin-top: 30px;
        }

        .three_3_4 {
            width: 120px;
            height: 175px;
            float: right;
            margin-top: 30px;
        }

        .three_3_p1 {
            text-decoration: underline;
            font-size: 16px;
            color: #cc7680;
            font-family: "微软雅黑";
            font-weight: bold;
        }

        .three_3_p2 {
            font-size: 12px;
            color: #231815;
            font-family: "微软雅黑";
            margin-top: 10px;
            opacity: 0.7;
        }

        .three_3_p3 {
            font-size: 12px;
            color: #231815;
            font-family: "微软雅黑";
            text-align: left;
        }

        .three_3_p4 {
            font-size: 12px;
            color: #cd4a48;
            font-family: "微软雅黑";
            text-align: left;
            font-style: italic;
        }

        .four {
            width: 892px;
            height: 613px;
            margin: 0 auto 10px auto;
        }

        .four_left {
            width: 415px;
            height: 613px;
            float: left;
        }

        .left_top {
            width: 415px;
            height: 162px;
        }

        .top_1 {
            width: 415px;
            height: 75px;
        }

        .top_1_left {
            width: 150px;
            height: 75px;
            float: left;
        }

        .top_1_left > p {
            font-size: 72px;
            font-family: "黑体";
            font-style: italic;
            color: #f5e327;
            font-weight: bold;
        }

        .top_1_right {
            width: 265px;
            height: 75px;
            float: right;
        }

        .top_1_right > p {
            font-size: 42px;
            font-family: "黑体";
            color: #11456b;
            font-weight: bold;
            margin-top: 30px;
        }

        .top_2 {
            width: 415px;
            height: 88px;
        }

        .top_2 > p {
            font-size: 42px;
            font-family: "黑体";
            color: #11456b;
            font-weight: bold;
            text-align: left;
        }

        #a {
            font-size: 33px;
            font-family: "黑体";
            color: #11456b;
            font-weight: bold;
        }

        .left_bottom {
            width: 415px;
            height: 450px;
            box-sizing: border-box;
            border-top: 2px solid #938e8c;
        }

        .bottom1 {
            width: 415px;
            height: 70px;
            margin-top: 10px;
        }

        .bottom1_p1 {
            font: 70px "微软雅黑";
            color: #f5e327;
            line-height: 55px;

        }

        .bottom1_p2 {
            font: 12px "宋体";
            color: #767777;
            text-align: right;
        }

        .bottom1 dl dt {
            float: left;
            height: 70px;
        }

        .bottom2 {
            width: 415px;
            height: 335px;
        }

        .bottom2 dl dt img {
            width: 200px;
            height: 315px;
            float: right;
            margin: 10px 0px 10px 0px;
        }

        .bottom2_p1 {
            font: 12px "宋体";
            color: #767777;
            text-align: left;
            text-indent: 2em;
        }

        .bottom3 p {
            font: 12px "宋体";
            color: #767777;
            text-align: right;
            text-indent: 2em;
        }

        .four_right {
            width: 458px;
            height: 613px;
            float: right;
        }

        .frt {
            width: 458px;
            height: 275px;
            background-image: url(imges/1.jpg);
            float: right;
        }

        .frt .tm {
            width: 458px;
            height: 61px;
            background: black;
            opacity: 0.6;
            margin-top: 214px;
        }

        .frt .tm .tb {
            width: 3px;
            height: 44px;
            margin: 10px 0px 0px 40px;
            float: left;
        }

        .frt .tm .tbp1 {
            font: 26px "微软雅黑";
            color: #ffffff;
            display: inline-block;
            float: left;
            margin: 15px 0px 0px 20px;
        }

        .frt .tm .tbp2 {
            font: 12px "微软雅黑";
            color: #72b16a;
            font-style: italic;
            display: inline-block;
            margin: 30px 0px 0px 10px;
        }

        .frb {
            width: 458px;
            height: 318px;
            float: left;
            margin-top: 20px;
        }

        .frb_up {
            width: 458px;
            height: 158px;
            background-color: #cccccc;
        }

        .du1 {
            width: 458px;
            height: 158px;
            float: left;
        }

        .du1 ul li {
            padding-top: 20px;
            margin-left: 40px;
            list-style-image: url("imges/text.jpg");
        }

        .s1 {
            font: 16px "宋体";
            color: #5a5b5b;
        }

        .s2 {
            font: 12px "宋体";
            color: #5a5b5b;
        }

        .frb_down {
            width: 458px;
            height: 160px;
            background-color: #cccccc;
        }

        .frb_down_left {
            width: 260px;
            height: 160px;
            float: left;
            background-color: #cd4a48;
        }

        .f1 {
            width: 80px;
            height: 160px;
            float: left;
        }

        .f1 p {
            font: 110px "微软雅黑";
            color: #ffffff;
            line-height: 160px;
            margin-left: 10px;
        }

        .f2 {
            width: 2px;
            height: 86px;
            background-color: #ffffff;
            float: left;
            margin-top: 40px;
        }

        .f3 {
            width: 178px;
            height: 160px;
            float: left;
        }

        .last1 {
            width: 168px;
            height: 90px;
            float: left;
        }

        .last1 p {
            font: 21px "黑体";
            font-style: italic;
            color: #ffffff;
            margin: 40px 0 0 10px;
        }

        .last2 {
            width: 168px;
            height: 70px;
            float: left;
        }

        .last2 p {
            font: 12px "黑体";
            color: #ffffff;
            margin-left: 10px;
        }

        .frb_down_right {
            width: 198px;
            height: 160px;
            float: right;
            background-color: #cccccc;
            position: relative;
        }

        .s3 {

            font: 72px "黑体";
            color: #d45d5c;
            position: absolute;
            top: -10px;
            left: -20px;
            display: inline-block;

        }

        .s4 {
            font: 72px "黑体";
            color: #d45d5c;
            position: absolute;
            bottom: -10px;
            right: 0px;
            display: inline-block;
        }

        .p5 {
            text-indent: 3em;
            font: 12px "黑体";
            color: #5a5b5b;
            padding: 10px 10px 0px 20px;
        }

        .five {
            width: 892px;
            height: 40px;
            margin: 0 auto 10px auto;
            box-sizing: border-box;
            border-top: 1px solid #938e8c;
            margin-top: 20px;
        }

        .five p {
            font: 12px "黑体";
            color: #d45d5c;
            text-align: right;
        }
    </style>
</head>
<body>
<div class="main">
    <div class="one">
        <div class="one_2">
            <p class="one_p">2016.03</p>
        </div>
        <div class="one_1">
            <p>ife.baidu.com</p>
        </div>
    </div>
    <div class="two">
        <div class="two_1">
            <div class="two_1_1"></div>
            <div class="two_1_2"></div>
        </div>
        <div class="two_2">
            <div class="two_2_1">
                <p class="two_2_p1">ABOUT<br>TECHNOLOGE</p>
                <p class="two_2_p2">absout technologe absout technologe absout technologe</p>
                <p class="two_2_p3">700</p>
            </div>
            <div class="two_2_2">
                <div class="two_2_2_1">
                    <p class="two_2_p4">3.2</p>
                </div>
                <div class="two_2_2_2">
                    <div class="two_2_2_3">
                        <p class="two_2_p5">css</p>
                    </div>
                    <div class="two_2_2_4">
                        <p class="two_2_p6">csscsscsscsscss</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="three">
        <div class="three_1">
            <p class="three_1_p1">What</p>
            <p class="three_1_p2">
                前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
        </div>
        <div class="three_2">
            <p class="three_2_p1">When</p>
            <p class="three_2_p2">
                前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
        </div>
        <div class="three_3">
            <div class="three_3_1">
                <p class="three_3_p1">How</p>
                <p class="three_3_p2">前端前端前端前端</p>
                <p class="three_3_p2">前端前端前端前端前端前端</p>
                <p class="three_3_p2">前端前端前端</p>
            </div>
            <div class="three_3_2">
                <div class="three_3_3">
                    <p class="three_3_p3">What----</p>
                    <p class="three_3_p3">What----</p>
                    <p class="three_3_p3">What----</p>
                </div>
                <div class="three_3_4">
                    <p class="three_3_p4">40%</p>
                    <p class="three_3_p4">30%</p>
                    <p class="three_3_p4">30%</p>
                </div>
            </div>
        </div>
    </div>
    <div class="four">
        <div class="four_left">
            <div class="left_top">
                <div class="top_1">
                    <div class="top_1_left">
                        <p>THE</p>
                    </div>
                    <div class="top_1_right">
                        <p>TECHNOLOGE</p>
                    </div>
                </div>
                <div class="top_2">
                    <p>OF FRONT</p>
                    <p id="a">前端技术领域</p>
                </div>
            </div>
            <div class="left_bottom">
                <div class="bottom1">
                    <dl>
                        <dt>
                        <p class="bottom1_p1">前</p></dt>
                        <dd>
                            <p class="bottom1_p2">
                                前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
                        </dd>
                    </dl>
                </div>
                <div class="bottom2">
                    <dl>
                        <dt><img src="imges/NJ.jpg"></dt>
                        <dd>
                            <p class="bottom2_p1">
                                前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端前端前前端前端前端前端前端前前端前端前端前端前端前前端前端前端前端前端前前端前端前端前端前端前前端前端前端前端前端前前端前端前端前端前端前前端</p>
                            <p class="bottom2_p1">
                                端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
                            <p class="bottom2_p1">端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前</p>
                        </dd>
                    </dl>
                </div>
                <!--<div class="bottom3">-->
                <!--<p>前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>-->
                <!--</div>-->
            </div>
        </div>
        <div class="four_right">
            <div class="frt">
                <div class="tm">
                    <div class="tb"></div>
                    <p class="tbp1">前端技术</p>
                    <p class="tbp2">前端技术前端技术</p>
                </div>
            </div>
            <div class="frb">
                <div class="frb_up">
                    <div class="du1">
                        <ul class="ul1">
                            <li><span class="s1">前端前端前端前端前端前端..............</span><span class="s2">前端</span></li>
                            <li><span class="s1">前端前端前端前端......................</span><span class="s2">前端</span></li>
                            <li><span class="s1">前端前端前端前端前端前端前端前端......</span><span class="s2">前端</span></li>
                        </ul>
                    </div>
                </div>
                <div class="frb_down">
                    <div class="frb_down_left">
                        <div class="f1"><p>0</p></div>
                        <div class="f2"></div>
                        <div class="f3">
                            <div class="last1"><p>ONE TWO<br> THREE FOUR FIVE</p></div>
                            <div class="last2"><p>hello world hello world hello world</p></div>
                        </div>
                    </div>
                    <div class="frb_down_right">
                        <span class="s3">“</span>
                        <p class="p5">world hello world hello world hello world hello world hello world hello world
                            hello world hello world hello world hello world hello world hello world </p>
                        <span class="s4">”</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="five">
        <p>ife.baidu.com</p>
    </div>
</div>

</body>
</html>
