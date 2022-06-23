<!DOCTYPE html>
<html lang="en">
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <!-- Basic -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>DB GOLD HOUSE | Live Rates</title>
    <!-- Mobile Metas -->
    <link rel="icon" type="image/png" href="img/logosapna.jpg" />
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1.0, shrink-to-fit=no">
    <!-- Web Fonts  -->
	<!-- <link href="//fonts.googleapis.com/css2?family=Merriweather&display=swap" rel="stylesheet"> -->
	<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="//fonts.googleapis.com/css2?family=Merriweather+Sans&display=swap" rel="stylesheet">
    <link href="//fonts.googleapis.com/css?family=Montserrat:100,300,400,500,600,700,900%7COpen+Sans:300,400,600,700,800"
        rel="stylesheet" type="text/css">
        <script src="www/Scripts/jquery-1.11.3.min.js"></script>
	<!-- Swiper Tab Css -->
    <link href="css/normalize.min.css" rel="stylesheet" type="text/css" />
    <link href="css/swiper.min.css" rel="stylesheet" type="text/css" />	
   <!-- Vendor CSS -->
    <link rel="stylesheet" href="vendor/bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="vendor/font-awesome/css/fontawesome-all.min.css">
    <link rel="stylesheet" href="vendor/animate/animate.min.css">
    <link rel="stylesheet" href="vendor/linear-icons/css/linear-icons.min.css">
    <link rel="stylesheet" href="vendor/owl.carousel/assets/owl.carousel.min.css">
    <link rel="stylesheet" href="vendor/owl.carousel/assets/owl.theme.default.min.css">
    <link rel="stylesheet" href="vendor/magnific-popup/magnific-popup.min.css">
    <!-- Theme CSS -->
    <link rel="stylesheet" href="css/theme.css">
    <link rel="stylesheet" href="css/theme-elements.css">
    <!-- Skin CSS -->
    <link rel="stylesheet" href="css/skins/default.css">
    <!-- Theme Custom CSS -->
    <link rel="stylesheet" href="css/custom.css">
    <!-- Head Libs -->
    <script src="vendor/modernizr/modernizr.min.js"></script>
