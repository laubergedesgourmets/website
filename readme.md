# Site de Guillaume Laublanc

- Accueil : 
	- explique l'histoire du restaurant
	- Les horaires, la situation (infos parking)
- Guillaume Laublanc
- Carte et Menu
- Tourisme dans les environs
- Les producteurs
- Contact
	- Horaire - situation (parking etc)
	- Contact email/téléphone
	- Chèques cadeaux
	
	
	Embed Instagram
	
	https://codepen.io/peytondodd/pen/XWJaQwg
		```
	<br>
	
	<div class="container">	
	<div id="instagram-feed-demo" class="instagram_feed"></div>
	</div>
	
	<script src="https://www.jqueryscript.net/demo/Instagram-Photos-Without-API-instagramFeed/jquery.instagramFeed.js"></script>
	<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
	<script>
	 (function($){
			$(window).on('load', function(){
				$.instagramFeed({
					'username': 'laubergedesgourmets',
					'container': "#instagram-feed-demo",
					'display_profile': true,
					'display_biography': true,
					'display_gallery': true,
					'get_raw_json': false,
					'callback': null,
					'styling': true,
					'items': 36,
					'items_per_row': 6,
					'margin': 0.3
				});
			});
		})(jQuery);
	  </script>
	
	<br></br>
	```