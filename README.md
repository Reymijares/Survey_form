# survey_form



<link rel="stylesheet" href="html/styles.css">

@import url('https://fonts.googleapis.com/css?family=Poppins&display=swap');
@import url('https://fonts.googleapis.com/css?family=Poppins:200i,400&display=swap');

<style>
* {
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  color: #fff;
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  text-align: center;
}

body::before {
  content: '';
  position: fixed;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  z-index: -1;
  background: #1b1b32;
  background-image: linear-gradient(115deg,
      rgba(58, 58, 158, 0.8),
      rgba(136, 136, 206, 0.7)),
    url(https://cdn.freecodecamp.org/testable-projects-fcc/images/survey-form-background.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}

h1 {
  margin: 2.5rem 0 0;
  font-weight: 400;
}

p {
  margin: 0 auto .5rem auto;
  font-weight: 200;
}

form {
  width: 100%;
  max-width: 720px;
  margin: 2rem auto 0 auto;
  padding: 30px 20px;
  background-color: rgba(27, 27, 50, 0.8);
  /* background-color: #fff; */
  border-radius: .25rem;
  box-shadow: 2px 5px 10px rgba(0, 0, 0, .4);
}

.form-control {
  margin-bottom: 20px;
  text-align: left;
}

.form-control label {
  display: block;
  margin-bottom: 6px;
}

.form-control input,
.form-control select,
.form-control textarea {
  display: block;
  width: 100%;
  padding: 10px;
  font-family: inherit;
  border: 1px solid #777;
  border-radius: .25rem;
}

.form-control input[type="radio"],
.form-control input[type="checkbox"] {
  display: inline-block;
  width: auto;
}

small {
  color: #e4e4e4;
}

textarea {
  min-height: 150px;
  padding: 0.625rem;
  resize: vertical;
}

button {
  background-color: #05c46b;
  color: #fff;
  margin-bottom: .625rem;
  padding: .75rem;
  font-family: inherit;
  border: none;
  border-radius: .25rem;
  /* display: block; */
  width: 100%;
  cursor: pointer;
}

button:hover {
  opacity: .9;
}
</style>


<html>
<head>
  <meta charset=“UTF-8”>
        <meta name=“viewport” content=“width=device-width, initial-scale=1.0”>
        <meta http-equiv=“X-UA-Compatible” content=“ie=edge”>
 <link rel=“stylesheet” type=“text/css” href=“main.css”>
 <title> </title>
  </head>
  
<body>
  <div class="container">
    <header>
      <h1 id="title">freeCodeCamp Survey Form</h1>
      <p id="description"><em>Thank you for taking the time to help us improve the platform</em></p>
    </header>
  <header>
    <h1 id="title">freeCodeCamp Survey Form</h1>
    <p id="description"><em>Thank you for taking the time to help us improve the platform</em></p>
  </header>

   <form id="survey-form">
      <div class="form-control">
        <label id="name-label" for="name">Name</label>
        <input id="name" type="text" name="name" placeholder="Enter your name" required>
      </div>
      <div class="form-control">
        <label id="email-label" for="email">Email</label>
        <input id="email" type="email" name="email" placeholder="Enter your Email" required>
      </div>
      <div class="form-control">
        <label id="number-label" for="number">Email</label>
        <input id="number" type="number" name="number" placeholder="Age" min="10" max="150" required>
      </div>
  <form id="survey-form">
    <div class="form-control">
      <label id="name-label" for="name">Name</label>
      <input id="name" type="text" name="name" placeholder="Enter your name" required>
    </div>
    <div class="form-control">
      <label id="email-label" for="email">Email</label>
      <input id="email" type="email" name="email" placeholder="Enter your email" required>
    </div>
    <div class="form-control">
      <label id="number-label" for="number">Age <small>(optional)</small></label>
      <input id="number" type="number" name="number" placeholder="Age" min="10" max="150">
    </div>

  <div class="form-control">
        
  <label for="dropdown">Which option best describes your current role?</label>
        <select id="dropdown" name="role" required>
          <option value disabled selected>Select current role</option>
          <option value="student">Student</option>
          <option value="full-time">Full-time</option>
          <option value="part-time">Part-time</option>
          <option value="other">Other</option>
        </select>
     </div>
    <div class="form-control">
      <label for="dropdown">Which option best describes your current role?</label>
      <select id="dropdown" name="role" required>
        <option value disabled selected>Select current role</option>
        <option value="student">Student</option>
        <option value="full-time">Full-time</option>
        <option value="part-time">Part-time</option>
        <option value="other">Other</option>
      </select>
    </div>
    

  <div class="form-control">
      <p>Would you recommend freeCodeCamp to a fried?</p>
        <label for="recommend-1"><input id="recommend-1" type="radio" name="recommend" value="definitely" checked>Definitely</label>
        <label for="recommend-2"><input id="recommend-2" type="radio" name="recommend" value="maybe">Maybe</label>
        <label for="recommend-3"><input id="recommend-3" type="radio" name="recommend" value="not-sure">Not sure</label>
      </div>
    <div class="form-control">
      <p>Would you recommend freeCodeCamp to a friend?</p>
      <label for="recommend-1"><input id="recommend-1" type="radio" name="recommend" value="definitely" checked>Definitely</label>
      <label for="recommend-2"><input id="recommend-2" type="radio" name="recommend" value="maybe">Maybe</label>
      <label for="recommend-3"><input id="recommend-3" type="radio" name="recommend" value="not-sure">Not sure</label>
    </div>

  <div class="form-control">
        <label for="feature">What is your favorite feature of freeCodeCamp?</label>
        <select id="feature" name="feature">
          <option value disabled selected>Select an option</option>
          <option value="challenges">Challenges</option>
          <option value="projects">Projects</option>
          <option value="community">Community</option>
          <option value="open-source">Open Source</option>
        </select>
      </div>
    <div class="form-control">
      <label for="feature">What is your favorite feature of freeCodeCamp?</label>
      <select id="feature" name="feature">
        <option value disabled selected>Select an option</option>
        <option value="challenges">Challenges</option>
        <option value="projects">Projects</option>
        <option value="community">Community</option>
        <option value="open-source">Open Source</option>
      </select>
    </div>

 <div class="form-control">
        <p>What would you like to see improved? <span clss="small">(Check all that apply)</span></p>
        <label for="improve-1"><input id="improve-1" type="checkbox" name="improve" value="front-end">Front-end Project</label>
        <label for="improve-2"><input id="improve-2" type="checkbox" name="improve" value="back-end">Back-end Project</label>
        <label for="improve-3"><input id="improve-3" type="checkbox" name="improve" value="data-visualization">Data Visualization</label>
        <label for="improve-4"><input id="improve-4" type="checkbox" name="improve" value="challenges">Challenges</label>
        <label for="improve-5"><input id="improve-5" type="checkbox" name="improve" value="open-source-community">Open Source Community</label>
        <label for="improve-6"><input id="improve-6" type="checkbox" name="improve" value="gitter-help-rooms">Gitter help rooms</label>
        <label for="improve-7"><input id="improve-7" type="checkbox" name="improve" value="videos">Videos</label>
        <label for="improve-8"><input id="improve-8" type="checkbox" name="improve" value="city-meetups">City Meetups</label>
        <label for="improve-9"><input id="improve-9" type="checkbox" name="improve" value="wiki">Wiki</label>
        <label for="improve-10"><input id="improve-10" type="checkbox" name="improve" value="forum">Forum</label>
        <label for="improve-11"><input id="improve-11" type="checkbox" name="improve" value="additional-courses">Additional Courses</label>
      </div>

   <div class="form-control">
        <label for="comments">Any comments or suggestions?</label>
        <textarea id="comments" name="comments" placeholder="Enter your comment here..."></textarea>
      </div>

   <button id="submit" type="submit">Submit</button>
    </form>
  </div>
    <div class="form-control">
      <p>What would you like to see improved? <small>(Check all that apply)</small></p>
      <label for="improve-1"><input id="improve-1" type="checkbox" name="improve" value="front-end">Front-end Project</label>
      <label for="improve-2"><input id="improve-2" type="checkbox" name="improve" value="back-end">Back-end Project</label>
      <label for="improve-3"><input id="improve-3" type="checkbox" name="improve" value="data-visualization">Data Visualization</label>
      <label for="improve-4"><input id="improve-4" type="checkbox" name="improve" value="challenges">Challenges</label>
      <label for="improve-5"><input id="improve-5" type="checkbox" name="improve" value="open-source-community">Open Source Community</label>
      <label for="improve-6"><input id="improve-6" type="checkbox" name="improve" value="gitter-help-rooms">Gitter help rooms</label>
      <label for="improve-7"><input id="improve-7" type="checkbox" name="improve" value="videos">Videos</label>
      <label for="improve-8"><input id="improve-8" type="checkbox" name="improve" value="city-meetups">City Meetups</label>
      <label for="improve-9"><input id="improve-9" type="checkbox" name="improve" value="wiki">Wiki</label>
      <label for="improve-10"><input id="improve-10" type="checkbox" name="improve" value="forum">Forum</label>
      <label for="improve-11"><input id="improve-11" type="checkbox" name="improve" value="additional-courses">Additional Courses</label>
    </div>

  <div class="form-control">
      <label for="comments">Any comments or suggestions?</label>
      <textarea id="comments" name="comments" placeholder="Enter your comment here..."></textarea>
    </div>

   <button id="submit" type="submit">Submit</button>
  </form>

  <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
</body>
</html>
