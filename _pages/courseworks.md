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
      margin: 15px 0;
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
      width: 220px;
      background-color: black;
      color: #fff;
      text-align: left;
      border-radius: 5px;
      padding: 5px;
      position: absolute;
      z-index: 1;
      bottom: 125%; /* Position the tooltip above the icon */
      left: 50%;
      margin-left: -120px; /* Center the tooltip */
      opacity: 0;
      transition: opacity 0.3s;
      font-size: 11px;
      font-family: Arial, sans-serif;
    }
    .tooltip i {
      font-size: 12px;
    }
    .tooltip:hover .tooltiptext {
      visibility: visible;
      opacity: 1;
    }
    .button-container {
      display: block;
    }
    .button {
      flex: 1 1 auto; /* 按钮自动调整宽度 */
      margin: 2px; /* 按钮之间的间距 */
    }
  </style>
</head>

<body>
  <p>You can find all my enrolled courses in CUHK-Shenzhen here, some course assignments or projects are also available.</p>
  <div class="button-container">
    <button class="button" onclick="filterBoxes('all')">Show All</button>
    <button class="button" onclick="filterBoxes('core')">Starred</button>
    <button class="button" onclick="filterBoxes('mr')">Major Requires</button>
    <button class="button" onclick="filterBoxes('me')">Major Electives</button>
    <button class="button" onclick="filterBoxes('ge')">General Educations</button>
    <button class="button" onclick="filterBoxes('fe')">Free Electives</button>
    <span class="tooltip">
      <i class="fas fa-info-circle">About grading?</i>
      <span class="tooltiptext">A, A-, ..., D, F stands for grade points 4.0, 3.7, ..., 1.0, 0.0;<br>DI(distinction), PA(pass), FA(failure) will not be counted in GPA;<br>DI may be unavaibale in some of P/F courses.</span>
    </span>
    <br>
    <button class="button" onclick="filterBoxes('22f')">22 Fall</button>
    <button class="button" onclick="filterBoxes('23s')">23 Spring</button>
    <button class="button" onclick="filterBoxes('23m')">23 Summer</button>
    <button class="button" onclick="filterBoxes('23f')">23 Fall</button>
    <button class="button" onclick="filterBoxes('24s')">24 Spring</button>
    <button class="button" onclick="filterBoxes('24f')">24 Fall</button>
    <button class="button" onclick="filterBoxes('25s')">25 Spring</button>
    <button class="button" onclick="filterBoxes('25f')">25 Fall</button>
    <button class="button" onclick="filterBoxes('26s')">26 Spring</button>
  </div>
  
  <div id="enroll-grade-container">
    <div class="enroll-grade-box 22f mr">
      <h3>CSC1001 - Introduction to Computer Science: Programming Methodology</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Programming with Python, basics of data structures, basics of algorithm designing.</p>
      <p><b>Course Assignments Available</b>: <a href="https://github.com/frankchenfu/CUHKSZ_CSC1001">https://github.com/frankchenfu/CUHKSZ_CSC1001</a></p>
    </div>
    <div class="enroll-grade-box 22f mr">
      <h3>MAT1001 - Calculus I</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the definition and calculation of single variable limits, derivatives, and integrations.</p>
    </div>
    <div class="enroll-grade-box 22f mr core">
      <h3>MAT2041 - Linear Algebra and Applications</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing vector and matrix operations, matrix decompositions, basic linear transformation and linear spaces.</p>
    </div>
    <div class="enroll-grade-box 22f ge">
      <h3>CHI1000 - Chinese</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning and appreciating modern Chinese poetry, prose and novels.</p>
    </div>
    <div class="enroll-grade-box 22f ge">
      <h3>ENG1001 - English Bridge Program (EBP)</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning basic English reading, speaking, and writing ability.</p>
      <p><b>Course Assignments Available</b>: <a href="../files/ENG1001/expressive-essay.docx">Expressive Essay</a> | <a href="../files/ENG1001/responsive-essay.docx">Responsive Essay</a> | <a href="../files/ENG1001/presentation-slides.pptx">Presentation (Slides)</a></p>
    </div>
    <div class="enroll-grade-box 22f ge">
      <h3>PED1001 - Physical Education</h3>
      <p><b>Enrolled in 2022 Fall Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Volleyball skills</p>
    </div>
    <div class="enroll-grade-box 23s mr">
      <h3>CSC1002 - Computational Laboratory</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Better Python programming with PEP-8 standards, hands-on experience of large program development and debugging.</p>
      <p><b>Course Projects Available</b>: <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A1">Chinese Slider Puzzle</a> | <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A2">Connect Four</a> | <a href="https://github.com/frankchenfu/CUHKSZ_CSC1002_A3">Snake</a></p>
    </div>
    <div class="enroll-grade-box 23s mr">
      <h3>CSC3100 - Data Structure</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning data structures, including linear structures (linked list, stack, queue), tree structures (binary trees, heap, BST, balanced trees), graph structures, etc; Learning Java programming.</p>
    </div>
    <div class="enroll-grade-box 23s mr">
      <h3>MAT1002 - Calculus II</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the definition and calculation of multivariable limits, derivatives, and integrations.</p>
    </div>
    <div class="enroll-grade-box 23s mr">
      <h3>DDA2001 - Introduction to Data Science</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">PA</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the areas of data science, including operations researches (OR), optimizations, CV, NLP, robotics, bioinformatics, etc.</p>
      <p><b>Course Assignments Available</b>: <a href="../files/DDA2001/presentation_slides.pptx">Presentation (Slides)</a> | <a href="../files/DDA2001/term-paper.pdf">Term Paper</a></p>
    </div>
    <div class="enroll-grade-box 23s mr">
      <h3>PHY1001 - Mechanics</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the foundamental of physics, especially in basic mechanics such as work and momentum.</p>
    </div>
    <div class="enroll-grade-box 23s ge">
      <h3>ENG1002 - English for Academic Purposes I (EAP-1)</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning reading and writing academic articles in English.</p>
      <p><b>Course Assignments Available</b>: <a href="../files/ENG1002/argumentative-essay.docx">Argumentative Essay</a> | <a href="../files/ENG1002/cause-and-effect-essay.docx">Cause & Effect Essay</a> | <a href="../files/ENG1002/presentation-slides.pptx">Presentation (Slides)</a></p>
    </div>
    <div class="enroll-grade-box 23s ge">
      <h3>GFN1000 - In Dialogue with Nature</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the history and developments of nature science, from Plato, Euclid to Darwin, Watson and Crick.</p>
      <p><b>Course Assignments Available</b>: <a href="../files/GFN1000/presentation-draft.docx">Short Presentation (Draft)</a> | <a href="../files/GFN1000/mindmap.pdf">Course Mindmap</a> | <a href="../files/GFN1000/reflective-journal.docx">Reflective Journal</a> | <a href="../files/GFN1000/term-paper.docx">Term Paper</a></p>
    </div>
    <div class="enroll-grade-box 23s ge">
      <h3>PED1002 - Fitness and Health</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Basketball skills</p>
    </div>
    <div class="enroll-grade-box 23s ge">
      <h3>ITE1000 - Information Technology</h3>
      <p><b>Enrolled in 2023 Spring Term | Credits: 1.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">DI</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Basketball skills</p>
    </div>
    <div class="enroll-grade-box 23m me core">
      <h3>MAT3007 - Optimization</h3>
      <p><b>Enrolled in 2023 Summer Special Session | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing optimization problems, solving convex optimization, simplex method, KKT conditions, branch-and-bound integer programming.</p>
    </div>
    <div class="enroll-grade-box 23f mr">
      <h3>CSC3001 - Discrete Mathematics</h3>
      <p><b>Enrolled in 2023 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning logical operations, set theory, combinational mathematics, inductive and deductive methods, graph theory and proofs.</p>
    </div>
    <div class="enroll-grade-box 23f mr">
      <h3>CSC3002 - C/C++ Programming</h3>
      <p><b>Enrolled in 2023 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning features of C/C++ languages, better understanding and experience of OOP, memory management</p>
    </div>
    <div class="enroll-grade-box 23f mr core">
      <h3>DDA3020 - Machine Learning</h3>
      <p><b>Enrolled in 2023 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing theories of machine learning; Learning SVM, regression models, clustering methods, neoron networks and basic CNN, RNN designs, dimension reductions <b>and their methematical derivations in the probabilistic perspective</b>; Gain expeience with packages such as <code>Scikit-Learning</code>, <code>PyTorch</code>, and large dataset preprocessing.</p>
    </div>
    <div class="enroll-grade-box 23f fe core">
      <h3>DDA2081 - Independent Studies I</h3>
      <p><b>Enrolled in 2023 Fall Term | Credits: 2.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Contribute to a research which is published afterwards.</p>
    </div>
    <div class="enroll-grade-box 23f mr core">
      <h3>STA2003 - Probability</h3>
      <p><b>Enrolled in 2023 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning the derivation of many probability theories, calculation of pmf/pdf, cdf, generating functions including mgf, multivatiable probabilities and joint distribution, CLT, etc.</p>
    </div>
    <div class="enroll-grade-box 23f fe core">
      <h3>MAT3040 - Advanced Linear Algebra</h3>
      <p><b>Enrolled in 2023 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p>Remark: Free elective course, originally for math major students.</p>
      <p><b>Learning Outcomes</b>: Gaining more general understanding of vector spaces, learning product/quotient spaces, annihilators, dual spaces, Jordan normal form, characteristic polynomials, essense of determinants, etc.</p>
    </div>
    <div class="enroll-grade-box 23f mr">
      <h3>BIO1008 - Chemistry and Life Science</h3>
      <p><b>Enrolled in 2023 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing more biochemistry knowledges including organic chemistry, biological features of human body.</p>
    </div>
    <div class="enroll-grade-box 23f ge">
      <h3>ENG2001 - English for Academic Purposes II (EAP-2)</h3>
      <p><b>Enrolled in 2023 Fall Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Gaining more advanced skills in academic writings; Conducting a mini-research in humanity science area and writing a research paper with presentation.</p>
      <p><b>Course Assignments Available</b>: <a href="../files/ENG2001/public-speaking-draft.docx">Public Speaking (Draft)</a> | <a href="../files/ENG2001/research-proposal.docx">Research Proposal</a> | <a href="../files/ENG2001/research-presentation.pptx">Research Paper (Presentation Slides)</a> | <a href="../files/ENG2001/research-paper.docx">Research Paper</a></p>
    </div>
    <div class="enroll-grade-box 24s mr">
      <h3>CSC3170 - Database System</h3>
      <p><b>Enrolled in 2024 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing data storing structures; Learning normal forms of data representations, data mining with databases; Familiar with SQL programming.</p>
    </div>
    <div class="enroll-grade-box 24s mr">
      <h3>CSC4001 - Software Engineering</h3>
      <p><b>Enrolled in 2024 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing testing workflow (UUT, system testing, etc.) and skills (differential testing, metamorphic testing, etc.); Learning dataflow analyses and its usage in software testing.</p>
    </div>
    <div class="enroll-grade-box 24s mr">
      <h3>ECE2050 - Digital Logic and Systems</h3>
      <p><b>Enrolled in 2024 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing basic digital logic, circuit design, and hardware structure design; Learning to use basic electronic devices (flip-flops, registers, etc.).</p>
    </div>
    <div class="enroll-grade-box 24s fe">
      <h3>STA2004 - Mathematical Statistics</h3>
      <p><b>Enrolled in 2024 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p>Remark: Free elective course, originally for statistics major students.</p>
      <p><b>Learning Outcomes</b>: Learning the calculation of basic statistics (covariance, etc.), estimators (especially MLE), confidence interval, all sorts of hypothesis testing (parametric and non-parametric).</p>
    </div>
    <div class="enroll-grade-box 24s ge">
      <h3>ENG2002S - English for Science and Engineering</h3>
      <p><b>Enrolled in 2024 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a-minus">A-</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Learning to write technical proposals (with presentation); Trying to write cover letters and CVs.</p>
      <p><b>Course Assignments Available</b>: <a href="../files/ENG2002S/technical-proposal-slides.pptx">Technical Proposal (Presentation Slides)</a> | <a href="../files/ENG2002S/technical-proposal.docx">Technical Proposal</a> | <a href="../files/ENG2002S/cover-letter-practice.pdf">Cover Letter Practice</a> | <a href="../files/ENG2002S/resume-writing-practice.pdf">CV Practice</a></p>
    </div>
    <div class="enroll-grade-box 24s ge">
      <h3>GFH1000 - In Dialogue with Humanity</h3>
      <p><b>Enrolled in 2024 Spring Term | Credits: 3.0 | Grade:
      <span class="right-content">
        <span class="grades"><span class="grade-icon a">A</span></span>
      </span></b></p>
      <p><b>Learning Outcomes</b>: Knowing the history and developments of humanity, from Aristotle to Rousseau.</p>
      <p><b>Course Assignments Available</b>: <a href="../files/GFH1000/rj-aristotle.docx">Reflective Journal I - Aristotle</a> | <a href="../files/GFH1000/rj-rousseau.docx">Reflective Journal II - Rousseau</a> | <a href="../files/GFH1000/presentation.pptx">Presentation (Slides)</a> | <a href="../files/GFH1000/term-paper.docx">Term Paper</a></p>
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