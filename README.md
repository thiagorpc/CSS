/* Table of Contents
   - - - - - - - - -
    1. Global
    2. Header
    3. Home Page
    4. Shared Hosting Page
    5. VPS Page
    6. Dedicated servers
    7. Domains
    8. About Us
    9. FAQ
    10. Datacenter
    11. Affiliates
    12. Blog
    13. Contact
    14. Elements
    15. Footer
    16. Media Queries
    - - - - - - - - -
    */
/* ============
   1 = Global
   ============ */
   body { background: #fff; color: #5a5a5a; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; font-size: 14px; font-style: normal; font-weight: normal; margin: 0; position: relative; webkit-font-smoothing: antialiased;}
   .row { margin-bottom: 0; margin-left: auto; margin-right: auto; margin-top: 0; max-width: 1280px; width: 100%; }
   .row.full-width { margin-bottom: 0; margin-left: auto; margin-right: auto; margin-top: 0; max-width: 100%; width: 100%; }
   .row.no-gutter { margin:0 auto;}
   .row.no-gutter [class*='col-']:not(:first-child), .row.no-gutter [class*='col-']:not(:last-child) { padding-left: 0; padding-right: 0; }
   .center-block { float: none; }
   a { color: #3F51B5; outline: 0; text-decoration: none; }
   a:hover, a:active, a:focus { outline: 0; text-decoration: none; color:#000; }
   code { background: #f5f2f0; border: 0; border-radius: 6px; color: #303038; display: block; font-family: consolas, monaco, 'andale mono', monospace; font-weight: normal; line-height: 1.3; margin: 8px 0; padding: 12px; text-shadow: 0 1px white; white-space: -moz-pre-wrap; white-space: -o-pre-wrap; white-space: pre-wrap; }
   img {  max-width: 100%;  height: auto; -ms-interpolation-mode: bicubic; display: inline-block;  vertical-align: middle;}
   .center-block { float: none; }
   .spacing-75 {padding-top:75px;}
   .spacing-50 {padding-top:50px;}
   .spacing-25 {padding-top:25px;}
   .alignright {float:right; padding-left:35px;}
   .alignleft {float:left; padding-right:35px;}

   /* ƒ¥eadings */
   h1, h2, h3, h4, h5, h6 { color: #5a5a5a; font-family: 'Montserrat', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; font-weight: 700; line-height: 1.3; margin-bottom: 12px; margin-top: 12px; text-rendering: optimizelegibility; letter-spacing: -.05em; }
   h1 { font-size: 44px; }
   h2 { font-size: 34px; }
   h3 { font-size: 27px; }
   h4 { font-size: 23px; }
   h5 { font-size: 17px; }
   h6 { font-size: 14px; }
   /* End of ƒ¥eadings */

   p { font-family: inherit; font-size: 17px; line-height: 1.5; margin: 0 0 17px 0;  font-weight: 300;}
   ul li, ol li { font-family: inherit; font-size: 17px; line-height: 1.5; font-weight: 300;}
   hr { border: solid #999; border-width: 1px 0 0; clear: both; height: 0; margin: 21px 0; }
   hr.small { border: solid #313740; border-width: 1px 0 0; clear: both; height: 0; margin: 0 auto; margin-top:21px; margin-bottom:21px; max-width:100px;}

   input[type="text"], input[type="password"], input[type="date"], input[type="datetime"], input[type="email"], input[type="number"], input[type="search"], input[type="tel"], input[type="time"], input[type="url"], textarea { border-radius: 0; }

   /* Bootstrap 5 columns */
   .col-xs-15, .col-sm-15, .col-md-15, .col-lg-15 {    position: relative;    min-height: 1px;    padding-right: 10px;    padding-left: 10px;}

   /* Border Effect below the Titles ----------------------- */
   .titleborder{ margin:27px 0; width:80%;}
   .titleborder.fullwidth { width:100%;}
   .titleborder_left{  height:1px;  }
   .titleborder_left {background:#D9D8DD;}
   .titleborder_sign {  background: #01ABEF;  width:14%;  height:4px; margin-top: -3px; right:43%;}
   .titleborder.pink .titleborder_sign {  background: #FF4081;}
   .titleborder.centered { margin:0 auto; width:80%; margin-top:37px; margin-bottom:37px;  text-align: center;}
   .titleborder.centered .titleborder_left{  height:1px;  width:37%;  margin-left:13%;  margin-right:auto;}
   .titleborder.centered .titleborder_right{  height:1px;  width:37%;  margin-left: auto;  margin-right: 13%;}
   .titleborder.centered .titleborder_left, .titleborder.centered .titleborder_right {background:#C9C9C9;}
   .titleborder.dark .titleborder_left, .titleborder.dark .titleborder_right {background:#313a4a;}
   .titleborder.centered .titleborder_sign {  background: #FF4081; width:14%;  height:4px;  position: absolute;  display: inline-block;  margin-top: -3px; left:43%; right:43%;}

/* ============
  2 = Header
  ============ */
  /* Top Bar ---------------------- */
  .topmenu { width: 100%; padding:5px 0; border:0; margin:0; background: #009DE0; }
  ul.top { list-style: none; margin:0; padding:5px 0;border:none;color: #fff;}
  ul.top li { float:left; display:inline; margin-right:27px; padding-top:4px; font-size:11px;}
  ul.top li i { margin-right:5px;}
  ul.top li:last-child {  margin-right:0; }
  ul.top li a {color: #fff;}
  ul.top li a:hover, ul.top li a:focus {color: #fff; text-decoration: none;  outline:0;}

  ul.topright { list-style: none; margin:0; padding:5px 0;border:none;color: #fff; float:right;}
  ul.topright li { float:left; display:inline; margin-right:27px; padding-top:4px; font-size:11px; }
  ul.topright li i { margin-right:5px;}
  ul.topright li:last-child {  margin-right:0; }
  ul.topright li a {color: #fff;}
  ul.topright li a:hover, ul.topright li a:focus {color: #fff;  text-decoration: none; outline:0;}

  /* Header ------------------------ */
  .header{ width: 100%; padding:0; border:0; margin:0;background: #01ABEF; box-shadow:0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24);  transition: all 450ms cubic-bezier(0.23, 1, 0.32, 1) 0ms;  -webkit-transition: all 450ms cubic-bezier(0.23, 1, 0.32, 1) 0ms;}
  .logo {padding-top:14px;}

  /* Navigation  ---------------------- */
  nav#desktop-menu {  padding: 0; float:right; text-align: left; }
  .f-nav{ z-index: 999; position: fixed; left: 0; top: 0; width: 100%; }
  .fadeindown { -webkit-animation-duration: .45s;  -webkit-animation-timing-function: ease;  -webkit-animation-fill-mode: both;  -webkit-animation-name: fadeInDown;  -moz-animation-duration: .45s;  -moz-animation-timing-function: ease;  -moz-animation-fill-mode: both;  -moz-animation-name: fadeInDown;  animation-duration: .45s;  animation-timing-function: ease;  animation-fill-mode: both;  animation-name: fadeInDown;}
  /*** ESSENTIAL STYLES ***/
  .sf-menu, .sf-menu * {  margin: 0;  padding: 0;  list-style: none;}
  .sf-menu li {  position: relative;}
  .sf-menu ul {  position: absolute;  display: none;  top: 100%;  left: 0;  z-index: 99;}
  .sf-menu > li {  float: left;}
  .sf-menu li:hover > ul, .sf-menu li.sfHover > ul {  display: block;}
  .sf-menu a {  display: block;  position: relative;}
  .sf-menu ul ul {  top: 0;  left: 100%;}

  /*** SKIN ***/
  .sf-menu {  float: left;  margin: 0;}
  .sf-menu ul {  min-width: 12em; *width: 12em; box-shadow: 0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);}
  /* 1st level */
  .sf-menu li {  white-space: nowrap;   *white-space: normal;}
  .sf-menu li a {color: #fff;  font-weight: 500;  padding:25px;  font-size: 13px;  letter-spacing: 0px;  text-transform: uppercase; transition: all 450ms cubic-bezier(0.23, 1, 0.32, 1) 0ms;  -webkit-transition: all 450ms cubic-bezier(0.23, 1, 0.32, 1) 0ms;}
  .sf-menu li:hover a, .sf-menu li.sfHover a, .sf-menu li.current a  { color: #fff;  background:#01ABEF; }
  .sf-menu li:last-child ul {  left: auto;  right: 0%; }
  /* 2nd level */
  .sf-menu ul li, .sf-menu li.current ul li{background:#fff!important; }
  .sf-menu ul li a {border-bottom: 0; background:#fff!important; font-size: 12px; padding: 16px 20px; color: #01ABEF!important;}
  .sf-menu ul li:hover a, .sf-menu ul li.sfHover a  { background: #01ABEF!important; color: #01ABEF;  -webkit-transition: none;  transition: none;}
  /* 3rd level */
  .sf-menu ul li.sfHover li a {background:#fff!important; }
  .sf-menu ul li li:hover a, .sf-menu ul li li.sfHover a  { background: #01ABEF!important; color: #01ABEF!important;  -webkit-transition: none;  transition: none;}
  /* styling for both css and generated arrows */
  .sf-arrows .sf-with-ul {  padding-right: 2.5em;  *padding-right: 1em; }
  .sf-arrows .sf-with-ul:after {  content: '';  position: absolute;  top: 50%;  right: 1em;  margin-top: -3px;  height: 0;  width: 0;  border: 5px solid transparent;  border-top-color: #fff; }
  .sf-arrows > li > .sf-with-ul:focus:after, .sf-arrows > li:hover > .sf-with-ul:after, .sf-arrows > .sfHover > .sf-with-ul:after {  border-top-color: #fff; }
  .sf-arrows ul .sf-with-ul:after {  margin-top: -5px;  margin-right: -3px;  border-color: transparent;  border-left-color: #01ABEF;  }
  .sf-arrows ul li > .sf-with-ul:focus:after, .sf-arrows ul li:hover > .sf-with-ul:after, .sf-arrows ul .sfHover > .sf-with-ul:after {  border-left-color: #01ABEF;}
  .slicknav_menu {  display:none;}

  /*======modal login=========*/
  #LoginModal .modal-content {border-radius:0; box-shadow: 0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);}
  #LoginModal .modal-header {border:0; background:#01ABEF;}
  #LoginModal .modal-header h4.modal-title {text-align: center; color:#fff; font-size:15px; }
  #LoginModal .modal-header h4.modal-title i {font-size:90px;  padding:15px 10px; display:table; margin:0 auto;}
  #LoginModal .modal-body {padding:15px 50px;}
  #LoginModal .modal-body button[type="submit"] {width:auto; font-size:12px; font-weight:500; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; text-transform: uppercase; margin:12px 0 8px; }

/* ============
  3 = Home Page
  ============ */

  /* Header Background ---------------------- */
  #mainimage { position: relative;    overflow: hidden; background: #282f39 url(images/pricingbox-bg-dark.jpg) no-repeat bottom center;}
  #mainimage .introcaption { opacity:0; }
  #mainimage h1 { font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; text-align: center; color:#000000; padding-top:70px; z-index:2; position: relative; font-weight:100; font-size: 3.28em; text-shadow: -1px 1px 0 #2d2d2f;}
  #mainimage h1 span#js-rotating {padding:25px 25px 0;  color:#000000; display:table; margin:0 auto; text-align:center; }
  .pricingbox.headerimg {padding-bottom:0; margin-top:30px; background:transparent;}
  .pricingbox.headerimg .verticalbottom { margin-top:139px;}
  .pricingbox.headerimg .progressbars {padding: 0 20px 20px; color:#fff;}
  .pricingbox.headerimg .progressbars:first-child {padding-top:20px;}
  .pricingbox.headerimg .progressbars:last-child {border-bottom:1px solid rgba(0,0,0,.1);}
  .pricingbox.headerimg .progressbars p {margin:2px 0 0; font-weight:300; text-align: left; padding:0; font-size:12px; letter-spacing: .09em;}
  .pricingbox.headerimg .progress { margin:8px 0 0;  padding:0;  width:100%;  height:8px;  overflow:hidden;  background:#fff; background: rgba(255,255,255,.4); border-radius:0; border:0;}
  .pricingbox.headerimg .meter { float:left;  min-width:1%;  height:100%; }
  .pricingbox.headerimg .progress.red .meter { background:#cc1a56;}
  .pricingbox.headerimg .progress.purple .meter { background:#7a1b8a;}
  .pricingbox.headerimg .progress.blue .meter { background:#2d3c8f;}

  /* Header Background Image Two ---------------------- */
  #mainimage-two {background: #282f39 url(images/head-bg-2.png);}
  #mainimage-two canvas {position: absolute; top: 0; left: 0;  right: 0; bottom: 0; }
  #mainimage-two [class*='col-'] { text-align:center;}
  .top-column-content {padding:90px 0 0;}
  #mainimage-two h2 {color:#fff; letter-spacing: -.03em; margin-bottom:50px; font-size:23px; font-weight:500;}
  #mainimage-two .subtitle {background:rgba(0,0,0,.15); padding:8px 15px; border-radius:6px; font-size:14px; letter-spacing: 0; display:table; margin:0 auto; font-weight:300; margin-top:18px;}
  #mainimage-two .part-one .pricing-price {background: rgba(255,64,129,.32);}
  #mainimage-two .part-two .pricing-price {background: rgba(124,87,228,.32);}
  #mainimage-two .part-three .pricing-price {background: rgba(1,171,239,.32);}
  .part-one { border-right:1px dotted rgba(255,255,255,.1);}
  .part-two { border-right:1px dotted rgba(255,255,255,.1);}
  .arrow_box {  position: relative;  background: transparent;  border: 2px solid rgba(255,255,255,.25);  border-left:0;  border-right:0;  border-bottom:0;  max-width:65%;  display:block;  margin:0 auto;}
  .arrow_box:after, .arrow_box:before {  bottom: 100%;  left: 50%;  border: solid transparent;  content: " ";  height: 0;  width: 0;  position: absolute;  pointer-events: none;}
  .arrow_box:after {  border-color: rgba(44, 51, 61, 0);  border-bottom-color: rgba(44, 51, 61, 0);  border-width: 15px;  margin-left: -15px;}
  .part-one .arrow_box:before {  border-color: rgba(255, 255, 255, 0);  border-bottom-color:#ff4081;  border-width: 18px;  margin-left: -18px;  margin-bottom:3px;}
  .part-two .arrow_box:before {  border-color: rgba(255, 255, 255, 0);  border-bottom-color:#7C57E4;  border-width: 18px;  margin-left: -18px;  margin-bottom:3px;}
  .part-three .arrow_box:before {  border-color: rgba(255, 255, 255, 0);  border-bottom-color:#01ABEF;  border-width: 18px;  margin-left: -18px;  margin-bottom:3px;}
  #mainimage-two .progressbars {padding: 0 20px 20px; color:#fff;}
  #mainimage-two .progressbars:first-child {padding-top:20px;}
  #mainimage-two .progressbars:last-child {border-bottom:0;}
  #mainimage-two .progressbars p {margin:2px 0 0; font-weight:300; text-align: left; padding:0; font-size:12px; letter-spacing: .09em;}
  #mainimage-two .progress { margin:8px 0 0;  padding:0;  width:100%;  height:5px;  overflow:hidden;  background:#fff; background: rgba(255,255,255,.7); border-radius:6px; border:0;}
  #mainimage-two .meter { float:left;  min-width:1%;  height:100%; }
  #mainimage-two .progress.red .meter { background:#ff4081;}
  #mainimage-two .progress.purple .meter { background:#7C57E4;}
  #mainimage-two .progress.blue .meter { background:#01ABEF;}
  #mainimage-two .mtr-btn {margin-top:15px;}

  /* Header Slider ---------------------- */
  #mainslider { position: relative;    overflow: hidden;}
  .flex-caption {left: 50%; top:50%; position: absolute; text-align: center; z-index: 2; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%);}
  .flex-caption h2 {font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; text-align:center; color: #E1E3E4; font-size: 2.5em; text-shadow: -1px 1px 0 #2d2d2f; font-weight:100; }
  .flex-caption h2 span {padding: 20px 0;color:#fff;}
  .flex-caption h4 {font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif;text-align:center; color: #fff; font-size: 1.5em; font-weight: 300; margin-top: 55px; text-shadow: -1px 1px 0 #2d2d2f;}
  .flex-caption .mtr-btn {margin-top:75px; margin-bottom:25px; font-size: 15px;}
  .flex-caption a.mtr-btn:hover, .flex-caption a.mtr-btn:focus {color:#fff;}

  /* Header Video Background ---------------------- */
  #home-intro .home-intro-container { height:90vh; position: relative;    overflow: hidden;}
  #home-intro .home-intro-container:after { background: rgba(34,34,34,.85); bottom: 0px; content: ""; left: 0; position: absolute; right: 0; top: 0; z-index: 1; }
  #home-intro .home-intro-container .introcaption { opacity:0; left: 50%; top:50%; position: absolute; text-align: center; z-index: 2; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%); }
  #home-intro .home-intro-container .introcaption h2 { font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; color: #E1E3E4; font-size: 4.19em; text-shadow: -1px 1px 0 #2d2d2f; font-weight:100; }
  #home-intro .home-intro-container .introcaption h2 span#js-rotating {padding:14px 0 0;  color:#01ABEF; display:block; }
  #home-intro .home-intro-container .introcaption h4 { font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif;  color: #fff; font-size: 2.1em; font-weight: 300; margin-top: 55px; text-shadow: -1px 1px 0 #2d2d2f; }
  #home-intro video {  width:100%; min-height:100%;   background-size: cover;    position: absolute;    top: 0;    left: 0; object-fit: cover; }
  .morphext > .animated { display: inline-block;}

  /* Features Multicolor ---------------------- */
  .introcolumns { text-align: center;background:#F0F0F0; padding:67px 0 55px;}
  .introcolumns [class*='col-'] {padding:0 45px;}
  .introcolumns h4 {color:#424242; font-weight:300; margin:20px 0;}
  .introcolumns p {font-size: 17px;}
  .introcolumns .circle {width:100px; height:100px; border-radius: 50%; background:#03A9F4; position:relative; margin:0 auto; box-shadow: 0 1px 1.5px 0 rgba(0, 0, 0, 0.12), 0 1px 1px 0 rgba(0, 0, 0, 0.24);}
  .introcolumns .circle.red {background:#FF4081;}
  .introcolumns .circle.purple {background:#8F4099;}
  .introcolumns .circle.orange {background: #FE6A2B;}
  .introcolumns .circle i {position:absolute; font-size:48px; color:#fff; top:50%; left:50%; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%);}

  /* Features ---------------------- */
  .features {background:#99ddf8; padding:55px 0;  overflow:hidden;}
  .features h3 {color:#424242; letter-spacing: -.03em; margin-bottom:70px; padding: 0 20px;}
  .features .circle {width:100px; height:100px; border-radius: 50%; background:#03A9F4; position:relative; margin:0 auto; box-shadow: 0 1px 1.5px 0 rgba(0, 0, 0, 0.12), 0 1px 1px 0 rgba(0, 0, 0, 0.24);}
  .features .circle i {position:absolute; font-size:48px; color:#fff; top:50%; left:50%; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%);}
  .features h4 {color:#424242; font-weight:300; margin:20px 0;}
  .features p {padding:0 40px;}

  /* Call To Action ------------------------ */
  .calltoaction {padding:55px 0 360px; background:#99ddf8 url(images/calltoaction.jpg) no-repeat bottom center; background-size:cover; overflow:hidden;}
  .calltoaction h2 {font-weight:300; font-size:31px; display:table; border-bottom:1px solid #e4e4e4; padding:15px; margin:0 auto; margin-bottom:25px; letter-spacing: -.05em;}
  .calltoaction h2 span {color:#FF4081; display: block; margin-top:15px; margin-bottom:15px; }
  .calltoaction .mtr-btn {margin-top:15px;}

  /* Pricing Boxes ------------------------ */
  .pricingbox {padding:55px 0; margin:0; background: #282f39 url(images/pricingbox-bg-dark.jpg) no-repeat bottom center; overflow:hidden; }
  .pricingbox.no-image-bg {background: #282f39 url(images/popular_plans_bg.jpg);}
  .pricingbox h3 {color:#fff; letter-spacing: -.03em; margin-bottom:30px; text-align: center; font-size:29px;}
  .pricingbox h3.poptitle {color:#fff; letter-spacing: -.03em; margin-bottom:20px; text-align: center; font-size:29px; font-weight:900; position: relative; padding-bottom:25px;}
  .pricingbox h3.poptitle::after {background-color: #FF377D; bottom: 0; content: ""; height: 2px; left: 50%; margin-left: -30px; position: absolute; width: 60px;}
  .pricingbox p {color:#fff; margin-bottom:70px; text-align: center; padding:0 95px; font-size:18px;}
  .pricingbox .row {margin-bottom:0; }

  .pricing-plan {   position: relative;   top: 0;   opacity: 1;   float: left;   padding: 30px 0px;   width: 100%;   border-radius: 0;   transform: scale(1);   -webkit-transform: scale(1);   -ms-transform: scale(1);   z-index: 5; background: #FF2770;}
  .pricing-plan:before {   content: "";   width: 100%;   height: 30px;   border-radius: 0;   position: absolute;   top: -10px;   left: 0;   transform: scale(.95);   -webkit-transform: scale(.95);   -ms-transform: scale(.95);   z-index: -1; background: rgba(255,39,112,.5);}
  .pricing-title {   width: 100%;   float: left;   line-height: 36px;   font-size: 23px;   font-weight: 400;   letter-spacing: -.03em;  color: #fff;   position: relative; padding-left:30px; margin-bottom:27px; font-family: 'Montserrat', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif;  }
  .pricing-title:before {   content: "";   width: 5px;   height: 100%;   position: absolute;   top: 0;   left: 0;   background: #fff;}
  .pricing-price { clear:both;  width: 100%;  font-size: 47px;   font-weight: 100;   letter-spacing: -.03em; color: #fff; padding:30px 30px 25px;  background: rgba(0,0,0,.15); text-align: center; }
  .pricing-price span {font-size: 17px;   font-weight: 300;  letter-spacing: 0; color: #fff;  }
  .pricing-price .starting {color:#ccc; margin-bottom:0; text-align: center; padding:0; font-size:11px; letter-spacing: .12em;}
  .pricing-features { padding:15px 0;}
  .pricing-features ul { padding:0; margin:0; list-style:none;}
  .pricing-features ul li { color:#fff; padding:10px 20px; border-bottom:1px solid rgba(0,0,0,.2); text-align: center;}

  .pricing-plan.red {  background: #FF2770;}
  .pricing-plan.red:before {  background: rgba(255,39,112,.5);}
  .pricing-plan.blue {  background: #3F51B5;}
  .pricing-plan.blue:before {  background: rgba(63,81,181,.5);}
  .pricing-plan.purple {  background: #9C27B0;}
  .pricing-plan.purple:before {  background: rgba(156,39,176,.5);}

  .pricing-plan button {display:table; margin:0 auto;}
  .pricing-plan button.mdl-button.mdl-button--raised {background:#fff;}
  .pricing-plan button i {font-size:14px;}

  /* Domain Names Search Box ------------------------ */
  .domainsearch{ width: 100%; background: #212832; padding:55px 0 40px;border-top:1px solid #252d38; position:relative; }
  .domainsearch h3 {color:#fff; letter-spacing: -.03em; margin-bottom:30px; text-align: center;}
  .domainsearch button{ position:absolute; top:100%; left:50%; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%); margin-top:40px; z-index:9; font-size:16px; line-height:29px; font-weight:300;}
  .domainform {padding:55px 0;background: #303843; display:none; }
  .domainform .material .material-input :focus ~ label, .domainform .material .material-input .filled ~ label {font-weight:300;}
  .domainform .material .material-input label {margin-top:7px;}
  .domainform .material .material-input input { font-size: 16px;   height:41px; width: 100%;    border:0;    border-bottom: 1px solid lightgray;    outline: none;    background: 0;    float:left;}
  .domainform .material .material-select { font-size: 14px;}
  .domainform .material .material-select ul {padding:0; margin:0; list-style:none;}
  .domainform button {width: 100%; -webkit-border-radius:0;  -moz-border-radius:0;  margin-top:22px; font-weight: 700;  outline: none;  -webkit-box-shadow: none;  -moz-box-shadow: none;  box-shadow: none; border:0; background:#FF4081; color:#fff;}
  .domainform button i {font-size:16px;}

  /* Home Page Features */
  .various {padding:60px 0; background: #99ddf8;  overflow:hidden;}
  .various h2 {font-weight:700; font-size:29px; display:inline-block; padding:15px 0 0; margin-bottom:0; }
  .various h5 {font-weight:700; font-size:20px;  padding:15px 0 6px; color:#FF4081;}
  .various p {font-size:17px; }
  .various .why {padding-right:25px; }
  .various a.mtr-btn {margin-top:15px; }
  .various i {font-size:49px; color:#FF4081; margin-top:29px; float:right;}

  /* Home Page Tabs */
  .features-tabs {padding:90px 0 75px; background:#E1DFE0; overflow:hidden;}
  .features-tabs .tab-content {margin-top:55px; padding:40px 40px 55px; font-size:16px; background:#fff; border: 1px solid #ccc; border-radius:5px; box-shadow:inset 0 -4px 0 0 #f6f6f6, inset 0 -5px 0 0 #ddd, inset 0 -10px 0 0 #f6f6f6, inset 0 -11px 0 0 #ddd,0 2px 8px -2px rgba(0, 0, 0, 0.1);}
  .features-tabs .tab-content h4 {font-weight:700; font-size:29px; color:#FF4081; display: block; margin:0 0 30px; padding-bottom:30px;  letter-spacing: -0.05em; text-align:center; position:relative;}
  .features-tabs .tab-content h4::after {background-color: #999; bottom: 0; content: ""; height: 2px; left: 50%; margin-left: -30px; position: absolute; width: 60px;}
  .features-tabs .tab-content p.subtitle {padding:0 150px; text-align:center;}
  .features-tabs .tabs-top-horizontal > .nav-tabs {  display:table;  margin:0 auto; }
  .features-tabs .tab-content > .tab-pane,.pill-content > .pill-pane {  display: none;}
  .features-tabs .tab-content > .active,.pill-content > .active {  display: block;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li {  float: left;  text-align: center; min-width:175px; margin-bottom: 0; border-right:1px solid #E1DFE0; background: #fff;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li i {display:block; text-align:center; margin-bottom:8px; font-size:30px;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li i.green {color:#B5BD8E;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li i.red {color:#DA3867;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li i.lightblue {color:#8ACDDD;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li i.orange {color:#E38F75;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li i.darkgray {color:#6A6665;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li i.royalblue {color:#405499;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li > a {  margin-right: 0;color:#424242;padding:25px 10px;-webkit-border-radius:0;-moz-border-radius:0; border-radius:0; border:0; text-transform: uppercase;font-size:14px;font-weight:400;}
  .features-tabs .tabs-top-horizontal > .nav-tabs > li > a:hover,.features-tabs .tabs-top-horizontal > .nav-tabs > li > a:focus {  border:0; -webkit-border-radius:0; -moz-border-radius:0; border-radius:0;background:#fff;}
  .features-tabs .tabs-top-horizontal > .nav-tabs .active > a,.features-tabs .tabs-top-horizontal > .nav-tabs .active > a:hover,.features-tabs .tabs-top-horizontal > .nav-tabs .active > a:focus {  border:0; -webkit-border-radius:0; -moz-border-radius:0; border-radius:0; background:#fff; position: relative;}
  .features-tabs .tabs-top-horizontal > .nav-tabs .active > a:after { top: 100%; left: 50%; border: solid transparent; content: " "; height: 0; width: 0; position: absolute; pointer-events: none; border-color: rgba(238, 238, 238, 0); border-top-color: #fff;  border-width: 15px;  margin-left: -15px;}
  .features-tabs .tab-content ul {list-style:none; margin:0; padding:0;}
  .features-tabs .tab-content ul li { padding:5px 20px 5px 0; border-bottom:1px solid #ccc;}
  .features-tabs .tab-content ul li:last-child {border-bottom:0;}
  .features-tabs .tab-content ul li i {margin-right:10px; color:#f67081;}

  /* fully managed tab */
  .fully-managed {text-align:center; padding-top:40px;}
  .fully-managed .block-grid-item {text-align: center; padding:50px 35px; border:1px solid #e9e6e8; border-left:0; border-top:0; }
  .fully-managed .block-grid-item:nth-child(3n+3) { border-right:0;}
  .fully-managed .block-grid-item:nth-last-child(-n+3) {border-bottom:0;}
  .fully-managed .block-grid-item h5 {font-weight:400; font-size:19px;padding-top:18px; }
  /* security tab */
  .security {padding-top:25px;}
  .security .block-grid-item {text-align: left; padding:10px 35px;}
  .security .security-tab-icon {float:left; width:17%; position:relative;}
  .security .security-tab-icon i {margin-top:25px; font-size:42px; color:#AEAEAE; text-align:center;}
  .security .security-tab-feature {float:right;  width:78%;}
  .security .block-grid-item h5 {font-weight:400; font-size:18px;padding-top:12px; color:#6A6665; }
  /* backups tab */
  .backups-restore .backupcolumn { border:1px solid #ccc; border-left:0; border-bottom:4px solid #FF4081; padding:25px!important; min-height:370px; background:#f6f4f5;}
  .backups-restore .backupcolumn:first-child { border-left:1px solid #ccc; }
  .backups-restore h5 {font-weight:300; font-size:20px;}
  .backups-restore h5.blue {color:#40549B;}
  .backups-restore h5.purple {color:#9C27B0;}
  .backups-restore h5.orange {color: #FE6A2B;}
  .backups-restore h5.lightblue {color:#01ABEF;}


  /* Testimonials ------------------------ */
  .testimonials {background: url(images/s8.png); padding:55px 0; overflow:hidden; }
  .testimonials h3 {color:#fff; letter-spacing: -.03em; margin-bottom:50px; text-align: center; font-size:29px; font-weight:900;}
  .testimonials .hr-awesome { position: relative; margin:0 auto; max-width:50%; margin-bottom:50px; border: solid rgba(255,255,255,.075); border-width: 1px 0 0;}
  .testimonials .hr-awesome::after { color: #fff; font-family:'FontAwesome'; content: "\f08a";  font-size: 19px; position: absolute; right: calc(50% - 15px);  top: calc(50% - 22px);  width: 40px; height:40px; border-radius:50%; background:#0099d7; padding:7px 0 0 11px;  box-shadow: 0 1px 1.5px 0 rgba(0, 0, 0, 0.12), 0 1px 1px 0 rgba(0, 0, 0, 0.24);}
  .testimonial-content { background:#fff; box-shadow: 0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12); position:relative; }
  #testimonials-carousel .item {margin:12px;   }
  #testimonials-carousel .item p { border-radius:0;color: #0099d7; font-size: 16px;  line-height: 1.5;  padding: 24px 16px; text-align: left; margin-bottom:0; }
  .testimonial-content h5 {font-size:14px; color:  #0099d7; text-transform: uppercase; font-weight:500; padding:16px; margin:0; border-top:1px solid rgba(0,0,0,.1);}
  .testimonial-content h5 a {color:#0099d7; }
  .testimonials  .owl-theme .owl-controls {margin-top:30px;}
  .testimonials  .owl-theme .owl-controls .owl-page span {width: 40px; height: 7px; background: #fff; cursor: pointer; border-radius: 10px; border: 0; margin: 5px 7px;    opacity: 1; box-shadow: 0 1px 1.5px 0 rgba(0,0,0,.24),0 1px 1px 0 rgba(0,0,0,.48);}
  .testimonials .owl-theme .owl-controls .owl-page.active span, .owl-theme .owl-controls.clickable .owl-page:hover span { opacity: 1; background: ##0099d7;}

  /* New Plans */
  .newplans {padding:55px 0 75px; background: #99ddf8;  overflow:hidden;}
  .newplans h3 {letter-spacing: -.03em; margin-bottom:45px; text-align: center; font-size:29px; font-weight:700;}
  .newplans_box {  position: relative;  background: #99ddf8;  border: 0;  border-bottom: 4px solid #E5E5E5; max-width:540px; margin:0 auto; margin-top:25px; margin-bottom:55px;}
  .newplans_box:after, .newplans_box:before {  top: 100%;  left: 50%;  border: solid transparent;  content: " ";  height: 0;  width: 0;  position: absolute;  pointer-events: none;}
  .newplans_box:after { border-color: rgba(255, 255, 255, 0);  border-top-color: #ffffff;  border-width: 15px;  margin-left: -15px;}
  .newplans_box:before {  border-color: rgba(229, 229, 229, 0);  border-top-color: #E5E5E5;  border-width: 21px;  margin-left: -21px;}
  .newplanscolumn {   position: relative;   top: 0;   opacity: 1;   float: left;   padding: 25px;   width: 100%;   border-radius: 0;   transform: scale(1);   -webkit-transform: scale(1);   -ms-transform: scale(1);   z-index: 5; background: #E5E5E5; min-height:370px;}
  .newplanscolumn:before {   content: "";   width: 100%;   height: 30px;   border-radius: 0;   position: absolute;   top: -10px;   left: 0;   transform: scale(.95);   -webkit-transform: scale(.95);   -ms-transform: scale(.95);   z-index: -1; background: rgba(229,229,229,.5);}
  .newplanscolumn h5 {color:#5A5A5A; font-size:19px; font-weight:900; border-bottom:1px solid #dfdbdb; padding-bottom:12px; letter-spacing: -.03em; margin-bottom:25px; text-transform: uppercase;}
  .newplanscolumn.white {background:#fff;}
  .newplanscolumn.white:before {background:rgba(255,255,255,.5);}
  .newplans p {font-size:17px;}
  .newplans ul {list-style:none; margin:0; padding:0;}
  .newplans ul li { padding:5px 0;}
  .newplans ul li:last-child {border-bottom:0;}
  .newplans ul li i {margin-right:10px; color:#7C57E4;}
  .progressbars p {margin-bottom:3px; font-weight:300;font-size:16px;}
  .thebar { position:relative; margin-bottom:25px;}
  p.percent { position:absolute;  top:10px;  right:0; margin:0; font-size:15px; padding:0; }
  .progress { margin:8px 0 0;  padding:0;  width:100%;  height:5px;  overflow:hidden;  background:#fff;  border-radius:6px; border:0; box-shadow: none;}
  .progress .meter {   float:left;  min-width:1%;  height:100%;  background:#E55E4B;}
  .progress.alt-1 .meter { background:#009DD7;}
  .progress.alt-2 .meter { background:#7C57E4;}
  .progress.alt-3 .meter { background:#0DB900;}


  /* Logos Carousel */
  .partners {background: #f0f0f0; padding:35px 0; border-top:1px solid #e4e4e4;}
  #company-partners .item {margin: 3px; text-align: center;}

  /* Subheaders */
  #subheader {padding:150px 25px; position: relative; background-size:cover;}
  .subheader-text {position: absolute; text-align: center; z-index: 2; left:1%; right:1%; top: 50%;  -webkit-transform: translateY(-50%);  -ms-transform: translateY(-50%);  transform: translateY(-50%);}
  #subheader h1 { text-align: center; color:#fff; font-weight:700; font-size: 31px; text-shadow: -1px 1px 0 #2d2d2f; letter-spacing:-0.05em; text-transform: uppercase;}
  #subheader h2 { text-align: center; color:#fff; font-weight:400; font-size: 17px; margin-top:25px;}

/* ========================
  4 = Shared Hosting Page
  ======================== */
  #subheader.shared {background:url(images/shared-bg.png); padding:100px 25px;}
  #subheader.shared h1 {color:#424242; text-shadow:none; }
  #subheader.shared h2 {color:#424242;}

  /* Choose Price Period */
  span.chooseprice { background: #009DE0; border-radius: 0; color: #fff; display: table; font-size: 16px; margin: 0 auto; padding: 5px 20px 8px; position: relative; }
  span.chooseprice:after { border: solid transparent; border-color: rgba(222, 98, 98, 0); border-top-color: #009DE0; border-width: 10px; content: " "; height: 0; left: 50%; margin-left: -10px; pointer-events: none; position: absolute; top: 100%; width: 0; }
  .price-per-period { display: table; margin: 0 auto; margin-top: 30px; text-align: center;}
  .price-per-period .btn { font-size: 15px; padding: 10px 15px 8px; border:0; border-radius: 0; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.24), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.24);}
  .btn-shared-checked { background: #673AB7;  border:0; box-shadow: none; color:#fff; border-radius: 0; }
  .btn-shared-checked:hover, .btn-shared-checked:focus, .btn-shared-checked.focus, .btn-shared-checked:active, .btn-shared-checked.active { border:none; box-shadow: none; color:#fff; border-radius: 0; outline: 0; }
  /* End of Choose Price Period */
  .yearprice, .twoyearprice { display: none; }

  .pricingbox.shared {padding:55px 0 90px;}

  /* Responsive Table - Shared Hosting */
  .shared-table {background: #fff; padding:45px 0 70px; z-index:0; position: relative;}
  .shared-table button.mtr-btn { position:absolute; top:0%; left:50%; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%); z-index:99999999; font-size:16px; line-height:29px; font-weight:300;}
  .shared-table p {font-weight:300;}
  .products-table { min-width:100%; border:1px solid #eae8e8; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif!important; background:#fcfcfc; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12); display:none; margin-bottom:45px;}
  .products-table thead th {background:#3E65BF; color:#fff!important; font-weight:400;  font-size:16px; border:0!important; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif!important;height:45px; }
  .products-table th {font-weight: normal;    -webkit-font-smoothing: antialiased;   padding:16px 12px; color: #424242;   font-size: 14px; background: #fff; }
  .products-table td {color: #424242;    padding:16px 12px; font-size: 16px; border-bottom:1px solid #eae8e8;}
  .products-table td, .products-table thead th {text-align: center;}
  .products-table td:first-child, .products-table thead th:first-child {text-align: left;}
  .products-table tr.even, .products-table tr.alt, .products-table tr:nth-of-type(even) {  background: #fff!important; }
  .products-table td i.fa-times {color:#ff4081;}
  .products-table td i.fa-check {color:#258D5C;}
  .products-table tr.price-comparison td {font-weight:300; font-size:19px;}
  .products-table tr.price-comparison td:first-child {font-weight:400; font-size:16px;}
  /* End of Responsive Table */

  .shared-table .difference h3 {letter-spacing: -.03em; margin-bottom:45px; text-align: center; font-size:29px;}
  .shared-table .block-grid-item {text-align: center; padding:50px 20px; border:1px solid #eae8e8; border-left:0; border-top:0; }
  .shared-table .block-grid-item:nth-child(3n+3) { border-right:0;}
  .shared-table .block-grid-item:nth-last-child(-n+3) {border-bottom:0;}
  .shared-table .block-grid-item h5 {font-weight:700; font-size:19px;padding-top:12px; }

  /* Video Background  */
  #shared-video .shared-video-container {  min-height: 600px;  padding-bottom: 50px;    position: relative; overflow:hidden;}
  #shared-video .shared-video-container:after { background: rgba(34,34,34,.9); bottom: 0px; content: ""; left: 0; position: absolute; right: 0; top: 0; z-index: 1; }
  #shared-video .shared-video-container .videocaption { left: 50%; top:50%; position: absolute; text-align: center; z-index: 2; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%); }
  #shared-video .shared-video-container .videocaption .videocaption-content {display:inline-block; padding:25px; background:#FF2770; background:rgba(255,39,112,.5); text-align: left; max-width:320px;  }
  #shared-video .shared-video-container .videocaption .videocaption-content h2 { color: #fff; font-size: 3.2em; font-weight:100; }
  #shared-video .shared-video-container .videocaption .videocaption-content hr { opacity:0.1; }
  #shared-video .shared-video-container .videocaption .videocaption-content p { color: #fff; font-size: 15px; font-weight: 300; margin-top: 25px; }
  #shared-video video { width:100%;    background-size: cover;    position: absolute;    top: 0;    left: 0;}

  /* Apps  */
  .apps {padding:55px 0 80px; overflow:hidden;}
  .apps-grid {text-align:center; padding-top:40px;}
  .apps-grid .block-grid-item {text-align: left; padding:15px 25px; border:2px solid #fff; border-left:0; border-top:0; background:#F0F0F0; }
  .apps-grid .block-grid-item:nth-child(3n+3) { border-right:0;}
  .apps-grid .block-grid-item:nth-last-child(-n+3) {border-bottom:0;}
  .apps-grid .block-grid-item h5 {font-weight:700; font-size:24px;padding-top:5px; }
  .apps-grid .block-grid-item .odometer {color:#d1cfcf; font-size:82px; font-weight:900; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; margin-top:10px; letter-spacing: -.05em; line-height:1; }
  .apps-grid .block-grid-item .graphicline span {display:block; width:100%; margin: 0px 0 16px; }
  .apps-grid .block-grid-item .graphicline {margin-bottom: 15px; }
  .apps-grid .block-grid-item p {margin-top:0; padding-top:0; }

/* ========================
  5 = VPS Page
  ======================== */

  /* Order Slider - VPS Page */
  .pricingbox.vps {padding-bottom:0;}
  .pricingbox.vps-comparison {padding:55px 0 90px; background: url(images/popular_plans_bg.jpg); background-size:cover;}
  .pricingbox.vps h1 {font-size:29px; display:table; border-bottom:0; padding:0 15px; margin:0 auto;color:#fff; font-weight:700; margin-bottom:0;}
  .pricingbox.vps .centralized {   position: relative;   top: 0;   opacity: 1;   float: left;   padding:15px 0 0;   width: 100%;   border-radius: 0;   transform: scale(1);   -webkit-transform: scale(1);   -ms-transform: scale(1);   z-index: 5; text-align:center; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12); background: #ff4081; margin-top:30px;}
  .pricingbox.vps .centralized:before {   content: "";   width: 100%;   height: 30px;   border-radius: 0;   position: absolute;   top: -10px;   left: 0;   transform: scale(.95);   -webkit-transform: scale(.95);   -ms-transform: scale(.95);   z-index: -1; background: rgba(255,64,129,.5);}
  .pricingbox.vps .centralized span.how_much {background:rgba(0,0,0,.17); width:100%; display: block; padding:15px; position:relative; font-weight:100; font-size:22px;}
  .pricingbox.vps .centralized span.how_much:after {  bottom: 100%;    left: 50%;    border: solid transparent;    content: " ";    height: 0;    width: 0;    position: absolute;    pointer-events: none;    border-color: rgba(196, 71, 71, 0);    border-bottom-color: rgba(0,0,0,.17);    border-width: 10px;    margin-left: -10px;}

  .pricingbox.vps h6 {font-size:15px;letter-spacing:.04em; color:#fff;font-weight:500; padding-bottom:12px;}
  .pricingbox.vps .how_much {font-size:19px;color:#fff; font-weight:900; text-transform: uppercase; letter-spacing: -.03em; }
  .ui-slider { position: relative; text-align: left; }
  .ui-slider .ui-slider-handle { cursor: default; height: 1.2em; position: absolute; width: 1.2em; z-index: 2; }
  .ui-slider .ui-slider-range { background-position:0 0; border: 0; display: block; font-size: .7em; position: absolute; z-index: 1; }
  .ui-slider-horizontal { height: .8em; }
  .ui-slider-horizontal .ui-slider-handle { margin-left: -.6em; top: -.3em; }
  .ui-slider-horizontal .ui-slider-range { height: 100%; top: 0; }
  .ui-slider-horizontal .ui-slider-range-min { left: 0; }
  .ui-slider-horizontal .ui-slider-range-max { right: 0; }
  .ui-slider-vertical { height: 100px; width: .8em; }
  .ui-slider-vertical .ui-slider-handle { left: -.3em; margin-bottom: -.6em; margin-left: 0; }
  .ui-slider-vertical .ui-slider-range { left: 0; width: 100%; }
  .ui-slider-vertical .ui-slider-range-min { bottom: 0; }
  .ui-slider-vertical .ui-slider-range-max { top: 0; }
  .vps-prices-drag { float: left; margin: 0; padding: 55px 30px; width: 100%;  background: rgba(0,0,0,.11); border-radius: 0;}
  .vps-prices-container {float: left; width: 100%; margin-top:30px;}
  .vps-prices-panel { float: left; width: 100%;  }
  .vps-prices-container #vps-slider { background: #bbbbbb; border-radius: 0; float: left; height:6px; margin: 0 0 15px; width: 100%;  padding:0; box-shadow: 0 13px 16px rgba(0,0,0,0.16), 0 13px 16px rgba(0,0,0,0.23); cursor:pointer;}

  .vps-prices-container #sliderlines { background: url(images/lines1.png) center top; display: table; height: 10px; margin: 0 auto; width: 100%; opacity:.2; }
  .vps-prices-container #vps-slider .ui-slider-range { background: #FF4081; border-radius: 0; }
  .vps-prices-container #vps-slider .ui-slider-handle { background: url(images/slider_range.png) no-repeat left top; border: 0; border-radius: 0; height: 25px; margin-left: -15px; margin-top:-6px; outline: none; width: 25px; }

  #vps_name_option h3 span {font-size:20px; display:table; border-bottom:0; padding:11px 29px; margin:0 auto; margin-top:0; margin-bottom:-30px; letter-spacing:.04em; color:#fff; background:#FF4081; font-weight:300; position: relative; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
  #vps_name_option h3 span:after {  top: 100%;  left: 50%;  border: solid transparent;  content: " ";  height: 0;  width: 0;  position: absolute;  pointer-events: none;  border-color: rgba(255, 64, 129, 0);  border-top-color: #FF4081;  border-width: 10px;  margin-left: -10px;}
  .total_amount h3 {text-align: center;  margin-top:40px; }
  .total_amount h3 span {font-size:45px; color:#fff; font-weight:400; letter-spacing: -0.09em; }
  .total_amount h3 span#period {font-size:22px; }
  /* End Order Slider - VPS Page */

  /* VPS Page Vertical Tabs */
  .vps-features-tabs {padding:55px 0 80px; background:#E9E9E9; overflow:hidden;}
  .vps-features-tabs h2 {font-size:29px; text-align:center; padding:0; margin-bottom:35px; letter-spacing: -0.05em; }
  .vps-features-tabs .tab-content {padding:50px 75px; float:right; width:85%; background:#fff; -webkit-border-radius: 6px;-webkit-border-top-left-radius: 0;-moz-border-radius: 6px;-moz-border-radius-topleft: 0;border-radius: 6px;border-top-left-radius: 0;}
  .vps-features-tabs .tab-content h4 {font-weight:700; font-size:24px; color:#FF4081; display: block; margin:0 0 20px; letter-spacing: -0.05em;}
  .vps-features-tabs .tab-content hr.small {margin:21px 0; border-color:#d8d6d6;}
  .vps-features-tabs .tab-content p.subtitle {font-size:19px; font-weight:400;}
  .vps-features-tabs .tab-content p {font-size:17px;}
  .vps-features-tabs .tabs-left-vertical {margin-top:55px;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs { float:left; width:15%; border:0; box-shadow:none;}
  .vps-features-tabs .tab-content > .tab-pane,.pill-content > .pill-pane {  display: none;}
  .vps-features-tabs .tab-content > .active,.pill-content > .active {  display: block;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li { text-align: left;  display:block; width:100%;  margin-bottom: 1px; }
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li i {margin-right:8px;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li i.green {color:#B5BD8E;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li i.red {color:#DA3867;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li i.lightblue {color:#8ACDDD;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li i.orange {color:#E38F75;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li i.darkgray {color:#6A6665;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li i.royalblue {color:#405499;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li > a {  margin-right: 0;color:#424242;padding:20px 10px;-webkit-border-radius:0;-moz-border-radius:0; border-radius:0; border:0; text-transform: uppercase;font-size:16px;font-weight:400;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs > li > a:hover,.vps-features-tabs .tabs-left-vertical > .nav-tabs > li > a:focus {  border:0; -webkit-border-radius:0; -moz-border-radius:0; border-radius:0;background:#fff; -webkit-border-top-left-radius: 6px;-webkit-border-bottom-left-radius: 6px;-moz-border-radius-topleft: 6px;-moz-border-radius-bottomleft: 6px;border-top-left-radius: 6px;border-bottom-left-radius: 6px;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs .active > a,.vps-features-tabs .tabs-left-vertical > .nav-tabs .active > a:hover,.vps-features-tabs .tabs-left-vertical > .nav-tabs .active > a:focus {  border:0; -webkit-border-radius:0; -moz-border-radius:0; border-radius:0; background:#fff; position: relative; -webkit-border-top-left-radius: 6px;-webkit-border-bottom-left-radius: 6px;-moz-border-radius-topleft: 6px;-moz-border-radius-bottomleft: 6px;border-top-left-radius: 6px;border-bottom-left-radius: 6px;}
  .vps-features-tabs .tabs-left-vertical > .nav-tabs .active > a:after { left: 100%;  top: 50%;  border: solid transparent;  content: " ";  height: 0;  width: 0;  position: absolute;  pointer-events: none;  border-color: rgba(255, 255, 255, 0);  border-left-color: #ffffff;  border-width: 15px;  margin-top: -15px; }

  .tabcircle {width:170px; height:170px; border-radius: 50%; background:#fff; border:8px solid #e1dfe0; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12); float:right; margin:0 0 30px 30px; position:relative; overflow:hidden;}
  .tabcircle i {left: 50%; top:50%; position: absolute; text-align: center; z-index: 2; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%); font-size:87px; text-shadow: 1px 1px rgb(230, 230, 230), 2px 2px rgb(230, 230, 230), 3px 3px rgb(230, 230, 230), 4px 4px rgb(230, 230, 230), 5px 5px rgb(230, 230, 230), 6px 6px rgb(230, 230, 230), 7px 7px rgb(230, 230, 230), 8px 8px rgb(230, 230, 230), 9px 9px rgb(230, 230, 230), 10px 10px rgb(230, 230, 230), 11px 11px rgb(230, 230, 230), 12px 12px rgb(230, 230, 230), 13px 13px rgb(230, 230, 230), 14px 14px rgb(230, 230, 230), 15px 15px rgb(230, 230, 230), 16px 16px rgb(231, 231, 231), 17px 17px rgb(231, 231, 231), 18px 18px rgb(232, 232, 232), 19px 19px rgb(232, 232, 232), 20px 20px rgb(233, 233, 233), 21px 21px rgb(234, 234, 234), 22px 22px rgb(234, 234, 234), 23px 23px rgb(235, 235, 235), 24px 24px rgb(235, 235, 235), 25px 25px rgb(236, 236, 236), 26px 26px rgb(236, 236, 236), 27px 27px rgb(237, 237, 237), 28px 28px rgb(238, 238, 238), 29px 29px rgb(238, 238, 238), 30px 30px rgb(239, 239, 239), 31px 31px rgb(239, 239, 239), 32px 32px rgb(240, 240, 240), 33px 33px rgb(241, 241, 241), 34px 34px rgb(241, 241, 241), 35px 35px rgb(242, 242, 242), 36px 36px rgb(242, 242, 242), 37px 37px rgb(243, 243, 243), 38px 38px rgb(243, 243, 243), 39px 39px rgb(244, 244, 244), 40px 40px rgb(245, 245, 245), 41px 41px rgb(245, 245, 245), 42px 42px rgb(246, 246, 246), 43px 43px rgb(246, 246, 246), 44px 44px rgb(247, 247, 247), 45px 45px rgb(248, 248, 248), 46px 46px rgb(248, 248, 248), 47px 47px rgb(249, 249, 249), 48px 48px rgb(249, 249, 249), 49px 49px rgb(250, 250, 250), 50px 50px rgb(250, 250, 250), 51px 51px rgb(251, 251, 251), 52px 52px rgb(252, 252, 252), 53px 53px rgb(252, 252, 252), 54px 54px rgb(253, 253, 253), 55px 55px rgb(253, 253, 253), 56px 56px rgb(254, 254, 254), 57px 57px rgb(255, 255, 255); }
  .tabcircle i.royalblue {color:#405499; }
  .tabcircle i.green {color:#B5BD8E; }
  .tabcircle i.red {color:#DA3867; }
  .tabcircle i.lightblue {color:#8ACDDD; }
  .tabcircle i.orange {color:#E38F75; }

  /* VPS Text */
  .vps-text {padding:55px 0; overflow:hidden;}
  .vps-text h2 {font-weight:700; font-size:26px; padding:0; margin-bottom:0; letter-spacing: -0.07em; }
  .vps-text p {font-size:16px; padding-right: 35px;}


  /* VPS Page Accordion */
  .vps-accordion {padding:55px 0; overflow:hidden; background:#E9E9E9;}
  .vps-accordion h3 {font-weight:700; font-size:26px; padding:0; margin-bottom:30px; letter-spacing: -0.07em; }
  .vps-accordion p.maintext {font-size:16px; padding-right: 35px;}
  .vps-accordion .panel {box-shadow: none !important; background:transparent;}
  .vps-accordion .panel, .vps-accordion .panel-group .panel-heading+.panel-collapse>.panel-body{ border: none; box-shadow: 0;}
  .vps-accordion .panel-body {border-top: 0 !important;}
  .vps-accordion .panel-heading {border:0; border-bottom:1px solid #d8d6d6; background:transparent;  border-radius:0; padding:12px 0;  }
  .vps-accordion .panel-heading h4.panel-title a {font-size:16px; font-weight:400; line-height: 1.3; color:#212121;}
  .vps-accordion .panel-heading h4.panel-title a:hover {color:#DA3867;}
  .vps-accordion .panel-heading h4.panel-title i {margin:2px 7px 0 0; vertical-align:middle; font-size:19px; color:#DA3867;}
  .vps-accordion .panel-body {padding:15px 0; margin:0;}
  .vps-accordion .panel-body p {text-align: left; font-size:16px; padding:0; margin:0;}

  /* Responsive Table - VPS */
  .vps-table {background: url(images/vps-table-bg.png) no-repeat; background-size:cover; padding:70px 0; z-index:0; position: relative;}
  .vps-products-table { min-width:100%; border:0; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif!important;margin-bottom:45px; }
  .vps-products-table thead {border:0;background:transparent;}
  .vps-products-table thead th {background:#FF4081; color:#fff!important; font-weight:900;  font-size:18px!important; border:0!important; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif!important;  text-shadow: none; padding-top:10px!important; padding-bottom:10px!important; text-align: center;}
  .vps-products-table thead th span {display:block; width:100%; margin-top:6px;}
  .vps-products-table thead th:first-child, .vps-products-table thead tr {background:transparent;}
  .vps-products-table th {font-weight: normal;    -webkit-font-smoothing: antialiased;   padding:16px 12px; color: #424242;   font-size: 14px; background: #fff; }
  .vps-products-table td {color: #424242;    padding:16px 12px; font-size: 14px; border-right:1px solid #eae8e8; text-align: center;}
  .vps-products-table td:first-child {text-align: left;}
  .vps-products-table td:last-child {border-right:0;}
  .vps-products-table tr {  background: #fff; }
  .vps-products-table td i.fa-times {color:#ff4081;}
  .vps-products-table td i.fa-check {color:#258D5C;}
  .vps-products-table tr.price-comparison {background:transparent;}
  .vps-products-table tr.price-comparison td {font-weight:300; font-size:23px; letter-spacing: -.06em; background:#ee2f70; border:0; color:#fff;}
  .vps-products-table tr.price-comparison td:first-child { background:transparent;  border-top:0; }
  /* End of Responsive Table */

 /* ========================
  6 = Dedicated Servers
  ======================== */
  #subheader.dedicated-servers {background:url(images/deticated-servers-bg.png); padding:100px 25px;}
  #subheader.dedicated-servers h1 {color:#424242; text-shadow:none; }
  #subheader.dedicated-servers h2 {color:#424242;}

  .pricingbox.servers {padding:55px 0 90px;}

  /* Dedicated Servers Table */
  .moreservers{ width: 100%; background: #212832; padding:55px 0 40px;border-top:1px solid #252d38; position:relative; }
  .moreservers h3 {color:#fff; letter-spacing: -.05em; margin-bottom:30px; text-align: center; font-size:29px;}
  .moreservers button{ position:absolute; top:100%; left:50%; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%); margin-top:40px; z-index:9; font-size:16px; line-height:29px; font-weight:300;}

  .servers-table {padding:75px 0 55px; overflow:hidden; display: none;}
  .server-products-table { min-width:100%; border:1px solid #eae8e8; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif!important;margin-bottom:45px; }
  .server-products-table thead {border:0;background:transparent;}
  .server-products-table thead th {background:#3F51B5; color:#fff!important; font-weight:900;  font-size:15px!important; border:0!important; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif!important;  text-shadow: none; padding-top:10px!important; padding-bottom:10px!important; text-align: center;}
  .server-products-table th {font-weight: normal;    -webkit-font-smoothing: antialiased;   padding:16px 12px; color: #424242;   font-size: 14px; background: #fff; }
  .server-products-table td {color: #424242;    padding:16px 12px; font-size: 14px; border-right:1px solid #eae8e8; text-align: center;}
  .server-products-table td:first-child, .server-products-table thead th:first-child {text-align: left;}
  .server-products-table td:last-child {border-right:0;}
  .server-products-table tr {  background: #fff; }
  .server-products-table td i.fa-times {color:#ff4081;}
  .server-products-table td i.fa-check {color:#258D5C;}

  /* Features */
  .features-server {background:#F0F0F0; padding:80px 0 55px;  overflow:hidden;}
  .features-server h3 {color:#424242; letter-spacing: -.05em; margin-bottom:30px; padding: 0 20px; font-size:29px;}
  .features-server p {font-size:17px; padding: 0 50px;}
  .server-feature {margin-bottom:40px;}
  .rightside {text-align:right;}
  .server-feature h4 {color:#3F51B5; margin-bottom:5px; padding: 0; font-size:18px;}
  .server-feature p {font-size:16px; padding: 0; margin-bottom: 0;}

/* ========================
  7 = Domains
  ======================== */

  .domainavailability {padding:55px 0 70px;background: #303843;}
  .domainavailability h1 {font-size:29px; display:table; border-bottom:0; padding:15px; margin:0 auto;color:#fff; font-weight:700; margin-bottom:40px; letter-spacing: -.05em;}
  .domain-form-container {   background:#000; position: relative;   top: 0;   opacity: 1;   float: left;   padding: 30px 50px;   width: 100%;   border-radius: 0;   transform: scale(1);   -webkit-transform: scale(1);   -ms-transform: scale(1);   z-index: 5;}
  .domain-form-container:before {  background:rgba(0,0,0,.5); content: "";   width: 100%;   height: 30px;   border-radius: 0;   position: absolute;   top: -10px;   left: 0;   transform: scale(.95);   -webkit-transform: scale(.95);   -ms-transform: scale(.95);   z-index: -1;}
  .domainavailability .material .material-input :focus ~ label, .domainform .material .material-input .filled ~ label {font-weight:300;}
  .domainavailability .material .material-input label {margin-top:7px;}
  .domainavailability .material .material-input input { font-size: 16px;   height:41px; width: 100%;    border:0;    border-bottom: 1px solid lightgray;    outline: none;    background: 0;    float:left;}
  .domainavailability .material .material-select { font-size: 14px;}
  .domainavailability .material .material-select ul {padding:0; margin:0; list-style:none;}
  .domainavailability button {width: 100%; -webkit-border-radius:0;  -moz-border-radius:0;  margin-top:22px; font-weight: 700;  outline: none;  -webkit-box-shadow: none;  -moz-box-shadow: none;  box-shadow: none; border:0; background:#FF4081; color:#fff;}
  .domainavailability button i {font-size:16px;}

  /* Domain TLDs */
  .domaintlds {padding:55px 0; background:#eee;  overflow:hidden;}
  .domaintlds h2 {letter-spacing: -.05em; font-size: 29px; margin-bottom:22px;}
  .domaintlds p.subtitle {padding:0 100px;}
  .domain-tlds-grid {text-align:center; margin:50px 0;}
  .domain-tlds-grid .block-grid-item {padding:25px;}
  .domain-tlds-grid .block-grid-item .tld {padding:25px;  background: #fff; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
  .tldprice {font-size:15px; padding-top:20px; margin:30px 0 0; border-top:2px solid #e2e0e0; position:relative; background: #ffffff;}
  .tldprice:after, .tldprice:before {  bottom: 100%;  left: 50%;  border: solid transparent;  content: " ";  height: 0;  width: 0;  position: absolute;  pointer-events: none;}
  .tldprice:after {  border-color: rgba(255, 255, 255, 0);  border-bottom-color: #ffffff;  border-width: 10px;  margin-left: -10px;}
  .tldprice:before {  border-color: rgba(204, 204, 204, 0);  border-bottom-color: #e2e0e0;  border-width: 13px;  margin-left: -13px;}
  .domaintlds h3 {font-size: 29px; letter-spacing: -.05em;}
  .domaintlds h3 strong {color:#ff4081; }
  .domaintlds h3 span {display:block; color:#ff4081; padding-top:10px;}

  .domain-prices {padding:67px 0; overflow:hidden; background: url(images/affiliates_steps.jpg);}
  #tld-table {min-width:100%; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; background: #fff; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12); border: 0; font-size: 16px; position: relative;  white-space: nowrap; }
  #tld-table thead {border:0!important; }
  #tld-table thead th {background:#FF4081; color:#fff!important; font-weight:900;  font-size:14px; position:relative; -webkit-box-shadow: -1px 0px 0px 0px rgba(255,255,255,.3);-moz-box-shadow: -1px 0px 0px 0px rgba(255,255,255,.3);box-shadow: -1px 0px 0px 0px rgba(255,255,255,.3); text-align:center; text-shadow: none; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif;}
  #tld-table thead th:first-child {box-shadow:none;}
  #tld-table th {font-weight: normal; -webkit-font-smoothing: antialiased;   padding:16px 12px; color: #6E6E6E;   font-size: 16px; background: #FFFFFF; }
  #tld-table td {color: #6E6E6E;    padding:16px 12px; font-size: 16px; border-bottom:1px solid #DFE0E5; text-align: center;}
  #tld-table td:first-child { font-weight:bold; text-align: left; background:#eee;}
  #tld-table thead th:first-child { text-align: left; }
  #tld-table tr.even, #tld-table tr.alt, #tld-table tr:nth-of-type(even) {  background: #FFFFFF!important; }

  /* Features */
  .domain-features-text {padding:67px 0 60px; overflow:hidden; background:#eee;}
  .domain-features-text h4 {color:#424242; margin-top:0; font-size:29px; letter-spacing: -.05em;}
  .domain-features-text h5 {font-size:23px; color:#FF4081; letter-spacing: -.05em;}
  .domain-features {padding:55px 0; overflow:hidden; border-top:4px solid #dcdada;}
  .domain-features h5 {font-weight:700; font-size:20px;  padding:0 0 6px; color:#FF4081; letter-spacing: -.05em;}
  .domain-features p {font-size:17px; }
  .domain-features img {margin-top:15px; background:#eee; padding:10px;}

/* ========================
  8 = About Us
  ======================== */

  #subheader.about {background: url(images/about_bg.jpg) center center no-repeat; padding:100px 25px;}
  #subheader.about:after { background: rgba(34,43,50,.9); bottom: 0px; content: ""; left: 0; position: absolute; right: 0; top: 0; z-index: 1; }

  /* Description */
  .about-descr {padding:55px 0 67px;  overflow:hidden;}
  .about-descr h3 {color:#424242; letter-spacing: -.05em; margin-bottom:0; padding: 0; text-align:center; font-size:29px;}
  .about-descr p {font-size:17px;}
  .about-descr p.topspacing {padding-top:50px;}
  .about-descr p.description {padding:0 40px; margin-bottom:55px; text-align:center; }
  .about-icons {background:#3F51B5; padding:67px 0 55px;  overflow:hidden; text-align:center;}
  .about-icons p {font-weight:100; font-size:21px; color:#fff; margin-top:25px;}
  .about-team {padding:55px 0;  overflow:hidden;}
  .about-team h3 {color:#424242; letter-spacing: -.05em; margin-bottom:30px; padding: 0; text-align:center; font-size:29px;}
  .about-team p {padding:0 40px; margin-bottom:55px; text-align:center; font-size:19px;}

  /* Team */
  .team-grid {margin-top:15px;}
  .team-grid .block-grid-item {padding:0; margin:0;}
  .team-grid .block-grid-item h6 {font-weight:700; font-size:20px; text-align: center; margin-bottom:0; padding:0;letter-spacing: -.05em;}
  .team-grid .block-grid-item p {font-size:16px; text-align: center; margin-bottom:17px;}

  /* Timeline */
  .about-timeline {padding:65px 0;  overflow:hidden; background:#eee;}
  .timeline {  list-style: none;  position: relative;  max-width: 1170px;  padding: 20px;  margin: 0 auto;  overflow: hidden; }
  .timeline:after {    content: "";    position: absolute;    top: 0;    left: 50%;    margin-left: -2px; background: #dad7d7; height: 100%;  width: 2px;  display: block; }
  .timeline .timeline-row {padding-left: 50%; position: relative; z-index: 10; }
  .timeline .timeline-row .timeline-time { position: absolute; right: 50%; top: 40px; text-align: right; margin-right: 40px; font-size: 25px;line-height: 1.3;font-weight: 300; color:#424242; }
  .timeline .timeline-row .timeline-icon {position: absolute; top: 37px;left: 50%;  margin-left: -18px; width: 36px; height: 36px; background:#80D5DD; overflow: hidden; z-index: 100; border-radius:50%; border:8px solid #eee;}
  .timeline .timeline-row .timeline-content {margin-left: 40px; position: relative; background: #ff4081;  color: #fff; border-radius: 0;  opacity: 1; transform: scale(1);   -webkit-transform: scale(1);   -ms-transform: scale(1);   z-index: 5; padding:25px;}
  .timeline .timeline-row .timeline-content:before {   content: "";   width: 100%;   height: 30px;   border-radius: 0;   position: absolute;   top: -10px;   left: 0;   transform: scale(.95);   -webkit-transform: scale(.95);   -ms-transform: scale(.95);   z-index: -1; background: rgba(255,64,129,.5); }
  .timeline .timeline-row .timeline-content:after { content: "";position: absolute; top: 53px;  left: -41px;  height: 2px; width: 40px; background: #dad7d7;
  z-index: -1; }
  .timeline .timeline-row .timeline-content .panel-body {padding: 15px 15px 2px; position: relative;z-index: 10;  }
  .timeline .timeline-row .timeline-content h2 {font-size: 19px; margin-bottom: 12px; margin-top: 0; line-height: 1.2; text-transform: uppercase; letter-spacing: -.03em; color:#fff;}
  .timeline .timeline-row .timeline-content p {margin-bottom: 15px; }
  .timeline .timeline-row:nth-child(odd) { padding-left: 0; padding-right: 50%; }
  .timeline .timeline-row:nth-child(odd) .timeline-time { right: auto; left: 50%; text-align: left; margin-right: 0; margin-left: 40px; }
  .timeline .timeline-row:nth-child(odd) .timeline-content { margin-right: 40px;  margin-left: 0; }
  .timeline .timeline-row:nth-child(odd) .timeline-content:after { left: auto; right: -41px; }
  .timeline.animated .timeline-row .timeline-content { left: 20px; -webkit-transition: all 0.8s; -moz-transition: all 0.8s; transition: all 0.8s; }
  .timeline.animated .timeline-row:nth-child(odd) .timeline-content { left: -20px; }
  .timeline.animated .timeline-row.active .timeline-content { left: 0; }
  .timeline.animated .timeline-row.active:nth-child(odd) .timeline-content {left: 0; }

/* ========================
  9 = FAQ
  ======================== */

  #subheader.faq {background:#3F445B; padding:100px 25px;}

  /* FAQ categories and accordions */
  .faq-tabs {padding:40px 0; background:#E9E9E9; overflow:hidden;}
  .faq-categories {overflow:hidden;}
  .faq-categories ul {list-style: none; padding:0; margin:0;}
  .faq-categories ul li a {border:3px solid #C6C6C8; color: #999; font-weight:400;  display: block; float: left; font-size: 15px;    margin: 0 6px 6px 0;  padding: 7px 10px;    position: relative; border-radius:8px;}
  .faq-categories ul li a span.badge {margin-left:5px; font-size:11px; background:#b2b2b4; padding:4px 7px 5px;}
  .faq-categories ul li a:hover, .faq-categories ul li.active a { border-color:#9E9996; color:#fff; background:#9E9996;}
  .faq-categories ul li a:hover span.badge, .faq-categories ul li.active span.badge {background:#fff;color: #999;}

  .faq-tabs-white {padding:55px 0; overflow:hidden;}
  .faq-tabs-white .tab-content {font-size:16px;}
  .faq-tabs-white .panel {box-shadow: none !important; background:transparent;}
  .faq-tabs-white .panel, .faq-tabs-white .panel-group .panel-heading+.panel-collapse>.panel-body{ border: none; box-shadow: 0;}
  .faq-tabs-white .panel-body {border-top: 0 !important;}
  .faq-tabs-white .panel-heading {border:0; border-bottom:1px solid #E9E9E9; background:transparent;  border-radius:0; padding:12px 0;  }
  .faq-tabs-white .panel-heading h4.panel-title a {font-size:16px; font-weight:400; line-height: 1.3; color:#212121;}
  .faq-tabs-white .panel-heading h4.panel-title a:hover {color:#DA3867;}
  .faq-tabs-white .panel-heading h4.panel-title i {margin:2px 7px 0 0; vertical-align:middle; font-size:19px; color:#DA3867;}
  .faq-tabs-white .panel-body {padding:15px 0; margin:0;}
  .faq-tabs-white .panel-body p {text-align: left; font-size:15px; padding:0; margin:0;}


  /* Support Nethods */
  .other-support-methods {padding:67px 0; background:url(images/other-support-bg.png); overflow:hidden;}
  .other-support-methods h3 {color:#fff; letter-spacing: -.05em; margin:0 0 20px; padding: 0; font-size:29px;}
  .other-support-methods p {color:#fff; margin:0; font-size:16px;}
  .support-method {padding-left:80px; margin-bottom:50px;}
  .support-method:last-child {margin-bottom:0;}
  .support-method h4 {padding: 0 0 15px; margin:0; font-size:24px; color:#fff;}
  .support-method h4 i {margin-right:8px; color:#E9E9E9;}
  .support-method p {color:#ccc; font-size:17px;}
  ul.support-links {margin:80px 0 0; padding:0; list-style:none;}
  ul.support-links li {background:#3b3f56; padding:8px 12px; margin-bottom:1px; color:#fff; font-size:16px;}
  ul.support-links li i {margin-right:8px; }
  ul.support-links li a {color:#fff; font-weight:300; }
  ul.support-links li a span {color:#01ABEF; font-weight:500;}

/* ========================
  10 = Datacenter
  ======================== */

  #subheader.datacenter {background:#3F445B;  padding:100px 25px;}

  /* Description */

  .datacenter-descr {padding:55px 0;  overflow:hidden; background: #fff url(images/dc_bg.jpg) center center no-repeat; background-size:cover; text-align:center; min-height:680px;}
  .datacenter-descr h3 {color:#424242; margin-bottom:0; padding: 0; font-size:29px; letter-spacing: -0.05em;text-align:center;}
  .datacenter-descr p {font-size:17px;  text-align:center;}

  .datacenter-grid {text-align:center; padding-top:40px;}
  .datacenter-grid .block-grid-item {text-align: left; padding:15px 25px; background:#F0F0F0; margin:1%; width:48%;}
  .datacenter-grid .block-grid-item.blue {background:#3F51B5; color:#fff;}
  .datacenter-grid .block-grid-item.gray {background:#494E66; color:#fff;}
  .datacenter-grid .block-grid-item.pink {background:#FF377D; color:#fff;}
  .datacenter-grid .block-grid-item.green {background:#51AF56; color:#fff;}
  .datacenter-grid .block-grid-item.blue h5, .datacenter-grid .block-grid-item.gray h5, .datacenter-grid .block-grid-item.pink h5, .datacenter-grid .block-grid-item.green h5 {color:#fff;}

  .datacenter-grid .block-grid-item h5 {font-size:22px;padding-top:5px; letter-spacing: -0.05em;}
  .datacenter-grid .block-grid-item p {margin-top:0; padding:0; text-align:left;  font-size:15px;}

  /* Map */

  .map_wrapper {padding:55px 0; background:url(images/other-support-bg.png);  }

  .datacenter-photos {padding:55px 0 75px;  overflow:hidden; background:#eee;}
  .datacenter-photos h3 {color:#424242; margin-bottom:0; padding: 0; font-size:29px; letter-spacing: -0.05em;text-align:center;}
  .datacenter-photos p {font-size:17px;  text-align:center;}

  #gallerypostContainer {margin-top:45px;}

/* ========================
  11 = Affiliates
  ======================== */

  #subheader.affiliates {background: url(images/affiliates_bg.jpg) center center no-repeat; }
  #subheader.affiliates:after { background: rgba(34,43,50,.9); bottom: 0px; content: ""; left: 0; position: absolute; right: 0; top: 0; z-index: 1; }
  #subheader.affiliates .mtr-btn {margin-top:35px;}

  /* Description */
  .affiliates-descr {padding:55px 0 70px;  overflow:hidden;}
  .affiliates-descr h3 {color:#424242; letter-spacing: -.05em; margin-bottom:20px; padding: 0 20px; font-size:29px;}
  .affiliates-descr p.description {padding:0 40px; margin-bottom:55px; text-align:center;}
  .affiliates-descr .number {color:#EB1E94; font-size:20px; font-weight:100; background:#ccc; padding:10px; text-align:center; margin-top:20px; border-radius:6px;}
  .affiliates-descr .number.darkgray {background:#2C2C2C;  color:#fff;}
  .affiliates-descr .number.red {background:#CA2C46; color:#fff;}
  .affiliates-descr .number.green {background:#89B22D; color:#fff;}
  .affiliates-descr h4 {color:#424242; padding:18px 0 10px; margin:0; font-size:18px;}
  .whiteframe {padding:15px; background:#fff; border: 1px solid #ccc; border-radius:5px; box-shadow:inset 0 -4px 0 0 #f6f6f6, inset 0 -5px 0 0 #ddd, inset 0 -10px 0 0 #f6f6f6, inset 0 -11px 0 0 #ddd,0 2px 8px -2px rgba(0, 0, 0, 0.1);}

  /* Counters */
  .affiliates-counts {background:url(images/affiliates_steps.jpg) center center no-repeat; padding:80px 0;  overflow:hidden; text-align:center;}
  .affiliates-counts .odometer {color:#fff; font-size:50px; font-weight:900; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif;}
  .affiliates-counts #odometer1.odometer:after {content: "$";  font-size:30px; margin:4px 0 0 4px; font-weight:100;}
  .affiliates-counts #odometer3.odometer:after {content: "%";  font-size:30px; margin:4px 0 0 4px; font-weight:100;}
  .odometer-inside {  display: inherit;}
  .affiliates-counts p {font-size:17px; font-weight: 300; margin:10px 0 0; color:#fff;}

  /* How it Works */
  .howitworks {padding:55px 0 70px; background: #eee;  overflow:hidden;}
  .howitworks h3 {color:#424242; letter-spacing: -.05em; margin-bottom:20px; padding: 0 20px; font-size:29px;}
  .howitworks p.description {padding:0 40px; margin-bottom:55px; text-align:center;}
  .howitworks .mtr-btn {margin-top:60px;}
  .affiliates-examples {text-align:center; padding-bottom:20px; background:#fff; color:#424242; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
  .affiliates-examples p { margin-bottom:0; font-weight:300; font-size:16px; background:#75787A;  padding:15px; color:#fff; }
  .affiliates-examples h5 { margin:0; padding:12px 0 0; font-size:40px; font-weight:900; }
  .affiliates-examples span { margin:0; padding:0; font-weight:300; font-size:14px; }
  .affiliates-features {padding:55px 0 67px; background: #fff;  overflow:hidden;}
  .affiliates-features i {font-size:60px; color:#B9B9B9; vertical-align: top; margin-top:25px; float:right;}
  .affiliates-features h5 {font-size:22px;  padding:15px 0 6px; color:#3F51B5;}
  .affiliates-features p {font-size:17px; }

/* ==============================
   12 = Blog
   ============================== */
   #subheader.blog {background:#3F445B;  padding:100px 25px;}
   #subheader.blog h2 a {color:#ccc;}
   #subheader.blog .mtr-btn {position:absolute; top:100%; left:50%; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%);z-index:9; font-size:16px; line-height:29px; font-weight:300; padding-top:12px;}
   .popover.sharing {background:#3F445B; border:0; border-radius:2px; padding:5px; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);z-index: 998;}
   .popover.sharing.bottom .arrow:after {  border-bottom-color: #3F445B;}
   .popover.sharing .popover-title {background:transparent; border-color:#444960;}
   .popover.sharing h3.popover-title {color:#fff; font-weight:300; text-align: center;}
   .blog-share-buttons {margin:0 auto; padding:0; display: table;}
   .blog-share-buttons li {  list-style: none;  display: inline-table;}
   .blog-share-buttons li a {  color:#fff; display: inline-block;  padding-top:10px;  text-align: center;  height: 42px;  width: 42px;  position: relative;    z-index: 1;  -webkit-transition: color 0.15s;  transition: color 0.15s;   -moz-osx-font-smoothing: grayscale; border-radius:50%; -webkit-backface-visibility: hidden;}
   .blog-share-buttons li a::before {  content: '';  position: absolute;  top: 0;  left: 0;  width: 100%;  height: 100%;  border-radius: inherit;  z-index: -1;  box-shadow: inset 0 0 0 35px #50556d;  -webkit-transform: scale3d(0.8, 0.8, 1);  transform: scale3d(0.8, 0.8, 1);  -webkit-transition: box-shadow 0.15s, -webkit-transform 0.15;  transition: box-shadow 0.15s, transform 0.15s;}
   .blog-share-buttons li a:hover::before {  -webkit-transform: scale3d(1.0, 1.0, 1);  transform: scale3d(1.0, 1.0, 1); box-shadow: inset 0 0 0 35px #FF4081;}
   .blog { background: #ECECEC; padding:60px 0 15px;}
   .blog article {background: #fff; border-radius:0; margin-bottom:70px; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
     .blog.single {padding:75px 0 60px;}
   .blog.single article {margin-bottom:35px;}
   .blog article .post-content {padding:25px;}
   .blog article .post-content h2 {font-size:29px;letter-spacing: -.05em; margin:10px 0 17px; padding:0; text-transform: uppercase;}
   .blog article .post-content h2 a {color:#666;}
   .blog article .post-content h2 a:hover {color:#212121;}
   .blog article .post-content hr {border-color:#ECECEC;}
   .blog article .post-content .themeta {font-family: 'Montserrat', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; color:#abaaaa; font-size:13px; font-weight:400;margin:12px 0 17px; }
   .blog article .post-content p {font-size:17px;}
   .blog article .post-content ul li {font-size:17px; font-weight:300;}
   .blog article .post-content .mtr-btn {margin:15px 0 10px;}
   .blog article .post-content blockquote {border: 0; border-left:5px solid #ff4081; background:#ebebeb; font-size:17px; font-weight:300; padding:12px 18px;}
   .blog .sidebar {background: #fff; border-radius: 0; padding:15px 25px; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
   .blog .sidebar .widget {margin-bottom:45px;}
   .blog .sidebar .widget h3.badge {border-radius:0; padding:12px; display:block; font-size:16px; text-align: left; color:#fff; background:#3F445B;}
   .blog .sidebar .widget ul {padding:0; margin:0; list-style:none;}
   .blog .sidebar .widget ul li {padding:9px 6px; font-size:15px; border-bottom:1px solid #EDEDED;}
   .blog .sidebar .widget ul li span.badge {float:right; margin-top:2px; background:#ff4081; border-radius: 2px;}
   .blog .sidebar .widget ul li a {color:#424242;}
   .blog .sidebar .widget ul li a:hover {color:#000;}
   .blog .sidebar .widget .blogsearch input[type="text"].form-control { border:0; box-shadow:none; border-radius: 6px; font-size: 18px; height: 55px; padding: 5px 15px; width: 100%; background: #EDEDED; }
   .tagcloud {overflow:hidden;}
   .tagcloud a { background: #ECECEC;    border: 0 none;    color: #424242;  font-weight:300;  display: block;    float: left;    font-size: 13px;    margin: 0 3px 3px 0;    padding: 5px 7px;    position: relative; border-radius:2px;}
   .tagcloud a:hover { background: #ff4081; color:#fff;}
   .blog nav ul.pagination {display:table; margin:0 auto; margin-bottom:45px; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
   .blog nav ul.pagination li {font-size:15px;}
   .blog nav ul.pagination li a {color:#424242; padding: 10px 18px 8px;}
   .blog nav ul.pagination li a:hover {background:#ECECEC; }

   /* Author box */
   .author-wrap {position: relative;  overflow:hidden; padding:0; background: #fff; border-radius: 0; margin-bottom:35px; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
   .author-gravatar {margin: 0;line-height: 1; background: url(images/s8.png) repeat; min-height:150px; position:relative;}
   .author-gravatar img {width:96px; -webkit-border-radius:50%;-moz-border-radius:50%;border-radius:50%; left: 50%; top:50%; position: absolute; text-align: center; z-index: 2; transform: translate(-50%, -50%);  -webkit-transform: translate(-50%, -50%); -ms-transform: translate(-50%, -50%); box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
   .author-info {padding:30px 20px;}
   .author-title {color: #424242;display: block;line-height: 1.5;margin: 0; padding: 0 0 10px;}
   .author-title h6 {padding:0; margin: 0 0 6px;font-size: 24px; color:#3F51B5; letter-spacing: -.05em;}
   .author-description {display: block; margin: 0 0 5px;}
   .author-description p {margin: 0; font-size: 17px;}

   /* Comments */
   .comments, #addcomments {padding:20px 30px 30px; background: #fff; border-radius: 0; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
   .comments { margin-bottom:35px;}
   #thecomments {margin-top: 0;}
   #thecomments h2, #respond h2 { font-size: 24px; color:#3F51B5; letter-spacing: -.05em;}
   #addcomments {margin-top: 0;}

   /* Comments List */
   ol.commentlist { margin: 0;  padding: 0;}
   .commentlist .comment-body{ padding: 0; margin: 0;  position: relative;    border-top: 0;}
   .comment-body a:hover{  text-decoration: underline;}
   .comment-body a.comment-reply-link {margin: 0; text-decoration:none; color:#fff; font-size:10px; border:0; -webkit-border-radius: 2px;-moz-border-radius: 2px;border-radius: 2px;}
   ol.commentlist li {  margin-top:0;  list-style: none;    padding: 20px 0;     background:#fff;  border-bottom: 1px solid #e9e9e9;}
   ol.commentlist li ul.children {margin-bottom: 0px !important;    margin-top: 25px !important;}
   ol.commentlist li ul.children li{ border-bottom: 0; padding-left: 20px  !important; margin: 10px 0; border-left:1px solid #e8e8e8;}
   ol.commentlist li ul.children .comment-body{ padding: 15px 0 5px;  margin: 10px 0 0; position: relative;}
   .reply {margin-bottom:10px;}
   ol.commentlist img.avatar { margin:10px 20px 0 0; float:left; width:48px;  -webkit-border-radius:50%;-moz-border-radius:50%;border-radius:50%;  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
   ol.commentlist .comment-author { line-height: 25px; border:0; width:100%; }
   .comment-body h6 {  margin:0; padding:14px 0 0; font-size:18px; letter-spacing: -.05em;}
   .comment-body h6 a {color: #424242; }
   .comment-body h6 a:hover {color: #DE6262; text-decoration: none;}
   .comment-time{  font-size: 12px;  font-style: normal;    color: #ccc;}
   .commentmetadata {  clear: both;    padding: 0;    margin: 0;}
   .commentmetadata a{ margin: 0;  color: #000;    text-decoration: underline;}
   .comment-body p{ padding:20px 0 6px; font-weight:300;}
   .comment-body .comment-author.vcard{  margin: 0; border-bottom: 1px solid #e8e8e8; padding-bottom:15px;}
   .comment-body ul, .comment-body ol {padding:0; margin:0;}
   .comment-body ul li, .comment-body ol li {padding:7px 0; margin:0; border:0;}
   .comment-body ul li ul, .comment-body ol li ol {padding:7px 0 7px 7px; margin:0; border:0;}
   #reply-title { margin:10px 0; padding:0 0 5px; font-weight:normal; font-size:26px; line-height:1.3; display: block; margin-bottom:-2px; font-weight: 700;}
   .comment-notes {padding:25px 0 0;}
   form#commentform input#submit {margin-top: 0; border:0; -webkit-border-radius: 2px;-moz-border-radius: 2px;border-radius: 2px;}

/* ==============================
   13 = Contact
   ============================== */
   #subheader.contact {background: url(images/contact_bg.png) center bottom no-repeat; padding:100px 25px;}
   #map_wrapper { height: 450px;}
   #map_canvas {width: 100%; height: 100%;}
   #map_canvas img {max-width: none;}
   .contact-elements {padding:55px 0 70px; background:#F1F1EF;}
   .contact-elements h3 {margin:0; padding:0; font-size:29px; }
   .contact-elements h4 {margin:10px 0; padding:0; font-size:22px; }
   .contact-elements p {padding:15px 0; margin-bottom:0;}
   .contactmethod {padding:15px; min-height:200px; color:#fff; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
   .contactmethod.purple {background:#9A22AC;}
   .contactmethod.blue {background:#3F90EF;}
   .contactmethod.green {background:#51AF56;}
   .contactmethod.darkgray {background:#4B4B4B;}
   .contactmethod h5 { margin:0; padding:0 0 12px; font-size:20px; border-bottom:1px solid rgba(255,255,255,.1); color:#fff;}
   .contactmethod p { margin-bottom:0; font-weight:300; font-size:15px; padding:12px 0 0; color:#fff; }
   .contactmethod p a {color:#fff; text-decoration: underline; font-size:500;}
   .contactmethod p span {display:block;}
   .contactmethod .mtr-btn {margin-top:15px;}
   #contactform  {margin-top:35px; padding:10px 25px 45px; font-size:16px; background:#fff; border: 1px solid #ccc; border-radius:5px; box-shadow:inset 0 -4px 0 0 #f6f6f6, inset 0 -5px 0 0 #ddd, inset 0 -10px 0 0 #f6f6f6, inset 0 -11px 0 0 #ddd,0 2px 8px -2px rgba(0, 0, 0, 0.1);}
   #contactform .material input, #contactform .material textarea {box-shadow:none; border-radius: 0; padding-left:0; padding-right:0;}
   #contactform .material p {padding:0;margin:0;}
   #contactform input#submit {background:#898BFE; color:#fff; margin-top:21px;  font-size:15px; border:0; line-height:15px; -webkit-border-radius: 2px;-moz-border-radius: 2px;border-radius: 2px; width:auto;  color:#fff; box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.12);}
   #sendstatus { margin: 10px 0 0;}
   #sendstatus .alert.alert-danger {border:0; background:#C266D3; color:#fff; border-radius: 0; margin-bottom:2px;}
   #sendstatus .alert.alert-success {border:0; background:#6FCCC6; color:#fff; border-radius: 0;}


/* ==============================
   14 = Elements
   ============================== */
   .elements { background: #e0e1e7; padding:20px 0 45px; overflow:hidden;}
   h2.elements { font-weight: 300; margin: 30px 0; font-size:24px; text-align:center; border-bottom: 4px solid #009DE0; padding-bottom:12px; background:#01ABEF; color:#fff;}
   .elements p { font-size: 17px; font-weight: 300; margin: 18px 0 0;}
   blockquote {border: 0; border-left:5px solid #ff4081; background:#ebebeb; font-size:17px; font-weight:300; padding:12px 18px;}

   /* Accordion */
   #accordion.example .panel {box-shadow: none !important; background:transparent;}
   #accordion.example .panel, .vps-accordion .panel-group .panel-heading+.panel-collapse>.panel-body{ border: none; box-shadow: 0;}
   #accordion.example .panel-body {border-top: 0 !important;}
   #accordion.example .panel-heading {border:0; border-bottom:1px solid #d8d6d6; background:transparent;  border-radius:0; padding:12px 0;  }
   #accordion.example .panel-heading h4.panel-title a {font-size:16px; font-weight:400; line-height: 1.3; color:#212121;}
   #accordion.example .panel-heading h4.panel-title a:hover {color:#DA3867;}
   #accordion.example .panel-heading h4.panel-title i {margin:2px 7px 0 0; vertical-align:middle; font-size:19px; color:#DA3867;}
   #accordion.example .panel-body {padding:15px 0; margin:0;}
   #accordion.example .panel-body p {text-align: left; font-size:15px; padding:0; margin:0;}

   /* Horizontal Tabs */
   .ds-horizontal-tabs .tab-content {margin-top:45px; border-top:1px solid #d9d1d5; padding:45px 0; font-size:16px;}
   .ds-horizontal-tabs .tab-content h4 {font-weight:300; font-size:21px; color:#FF4081; display: block; margin:0 0 20px;}
   .ds-horizontal-tabs .tabs-top-horizontal > .nav-tabs {  display:table;  margin:0 auto; }
   .ds-horizontal-tabs .tab-content > .tab-pane,.pill-content > .pill-pane {  display: none;}
   .ds-horizontal-tabs .tab-content > .active,.pill-content > .active {  display: block;}
   .ds-horizontal-tabs .tabs-top-horizontal > .nav-tabs > li {  float: left;  text-align: center; border:0; margin-bottom: 0; background: #e9e9e9;}
   .ds-horizontal-tabs .tabs-top-horizontal > .nav-tabs > li > a {  margin-right: 0;color:#424242;padding:10px;-webkit-border-radius:0;-moz-border-radius:0; border-radius:0; border:0; text-transform: uppercase;font-size:14px;font-weight:400;}
   .ds-horizontal-tabs .tabs-top-horizontal > .nav-tabs > li.active:after > a { content:"";}

   /* Vartical Tabs */
   .ds-vertical-tabs .tab-content {padding:0 50px; font-size:16px; float:right; width:85%;}
   .ds-vertical-tabs .tab-content h4 {font-weight:300; font-size:31px; color:#FF4081; display: block; margin:0 0 20px;}
   .ds-vertical-tabs .tab-content hr.small {margin:21px 0; border-color:#d8d6d6;}
   .ds-vertical-tabs .tabs-left-vertical > .nav-tabs { float:left; width:15%; }
   .ds-vertical-tabs .tab-content > .tab-pane,.pill-content > .pill-pane {  display: none;}
   .ds-vertical-tabs .tab-content > .active,.pill-content > .active {  display: block;}
   .ds-vertical-tabs .tabs-left-vertical > .nav-tabs > li { text-align: left;  display:block; width:100%; border:0; margin-bottom: 0; background: #e9e9e9;}
   .ds-vertical-tabs .tabs-left-vertical > .nav-tabs > li > a {  margin-right: 0;color:#424242;padding:20px 10px;-webkit-border-radius:0;-moz-border-radius:0; border-radius:0; border:0; text-transform: uppercase;font-size:14px;font-weight:400;}

   /* Buttons */
   .buttons-example {display:table; margin:0 auto;}
   .elements .btn {margin-bottom:12px;}
   .btn {text-shadow:none; border:0; }
   .btn.no-radius {border-radius: 0;}
   .btn.btn-default {background:#DADFE1;}
   .btn.btn-primary {background:#4B77BE;}
   .btn.btn-info {background:#59ABE3;}
   .btn.btn-success {background:#26C281;}
   .btn.btn-warning {background:#E67E22;}
   .btn.btn-danger {background:#F62459;}

   /* Counters */
   .counters .odometer {color:#424242; font-size:50px; text-align:center; font-weight:900; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif;}

   .elements h5.badge {font-size:18px; padding:9px 20px; background:#DE6262; display:table; margin:0 auto; margin-top:40px; margin-bottom:30px;}
   .pricingtables.default { background: #fff; overflow: hidden; padding:0; }
   .pricingtables.default .panel-heading { background: #222; }
   .pricingtables.default .most-popular .panel-heading { background: #3a5955; }
   .pricingtables.default .panel-heading h3 { color: #fff; font-size: 16px; font-weight: 400; letter-spacing: -.07em; margin: 0; padding: 12px 0; }

   /* BUTTONS */
   .mtr-btn {  border: none;    border-radius: 2px;   display: block;    position: relative;   min-width: 64px;    padding: 8px;    display: inline-block;  font-size: 14px;    font-weight: 500;    text-transform: uppercase;    letter-spacing: 0;    overflow: hidden;  will-change: box-shadow,transform;    -webkit-transition: box-shadow .2s cubic-bezier(.4,0,1,1),background-color .2s cubic-bezier(.4,0,.2,1),color .2s cubic-bezier(.4,0,.2,1);    transition: box-shadow .2s cubic-bezier(.4,0,1,1),background-color .2s cubic-bezier(.4,0,.2,1),color .2s cubic-bezier(.4,0,.2,1);    outline: none;    cursor: pointer;    text-decoration: none;    text-align: center;    vertical-align: middle; box-shadow: 0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);}
   .mtr-btn.btn-lg {  padding:12px 24px;  font-size: 20px;}
   .mtr-btn.btn-sm {  padding: 6px;  font-size: 13px;}
   .mtr-btn.btn-xs {  padding: 3px;  font-size: 12px; }
   .button-fab { color: #fff; background: #ff4081; }
   .button-raised {background: #ccc;}
   .button-white {background: #fff;}
   .button-purple {color:#fff; background:#7C57E4;}
   .button-blue {color: #fff; background: #3F51B5;}
   .button-navy {color: #fff; background:#01ABEF;}
   a.button-fab, a.button-purple, a.button-blue, a.button-navy { color: #fff; text-decoration: none;}
   a.button-fab:hover, a.button-purple:hover, a.button-blue:hover, a.button-navy:hover, a.button-fab:focus, a.button-purple:focus, a.button-blue:focus, a.button-navy:focus { color: #fff; text-decoration: none;}
   a.button-raised, a.button-white { color: #000; text-decoration: none;}
   a.button-raised:hover, a.button-white:hover, a.button-raised:focus, a.button-white:focus { color: #000; text-decoration: none;}

   .button-circle {border-radius: 50%;    font-size: 24px;    height: 56px;    margin: auto;    min-width: 56px;    width: 56px;    padding: 0;    overflow: hidden;
    box-shadow: 0 1px 1.5px 0 rgba(0,0,0,.12),0 1px 1px 0 rgba(0,0,0,.24);    position: relative;    line-height: normal; }
    button.button-circle i {color:#fff;}

    /* Ripple Effect */
    .ripple-wrapper {  display: block;  position: absolute;  background: rgba(255,255,255,0.4);  border-radius: 100%;  -webkit-transform: scale(0);  -ms-transform: scale(0);  -o-transform: scale(0);  transform: scale(0);}
    .ripple-wrapper.animated {  animation: ripple 0.65s linear;  -webkit-animation: ripple 0.65s linear;  -moz-animation: ripple 0.65s linear;  -o-animation: ripple 0.65s linear;}
    .has-ripple {  overflow: hidden;  position: relative;  user-select: none;  outline: none;}
    @keyframes ripple {  100% {    -webkit-transform: scale(2.5);    -ms-transform: scale(2.5);    -o-transform: scale(2.5);    transform: scale(2.5);    opacity: 0;  }}
    @-webkit-keyframes ripple {  100% {    -webkit-transform: scale(2.5);    -ms-transform: scale(2.5);    -o-transform: scale(2.5);    transform: scale(2.5);    opacity: 0;  }}
    @-o-keyframes ripple {  100% {    -webkit-transform: scale(2.5);    -ms-transform: scale(2.5);    -o-transform: scale(2.5);    transform: scale(2.5);    opacity: 0;  }}
    @-moz-keyframes ripple {  100% {    -webkit-transform: scale(2.5);    -ms-transform: scale(2.5);    -o-transform: scale(2.5);    transform: scale(2.5);    opacity: 0;  }}

    /* FORMS */
    .material .material-input{  position: relative; padding-top: 18px; margin-bottom: 10px; }
    .material .material-input:after{ display: block; clear: both; content:"";}
    .material .material-input input{ font-size: 16px; width: 100%; border:0; border-bottom: 1px solid lightgray; outline: none; background: 0; float:left;  height: 32px; color:#757575;  font-size: 12px; font-weight:500; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif;}
    .material .material-input textarea{ font-size: 16px; width: 100%; border:0; border-bottom: 1px solid lightgray; outline: none; background: 0; float:left; height: 120px; padding:7px 0;}
    .material .material-input label{ color:#757575; font-size: 14px; font-weight:500; font-family: 'Roboto', Optima, Segoe, "Segoe UI", Candara, Calibri, Arial, sans-serif; position: absolute; left:0; top:15px; line-height: 32px;}
    .material .material-bar{    position: absolute;    bottom:0;left:0;    display: block;    width: 100%;}
    .material .material-bar:before,.material .material-bar:after{    content:""; height: 2px; width: 0; bottom:0; position: absolute; background: #009DE0;}
    .material .material-bar:before{ left:50%; }
    .material .material-bar:after{ right:50%; }
    .material .material-input :focus ~ .material-bar:before,.material .material-input :focus ~ .material-bar:after{  width:50%;}
    .material .material-input :focus ~ label,.material .material-input .filled ~ label{ color:lightgray; font-size: 13px; top:0; line-height: 24px;}

    /* Radio */
    .material .material-group{    padding-top: 10px;}
    .material .material-group input{    display: none;}
    .material .material-group-item{    position: relative;    margin-bottom: 5px;}
    .material .material-group-item:last-child{    margin-bottom: 0;}
    .material .material-group label{    padding-left: 30px;    position: relative;    cursor: pointer;    z-index: 2;    font-weight: 300;}
    .material .material-checkbox,.material .material-radio{    width: 18px;    height: 18px;    background:#fff;    left:0;    top:50%;    margin-top: -9px;    position: absolute;    z-index: 1;    border: 2px solid gray;}
    .material .material-radio{    border-radius: 10px;}
    .material .material-checkbox{    border-radius: 3px;}
    .material .material-checkbox:before{    content:"a";    font-size: 14px;    text-align: center;    padding-top: 3px;    color:#fff;    background:gray;    position: absolute;    top:0;left:0;right:0;bottom:0;    -webkit-transform: scale(0);       -moz-transform: scale(0);        -ms-transform: scale(0);         -o-transform: scale(0);            transform: scale(0);}
    .material .material-radio:before{    position: absolute;    top:3px;left:3px;    width: 8px;    height: 8px;    border-radius: 4px;    background:gray;    content:"";    -webkit-transform: scale(0);       -moz-transform: scale(0);        -ms-transform: scale(0);         -o-transform: scale(0);            transform: scale(0);}
    .material input:checked ~ .material-radio:before,.material input:checked ~ .material-checkbox:before{    -webkit-transform: scale(1);       -moz-transform: scale(1);        -ms-transform: scale(1);         -o-transform: scale(1);            transform: scale(1);}

    /* Select */
    .material .material-select {    font-size: 16px;    font-weight: 300;    width: 100%;    position: relative;    margin-bottom: 10px;    padding-top: 18px;    z-index: 3;}
    .material .material-select input{display: none;}
    .material .material-select > label{    color:gray;    border-bottom: 1px solid lightgray;    height: 40px;    line-height: 40px;    padding:0 30px 0 0px;    width: 100%;    cursor: pointer;    position: relative;    display: block;}
    .material .material-select > .material-title{    position: absolute;    color:lightgray;    height: 40px;    line-height: 40px;    top:18px;left:0;    opacity: 0;    visibility: hidden;}
    .material .material-select > input:checked + .material-title,.material .material-select.filled > .material-title{    top:0;    opacity: 1;    visibility: visible;    font-size: 13px;    line-height: 24px;}
    .material .material-select > label strong{    border-color: lightgray transparent transparent transparent;    border-style: solid;    border-width: 6px 5px 0 5px;    margin-top: -3px;    width: 0;    height: 0;    position: absolute;    right:0;top:50%;}
    .material .material-select > input:checked ~ ul{    visibility: visible;    opacity: 1;    top:24px;}
    .material .material-select ul{    background:#fff;    top:0;    left:0;width: 100%;    position: absolute;    opacity: 0;    visibility: hidden;    z-index: 2;}
    .material .material-select ul li label{    color:gray;}
    .material .material-select ul li input:checked + label,.material .material-select ul li:hover input:checked + label{    font-weight: 400;}
    .material .material-select ul li label{    display: block;    cursor: pointer;    padding:7px 10px;}
    .material .material-select ul li label:hover{    background:#f5f5f5;}
    .material .material-select > input:checked + .material-bar{    top:22px;}
    .material .material-select .material-bar{    height: 2px;    background: #0000ff;    width: 0;    bottom:auto;    top:56px;}

    /* Shadow */
    .material .material-select ul{ box-shadow: 0 2px 2px rgba(0,0,0,.2);}

    /* Animation */
    .material .material-select ul,.material .material-bar:before,.material .material-bar:after,.material .material-input label,.material .material-select .material-bar,.material .material-select > span,.material .material-radio:before,.material .material-checkbox,.material .material-checkbox:before,.material .material-checkbox:after{    transition:.2s ease all;    -moz-transition:.2s ease all;    -webkit-transition:.2s ease all;}

    /* Disable select */
    .material{    -webkit-user-select: none;    -moz-user-select: none;    -ms-user-select: none;    user-select: none;}

    /* Material border box reset */
    .material *,.material *:before,.material *:after {    -webkit-box-sizing: border-box;    -moz-box-sizing:    border-box;    box-sizing:         border-box;}

/* ========================
  15 = Footer
  ======================== */
  /* Footer ---------------------- */
  .footer{ width: 100%; background: #01ABEF; padding:55px 0; }
  .footer h4 {color:#e0e0e0; font-weight:700; padding-bottom:17px; font-size: 20px; margin:0 0 17px; position:relative;}
  .footer h4::after {background-color: #0593D0; bottom: 0; content: ""; height: 1px; left: 0%; position: absolute; width: 40px;}
  .footer a {color:#eeeeee;}
  .footer a:hover {color:#01ABEF; text-decoration: none;}
  .footer ul {margin:0; padding:0; list-style:none;}
  .footer ul li {font-size:15px; font-weight:300; padding-bottom:4px;  list-style: none;}
  .footer ul li:last-child {border:0;}

  /* MailChimp Newsletter Form Styling  ----------------------- */
  #mc_embed_signup input[type="email"] { border-radius:0;}
  #mc_embed_signup input[type="submit"] { margin-top:10px;}

  /* Footer / Social Buttons ---------------------- */
  .social{ width: 100%; background: #0099d7; padding:20px 0; }
  .social-links {margin:0 auto; padding:0; display: table;}
  .social-links li {  list-style: none;  display: inline-table;}
  .social-links li a {  color:#fff; display: inline-block;  padding-top:10px;  text-align: center;  height: 42px;  width: 42px;  position: relative;    z-index: 1;  -webkit-transition: color 0.15s;  transition: color 0.15s;   -moz-osx-font-smoothing: grayscale; border-radius:50%; -webkit-backface-visibility: hidden;}
  .social-links li a::before {  content: '';  position: absolute;  top: 0;  left: 0;  width: 100%;  height: 100%;  border-radius: inherit;  z-index: -1;  box-shadow: inset 0 0 0 35px #333;  -webkit-transform: scale3d(0.7, 0.7, 1);  transform: scale3d(0.7, 0.7, 1);  -webkit-transition: box-shadow 0.15s, -webkit-transform 0.15;  transition: box-shadow 0.15s, transform 0.15s;}
  .social-links li a:hover::before {  -webkit-transform: scale3d(1.0, 1.0, 1);  transform: scale3d(1.0, 1.0, 1); box-shadow: inset 0 0 0 35px  #009DE0;}
  .social p {padding-top:15px; font-size:14px; margin-bottom:0;}

  /* Back to Top Button  ----------------------- */
  #back-to-top { color:#fff; position:fixed; bottom:20px; right:20px; z-index:99; display:none; text-align: center; border-radius: 50%; -moz-border-radius: 50%;  -webkit-border-radius:  50%; -o-border-radius:  50%;    z-index: 10000;    height: 59px;    width: 59px;    background-color:#6734BA;    background-repeat: no-repeat;    background-position: center;  box-shadow: 0 1px 1.5px 0 rgba(0, 0, 0, 0.12), 0 1px 1px 0 rgba(0, 0, 0, 0.24); -webkit-transform: scale3d(0.7, 0.7, 1);  transform: scale3d(0.7, 0.7, 1);  -webkit-transition: box-shadow 0.15s, -webkit-transform 0.15;  transition: box-shadow 0.15s, transform 0.15s;}
  #back-to-top i { padding-top:20px; font-size:17px; }
  #back-to-top:hover { background:#FF377D;  -webkit-transform: scale3d(1.0, 1.0, 1);  transform: scale3d(1.0, 1.0, 1);}


/* ===================
   16 = Media Queries
   =================== */

   /* For IE Edge (Spartan)  ----------------------- */
   @supports (-ms-accelerator:true) {
    .header{ padding:0 0 1px 0;}
    .sf-menu ul { top: 101%; }
    ::-webkit-input-placeholder {  opacity:  0;}
  }
  /* End For IE Edge (Spartan)  ----------------------- */

  @media only screen and (max-width: 767px) {
    #navigation {display:none;}
    .slicknav_menu {display:block; font-size:13px; font-weight:500; background:#29303C;}
    .slicknav_btn {font-size:16px; background:#8F4099; border-radius:100%; width:34px; height:34px; padding:11px 0 0 8px; }
    .slicknav_nav a {text-transform: uppercase; font-size:13px; font-weight:500;}
    .slicknav_nav a:hover {-webkit-border-radius: 0!important; -moz-border-radius: 0!important; border-radius:0!important; background:#373f4b!important; color: #fff; }
    ul.top, ul.topright {display:table; margin:0 auto; text-align:center;}
    ul.topright {float:none;}
    ul.topright li { margin-right:17px;}
    .logo img {text-align:center; display:table; margin:0 auto; max-width:60%; padding-bottom:15px;}
    #mainimage { height:auto;  position: relative;    overflow: hidden; background: #282f39 url(images/pricingbox-bg-dark.jpg) fixed bottom center;}
    #mainimage h1 { font-size:2em;}
    #home-intro .home-intro-container  { display:none; }
    .pricingbox.headerimg { position:relative; }
    .pricingbox.headerimg .verticalbottom { margin-top:0;}
    .pricingbox.headerimg .pricing-price p {color:#ccc; margin-bottom:0; text-align: center; padding:0; font-size:11px; letter-spacing: .12em;}
    .row.no-gutter [class*='col-']:not(:first-child), .row.no-gutter [class*='col-']:not(:last-child) { padding-left: 15px; padding-right: 15px; }
    .calltoaction {padding:40px 0; background:#fff;}
    .pricingbox {padding:40px 0;}
    .pricingbox p {margin-bottom:70px;padding:0 15px;}
    .pricing-plan {margin-bottom:30px;}
    .domainsearch{ padding:20px 0 10px;}
    .various {text-align: center;}
    .testimonials .owl-theme .owl-controls .owl-page span {width: 30px; height: 8px; margin: 5px;}
    .testimonial-content h5 {font-size:13px;}
    .titleborder{ width:100%;}
    .various .why {padding-right:0; }
    .various i {float:none; }
    .newplanscolumn {margin-bottom:30px;}
    .footer h4 {margin-top:20px;}
    .affiliates-counts p, .affiliates-examples {margin-bottom:25px;}
    .affiliates-features {text-align:center;}
    .affiliates-features i {float:none;}
    #subheader, #subheader.shared,   #subheader.dedicated-servers,  #subheader.about,  #subheader.faq,  #subheader.datacenter, #subheader.blog,   #subheader.contact {padding-top:25px; padding-bottom:25px;}
    #subheader h1 {font-size: 2.18em;}
    #subheader h2 {font-size: 1em;}
    .subheader-text {position: relative; -webkit-transform: translateY(0);  -ms-transform: translateY(0);  transform: translateY(0);}
    .features-tabs .tabs-top-horizontal > .nav-tabs > li { border-right:0; display:block; width:100%; margin-bottom:2px;}
    .features-tabs .tabs-top-horizontal > .nav-tabs .active { border-bottom: 2px solid #424242;}
    .features-tabs .tab-content p.subtitle {padding:0; text-align:center;}
    .features-tabs .tabs-top-horizontal > .nav-tabs .active > a:after { border-width: 0;}
    .fully-managed .block-grid-item {padding:30px 15px; border:0; }
    .security .block-grid-item {text-align: left; padding:10px;}
    .security .security-tab-icon {float:none; width:100%; }
    .security .security-tab-icon i {margin-top:25px; font-size:42px; color:#AEAEAE; text-align:center;}
    .security .security-tab-feature {float:none; width:100%; }
    .backups-restore .backupcolumn { min-height:25px; margin-bottom: 15px;}
    #emails img,  #monitoring img,  #cdn img {margin-bottom:20px;}
    .products-table td, .products-table thead th {text-align: left;}
    .products-table td:first-child, .products-table thead th:first-child {background:#3E65BF; color:#fff!important;}
    .apps-grid .block-grid-item {border:0; margin-bottom:2px; }
    .vps-features-tabs .tab-content {padding:25px 0 0; width:100%; float:none;}
    .vps-features-tabs .tabs-left-vertical > .nav-tabs { width:100%; float:none; }
    .vps-features-tabs .tabs-left-vertical > .nav-tabs .active > a:after { border-width: 0;}
    .tabcircle {float:none; padding-left:0; display:table; margin:0 auto; margin-top:30px; margin-bottom:30px; text-align:center; }
    .tabcircle i { text-shadow:none; }
    .vps-products-table td, .vps-products-table thead th {text-align: left; border-bottom:1px solid #e9e9e9;}
    .vps-products-table td:first-child, .vps-products-table thead th:first-child, .vps-products-table tr.price-comparison td:first-child {background:#FF4081; color:#fff!important;}
    .vps-products-table tr.price-comparison td {font-weight:400; font-size:14px; letter-spacing: 0; background:#fff; color:#424242;}
    .rightside {text-align:left;}
    .features-server p {padding: 0 15px;}
    .moreservers button{ margin-top:70px; }
    .server-products-table td, .server-products-table thead th {text-align: left; border-bottom:1px solid #e9e9e9;}
    .server-products-table td:first-child, .server-products-table thead th:first-child {background:#3F51B5; color:#fff;}
    .server-products-table tr td:first-child .tablesaw-cell-label {display:none;}
    .domaintlds p.subtitle {padding:0 15px;}
    #tld-table td {text-align:left;}
    ul.support-links {margin:30px 0;}
    ul.support-links li {padding:6px 10px; font-size:15px;}
    .support-method {padding:0;}
    .about-team p {padding:0;}
    .datacenter-grid .block-grid-item {margin:1% 0; width:100%;}
    .contactmethod, .whiteframe {margin-bottom:15px;}
  }

  @media only screen and (min-width: 768px) and (max-width: 959px) {
    .logo {margin-top:7px;}
    .sf-menu li a {padding:25px 10px; }
    #home-intro .home-intro-container .introcaption h2 { font-size: 2.6em; }
    #home-intro .home-intro-container .introcaption h4 { font-size: 1.65em;}
    .flex-caption h2 { font-size: 1.7em;}
    .flex-caption h2 span {border:0; }
    .flex-caption h4 {font-size: 1.25em; margin-top: 15px;}
    .flex-caption .mtr-btn {margin-top:15px; margin-bottom:0;}
    .flex-control-nav {bottom:10px;}
    .features-tabs .tab-content { padding:30px 15px; }
    .features-tabs .tabs-top-horizontal > .nav-tabs > li { min-width:110px;}
    .features-tabs .tab-content p.subtitle {padding:0; }
    .fully-managed .block-grid-item {padding:50px 10px;}
    .fully-managed .block-grid-item h5 {ffont-size:16px;}
    .security .block-grid-item {text-align: left; padding:10px;}
    .security .security-tab-icon {float:none; width:100%; }
    .security .security-tab-icon i {margin-top:25px; font-size:42px; color:#AEAEAE; text-align:center;}
    .security .security-tab-feature {float:none; width:100%; }
    .backups-restore .backupcolumn { min-height:570px; }
    #emails img,  #monitoring img,  #cdn img {margin-bottom:20px;}
    .pricingbox.headerimg .verticalbottom {margin-top:130px;}
    .pricing-title { font-size: 15px; }
    .pricing-price { font-size: 25px; }
    .pricingbox.headerimg .progressbars, #mainimage-two .progressbars {padding: 0 0 20px; }
    #mainimage-two h2 {font-size:18px;}
    .pricingbox.headerimg ul li, .pricingbox.shared ul li, .pricingbox.servers ul li {font-size: 15px;}
    .features p {padding:0 10px; font-size:16px;}
    #shared-video .shared-video-container { min-height: 380px;}
    #shared-video .shared-video-container .videocaption .videocaption-content {max-width:480px;  }
    .apps-grid .block-grid-item .odometer {font-size:60px; }
    .vps-features-tabs .tab-content {padding:0 30px; width:80%;}
    .vps-features-tabs .tabs-left-vertical > .nav-tabs { width:20%; }
    .vps-products-table tr.price-comparison td {font-weight:300; font-size:17px;}
    .tabcircle {margin-bottom:15px;}
    .rightside {text-align:left;}
    .features-server p {padding: 0 15px;}
    .rightside,  .server-feature h4,   .server-feature p  {text-align:center;}
    #tld-table thead th {font-weight:500;  font-size:11px;}
    #tld-table th {padding:12px 7px;font-size: 11px;}
    #tld-table td {padding:12px 7px;font-size: 11px;}
    .testimonial-content h5 {font-size:13px;}
    .newplanscolumn {margin-bottom:30px;}
    .footer h4 {font-size: 13px;}
    .contactmethod {min-height:300px;}
    .contactmethod h5 {font-size:14px;}
    .contact-elements h3 {font-size:19px; }
    .whiteframe {padding:8px;}
    .whiteframe p {font-size:15px;}
  }

  @media only screen and (min-width: 960px) and (max-width: 1025px) {
    #home-intro .home-intro-container .introcaption h2 { font-size: 3.1em; }
    #home-intro .home-intro-container .introcaption h4 { font-size: 1.65em;}
    .flex-caption h2 {font-size: 2.1em;}
    .flex-caption h2 span {padding: 14px 0;color:#fff;}
    .flex-caption h4 {font-size: 1.3em; margin-top:35px;}
    .flex-caption .mtr-btn {margin-top:35px;}
    .pricing-title { font-size: 20px; }
    .pricing-price { font-size: 36px; }
    #shared-video .shared-video-container { min-height: 370px;}
    #shared-video .shared-video-container .videocaption .videocaption-content {max-width:520px;  }
    .features-tabs .tabs-top-horizontal > .nav-tabs > li { min-width:140px;}
    .security .security-tab-icon i {font-size:35px;}
    .backups-restore .backupcolumn { min-height:400px; }
    .testimonial-content h5 {font-size:12px;}
    .newplanscolumn {min-height:400px;}
    .newplanscolumn p {margin-bottom:0;}
    .newplanscolumn {margin-bottom:30px;}
    .about-descr p {font-size:16px;}
  .about-descr p.topspacing {padding-top:0;}
  .whiteframe {padding:8px;}
  }

  @media (max-width: 1200px) {
    .timeline { padding: 15px 10px; }
    .timeline:after { left: 26px; }
    .timeline .timeline-row { padding-left: 0; margin-bottom: 16px; }
    .timeline .timeline-row .timeline-time { position: relative; right: auto; top: 0;text-align: left; margin: 0 0 6px 56px; padding:0 0 12px 20px;}
    .timeline .timeline-row .timeline-icon { top: 65px; left: -2px; margin-left: 0; }
    .timeline .timeline-row .timeline-content { margin-left: 56px;  position: relative; }
    .timeline .timeline-row .timeline-content:after { right: auto !important;left: -48px !important; top: 32px; }
    .timeline .timeline-row:nth-child(odd) { padding-right: 0; }
    .timeline .timeline-row:nth-child(odd) .timeline-time { position: relative;right: auto;left: auto; top: 0;text-align: left; margin: 0 0 6px 56px; }
    .timeline .timeline-row:nth-child(odd) .timeline-content { margin-right: 0;margin-left: 55px; }
    .timeline.animated .timeline-row:nth-child(odd) .timeline-content { left: 20px; }
    .timeline.animated .timeline-row.active:nth-child(odd) .timeline-content { left: 0; }
  }

  @media (min-width: 768px) {
    .col-sm-15 { width: 20%;  float: left; }
  }
  @media (min-width: 992px) {
    .col-md-15 { width: 20%;  float: left; }
  }
  @media (min-width: 1200px) {
    .col-lg-15 { width: 20%;  float: left; }
  }
