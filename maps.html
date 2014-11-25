<!DOCTYPE html>
<html>
<head>
	<title>Карта</title>
	<style type="text/css">
	label,
	input {
		display: block;
	}
	input {
		margin-bottom: 10px;

	}
	#hidden{
		margin: 0px auto; 
		width: 500px; 
		display:none;
	}
	#pressing{
		margin: 0px auto; 
		width: 500px;
		display:none;
	}
	#pcab{
		margin: 0px auto; 
		width: 500px;
		display:none;
	}
	#map_canvas {
		height:400px;
		
		width:400px
	}
	#friends{
		width:150px; 
		height:50px;
		position:absolute; 
		right:190px; 
		top:100px;
	}


	</style>
	<script type="text/javascript" src="http://maps.google.com/maps/api/js?sensor=false"></script>
	<script type="text/javascript" src="js/jquery.js"></script>
	<script type="text/javascript">
		var users = new Array;
		var myUsers = new Array;
		function saveLogin() {
		var login = document.getElementById("login").value;
		var password = document.getElementById("password").value;
		users = JSON.parse(localStorage.getItem('users')); 	
		    for (var i in users) {
		    	var log = users[i].login;
		    	var pass = users[i].password;
		    	if(log == document.getElementById("login").value &&  pass == document.getElementById("password").value){
		    		localStorage.setItem('activeusers',users[i].id);
		    		initialize();
		    		return pcab();
		       	} 
			}       alert('Пожалуйста, зарегистрируйтесь');
		    		openRegistr();
		    		closeMap();	    	
		}
		  
   	function showRegistr(){
		var inner = document.getElementById("pressing");
			if (inner.style.display == "none"){
			 	inner.style.display = "block"; 
			} 	
			else{
		 	inner.style.display = "none";
	    } 
	    
	}

	function openRegistr(){
		var div = document.getElementById('hidden').style;
			if(div.display == 'none'){
				div.display = 'block'
			}
			else{
			div.display = 'none';
			}
			window.location.hash = 'registration';
	}


	function pressing(){
		var el = document.getElementById('pcab').style;
			if(el.display == 'block'){
				el.display = 'none'
			}
			else{
				el.display = 'block';
			}
			window.location.hash = 'login';
	}


	function pcab(){
		var inners = document.getElementById("pcab");
			if (inners.style.display == "none"){
			 	inners.style.display = "block"; 
			} 	
			else{
		 	inners.style.display = "none";
	    } 
			window.location.hash = 'map1';
	}

	function closeMap(){
			var mapIn = document.getElementById('map_canvas').style;
				if(mapIn.display == 'block'){
					mapIn.display = 'none';
				}
				else{
					mapIn.display = 'block';
				}
		}


function showMarker(){
		var inners = document.getElementById("showMarker");
			if (inners.style.display == "none"){
			 	inners.style.display = "block"; 
			} 	
			else{
		 	inners.style.display = "none";
	    } 
			window.location.hash = 'map1';
	}


	function hidden(){
		var inner = document.getElementById("hidden");
			if (inner.style.display == "none"){
			 	inner.style.display = "block"; 
			} 	
			else{
		 	inner.style.display = "none";
	    } 
			window.location.hash = 'registration';
	}


	function pressing(){
		var inner = document.getElementById("pressing");
			if (inner.style.display == "none"){
			 	inner.style.display = "block"; 
			} 	
			else{
		 	inner.style.display = "none";
	    } 
			window.location.hash = 'login';
	}

	function openChange(){
			var change = document.getElementById('nameMarker').style;
			if(change.display == 'none'){
				change.display = 'block';
			}
			else{
				change.display = 'none'
			}
		}


	function openFriends(){
			var opFr = document.getElementById('friends').style;
				if(opFr.display == 'none'){
					opFr.display = 'block';
				}
				else{
					opFr.display = 'none';
				}
		}

