 <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Praktikum WEB 1</title>
	<style type="text/css">
		body{
		background-color: aqua;
	background-image: url(poto/10.jpg);
	background-repeat: no-repeat;
	background-position: right;
	height: 670px;
	background-size: 320px;
}
header {
        background-color: white;
	text-align: center;
	width: 100;
	height: 30;
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
table-container {
    position: relative;
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
   <div class="navigasi">
		<div class="menu">
			<ul>
				<li><a href="menu.html">Menu</a></li>
				<li><a href="Beranda.html">Beranda</a></li>
				<li><a href="kontak.html">Kontak</a></li>
			</ul>
		</div>
<div class="table-container">
 <table>
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
