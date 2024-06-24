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
  <style>
    .enroll-grade-box {
      display: inline-block;
      border: 2px solid #ccc; /* 边框颜色和粗细 */
      border-radius: 10px; /* 圆角半径 */
      padding: 10px; /* 内边距 */
    }
    /* Styling for each grade icon */
    .grade-icon {
      display: inline-block;
      width: 30px; /* Adjust size as needed */
      height: 30px; /* Adjust size as needed */
      border-radius: 50%;
      line-height: 25px; /* Adjust line-height to center text vertically */
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
    .grade-icon.a-minus { background-color: #8BC34A; } /* Light Green */
    .grade-icon.b-plus { background-color: #CDDC39; } /* Lime */
    .grade-icon.b { background-color: #FFEB3B; } /* Yellow */
    .grade-icon.b-minus { background-color: #FFC107; } /* Amber */
    .grade-icon.c-plus { background-color: #FF9800; } /* Orange */
    .grade-icon.c { background-color: #FF5722; } /* Deep Orange */
    .grade-icon.c-minus { background-color: #F44336; } /* Red */
    .grade-icon.d { background-color: #E91E63; } /* Pink */
    .grade-icon.f { background-color: #9C27B0; } /* Purple */
  </style>
</head>

<body>
  <button class="filter-btn" onclick="filterBoxes('all')">Show All</button>
  <button class="filter-btn" onclick="filterBoxes('mr')">Show Major Requires</button>
  <button class="filter-btn" onclick="filterBoxes('me')">Show Major Electives</button>
  <button class="filter-btn" onclick="filterBoxes('ge')">Show General Educations</button>
  <button class="filter-btn" onclick="filterBoxes('fe')">Show Free Electives</button>
  <div id="enroll-grade-container">
    <div class="enroll-grade-box mr">
      <h3>CSC1001 Introduction to Computer Science: Programming Methodology</h3>
      <p>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></p>
      <p>Learning Outcomes: Programming with Python, basics of data structures, basics of algorithm designing.
      <p>Course Assignments: <a href="https://github.com/frankchenfu/CUHKSZ_CSC1001">https://github.com/frankchenfu/CUHKSZ_CSC1001</a></p>
    </div>
    <div class="enroll-grade-box me">
      <h3>CSC1002 Introduction to Computer Science: Programming Methodology</h3>
      <p>Enrolled in 2022 Fall Spring | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></p>
      <p>Learning Outcomes: Better Python programming with PEP8 standards, hands-on experience of large program development and debugging.
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