<!DOCTYPE html>
<html dir="ltr" lang="en-US"><head><!-- Created by Artisteer v4.1.0.59861 -->
    <meta charset="utf-8">
    <title>Main</title>
	<link rel="icon" type="image/ico" href="images/title-icon.png" />
    <meta name="viewport" content="initial-scale = 1.0, maximum-scale = 1.0, user-scalable = no, width = device-width">

    <!--[if lt IE 9]><script src="https://html5shiv.googlecode.com/svn/trunk/html5.js"></script><![endif]-->
    <link rel="stylesheet" href="style.css" media="screen">
    <!--[if lte IE 7]><link rel="stylesheet" href="style.ie7.css" media="screen" /><![endif]-->
    <link rel="stylesheet" href="style.responsive.css" media="all">


    <script src="jquery.js"></script>
    <script src="script.js"></script>
    <script src="script.responsive.js"></script>


<script>jQuery(function($) {
    'use strict';
    if ($.fn.slider) {
        $(".art-slidecontainertobacco").each(function () {
            var slideContainer = $(this), tmp;
            var inner = $(".art-slider-inner", slideContainer);
            var helper = null;

            if ($.support.transition) {
                helper = new BackgroundHelper();
                helper.init("fade", "next", $(".art-slide-item", inner).first().css($.support.transition.prefix + "transition-duration"));
                inner.children().each(function () {
                    helper.processSlide($(this));
                });

            }


            inner.children().eq(0).addClass("active");
            slideContainer.slider({
                pause: 2600,
                speed: 600,
                repeat: true,
                animation: "fade",
                direction: "next",
                navigator: slideContainer.siblings(".art-slidenavigatortobacco"),
                helper: helper                
            });
        });
    }
});
</script><style>.art-content .art-postcontent-0 .layout-item-0 { margin-top: 20px;margin-bottom: 20px;  }
.art-content .art-postcontent-0 .layout-item-1 { padding-right: 10px;padding-left: 10px;  }
.ie7 .art-post .art-layout-cell {border:none !important; padding:0 !important; }
.ie6 .art-post .art-layout-cell {border:none !important; padding:0 !important; }

.art-slidecontainertobacco {
    position: relative;
        width: 380px;
    height: 283px;
        }

.art-slidecontainertobacco .art-slide-item
{

}



.art-slidecontainertobacco .art-slide-item {
    -webkit-transition: 600ms ease-in-out opacity;
    -moz-transition: 600ms ease-in-out opacity;
    -ms-transition: 600ms ease-in-out opacity;
    -o-transition: 600ms ease-in-out opacity;
    transition: 600ms ease-in-out opacity;
    position: absolute;
    display: none;
	left: 0;
	top: 0;
	opacity: 0;
    width:  100%;
    height: 100%;
}

.art-slidecontainertobacco .active, .art-slidecontainertobacco .next, .art-slidecontainertobacco .prev {
    display: block;
}

.art-slidecontainertobacco .active {
    opacity: 1;
}

.art-slidecontainertobacco .next, .art-slidecontainertobacco .prev {
    width: 100%;
}

.art-slidecontainertobacco .next.forward, .art-slidecontainertobacco .prev.back {
    opacity: 1;
}

.art-slidecontainertobacco .active.forward {
    opacity: 0;
}

.art-slidecontainertobacco .active.back {
    opacity: 0;
}


.art-slidetobacco0 {
    background-image:  url('images/slidetobacco0.png');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}
.art-slidetobacco1 {
    background-image:  url('images/slidetobacco1.png');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}
.art-slidetobacco2 {
    background-image:  url('images/slidetobacco2.png');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}


.art-slidenavigatortobacco {
  display: inline-block;
  position: absolute;
  direction: ltr !important;
  top: 259px;
  left: 83.16%;
  z-index: 101;
  line-height: 0 !important;
  -webkit-background-origin: border !important;
  -moz-background-origin: border !important;
  background-origin: border-box !important;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  text-align: center;
    white-space: nowrap;
    }
