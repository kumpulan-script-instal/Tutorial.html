<!DOCTYPE html>
<html>
  <head>
  <title>PHP GET and POST Method Example</title>
    <link rel="stylesheet" href="css/style.css"/>
	<script src="https://github.com/on-store/Kategori/commit/82c026a3c2b526377f63743c215f4ba3e8012f06"></script>
	<script type="text/javascript" src="js/metode.js"></script>
  </head>	
  <body>
	<div class="container">
		<div class="main">
	      <form  method="get" action="index.php" id="form">
			<h2>APLIKASI-ANDROID</h2>
      <hr/>
			<label>Nama :</label>
			<input type="text" name="fnama" id="fnama"/>
			<label>Alamat :</label>
			<input type="text" name="lalamat" id="lalamat"/>
			<label>Pilih Metode :</label>
			<span><input type="radio" name="method" value="get" checked> GET &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
			<input type="radio" name="method" value="post" > POST </span>	
			<input type="submit" name="submit" id="submit" value="Submit">
		  </for>
		<?php include "proses.php";?>
		</div>
   </div>
 </body>
</html>