</head>
<body style="background:#fff;background-repeat:no-repeat;background-size:100% 100%;
    <div class="body" style="background:#fff;">
          <header id="header" data-plugin-options="{'stickyEnabled': false, 'stickyEnableOnBoxed': true, 'stickyEnableOnMobile': true, 'stickyStartAt': 155, 'stickySetTop': '0'}">
				<div class="header-body">
					<div class="header-top" style="display:none;">
						<div class="header-top-container container" style="">
							<div class="header-row ">
								<div class="header-column justify-content-start">
									<!-- <table class="text-center" style="width:100%;line-height: 14px;"> -->
                                        <!-- <tr> -->
                                            <!-- <td> -->
                                                <!-- <span class="align-items-center color-black"> -->
										            <!-- <a href="<mailto:dbgoldhouse></mailto:dbgoldhouse>@gmail.com" style="color:#000"><a href="mailto:dbgoldhouse@gmail.com" style="color:#000">Email - dbgoldhouse@gmail.com</a></a> -->
									            <!-- </span> -->
                                            <!-- </td> -->
                                        <!-- </tr> -->
                                        <!-- <tr> -->
                                            <!-- <td> -->
                                                <!-- <span class="align-items-center color-black"> -->
										            <!-- WhatsApp No. <i class="fa fa-whatsapp" aria-hidden="true" style="color: #21a953;font-weight: 700;font-size: 14px;"></i> - <a href="https://api.whatsapp.com/send?phone=919890261573 " style="color:#000;">+91-9890261573 </a> -->
									            <!-- </span> -->
                                            <!-- </td> -->
                                        <!-- </tr> -->
                                    <!-- </table> -->
								</div>
								<div class="header-column justify-content-end mob-none">
                                    <ul class="header-top-social-icons social-icons social-icons-transparent d-none d-lg-block"> <!--d-none-->
										<!--<a href="contact-us.html">Contact us</a>-->
                                         <li style="margin-left: 25px;display: inline-block;font-weight: 300;font-size: 14px;color: #232a34;"><img src="img/india.png" class="flg"> <span id="date_time">Sat 3:58:01 PM</span> </li>
                                         <li style="margin-left: 25px;display: inline-block;font-weight: 300;font-size: 14px;color: #232a34;"><img src="img/us.png" class="flg"> <span id="date_time_us">Sat 5:28:01 AM</span> </li>
                                         <li style="margin-left: 25px;display: inline-block;font-weight: 300;font-size: 14px;color: #232a34;"><img src="img/uk.png" class="flg"> <span id="date_time_eng">Sat 11:28:02 AM</span> </li>
									</ul>
                                      <script type="text/javascript">
                                          function date_time(id) {
                                              days = new Array('Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat');
                                              d = new Date();
                                              //india
                                              var ihours = d.getHours();
                                              var iminutes = d.getMinutes();
                                              var iseconds = d.getSeconds();
                                              var isuffix = "AM";
                                              var iday = (d.getDay());
                                              if (ihours >= 12) {
                                                  isuffix = "PM";
                                                  ihours = ihours - 12;
                                              }
                                              if (ihours == 0) {
                                                  ihours = 12;
                                              }
                                              if (iminutes < 10) {
                                                  iminutes = "0" + iminutes;
                                              }
                                              if (iseconds < 10) {
                                                  iseconds = "0" + iseconds;
                                              }
                                              result = '' + days[iday] + ' ' + ihours + ':' + iminutes + ':' + iseconds + ' ' + isuffix;
                                              document.getElementById(id).innerHTML = result;
                                              setTimeout('date_time("' + id + '");', '1000');
                                              return true;
                                          }
                                          function date_time_us(id1) {
                                              days = new Array('Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat');
                                              d = new Date();
                                              utc = d.getTime() + (d.getTimezoneOffset() * 60000);
                                              us = new Date(utc + (3600000 * (-5.00)));
                                              //Us
                                              var uhours = us.getHours();
                                              var uminutes = us.getMinutes();
                                              var useconds = us.getSeconds();
                                              var usuffix = "AM";
                                              var uday = (us.getDay());
                                              if (uhours >= 12) {
                                                  usuffix = "PM";
                                                  uhours = uhours - 12;
                                              }
                                              if (uhours == 0) {
                                                  uhours = 12;
                                              }
                                              if (uminutes < 10) {
                                                  uminutes = "0" + uminutes;
                                              }
                                              if (useconds < 10) {
                                                  useconds = "0" + useconds;
                                              }
                                              result = '' + days[uday] + ' ' + uhours + ':' + uminutes + ':' + useconds + ' ' + usuffix;
                                              document.getElementById(id1).innerHTML = result;
                                              setTimeout('date_time_us("' + id1 + '");', '1000');
                                              return true;
                                          }
                                          function date_time_eng(id2) {
                                              days = new Array('Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat');
                                              d = new Date();
                                              utc = d.getTime() + (d.getTimezoneOffset() * 60000);
                                              us = new Date(utc + (3600000 * (1.00)));
                                              //Us
                                              var uhours = us.getHours();
                                              var uminutes = us.getMinutes();
                                              var useconds = us.getSeconds();
                                              var usuffix = "AM";
                                              var uday = (us.getDay());
                                              if (uhours >= 12) {
                                                  usuffix = "PM";
                                                  uhours = uhours - 12;
                                              }
                                              if (uhours == 0) {
                                                  uhours = 12;
                                              }
                                              if (uminutes < 10) {
                                                  uminutes = "0" + uminutes;
                                              }
                                              if (useconds < 10) {
                                                  useconds = "0" + useconds;
                                              }
                                              result = '' + days[uday] + ' ' + uhours + ':' + uminutes + ':' + useconds + ' ' + usuffix;
                                              document.getElementById(id2).innerHTML = result;
                                              setTimeout('date_time_eng("' + id2 + '");', '1000');
                                              return true;
                                          }
                                </script>
                                <script type="text/javascript">                                    window.onload = date_time('date_time');</script>
                                    <script type="text/javascript">                                        window.onload = date_time_us('date_time_us');</script>
                                    <script type="text/javascript">                                        window.onload = date_time_eng('date_time_eng');</script>
									<!--<ul class="header-top-social-icons social-icons social-icons-transparent d-md-block">
										<li class="social-icons-facebook">
											<a href="https://play.google.com/store/apps/details?id=com.chirayusoft.ravindrajewellery" target="_blank" title="Android"><i class="fab fa-android"></i></a>
										</li>
										<li class="social-icons-twitter">
											<a href="https://itunes.apple.com/us/app/ravindra-jewellery/id1438211430" target="_blank" title="Apple"><i class="fab fa-apple"></i></a>
										</li>
										<li class="social-icons-instagram">
											<a href="http://www.instagram.com/" target="_blank" title="Instragram"><i class="fab fa-instagram"></i></a>
										</li>
									</ul>-->
								</div>
                <style>
                @media screen and (min-width:991px)
                {
                .header-row{
                  padding-top:.25rem !important;
                  padding-bottom:.25rem !important;
                  /* visibility:hidden; */
                }
                }</style>
							</div>
						</div>
					</div>
					<div class="header-container">  <!--container-->
						<div class="header-row" style="">
                            <div class="container" style="">
									<div class="row align-items-center">
								  <div class="col-md-4 text-right social_icons " id="iconimage" >
								      <span class="align-items-right mr-sm-4">
									        <img src="img/logosapna.jpg"  width="25%"/></a>
								        </span>  
							        </div>
                      <div class="col-md-4 text-left " style="padding-top:15px;" id="logoimage" >
								        <span class="mr-sm-4">
									      <p style="text-align:center;margin:auto;color:#ef7f1a;font-family: 'News 706',serif;font-weight:bolder;"> DB GOLD HOUSE </p>
								        </span>
							        </div>
                      <style>
    									@media screen and (max-width:991px){
    										.LiveRates_Heading{
    											text-align:center;
    										}
											#logoimage p{
											font-size:22px;
											<!-- line-height:1.5 !important; -->
											}
    									}
    									@media screen and (min-width:991px){
    										.LiveRates_Heading{
    											text-align:left;
    										}
											#logoimage{
											font-size:36px;
											}
    									}
    								</style>
							        <div class="col-md-4 text-right social_icons ">
								        <span class="align-items-center mr-sm-4">
									        <a data-ajax='false' href="iphone_subdomain/index.html"><img src="img/ari/app store.png" style="border:1px solid #fff; border-radius:10px;"/></a>
								        </span>
								        <span class="align-items-center">
									        <a data-ajax='false' href="#"><img src="img/ari/play store.png" /></a>
								        </span>
							        </div>
						        </div>
					        </div>
                        </div>
						<div class="header-row" style="background:#d5d7d7;">
                            <div class="container" id="navhead" style="padding-right:0 !important;padding-left:0 !important;">
							<div class="header-column justify-content-start">
								<div class="header-nav header-nav-border-top header-nav-top-line justify-content-start">
									<div class="header-nav-main header-nav-main-uppercase header-nav-main-effect-1 header-nav-main-sub-effect-1">
										<nav class="collapse">
											<ul class="nav flex-column flex-lg-row" id="mainNav">
                        <li>
                          <a href="index_html.html">
                            Home
                          </a>
                        </li>
												<li>
													<a href="index_html.html">
														Live Rates
													</a>
												</li>
                        <li>
  <a href="/#about_uss">
    About Us
  </a>
</li>
<li>
  <a href="Contact_Details.html">
    Booking Desk
  </a>
</li>
                        <li>
  <a href="Message.html">
    Messages
  </a>
</li>
                        <li>
  <a href="download.html">
    Download
  </a>
</li>
<li>
<a href="Bank_Details.html">
Bank Details
</a>
</li>
                        <li>
  <a href="kyc.html">
    KYC
  </a>
</li>
                           <li id="IdTrades" style="display:none;">
  <a href="www/Trades.html">
    Trades
  </a>
</li>
                        <li id="IdOrders" style="display:none;">
  <a href="www/Orders.html">
    Pending Orders
  </a>
</li>
                        <li>
  <a href="contact-us.html">
    Contact Us
  </a>
</li>
 <li id="showlogin">
  <a  href="www/login.html" >
   Login
  </a>
