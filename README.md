<html>
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name='viewport' content='width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no'>
        <title>Classic</title>
        
        <link rel="stylesheet" href="css/jquery.bxslider.css">
        <link rel='stylesheet' href='css/normalize.css' />
        <link rel='stylesheet' href='css/edit.css' />
        <link rel='stylesheet' href='css/font-awesome.min.css' />
        
        <style>
        * {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}

.container{
    width: 1200px;
    margin: auto;
}

ul{
    list-style: none;
    padding: 0;
    margin: 0;
}

.navbar,
.header,
.services,
.our-team,
.our-projects,
.footer{
    min-width: 1200px;;
}

/*navbar*/
.navbar{
    color: #FFF;
    font-size: 20px;
    height: 0;
    z-index: 2;
    color: #FFF;
    position: relative;
}

.navbar .brand{
    float: left;
    width: 40%;
    text-transform: uppercase;
}

.navbar .links{
    width: 60%;
    margin-left: 550px;
    padding: 10px;
    font-weight: bold;
}


.navbar .links li{
    display: inline-block;
    padding: 10px 15px;
    margin: 0 10px;
    border-bottom: 2px solid transparent
}

.navbar .links li a{
    color: #FFF;
    text-decoration: none;
}

.navbar .links li.active a,
.navbar .links li a:hover{
    color: #1abc9c;
}

.navbar .links li.active,
.navbar .links li:hover{
    border-bottom: 2px solid #1abc9c;
}

/*header*/

.header{
    background: url('../imgs/header.jpg');
    position: relative;
    max-height: 1150px;
}

.header .overlay{
    background-color: rgba(0, 0, 0, 0.7);
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    height: 1150px;;
    width: 100%;
    color: #FFF;
    z-index: 1;
    padding: 0;
    margin: 0;
}

/*bxslider

.header .bx-wrapper{
    height: 100%;
}

.header .bx-wrapper .bx-viewport{
    box-shadow: none;
    border: 0;
    background: none;
    height: 100% !important;
    text-align: center;
}

.header .bxslider{
    height: 100%;
}

.header .bxslider li{
    display: block;
}

.header .bxslider li h2{
    font-size: 60px;
}

.header .bxslider li h2 span{
    color: #1abc9c;
}*/

/*services*/

.services{
    padding: 80px 20px 40px;
}

.services h2{
    margin: 0;
    font-weight: normal;
}

.services .item{
    float: left;
    width: 33.3333%;
    margin-top: 50px;
    margin-bottom: 20px;
}

.services .item i{
    float: left;
    margin-top: 10px; 
    color: #1abc9c;
    width: 17%;
    margin-right: 8%;
}

.services .item .info{
    float: left;
    width: 70%;
}

.services .item .info h3{
    color: #585353;
    font-weight: normal; 
    margin-bottom: 10px;
}

.services .item .info p{
    margin: 0;
    color: #888;
}

.our-team{
    padding: 40px 20px;
}

.our-team .box{
    float: left;
}

.our-team .box:first-child{
    width: 35%;
}

.our-team .box p{
    color: #888;
    line-height: 1.5;
    font-size: 14px;
    margin-top: 20px;
}

.our-team .box h2{
    font-weight: normal;
}

.our-team img{
    height: 230px;
}

.our-team .box:not(:first-child){
    width: 15.25%;
    margin-left: 1%;
    position: relative;

}

.our-team .box:not(:first-child) .overlay{
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    line-height: 223px;
    font-size: 20px;
    font-weight: bold;
    background-color: #1abc9c;
    color: #FFF;
    text-align: center;
    display: none;
    transition: all 1s ease-in-out;
    opacity: .9;
}

.our-team .box:not(:first-child):hover .overlay{
    display: block;
}

.our-team .box:not(:first-child) img {
    width: 100%;
}

.our-team h2{
    font-weight: normal;
    padding: 0 0 15px;
}

/*Testimonials*/

.testim{
    background: url('../imgs/1857a2e6b5e9391.jpg');
    -webkit-background-size:cover;
    -moz-background-size:cover;
    -O-background-size:cover;
    background-size:cover;
    height: 400px;
    position: relative;
    text-align: center;
    padding: 80px 0;
}

.testim .t-overlay{
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    color: #FFF;
    background-color: rgba(0, 0, 0, .8);
}

.testim h2{
    font-size: 40px;
    margin: 80px 0 10px;
}

.testim q{
    font-size: 20px;
    line-height: 2;
    color: #D8D0D0;
    display: block;
    margin-top: 60px;
}

.testim p{
    font-size: 30px;
    color: #1abc9c;
}

