<template>

<header class="header_area sticky-header">
		<div class="main_menu">
			<nav class="navbar navbar-expand-lg navbar-light main_box">
				<div class="container">
					<!-- Brand and toggle get grouped for better mobile display -->
					<router-link :to="{name: 'home'}"  active-class="homebtn-class" exact>
						<a>Clone.ns</a>
					</router-link>

					<nav>
            <div class="UpperNav">
                <div class = "navContainer">
                    <a href="">AvatarNFT</a>
                    <a href="">MarketPlace</a>
                    <a href="">My NFT</a> 
                </div>
    
                <div class = "loginContainer">
                    <a href="">login</a>
                    <a class="registerBox" href="">register</a>
                   
     
                </div>
            </div>
        </nav>
					
					<!-- Collect the nav links, forms, and other content for toggling -->
					<div class="collapse navbar-collapse offset" id="navbarSupportedContent">
						<ul class="nav navbar-nav menu_nav ml-auto">
							
						<router-link :to="{name: 'shop'}"  active-class="shopbtn-class" exact>
							<a>Shop</a>
						</router-link>


						</ul>
						<ul class="nav navbar-nav navbar-right">
							<li class="nav-item"><a href="#" class="cart"><span class="ti-bag"></span></a></li>
							<li class="nav-item">
								<button class="search"><span class="lnr lnr-magnifier" id="search"></span></button>
							</li>
						</ul>
					</div>
				</div>
			</nav>
		</div>
		<div class="search_input" id="search_input_box">
			<div class="container">
				<form class="d-flex justify-content-between">
					<input type="text" class="form-control" id="search_input" placeholder="Search Here">
					<button type="submit" class="btn"></button>
					<span class="lnr lnr-cross" id="close_search" title="Close Search"></span>
				</form>
			</div>
		</div>
	</header>

  
</template>

<script>
export default {

}
</script>

<style>

</style>