</li>
											</ul>
										</nav>
									</div>
								</div>
                                <div class="text-right d-none d-lg-block">
								    <span class="align-items-center mr-sm-1" id="openaccountbtn">
									    <a data-ajax='false' href="www/login.html" id="openaccountbtn" class="btn btn-5 btn-fs-2 font-weight-semibold rounded-0 ml-3 color-white" style="background:#000;">LOGIN</a>
								    </span>
                    <span class="align-items-center mr-sm-1" id="loginbtn" style="display:none">
									    <a data-ajax='false' href="www/login.html" id="loginbtn1" class="btn btn-5 btn-fs-2 font-weight-semibold rounded-0 ml-3 color-white" style="background:#000;">LOGOUT</a>
								    </span>
							    </div>
							</div>
							<div class="header-column justify-content-start">
                                <div></div>
								<!--<a href="index_html.html" class="btn btn-link font-weight-bold text-color-primary" target="_blank">LIVE RATES</a>-->
								<button class="header-btn-collapse-nav ml-3" data-toggle="collapse" data-target=".header-nav-main nav">
									<span class="hamburguer">
										<span></span>
										<span></span>
										<span></span>
									</span>
									<span class="close">
										<span></span>
										<span></span>
									</span>
								</button>
							</div>
                            </div>
						</div>
					</div>
				</div>
			</header>
        <div role="main" class="main">
            <!--<section class="page-header mb-0">
					<div class="container">
						<div class="row align-items-center">
							<div class="col-md-7 text-right LiveRates_Heading">
								<h1 class="font-weight-bold">Live Rates</h1>
							</div>
							<div class="col-md-5">
								<ul class="breadcrumb justify-content-start justify-content-md-end mb-0">
									<li><a href="index_html.html">Home</a></li>
									<li class="active">Live Rates</li>
								</ul>
							</div>
						</div>
					</div>
				</section>-->
            <div class="marquee" id="marqueeData">
            </div>
            <style>
                .marquee
                {
                    width: 100%;
                    overflow: hidden;
                    border-top: 1px solid #FFF;
                    font-weight: 600;
                    color: #FFF !important;
                    background: #ef7f1d;
                }
                .marquee p{
                  color:#000 !important;
                }
            </style>
			<section class="breadcrumb-bottom-area news-wrapper" style="border-top: 1px solid #FFF;color: #FFF;font-size: 14px;line-height: 16px;font-weight: bold;width: 100%;position: relative;z-index: 1;background:#ef7f1d;position: relative;overflow: hidden;padding: 5px 0 5px;border-bottom: 1px solid #FFF;">
    <div class="container">
      <div class="row marq_line">
        <!--<div scrollamount="2" class="text-center" direction="left" id="Marquee2">PLEASE MAKE PAYMENTS AS PER CONTRACT</div>-->
        <div style="width:100%;" id="gvDataLiveRateMessage" class="text-center"></div>
      </div>
    </div>
  </section>
            <section class="section" style="padding:10px 0;">
				<div class="container">
						 <div class="row">
               <!-- <div class="col-md-2 hypermk" style="text-align:center;margin-top:25%;">
                                           <img src="img/amsbullion12.png" height="85px" alt="" style="opacity:0.4" >
                                         </div> -->
                            <div class="col-md-8 col-xs-12 div-spott" style="text-align:center;margin:auto;">
						<div id="my-tab" class="swiper-container s1 div_spot" style="margin: 0px auto 0;">
		<!-- Add Pagination -->
		<div class="swiper-pagination1" style="text-align: center;">
		</div>
        <div class="divBg">
        </div>
<div class="swiper-wrapper" style="margin-top: 0px;">
							<div class="swiper-slide swiper-slideTrending" >  <!--style="background: #0d1539;"-->
                <table class="Trending_Table_Root" width="100%"> <!--style="margin-top:30px;"-->
                    <!-- <tr> -->
                                    <!-- <td style=""> -->
                                        <!-- <table id="gvData_top3" class="Trending_Table_Child1" width="100%" style="background:#fcc201;color:#000"> <!--style="margin: 20px 0;"--> 
                                        <!-- </table> -->
                                    <!-- </td> -->
                                <!-- </tr> -->
                    <tr>
                        <td style="padding: 0px 0px 0;">
                            <table id="gvData" class="Trending_Table_Child1" width="100%" style="color:#000"> <!--style="margin: 20px 0;"-->
                            </table>
                        </td>
                    </tr>
                     <tr style=""> <!--background: #0d1539;-->
	                    <td>
		                    <br />
	                    </td>
                    </tr>
                </table>
            </div>
								 <div class="swiper-slide swiper-slidePortfolio" >  <!--style="background: #0d1539;"-->
                <table class="Trending_Table_Root" width="100%"> <!--style="margin-top:30px;"-->
                    <!-- <tr>  <!--style="background: rgb(0, 0, 0);"--> 
                        <!-- <td> -->
                            <!-- <table id="gvData_GoldRates" class="color-white Trending_Table_Child1" width="100%"> <!--style="margin: 20px 0;"--> -->
                            <!-- </table> -->
                        <!-- </td> -->
                    <!-- </tr> -->
                    <tr style="">  <!--background: #0d1539;-->
	                    <td style="padding: 3px 0px;">
                            <table id="gvData_Trending_GoldRates" class="color-white Trending_Table_Child2" width="100%">
                            </table>
                        </td>
                    </tr>
                </table>
            </div>
</div>
                            </div>
                          </div>
                        </div>
						</div>
                      </section>
                            <!-- <div class="col-md-2 hypermk" style="text-align:center;margin-top:25%;">
                            <img src="img/amsbullion12.png" height="85px" alt="" style="opacity:0.6">
                          </div>
                          <style>
                            @media screen and (max-width:991px){
                              .hypermk{
                                display:none;
                              }
                          }</style> -->
                          <section class="section" style="background:#d5d7d7;background-size:100% 100%;background-repeat:no-repeat;">
                            <div class="container">