.art-slidenavigatortobacco
{
background: #9C9C9C;background: linear-gradient(top, rgba(194, 194, 194, 0.6) 0, rgba(128, 128, 128, 0.6) 84%, rgba(115, 115, 115, 0.6) 100%) no-repeat;background: -webkit-linear-gradient(top, rgba(194, 194, 194, 0.6) 0, rgba(128, 128, 128, 0.6) 84%, rgba(115, 115, 115, 0.6) 100%) no-repeat;background: -moz-linear-gradient(top, rgba(194, 194, 194, 0.6) 0, rgba(128, 128, 128, 0.6) 84%, rgba(115, 115, 115, 0.6) 100%) no-repeat;background: -o-linear-gradient(top, rgba(194, 194, 194, 0.6) 0, rgba(128, 128, 128, 0.6) 84%, rgba(115, 115, 115, 0.6) 100%) no-repeat;background: -ms-linear-gradient(top, rgba(194, 194, 194, 0.6) 0, rgba(128, 128, 128, 0.6) 84%, rgba(115, 115, 115, 0.6) 100%) no-repeat;background: linear-gradient(top, rgba(194, 194, 194, 0.6) 0, rgba(128, 128, 128, 0.6) 84%, rgba(115, 115, 115, 0.6) 100%) no-repeat;-svg-background: linear-gradient(top, rgba(194, 194, 194, 0.6) 0, rgba(128, 128, 128, 0.6) 84%, rgba(115, 115, 115, 0.6) 100%) no-repeat;
-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;


padding:7px;





}
.art-slidenavigatortobacco > a
{
background: #575757;background: #575757;background: #575757;background: #575757;background: #575757;background: #575757;background: #575757;-svg-background: #575757;
-webkit-border-radius:50%;-moz-border-radius:50%;border-radius:50%;



margin:0 10px 0 0;

width: 10px;

height: 10px;
}
.art-slidenavigatortobacco > a.active
{
background: #FDDB7C;background: #FDDB7C;background: #FDDB7C;background: #FDDB7C;background: #FDDB7C;background: #FDDB7C;background: #FDDB7C;-svg-background: #FDDB7C;
-webkit-border-radius:50%;-moz-border-radius:50%;border-radius:50%;



margin:0 10px 0 0;

width: 10px;

height: 10px;
}
.art-slidenavigatortobacco > a:hover
{
background: #AB7E03;background: #AB7E03;background: #AB7E03;background: #AB7E03;background: #AB7E03;background: #AB7E03;background: #AB7E03;-svg-background: #AB7E03;
-webkit-border-radius:50%;-moz-border-radius:50%;border-radius:50%;



margin:0 10px 0 0;

width: 10px;

height: 10px;
}

</style></head>
<body>
<div id="art-main">
    <div class="art-sheet clearfix">
<header class="art-header">
<div class="art-slider art-slidecontainerheader" data-width="1000" data-height="200">
    <div class="art-slider-inner">
<div class="art-slide-item art-slideheader0">

</div>
<div class="art-slide-item art-slideheader1">

</div>
<div class="art-slide-item art-slideheader2">

</div>

    </div>
</div>
<div class="art-slidenavigator art-slidenavigatorheader" data-left="93.6">
<a href="#" class="art-slidenavigatoritem"></a><a href="#" class="art-slidenavigatoritem"></a><a href="#" class="art-slidenavigatoritem"></a>
</div>



    <div class="art-shapes">

            </div>
<h1 class="art-headline" data-left="70.39%">
    <a href="#">UNITED TOBACCO GROUP (UTG)</a>
</h1>




                
                    
</header>
<nav class="art-nav">
    <ul class="art-hmenu"><li><a href="main.html" class="active">Main</a></li><li><a href="products.html">Products</a></li><li><a href="contact-us.html">Contact Us</a></li><li><a href="about-us.html">About Us</a></li><li><a href="car-reviews.html">Articles</a></li></ul> 
    </nav>
<div class="art-layout-wrapper">
                <div class="art-content-layout">
                    <div class="art-content-layout-row">
                        <div class="art-layout-cell art-content"><article class="art-post art-article">
                                
                                                
                <div class="art-postcontent art-postcontent-0 clearfix"><div class="art-content-layout-wrapper layout-item-0">
<div class="art-content-layout">
    <div class="art-content-layout-row">
    <div class="art-layout-cell layout-item-1" style="width: 43%" >
<div id="tobacco" style="position: relative; display: inline-block; z-index: 0; margin: 0px;  border-width: 0px;  " class="art-collage">
<div class="art-slider art-slidecontainertobacco" data-width="380" data-height="283">
    <div class="art-slider-inner">
<div class="art-slide-item art-slidetobacco0">

</div>
<div class="art-slide-item art-slidetobacco1">

</div>
<div class="art-slide-item art-slidetobacco2">

</div>

    </div>
</div>
<div class="art-slidenavigator art-slidenavigatortobacco" data-left="83.16">
<a href="#" class="art-slidenavigatoritem"></a><a href="#" class="art-slidenavigatoritem"></a><a href="#" class="art-slidenavigatoritem"></a>
</div>



    </div>

    </div><div class="art-layout-cell layout-item-1" style="width: 57%" >
        <span style="font-size: 20px;">United Tobacco Group is a tobacco manufacturing company that produces various brands for various clients. Our products range from the fully manufactured cigarettes to unprocessed raw tobacco depending on your needs. Our main target markets are tobacco processing companies, retailers and supermarkets that distribute tobacco products.</span><br>
    </div>
    </div>
