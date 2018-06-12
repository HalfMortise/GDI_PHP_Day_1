# GDI_PHP_Day_1
<!DOCTYPE html>
<html>
  <head>
    <title>Test Page</title>
  </head>
  <body>
    <p>
      <?php
function turtleFact()
{
  echo  '<Br/>'.'A turtle\'s lower shell is called plastron.';
}     
      echo 'Hello World';
      $numberOfKittens = 5;
      $numberOfPuppies = 4;
      $numberOfSnakes = 25;
      $numberOfAnimals = $numberOfKittens - $numberOfPuppies * $numberOfSnakes;
      echo '<Br/>'. $numberOfAnimals;
      $kittensName = 'Fluffy';
      $fullName = $kittensName . ' McDougle';
      echo '<Br/>'. $fullName;
      echo '<Br/>'. 'I\'d like to use an apostrophe.';
      turtleFact();
      turtleFact();

      function callKitten ($kittenName)
      {
  echo '<Br/>'.'Come here, ' . $kittenName . '!';
      }
callKitten ('Fluffy');
function addNumbers($a, $b) 
      {
  echo $a + $b;
      }
addNumbers(5,7);
addNumbers(9,12);

function square($num) 
      {
  return $num * $num;
      }
echo '<Br/>'. square(4);   // outputs '16'.
echo '<Br/>'. square(5);

$squareOfFive = square(5); // will make $squareOfFive equal 25.
$squareOfFour = square(4); // will make $squareOfFour equal 16

echo '<Br/>'. $squareOfFour;
echo '<Br/>'. $squareOfFive;

      ?>
    </p>
  </body>
</html>