.testim .slider > div{
    display: none
}

.testim .slider .active{
    display: block
}

/*projects*/


.our-projects h2{
    font-weight: normal;
}

.our-projects ul{
    margin-top: 50px;
}

.our-projects ul li{
    display: inline-block;
    border: 2px solid #D4CCCC;
    color: #A7A7A7;
    padding: 10px;
    border-radius: 5px;
    margin-right: 5px;
}

.our-projects ul li.selected{
    background-color: #1abc9c;
    border: 2px solid #1abc9c;
    color: #FFF;
}

.our-projects .gallery{
    margin-top: 50px;
    overflow: hidden;
}

.our-projects .gallery .row > div{
    width: 32.666%;
    float: left;
    margin-bottom: 12px;
    background-color: #DDD;
    position: relative;
}

.our-projects .gallery .row > div img{
    width: 100%;
}

.our-projects .gallery .row > div:nth-child(2){
    margin-right: 1%;
    margin-left: 1%;

}

.our-projects .gallery .row > div .over{
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    line-height: 183px;
    font-size: 20px;
    font-weight: bold;
    background-color: #1abc9c;
    color: #FFF;
    text-align: center;
    opacity: .9;
    display: none;
}

.our-projects .gallery .row > div .heart{
    position: absolute;
    bottom: 20px;
    right: 20px;
    color: #FFF;
    display: none;
}

.our-projects .gallery .row > div:hover .over,
.our-projects .gallery .row > div:hover .heart{
    display: block;
}

/*.our-projects .mix {
    display: none;
}*/

.our-projects .shuffle li{
    cursor: pointer;
}

/*footer*/

.footer{
    background-color: #232323;
    color: #6C6C6C;
    padding: 40px 0;
    overflow: hidden;
}

.footer .col{
    width: 25%;
    float: left;
}


.footer .col h2{
    color: #FFF;
    font-weight: normal;
    font-size: 18px;
}

.footer .col p{
    margin-bottom: 20px;
    line-height: 1.6;
}

.footer .col i{
    display: inline-block;
    color: #979797;
    border: 1px solid #979797;
    width: 40px;
    padding: 10px;
}

.footer .tags span{
    display: inline-block;
    color: #CCC;
    border: 1px solid #979797;
    padding: 10px;
    margin-right: 5px;
    margin-bottom: 10px;
    margin-left: 10px;
}

.footer .col img{
    width: 120px;
    height: 70px;
}

.footer .recent div{
    overflow: hidden;
    margin-bottom: 16px;
}

.footer .recent div img{
    float: left;
    margin-right: 10px;
}

.footer .recent div h4{
    color: #CCC;
    font-weight: normal;
}

.footer .blog ul li{
    padding: 15px;
    border-bottom: 1px solid #979797;
}

.footer .copyright{
    margin-top: 30px;
}

/*Frame Work*/

.clearfix{
    clear: both;
}
 .special-heading {
    position: relative;
 }

 .special-heading:after{
    content: "";
    display: block;
    position: absolute;
    top: 40px;
    left: 0;
    width: 40px;
    border-bottom: 2px solid #333;
}

