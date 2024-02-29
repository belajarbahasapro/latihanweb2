<?php

$mahasiswa = [
    [
        "nim" => "23510020",
        "nama" => "siswanto",
        "jurusan" => "Sistem Informasi",
        "email" => "Siswanto@siswantoxor.com",
        
    ],
    [
        "nim" => "23521120,
        "nama" => "farhan",
        "jurusan" => "Teknologi Informasi",
        "email" => "farhan@stimata.ac.id",
        
    ],
    [
        "nim" => "2241120",
        "nama" => "rani",
        "jurusan" => "Teknologi Informasi",
        "email" => "rani@stimata.ac.id",
        
    ],

];

?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Daftar Mahasiswa</h1>
    <?php foreach ($mahasiswa as $mhs) : ?>
        <ul>
            <li>
                <a href="latihan1.php?nama=<?php echo $mhs['nama']; ?>&nim=<?php echo $mhs['nim']; ?>&jurusan=<?php echo $mhs['jurusan']; ?>&email=<?php echo $mhs['email']; <?php echo  > <?php echo $mhs['nama']; ?></a>
            </li>
        </ul>
    <?php endforeach; ?>
</body>
</html>
 <?php

$nama = $_GET['nama'];
$nim = $_GET['nim'];
$jurusan = $_GET['jurusan'];
$email = $_GET['email'];
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="<?= $img; ?>" alt="">
    <h1><?= $nama; ?></h1> siswanto;
    <h1><?= $nim; ?></h1>  farhan;
    <h1><?= $jurusan; ?></h1> rani;
    <h1><?= $email; ?></h1> 
</body>
</html>
