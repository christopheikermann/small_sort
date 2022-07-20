# small_sort

php > $a = [6,5,8,3];
php > for($i=0; $i < sizeof($a)-1;($a[$i] > $a[$i+1]) ? ($a[$i+1] ^= $a[$i] ^= $a[$i+1] ^= $a[$i]) && $i=0: $i++) {}
php > var_dump($a); // 3, 5, 6, 8