</div>
</div>
<div class="art-content-layout">
    <div class="art-content-layout-row">
    <div class="art-layout-cell layout-item-1" style="width: 33%" >
        <h3><span style="color: #93E64E;">High Quality Products</span></h3><p style="text-align: left;"><span style="font-size: 14px;">We manufacture high quality tobacco products available for wholesale or retail at very low costs.We have a team of professional quality control workers who monitor the chain of processes from raw materials to finished products</span><br></p>
         
        <p style="text-align: left;"><img width="294" height="162" alt="" class="art-lightbox" src="images/04_AH_Cigarette%2087-ab.jpeg"><br></p>
    </div><div class="art-layout-cell layout-item-1" style="width: 34%" >
        <h3><span style="color: #84E236;">Various Brands</span></h3>
         
        <p><span style="font-size: 14px;">We have a wide range of brands to choose from. Currently we have 4 brands, which are</span></p><p></p><ul><li><span style="font-size: 16px;"><span style="line-height: normal;"><span style="text-decoration: underline; font-weight: bold; font-style: italic;"><a href="products.html" title="go to Products page">Yes</a></span></span><br></span></li><li><span style="font-size: 16px;"><span style="line-height: normal;"><span style="text-decoration: underline; font-weight: bold; font-style: italic;"><a href="products.html" target="_self" title="go to Products page">Forum</a></span></span><br></span></li><li><span style="font-size: 16px;"><span style="line-height: normal;"><span style="text-decoration: underline; font-weight: bold; font-style: italic;"><a href="products.html" title="go to Products page">Legends</a></span></span><br></span></li><li><span style="line-height: normal; font-size: 16px;"><a href="products.html" target="_self" title="go to Products page" style="text-decoration: underline; font-weight: bold; font-style: italic; ">Supermatch</a></span><br></li></ul><p></p><p><span style="font-size: 14px;">We will introduce more brands in the near future according to people's demands</span></p><p><br></p><p><br></p><p><br></p><p><br></p>
    </div><div class="art-layout-cell layout-item-1" style="width: 33%" >
        <h3><span style="color: #93E64E;">Competitive Prices</span></h3>
         
        <p><span style="font-size: 14px;">We have a fast and efficient production line which enables us to present competitive prices on the market. 
		Since our production process is fast and effective, we sell our products at &nbsp;very reasonable prices. This gives us an edge over our competitors.</span></p>
         
        <p><img width="289" height="163" alt="" class="art-lightbox" src="images/1.jpg"><br></p>
    </div>
    </div>
</div>
<div class="art-content-layout">
    <div class="art-content-layout-row">
    <div class="art-layout-cell layout-item-1" style="width: 33%" >
        <h3><span style="color: rgb(147, 230, 78);">Based on user feedback</span></h3><p><span style="font-size: 14px;">We always adjust our product elementary proportions according to the feedback we get from end-users of our branded products. We have professionals who conduct some surveys as well as statical inference on the feedback data .</span><br></p><p><img width="139" height="210" alt="" class="art-lightbox" src="images/Fotolia_5170186_X-01.jpg"><img width="139" height="210" alt="" class="art-lightbox" src="images/Fotolia_4837644_X-04.jpg"><span style="font-size: 14px;"><br></span></p>
    </div><div class="art-layout-cell layout-item-1" style="width: 34%" >
        <h3><span style="color: rgb(147, 230, 78);">Reliable</span></h3><p><span style="font-size: 14px;">Our services are reliable and we always strive to meet our customers needs in every circumstance</span><span style="color: rgb(147, 230, 78);"><br></span></p><p><img width="225" height="225" alt="" class="art-lightbox" src="images/shutterstock_59193421-09.jpg"><span style="font-size: 14px;"><br></span></p><p><br></p>
    </div><div class="art-layout-cell layout-item-1" style="width: 33%" >
        <h3><span style="color: rgb(147, 230, 78);">Wide coverage</span></h3><p><span style="font-size: 14px;">We are currently &nbsp;operational in more three countries and we are still expanding. Our goal is to supply locally made tobacco products in all Southern African countries</span><span style="color: rgb(147, 230, 78);"><br></span></p><p><img width="225" height="225" alt="" class="art-lightbox" src="images/Fotolia_28025822_X-03.jpg"><br></p>
    </div>
    </div>
</div>
</div>


</article></div>
                    </div>
                </div>
            </div><footer class="art-footer">
<p>United Tobacco Group,Copyright © 2019, . All Rights Reserved.</p>
</footer>

    </div>

</div>


</body></html>