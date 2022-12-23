
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
        Degenerative disc disease
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
      <p>Which two Greek Gods were twins?</p>
      <label>
        <input type="radio" name="question4" value="A" required>
        Zeus and Hades
      </label>
      <br>
      <label>
        <input type="radio" name="question4" value="B">
        Zeus and Poseidon
      </label>
      <br>
      <label>
        <input type="radio" name="question4" value="C">
        Artemis and Apollo
      </label>
      <br>
      <label>
        <input type="radio" name="question4" value="D">
        Hephaestus and Ares
      </label>
      <br>
      <button id="next4">Next</button>
    </div>
    
    
         <!-- Fifth question -->
    <div id="question5" style="display:none">
      <h2>Question 5</h2>
      <p>Which two Greek Gods were twins?</p>
      <label>
        <input type="radio" name="question5" value="A" required>
        Zeus and Hades
      </label>
      <br>
      <label>
        <input type="radio" name="question5" value="B">
        Zeus and Poseidon
      </label>
      <br>
      <label>
        <input type="radio" name="question5" value="C">
        Artemis and Apollo
      </label>
      <br>
      <label>
        <input type="radio" name="question5" value="D">
        Hephaestus and Ares
      </label>
      <br>
      <button id="next5">Next</button>
    </div>

    <!-- Result -->
    <div id="result" style="display:none">
      <h2>Congratulations!</h2>
      <p>You have completed the quiz.</p>
    </div>
    
       <script>
      // Set correct answers
const correctAnswers = {
  question1: 'B',
  question2: 'A'
  question3: 'C'
  question4: 'C'
  question5: 'C'       
};

// Get reference to buttons and result div
const next1Button = document.getElementById('next1');
const next2Button = document.getElementById('next2');
const next3Button = document.getElementById('next3');
const next4Button = document.getElementById('next4');
const next5Button = document.getElementById('next5');         
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
         
next5Button.addEventListener('click', function(event) {
  event.preventDefault();
  // Check if correct answer was selected
  const answer5 = document.querySelector('input[name="question5"]:checked');
  if (answer5 && answer5.value === correctAnswers.question5) {
    // Show result div
    document.getElementById('question5').style.display = 'none';
    resultDiv.style.display = 'block';
  }
});

              
</script>

  </body>
</html>
