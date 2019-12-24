<?php 
//-------------------------log in page-----------------------

$username = "tariq";
$password = "789";

$dbusername ="ahmed";
$dbpassword = "123";

$dbusername1 ="tariq";
$dbpassword1 = "789";

if ($username === $dbusername && $password === $dbpassword) {
	echo "welcome ";
}elseif ($username === $dbusername1 && $password === $dbpassword1) {
	echo "welcome ";
}
else {
	echo "error";
}
echo "<hr>";

//-----------------tester----------------------
$test = false;
 
  if (is_string($test)) {
  	echo "$test";
  }elseif (is_int($test)) {
  	echo " $test" + 5;
  }elseif (is_float($test)) {
  	echo " $test" * 7;
  }// some thing is wrong here but i bo not know it
  /*elseif ($test->is_type( 'true' ) ){
    echo "yes";
  }elseif ($test->is_type( 'false' ) ){
    echo "no";
  }*/

  else {
  	echo "error";
  }
  echo "<hr>";
  //-----------------Days----------------------
$day ="الجمعه";
 if ($day =="السبت ") {
 	echo "Saturday";
 } elseif ($day == "الاحد") {
 	echo "Sunday";
 }elseif ($day == "الاتنين") {
 	echo "Monday";
}elseif ($day == "الثلاثاء") {
 	echo "Tuesday";
}elseif ($day == "الاربعاء") {
 	echo "Wednesday";
 }elseif ($day == "الخميس") {
 	echo "Thursday";
}elseif ($day == "الجمعه") {
 	echo "Friday";
}

?>
