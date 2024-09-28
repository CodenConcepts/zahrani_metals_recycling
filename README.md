<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zahrani Metals Trading Recycling</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
    <link rel="stylesheet" href="/style.css">
    <style>
        body {
    background-color: white;
    color: #333;
    font-family: 'Poppins', sans-serif;
}














@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');

	body{
		line-height: 1.5;
		font-family: 'Poppins', sans-serif;
		font-weight: 400;
		overflow-x: unset;
	}
	*{
		margin:0;
		box-sizing: border-box;
	}
	:before,:after{
		box-sizing: border-box;
	}
	.container{
		max-width: 1200px;
		margin:auto;
	}
	.row{
		display: flex;
		flex-wrap: wrap;
	}
	.v-center{
		align-items: center;
	}
	ul{
		list-style: none;
		margin:0;
		padding:0;
	}
	a{
		text-decoration: none;
	}
	/* header */
	.new--header{position: sticky;top: 0;background-color: white;z-index: 998;}
	.header{
		display: block;
		width: 100%;
		position: relative;
		z-index: 99;
		padding:15px;
	}
	.header .item-left{
		flex:0 0 17%;
	}
	.header .logo a{
		font-size: 30px;
		color:#000000;
		font-weight: 700;
		text-decoration: none;
	}
	.trans--img {
		max-height: 36px;
	}
	.header .item-center{
		flex:0 0 66%;
	}
	.header .item-right{
		flex:0 0 17%;
		display: flex;
		justify-content: flex-end;
	}
	.fa-angle-down {
		display: inline-block;
		visibility: visible !important;
	}

	.header .item-right a {
		text-decoration: none;
		font-size: 18px;
		color: rgb(23 6 37);
		display: inline-block;
		margin-left: 10px;
		transition: color 0.3s;
	}
	.header .menu > ul > li{
		display: inline-block;
		line-height: 50px;
		margin-left: 25px;
	}
	.header .menu > ul > li > a{
		font-size: 15px;
		font-weight: 500;
		color:#000000;
		position: relative;
		text-transform: capitalize;
		transition: color 0.3s ease;
	}
	.header .menu > ul > li .sub-menu{
		position: absolute;
		z-index: 500;
		background-color:#ffffff;
		box-shadow: -2px 2px 70px -25px rgba(0,0,0,0.3); 
		padding: 20px 30px;
		transition: all 0.5s ease;
		margin-top:25px;
		opacity:0;
		visibility: hidden;
	}

	.header .menu > ul > li .sub-menu > ul > li{
		line-height: 1;
	}
	.header .menu > ul > li .sub-menu > ul > li > a{
		display: inline-block;
		padding: 10px 0;
		font-size: 15px;
		color: #555555;
		transition: color 0.3s ease;
		text-decoration: none;
		text-transform: capitalize;
	}
	.header .menu > ul > li .single-column-menu{
		min-width: 280px;
		max-width: 350px;
	}
	.header .menu > ul > li .sub-menu.mega-menu > .list-item > ul > li{
	line-height: 1;
	display: block; 
	}
	.header .menu > ul > li .sub-menu.mega-menu > .list-item > ul > li > a {
		padding:10px 0;
		display: inline-block;
		font-size: 15px;
		color:#555555;
		transition: color 0.3s ease;
	}
	.header .menu > ul > li .sub-menu.mega-menu{ 
		left: 50%;
		transform: translateX(-50%);	
	}

	.header .menu > ul > li .sub-menu.mega-menu-column-4{
	max-width: 1100px;
	width: 100%; 	
	display: flex;
	flex-wrap: wrap;
	padding:20px 15px;
	}
	.header .menu > ul > li .sub-menu.mega-menu-column-4 > .list-item{
	flex:0 0 25%;
	padding:0 15px;
	}
	.header .menu > ul > li .sub-menu.mega-menu-column-4 > .list-item .title{
		font-size: 16px;
		color:#460d46;
		font-weight: 500;
		line-height: 1;
		padding:10px 0;
	}
	.header .menu > ul > li .sub-menu.mega-menu-column-4 > .list-item.text-center .title{
		text-align: center;
	}
	.header .menu > ul > li .sub-menu.mega-menu-column-4 > .list-item img{
		max-width: 100%;
		width: 100%;
		vertical-align: middle;
		margin-top: 10px;
		height: 300px;
		object-fit: cover;
	}
	.header .menu > ul > li .sub-menu.mega-menu > .list-item > ul > li > a:hover,
	.header .menu > ul > li .sub-menu > ul > li > a:hover,
	.header .item-right a:hover,
	.header .menu > ul > li:hover > a{
		color:#cc36ea;
	}
	/* banner section */
	.banner-section{
	background-image: url('../img/banner.jpg');
	background-size: cover;
	background-position: center;
	height: 700px;
	width: 100%;
	display: block;
	}
	.mobile-menu-head,
	.mobile-menu-trigger{
		display: none;
	}
	







	.language-switcher .btn{padding: 0 1px;}
	.language-switcher .btn img{max-height: 35px;}
	.language-switcher .btn:hover img{padding: 1px;}








