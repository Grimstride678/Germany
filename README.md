<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>გერმანიის ქვიზი</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Segoe UI", sans-serif;
      background: linear-gradient(to bottom, #000000, #dd0000, #ffce00);
      color: #fff;
      min-height: 100vh;
    }
  
    header {
      text-align: center;
      padding: 2rem;
      background-color: rgba(0, 0, 0, 0.7);
    }
  
    header h1 {
      margin: 0;
      color: #ffce00;
      font-size: 2.5rem;
    }
  
    .container {
      max-width: 800px;
      margin: 2rem auto;
      background: rgba(255, 255, 255, 0.1);
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 0 15px rgba(0,0,0,0.5);
    }
  
    h2 {
      color: #ffce00;
      text-align: center;
      margin-bottom: 2rem;
    }
  
    .question {
      margin-bottom: 2rem;
      background-color: rgba(255, 255, 255, 0.1);
      padding: 1rem;
      border-radius: 12px;
    }
  
    .question p {
      font-size: 1.2rem;
      margin-bottom: 1rem;
    }
  
    button {
      background-color: #ffffff;
      color: #000;
      border: none;
      padding: 0.6rem 1.2rem;
      margin: 0.4rem 0.5rem 0 0;
      border-radius: 8px;
      cursor: pointer;
      transition: all 0.3s ease;
    }
  
    button:hover {
      background-color: #f0f0f0;
    }
  
    .correct {
      background-color: #4caf50 !important;
      color: white;
    }
  
    .incorrect {
      background-color: #f44336 !important;
      color: white;
    }
  
    /* მობილურისთვის */
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
  
      .container {
        margin: 1rem;
        padding: 1.2rem;
      }
  
      .question p {
        font-size: 1.05rem;
      }
  
      button {
        width: 100%;
        margin: 0.3rem 0;
        padding: 0.8rem;
        font-size: 1rem;
      }
    }
  </style>  
</head>
<body>
  <header>
    <h1>გერმანიის ქვიზი</h1>
  </header>

  <div class="container">
    <h2>უპასუხე 10 კითხვას და გამოავლინე შენი ცოდნა გერმანიაზე!</h2>

    <!-- Question 1 -->
    <div class="question">
      <p><strong>1. რომელ ქვეყანას არ ესაზღვრება გერმანია?</strong></p>
      <button onclick="checkAnswer(this, false)">შვეიცარია</button>
      <button onclick="checkAnswer(this, false)">ნიდერლანდები</button>
      <button onclick="checkAnswer(this, true)">პორტუგალია</button>
    </div>

    <!-- Question 2 -->
    <div class="question">
      <p><strong>2. რამდენ ფედერაციულ მიწას მოიცავს გერმანია?</strong></p>
      <button onclick="checkAnswer(this, false)">12</button>
      <button onclick="checkAnswer(this, true)">16</button>
      <button onclick="checkAnswer(this, false)">20</button>
    </div>

    <!-- Question 3 -->
    <div class="question">
      <p><strong>3. რომელი მთაა ყველაზე მაღალი გერმანიაში?</strong></p>
      <button onclick="checkAnswer(this, false)">ფუჯი</button>
      <button onclick="checkAnswer(this, false)">პეგლაუკი</button>
      <button onclick="checkAnswer(this, true)">ცუგშპიცე</button>
    </div>

    <!-- Question 4 -->
    <div class="question">
      <p><strong>4. რომელია გერმანიის ყველაზე გრძელი მდინარე?</strong></p>
      <button onclick="checkAnswer(this, true)">რაინი</button>
      <button onclick="checkAnswer(this, false)">შპრეე</button>
      <button onclick="checkAnswer(this, false)">ოდერი</button>
    </div>

    <!-- Question 5 -->
    <div class="question">
      <p><strong>5. როგორია გერმანიის კლიმატი?</strong></p>
      <button onclick="checkAnswer(this, true)">ზომიერი</button>
      <button onclick="checkAnswer(this, false)">ტროპიკული</button>
      <button onclick="checkAnswer(this, false)">უდაბნოს</button>
    </div>

    <!-- Question 6 -->
    <div class="question">
      <p><strong>6. გერმანიის დედაქალაქია:</strong></p>
      <button onclick="checkAnswer(this, true)">ბერლინი</button>
      <button onclick="checkAnswer(this, false)">მიუნხენი</button>
      <button onclick="checkAnswer(this, false)">ჰამბურგი</button>
    </div>

    <!-- Question 7 -->
    <div class="question">
      <p><strong>7. გერმანიაში რომელი ენაა ოფიციალური?</strong></p>
      <button onclick="checkAnswer(this, true)">გერმანული</button>
      <button onclick="checkAnswer(this, false)">ინგლისური</button>
      <button onclick="checkAnswer(this, false)">ფრანგული</button>
    </div>

    <!-- Question 8 -->
    <div class="question">
      <p><strong>8. გერმანიის ეროვნული ფერები არის:</strong></p>
      <button onclick="checkAnswer(this, true)">შავი, წითელი, ყვითელი</button>
      <button onclick="checkAnswer(this, false)">ლურჯი, თეთრი, წითელი</button>
      <button onclick="checkAnswer(this, false)">მწვანე, თეთრი, წითელი</button>
    </div>

    <!-- Question 9 -->
    <div class="question">
      <p><strong>9. გერმანიაში გავრცელებული ცნობილი მანქანის ბრენდია:</strong></p>
      <button onclick="checkAnswer(this, true)">BMW</button>
      <button onclick="checkAnswer(this, false)">Toyota</button>
      <button onclick="checkAnswer(this, false)">Hyundai</button>
    </div>

    <!-- Question 10 -->
    <div class="question">
      <p><strong>10. რომელ ქალაქში იმართება ცნობილი ოქტობერფესტი?</strong></p>
      <button onclick="checkAnswer(this, false)">ბერლინში</button>
      <button onclick="checkAnswer(this, true)">მიუნხენში</button>
      <button onclick="checkAnswer(this, false)">კიოლნში</button>
    </div>

  </div>

  <script>
    function checkAnswer(button, isCorrect) {
      const buttons = button.parentElement.querySelectorAll("button");
      buttons.forEach(btn => btn.disabled = true);
      button.classList.add(isCorrect ? "correct" : "incorrect");
    }
  </script>
</body>
</html>
