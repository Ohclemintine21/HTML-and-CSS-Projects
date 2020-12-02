# HTML-and-CSS-Projects

An overview of a few HTML and CSS Projects I completed during my time at The Tech Academy. 
During this course I gained the knowledge of how to work with Front End code and how the designed code translates to a webpage.
Below, are snippets of code projects I worked on during the course. I throughly enjoy working with Front End code and find it fun to work with.

Space Webpage HTML Navbar and Home structure



    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8">
        <title>Space is Incredible</title>
        <link rel="stylesheet" href="./css/shared.css">
        <link rel="stylesheet" href="./css/animation.css">
      </head>
      <body>

        <!---NAV-->
        <div class="wrap">
          <div class="menu-container">
            <ul class="menu">
              <a href=" #home"><li>HOME</li></a>
              <a href=" #Gallery"><li>GALLERY</li></a>
              <a href=" #RESERVATIONS"><li>RESERVATIONS</li></a>
            </ul>
          </div>
        </div>
        <!----END NAV-->

        <!--HOME-->
        <div id="home">
          <div class="container">
            <div class="text-center">
              <span class="head-main">The Space Station</span>
            </div>
          </div>
        </div>
        <!--END HOME-->



Space Webpage CSS styling Home Page



    *---------------------------------------------------------
        HOME SECTION STYLES
    ----------------------------------------------------------*/
    #home {
        background: url(../images/planets.jpg) no-repeat 50% 50%;
        background-attachment: fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: cover;
        width: 100%;
        display: block;
        height: auto;
        padding-top: 350px; /* This is spacer before the Main title Logo*/
        padding-bottom: 500px; /* This is spacer after the Main title Logo */
        color: #fff;
    }

    .head-main {
        text-shadow:2px 4px 5px rgba(0,0,0,0.9);
        font-variant: small-caps;
        color: #fff;
        letter-spacing: 5pt;
        word-spacing: 21pt;
        font-size: 4.5em;
        text-align: left;
        font-family: impact, san-serif;
        line-height: 2;
        font-weight: 900;
        border: 5px double #fff;
        padding: 10px;
    }

    .head-sub-main {
        font-size: 23px ;
        font-weight: 500;
        padding: 50px 20px 10px 20px;
        text-transform: uppercase;
    }

    .head-last {
        font-size: 18px;
        font-weight: 900;
        padding: 5px 20px 20px 20px;
        border: 1px dotted #fff;
        padding: 5px; 
    }

  

I was also very proud of the Portfolio site I created which can be viewed in link below

https://github.com/Ohclemintine21/HTML-and-CSS-Projects/tree/master/portfolio


