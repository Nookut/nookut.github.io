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
