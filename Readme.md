@charset "utf-8";

/* ズームアップダウンすると原本のサイトはスペースが開かないのでwidthにautoを入れている？？ */

/* Reset CSS*/
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}

/* body */
body {
border: 20px solid rgb(0, 0, 0);
}

/* body */

/* header */

header div img#upper_center_pic {
  width: 1100px;
  height: 670px;
}

/* 
header div img#upper_center_logo_letters {
  width: 1140px;
  height: 690px;
  position: relative;
  bottom: 700px;
} */

header div img#upper_center_logo {
  width: 300px;
  height: 35.91px;
  position: relative;
  bottom: 650px;
  left: 30px;
}

header div h2 {
  position: relative;
  text-align: center;
  bottom: 250px;
  color: white;
  font-size: 36px;
}


header #upper_separate {
  display: flex;
}

/* header #upper_left{
  width: 564.5px;
  height: 450px;
  float: left;
} */

header div div img#upper_left_logo {
  width: 550px;
  height: 450px;
  float: left;
}

header div div h2 {
  font-size: 32px;
  color: black;
  font-weight: bold;
}

/* header #upper_right{
  width: 564.5px;
  height: 450px;
  background-color: rgb(43, 165, 236);
  float: left;
} */

header div div img#upper_left_ramen {
  width: 550px;
  height: 450px;
}

/* header */

/* section */

section #bottom_center {
  width: 1129px;
  height: 907.2px;
  background-color: rgb(239, 255, 183);
}

section #bottom_separate {
  display: flex;
}

section #bottom_left {
  width: 544.5px;
  height: 450px;
  background-color: rgb(214, 88, 166);
}

section #bottom_right {
  width: 500.5px;
  height: 450px;
  background-color: rgb(40, 231, 183);
}

/* section */

/* footer */

footer {
  width: 1129px;
  height: 112.5px;
  background-color: gray;
}

/* footer */

html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <link rel="icon" href="./images/favicon.ico" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"></script>
    <title>Hokkaido Ramen Santouka</title>
  </head>
  <body>
    <!-- wrapper -->
    <div id="wrapper">
      <!-- header -->
      <header>
        <!-- upper_center -->
        <div id="upper_center">
          <img
            id="upper_center_pic"
            src="./images/upper_center_pic.jpg"
            alt="upper_center_pic"
          />
          <!-- <img
            id="upper_center_logo_letters"
            src="./images/logo-letters.png"
            alt="upper_center_pic"
          /> -->
          <img
            id="upper_center_logo"
            src="./images/logo.png"
            alt="upper_center_logo"
          />

          <h2>scroll</h2>
          <!-- 表示されないので、一度スキップ<i class="fa-solid fa-angle-down"></i> -->
        </div>
        <!-- upper_center -->

        <div id="upper_separate">
          <!-- upper_left -->
          <div id="upper_left">
            <!-- 表示されないのでスキップ<i class="fa-brands fa-pagelines" style="color: #fafafa"></i> -->
            <img
              id="upper_left_logo"
              src="./images/upper_left_pic.jpeg"
              alt="upper_left_pic"
            />
            <h2>OUR STORY</h2>
            <!-- <p>test</p> -->
            <!-- ボックスの大きさを変更して中に文字を入れる -->
            <!-- <i class="fa-regular fa-stop"></i> -->
          </div>
          <!-- upper_left -->

          <!-- upper_right -->
          <div id="upper_right">
            <img id="upper_left_ramen" src="./images/upper_right_ramen.jpg" alt="upper_right_pic" />
          </div>
          <!-- upper_right -->
        </div>
      </header>

      <!-- section -->
      <section>
        <!-- bottom_center -->
        <div id="bottom_center"></div>
        <!-- bottom_center -->

        <div id="bottom_separate">
          <!-- bottom_left -->

          <div id="bottom_left"></div>

          <!-- bottom_left -->

          <!-- bottom_right -->
          <div id="bottom_right"></div>
          <!-- bottom_right -->
        </div>
      </section>
      <!-- section -->
    </div>
    <!-- wrapper -->

    <footer></footer>
  </body>
</html>