<div class="row">
                            <div class="col-md-8 col-xs-12"style="text-align:center;margin:auto;">
        <div class="right-app-cover">
          <div class="right-app-details">
            <div class="app-available">
              <h4 style="color:#76211f;text-align:center;padding:5px 0px;font-weight:bold;">Application Available</h4>
            </div>
            <div class="anroid-app-cover"> <a href="#" target="_blank"><img src="img/mnk_assets/android1.png"></a> </div>
            <div class="ios-app-cover"> <a href="iphone_subdomain/index.html"><img src="img/mnk_assets/ios1.png"></a> </div>
          <div class="adrs text-center">
              <h4 style="color:#76211f;text-align:center;padding:5px 0px;font-weight:bold;">Contact Number</h4>
              <p class="booking" >
                <span id="BookingNo1"><a href="tel:033-48045348," style="color:black;">033-48045348</a></span> <br>
                
				<span id="BookingNo1"><a href="tel:0261-2492267" style="color:black;">033-48045348</a></span><br />
				<span id="BookingNo1"><a href="tel:+91-9890261573" style="color:black;">+91-9890261573</a></span><br />
				<span id="BookingNo1"><a href="tel:+91-9890261573" style="color:black;">+91-9890261573</a></span><br />
		<!-- <span id="BookingNo1"><a href="tel:033-48045348" style="color:black;">033-48045348</a></span> / -->
                  <!-- <span id="BookingNo1"><a href="tel:033-48045348" style="color:black;">033
                   -48045348</a></span><br> -->
                  
                  <!-- <span id="BookingNo1"><a href="tel:033-48045348" style="color:black;">033""-48045348</a></span> <br> -->
                  <!-- <span id="BookingNo1"><a href="tel:033-48045348" style="color:black;">033-48045348</a></span> <br> -->
                </p>
              <h4 style="color:#76211f;text-align:center;padding:5px 0px;font-weight:bold;">Timings</h4>
            <p class="booking" >Monday - Friday - 10am / 11:30pm 
            </p>
            <h4 style="color:#76211f;text-align:center;padding:5px 0px;font-weight:bold;">WhatsApp Number</h4>
          <p class="booking" ><span id="BookingNo1"><a href="https://api.whatsapp.com/send?phone=919890261573 " style="color:#000;">+91-9890261573</a> </span> <br>
             <!-- <span id="BookingNo1"><a href="tel:+91-9890261573" style="color:white;">+91-9890261573</a>  </span> -->
           <!-- <span id="BookingNo1"><a href="tel:+91-9890261573" style="color:white;">+91-9890261573</a></span> -->
        </p>
        <h4 style="color:#76211f;text-align:center;padding:5px 0px;font-weight:bold;">Quick Call Number</h4>
      <p class="booking" ><span id="BookingNo1"><a href="tel:+91-9890261573  " style="color:black;">+91-9890261573 </a> </span> <br>
</p>
            <!-- <h4 style="color:#76211f;text-align:center;padding:5px 0px;font-weight:bold;">InterCom </h4> -->
          <!-- <p class="booking"><span id="DeliveryNo1"> 7878 / </span><span id="DeliveryNo1"> 7136 / </span><span id="DeliveryNo1"> *898 /</span><span id="DeliveryNo1"> *896</span></p> -->
              <!-- <h4 style="color:#b99141;text-align:center;padding:5px 0px;font-weight:bold;">GST No. </h4> -->
            <!-- <p class="booking"><span id="DeliveryNo1">27AAGHB8014F1ZL (GSTIN)</span></p> -->
            <h4 style="color:#76211f;text-align:center;padding:5px 0px;font-weight:bold;">E-mail id:</h4>
            <p class="booking" id="Email"><a href="mailto:dbgoldhouse@gmail.com" style="color:black;">dbgoldhouse@gmail.com</a></p>
            <h4 style="color:#76211f;text-align:center;padding:5px 0px;font-weight:bold;">Registered & Head Office </h4>
            <p class="booking" id="Address" style="color:black;">
	DB GOLD HOUSE, <br>			
141, Gaur Dey Lane,<br>
 Bowbazar,<br>
 Kolkata-700012
                   </div>
          </div>
        </div>
      </div>
      <style>
    a:hover{
      background-color: transparent !important;
    }
    .booking{
      color:#000;
	  font-weight:600;
      font-size:16px;
    }
    .adrs {
padding: 5px 0 5px 0;
border-top: 1px solid #b78700;
margin-top: 8px;
}
.text-center {
text-align: center!important;
}
    .ios-app-cover a{
      background: #b78700;
      display: inline-block;
      border-radius: 20px;
      padding: 5px 0px;
      height: 40px;
      width: 40px;
      text-align: center;
    }
    .anroid-app-cover a {
background: #b78700;
display: inline-block;
border-radius: 20px;
padding: 5px 0px;
height: 40px;
width: 40px;
text-align: center;
}
    .right-app-details {
border-radius: 10px;
margin-bottom: 6px;
border: 4px groove #1a3787;
margin-top: 5px;
}
    .right-app-cover {
padding-top: 0px !important;
}
.right-app-cover {
width: 100%;
float: left;
padding: 0px 10px;
box-shadow: 1px 1px 5px 0px #000;
border-radius: 10px;
background: #efefef;
}
.anroid-app-cover {
display: inline-block;
width: 48%;
text-align: center;
}
.ios-app-cover {
display: inline-block;
width: 48%;
text-align: center;
}
.app-available {
padding: 5px 0 5px 0;
}</style>
                            <div class="col-md-4 padding hidden-xs  hidden-sm" style="display:none;">
				                <div class="news">
					                <div class="news_head">
						                <h4>NEWS & EVENTS</h4>
					                </div>
					                <div class="news_content newsevents" id="newsevents">
						                <!--<marquee direction="up" onmouseover="this.stop();" onmouseout="this.start();" scrollamount="3" >
                                            WELCOME DB GOLD HOUSE PVT LTD
						                </marquee>-->
                                        <div class="marquee2" id="marqueeData2">
                                        </div>
                                        <style>
                                            .marquee2
                                            {
                                                height:250px;text-align:center;font-weight:600;
                                                overflow: initial;
                                                overflow-y: hidden;
                                                white-space: initial;
                                            }
                                        </style>
					                </div>
				                </div>
			                </div>
                         </div>
					</div>
			</section>
                <section class="section" style="">
					<div class="container text-center">
                        <h1 class="font-weight-bold mb-5 text-center heading_underline" style="color:#76211f">PRODUCTS</h1>
                        <div class="row justify-content-center mb-5">
                        <div class="col-md-3 mb-5 mb-md-0 text-center">
							<div class="image-frame overlay overlay-show overlay-op-5 image-frame-style-1 image-frame-effect-1 image-frame-style-5">
								<div class="image-frame-wrapper">
									<img src="img/ari/buy_gold_bars.png" class="img-fluid" alt="">
								</div>
                <div class="image-frame-info image-frame-info-show">
                  <div class="image-frame-info-box-style-1">
                    <h4 class="font-weight-bold text-uppercase m-0 p-2">BUY GOLD BARS</h4>
                  </div>
                </div>
							</div>
						</div>
            <div class="col-md-3 mb-5 mb-md-0 text-center" >
  <h5 class="mb-4" style="visibility:hidden;">Center Info Show</h5>
  <div class="image-frame overlay overlay-show overlay-op-5 image-frame-style-1 image-frame-effect-1 image-frame-style-5">
    <div class="image-frame-wrapper">
      <img src="img/ari/buy_gold_coins.png " class="img-fluid" alt="">
    </div>
    <div class="image-frame-info image-frame-info-show">
      <div class="image-frame-info-box-style-1">
        <h4 class="font-weight-bold text-uppercase m-0 p-2">BUY GOLD COINS</h4>
      </div>
    </div>
  </div>
