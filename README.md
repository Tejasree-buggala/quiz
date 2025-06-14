<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Quiz Application</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="quiz-container">
    <h1>Basic Quiz</h1>
    
    <form>
      <!-- Question 1 -->
      <div class="question">
        <p>1. What is the capital of India?</p>
        <label><input type="radio" name="q1"> Mumbai</label><br>
        <label><input type="radio" name="q1"> New Delhi</label><br>
        <label><input type="radio" name="q1"> Bangalore</label><br>
        <label><input type="radio" name="q1"> Kolkata</label>
      </div>

      <!-- Question 2 -->
      <div class="question">
        <p>2. Which planet is known as the Red Planet?</p>
        <label><input type="radio" name="q2"> Earth</label><br>
        <label><input type="radio" name="q2"> Mars</label><br>
        <label><input type="radio" name="q2"> Jupiter</label><br>
        <label><input type="radio" name="q2"> Saturn</label>
      </div>

      <!-- Add more questions similarly -->

      <button type="submit" class="submit-btn">Submit</button>
    </form>
  </div>
</body>
</html>
