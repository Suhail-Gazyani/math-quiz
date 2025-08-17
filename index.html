<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Class 10 Math Quiz</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #e6f7ff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }
    .quiz-box {
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      text-align: center;
      max-width: 400px;
    }
    h1 {
      margin-bottom: 20px;
    }
    input[type="text"] {
      padding: 10px;
      width: 200px;
      font-size: 16px;
    }
    button {
      padding: 10px 20px;
      margin-top: 15px;
      font-size: 16px;
      cursor: pointer;
    }
    #feedback {
      margin-top: 20px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="quiz-box">
    <h1>Class 10 Math Quiz</h1>
    <p id="question"></p>
    <input type="text" id="answerInput" placeholder="Your answer (e.g., 13x or x=1, x=3)">
    <br>
    <button onclick="checkAnswer()">Submit</button>
    <p id="feedback"></p>
  </div>

  <script>
    let correctAnswer = "";

    function generateLinearQuestion() {
      let a = Math.floor(Math.random() * 10) + 1;
      let b = Math.floor(Math.random() * 10) + 1;
      correctAnswer = (a + b) + "x";
      document.getElementById("question").textContent = `Simplify: ${a}x + ${b}x`;
    }

    function generateQuadraticQuestion() {
      // ax² + bx + c where middle term breaks nicely
      const questions = [
        { eq: "x² + 5x + 6", ans: "x=2, x=3" },
        { eq: "x² + 7x + 10", ans: "x=2, x=5" },
        { eq: "2x² + 9x + 7", ans: "x=-1, x=-3.5" },
        { eq: "x² + 6x + 8", ans: "x=2, x=4" },
        { eq: "4x² + 7x + 3", ans: "x=-1, x=-0.75" }
      ];
      const q = questions[Math.floor(Math.random() * questions.length)];
      document.getElementById("question").textContent = `Factor: ${q.eq}`;
      correctAnswer = q.ans;
    }

    function generateQuestion() {
      document.getElementById("answerInput").value = '';
      document.getElementById("feedback").textContent = '';

      let type = Math.random() > 0.5 ? "linear" : "quadratic";
      if (type === "linear") {
        generateLinearQuestion();
      } else {
        generateQuadraticQuestion();
      }
    }

    function normalize(str) {
      return str.replace(/\s/g, "").toLowerCase();
    }

    function checkAnswer() {
      const userAnswer = normalize(document.getElementById("answerInput").value);
      const correct = normalize(correctAnswer);

      if (userAnswer === correct) {
        document.getElementById("feedback").textContent = "✅ Correct!";
      } else {
        document.getElementById("feedback").textContent = `❌ Wrong. Correct answer: ${correctAnswer}`;
      }

      setTimeout(generateQuestion, 3000);
    }

    generateQuestion();
  </script>
</body>
</html>