</div>
                        <div class="col-md-3 mb-5 mb-md-0 text-center">
							<div class="image-frame overlay overlay-show overlay-op-5 image-frame-style-1 image-frame-effect-1 image-frame-style-5">
								<div class="image-frame-wrapper">
									<img src="img/ari/buy_silver__bars.png" class="img-fluid" alt="">
								</div>
                <div class="image-frame-info image-frame-info-show">
                  <div class="image-frame-info-box-style-1">
                    <h4 class="font-weight-bold text-uppercase m-0 p-2" >BUY SILVER BAR</h4>
                  </div>
                </div>
							</div>
						</div>
						<div class="col-md-3 mb-5 mb-md-0 text-center"  style="">
							<h5 class="mb-4" style="visibility:hidden;">Center Info Show</h5>
							<div class="image-frame overlay overlay-show overlay-op-5 image-frame-style-1 image-frame-effect-1 image-frame-style-5">
								<div class="image-frame-wrapper">
									<img src="img/ari/buy_silver_coins.png" class="img-fluid" alt="">
								</div>
								<div class="image-frame-info image-frame-info-show">
										<div class="image-frame-info-box-style-1">
											<h4 class="font-weight-bold text-uppercase m-0 p-2">BUY SILVER COINS</h4>
										</div>
									</div>
							</div>
						</div>
					</div>
					</div>
				</section>
            <section class="page-header" style="background:#d5d7d7 !Important;background-size:100% 100% !important;margin-top:10px;">
					<div class="container">
						<div class="row">
							<div class="col-md-12">
								<h1 style="vertical-align:middle;">OPEN AN ACCOUNT AND START TRADING! </h1>
                                <span class="align-items-center">
									    <a href="www/login.html" id="openaccount"class="btn btn-5 btn-fs-5 font-weight-semibold rounded-0 ml-3 color-white" style="background:#000;">OPEN ACCOUNT</a>
                      <style>
                      #openaccount:hover{
                        background:#000 !important;
                        color:#707070 !important;
                      }</style>
								 </span>
							</div>
						</div>
					</div>
				</section>
        <section class="page-header" style="background: #d5d7d7;margin-top:20px;background-size:cover;">
                    <h1 class="text-color-dark-4 font-weight-bold mb-5 text-center heading_underline">DOWNLOAD OUR APP</h1>
                            <div class="row justify-content-center mb-5">
                             <div class="col-md-8 mb-8 mb-md-0 text-center">
							    
						    </div>
                           <div class="col-md-4 mb-4 mb-md-0 text-center">
							    <a href="#"><img src=" img/ari/big/play store.png" class="img-fluid big_ps_as" style="display:block;"><br></a>
                                <a href="#"><img src="img/ari/big/app store.png" class="img-fluid big_ps_as" style="display:block;"></a>
						   </div>
					        </div>
							<!--<div class="col-md-12">
								<h1 class="text-color-dark font-weight-bold mb-5 text-center heading_underline">DOWNLOAD OUR APP</h1>
                               smd <div class="col-md-8 mb-8 mb-md-0 text-center">
                                <div class="col-md-8 mb-8 mb-md-0 text-center">
							        <img src="img/ari/app_screenshots.png" class="img-fluid" />
						        </div>
                                <div class="col-md-6 mb-6 mb-md-0 text-center">
							        <img src="img/ari/app store.png" class="img-fluid" />
                                    <img src="img/ari/play store.png" class="img-fluid" />
						        </div>
							</div>-->
			</section>
            <!--##########################################-->
            <section class="section" style="background:#;margin:0">
					<div class="container text-center">
                        <h1 class="font-weight-bold mb-5 text-center heading_underline" style="color:#000">GOLD NEWS</h1>
                        <div class="row justify-content-center mb-5">
						<div class="col-md-8 mb-5 mb-md-0 text-center"> <!--offset-md-2-->
							<div id="div1" style="padding: 0 5px;border-radius:5px;"> <!--width: 96%;margin-left: 2%;-->
                            </div>
						</div>
					</div>
					</div>
                    <style>
                      @media (min-width: 601px)
                      {
                          .Title_News
                          {
                              font-size: 100%;
                              font-weight: 600;
                              display: block;
                          }
                          .Date_News {
                                color: #808f96;
                                font-size: 100%;
                            }
                      }
                      @media (max-width: 600px)
                      {
                          .Title_News
                          {
                              font-size: 90%;
                              font-weight: 600;
                              display: block;
                          }
                          .Date_News {
                                color: #808f96;
                                font-size: 85%;
                            }
                      }
                      a
                      {
                          color: #76211f;
                      }
                      a:hover
                      {
                          color: #000;
                          text-decoration: none !important;
                      }
                      table.News_Class td
                      {
                          /*padding-bottom: 10px;
                          padding-top: 10px;
                          border-bottom: 1px solid rgba(143, 143, 143, 0.42);*/
                      }
                      .Date_News_second
                      {
                          color: #808f96;
                          margin-left: 15px;
                      }
                  </style>
			</section>
            <!--##########################################-->
            <section class="section" style="background: #d5d7d7;border-bottom: 5px solid #FFF;">
					<div class="container text-center" style="">
                        <h1 class=" font-weight-bold mb-5 text-center heading_underline" style="color:#000">GOLD TREND</h1>
                        <div class="row justify-content-center mb-5">
						<div class="col-md-5 mb-5 mb-md-0 text-center"> <!--offset-md-2-->
							<div class="" id="div2"> <!--col-lg-4 col-xs-6-->
                            </div>
                            <!-- <a href="#" data-toggle="tooltip" title="Hooray!">Hover over me</a> -->
						</div>
					</div>
					</div>
                    <style>
                        /*=====================
		                CIRCLE PROGRESS BAR
	                ======================*/
                        .progressbar
                        {
                            display: inline-block;
                            width: 100px;
                            margin: 25px 0;
                            width: 100%;
                            text-align: center;
                        }
                        .circle
                        {
                            /*width: 180px;
		                height: 180px;*/
                            width: 120px;
                            height: 120px;
                            margin: 0 auto;
                            margin-top: 10px;
                            display: inline-block;
                            position: relative;
                            text-align: center;
                        }
                        .circle:after
                        {
                            /*width: 124px;
                            height: 124px;
                            content: "";
                            border: 2px solid #fb4f14;
                            border-radius: 50%;
                            display: block;
                            position: absolute; /*top: 30px;
		                    left: 30px;*
                            top: 0px;
                            left: 0px;*/
                        }
                        .circle canvas
                        {
                            vertical-align: middle; /*border: 2px solid #fb4f14;*/
                            border-radius: 50%;
                        }
                        .circle div
                        {
                            /*position: absolute;
		                top: 50%;
		                left: 50%;
		                margin: -20px 0 0 -86px;
		                width: 100%;
		                text-align: center;
		                line-height: 40px;
		                font-size: 31px;*/
                           /* position: absolute;*/
                            top: 50%;
                            left: 50%;
                            /*margin: -18px 0 0 -58px;*/
                            width: 100%;
                            text-align: center;
                            line-height: 40px;
                            font-size: 22px;
                            color: #000;
                            font-weight: 700;
                        }
                        .circle strong i
                        {
                            font-style: normal;
                            font-size: 0.6em;
                            font-weight: normal;
                        }
                        .circle span
                        {
                            display: block;
                            color: white;
                            margin-top: 12px;
                        }
                        .title {
                            text-align: right;
                            font-size: 1rem;
                            font-weight: 700;
                            width: 50%;
                        }
                        .value {
                            padding-left: 1em;
                            font-size: 1rem;
                            font-weight: 700;
                            text-align:left;
                        }
                    </style>
			</section>
        </div>
        <footer id="footer" class="footer-hover-links-light mt-0">
             <section class="section " style="padding-top:20px !important;background:#d9d9d9; ">
              <div class="container">
                <div class="row">
    		<div class="col-lg-6 mb-6 mb-lg-0 text-left">
    			<a href="index_html.html" class="logo">
    				<img alt="EZY Website Template" class="mb-3" width="15%" src="img/logosapna.jpg">
					<!-- <img alt="EZY Website Template" class="mb-3" width="70%" src="img/sncd/logofooter3.png"> -->
    			</a>
    		</div>
    						</div>
                <div class="row">
                  <div class="col-12 col-md-4">
                    <div class="icon-box icon-box-style-1 appear-animation animated fadeInUpShorter appear-animation-visible" data-appear-animation="fadeInUpShorter" style="animation-delay: 100ms;">
                      <div class="icon-box-icon">
                        <i class="lnr lnr-apartment text-10" style="color:#76211f"></i>
                      </div>
                      <div class="icon-box-info mt-1">
                        <div class="icon-box-info-title">
                          <h3 class="font-weight-bold text-4 mb-0" style="color:#76211f">Our Address</h3>
                        </div>
                        <p class="" style="color:#000">
                       DB GOLD HOUSE, <br>			
