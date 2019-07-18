<html>
 <head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <title>Задания</title>
 </head>
 <body>
 <?php
$a = array();
$a[1] = '1'; 
$a[2] = '1';
for ($n = 3; $n < 65; $n++) {
  $a[$n] = bcadd($a[$n-1], $a[$n-2]);
}
for ($n = 1; $n < 65; $n++) {
  echo($n."\t".$a[$n]." <br/>\n");
}
?>
 </body>
</html>
