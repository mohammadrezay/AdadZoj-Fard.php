# AdadZoj-Fard.php
<?php
$EvenOddNumber = readline("Enter a natural number : ");
if($EvenOddNumber >= 0 and is_int($EvenOddNumber)){
	if($EvenOddNumber % 2 == 0){
		echo $EvenOddNumber . " is a even.";
	}else{
		echo $EvenOddNumber . " is a odd.";
	}
}else{
	echo "wrong! The entered number is not a natural number.";
}
