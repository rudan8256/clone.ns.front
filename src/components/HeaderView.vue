<template>

<header>
			<nav class="UpperNav">
				<div class="container">
					<!-- Brand and toggle get grouped for better mobile display -->
					<p>
					<router-link :to="{name: 'home'}" active-class="homebtn-class" exact>
						Clone.ns
					</router-link>
					<router-link :to="{name: 'shop'}" active-class="homebtn-class" exact>
						MarketPlace
					</router-link>
					<router-link :to="{name: 'mypage'}" active-class="homebtn-class" exact>
						My NFT
					</router-link>

					</p>
				
					
				

				</div>
				<div class = "loginContainer">
                    <a href="">login</a>
                    <a class="registerBox" href="">register</a>
                   
     
                </div>


			</nav>
	
	</header>

  
</template>

<script>
export default {

}
</script>

<style>

</style>