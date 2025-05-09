<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Yugma Vidya Batch - Online Admission Form</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #e0f2f1, #80deea);
      margin: 0;
      padding: 0;
    }
    .container {
      width: 90%;
      max-width: 700px;
      margin: 40px auto;
      background-color: #ffffff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    }
    h2 {
      text-align: center;
      color: #006064;
      margin-bottom: 25px;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: 600;
      color: #004d40;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #b2ebf2;
      border-radius: 6px;
      font-size: 16px;
    }
    input[type="file"] {
      border: none;
    }
    button {
      margin-top: 25px;
      width: 100%;
      padding: 12px;
      font-size: 16px;
      background-color: #00796b;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    button:hover {
      background-color: #004d40;
    }
    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Yugma Vidya Batch - Online Admission Form</h2>
    <form action="https://formsubmit.co/veeraceneetacademy@gmail.com" method="POST" enctype="multipart/form-data">
      
      <label for="name">Full Name</label>
      <input type="text" id="name" name="Full Name" required>

      <label for="contact">Contact Number</label>
      <input type="tel" id="contact" name="Contact Number" pattern="[0-9]{10}" required>

      <label for="email">Email Address</label>
      <input type="email" id="email" name="Email" required>

      <label for="application">Application Number</label>
      <input type="text" id="application" name="Application Number" required>

      <label for="medium">Preferred Medium</label>
      <select id="medium" name="Medium" required>
        <option value="">-- Select Medium --</option>
        <option value="English">English</option>
        <option value="Kannada">Kannada</option>
      </select>

      <label for="percent">Class 10 Percentage</label>
      <input type="number" id="percent" name="Class 10 Percentage" min="0" max="100" step="0.01" required>

      <label for="score">Entrance Exam Score</label>
      <input type="number" id="score" name="Entrance Exam Score" min="0" max="100" step="0.01" required>

      <label for="photo">Upload Passport Size Photo</label>
      <input type="file" id="photo" name="Photograph" accept="image/*" required>

      <label for="sign">Signature</label>
      <input type="text" id="sign" name="Signature" required>

      <!-- Hidden fields for Formsubmit -->
      <input type="hidden" name="_subject" value="New Yugma Vidya Admission Submission">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_template" value="table">

      <button type="submit">Submit Admission Form</button>
    </form>
  </div>
</body>
</html>