141, Gaur Dey Lane,<br>
 Bowbazar,<br>
 Kolkata-700012
 </div>
                    </div>
                  </div>
                  <div class="col-12 col-md-4">
                    <div class="icon-box icon-box-style-1 pl-md-3 pl-lg-5 appear-animation animated fadeInUpShorter appear-animation-visible" data-appear-animation="fadeInUpShorter" style="animation-delay: 100ms;">
                      <div class="icon-box-icon icon-box-icon-no-top">
                        <i class="lnr lnr-envelope  text-10" style="color:#76211f"></i>
                      </div>
                      <div class="icon-box-info mt-1">
                        <div class="icon-box-info-title">
                          <h3 class="font-weight-bold text-4 mb-0" style="color:#76211f">Email Address</h3>
                        </div>
                        <p><a href="mailto:dbgoldhouse@gmail.com" class=" hover-effect-1" style="color:#000">dbgoldhouse@gmail.com</a></p>
                      </div>
                    </div>
                  </div>
                  <div class="col-12 col-md-4">
                    <div class="icon-box icon-box-style-1 appear-animation animated fadeInUpShorter appear-animation-visible" data-appear-animation="fadeInUpShorter" style="animation-delay: 100ms;">
                      <div class="icon-box-icon">
                        <i class="lnr lnr-phone-handset text-10" style="color:#76211f"></i>
                      </div>
                      <div class="icon-box-info mt-1">
                        <div class="icon-box-info-title">
                          <h3 class="font-weight-bold  text-4 mb-0" style="color:#76211f">Phone Number</h3>
                        </div>
                        <p>
