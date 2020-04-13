<!DOCTYPE html>
<html>
<head>
	<title>Form Validation</title>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<style>
	.warning {color: #FF0000;}
</style>
</head>
<body>

<?php
$erorr_nama = "";
$error_email = "";
$erorr_web = "";
$erorr_pesan = "";
$erorr_telp = "";

$nama = "";
$email = "";
$web = "";
$pesan = "";
$telp = "";

if ($_SERVER["REQUEST_METHOD"] == "POST") {
	if (empty($_POST["nama"])) {
		$erorr_nama = "Nama Tidak Boleh Kosong";
	}
	else{
		$nama = cek_input($_POST["nama"]);
		if (!preg_match("/^[a-zA-Z]*$/",$nama)) {
			$erorr_nama = "Inputan Hanya boleh huruf dan spasi";
		}
	}if (empty($_POST["email"])) {
		$erorr_email = "Email Tidak Boleh Kosong";
	}
	else{
		$email = cek_input($_POST["email"]);
		if (!filter_var($email, FILTER_VALIDATE_EMAIL)) {
			$erorr_email = "Format Email Invalid";
		}
	}if (empty($_POST["pesan"])) {
		$erorr_pesan = "pesan Tidak boleh Kosong";
	}else{
		$pesan = cek_input($_POST("pesan"));
	}if (empty($_POST["web"])) {
		$erorr_web = "Website tidak boleh kosong";
	}else{
		$web = cek_input($_POST["web"]);

		if (!preg_match("/\b(?:(?:https?|ftp):\/\/|www\.)[-a-z0-9+&@#\/%?=~_|!:,.;]*[-a-z0-9+&@#\/%=~_|]/i",$web)) {
		$erorr_web = "URL tidak valid";
		}
	}if (empty($_POST["telp"])) {
		$erorr_telp = "telp Tidak boleh kosong";
	}else{
		$telp = cek_input($_POST["telp"]);

		if (!is_numeric($telp)) {
			$erorr_telp = "NOmer telp hanya boleh angka";
		}
	}
}

function cek_input($data){
	$data = trim($data);
	$data = stripcslashes($data);
	$data = htmlspecialchars($data);
	return $data;
}
?>

<div class="row">
<div class="col-md-6">
<div class="card">
	<div class="card-header">
		Contoh Validasi Form dengan PHP
	</div>
	<div class="card-body">
		<form method="post" action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]);?>"> <div class="form-grup row">
			<label for="nama" class="col-sm-2 col-form-label">Nama</label>
			<div class="col-sm-10">
				<input type="text" name="nama" class="form-control <?php echo ($erorr_nama !="" ? "is-invalid" : ""); ?>" id="nama" placeholder="nama" value="<?php echo $nama; ?>"><span class="warning"><?php echo $erorr_nama;?></span>
			</div>
		</div>
		<div class="form-group row">
			<label for="email" class="col-sm-2 col-form-label">Email</label>
			<div class="col-sm-10">
				<input type="text" name="email" class="form-control <?php echo ($erorr_email !="" ? "is-invalid" : ""); ?>" id="email" placeholder="email" value="<?php echo $email; ?>"><span class="warning"><?php echo $error_email; ?></span>
			</div>
		</div>
		<div class="form-group row">
			<label for="web" class="col-sm-2 col-form-label">Website</label>
			<div class="col-sm-10">
				<input type="text" name="web" class="form-control <?php echo ($erorr_web !="" ? "is-invalid" : ""); ?>" id="web" placeholder="web" value="<?php echo $web; ?>"><span class="warning"><?php echo $erorr_web;?></span>
			</div>
		</div>
		<div class="form-group row">
			<label for="telp" class="col-sm-2 col-form-label">Telp</label>
			<div class="col-sm-10">
				<input type="text" name="telp" class="form-control <?php echo ($erorr_telp !="" ? "is-invalid" : ""); ?>" id="telp" placeholder="telp" value="<?php echo $telp; ?>"><span class="warning"><?php echo $erorr_telp;?></span>
			</div>
		</div>
		<div class="form-group row">
			<label for="pesan" class="col-sm-2 col-form-label">Pesan</label>
			<div class="col-sm-10">
				<textarea name="pesan" class="form-control <?php echo ($erorr_pesan !="" ? "is-invalid" : ""); ?>"><?php echo $pesan; ?></textarea><span class="warning"><?php echo $erorr_pesan;?></span>
			</div>
		</div>
		<div class="form-group row">
			<div class="col-sm-10">
				<button type="submit" class="btn btn-primary">Sign In</button>
			</div>
		</div>
		</form>
		
	</div>
</div>	
</div>	
</div>

<?php
echo "<h2> Your Input:</h2>";
echo "nama = ".$nama;
echo "<br>";
echo "Email = ".$email;
echo "<br>";
echo "Website = ".$web;
echo "<br>";
echo "Telp = ".$telp;
echo "<br>";
echo "Pesan = ".$pesan;


  ?>



</body>
</html>