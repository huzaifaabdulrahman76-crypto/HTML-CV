<!DOCTYPE html>
<html>
<head>
  
  <title>Huzaifa Abdul Rahman</title>

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  
  <style>
    body {   /* the background color */
      font-family: 'Roboto', sans-serif;  
      background: #f5f7fa;
      margin: 0;
      padding: 20px;
      color: #333;
    }

    .cv {
      max-width: 1000px;   /* the right side of the cv in which objectives are written BG color */
      margin: auto;
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
    }

    .header {/*the top of the cv in which the colors are in white and blue */
      background: linear-gradient(90deg, #e3f2fd, #bbdefb);
      padding: 40px;
      text-align: center;
    }

    .photo {/* the photo section shadows */
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 6px solid white;
      box-shadow: 0 5px 15px rgba(255, 0, 0, 0.2);
    }

    .name {/* the name section */
      font-size: 42px;
      margin: 10px 0 5px;
      color: #0d47a1;
    }

    .title {/* the title section where BS AI is written*/
      font-size: 22px;
      color: #1565c0;
      margin-bottom: 20px;
    }

    .content {   /* the main content area with left and right sections */
      display: flex;
      flex-wrap: wrap;
    }

    .left {   /* the left side of the cv with personal info, skills, and languages */
      flex: 1;
      background: #f9fbfc;
      padding: 35px;
      min-width: 280px;
    }

    .right {   /* the right side of the cv with objectives, education, and experience */
      flex: 2;
      padding: 35px;
      min-width: 300px;
    }

    .section {   /* section headers like SKILLS, LANGUAGES, OBJECTIVE, EDUCATION */
      font-size: 20px;
      color: #1565c0;
      border-bottom: 3px solid #42a5f5;
      padding-bottom: 8px;
      margin: 25px 0 15px;
    }

    .info {
      display: flex;
      align-items: center;
      margin-bottom: 15px;
      font-size: 16px;
    }

    .info i {
      width: 30px;
      color: #42a5f5;
      font-size: 20px;
    }

    ul {
      padding-left: 20px;
      margin: 10px 0;
    }

    li {
      margin-bottom: 7px;
    }

    .job {
      margin-bottom: 25px;
    }

    .job-title {
      color: #1565c0; /* Removed font-weight: bold; as <b> will handle it */
      font-size: 17px;
    }

    .company {
      font-weight: 500;
    }

    .date {
      float: right;
      color: #42a5f5;
      font-weight: 500;
    }

    @media (max-width: 768px) {
      .content {
        flex-direction: column;
      }
      .date {
        float: none;
      }
    }
  </style>
</head>
<body>

  <div class="cv">
    <div class="header">
      <img src="C:\Users\Dell\Desktop\HAR.png" alt="Huzaifa" class="photo">
      <h1 class="name">HUZAIFA ABDUL RAHMAN</h1>
      <p class="title">BS ARTIFICIAL INTELLIGENCE STUDENT</p>
    </div>

    <div class="content">
      <div class="left">
        <div class="info"><i class="fas fa-user"></i><p>Male</p></div>
        <div class="info"><i class="fas fa-calendar-alt"></i><p>Born 2006</p></div>
        <div class="info"><i class="fas fa-phone"></i><p>+92 318 8140889</p></div>
        <div class="info"><i class="fas fa-envelope"></i><p>huzaifaabdulrahman76@gmail.com</p></div>
        <div class="info"><i class="fas fa-map-marker-alt"></i><p>Hazro, District Attock, Pakistan</p></div>
        <div class="section">SKILLS</div>
        <ul>
          <li><b>Strong Computer Knowledge</b></li>
          <li><b>Programming Fundamentals</b></li>
          <li><b>Artificial Intelligence Basics</b></li>
          <li><b>Microsoft Office</b> (Word, Excel, PowerPoint)</li>
          <li><b>Internet Research & Typing</b></li>
        </ul>

        <div class="section">LANGUAGES</div>
        <ul>
          <li><b>English</b> (Fluent)</li>
          <li><b>Urdu</b> (Native)</li>
          <li><b>Punjabi</b> (Fluent)</li>
          <li><b>Pashto</b> (Native)</li>
        </ul>
      </div>

      <div class="right">
        <div class="section">OBJECTIVE</div>
        <p>To obtain an internship or entry-level position in <b>Artificial Intelligence</b>, <b>Software Development</b>, or <b>IT</b> where I can apply my academic knowledge, strong computer skills, and passion for technology. Eager to contribute to innovative projects while further developing practical experience in <b>AI</b> and <b>programming</b>.</p>

        <div class="section">EDUCATION</div>
        <div class="job">
          <div class="job-title"><b>Bachelor of Science in Artificial Intelligence</b></div>
          <div class="company">Air University, Kamra Campus</div>
          <span class="date">2025 – Present</span>
        </div>

        <div class="job">
          <div class="job-title"><b>FSc Pre-Engineering (ICS - Computer Science)</b></div>
          <div class="company">Scholars College</div>
          <span class="date">2023 – 2024</span>
          <p><b>Grade:</b> 81%</p>
        </div>

        <div class="job">
          <div class="job-title"><b>Matriculation (Computer Science)</b></div>
          <div class="company">MRF Kamra</div>
          <span class="date">2022 – 2023</span>
          <p><b>Grade:</b> 79%</p>
        </div>

        <div class="section">INTERESTS</div>
        <ul>
          <li><b>Artificial Intelligence & Machine Learning</b></li>
          <li><b>Coding and Software Development</b></li>
          <li><b>Technology & Gadgets</b></li>
          <li><b>Reading Tech Blogs</b></li>
          <li><b>Cricket & Football</b></li>
        </ul>
      </div>
    </div>
  </div>

</body>
</html> 
