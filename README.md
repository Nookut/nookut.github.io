# nookut.github.io
<html>
  <head>
    <title>Quiz</title>
  </head>
  <body>
    <h1>Quiz Title</h1>
    <p>Quiz instructions</p>

    <!-- First question -->
    <div id="question1">
      <h2>Question 1</h2>
      <p>Question text</p>
      <label>
        <input type="radio" name="question1" value="A" required>
        Answer A
      </label>
      <br>
      <label>
        <input type="radio" name="question1" value="B">
        Answer B
      </label>
      <br>
      <label>
        <input type="radio" name="question1" value="C">
        Answer C
      </label>
      <br>
      <label>
        <input type="radio" name="question1" value="D">
        Answer D
      </label>
      <br>
      <button id="next1">Next</button>
    </div>
    
    <script>
      // Set correct answers
const correctAnswers = {
  question1: 'A',
  question2: 'C'
};

// Get reference to buttons and result div
const next1Button = document.getElementById('next1');
const next2Button = document.getElementById('next2');
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
    // Show result div
    document.getElementById('question2').style.display = 'none';
    resultDiv.style.display = 'block';
  }
});

</script>

    <!-- Second question -->
    <div id="question2" style="display:none">
      <h2>Question 2</h2>
      <p>Question text</p>
      <label>
        <input type="radio" name="question2" value="A" required>
        Answer A
      </label>
      <br>
      <label>
        <input type="radio" name="question2" value="B">
        Answer B
      </label>
      <br>
      <label>
        <input type="radio" name="question2" value="C">
        Answer C
      </label>
      <br>
      <label>
        <input type="radio" name="question2" value="D">
        Answer D
      </label>
      <br>
      <button id="next2">Next</button>
    </div>

    <!-- Result -->
    <div id="result" style="display:none">
      <h2>Congratulations!</h2>
      <p>You have completed the quiz.</p>
    </div>
  </body>
</html>