.section--hero {
    background: linear-gradient(rgb(0 0 0 / 22%), rgb(0 0 0)), url(/images/yellow-excavator-sits-junkyard-surrounded-by-scrap-metal.png) no-repeat center center;
    height: 70vh;
    background-size: cover;
    color: #fff;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
}
h1#hero-title {
    font-size: calc(31px + 2.5vw);
    font-weight: 800;
    color: #ebe3eb;
}
.bg--green {
    background-color: #4caf50a1;
    padding: 5px 15px;
    font-weight: 750;
    font-size: calc(24px + 3vw);
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 30%;
    width: 100%;
    margin: 0 auto;
    margin-bottom: 25px;
}
.btn-custom {
    background-color: #4caf50;
    color: #ffffff;
	font-weight: 600!important;
}
.btn-custom:hover{color: #ffffff;background-color: #904bc8;}
.btn-purple {
    background-color: #ffffff;
    color: #6a1b9a;
	font-weight: 600!important;
}
.btn-purple:hover{color: #ffffff;background-color: #904bc8;}
.btn {
    font-size: calc(10px + 0.4vw);
    letter-spacing: 1.1px;
    line-height: 1;
    padding: 7px 15px;
	font-family: Poppins, sans-serif;
   
}



.section {
    padding: 70px 0;
}


.section--hero p{font-size:calc(16px + 0.6vw)}











	/* Banner Carousel Styles */
	.section--banner-carousel {
		position: relative;
		width: 100%;
		height: 65vh; /* Ensure full height */
		padding: 0;

	}
	.section--banner-carousel .container-fluid{padding: 0;}
	.section--banner-carousel .carousel-indicators li {
		box-sizing: content-box;
		-ms-flex: 0 1 auto;
		flex: 0 1 auto;
		width: 21px;
		height: 21px;
	
	}
	

	.carousel-item {
		height: 65vh; /* Fixed height for carousel items */
		background-size: cover!important; /* Ensure image covers the item */
		background-repeat: no-repeat!important; /* Prevent repeating */
		background-position: center center; /* Center the background image */
	}

	.carousel-item:nth-child(1) {
		background: linear-gradient(rgb(0 0 0 / 22%), rgb(0 0 0)), url('/images/beard-worker-man-suit-construction-worker-safety-orange-helmet-sunglasses-against-tractor-with-mobile-phone-hand_627829-11387.jpg');
	}

	.carousel-item:nth-child(2) {
		background: linear-gradient(rgb(0 0 0 / 22%), rgb(0 0 0)), url('/images/industrial-worker-salvaging-valuable-materials-from-scrap-metal_620829-2837.jpg');
	}

	.carousel-item:nth-child(3) {
		background: linear-gradient(rgb(0 0 0 / 22%), rgb(0 0 0)), url('/images/crane-grab-scrap_1112-1220.jpg'); /* Replace with unique image path */
	}

	.carousel-item:nth-child(4) {
		background: linear-gradient(rgb(0 0 0 / 22%), rgb(0 0 0)), url('/images/mechanic-welding-part-heavy-construction-machine_997534-45256.jpg'); /* Replace with unique image path */
	}

	.carousel-item:nth-child(5) {
		background: linear-gradient(rgb(0 0 0 / 22%), rgb(0 0 0)), url('/images/yellow-excavator-sits-junkyard-surrounded-by-scrap-metal.png'); /* Replace with unique image path */
	}

	/* Continue with background images for other slides... */

	.carousel-caption {
		position: absolute;
		bottom: 15%;
		left: 0;
		right: 0;
		color: white;
		text-align: center;
		font-family: Arial, sans-serif;
	}

	.carousel-caption h1 {
		font-size: calc(35px + 1.5vw);
		font-weight: 700;
		color: #c7eee6;
	}
	.bg--diff{font-size: calc(40px + 1.5vw);font-weight: 700;background-color: #d332d345;max-width: fit-content;margin: 0 auto;padding: 0 30px;margin-bottom: 15px;}

	.carousel-caption p {
		font-size: 1.25rem;
		color: #f2ffffce;
	}

	.btn-success {
		background-color: #28a745;
		border: none;
		padding: 10px 20px;
		color: white;
		font-size: 1rem;
		text-transform: uppercase;
		font-weight: bold;
		transition: background-color 0.3s ease;
	}

	.btn-success:hover {
		background-color: #218838;
	}

	.carousel-control-next, .carousel-control-prev {
		z-index: 100;
		
	}















	/* Recycling Section Styles */
	.section--recycling {
		background-color: #f8f8f8;
		padding: calc(50px + 2vw) 0;
	}

	.section--recycling h2 {
		text-align: center;
		margin-bottom: 20px;
		color: #333;
		font-weight: 800;
		font-size: calc(28px + 1.8vw);
		
	}

	.section--recycling p {
		text-align: center;
		color: #666;
		font-size: 22px;
		font-family: system-ui;
		line-height: 1.2;
	}

	.recycling-stats {
		display: flex;
		flex-wrap: wrap; /* Wrap items if needed */
		justify-content: space-around; /* Space out the items */
	}

	.stat-item {
		flex: 1 1 calc(33% - 40px); /* Responsive layout for three items per row with spacing */
		margin: 20px; /* Margin for spacing */
		text-align: center; /* Center the content */
		background-color: #fff; /* White background for stat items */
		padding: 20px; /* Padding inside each item */
		border-radius: 10px; /* Rounded corners */
	
	}

	.stat-item:hover h3 {
	cursor: pointer;
	color: #000000;
	transition: cubic-bezier(0.075, 0.82, 0.165, 1);
	}
	.stat-item:hover p {
		cursor: pointer;
		color: #000000;
		transition: cubic-bezier(0.075, 0.82, 0.165, 1);
	}
	

	.stat-item h3 {
		margin: 10px 0 0 0;
		color: #218b7d;
		font-size: calc(40px + 1.5vw);
		font-weight: 700;
	}

	.stat-item p {
		font-size: 20px;
		font-weight: 600;
		font-family: system-ui;
		line-height: 1.2;
	}

	.stat-item .icon {
		width: 70px;
		height: 70px;
		margin-bottom: 10px; 
	}













	.section--sliders {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		overflow: hidden;
	}
	.slider {
		position: relative;
		width: 80%; /* Set the width for the sliders */
		background-color: #f8f8f8;
		border-radius: 8px;
		box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
	
	}

	.slider-inner {
		display: flex;
		white-space: nowrap; /* Prevent line breaks */
		animation: scroll-right 10s linear infinite; 
		padding:calc(20px + 1vw) 0;
	}

	
	.card--slider {
		/* background-color: #eef0e2a8; */
		padding: 11px;
		border-radius: 8px;
		box-shadow: 0 4px 8px rgb(0 0 0 / 30%);
		/* margin-bottom: 20px; */
		border: none;
		/* align-items: center; */
		justify-content: center;
	}
	
	.card {
		min-width: 250px;
		margin: 0 10px;
		padding: 7px;
		border-radius: 5px;
		transition: transform 0.15s ease;
	}

	.card--slider h3 {
		font-family: 'Poppins', sans-serif;
		font-size: calc(10px + 0.7vw);
		font-weight: 700;
		color: #241127;
		white-space: normal;
		font-family: math;
		line-height: 1.0;
	}

	.card--slider p {
		white-space: normal;
		font-size: calc(10px + 0.4vw);
		color: #241127;
		font-family: math;
		line-height: 1.1;
		margin-bottom: 0;
	}


	/* Increase size on hover */
	.card--slider:hover {
		transform: scale(1.1);
		z-index: 50;
		cursor: pointer;
		background-color:transparent;
		
	}






	/* Animation for scrolling right */
	@keyframes scroll-right {
		0% {
			transform: translateX(-15%);
		}
		100% {
			transform: translateX(-50%); /* Adjust for the duplicated cards */
		}
	}

	/* Animation for scrolling left */
	.slider--left .slider-inner {
		animation: scroll-left 25s linear infinite; /* Left scrolling animation */
	}

	@keyframes scroll-left {
		0% {
			transform: translateX(-55%);
		}
		100% {
			transform: translateX(-15%); /* Adjust for the duplicated cards */
		}
	}

	/* Stop animation on hover */
	.slider:hover .slider-inner {
		animation-play-state: paused;
	}

	.content--services h2 {
		font-size: calc(25px + 1.8vw);
		font-weight: 800;
		margin: 0;
	}










	.faq-section {
        margin: 20px 0;
		
    }

    .section-title {
        
        margin-bottom: 20px;
		font-size: calc(25px + 1.8vw);
		font-weight: 800;
    }

    .faq-item {
        border: 1px solid #ccc;
        border-radius: 5px;
        margin-bottom: 10px;
        overflow: hidden;
    }

    .faq-header {
        background: #f8f9fa;
        padding: 15px;
        cursor: pointer;
        display: flex;
        justify-content: space-between;
        align-items: center;
		font-size: 22px;
    }
	.faq-content p{font-size: 22px;color: #0d092c;}

    .faq-content {
        display: none;
        padding: 15px;
        background: #fff;
    }

    .faq-icon {
        font-size: 20px;
        transition: transform 0.3s ease;
    }

    .faq-header.active .faq-icon {
        transform: rotate(90deg); /* Rotate icon on open */
    }




















	footer {
		background-color: #f8f9fa; /* Light background color */
	}

	footer h1 {
		margin-bottom: 20px; /* Space below heading */
		font-size: 3.5em;
		font-weight: 800;
		/* Larger font size for the main title */
	}

	footer h2 {
		margin-bottom: 15px; /* Space below subheadings */
		font-size: 1.5em; /* Medium font size for subheadings */
	}

	footer p, footer ul li {
		font-size: 0.9em; /* Smaller font size for readability */
		color: #555; /* Darker text color */
	}

	footer .btn {
		transition: background-color 0.3s, color 0.3s; /* Transition for button effects */
	}

	footer .btn:hover {
		background-color: #343a40; /* Dark background on hover */
		color: #fff; /* White text on hover */
	}

	/* Hover effect for the buttons */
	.hover-effect {
		position: relative;
	}

	.hover-effect::before {
		content: "";
		position: absolute;
		background: #343a40; /* Dark background */
		height: 100%;
		width: 100%;
		left: 0;
		top: 0;
		z-index: -1; /* Behind the button */
		transform: scaleY(0);
		transition: transform 0.5s ease;
	}

	.hover-effect:hover::before {
		transform: scaleY(1); /* Scale to full height on hover */
	}







































@media(min-width: 992px){
	.header .menu > ul > li.menu-item-has-children:hover .sub-menu{
		margin-top: 0;
		visibility: visible;
		opacity: 1;
	}
}




@media(min-width: 1381px){
    .language-switcher {
        position: fixed;
        top: 1.5rem;
        right: 0.3rem;
        z-index: 999;
    }
}









@media(min-width: 1200px){
    

    
}



@media(max-width: 1380px){
    .language-switcher {
        top: 3.5rem;
        right: 0;
        position: fixed;
        z-index: 999;
    }   
}

/*responsive header*/
@media(max-width: 991px){

	.header .item-center{
		order:3;
		flex:0 0 100%;
	}
	.header .item-left,
	.header .item-right{
		flex:0 0 auto;
	}
	.v-center{
		justify-content: space-between;
	}
	.header .mobile-menu-trigger{
		display: flex;
		height: 30px;
		width: 30px;
		margin-left: 15px;
		cursor: pointer;
		align-items: center;
		justify-content: center;
	}
	.header .mobile-menu-trigger span{
		display: block;
		height: 2px;
		background-color: #333333;
		width: 24px;
		position: relative;
	}
	.header .mobile-menu-trigger span:before,
	.header .mobile-menu-trigger span:after{
		content: '';
		position: absolute;
		left:0;
		width: 100%;
		height: 100%;
		background-color: #333333;
	}
	.header .mobile-menu-trigger span:before{
		top:-6px;
	}
	.header .mobile-menu-trigger span:after{
		top:6px;
	}
	.header .item-right{
		align-items: center;
	}

	.header .menu{
		position: fixed;
		width: 320px;
		background-color:#ffffff;
		left:0;
		top:0;
		height: 100%;
		overflow: hidden;
		transform: translate(-100%);
		transition: all 0.5s ease;
		z-index: 1099;
	}
	.header .menu.active{
	transform: translate(0%);	
	}
	.header .menu > ul > li{
		line-height: 1;
		margin:0;
		display: block;
	}
	.header .menu > ul > li > a{
		line-height: 50px;
		height: 50px;
		padding:0 50px 0 15px;
		display: block;
		border-bottom: 1px solid rgba(0,0,0,0.1);
	}
	.header .menu > ul > li > a i{
		position: absolute;
		height: 50px;
		width: 50px;
		top:0;
		right: 0;
		text-align: center;
		line-height: 50px;
		transform: rotate(-90deg);
	}
	.header .menu .mobile-menu-head{
		display: flex;
		height: 50px;
		border-bottom: 1px solid rgba(0,0,0,0.1);
		justify-content: space-between;
		align-items: center;
		position: relative;
		z-index: 501;
		position: sticky;
		background-color: #ffffff;
		top:0;
	}
	.header .menu .mobile-menu-head .go-back{
		height: 50px;
		width: 50px;
		border-right: 1px solid rgba(0,0,0,0.1);
		cursor: pointer;
		line-height: 50px;
		text-align: center;
		color:#000000;
		font-size: 16px;
		display: none;
	}
	.header .menu .mobile-menu-head.active .go-back{
		display: block;
	}
	.header .menu .mobile-menu-head .current-menu-title{
		font-size: 15px;
		font-weight: 500;
		color:#000000;
	}
	.header .menu .mobile-menu-head .mobile-menu-close{
		height: 50px;
		width: 50px;
		border-left: 1px solid rgba(0,0,0,0.1);
		cursor: pointer;
		line-height: 50px;
		text-align: center;
		color:#000000;	
		font-size: 25px;
	}
	.header .menu .menu-main{
		height: 100%;
		overflow-x: hidden;
		overflow-y: auto;
	}
	.header .menu > ul > li .sub-menu.mega-menu,
	.header .menu > ul > li .sub-menu{
		visibility: visible;
		opacity: 1;
		position: absolute;
		box-shadow: none;
		margin:0;
		padding:15px;
		top:0;
		left:0;
		width: 100%;
		height: 100%;
		padding-top: 65px;
		max-width: none;
		min-width: auto;
		display: none;
		transform: translateX(0%);
		overflow-y: auto;
	}
.header .menu > ul > li .sub-menu.active{
	display: block;
}
@keyframes slideLeft{
	0%{
		opacity:0;
		transform: translateX(100%);
	}
	100%{
		opacity:1;
		transform: translateX(0%);	
	}
}
@keyframes slideRight{
	0%{
		opacity:1;
		transform: translateX(0%);
	}
	100%{
		opacity:0;
		transform: translateX(100%);	
	}
}
	.header .menu > ul > li .sub-menu.mega-menu-column-4 > .list-item img{
		margin-top:0;
	}
	.header .menu > ul > li .sub-menu.mega-menu-column-4 > .list-item.text-center .title{
		margin-bottom: 20px;
	}
	.header .menu > ul > li .sub-menu.mega-menu-column-4 > .list-item.text-center:last-child .title{
		margin-bottom:0px;
	}
	.header .menu > ul > li .sub-menu.mega-menu-column-4 > .list-item{
		flex: 0 0 100%;
		padding: 0px;
	}
	.header .menu > ul > li .sub-menu > ul > li > a,
	.header .menu > ul > li .sub-menu.mega-menu > .list-item > ul > li > a{
		display: block;
	}
	.header .menu > ul > li .sub-menu.mega-menu > .list-item > ul {
		margin-bottom: 15px;
	}
	.menu-overlay{
		position: fixed;
		background-color: rgba(0,0,0,0.5);
		left:0;
		top:0;
		width: 100%;
		height: 100%;
		z-index: 1098;
		visibility: hidden;
		opacity:0;
		transition: all 0.5s ease;
	}
	.menu-overlay.active{
	visibility: visible;
	opacity:1;	
	}
}


@media(max-width: 527px){
    .language-switcher {
		transition: all 0.6s;
		transform: rotate(-90deg);
		top: 6.17rem;
		right: -1.56rem;
	}
	.bg--green{max-width: 100%;}
}
@media(min-width: 528px){
    .language-switcher{transition:all 0.6s}
}
@media(max-width: 991px){
    
}
@media(max-width: 991px){
   
}
@media(max-width: 991px){
    
}
@media(min-device-width: 528px) and (max-device-width: 1199px){
    .bg--green{max-width: 40%;}
}


    </style>
</head>
<body>


    <!-- header start -->
    <header class="new--header">
        <header class="header">
            <div class="container">
                <div class="row v-center">
                    <div class="header-item item-left">
                        <div class="logo">
                            <a href="#">
                                <img alt="Zahrani Metals Trading Recycling" src="/images/logo.png" class="img-fluid trans--img">
                            </a>
                        </div>
                    </div>
                    <div class="header-item item-center">
                        <div class="menu-overlay"></div>
                        <nav class="menu">
                            <div class="mobile-menu-head">
                                <div class="go-back"><i class="fa fa-angle-left"></i></div>
                                <div class="current-menu-title"></div>
                                <div class="mobile-menu-close">&times;</div>
                            </div>
                            <ul class="menu-main">
                                <li>
                                    <a href="#" class="translatable" 
                                    data-en="Home" 
                                    data-ar="الرئيسية">Home</a>
                                </li>
                                <li class="menu-item-has-children">
                                    <a href="#" class="translatable" 
                                    data-en="Services" 
                                    data-ar="الخدمات">Services <i class="fa fa-angle-down"></i>
                                    </a>
                                    <div class="sub-menu mega-menu mega-menu-column-4">
                                        <div class="list-item text-center">
                                            <a href="#">
                                                <img src="/images/man-helmet-is-moving-piece-rail-metal-factory_613910-17160.jpg" alt="Recycling Services" />
                                                <h4 class="title translatable" 
                                                    data-en="Metal Recycling" 
                                                    data-ar="إعادة تدوير المعادن">Metal Recycling</h4>
                                            </a>
                                        </div>
                                        <div class="list-item text-center">
                                            <a href="#">
                                                <img src="/images/assortment-dirty-dumped-objects.jpg" alt="Electronics Recycling" />
                                                <h4 class="title translatable" 
                                                    data-en="Electronics Recycling" 
                                                    data-ar="إعادة تدوير الإلكترونيات">Electronics Recycling</h4>
                                            </a>
                                        </div>
                                        <div class="list-item text-center">
                                            <a href="#">
                                                <img src="/images/upside-down-car-scrap-yard_175117-3435.jpg" alt="Plastic Recycling" />
                                                <h4 class="title translatable" 
                                                    data-en="Plastic Recycling" 
                                                    data-ar="إعادة تدوير البلاستيك">Plastic Recycling</h4>
                                            </a>
                                        </div>
                                        <div class="list-item text-center">
                                            <a href="#">
                                                <img src="/images/industrial-worker-salvaging-valuable-materials-from-scrap-metal_620829-2837.jpg" alt="Wood Recycling" />
                                                <h4 class="title translatable" 
                                                    data-en="Wood Recycling" 
                                                    data-ar="إعادة تدوير الخشب">Wood Recycling</h4>
                                            </a>
                                        </div>
                                    </div>
                                </li>
                                
                                <li class="menu-item-has-children">
                                    <a href="#" class="translatable" 
                                    data-en="Shop" 
                                    data-ar="تسوق">Shop <i class="fa fa-angle-down"></i></a>
                                    <div class="sub-menu mega-menu mega-menu-column-4">
                                        <div class="list-item">
                                            <h4 class="title translatable" 
                                                data-en="Recycling Equipment" 
                                                data-ar="معدات إعادة التدوير">Recycling Equipment</h4>
                                            <ul>
                                                <li><a href="#" class="translatable" data-en="Shredders" data-ar="مكابس">Shredders</a></li>
                                                <li><a href="#" class="translatable" data-en="Compactors" data-ar="ضغطات">Compactors</a></li>
                                                <li><a href="#" class="translatable" data-en="Balers" data-ar="بالير">Balers</a></li>
                                                <li><a href="#" class="translatable" data-en="Sorting Systems" data-ar="أنظمة الفرز">Sorting Systems</a></li>
                                            </ul>
                                        </div>
                                        <div class="list-item">
                                            <h4 class="title translatable" 
                                                data-en="Eco-Friendly Products" 
                                                data-ar="منتجات صديقة للبيئة">Eco-Friendly Products</h4>
                                            <ul>
                                                <li><a href="#" class="translatable" data-en="Reusable Bags" data-ar="أكياس قابلة للاستخدام">Reusable Bags</a></li>
                                                <li><a href="#" class="translatable" data-en="Biodegradable Containers" data-ar="حاويات قابلة للتحلل">Biodegradable Containers</a></li>
                                            </ul>
                                        </div>
                                    </div>
                                </li>
                                <li class="menu-item-has-children">
                                    <a href="#" class="translatable" 
                                    data-en="Blog" 
                                    data-ar="مدونة">Blog <i class="fas fa-angle-down"></i></a>
                                    <div class="sub-menu single-column-menu">
                                        <ul>
                                            <li><a href="#" class="translatable" 
                                                data-en="Recycling Tips" 
                                                data-ar="نصائح لإعادة التدوير">Recycling Tips</a></li>
                                            <li><a href="#" class="translatable" 
                                                data-en="Industry News" 
                                                data-ar="أخبار الصناعة">Industry News</a></li>
                                        </ul>
                                    </div>
                                </li>
                                <li class="menu-item-has-children">
                                    <a href="#" class="translatable" 
                                    data-en="Contact" 
                                    data-ar="اتصل بنا">Contact <i class="fas fa-angle-down"></i></a>
                                    <div class="sub-menu single-column-menu">
                                        <ul>
                                            <li><a href="#" class="translatable" 
                                                data-en="Get in Touch" 
                                                data-ar="تواصل معنا">Get in Touch</a></li>
                                            <li><a href="#" class="translatable" 
                                                data-en="Request a Quote" 
                                                data-ar="طلب عرض أسعار">Request a Quote</a></li>
                                        </ul>
                                    </div>
                                </li>
                            </ul>
                        </nav>
                    </div>
                    <div class="header-item item-right">
                        <a href="#"><i class="fas fa-search"></i></a>
                        <a href="#"><i class="far fa-heart"></i></a>
                        <a href="#"><i class="fas fa-shopping-cart"></i></a>
                        
                        <div class="mobile-menu-trigger">
                            <span></span>
                        </div>
                    </div>
                </div>
            </div>
        </header>
    </header>
    <!-- header end -->

    <div class="language-switcher">
        <button class="btn" onclick="changeLanguage('en')">
            <img class="" src="/images/united-states_4855884.png">
        </button>
        <button class="btn" onclick="changeLanguage('ar')">
            <img class="" src="/images/flag_13980429.png">
        </button>
    </div>

    <!-- Hero Section -->
    <section class="section section--hero">
        <div class="container-fluid text-center">
            <h1 id="hero-title" class="translatable" 
                data-en="Zahrani Metals Trading" 
                data-ar="الزهراني لتجارة المعادن">
                Zahrani Metals Trading 
            </h1>
            <!-- H2 for Recycling translated into Arabic -->
            <h2 id="recycling-text" class="bg--green translatable" 
                data-en="Recycling" 
                data-ar="إعادة التدوير">
                Recycling
            </h2>
            <p id="hero-desc" class="translatable" 
                data-en="Sustainable solutions for metal scrap recycling" 
                data-ar="حلول مستدامة لإعادة تدوير الخردة المعدنية">
                Sustainable solutions for metal scrap recycling
            </p>
            <a href="#products" id="hero-btn1" class="btn btn-custom btn-lg mr-2 translatable" 
                data-en="Get Started" 
                data-ar="ابدأ الآن">Get Started</a>
            <a href="#services" id="hero-btn2" class="btn btn-purple btn-lg translatable" 
                data-en="View Services" 
                data-ar="عرض الخدمات">View Services</a>
        </div>
    </section>
    <!-- Hero Section End -->

    <!-- Slider Section -->
    <section class="section--sliders">
        <div class="slider slider--right">
            <div class="slider-inner">
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Ferrous Metals" 
                        data-ar="المعادن الحديدية">
                        Ferrous Metals
                    </h3>
                    <p class="translatable" 
                        data-en="Recycling of ferrous metals like iron and steel is crucial for reducing environmental impact." 
                        data-ar="إعادة تدوير المعادن الحديدية مثل الحديد والصلب أمر بالغ الأهمية لتقليل التأثير البيئي.">
                        Recycling of ferrous metals like iron and steel is crucial for reducing environmental impact.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Non-Ferrous Metals" 
                        data-ar="المعادن غير الحديدية">
                        Non-Ferrous Metals
                    </h3>
                    <p class="translatable" 
                        data-en="We specialize in the recycling of aluminum, copper, and brass, which are valuable for their properties." 
                        data-ar="نحن متخصصون في إعادة تدوير الألومنيوم والنحاس والنحاس الأصفر، وهي مواد قيمة لخصائصها.">
                        We specialize in the recycling of aluminum, copper, and brass, which are valuable for their properties.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Scrap Collection Services" 
                        data-ar="خدمات جمع الخردة">
                        Scrap Collection Services
                    </h3>
                    <p class="translatable" 
                        data-en="Our efficient collection services ensure that your metal waste is disposed of responsibly." 
                        data-ar="تضمن خدمات الجمع الفعالة لدينا التخلص المسؤول من نفايات المعادن الخاصة بك.">
                        Our efficient collection services ensure that your metal waste is disposed of responsibly.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Metal Trading" 
                        data-ar="تجارة المعادن">
                        Metal Trading
                    </h3>
                    <p class="translatable" 
                        data-en="We offer competitive prices for both buying and selling ferrous and non-ferrous metals." 
                        data-ar="نحن نقدم أسعارًا تنافسية لكل من شراء وبيع المعادن الحديدية وغير الحديدية.">
                        We offer competitive prices for both buying and selling ferrous and non-ferrous metals.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Environmental Compliance" 
                        data-ar="الامتثال البيئي">
                        Environmental Compliance
                    </h3>
                    <p class="translatable" 
                        data-en="Committed to adhering to environmental regulations, we ensure safe recycling practices." 
                        data-ar="ملتزمون بالامتثال للوائح البيئية، نضمن ممارسات إعادة تدوير آمنة.">
                        Committed to adhering to environmental regulations, we ensure safe recycling practices.
                    </p>
                </div>
                <!-- Duplicate Cards for Infinite Scroll Effect -->
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Ferrous Metals" 
                        data-ar="المعادن الحديدية">
                        Ferrous Metals
                    </h3>
                    <p class="translatable" 
                        data-en="Recycling of ferrous metals like iron and steel is crucial for reducing environmental impact." 
                        data-ar="إعادة تدوير المعادن الحديدية مثل الحديد والصلب أمر بالغ الأهمية لتقليل التأثير البيئي.">
                        Recycling of ferrous metals like iron and steel is crucial for reducing environmental impact.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Non-Ferrous Metals" 
                        data-ar="المعادن غير الحديدية">
                        Non-Ferrous Metals
                    </h3>
                    <p class="translatable" 
                        data-en="We specialize in the recycling of aluminum, copper, and brass, which are valuable for their properties." 
                        data-ar="نحن متخصصون في إعادة تدوير الألومنيوم والنحاس والنحاس الأصفر، وهي مواد قيمة لخصائصها.">
                        We specialize in the recycling of aluminum, copper, and brass, which are valuable for their properties.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Scrap Collection Services" 
                        data-ar="خدمات جمع الخردة">
                        Scrap Collection Services
                    </h3>
                    <p class="translatable" 
                        data-en="Our efficient collection services ensure that your metal waste is disposed of responsibly." 
                        data-ar="تضمن خدمات الجمع الفعالة لدينا التخلص المسؤول من نفايات المعادن الخاصة بك.">
                        Our efficient collection services ensure that your metal waste is disposed of responsibly.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Metal Trading" 
                        data-ar="تجارة المعادن">
                        Metal Trading
                    </h3>
                    <p class="translatable" 
                        data-en="We offer competitive prices for both buying and selling ferrous and non-ferrous metals." 
                        data-ar="نحن نقدم أسعارًا تنافسية لكل من شراء وبيع المعادن الحديدية وغير الحديدية.">
                        We offer competitive prices for both buying and selling ferrous and non-ferrous metals.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Environmental Compliance" 
                        data-ar="الامتثال البيئي">
                        Environmental Compliance
                    </h3>
                    <p class="translatable" 
                        data-en="Committed to adhering to environmental regulations, we ensure safe recycling practices." 
                        data-ar="ملتزمون بالامتثال للوائح البيئية، نضمن ممارسات إعادة تدوير آمنة.">
                        Committed to adhering to environmental regulations, we ensure safe recycling practices.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Metal Recovery Solutions" 
                        data-ar="حلول استعادة المعادن">
                        Metal Recovery Solutions
                    </h3>
                    <p class="translatable" 
                        data-en="Innovative techniques for recovering valuable metals from electronic waste." 
                        data-ar="تقنيات مبتكرة لاستعادة المعادن القيمة من النفايات الإلكترونية.">
                        Innovative techniques for recovering valuable metals from electronic waste.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Sustainability Practices" 
                        data-ar="ممارسات الاستدامة">
                        Sustainability Practices
                    </h3>
                    <p class="translatable" 
                        data-en="Our sustainability initiatives aim to minimize waste and maximize resource recovery." 
                        data-ar="تهدف مبادرات الاستدامة لدينا إلى تقليل النفايات وزيادة استرداد الموارد.">
                        Our sustainability initiatives aim to minimize waste and maximize resource recovery.
                    </p>
                </div>
            </div>
        </div>
        <div class="content--services">
            <h2 class="translatable" 
                data-en="Our Top Notch Services" 
                data-ar="خدماتنا الممتازة">
                Our Top Notch Services
            </h2>

        </div>
        <div class="slider slider--left">
            <div class="slider-inner">
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="E-Waste Recycling" 
                        data-ar="إعادة تدوير النفايات الإلكترونية">
                        E-Waste Recycling
                    </h3>
                    <p class="translatable" 
                        data-en="We provide comprehensive solutions for recycling electronic waste, extracting precious metals and reducing landfill impact." 
                        data-ar="نقدم حلولًا شاملة لإعادة تدوير النفايات الإلكترونية، واستخراج المعادن الثمينة وتقليل تأثير النفايات في مدافن النفايات.">
                        We provide comprehensive solutions for recycling electronic waste, extracting precious metals and reducing landfill impact.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Environmental Impact" 
                        data-ar="التأثير البيئي">
                        Environmental Impact
                    </h3>
                    <p class="translatable" 
                        data-en="Our processes are designed to minimize environmental impact while maximizing metal recovery." 
                        data-ar="تم تصميم عملياتنا لتقليل التأثير البيئي مع زيادة استرداد المعادن.">
                        Our processes are designed to minimize environmental impact while maximizing metal recovery.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Customized Recycling Programs" 
                        data-ar="برامج إعادة التدوير المخصصة">
                        Customized Recycling Programs
                    </h3>
                    <p class="translatable" 
                        data-en="We tailor recycling programs to meet the specific needs of businesses and communities." 
                        data-ar="نقوم بتخصيص برامج إعادة التدوير لتلبية الاحتياجات الخاصة للشركات والمجتمعات.">
                        We tailor recycling programs to meet the specific needs of businesses and communities.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Community Outreach" 
                        data-ar="التواصل المجتمعي">
                        Community Outreach
                    </h3>
                    <p class="translatable" 
                        data-en="Our outreach programs educate the community about the importance of recycling metals." 
                        data-ar="تعمل برامجنا على توعية المجتمع بأهمية إعادة تدوير المعادن.">
                        Our outreach programs educate the community about the importance of recycling metals.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Responsible Disposal" 
                        data-ar="التخلص المسؤول">
                        Responsible Disposal
                    </h3>
                    <p class="translatable" 
                        data-en="We ensure that all collected materials are disposed of responsibly and in accordance with regulations." 
                        data-ar="نضمن أن يتم التخلص من جميع المواد المجمعة بشكل مسؤول ووفقًا للوائح.">
                        We ensure that all collected materials are disposed of responsibly and in accordance with regulations.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Innovative Technologies" 
                        data-ar="تقنيات مبتكرة">
                        Innovative Technologies
                    </h3>
                    <p class="translatable" 
                        data-en="Utilizing cutting-edge technologies to improve metal recovery rates and efficiency." 
                        data-ar="نستخدم تقنيات متطورة لتحسين معدلات استرداد المعادن والكفاءة.">
                        Utilizing cutting-edge technologies to improve metal recovery rates and efficiency.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="E-Waste Recycling" 
                        data-ar="إعادة تدوير النفايات الإلكترونية">
                        E-Waste Recycling
                    </h3>
                    <p class="translatable" 
                        data-en="We provide comprehensive solutions for recycling electronic waste, extracting precious metals and reducing landfill impact." 
                        data-ar="نقدم حلولًا شاملة لإعادة تدوير النفايات الإلكترونية، واستخراج المعادن الثمينة وتقليل تأثير النفايات في مدافن النفايات.">
                        We provide comprehensive solutions for recycling electronic waste, extracting precious metals and reducing landfill impact.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Environmental Impact" 
                        data-ar="التأثير البيئي">
                        Environmental Impact
                    </h3>
                    <p class="translatable" 
                        data-en="Our processes are designed to minimize environmental impact while maximizing metal recovery." 
                        data-ar="تم تصميم عملياتنا لتقليل التأثير البيئي مع زيادة استرداد المعادن.">
                        Our processes are designed to minimize environmental impact while maximizing metal recovery.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Customized Recycling Programs" 
                        data-ar="برامج إعادة التدوير المخصصة">
                        Customized Recycling Programs
                    </h3>
                    <p class="translatable" 
                        data-en="We tailor recycling programs to meet the specific needs of businesses and communities." 
                        data-ar="نقوم بتخصيص برامج إعادة التدوير لتلبية الاحتياجات الخاصة للشركات والمجتمعات.">
                        We tailor recycling programs to meet the specific needs of businesses and communities.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Community Outreach" 
                        data-ar="التواصل المجتمعي">
                        Community Outreach
                    </h3>
                    <p class="translatable" 
                        data-en="Our outreach programs educate the community about the importance of recycling metals." 
                        data-ar="تعمل برامجنا على توعية المجتمع بأهمية إعادة تدوير المعادن.">
                        Our outreach programs educate the community about the importance of recycling metals.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Responsible Disposal" 
                        data-ar="التخلص المسؤول">
                        Responsible Disposal
                    </h3>
                    <p class="translatable" 
                        data-en="We ensure that all collected materials are disposed of responsibly and in accordance with regulations." 
                        data-ar="نضمن أن يتم التخلص من جميع المواد المجمعة بشكل مسؤول ووفقًا للوائح.">
                        We ensure that all collected materials are disposed of responsibly and in accordance with regulations.
                    </p>
                </div>
                <div class="card card--slider">
                    <h3 class="translatable" 
                        data-en="Innovative Technologies" 
                        data-ar="تقنيات مبتكرة">
                        Innovative Technologies
                    </h3>
                    <p class="translatable" 
                        data-en="Utilizing cutting-edge technologies to improve metal recovery rates and efficiency." 
                        data-ar="نستخدم تقنيات متطورة لتحسين معدلات استرداد المعادن والكفاءة.">
                        Utilizing cutting-edge technologies to improve metal recovery rates and efficiency.
                    </p>
                </div>
            </div>
        </div>
        
    </section>
    <!-- Slider Section End -->

    <!-- Banner Carousel Section -->
    <section class="section section--banner-carousel">
        <div class="container-fluid">
            <div id="carouselIndicators" class="carousel slide" data-ride="carousel" data-interval="5000">
                <!-- Indicators -->
                <ol class="carousel-indicators">
                    <li data-target="#carouselIndicators" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselIndicators" data-slide-to="1"></li>
                    <li data-target="#carouselIndicators" data-slide-to="2"></li>
                    <li data-target="#carouselIndicators" data-slide-to="3"></li>
                    <li data-target="#carouselIndicators" data-slide-to="4"></li>
                </ol>

                <!-- Carousel Items -->
                <div class="carousel-inner">
                    <!-- Slide 1 -->
                    <div class="carousel-item active" data-ar="شركاؤك الموثوقون" data-en="Your Trusted Partners">
                        <div class="carousel-caption d-md-block">
                            <h1 id="hero-title" class="translatable" data-en="Zahrani Metals Trading" data-ar="الزهراني لتجارة المعادن">Zahrani Metals Trading</h1>
                            <h2 id="recycling-text" class="bg--green translatable" data-en="Recycling" data-ar="إعادة التدوير">Recycling</h2>
                            <p id="hero-desc" class="translatable" data-en="Sustainable solutions for metal scrap recycling" data-ar="حلول مستدامة لإعادة تدوير الخردة المعدنية">Sustainable solutions for metal scrap recycling</p>
                            <a href="#products" id="hero-btn1" class="btn btn-custom btn-lg mr-2 translatable" data-en="Get Started" data-ar="ابدأ الآن">Get Started</a>
                            <a href="#services" id="hero-btn2" class="btn btn-purple btn-lg translatable" data-en="View Services" data-ar="عرض الخدمات">View Services</a>
                        </div>
                    </div>
                    <!-- Slide 2 -->
                    <div class="carousel-item" data-ar="إعادة التدوير الفعالة" data-en="Efficient Recycling">
                        <div class="carousel-caption d-md-block">
                            <h1 class="translatable" data-en="Efficient Recycling" data-ar="إعادة التدوير الفعالة">Efficient Recycling</h1>
                            <h2 class="bg--diff translatable" data-en="Maximizing Resource Recovery" data-ar="زيادة استرداد الموارد">Maximizing Resource Recovery</h2>
                            <p class="translatable" data-en="Our state-of-the-art recycling process guarantees efficiency and sustainability." data-ar="عمليات إعادة التدوير لدينا تضمن الكفاءة والاستدامة">Our state-of-the-art recycling process guarantees efficiency and sustainability.</p>
                            <a href="#" class="btn btn-success translatable" data-en="Learn More" data-ar="تعرف على المزيد">Learn More</a>
                        </div>
                    </div>
                    <!-- Slide 3 -->
                    <div class="carousel-item" data-ar="حلول مبتكرة" data-en="Innovative Solutions">
                        <div class="carousel-caption d-md-block">
                            <h1 class="translatable" data-en="Innovative Solutions" data-ar="حلول مبتكرة">Innovative Solutions</h1>
                            <h2 class="bg--diff translatable" data-en="Leading the Future of Recycling" data-ar="قيادة مستقبل إعادة التدوير">Leading the Future of Recycling</h2>
                            <p class="translatable" data-en="Cutting-edge technology for sustainable metal recycling." data-ar="تقنيات مبتكرة لإعادة تدوير المعادن بشكل مستدام">Cutting-edge technology for sustainable metal recycling.</p>
                            <a href="#" class="btn btn-success translatable" data-en="Discover More" data-ar="اكتشف المزيد">Discover More</a>
                        </div>
                    </div>
                    <!-- Slide 4 -->
                    <div class="carousel-item" data-ar="قيادة صناعة الخردة" data-en="Leading the Scrap Industry">
                        <div class="carousel-caption d-md-block">
                            <h1 class="translatable" data-en="Leading the Scrap Industry" data-ar="قيادة صناعة الخردة">Leading the Scrap Industry</h1>
                            <h2 class="bg--diff translatable" data-en="Pioneering Sustainable Practices" data-ar="ريادة الممارسات المستدامة">Pioneering Sustainable Practices</h2>
                            <p class="translatable" data-en="Global leader in metal scrap recycling and sustainability." data-ar="الريادة العالمية في إعادة تدوير الخردة المعدنية والاستدامة">Global leader in metal scrap recycling and sustainability.</p>
                            <a href="#" class="btn btn-success translatable" data-en="Join Us" data-ar="انضم إلينا">Join Us</a>
                        </div>
                    </div>
                    <!-- Slide 5 -->
                    <div class="carousel-item" data-ar="أفضل حلول للخردة" data-en="Best Scrap Solutions">
                        <div class="carousel-caption d-md-block">
                            <h1 class="translatable" data-en="Best Scrap Solutions" data-ar="أفضل حلول للخردة">Best Scrap Solutions</h1>
                            <h2 class="bg--diff translatable" data-en="Comprehensive Recycling Strategies" data-ar="استراتيجيات إعادة تدوير شاملة">Comprehensive Recycling Strategies</h2>
                            <p class="translatable" data-en="Providing comprehensive scrap recycling solutions." data-ar="توفير حلول شاملة لإعادة تدوير الخردة.">Providing comprehensive scrap recycling solutions.</p>
                            <a href="#" class="btn btn-success translatable" data-en="Contact Us" data-ar="اتصل بنا">Contact Us</a>
                        </div>
                    </div>
                </div>

                <!-- Controls -->
                <a class="carousel-control-prev" href="#carouselIndicators" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselIndicators" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>
        </div>
    </section>
    <!-- Banner Carousel Section End -->

    <!-- Trending Recycling Section -->
    <section class="section--recycling">
    <div class="container">
    <h2 class="trending-heading translatable" 
        data-en="Sustainability in Action: Metal Recycling Revolution" 
        data-ar="الاستدامة في العمل: ثورة إعادة تدوير المعادن">
        Sustainability in Action: Metal Recycling Revolution
    </h2>
    <p class="translatable" 
        data-en="Leading the charge in metal recycling, Zahrani Metals Trading is committed to reducing waste and promoting environmental sustainability through efficient recycling solutions." 
        data-ar="تقود شركة الزهراني لتجارة المعادن زمام الأمور في إعادة تدوير المعادن، ملتزمة بتقليل النفايات وتعزيز الاستدامة البيئية من خلال حلول إعادة تدوير فعالة.">
        Leading the charge in metal recycling, Zahrani Metals Trading is committed to reducing waste and promoting environmental sustainability through efficient recycling solutions.
    </p>
    <div class="recycling-stats">
        <div class="stat-item">
            <img src="https://cdn-icons-png.flaticon.com/512/1377/1377460.png" alt="Years of Experience Icon" class="icon" />
            <h3 class="count" data-count="15">0</h3>
            <p class="translatable" 
                data-en="Years of Experience" 
                data-ar="سنوات الخبرة">Years of Experience</p>
        </div>
        <div class="stat-item">
            <img src="https://cdn-icons-png.flaticon.com/512/107/107624.png" alt="Countries Icon" class="icon" />
            <h3 class="count" data-count="20">0</h3>
            <p class="translatable" 
                data-en="Countries Served" 
                data-ar="الدول المخدومة">Countries Served</p>
        </div>
        <div class="stat-item">
            <img src="https://cdn-icons-png.flaticon.com/512/1144/1144760.png" alt="Satisfied Customers Icon" class="icon" />
            <h3 class="count" data-count="1500">0</h3>
            <p class="translatable" 
                data-en="Satisfied Customers" 
                data-ar="العملاء الراضون">Satisfied Customers</p>
        </div>
        <div class="stat-item">
            <img src="https://cdn-icons-png.flaticon.com/512/1695/1695452.png" alt="Metric Tonnes Volume Annually Icon" class="icon" />
            <h3 class="count" data-count="12000">0</h3>
            <p class="translatable" 
                data-en="Metric Tonnes Recycled Annually" 
                data-ar="الأطنان المترية المعاد تدويرها سنويًا">Metric Tonnes Recycled Annually</p>
        </div>
        <div class="stat-item">
            <img src="https://cdn-icons-png.flaticon.com/512/732/732146.png" alt="Revenue Icon" class="icon" />
            <h3 class="count" data-count="500">0</h3>
            <p class="translatable" 
                data-en="Million USD Revenue" 
                data-ar="مليون دولار أمريكي الإيرادات">Million USD Revenue</p>
        </div>
        <div class="stat-item">
            <img src="https://cdn-icons-png.flaticon.com/512/2698/2698532.png" alt="CO2 Emission Saving Icon" class="icon" />
            <h3 class="count" data-count="20000">0</h3>
            <p class="translatable" 
                data-en="Metric Tonnes CO2 Emission Savings (2022)" 
                data-ar="الأطنان المترية لانبعاثات ثاني أكسيد الكربون التي تم توفيرها (2022)">Metric Tonnes CO2 Emission Savings (2022)</p>
        </div>
    </div>
    </div>
    </section>
    <!-- Trending Recycling Section End -->

<!-- FAQ Section -->
<section class="faq-section">
    <div class="container">
        <h2 class="section-title translatable" data-en="FAQ" data-ar="الأسئلة الشائعة">FAQ</h2>
        <div class="faq-item">
            <div class="faq-header" onclick="toggleFAQ(this)">
                <span class="translatable" data-en="What materials can be recycled?" data-ar="ما المواد التي يمكن إعادة تدويرها؟">What materials can be recycled?</span>
                <span class="faq-icon">&#9654;</span> <!-- Arrow right icon -->
            </div>
            <div class="faq-content">
                <p class="translatable" data-en="We recycle a wide range of metals including aluminum, copper, and steel." data-ar="نقوم بإعادة تدوير مجموعة واسعة من المعادن بما في ذلك الألمنيوم والنحاس والصلب.">
                    We recycle a wide range of metals including aluminum, copper, and steel.
                </p>
            </div>
        </div>

        <div class="faq-item">
            <div class="faq-header" onclick="toggleFAQ(this)">
                <span class="translatable" data-en="How does the recycling process work?" data-ar="كيف تعمل عملية إعادة التدوير؟">How does the recycling process work?</span>
                <span class="faq-icon">&#9654;</span> <!-- Arrow right icon -->
            </div>
            <div class="faq-content">
                <p class="translatable" data-en="Our recycling process involves collection, sorting, shredding, and melting metals." data-ar="تشمل عملية إعادة التدوير لدينا الجمع والفرز والتمزيق وصهر المعادن.">
                    Our recycling process involves collection, sorting, shredding, and melting metals.
                </p>
            </div>
        </div>

        <div class="faq-item">
            <div class="faq-header" onclick="toggleFAQ(this)">
                <span class="translatable" data-en="Where can I drop off recyclable materials?" data-ar="أين يمكنني تسليم المواد القابلة لإعادة التدوير؟">Where can I drop off recyclable materials?</span>
                <span class="faq-icon">&#9654;</span> <!-- Arrow right icon -->
            </div>
            <div class="faq-content">
                <p class="translatable" data-en="You can drop off recyclable materials at our designated recycling centers." data-ar="يمكنك تسليم المواد القابلة لإعادة التدوير في مراكز إعادة التدوير المعينة لدينا.">
                    You can drop off recyclable materials at our designated recycling centers.
                </p>
            </div>
        </div>

        <div class="faq-item">
            <div class="faq-header" onclick="toggleFAQ(this)">
                <span class="translatable" data-en="Do you offer pickup services?" data-ar="هل تقدمون خدمات النقل؟">Do you offer pickup services?</span>
                <span class="faq-icon">&#9654;</span> <!-- Arrow right icon -->
            </div>
            <div class="faq-content">
                <p class="translatable" data-en="Yes, we offer pickup services for large quantities of recyclable materials." data-ar="نعم، نقدم خدمات النقل لكميات كبيرة من المواد القابلة لإعادة التدوير.">
                    Yes, we offer pickup services for large quantities of recyclable materials.
                </p>
            </div>
        </div>

        <div class="faq-item">
            <div class="faq-header" onclick="toggleFAQ(this)">
                <span class="translatable" data-en="What are the benefits of recycling?" data-ar="ما هي فوائد إعادة التدوير؟">What are the benefits of recycling?</span>
                <span class="faq-icon">&#9654;</span> <!-- Arrow right icon -->
            </div>
            <div class="faq-content">
                <p class="translatable" data-en="Recycling helps conserve natural resources and reduces pollution." data-ar="تساعد إعادة التدوير في الحفاظ على الموارد الطبيعية وتقليل التلوث.">
                    Recycling helps conserve natural resources and reduces pollution.
                </p>
            </div>
        </div>

        <div class="faq-item">
            <div class="faq-header" onclick="toggleFAQ(this)">
                <span class="translatable" data-en="How can I learn more about recycling?" data-ar="كيف يمكنني معرفة المزيد عن إعادة التدوير؟">How can I learn more about recycling?</span>
                <span class="faq-icon">&#9654;</span> <!-- Arrow right icon -->
            </div>
            <div class="faq-content">
                <p class="translatable" data-en="Visit our website or contact us for more information on recycling programs." data-ar="قم بزيارة موقعنا على الويب أو اتصل بنا لمزيد من المعلومات حول برامج إعادة التدوير.">
                    Visit our website or contact us for more information on recycling programs.
                </p>
            </div>
        </div>

        <div class="faq-item">
            <div class="faq-header" onclick="toggleFAQ(this)">
                <span class="translatable" data-en="Is recycling mandatory?" data-ar="هل إعادة التدوير إلزامية؟">Is recycling mandatory?</span>
                <span class="faq-icon">&#9654;</span> <!-- Arrow right icon -->
            </div>
            <div class="faq-content">
                <p class="translatable" data-en="It varies by location; some places have mandatory recycling laws." data-ar="يختلف ذلك حسب الموقع؛ بعض الأماكن لديها قوانين إلزامية لإعادة التدوير.">
                    It varies by location; some places have mandatory recycling laws.
                </p>
            </div>
        </div>

    </div>
</section>
<!-- FAQ Section End -->


    <!-- Footer Section -->
    <footer class="bg-light text-dark d-flex flex-column justify-content-center align-items-center" style="height: 75vh;">
        <div class="container text-center">
            <h1 class="translatable" 
                data-en="Welcome to Zahrani Metals Trading" 
                data-ar="مرحبًا بكم في الزهراني لتجارة المعادن">
                Welcome to Zahrani Metals Trading
            </h1>
            <p class="translatable" 
                data-en="Your trusted partner in metal trading and recycling." 
                data-ar="شريكك الموثوق في تجارة المعادن وإعادة التدوير.">
                Your trusted partner in metal trading and recycling.
            </p>
            
            <div class="row mt-5">
                <div class="col-md-4">
                    <h2 class="translatable" 
                        data-en="About Us" 
                        data-ar="معلومات عنا">
                        About Us
                    </h2>
                    <p class="translatable" 
                        data-en="Zahrani Metals Trading is committed to delivering the highest quality services in the metal trading sector." 
                        data-ar="تلتزم الزهراني لتجارة المعادن بتقديم أعلى جودة من الخدمات في قطاع تجارة المعادن.">
                        Zahrani Metals Trading is committed to delivering the highest quality services in the metal trading sector.
                    </p>
                </div>
                <div class="col-md-4">
                    <h2 class="translatable" 
                        data-en="Services" 
                        data-ar="الخدمات">
                        Services
                    </h2>
                    <ul class="list-unstyled">
                        <li class="translatable" 
                            data-en="Metal Recovery" 
                            data-ar="استعادة المعادن">
                            Metal Recovery
                        </li>
                        <li class="translatable" 
                            data-en="Scrap Collection" 
                            data-ar="جمع الخردة">
                            Scrap Collection
                        </li>
                        <li class="translatable" 
                            data-en="Metal Trading" 
                            data-ar="تجارة المعادن">
                            Metal Trading
                        </li>
                        <li class="translatable" 
                            data-en="Consultation Services" 
                            data-ar="خدمات الاستشارة">
                            Consultation Services
                        </li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h2 class="translatable" 
                        data-en="Contact Us" 
                        data-ar="اتصل بنا">
                        Contact Us
                    </h2>
                    <p class="translatable" 
                        data-en="Email: info@zahranimetals.com" 
                        data-ar="البريد الإلكتروني: info@zahranimetals.com">
                        Email: info@zahranimetals.com
                    </p>
                    <p class="translatable" 
                        data-en="Phone: +123 456 7890" 
                        data-ar="الهاتف: +123 456 7890">
                        Phone: +123 456 7890
                    </p>
                </div>
            </div>
    
            <div class="mt-5">
                <h2 class="translatable" 
                    data-en="Follow Us" 
                    data-ar="تابعنا">
                    Follow Us
                </h2>
                <a href="#" class="btn btn-outline-dark m-1 hover-effect">Facebook</a>
                <a href="#" class="btn btn-outline-dark m-1 hover-effect">Twitter</a>
                <a href="#" class="btn btn-outline-dark m-1 hover-effect">Instagram</a>
            </div>
            <div class="sust--img mt-4">
                <img class="img-fluid" src="/images/sustanaible--logo.jpg">
            </div>
        </div>
    </footer>
     <!-- Footer Section End -->   

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>   
<script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>

    <!-- JavaScript for Language Switching -->
    <script>
        function changeLanguage(lang) {
        document.querySelectorAll('.translatable').forEach(element => {
            // Preserve the icons and only change the text part
            const icon = element.querySelector('i');
            const text = element.getAttribute(`data-${lang}`);
            
            // Update the text content, not the whole innerHTML
            if (icon) {
                element.innerHTML = `${text} <i class="${icon.className}"></i>`;
            } else {
                element.textContent = text;
            }
        });
    }

        
    </script>

    <script>
        

            const menu = document.querySelector(".menu");
            const menuMain = menu.querySelector(".menu-main");
            const goBack = menu.querySelector(".go-back");
            const menuTrigger = document.querySelector(".mobile-menu-trigger");
            const closeMenu = menu.querySelector(".mobile-menu-close");
            let subMenu;
            menuMain.addEventListener("click", (e) =>{
                if(!menu.classList.contains("active")){
                    return;
                }
            if(e.target.closest(".menu-item-has-children")){
                const hasChildren = e.target.closest(".menu-item-has-children");
                showSubMenu(hasChildren);
            }
            });
            goBack.addEventListener("click",() =>{
                hideSubMenu();
            })
            menuTrigger.addEventListener("click",() =>{
                toggleMenu();
            })
            closeMenu.addEventListener("click",() =>{
                toggleMenu();
            })
            document.querySelector(".menu-overlay").addEventListener("click",() =>{
                toggleMenu();
            })
            function toggleMenu(){
                menu.classList.toggle("active");
                document.querySelector(".menu-overlay").classList.toggle("active");
            }
            function showSubMenu(hasChildren){
                subMenu = hasChildren.querySelector(".sub-menu");
                subMenu.classList.add("active");
                subMenu.style.animation = "slideLeft 0.5s ease forwards";
                const menuTitle = hasChildren.querySelector("i").parentNode.childNodes[0].textContent;
                menu.querySelector(".current-menu-title").innerHTML=menuTitle;
                menu.querySelector(".mobile-menu-head").classList.add("active");
            }

            function  hideSubMenu(){  
                subMenu.style.animation = "slideRight 0.5s ease forwards";
                setTimeout(() =>{
                subMenu.classList.remove("active");	
                },300); 
                menu.querySelector(".current-menu-title").innerHTML="";
                menu.querySelector(".mobile-menu-head").classList.remove("active");
            }
            
            window.onresize = function(){
                if(this.innerWidth >991){
                    if(menu.classList.contains("active")){
                        toggleMenu();
                    }

                }
            }


    </script>



    <script>
        document.addEventListener("DOMContentLoaded", function() {
            let counters = document.querySelectorAll('.count');
            let speed = 200; // Speed of counting

            counters.forEach(counter => {
                let animateCount = () => {
                    const target = +counter.getAttribute('data-count');
                    const count = +counter.innerText;

                    const increment = target / speed;

                    if (count < target) {
                        counter.innerText = Math.ceil(count + increment);
                        setTimeout(animateCount, 20);
                    } else {
                        counter.innerText = target;
                    }
                };

                animateCount();
            });
        });
    </script>


<script>
     function toggleFAQ(header) {
        const content = header.nextElementSibling;
        content.style.display = content.style.display === "block" ? "none" : "block";
        header.classList.toggle('active');
    }
</script>


</body>
</html>
