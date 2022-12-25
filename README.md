
<html>
  <head>
    <title>Quiz</title>
  </head>
  <body>
    <h1>Nallys Christmas Quiz</h1>
    <p>To get to your gift you must answer each of my questions correctly.</p>

    <!-- First question -->
    <div id="question1">
      <h2>Question 1</h2>
      
   
      <p>If you were Lewis Hamilton, who would be the first person to thank upon receiving your gift?</p>
      <label>
        <input type="radio" name="question1" value="A" required>
        God
      </label>
      <br>
      <label>
        <input type="radio" name="question1" value="B">
        The fans
      </label>
      <br>
      <label>
        <input type="radio" name="question1" value="C">
        Your sponsors
      </label>
      <br>
      <label>
        <input type="radio" name="question1" value="D">
        Your parents
      </label>
      <br>
      <button id="next1">Next</button>
    </div>

    <!-- Second question -->
    <div id="question2" style="display:none">
      <h2>Question 2</h2>  
      <p>Why does Abby Lee Miller require a wheelchair?</p>
      <label>
        <input type="radio" name="question2" value="A" required>
        Lymphoma
      </label>
      <br>
      <label>
        <input type="radio" name="question2" value="B">
        Type 2 diabetes
      </label>
      <br>
      <label>
        <input type="radio" name="question2" value="C">
        Arthritis
      </label>
      <br>
      <label>
        <input type="radio" name="question2" value="D">
        Stroke complications
      </label>
      <br>
      <button id="next2">Next</button>
    </div>
    
    
     <!-- Third question -->
    <div id="question3" style="display:none">
      <h2>Question 3</h2> 
      <p>Which two Greek Gods were twins?</p>
      <label>
        <input type="radio" name="question3" value="A" required>
        Zeus and Hades
      </label>
      <br>
      <label>
        <input type="radio" name="question3" value="B">
        Zeus and Poseidon
      </label>
      <br>
      <label>
        <input type="radio" name="question3" value="C">
        Artemis and Apollo
      </label>
      <br>
      <label>
        <input type="radio" name="question3" value="D">
        Hephaestus and Ares
      </label>
      <br>
      <button id="next3">Next</button>
    </div>
    
         <!-- Fourth question -->
    <div id="question4" style="display:none">
      <h2>Question 4</h2>  
      <p>What was the first National park in Canada?</p>
      <label>
        <input type="radio" name="question4" value="A" required>
        Yoho
      </label>
      <br>
      <label>
        <input type="radio" name="question4" value="B">
        Riding Mountain
      </label>
      <br>
      <label>
        <input type="radio" name="question4" value="C">
        Jasper
      </label>
      <br>
      <label>
        <input type="radio" name="question4" value="D">
        Banff
      </label>
      <br>
      <button id="next4">Next</button>
    </div>
    
         <!-- Fifth question -->
    <div id="question5" style="display:none">
      <h2>Question 5</h2> 
      <p>How long were Kim K and Kris Humphries married for?</p>
      <label>
        <input type="radio" name="question5" value="A" required>
        6 months
      </label>
      <br>
      <label>
        <input type="radio" name="question5" value="B">
        60 days
      </label>
      <br>
      <label>
        <input type="radio" name="question5" value="C">
        7 weeks
      </label>
      <br>
      <label>
        <input type="radio" name="question5" value="D">
        72 days
      </label>
      <br>
      <button id="next5">Next</button>
    </div>
    
        <!-- sixth question -->
    <div id="question6" style="display:none">
      <h2>Question 6</h2> 
      <p>What song did James Charles sing while suspended over a canyon?</p>
      <label>
        <input type="radio" name="question6" value="A" required>
        God is a Woman - Ariana Grande
      </label>
      <br>
      <label>
        <input type="radio" name="question6" value="B">
        I Will Always Love You - Whitney Houston
      </label>
      <br>
      <label>
        <input type="radio" name="question6" value="C">
        Hallelujah - Leonard Cohen
      </label>
      <br>
      <label>
        <input type="radio" name="question6" value="D">
        Stay With Me - Sam Smith
      </label>
      <br>
      <button id="next6">Next</button>
    </div>
    
        <!-- seventh question -->
    <div id="question7" style="display:none">
      <h2>Question 7</h2>
      <p>In Sims 4, how many Sims can be in a household?</p>
      <label>
        <input type="radio" name="question7" value="A" required>
        5
      </label>
      <br>
      <label>
        <input type="radio" name="question7" value="B">
        8
      </label>
      <br>
      <label>
        <input type="radio" name="question7" value="C">
        10
      </label>
      <br>
      <label>
        <input type="radio" name="question7" value="D">
        6
      </label>
      <br>
      <button id="next7">Next</button>
    </div>
    
        <!-- eigth question -->
    <div id="question8" style="display:none">
      <h2>Question 8</h2>
      <p>How many Kilometers do a pair of running shoes last on average?</p>
      <label>
        <input type="radio" name="question8" value="A" required>
        640
      </label>
      <br>
      <label>
        <input type="radio" name="question8" value="B">
        1,000
      </label>
      <br>
      <label>
        <input type="radio" name="question8" value="C">
        5,000
      </label>
      <br>
      <label>
        <input type="radio" name="question8" value="D">
        10,000
      </label>
      <br>
      <button id="next8">Next</button>
    </div>

    <!-- Result -->
    <div id="result" style="display:none">
      <h2>Congratulations!</h2>
      <p>You have completed the quiz! Your prize is $50 towards a pair of running shoes because you passed 640km a while ago.</p>
       
    </div>
    
       <script>
      // Set correct answers
