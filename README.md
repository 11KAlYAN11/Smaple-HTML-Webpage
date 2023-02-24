# Smaple-HTML-Webpage
sample code for html webpage



Date 21/04/2021(sree rama navami)

html demo webpage
<html>
    <title>Kalyan_Demo_Webpage</title>
    <head>
        <style>
            div {
            background-image: url('https://www.bing.com/th?id=OIP.M9AsZ7Sm6Qq-LXpY92Tt2AHaEK&w=251&h=160&c=8&rs=1&qlt=90&dpr=1.25&pid=3.1&rm=2');
            }
        </style>
    </head>
    <body>
        <h1>image maps</h1>
        <img src="C:\Users\KALYAN\Pictures\workplace1.jpg" alt="workplace" usemap="#workmap">
        <!--<img src="C:\Users\KALYAN\Pictures\workspace2.jpg">
        <img src="C:\Users\KALYAN\Pictures\workspace3.jfif">
        <img src="C:\Users\KALYAN\Pictures\workspace4.jfif">-->
        <map name="workmap">
            <area shape="rect" coords="35,46,299,376" alt="computer" href="C:\Users\KALYAN\Pictures\workspace2.jpg">
            <area shape="rect" coords="317,189,368,267" alt="mobile phone" href="C:\Users\KALYAN\Pictures\workspace3.jfif">
            <area shape="circle" coords="375,322,50" alt="cup of coffe" href="C:\Users\KALYAN\Pictures\workspace4.jfif">
        </map>
        <img src="C:\Users\KALYAN\Pictures\kalyanmain1.jpg" alt="group of friends" usemap="#friends">
        <map name="friends">
            <area shape="poly" coords="361,760,341,700,251,660,250,494,313,409,303,288,344,242,412,266,423,379,468,397,504,466,543,566,525,736" alt="friends" href="C:\Users\KALYAN\Pictures\pavankalyan2.jpg">
            <area shape="poly" coords="481,412,511,477,542,580,455,364,455,284,491,212,555,261,592,329,602,388,607,480,612,580," alt ="friends" href="C:\Users\KALYAN\Pictures\sai.jpg">
            <area shape="poly" coords="671,739,652,620,606,484,597,387,720,351,780,412,810,485,831,568,930,622" alt="friends" href="C:\Users\KALYAN\Pictures\shansha.jpg">
            <area shape="poly" coords="" alt="friends" href="C:\Users\KALYAN\Pictures\">
        </map>
        
        <br><br><hr><hr><marquee scrollamount="9%" direction ="right" width="80%" style="color:green;background-color:gold">This webpage is open source plartform</marquee><hr><hr><br><br>
        </style>

        <div>
            You can specify background images<br>
            for any visible HTML element.<br>
            In this example, the background image<br>
            is specified for a div element.<br>
            By default, the background-image<br>
            will repeat itself in the direction(s)<br>
            where it is smaller than the element<br>
            where it is specified. (Try resizing the<br>
            browser window to see how the<br>
b            ackground image behaves.
        </div><br><br>
      <center> <table border="10%" cellpadding="20%" cellspacing="20%" width="100%" height="40%" style="color:rgb(128, 0, 107);background-color: mediumaquamarine;font-family:Verdana">
            <tr>
                <th>first name</th>
                <th>last name</th>
                <th>address</th>
            </tr>
            <tr>
                <td>asam</td>
                <td colspan="2">kalyan reddy from KDP</td>
               
            </tr>
            <tr>
                <td rowspan="2">pavan kalyan</td>
                <td>kalyan</td>
                <td>ATP</td>
            </tr>
            <tr>
                <td>sewag</td>
                <td>KOL..</td>
            </tr>
        </table></center> 

        <ul type="square">
            <li>Coffee</li>
            <li>Tea
              <ul>
                <li>Black tea</li>
                <li>Green tea</li>
              </ul>
            </li>
            <li>Milk</li>
            <ul>
            <li>white milk</li>
            <li>pure white milk</li>
            <li>good health milk</li>
            </ul>
            
          </ul>
          <hr>
          bdo=bi directional over ride😏<br><hr>
          <bdo dir="rtl">
            This text will goes from right to left<hr>
          </bdo>
          <hr><hr>
          <audio controls style="color:darkmagenta;background-color:olive;font-family:verdana;">
         <source src="C:\Users\KALYAN\Music\Bulle-SenSongsMp3.Co.mp3" type="audio/mpeg">
          </audio><br><hr>

          <audio controls style="color:darkmagenta;background-color:olive;font-family:verdana;">
          <source src="C:\Users\KALYAN\Music\Gichchi Gichchi-SenSongsMp3.Co.mp3" type="audio/mpeg">
          </audio><br><hr>

          <audio controls style="color:darkmagenta;background-color:olive;font-family:verdana;">
          <source src="C:\Users\KALYAN\Music\Dimaak Kharaab - SenSongsMp3.Co.mp3" type="audio/mpeg">
         </audio><br><hr>

        <!-- audio and video tags-->
        <audio controls>
            <source src="C:\Users\KALYAN\Music\Gichchi Gichchi-SenSongsMp3.Co.mp3" type="audio/ogg">
        </audio>
        <br>
        <video controls width="80%" height="90%">
            <source src="C:\Users\KALYAN\Videos\desi_kalkar.mkv" type="">
           
        </video>
        <video controls width="38%" height="42%">
            <source src="C:\Users\KALYAN\Videos\lut_gaya.mkv" typer="video.mp4">
        </video>

        <!-- Object and embed tags ans it's uses-->
        <br>
        <h2>useing object tag to display some text files info</h2>
         <object data="D:\C notes\basic string operations.txt" width="30%" height="200px"></object>
         <h3>also we can display photos useing object tag</h3>
        <object data="C:\Users\KALYAN\Pictures\kalyanmain1.jpg" width="500" height="350"></object>
        <hr>
        <!-- Since it is not working in modren browsers 👍-->
        <!--<embed data="C:\Users\KALYAN\Pictures\kalyanmain1.jpg" width="500" height="350"> </embed> -->
        <hr><br>
        <h2>playing our videeos from youtbe😃</h2>
        <iframe src="https://www.youtube.com/watch?v=g2PA7JTLhhs autoplay=1&mute=1,loop=1,controls=1" width="420" height="345" ></iframe>
        <!--
            true = 1;
            false = 0
            autoplay = 1(true) & mute = 1(true)#muted video wil play
            loop = 1(video play number of times)
            controls = 1(pauae/play/sound/fullscreen controls(1 display/ 0 not display))
            like this youtube has many specifications
        -->
    </body>
</html>







see you boy
