<!-- <?php 
    class car {
        public $color;
        public $model;
        public function __construct($color, $model){
            $this->color = $color;
            $this->model = $model;
        }
        public function message() {
            return "My car is " . $this->color . ' ' . $this->model . "!";
        }
    }
    $myCar = new car("black", "TESLA");
    echo  $myCar -> message();
    echo "<br>"; 
    $GayzadeCar = new car("pink", "206");
    echo $GayzadeCar -> message();
    ?> -->
STRINGS IN PHP😁
====================================

for get a  str lenghts you should do it =>  echo strlen('charmi');

====================================

- Count Words in a String =>>
- str_word_count(value)
-  ???=> this function can calculate your word num or how any words in your text not letter !!!! ``word``

=====================================
REVERSE A STRS ===================
===============================
strrev(value) ==> str, rev

========><====================>
Search For a Text Within a String
===================================
strpos(value, want);

Example:
    echo strpos('charmi', 'c');
==============:)===============
Replace Text Within a String:)
عوض  کردن یک کلمه ددر یک متن 
==============================
str_replace(want,  replace, "text" )

Example: 
str_replace(ali , a , ali to ra bosid)

>>>>>>>>>>>>>>>>>>>>>>>><<<<<<<<<>>>>>>>>>
    NUMBERS IN PHP
(=========================================)
FLOATS 
=================================
CAPTION////////////
When you want use or calculate and etc in php you should use  (((Var_dump)))
in float you should do their  =>>
==========================
Is  it float ? ==>> ==> -> var_dump(is_float($X))

ANSWER: BOOL(TRUE) ||  BOOL(FALSE)


=========================================
FLOAT INFINITY :)
======================================
JUST in float the php will say to you 
some number is infinity But in int or 
etc you can not do any one.:)
==================================
$x = 1.1e07
var_dump($x);

ANSWER:
    float(INF)



========================================
PHP NUN 
    mean: Not a Number :)
===================================== 
Example : 
    $x = acos(8);
    var_dump($x);
))))))))))))))))())))())())())
PHP Numerical Strings:::::
()())))))))))
=====================================
The PHP is_numeric() function can be used to find whether a variable is numeric. The function 
((((((returns true if the variable is a number or a numeric string, false otherwise.))))))))
=================================
==========================
Example: 
<?php
$x = 5985;
var_dump(is_numeric($x));

$x = "5985";
var_dump(is_numeric($x));

$x = "59.85" + 100;
var_dump(is_numeric($x));

$x = "Hello";
var_dump(is_numeric($x));
?>

====================================
CHANGE etc data types to int 
========================================
Caption:
    sometimes you need or shoukd change  
    some data types to int . in php we can 
    do all their and ..........:)
========================================
$x = 23465.768;
$int_cast = (int)$x;
echo $int_cast;
====================================
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
php Constants or in js consts :)
======================================
for  use a Constants  in php we should 
write their as this 
    
Example :
      define("Name", "Text");
    echo Name ;

    ,
    define("Great" , "Hi welcome to arian web")
    
    echo great
    || 
    echo Great
!!!!!Tip:
    if you say the Constants name upper or lower
    case can't make different and don't 
    worry
============================================
===========================================
===
===
===
===
========================================
======================================
===
===
===
===
===
===========================================
============================================
switch :
Example : 
    <?php
$favcolor = "red";

switch ($favcolor) {
  case "red":
    echo "Your favorite color is red!";
    break;
  case "blue":
    echo "Your favorite color is blue!";
    break;
  case "green":
    echo "Your favorite color is green!";
    break;
  default:
    echo "Your favorite color is neither red, blue, nor green!";
}
?>

=================================
==================
========
========
=================
=================================
do loop in php
///////////////////////////////
do {
  code to be executed;
} while (condition is true);

 Example:
    $x = 1;

do {
  echo "The number is: $x <br>";
  $x++;
} while ($x <= 5);



eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee
eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee
===========================
===================
===========================
==================================
==========================================
for each 
for know all array or etc we should use  for each in php 

as,Example : 

    $colors = array("red", "green", "blue", "yellow"); 

    foreach ($colors as $value) {
    echo "$value <br>";
    }    
)()()()())))()()()))()())()()()())))(())
How make  a bet for  ? 
 
    as,Example : 
        for ($x = 0; $x < 10; $x++) {
    if ($x == 4) {
    break;
    }
    echo "The number is: $x <br>";
}
>>>>>>>>>>>>>>>>>>>>>>>>><<<<<<<<<<<<<<<<>>>>>>>>>>>>>>>>
<<<<<<<<<<<<<<<<<<<>>>>>>>>>>>>>>>>>>>
eeeeeeeeeeeeeeee
vvvvvvvvvv
vvvvvvvvv
vvvvvvvvvvv
rrrrrrrrrrrrrrr
for  can calculate in  the functions 
you should befor direct html! say 
<?php declare(strict_types=1); // strict requirement ?>
=========================================================
====================================================
==============================================:)
for use arrayyou should use a array(value):)

and  for coount you should use this 

count($array)
=======================================================
=================================================
PHP Indexed Arrays:)
replace or update a arrays 
=========================================
===
Example:
    <?php

    $arr = array();
    $arr[0] = 'BMW';
    echo($arr[0])

    ?>

================================================
========================================
how alert all index of array in php ? 
=============================
CAPTION: 
    for  this we should use the for loops
    as this
Example:
    $cars = array("Volvo", "BMW", "Toyota");
    $arrlength = count($cars);

    for($x = 0; $x < $arrlength; $x++) {
    echo $cars[$x];
    echo "<br>";
    }

=================================================
PHP Associative Arrays:)
=============================================
CAPTION: 
    Associative arrays are arrays that use named keys that you assign to them.
\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\|\\|\|\|
There are two ways to create an associative array: 
FIRST:
    $age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");
SECOUNDS:
$age = array('Peter', 'Ben', 'Joe');
    $age['Peter'] = "35";
    $age['Ben'] = "37";
    $age['Joe'] = "43";
    ===================
=======================================================
=================================================================
HOW USE ALL OF INDEX OF THE ARRAYS I PHP:

    this is 2 ti for do it 
    last p we used for loops and 
    in this tutorial we want to use this with
    FOR EACH loops 

as : 
    $age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");

    foreach($age as $x => $x_value) {
    echo "Key=" . $x . ", Value=" . $x_value;
    echo "<br>";
    }
برای اینکه بتونی یک ارایه رو تو یک متغییر بریزی و جابهجا کنی باید از  
as 
استفاده کنی.
:)





>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
GLOBALS
    server:
    echo $_SERVER['PHP_SELF'];
echo "<br>";
echo $_SERVER['SERVER_NAME'];
echo "<br>";
echo $_SERVER['HTTP_HOST'];
echo "<br>";
echo $_SERVER['HTTP_REFERER'];
echo "<br>";
echo $_SERVER['HTTP_USER_AGENT'];
echo "<br>";
echo $_SERVER['SCRIPT_NAME'];