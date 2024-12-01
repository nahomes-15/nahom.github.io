<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Omar Montasser</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <div class="left-section">
      <img src="your-image.jpg" alt="Omar Montasser" class="profile-pic">
      <h1>Omar Montasser</h1>
      <p><strong>Email:</strong> <a href="mailto:omar.montasser@yale.edu">omar.montasser@yale.edu</a></p>
      <p><strong>Links:</strong> 
        <a href="#">Google Scholar</a> | 
        <a href="#">DBLP</a>
      </p>
      <p><strong>Location:</strong> Kline Tower, Room 1051.</p>
    </div>
    <div class="right-section">
      <h2>Welcome!</h2>
      <p>I am an Assistant Professor at Yale, in the <strong>Department of Statistics and Data Science</strong>. My research broadly explores theory and foundations of machine learning, with a particular interest in addressing modern challenges such as robustness to adversarial examples and distribution shifts.</p>

      <h3>Prospective Students:</h3>
      <p>I am looking for motivated PhD students to join my group. If you are interested in working with me, please apply to our <a href="#">PhD program</a> and mention my name. If you are already at Yale, feel free to email me with a short description of your research interests and your CV.</p>

      <h3>Background:</h3>
      <p>Prior to Yale, I spent one year at UC Berkeley as a FODSI-Simons postdoctoral researcher. I received my PhD from the Toyota Technological Institute at Chicago, where I was fortunate to be advised by Nathan Srebro. During my PhD, I primarily thought about questions related to learning machine learning models robust against adversarial examples, through the lens of learning theory.</p>

      <h3>Publications:</h3>
      <ul>
        <li><a href="#">Transformation-Invariant Learning and Theoretical Guarantees for OOD Generalization</a><br>
        <i>Omar Montasser, Han Shao, Emmanuel Abbe</i> - To appear in NeurIPS, 2024.</li>
        <li><a href="#">Derandomizing Multi-Distribution Learning</a><br>
        <i>Kasper Green Larsen, Omar Montasser, Nikita Zhivotovsky</i> - To appear in NeurIPS, 2024.</li>
        <li><a href="#">Agnostic Multi-Robust Learning Using ERM</a><br>
        <i>Saba Ahmadi, Avrim Blum, Omar Montasser, Kevin Stangl</i> - AISTATS, 2024.</li>
        <li><a href="#">Strategic Classification under Unknown Personalized Manipulation</a><br>
        <i>Han Shao, Avrim Blum, Omar Montasser</i></li>
      </ul>
    </div>
  </div>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f7f7f7;
  color: #333;
}

.container {
  display: flex;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.left-section {
  width: 30%;
  background-color: #1a202c;
  color: white;
  padding: 20px;
  text-align: center;
  border-radius: 8px;
}

.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  margin-bottom: 20px;
}

.left-section h1 {
  font-size: 24px;
  margin-bottom: 10px;
}

.left-section p, .left-section a {
  font-size: 14px;
  margin-bottom: 10px;
  color: white;
  text-decoration: none;
}

.right-section {
  width: 70%;
  padding: 20px;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.right-section h2 {
  font-size: 28px;
  margin-bottom: 10px;
}

.right-section h3 {
  font-size: 20px;
  margin-top: 20px;
}

.right-section p, .right-section ul {
  font-size: 16px;
  line-height: 1.6;
}

.right-section ul {
  list-style-type: disc;
  margin-left: 20px;
}

a {
  color: #007bff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

