# cit241
<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <script>
      // Method to add calories.  Will be called from onclick.
      var addCalories = function(currentCalories, newCalories) {
        // currentCalories should read the sum of the previous calculation.
        // If no previous calculation, currentCalories should read 0.
        var currentCalories;
        // Reads calorie input from user.
        var newCalories = document.getElementById('newCalories').value;
        // Parses input text into stored values.
        var parseCalories = parseFloat(newCalories);
        // Calculates the sum of the previous calculation (or 0) and the new value.
        var totalCalories = currentCalories + parseCalories;
        //Displays new calorie total to the user.
        document.getElementById('totalCalories').innerHTML = totalCalories;
      }    
            var answer = prompt("How many calories did you intake?"); 
            answer = true;
            answer = false;
            switch(answer) { 
                case answer <= 20: 
                console.log("awesome, keep eating!"); 
                break; 
                 case answer > 20 && answer <= 50: 
                console.log("great, you're so healthy!"); 
                break; 
                case answer > 50 && answer <= 100: 
                console.log("coolio! keep eating"); 
                break; 
                case answer > 100 && answer <= 200: 
                console.log("awesome, time for a break!"); 
                break; 
                case answer > 200 && answer <= 400: 
                console.log("nice meal! wait a couple hours before anything else!"); 
                break; 
                case answer > 400: 
                console.log("sounds yummy! go workout!"); 
                break; 
                default: 
                console.log("please enter a number, such as 100 or 70.") 
            } 
        </script>
    </head>
    <body>
    </body>
</html>

