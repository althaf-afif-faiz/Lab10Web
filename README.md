# Lab10Web

## Nama : Althaf Afif Faiz
## NIM : 312410404
## Kelas : TI.24.A.3

## Tampilan Dashboard
<img width="1919" height="398" alt="image" src="https://github.com/user-attachments/assets/e1b34674-4217-41a0-93ce-20603a1d9dc4" />

## OOP Mobil 
Program : 
```
<?php

?>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>OOP Mobil</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">

<?php
class Mobil
{
    private $warna;
    private $merk;
    private $harga;

    public function __construct()
    {
        $this->warna = "Biru";
        $this->merk = "BMW";
        $this->harga = "10000000";
    }

    public function gantiWarna($warnaBaru)
    {
        $this->warna = $warnaBaru;
    }

    public function tampilWarna()
    {
        echo "Warna mobilnya : " . $this->warna;
    }
}

$a = new Mobil();
$b = new Mobil();

echo "<b>Mobil pertama</b><br>";
$a->tampilWarna();
echo "<br>Mobil pertama ganti warna<br>";
$a->gantiWarna("Merah");
$a->tampilWarna();

echo "<br><br><b>Mobil kedua</b><br>";
$b->gantiWarna("Hijau");
$b->tampilWarna();
?>

</div>

</body>
</html>
```
Output :     
<img width="540" height="269" alt="image" src="https://github.com/user-attachments/assets/fd5ed886-e99c-4156-963e-7f8a11120dea" />

## Form OOP 

Output :   
<img width="1083" height="333" alt="image" src="https://github.com/user-attachments/assets/4b4acde7-4ee2-4a4e-b0ba-de779029381a" />

## Data Barang 
Output : <img width="1398" height="377" alt="image" src="https://github.com/user-attachments/assets/17666368-fb28-41eb-840c-664d2e7ac171" />

## Data Mobil
Output : <img width="1912" height="362" alt="image" src="https://github.com/user-attachments/assets/dbf53e27-4742-4900-aaf3-e50565655174" />