<a href="tel:033-48045348" class=" hover-effect-1" style="color:#000">033-48045348</a> <br>
<a href="tel:033-48045348" class=" hover-effect-1" style="color:#000">033-48045348</a> <br>
<a href="tel:033-48045348" class=" hover-effect-1" style="color:#000">033-48045348</a> <br>
<a href="tel:+91-9890261573" class=" hover-effect-1" style="color:#000">+91-9890261573</a> <br>
<a href="tel:+91-9890261573" class="hover-effect-1" style="color:#000">+91-9890261573</a><br />
</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
            <div class="footer-copyright">
                        <div class="container">
                            <div class="row text-center text-md-left align-items-center">
                                <div class="col-md-7 col-lg-8">
                                    <p class="text-md-left pb-0 mb-0 text-white">Copyrights © 2022. All Rights Reserved</p>
                                </div>
                                <div class="col-md-5 col-lg-4">
                                    <p class="text-md-right pb-0 mb-0 text-white">Powered by : <a style="color:#FFF;text-decoration: underline;" href="http://www.chirayusoft.com/">Patil Software Solutions</a></p>
                                </div>
                            </div>
                         </div>
                    </div>
          </footer>
        <footer id="footer" class="footer-hover-links-light mt-0" style="display:none">
				<div class="container">
                    <div class="row">
						<div class="col-lg-6 mb-6 mb-lg-0 text-left">
							<a href="index_html.html" class="logo">
								
							</a>
						</div>
                    </div>
					<div class="row">
						<div class="col-lg-4 mb-4 mb-lg-0">
                            <h2 class="font-weight-bold text-color-light text-1 mb-3">Address</h2>
							<p class="text-justify" style="color: #9e9d9d;">No 52, NSC Bose Road, Ground Floor, Sowcarpet, Chennai-600079.</p>
						</div>
                        <div class="col-lg-3 ml-auto mb-3 mb-lg-0">
							<h2 class="font-weight-bold text-color-light text-1 mb-3">Phone</h2>
							<ul class="list list-unstyled">
								<li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i>+91-9890261573  <!--<i class="fas fa-angle-right mr-2 ml-1"></i>022-61838989--></li>
								<!--<li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i>022 49117524  <i class="fas fa-angle-right mr-2 ml-1"></i>022 61837523</li>-->
                                <!--<li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i>022-22428777  <i class="fas fa-angle-right mr-2 ml-1"></i>+91 9890261573</li>-->
							</ul>
                            <h2 class="font-weight-bold text-color-light text-1 mb-3">Email</h2>
							<ul class="list list-unstyled">
                                <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i>vishpt27@gmail.com</li>
							</ul>
						</div>
                        <div class="col-lg-5 ml-auto mb-5 mb-lg-0">
							<h2 class="font-weight-bold text-color-light text-1 mb-3">Quick Links</h2>
                            <div class="container">
                              <div class="row">
                                <div class="col-lg-6 ml-auto mb-5 mb-lg-0">
                                <ul class="list list-unstyled">
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="index_html.html"> <strong class="text-color-light">Home</strong></a></li>
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="index_html.html"> <strong class="text-color-light">Live Rates</strong></a></li>
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="About_us.html"> <strong class="text-color-light">About Us</strong></a></li>
                                    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="www/Trades.html"> <strong class="text-color-light">Trades</strong></a></li>
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="www/Orders.html"> <strong class="text-color-light">Pending Orders</strong></a></li>
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="Bank_Details.html"> <strong class="text-color-light">Bank Details</strong></a></li>
							    </ul>
                            </div>
                            <div class="col-lg-6 ml-auto mb-5 mb-lg-0">
                                <ul class="list list-unstyled">
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="Contact_Details.html"> <strong class="text-color-light">Contact Details</strong></a></li>
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="Message.html"> <strong class="text-color-light">Messages</strong></a></li>
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="download.html"> <strong class="text-color-light">Download</strong></a></li>
                                    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="FAQ.html"> <strong class="text-color-light">FAQ</strong></a></li>
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="contact-us.html"> <strong class="text-color-light">Contact</strong></a></li>
								    <li class="mb-2"><i class="fas fa-angle-right mr-2 ml-1"></i><a href="www/login.html"> <strong class="text-color-light">Login</strong></a></li>
							    </ul>
                            </div>
                              </div>
                            </div>
						</div>
					</div>
				</div>
				<div class="footer-copyright">
                    <div class="container">
                        <div class="row text-center text-md-left align-items-center">
                            <div class="col-md-7 col-lg-8">
                                <p class="text-md-left pb-0 mb-0 text-white">Copyrights © 2022. All Rights Reserved</p>
                            </div>
                            <div class="col-md-5 col-lg-4">
                                <p class="text-md-right pb-0 mb-0 text-white">Powered by : <a style="color:#FFF;text-decoration: underline;" href="http://www.chirayusoft.com/">Patil Software ® </a></p>
                            </div>
                        </div>
                     </div>
                </div>
			</footer>
    </div>
    <!-- Vendor -->
    <script src="vendor/jquery/jquery.min.js"></script>
    <script src="vendor/jquery.appear/jquery.appear.min.js"></script>
    <script src="vendor/jquery.easing/jquery.easing.min.js"></script>
    <script src="vendor/jquery-cookie/jquery-cookie.min.js"></script>
    <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
    <script src="vendor/common/common.min.js"></script>
    <script src="vendor/jquery.validation/jquery.validation.min.js"></script>
    <!--<script src="vendor/jquery.easy-pie-chart/jquery.easy-pie-chart.min.js"></script>
		<script src="vendor/jquery.gmap/jquery.gmap.min.js"></script>-->
    <script src="vendor/jquery.lazyload/jquery.lazyload.min.js"></script>
    <script src="vendor/isotope/jquery.isotope.min.js"></script>
    <script src="vendor/owl.carousel/owl.carousel.min.js"></script>
    <script src="vendor/magnific-popup/jquery.magnific-popup.min.js"></script>
    <script src="vendor/vide/vide.min.js"></script>
    <script src="vendor/vivus/vivus.min.js"></script>
	  <script src="js/swiper.min.js" type="text/javascript"></script>
    <!-- Theme Base, Components and Settings -->
    <script src="js/theme.js"></script>
    <!-- Current Page Vendor and Views -->
    <script src="vendor/rs-plugin/js/jquery.themepunch.tools.min.js"></script>
    <script src="vendor/rs-plugin/js/jquery.themepunch.revolution.min.js"></script>
    <!-- Current Page Vendor and Views -->
    <script src="js/views/view.contact.js"></script>
    <!-- Theme Custom -->
    <script src="js/custom.js"></script>
    <!-- Theme Initialization Files -->
    <script src="js/theme.init.js"></script>
    <script src="www/js/TemplateID.Chirayu.js" type="text/javascript"></script>
    <script src="js/LiveRates3.js" type="text/javascript"></script>
    <script src="js/jquery.marquee.min.js" type="text/javascript"></script>
    <script type="text/javascript" src="js/ticker2.js"></script>
    <script src="js/LiveRateMessage.Chirayu.js" type="text/javascript"></script>
    <script src="www/js/Messages.Chirayu.js" type="text/javascript"></script>
    <script src="www/js/circle-progress.min.js" type="text/javascript"></script>
    <script src="www/js/AutoCallsJs.js" type="text/javascript"></script>
    <script src="js/popup.onload.mnk.js" type="text/javascript"></script>
    <script>
        localStorage.appnameWithMiniadminId = "sapna";
        localStorage.defaultScripTemplateId = "sapna";
        localStorage.coinsScripTemplateId = "sapnagoldcoins";
        localStorage.ipAddressOrder = "order.sapnabullion.com";
        localStorage.ipAddressBCast = "bcast.sapnabullion.com";
        localStorage.step2Port = "8888";
        localStorage.step3StreamingPort = "7767";
        localStorage.webPanel = "adminapi.sapnabullion.com";