.seperator{
    border: 1px solid #EEE;
}
        </style>
        
    </head>
    
    <body>
        <!--navbar-->
        
        <div class="navbar">
            <div class="container">
            <div class="brand">
                <h2>Classic</h2>
            </div>
                <ul class="links">
                    <li class="active"><a href="#">Home</a></li>
                    <li><a href="#" data-value="ser">About</a></li>
                    <li><a href="#" data-value="test">Test imonials</a></li>
                    <li><a href="#" data-value="port">Portfolio</a></li>
                    <li><a href="#" data-value="cont">Contact</a></li>
                </ul>
            <div class="clearfix"></div>
            </div>
        </div>

        <!--start Header-->
        
        <div class="header">
            <div class="overlay">
                <!--<ul class="bxslider">
                    <li>
                        <h2>Welcome to <span>Classic</span></h2>
                        <p>This test Paragraph</p>
                    </li>
                    <li>
                        <h2>Welcome to <span>Classic</span></h2>
                        <p>This test Paragraph</p>
                    </li>
                    <li>
                        <h2>Welcome to <span>Classic</span></h2>
                        <p>This test Paragraph</p>
                    </li>
                    <li>
                        <h2>Welcome to <span>Classic</span></h2>
                        <p>This test Paragraph</p>
                    </li>
                </ul>-->
            </div>
        </div>

        <!--services-->
        <div id="ser" class="services">
            <div class="container">
                <h2 class="special-heading">Our Services</h2>
                <div class="item">
                    <i class="fa fa-laptop fa-4x fa-fw"></i>
                    <div class="info">
                        <h3>Responsive</h3>
                        <p>Responsive web design is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes.</p>
                    </div>                
                </div>

                <div class="item">
                    <i class="fa fa-clone fa-4x fa-fw"></i>
                    <div class="info">
                        <h3>Cloud Services</h3>
                        <p>Responsive web design is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes.</p>
                    </div>                
                </div>

                <div class="item">
                    <i class="fa fa-lightbulb-o fa-4x fa-fw"></i>
                    <div class="info">
                        <h3>Fresh Ideas</h3>
                        <p>Responsive web design is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes.</p>
                    </div>                
                </div>

                <div class="item">
                    <i class="fa fa-envelope-o fa-4x fa-fw"></i>
                    <div class="info">
                        <h3>Attachments</h3>
                        <p>Responsive web design is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes.</p>
                    </div>                
                </div> 
                <div class="item">
                    <i class="fa fa-star-o fa-4x fa-fw"></i>
                    <div class="info">
                        <h3>Support video</h3>
                        <p>Responsive web design is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes.</p>
                    </div>                
                </div>
                <div class="item">
                    <i class="fa fa-heart-o fa-4x fa-fw"></i>
                    <div class="info">
                        <h3>Lovely Design</h3>
                        <p>Responsive web design is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes.</p>
                    </div>                
                </div> 
                <div class="clearfix"></div>                                                          
            </div>
        </div>

        <div class="our-team">
            <div class="container">
                <div class="box">
                    <h2 class="special-heading">Our Team</h2>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
                </div>
                <div class="box">
                    <div class="overlay">
                        Abdallah
                    </div>
                    <img src="imgs/01.jpg" alt="Image1"/>
                </div>
                <div class="box">
                    <div class="overlay">
                        Hassan
                    </div>
                    <img src="imgs/02.jpg" alt="Image2"/>
                </div>  
                <div class="box">
                    <div class="overlay">
                        Sayed
                    </div>
                    <img src="imgs/03.jpg" alt="Image3"/>
                </div> 
                <div class="box">
                    <div class="overlay">
                        Ragab
                     </div>
                    <img src="imgs/04.jpg" alt="Image4"/>
                </div> 
                <div class="clearfix"></div>                                           
            </div>
        </div>

        <!--Testimonials-->

        <div id="test" class="testim">
            <div class="t-overlay">
                <div class="container">
                    <h2>What Our clients Say</h2>
                    <div class="slider">
                        <div class="active">
                            <q>Hello this is very good website I loved it so much because reason test Hello this is very good website I loved it so much because reason testHello this is very good website I loved it so much because reason test</q>
                            <p>Abdallah</p>
                        </div>
                        <div>
                            <q>Hello this is very good website I loved it so much because reason test Hello this is very good website I loved it so much because reason testHello this is very good website I loved it so much because reason test</q>
                            <p>hassan</p>
                        </div>
                        <div>
                            <q>Hello this is very good website I loved it so much because reason test Hello this is very good website I loved it so much because reason testHello this is very good website I loved it so much because reason test</q>
                            <p>Sayed</p>
                        </div>
                        <div>
                            <q>Hello this is very good website I loved it so much because reason test Hello this is very good website I loved it so much because reason testHello this is very good website I loved it so much because reason test</q>
                            <p>Ragab</p>
                        </div>
                        <div>
                            <q>Hello this is very good website I loved it so much because reason test Hello this is very good website I loved it so much because reason testHello this is very good website I loved it so much because reason test</q>
                            <p>Medo</p>
                        </div>                          
                    </div>
                </div>
            </div>
        </div>

        <!--Projects-->

        <div id="port" class="our-projects">
            <div class="container">
                <h2 class="special-heading">Projects</h2>
                <ul class="shuffle">
                    <li class="selected filter" data-filter="all">All</li>
                    <li class="filter" data-filter=".mobile">Mobile</li>
                    <li class="filter" data-filter=".coffe">Coffe</li>
                    <li class="filter" data-filter=".video">Video</li>
                </ul>
                <div id="Container" class="gallery">
                    <div class="row">
                        <div class="mix mobile">
                        <div class="over">View More</div>
                        <span class="heart">
                            <i class="fa fa-heart"></i> 14
                        </span>
                          <img src="imgs/project1.jpg">
                        </div>
                        <div class="mix coffe">
                            <div class="over">View More</div>
                            <span class="heart">
                                    <i class="fa fa-heart"></i> 23
                                </span>
                           <img src="imgs/project2.jpg">
                        </div>
                        <div class="mix coffe">
                            <div class="over">View More</div>
                            <span class="heart">
                                    <i class="fa fa-heart"></i> 18
                            </span>
                           <img src="imgs/project3.jpg">
                        </div>   
                    </div>
                    <div class="row">
                        <div class="mix mobile">
                            <div class="over">View More</div>
                            <span class="heart">
                                    <i class="fa fa-heart"></i> 119
                                </span>
                           <img src="imgs/project4.jpg">
                        </div>
                        <div class="mix video">
                            <div class="over">View More</div>
                            <span class="heart">
                                    <i class="fa fa-heart"></i> 98
                                </span>
                           <img src="imgs/project5.jpg">
                        </div>
                        <div class="mix video">
                            <div class="over">View More</div>
                            <span class="heart">
                                    <i class="fa fa-heart"></i> 74
                                </span>
                           <img src="imgs/project6.jpg">
                        </div>
                    </div>
                </div>
            </div>

            <!--Footer-->
            
            <div id="cont" class="footer">
                <div class="container">
                    <div class="col">
                        <h2>About Classic</h2>
                        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s</p>
                        <i class="fa fa-facebook fa-lg fa-fw"></i>
                        <i class="fa fa-google-plus fa-lg fa-fw"></i>
                        <i class="fa fa-twitter fa-lg fa-fw"></i>
                    </div>
                    <div class="col tags">
                        <h2>Tags</h2>
                        <span>Html</span>
                        <span>Css</span>
                        <span>Photoshop</span>
                        <span>Responsive</span>
                        <span>Art</span>
                    </div>
                    <div class="col recent">
                        <h2>Recent Posts</h2>
                        <div>
                            <img src="imgs/footer/01.jpg" alt="" />
                            <h4>How to get Ride</h4>
                            <span>June, 2014</span>
                        </div>
                        <div>
                            <img src="imgs/footer/02.png" alt="" />
                            <h4>Why I'm Running</h4>
                            <span>June, 2014</span>
                        </div>
                        <div>
                            <img src="imgs/footer/03.png" alt="" />
                            <h4>Cassela Waste</h4>
                            <span>June, 2014</span>
                        </div>
                    </div>
                    <div class="col blog">
                        <h2>Blog Catogries</h2>
                        <ul>
                            <li>Agency</li>
                            <li>Bussines</li>
                            <li>Hultu Purpose</li>
                            <li>Audio</li>
                        </ul>
                    </div> 
                    <div class="clearfix"></div>
                    <div class="copyright">Copyright &copy; 2015 All Rights Reversed</div>                   
                </div>
            </div>

        
        <script src='js/jquery.min.js'></script>
        <script src="js/jquery.bxslider.js"></script>
        <script src="js/mixitup.min.js"></script>
        <script src="js/jquery.nicescroll.min.js"></script>
        <script src='js/edit.js'></script>
        
        <script>
        
        $(function() {

    'use strict'

    //Adjust header height

    var myHeader = $('.header');

    myHeader.height($(window).height());

    $(window).resize(function () {

        myHeader.height($(window).height());

        $('.bxslider').each(function() {

           $(this).css('paddingTop', ($(window).height() - $('.bxslider li').height()) / 2);
    
       });

    });

    //links Add active class

    $('.links li a').click(function() {

     $(this).parent().addClass('active').siblings().removeClass('active');

    });

    $('.links li a').click(function() {

        $('html, body').animate({

            scrollTop: $('#' + $(this).data('value')).offset().top

        }, 1000);
    });

    //Adjust bxslider

   $('.bxslider').each(function() {

     $(this).css('paddingTop', ($(window).height() - $('.bxslider li').height()) / 2);

    });

        $('.bxslider').bxSlider({

        pager: false
    
  });

  // Auto slider code

  (function autoSlider() {
      $('.slider .active').each(function () {

        if(!$(this).is(':last-child')) {

            $(this).delay(3000).fadeOut(1000, function() {

                $(this).removeClass('active').next().addClass('active').fadeIn();

                autoSlider();
            });
        }else{

            $(this).delay(3000).fadeOut(1000, function() {

                $(this).removeClass('active');

                $('.slider div').eq(0).addClass('active').fadeIn();

                autoSlider();
          
            });
        }

      });

  }());

  //mixItUp

  $('#Container').mixItUp();

  //Adjust shuffle

  $('.shuffle li').click(function() {

    $(this).addClass('selected').siblings().removeClass('selected');

  });

  //Trigger nice scroller

  $('html').niceScroll({

    cursorcolor: '#labc9c',
    cursorwidth: '20px'
  })

});
        
        </script>

    </body>
       
</html>

