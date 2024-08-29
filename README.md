# PRAKTIKUM1 PENGENALAN PHP

1. Jawaban nya adalah (case 3 : Isi variabel bulan adalah Maret karena nilai variabel bulan adalah 3, jadi dicocokkan dengan nilai case yang ada didalam switch

```php
<?php
$bulan = 3;

switch ($bulan) {
    case 1 : 
        echo "Isi variabel bulan adalah January"; 
        break;
    case 2 : 
        echo "Isi variabel bulan adalah February"; 
        break;
    case 3 : 
        echo "Isi variabel bulan adalah Maret"; 
        break;
    case 4 : 
        echo "Isi variabel bulan adalah April"; 
        break;
    case 5 : 
        echo "Isi variabel bulan adalah Mei"; 
        break;
    default :
        echo "Isi variabel tidak ditemukan";
        break;
}
?>

```
