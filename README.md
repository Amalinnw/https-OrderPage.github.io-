<!DOCTYPE html>
<html>
<head>
    <title>Order Page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="style.css">

    <style>
        /* This style sets the width of all images to 100%: */
        img {
            width: 100%;
        }

        #demoimage {
            float: left;
        }

        #demotext {
            float: left;
        }

        #democontainer {
            width: 400px;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
        }
    </style>
</head>
<body>
    <!-- top navigation -->

    <div class="wrapper">

        <div class="top_nav">
            <div class="left">
                <div class="logo">
                    <p>FASHION BUGGS</p>
                </div>
            </div>
        </div>

        <div class="bottom_nav">
            <ul>
                <li><a href="#" class="active" class="nav_link">Home</a></li>
                <li><a href="#" class="nav_link">New Arrival</a></li>
                
                <li><a href="#" class="nav_link">About</a></li>
                <li><a href="#" class="nav_link">Contact</a></li>
                <li><a href="#" class="nav_link">FAQ</a></li>
                <li><a href="#" class="fa fa-shopping-cart">Cart</a></li>
            </ul>
        </div>
    </div>
    <br /><br /><br /><br /><br /><br /><br /><br />

    <!--Content-->
    <!-- TESTTTT ON HOLD
    <p>The second image uses the style attribute to set the width to 128 pixels, this will not be overridden by the style in the head section:</p>
    <br /><br />
    <img src="zalora-work-1645-6340342-1.jpg" alt="HTML5 Icon" style="width:25%; height:25%;">


        <div id="democontainer">
         <img id="demoimage" src="zalora-work-1645-6340342-1.jpg" width="25%" height="25%">
         <ul id="demotext">
             <li>Free contact form</li>
             <li>  [..etc..]  </li>
         </ul>
         <br style="clear: both;">
     </div>

     -->


    <body>
        <table style="width:60%">
            <td><font size="6"><img src="zalora-work-9764-8421932-1.jpg" width="600" height="500" class="center" align="right"></td>

            <td>
                <center>
                    <b><h3>YOKE BLOUSE</b></h3><br />
                    <p>RM 29.00</p><br /><br />
                    <p> -  Printed long sleeve button detail blouse</p></br>
                    <p>-  Smooth cotton material</p><br />
                    <p>-  Regular fit</p></br>

                    <p>Please select your size</p>
                    <input type="radio" id="s" name="size" value="s">
                    <label for="male">S</label><br>
                    <input type="radio" id="m" name="size" value="m">
                    <label for="female">M</label><br>
                    <input type="radio" id="l" name="size" value="l">
                    <label for="male">L</label><br>
                    



                    <br /><br />
                    <form action="/action_page.php">
                        <label for="quantity">Quantity</label>
                        <br /><input type="number" id="quantity" name="quantity" min="1" max="5"><br /><br /><br />
                        <input type="submit" style="background-color:coral" value="     Add To Cart    " class="btn">
                    </form><br />

                    <hr style="height:2px;border-width:0;color:gray;background-color:gray">
                    <h3>Delivery Estimate</h3>
                    <p>
                        Selangor: 2-4 days; Johor, Penang: 3-5 days; 
                        <br>Rest of Peninsular Malaysia: 3-7 days; 
                        <br>East Malaysia: 8-13 days.
                        <br> All in working days.
                    </p>
</td></center>

        </table>
        </tr> <br
        </table>

    </body>



    <br /><br /><br />
    <div class="footer">
        <p>&copy; Copyright 2021 Fashion Buggs Offical</p>
    </div>


</body>
</html>
