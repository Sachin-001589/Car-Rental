# Car-Rental
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vehicle Rent Form</title>

  <style>

    body{
      font-family: Arial, sans-serif;
      background:#f4f4f4;
      margin:0;
      padding:40px;
    }

    .container{
      max-width:600px;
      background:#fff;
      padding:30px;
      margin:auto;
      border-radius:12px;
      box-shadow:0 0 10px rgba(0,0,0,0.1);
    }

    h1{
      text-align:center;
      color:#333;
      margin-bottom:25px;
    }

    .form-group{
      margin-bottom:20px;
    }

    label{
      display:block;
      margin-bottom:8px;
      font-weight:bold;
      color:#444;
    }

    input,
    textarea,
    select{
      width:100%;
      padding:12px;
      border:1px solid #ccc;
      border-radius:8px;
      font-size:16px;
      box-sizing:border-box;
    }

    textarea{
      resize:vertical;
    }

    button{
      width:100%;
      padding:14px;
      background:#007bff;
      border:none;
      color:white;
      font-size:18px;
      border-radius:8px;
      cursor:pointer;
    }

    button:hover{
      background:#0056b3;
    }

  </style>
</head>
<body>

  <div class="container">

    <h1>Vehicle Rent Form</h1>

    <form>

      <!-- Name -->
      <div class="form-group">
        <label>Full Name</label>
        <input type="text" placeholder="Enter your full name" required>
      </div>

      <!-- Contact Number -->
      <div class="form-group">
        <label>Contact Number</label>
        <input type="tel" placeholder="Enter contact number" required>
      </div>

      <!-- Village -->
      <div class="form-group">
        <label>Village</label>
        <input type="text" placeholder="Enter village name" required>
      </div>

      <!-- Address -->
      <div class="form-group">
        <label>Full Address</label>
        <textarea rows="4" placeholder="Enter full address"></textarea>
      </div>

      <!-- Driving License Upload -->
      <div class="form-group">
        <label>Upload Digital License</label>
        <input type="file" accept="image/*,.pdf" required>
      </div>

      <!-- Selfie Upload -->
      <div class="form-group">
        <label>Upload Your Selfie</label>
        <input type="file" accept="image/*" required>
      </div>

      <!-- Purpose -->
      <div class="form-group">
        <label>Purpose for Rent</label>
        <textarea rows="3" placeholder="Why do you need the vehicle?"></textarea>
      </div>

      <!-- Rent Time -->
      <div class="form-group">
        <label>Time for Rent</label>

        <select required>
          <option value="">Select Duration</option>
          <option>1 Hour</option>
          <option>3 Hours</option>
          <option>Half Day</option>
          <option>Full Day</option>
          <option>Multiple Days</option>
        </select>
      </div>

      <!-- Submit -->
      <button type="submit">Submit Form</button>

    </form>

  </div>

</body>
</html>
