# question_one
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>question one</title>

  <script language="javascript">

          /*Question 1: FizzBuzz
        Write a program that prints the numbers from 1 to 100. For multiples of 3, print "Fizz"; for 
        multiples of 5, print "Buzz"; and for numbers that are multiples of both 3 and 5, print 
        "FizzBuzz".*/
        
      function fizzbus(){
        var number;
      
      for (number = 1; number<=100; number ++){
        if(number%3 === 0 && number%5 === 0){
          document.write('fizzbuzz <br>');
        }
        else if(number%3 === 0){
          document.write('fizz <br>');
        }
        else if(number%5 === 0){
          document.write('buzz <br>');
        }
        else{
          document.write(number + '<br>');
        }
      }
      }
  </script>
</head>
<body>
  <button class="one" onclick="fizzbus()">calculate</button>
</body>
</html>