const correctAnswers = {
  question1: 'B',
  question2: 'A',
  question3: 'C',
  question4: 'D',
  question5: 'D',
  question6: 'C',
  question7: 'B',
  question8: 'A'
};

// Get reference to buttons and result div
const next1Button = document.getElementById('next1');
const next2Button = document.getElementById('next2');
const next3Button = document.getElementById('next3');
const next4Button = document.getElementById('next4');
const next5Button = document.getElementById('next5');  
const next6Button = document.getElementById('next6');  
const next7Button = document.getElementById('next7');  
const next8Button = document.getElementById('next8');  

const resultDiv = document.getElementById('result');

// Add event listeners to buttons
next1Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer1 = document.querySelector('input[name="question1"]:checked');
  if (answer1 && answer1.value === correctAnswers.question1) {
    // Show second question
    document.getElementById('question1').style.display = 'none';
    document.getElementById('question2').style.display = 'block';
  }
});

         next2Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer2 = document.querySelector('input[name="question2"]:checked');
  if (answer2 && answer2.value === correctAnswers.question2) {
    // Show third question
    document.getElementById('question2').style.display = 'none';
    document.getElementById('question3').style.display = 'block';
  }
});
         
              next3Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer3 = document.querySelector('input[name="question3"]:checked');
  if (answer3 && answer3.value === correctAnswers.question3) {
    // Show third question
    document.getElementById('question3').style.display = 'none';
    document.getElementById('question4').style.display = 'block';
  }
});

  			next4Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer4 = document.querySelector('input[name="question4"]:checked');
  if (answer4 && answer4.value === correctAnswers.question4) {
    // Show third question
    document.getElementById('question4').style.display = 'none';
    document.getElementById('question5').style.display = 'block';
  }
});

  next5Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer5 = document.querySelector('input[name="question5"]:checked');
  if (answer5 && answer5.value === correctAnswers.question5) {
    // Show third question
    document.getElementById('question5').style.display = 'none';
    document.getElementById('question6').style.display = 'block';
  }
});

  next6Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer6 = document.querySelector('input[name="question6"]:checked');
  if (answer6 && answer6.value === correctAnswers.question6) {
    // Show third question
    document.getElementById('question6').style.display = 'none';
    document.getElementById('question7').style.display = 'block';
  }
});

  next7Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer7 = document.querySelector('input[name="question7"]:checked');
  if (answer7 && answer7.value === correctAnswers.question7) {
    // Show third question
    document.getElementById('question7').style.display = 'none';
    document.getElementById('question8').style.display = 'block';
  }
});
         
next8Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer8 = document.querySelector('input[name="question8"]:checked');
  if (answer8 && answer8.value === correctAnswers.question8) {
    // Show result div
    document.getElementById('question8').style.display = 'none';
    resultDiv.style.display = 'block';
  }
});

              
</script>

  </body>
</html>
