<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
		<meta name="description" content="Интерактивная карта H1Z1" />
		<meta name="keywords" content="h1z1,interactive,world,map,spawns,locations,places,карта,хизи,спавн,дома,локации,онлайн,интерактивная" />
		<meta property="og:title" content="H1Z1 Карта" />
		<meta property="og:url" content="http://map.bigpandabar.com/" />
		<meta property="og:description" content="Интерактивная карта H1Z1" />
		<meta property="og:image" content="http://www.h1z1db.co.uk/inc/images/facebookLogo.png" />

		<title>Карта H1Z1</title>

		<link rel="stylesheet" href="/inc/css/bootstrap.min.css" type="text/css" media="screen" />
		<link rel="stylesheet" href="/inc/css/font-awesome.min.css" type="text/css" media="screen" />
		<link rel="stylesheet" href="/inc/css/leaflet.css" type="text/css" media="screen" />
		<link rel="stylesheet" href="/inc/css/style.css" type="text/css" media="screen" />
		<link rel="canonical" href="http://map.bigpandabar.com/" />

		<script type="text/javascript" src="/inc/js/jquery-1.11.2.min.js"></script>
		<script type="text/javascript" src="/inc/js/bootstrap.min.js"></script>
		<script type="text/javascript" src="/inc/js/leaflet.js"></script>
		<script type="text/javascript" src="/inc/js/leaflet-heat.js"></script>
		<script type="text/javascript" src="/inc/js/math.js"></script>
		<script type="text/javascript" src="/inc/js/map.js"></script>
		<script type="text/javascript" src="/inc/js/main.js"></script>
	</head>
	<body>

		<div id="header">
			 <div class="logo"><a href="/" title="Карта H1Z1"><img src="/inc/images/logo.png" height="70" /></a>  </div><div class="nazad"><a href="http://bigpandabar.com/" title="На сайт"><img src="/inc/images/nazad.png" height="70" /></a></div>

			
		</div>
	
	<div id="map-container">
		<div id="sidebar">
			<div class="fa hideShow visible-sm visible-xs"></div>
			<div class="content">

				<ul class="check">
					<li><span class="fa box checked" id="roadsPlaces"></span> Показывать дороги/Названия мест</li>
					<li><span class="fa box" id="spawns"></span> Показывать спавн игроков</li>
				</ul>

				<ul class="legend row">
					<li data-type="pin_caravan_camp" class="col-xs-6"><img src="/inc/images/pin_caravan_camp.png"> Лагерь</li>
					<li data-type="pin_carspawn" class="col-xs-6"><img src="/inc/images/pin_carspawn.png"> Спавн авто</li>
					<li data-type="pin_church" class="col-xs-6 clearfix"><img src="/inc/images/pin_church.png"> Церковь</li>
					<li data-type="pin_housing" class="col-xs-6"><img src="/inc/images/pin_housing.png"> Дом</li>
					<li data-type="pin_industrial" class="col-xs-6"><img src="/inc/images/pin_industrial.png"> Завод</li>
					<li data-type="pin_map_info" class="col-xs-6"><img src="/inc/images/pin_map_info.png"> Карта</li>
					<li data-type="pin_market_gasstation_shop" class="col-xs-6"><img src="/inc/images/pin_market_gasstation_shop.png"> Магазин</li>
					<li data-type="pin_policestation" class="col-xs-6"><img src="/inc/images/pin_policestation.png"> Полиц. участок</li>
					<li data-type="pin_superstore" class="col-xs-6"><img src="/inc/images/pin_superstore.png"> Супермаркет</li>
					<li data-type="pin_water_well" class="col-xs-6"><img src="/inc/images/pin_water_well.png"> Колодец</li>
					<li data-type="quest" class="col-xs-6"><img src="/inc/images/quest.png"> Сундук</li>
				</ul>
<p>&nbsp;</p><p>&nbsp;</p>
										<p>1. Нажмите клавишу "M" в игре. <br />
			2. Напишите в чате /loc. <br />
			3. Выделите с чата весь текст, затем скопируйте(ctrl+c). <br />
			4. Вставьте текст в поле ниже(ctrl+v). <br />
			5. Нажмите на кнопку "Найти!". </p>
				
				<form id="locationSearch" class="location row">
					<div class="col-xs-8" style="padding-right:0;"><input  data-toggle="tooltip" data-placement="top"  id="locationText" type="text" class="form-control" placeholder="/loc" /></div>
					<div class="col-xs-4"><input type="submit" class="btn btn-primary btn-block" value="Найти!" /></div>
				</form>
				
						<center>
		<p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p>
		<a href="http://steamcommunity.com/groups/bigpandabar" ><img hspace="10px" src="steam.png"></a>
		<p>&nbsp;</p>
		<a href="ts3server://bigpandabar.com" ><img hspace="10px" src="teamspeak.png"></a>
		<p>&nbsp;</p>
		<a href="https://vk.com/h1z1mmo" ><img src="vk.png" hspace="10px"></a>
		</center>
				
            </div>
		</div>
		<div id="map">
			<div class="canvas"></div>
            <div class="location">0.00, 0.00</div>
		</div>
	</div>

	</body>
</html>