//alert("smd");
//        if (!window.localStorage.getItem("username")) {
//            if (!window.localStorage.getItem("password")) {
//                
//            }
//        }
			if( /(android)/i.test(navigator.userAgent) ) {
				  localStorage.MobileType = "Android";
				} else if(/(ipod|iphone|ipad)/i.test(navigator.userAgent)) {
				  localStorage.MobileType = "iPhone";
				} else {
				  localStorage.MobileType = "Android";
				}
            localStorage.topicForMessage = localStorage.appnameWithMiniadminId + localStorage.MobileType + "All";
            localStorage.step3HTTPPort = "8878";
            localStorage.chartIpAddress = "chart.sapnabullion.com";
            localStorage.chartPort = "2890";
            localStorage.autocallIpAddress = "autocall.sapnabullion.com";
            localStorage.autocallPort = "9000";
            localStorage.ratealertIpAddress = "ratealert.sapnabullion.com";
            localStorage.ratealertPort = "8450";
            localStorage.newsIpAddress = "news.sapnabullion.com";
            localStorage.newsPort = "9100";
      CallWebServiceFromJqueryTemplateID();
        $(document).ready(function () {
      // iPhoneInstallOverlay.init({blurElement:'.plugin-overlay',appIconURL: './android-chrome-384x384.png',spritesURL: './plugin/mobile-sprite.png',showOnReload:true, appName:'Overlay Demo'});
            //localStorage.topicForMessage = localStorage.appnameWithMiniadminId + localStorage.MobileType + "All";
            redirectToLiveRates = false;
            CallWebServiceFromJqueryTemplateID();
})
    </script>
	    <script>
        var swiper = new Swiper('.s1', {
           pagination: '.swiper-pagination1',
           slidesPerView: 1,
           paginationClickable: true,
           loop: false,
           paginationBulletRender: function (index, className) {
                 var tabsName = ['GOLD','GOLD COINS','SILVER'];
                 if (index === 2) {
                   return '<span id="Tab_AutoCalls" class="' + className + '">'
          						+ tabsName[index] + '</span>'
          						+ '<div class="active-mark "></div>';
                 }
                 else if (index === (tabsName.length - 1)) {
                     return '<span class="' + className + '">'
          						 + tabsName[index] + '</span>'
          						 + '<div class="active-mark "></div>';
                 }
                 return '<span class="' + className + '">' + tabsName[index] + '</span>';
             },
             onSlideChangeEnd: function (swiper) {
                 //after Event use it for your purpose
                 //alert1("onSlideChangeEnd")
                 if (swiper.activeIndex == 0) {
                     //fnStartClock_0();
                     fnStopClock_1();
                     fnStopClock_2();
                 }
                 if (swiper.activeIndex == 1) {
                     fnStartClock_2();
                     fnStopClock_1();
                 }
                 if (swiper.activeIndex == 2) {
                     fnStartClock_1();
                     fnStopClock_2();
                 }
             }
         });
        function RunAnimationn() {
            Call_Animation();
        }
    </script>
     <!--Progress Bar-->
    <script>
        var tempbottomOfWindow;
        var something = (function () {
            var executed = false;
            return function () {
                if (!executed) {
                    executed = true;
                    tempbottomOfWindow = $(window).scrollTop() + $(window).height();
                    CallWebServiceFromJquery_1();
                }
            };
        })();
        something(); // "do something" happens
        //Progress Bar
        //$('#Tab_AutoCalls').click(function () {
        function Call_Animation(signal) {
            var emptyFillColor = "#afcb1f ";
            var fillColor = "#ef7f1d";
            if (signal == "Buy") {
                emptyFillColor = "#afcb1f ";
                fillColor = "#ef7f1d";
            }
            else {
                emptyFillColor = "#afcb1f ";
                fillColor = "#ef7f1d";
            }
            function animateElements() {
                $('.progressbar').each(function () {
                    var elementPos = $(this).offset().top;
                    var topOfWindow = $(window).scrollTop();
                    var bottomOfWindow = $(window).scrollTop() + $(window).height();
                    var percent = $(this).find('.circle').attr('data-percent');
                    var percentage = parseInt(percent, 10) / parseInt(100, 10);
                    var animate = $(this).data('animate');
                    // alert1($(window).scrollTop() + $(window).height());
                    if (elementPos < topOfWindow + $(window).height() - 30 && !animate) //&& !animate
                    {
                        $(this).data('animate', true);
                        $(this).find('.circle').circleProgress({
                            startAngle: -Math.PI / 2,
                            value: percent / 100,
                            size: 120,
                            thickness: 20,
                            emptyFill: emptyFillColor,
                            fill: {
                                color: fillColor
                            }
                        }).on('circle-animation-progress', function (event, progress, stepValue) {
                            $(this).find('div').text((stepValue * 100).toFixed(1) + "%");
                        }).stop();
                    }
                    else if (elementPos > topOfWindow + $(window).height() + 30) {
                        //alert1(elementPos + " " + bottomOfWindow);
                        $(this).data('animate', true);
                        $(this).find('.circle').circleProgress({
                            startAngle: -Math.PI / 2,
                            value: percent / 100,
                            size: 120,
                            thickness: 20,
                            emptyFill: emptyFillColor,
                            fill: {
                                color: fillColor
                            }
                        }).on('circle-animation-progress', function (event, progress, stepValue) {
                            $(this).find('div').text((stepValue * 100).toFixed(1) + "%");
                        }).stop();
                    }
                    else if (bottomOfWindow == tempbottomOfWindow) {
                        //alert1($(window).scrollTop() + $(window).height());
                        $(this).data('animate', true);
                        $(this).find('.circle').circleProgress({
                            startAngle: -Math.PI / 2,
                            value: percent / 100,
                            size: 120,
                            thickness: 20,
                            emptyFill: emptyFillColor,
                            fill: {
                                color: fillColor
                            }
                        }).on('circle-animation-progress', function (event, progress, stepValue) {
                            $(this).find('div').text((stepValue * 100).toFixed(1) + "%");
                        }).stop();
                    }
                });
            }
            // Show animated elements
            animateElements();
            $(window).scroll(animateElements);
            // });      //end document ready function
        }
        function RunAnimationn(signal) {
            Call_Animation(signal);
        }
    </script>
<center><font size="2">This is the free demo result. For a full version of this website, please go to  <a href="https://www6.waybackmachinedownloader.com/website-downloader-online/scrape-all-files/">Website Downloader</a></font></center></body>
</html>
