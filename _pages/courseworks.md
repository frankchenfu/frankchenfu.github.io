---
layout: archive
title: "Course Works"
permalink: /courseworks/
author_profile: true
redirect_from:
  - /course-works
  - /coursework
  - /coursework
---

{% include base_path %}

<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    .button {
      font-family: 'Comic Sans MS', sans-serif;
      display: inline-block;
      padding: 6px 12px;
      font-size: 14px;
      font-weight: bold;
      text-align: center;
      text-decoration: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      /* 其他样式，如背景颜色、边框等根据需要添加 */
    }
    .button:hover {
      background-color: #57B6D0; /* 鼠标悬停时的背景色 */
      color: white; /* 鼠标悬停时的文字颜色 */
    }
    .enroll-grade-box {
      display: block;
      width: 100%;
      border: 2px solid #ccc; /* 边框颜色和粗细 */
      border-radius: 10px; /* 圆角半径 */
      margin: 10px 0;
      padding: 10px; /* 内边距 */
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      background-color: #f9f9f9;
      font-size: 14px; /* Adjust font size */
      line-height: 1.2; /* Adjust line height */
    }
    .enroll-grade-box h3 {
      margin-top: 0;
      font-size: 16px; /* Adjust font size for heading */
      line-height: 1.2; /* Adjust line height for heading */
    }
    /* Styling for each grade icon */
    .grade-icon {
      display: inline-block;
      width: 25px; /* Adjust size as needed */
      height: 25px; /* Adjust size as needed */
      border-radius: 50%;
      line-height: 20px; /* Adjust line-height to center text vertically */
      text-align: center;
      color: white;
      font-weight: bold;
      margin-left: 10px; /* Adjust spacing between grade icon and title */
    }
    .grades {
      display: inline-block; /* Ensure it stays on the same line */
    }
    .right-content {
      display: inline-block; /* Ensure it stays on the same line */
      vertical-align: middle; /* Align vertically */
    }
    /* Different background colors for each grade */
    .grade-icon.a { background-color: #4CAF50; } /* Green */
    .grade-icon.a-minus { background-color: #90C36A; } /* Light Green */
    .grade-icon.b-plus { background-color: #CDDC39; } /* Lime */
    .grade-icon.b { background-color: #FFEB3B; } /* Yellow */
    .grade-icon.b-minus { background-color: #FFC107; } /* Amber */
    .grade-icon.c-plus { background-color: #FF9800; } /* Orange */
    .grade-icon.c { background-color: #FF5722; } /* Deep Orange */
    .grade-icon.c-minus { background-color: #F44336; } /* Red */
    .grade-icon.d { background-color: #E91E63; } /* Pink */
    .grade-icon.f { background-color: #9C27B0; } /* Purple */
    .tooltip {
      position: relative;
      display: inline-block;
      cursor: pointer;
    }
    .tooltip .tooltiptext {
      visibility: hidden;
      width: 180px;
      background-color: black;
      color: #fff;
      text-align: center;
      border-radius: 5px;
      padding: 5px;
      position: absolute;
      z-index: 1;
      bottom: 125%; /* Position the tooltip above the icon */
      left: 50%;
      margin-left: -90px; /* Center the tooltip */
      opacity: 0;
      transition: opacity 0.3s;
      font-size: 11px;
      font-family: Arial, sans-serif;
    }
    .tooltip i {
      font-size: 12px; /* 调整信息图标的字体大小 */
      font-family: Arial, sans-serif;
    }
    .tooltip:hover .tooltiptext {
      visibility: visible;
      opacity: 1;
    }
  </style>
</head>

<body>
  <p>You can find all my enrolled courses in CUHK-Shenzhen here, some course assignments or projects are also available.</p>
  <button class="button" onclick="filterBoxes('all')">Show All</button>
  <button class="button" onclick="filterBoxes('core')">Core Courses</button>
  <button class="button" onclick="filterBoxes('mr')">Major Requires</button>
  <button class="button" onclick="filterBoxes('me')">Major Electives</button>
  <button class="button" onclick="filterBoxes('ge')">General Educations</button>
  <button class="button" onclick="filterBoxes('fe')">Free Electives</button>
  <span class="tooltip">
    <i class="fas fa-info-circle">About grading?</i>
    <span class="tooltiptext">A, A-, ..., D, F stands for grade points 4.0, 3.7, ..., 1.0, 0.0; DI(distinction), PA(pass), FA(failure) will not be counted in GPA, and DI may be unavaibale in some of P/F courses.</span>
  </span>
  <div id="enroll-grade-container">
    <div class="enroll-grade-box mr">
      <h3>CSC1001 - Introduction to Computer Science: Programming Methodology</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Programming with Python, basics of data structures, basics of algorithm designing.</p>
      <p><b>Course Assignments</b>: <a href="https://github.com/frankchenfu/CUHKSZ_CSC1001">https://github.com/frankchenfu/CUHKSZ_CSC1001</a></p>
    </div>
    <div class="enroll-grade-box mr">
      <h3>MAT1001 - Calculus I</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the definition and calculation of single variable limits, derivatives, and integrations.</p>
    </div>
    <div class="enroll-grade-box mr">
      <h3>MAT2041 - Linear Algebra and Applications</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing vector and matrix operations, matrix decompositions, basic linear transformation and linear spaces.</p>
    </div>
    <div class="enroll-grade-box ge">
      <h3>CHI1000 - Chinese</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning and appreciating modern Chinese poetry, prose and novels.</p>
    </div>
    <div class="enroll-grade-box ge">
      <h3>ENG1001 - English Bridge Program (EBP)</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning basic English reading, speaking, and writing ability.</p>
    </div>
    <div class="enroll-grade-box ge">
      <h3>PED1001 - Physical Education</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Volleyball skills</p>
    </div>
    <div class="enroll-grade-box mr">
      <h3>CSC1002 - Computational Laboratory</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Better Python programming with PEP-8 standards, hands-on experience of large program development and debugging.</p>
      <p><b>Course Projects</b>: <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A1">Chinese Slider Puzzle</a>, <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A2">Connect Four</a>, and <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A3">Snake</a></p>
    </div>
    <div class="enroll-grade-box mr">
      <h3>CSC1002 - Computational Laboratory</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Better Python programming with PEP-8 standards, hands-on experience of large program development and debugging.</p>
      <p><b>Course Projects</b>: <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A1">Chinese Slider Puzzle</a>, <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A2">Connect Four</a>, and <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A3">Snake</a></p>
    </div>
    <div class="enroll-grade-box mr">
      <h3>CSC3100 - Data Structure</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning data structures, including linear structures (linked list, stack, queue), tree structures (binary trees, heap, BST, balanced trees), graph structures, etc.</p>
    </div>
    <div class="enroll-grade-box mr">
      <h3>MAT1002 - Calculus II</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the definition and calculation of multivariable limits, derivatives, and integrations.</p>
    </div>
    <div class="enroll-grade-box mr">
      <h3>DDA2001 - Introduction to Data Science</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">PA</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the areas of data science, including operations researches (OR), optimizations, CV, NLP, robotics, bioinformatics, etc.</p>
    </div>
    <div class="enroll-grade-box mr">
      <h3>PHY1001 - Mechanics</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">PA</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the foundamental of physics, especially in basic mechanics such as work and momentum.</p>
    </div>
    <div class="enroll-grade-box ge">
      <h3>ENG1002 - English for Academic Purposes I (EAP-1)</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning reading and writing academic articles in English.</p>
    </div>
    <div class="enroll-grade-box ge">
      <h3>GFN1000 - In Dialogue with Nature</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the history and developments of nature science, from Plato, Euclid to Darwin, Watson and Crick.</p>
    </div>
    <div class="enroll-grade-box ge">
      <h3>PED1002 - Fitness and Health</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Basketball skills</p>
    </div>
    <div class="enroll-grade-box ge">
      <h3>ITE1000 - Information Technology</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">DI</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Basketball skills</p>
    </div>
  </div>

  <script>
    function filterBoxes(tag) {
      var boxes = document.querySelectorAll('.enroll-grade-box');

      boxes.forEach(function(box) {
        if (tag === 'all' || box.classList.contains(tag)) {
          box.style.display = 'inline-block';
        } else {
          box.style.display = 'none';
        }
      });
    }
  </script>
</body>