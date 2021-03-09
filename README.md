<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="left">
<h2>Введите название города</h2>
 <p>Например: <span style="color:green; font-size:16px;">Kharkiv, Kyiv, Tokio, <br>Moscow, Saint Petersburg, Tver ...</span></p>
 <input type="text" id="city" placeholder="Введите название города (англ.)..."/>
 <button id="cityB" onclick="showDateTime();">OK</button>
<h2>Или выберите из списка (25 городов)</h2>
<p><select  class="select" name="cityes">  
    <option selected value="Kyiv">Киев</option>
	<option value="Kharkiv">Харьков</option>
	<option value="Lviv">Львов</option>	
    <option value="Moscow">Москва</option>
	<option value="Tver">Тверь</option>
	<option value="Stavropol">Ставрополь</option>
	<option value="Chelyabinsk">Челябинск</option>	
    <option value="Minsk">Минск</option>
	<option value="Astana">Астана</option>
    <option value="Tbilisi">Тбилиси</option>
	<option value="Chisinau">Кишинёв</option>	
	<option value="Berlin">Берлин</option>
    <option value="Rio de Janeiro">Рио-де-Жанейро</option>
    <option value="Beijing">Пекин</option>
    <option value="Melbourne">Мельбурн</option>
    <option value="Managua">Манагуа</option>	
	<option value="Madrid">Мадрид</option>
    <option value="Helsinki">Хельсинки</option>
    <option value="Warsaw">Варшава</option>
    <option value="Ottawa">Оттава</option>
    <option value="London">Лондон</option>
	<option value="Rome">Рим</option>
	<option value="Mexico city">Мехико</option>
    <option value="Delhi">Дели</option>    
    <option value="Tokio">Токио</option>	
   </select></p>  
<p class="text-center">Прогноз на 4 дня <br><span id="cityC"></span><p>	
	<div id="tablo">            
		<div class="day">
			  <img id="tmp4"/><br>
			 <p id="day1"></p>
			 <div id="demo7"></div>
			 <div id="demo5" ></div>
			 <div id="demo6"></div>
			 <div id="demo4"></div>
		</div>

		<div class="day">
			   <img id="tmp5"/><br>
			 <p id="day2"></p>
			 <div id="demo10"></div>
			 <div id="demo11"></div>
			 <div id="demo8"></div>
			 <div id="demo9"></div>
		</div> 

		<div class="day">
			   <img id="tmp6"/><br>
			 <p id="day3"></p>
			 <div id="demo14"></div>
			 <div id="demo15"></div>
			 <div id="demo12"></div>
			 <div id="demo13"></div>
		</div> 

		<div class="day">
			   <img id="tmp7"/><br>
			 <p id="day4"></p>
			 <div id="demo18"></div>
			 <div id="demo19"></div>
			 <div id="demo16"></div>
			 <div id="demo17"></div>
		</div>
  </div>
  </div>
<script src="https://code.jquery.com/jquery-1.11.1.min.js"></script>
<script src="js2.js"></script>
</body>
</html>