function closeFriends(){
			var opFr = document.getElementById('friends').style;
				if(opFr.display == 'block'){
					opFr.display = 'none';
				}
				else{
					opFr.display = 'block';
				}
		}


	var user =  {};
	function saveRegistr(){
		user.id = 0;
		user.login = document.getElementById("login1").value;
		user.password = document.getElementById("password1").value;
		var res = localStorage.getItem('users');
		if (res == null){
			var users = new Array;
			user.id = 1;
			users.push(user);
		} else { 
			var users = JSON.parse(res);
			user.id = users.length + 1;
			users.push(user);
		}
		localStorage.setItem('users',JSON.stringify(users));
		//var myUsers = JSON.parse(localStorage.getItem('users'));
		location.hash = "#login";	
		showRegistr();	
    }

		function activeUser(){
	       	var activeuser = localStorage.getItem('activeusers');
        	var activeusers;
        	if (activeuser) {
        		users = JSON.parse(localStorage.getItem('users'));
        		for (i in users)
        		if (users[i].id == activeuser) {
        			activeusers = users[i];
        			break;
        		}
        	}
        	var activMarkers = JSON.parse(localStorage.getItem('markerArray'));
        	activeusers.marker = activMarkers;
			localStorage.setItem('myUsers', JSON.stringify(myUsers));
        }
       
var map;
    function initialize(){
        var latlng = new google.maps.LatLng(49.998976, 36.233051);
        var myOptions = {
            zoom: 8,
            center: latlng,
            mapTypeId: google.maps.MapTypeId.ROADMAP,
            mapTypeControl: true,
            mapTypeControlOptions: {style: google.maps.MapTypeControlStyle.DROPDOWN_MENU},
            navigationControl: true,
            navigationControlOptions: {style: google.maps.NavigationControlStyle.SMALL}
        };
       map = new google.maps.Map(document.getElementById("map_canvas"), myOptions);
        //обработчик события при клике на карту
        google.maps.event.addDomListener(window, 'load', initialize);
        google.maps.event.addListener(map, "click", function(event){
        	placeMarker(event.latLng);
        	var coord = new Array;
	        var X = event.latLng.lat();
	        var Y = event.latLng.lng();
        });
       /* var myUsers = JSON.parse(localStorage.getItem('myUsers'));
        if (myUsers == null) {
        	myUsers = new Array;
		} 
       var myUser = $.extend({}, user, positions, markers);
        myUsers.push(myUser);
        localStorage.setItem('myUsers',JSON.stringify(myUsers));*/
         


        window.location.hash = 'map1';
        //initialize();
    }

	var positions = {};
    function placeMarker(position){
    	  	var marker = new google.maps.Marker({
    		position: position,
    		map: map,
    		title: "dslkv",
		    animation: google.maps.Animation.DROP,
		    draggable: true
    	});
        var markersArray = JSON.parse(localStorage.getItem('markersArray'));
        if (markersArray == null) {
        	markersArray = new Array;
		} 
         positions = {
            lt: position.lat(),
            lg: position.lng()
        };
    	map.panTo(position);
    	markersArray.push(positions);
        localStorage.setItem('markersArray',JSON.stringify(markersArray));
    	marker.setMap(map);
			var infowindow;
			var html = "<table>" +
                 "<tr><td>Наименование:</td> <td><input type='text' id='name'/> </td> </tr>" +
                 "<tr><td>Адрес:</td> <td><input type='text' id='address'/></td> </tr>" +
                 "<tr><td>Тип:</td> <td><select id='type'>" +
                 "<option value='bar' SELECTED>bar</option>" +
                 "<option value='cafe' SELECTED>cafe</option>" +
                 "<option value='restaurant'>restaurant</option>" +
                 "</select> </td></tr>" +
                 "<tr><td></td><td><input style='display:block' id='click' type = 'button' onclick='saveData()' value='Сохранить'></input></td></tr>";
                   	infowindow = new google.maps.InfoWindow({
			     	content: html
			   		});
			  	  google.maps.event.addListener(marker, 'click', function() {
			      infowindow.open(map, marker);
			       //saveInfowindow();
			  	  });
		
    }

	var markers = {};
	function saveData() {
			var markerArray = [];
			markers = {};
			markers.name = document.getElementById("name").value;
	     	 markers.address = document.getElementById("address").value;
	     	 markers.type = document.getElementById("type").value;
			var ress = localStorage.getItem('markerArray');
			if (ress == null){
				var markerArray = new Array;
				markerArray.push(markers);
			} 	else { 
				var markerArray = JSON.parse(ress);
				markerArray.push(markers);
			}
			localStorage.setItem('markerArray',JSON.stringify(markerArray));

 		var myUsers = JSON.parse(localStorage.getItem('myUsers'));
        if (myUsers == null) {
        	myUsers = new Array;
		} 
       var myUser = $.extend({}, user, positions, markers);
        myUsers.push(myUser);
        localStorage.setItem('myUsers',JSON.stringify(myUsers));
    }


	function pushMarker(){
		debugger
		var activeuser = localStorage.getItem('activeusers');
			var activeusers;
			if(activeuser){
				var myUsers = JSON.parse(localStorage.getItem('myUsers'));
				for(var i in myUsers){
					if(myUsers[i].id == activeuser){
						activeusers = myUsers[i];
						break;
					} 
				}
			}
			//как пропустить этот код, если нет маркеров
			var user = activeusers;
			//var myUsers = JSON.parse(localStorage.getItem('myUsers'));
			var markerArray = new Array;
			markerArray.push(user.lt, user.lg);
				for(var i in markerArray) {
					var marker = new google.maps.Marker({
					position: new google.maps.LatLng(user.lt, user.lt), 
					map: map
					});
				}
			
		
				
		}

		var j = 0;
		var allusers = new Array;
		function allUsers(){
			//debugger
			j++;
			var users = JSON.parse(localStorage.getItem('users'));
			for(var i in users){
				var activeusersId = JSON.parse(localStorage.getItem('activeUser'));
				if(users[i].id != activeusersId){
					allusers[j] = document.createElement("input");
					allusers[j].id = users[i].id;
					allusers[j].type = "button";
					allusers[j].value = users[i].login;
					document.getElementById("friendList").appendChild(allusers[j]);
				}
			}
		}
		function openUser(){
			var users = JSON.parse(localStorage.getItem('users'));
			for( var i in users){
				if( id == users[i].id){
						var markerArray = new Array;
						markerArray.push(user.lt, user.lg);
							for(var i in markerArray) {
							markerArray = new google.maps.Marker({
							position: new google.maps.LatLng(user.lt, user.lt), 
							map: map
							});
						}
					
				}
			}
			
		}
		

