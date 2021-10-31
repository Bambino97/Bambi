<template>
	<div>
		<div>
			<img 
				class="img"
				src="/img/slikaa.jpg"
				alt="fotopalma">
		</div>
		<div class="topnav">
			  <a class="active" href="#home">Usluge</a>
			  <a href="#about">O nama</a>
			  <a href="#contact">Kontakt</a>
			  <input type="text" placeholder="Pretrazi...">
		</div>
	</div>
</template>

	<style>
	.img{
			width:300px;
			height:300px;
			display: block;
			margin-left:0;
			margin-right:;
			margin-top: 0
		}
body {
			 margin: 0;
			font-family: Arial, Helvetica, sans-serif;
		}

	.topnav {
	  overflow: hidden;
	  background-color: #e9e9e9;
	}

	.topnav a {
	  float: left;
	  display: block;
	  color: black;
	  text-align: center;
	  padding: 14px 16px;
	  text-decoration: none;
	  font-size: 17px;
	}

	.topnav a:hover {
	  background-color: #ddd;
	  color: black;
	}

	.topnav a.active {
	  background-color: #2196F3;
	  color: white;
	}

	.topnav .search-container {
	  float: right;
	}

	.topnav input[type=text] {
		margin-left:1026px;
	  padding: 6px;
	  margin-top: 8px;
	  font-size: 17px;
	  border:all;
	}

	.topnav .search-container button {
	  float: right;
	  padding: 6px;
	  margin-top: 8px;
	  margin-right: 16px;
	  background: #ddd;
	  font-size: 17px;
	  border: none;
	  cursor: pointer;
	}

	.topnav .search-container button:hover {
	  background: #ccc;
	}

@media screen and (max-width: 600px) {
	.topnav .search-container {
	    float: none;
	  }
	.topnav a, .topnav input[type=text], .topnav .search-container button {
	    float: none;
	    display: block;
	    text-align: left;
	    width: 100%;
	    margin: 0;
	    padding: 14px;
	  }
	 .topnav input[type=text] {
	    border: 1px solid #ccc;  
	  }
}




	</style>