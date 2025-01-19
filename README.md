 <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Praktikum WEB 1</title>
	<style type="text/css">
html, body {
       margin: 0;
	padding: 0;
	width: 100%;
	height: 100%;
	display: table;
	background-color: #336699;
}
.contentContainer {
	display: table-cell;
	text-align: center;
	vertical-align: middle;
	background-color: #CCCC00;
}
.content {
	width: 300px;
	height: 300px;
	background-color: #0000FF;
	margin-left: auto;
	margin-right: auto;
}
.header, .footer {
	background-color: #993300;
	width: 100%;
	height: 50px;
	display: table-row;
}
.menu {
	height: 75%;
	width: 150px;
	position: absolute;
	background: white;
	transition: 0.5s ease;
	transform: translateY(0);
}
.menu ul li a{
	text-decoration: none;
	color: red;
	font-family: Arial Black;
	color: black;
}
.footer {
	position: 100px;
	bottom: 0;
	text-align: center;
	background-color: white;
	width: 100%;
	height: 30px;
	color: black;
	padding: 3px;
	margin: 50px auto 0px;
}
table {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

</style>
</head>
<body>
<td>
<img src="foto/P.PNG" width="100" height="100">
</td>

<header>
<h1> Data Mahasiswa Teknik Informatika</h1>
 </header>
   <div class="header">
		<div class="menu">
			<ul>
				<li><a href="menu.html">Menu</a></li>
				<li><a href="Beranda.html">Beranda</a></li>
				<li><a href="kontak.html">Kontak</a></li>
			</ul>
              </div>
   <div>
<div class="contentContainer">
<div class="content">	   
<table  align="center">
	    <tr>
	    <td>NO</td>
	    <td>NAMA MAHASISWA</td>
	    <td>NPM</td>
	    <td>ALAMAT</td>
            <tr>
	    <tr>
            	<td>1</td>
            	<td>RAHMAT FAJAR</td>
            	<td>2023511030</td>
            	<td>LUYO</td>
            </tr>
            <tr>
            	<td>2</td>
            	<td>DZULFIKAR</td>
            	<td>2023511003</td>
            	<td>LANTORA</td>
            </tr>
            <tr>
            	<td>3</td>
            	<td>GIAN PRABOWO</td>
            	<td>2023511008</td>
            	<td>MANDING</td>
            </tr>
            <tr>
            	<td>4</td>
            	<td>RISKAL HIDAYAT</td>
            	<td>2023511023</td>
            	<td>MANDING</td>
            </tr>
 </table>
</div>	
<h3><p align="center">Mahasiswa Teknik informatika Universitas</p></h3>
<h3><p align="center">Al-Asyariah Mandar sebanyak</p></h3> 
	
<div class="footer">
<p align="center">Copy Right @dzulfikar003,Halaman Web Saya</p>
</div>
</body>
</html>