window.onload = function(){
		if(location.hash == '#map1'){
			 initialize();
			 pcab();
			 closeMap();
		}

		if(location.hash == '#login' || location.hash == ''){
			showRegistr();
		}

		if(location.hash == '#registration'){
			openRegistr(); 
			closeMap();
		}
     document.getElementById('pressing').onsubmit = function (){
    	saveLogin();
    	showRegistr();
    	allUsers();
    	openFriends();
    	closeMap();
    	pushMarker();
    	return false;
	}
	document.getElementById('click').onclick = function(){
		openRegistr(); 
		showRegistr();
		closeMap();
		return false;
	}
	document.getElementById('click1').onclick = function(){
		openRegistr(); 
		saveLogin();
		return false;
	}
	document.getElementById('hidden').onsubmit = function(){
		openRegistr();
		saveRegistr();
		closeMap();
		return false;
	}
	document.getElementById('pcab').onsubmit = function(){
		initialize();
		closeMap();
		return false;
	}

	document.getElementById('friendList').onclick = function(){
			initialize();
			openUser();
			return false;
	}
}
</script>
</head>
<body>
	<form id="pressing" style="display:none" method="post" href="#login"  name="anchor">
			<h3>Личная страница</h3>
			<label for="login">Логин:</label>
			<input id="login" type="login" name="login"><br>
			<label for="password">Пароль:</label>
			<input id="password" type="password" name="password" ><br>
			<input id="save" type="submit" value="Вход"></input>
		  	<input id="click" type = "button" value="Регистрация"></input>
	</form>
	<form style="display:none" id="hidden" method="post" href="#registration"  name="anchor">
			<h3>Регистрация</h3>
			<label for="login1">Логин:</label>
			<input id="login1" type="login" name="login" autofocus required><br>
			<label for="password1">Пароль:</label>
			<input id="password1" type="password" name="password" autofocus required><br>
			<input id="saveRegistr" type="submit" value="Сохранить"></input>
			<input id="click1" type="button" value="Вход"></input>
	</form>
	<form id="pcab" style="display:none" method="post" href="#map1"  name="anchor" align="left">
			<input type="button" value="Выход" onclick="openRegistr(); closeMap(); closeFriends(); return false;" href="#registration" ></input>
	</form>
	<form  id="map_canvas" method="post" href="#map1"  name="anchor" align="center"></form>
	<form id="markers" style="display:none" method="post" href="#"  name="anchor">
		<textarea></textarea>
		<input value="Сохранить">
	</form>
<form id="showMarker" style="display:none" method="post" href="#map1"  name="anchor" align="left">
	<input type="submit" value="Показать маркеры" ></input>
</form>
<form id="friends" style="display:none">
		<div id="friendList">
			<h1 id="FR">Друзья</h1><br>
		</div>
	</form>
</body>
</html>
	
