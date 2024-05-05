# GSFC-In-house-library-project
An HTML and CSS-based project of an Inhouse library for GSFC university 
<!DOCTYPE html>
<html>

<head>
    <title>
        In House Library
    </title>
    <style>
        header,
        footer {
            background-color: #333;
            color: white;
            padding: 0%;
            text-align: center;
        }
        
        ul {
            list-style-type: none;
            margin: 10;
            padding: 2;
            overflow: hidden;
            background-color: #4d769a;
        }
        
        li {
            float: left;
        }
        
        li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 15px;
            text-decoration: none;
        }
        
        li a:hover {
            background-color: rgb(61, 154, 103);
        }
        
        button {
            background-color: #a94d50;
            border: none;
            border-radius: 20px;
            color: white;
            padding: 20px 30px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 20px 0;
            cursor: pointer;
        }
        
        th {
            padding-right: 100px;
        }
        
        .dropbtn {
            background-color: #a94d50;
            border: none;
            border-radius: 20px;
            color: white;
            padding: 20px 30px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 20px 0;
            cursor: pointer;
        }
        
        .dropdown {
            position: relative;
            display: inline-block;
        }
        
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #6391BA;
            min-width: 160px;
            z-index: 1;
        }
        
        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }
        
        .dropdown-content a:hover {
            background-color: #f1f1f1
        }
        
        .dropdown:hover .dropdown-content {
            display: block;
        }
        
        .dropdown:hover .dropbtn {
            background-color: #3e8e41;
        }
        
        h3 {
            background-image: url("C:/Users/dhruv/Desktop/HTML_PICS/GSFC_image-2.jpeg");
            background-repeat: no-repeat;
            background-size: cover;
            background-attachment: fixed;
        }
    </style>
    <!--website icon-->
    <link rel="icon" type="image/x-icon" href="C:\Users\dhruv\Desktop\HTML_PICS\in_house_library.ico">
</head>

<body style="background-color:#95b9d9;">

    <header>
        <h1 style="text-align:center; color:#a94d50; font-size:45px;">Welcome to the Inhouse Library</h1>
    </header>
    <hr>
    <!--navigation bar-->
    <ul>
        <li><a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\nav_bar_books.html">Books</a></li>
        <li><a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\nav_bar_articles.html">Articles</a></li>
        <li><a href="https://www.gsfcuniversity.ac.in/about-gsfcu">About Us</a></li>
    </ul>
    <p style="text-align:center; font-size:30px"><b><i>A page for reviewing and retriving Articals,Books and Information for Readers and Thinkers </i></b></p>
    <i>
        <h3 style="Font-size:100px; font-family:'Times New Roman', Times, serif;text-align:center; color:#8e3f41">
            GSFC <br>
            University<br>
            Education Re-Envisioned<br>
            <p style="font-size:35px">AN ISO 9001:2015 Certified University</p> 
        </h3>
    </i>
    <!--buttons-->
    <center>
        <table>
            <tr>
                <th>
                    <div class="dropdown">
                        <button class="dropbtn">Books</button>
                        <div class="dropdown-content">
                            <a href="computer_science_books.html">B.Tech Computer Science</a>
                            <a href="chemical_books.html">B.Tech Chemical Engineering</a>
                            <a href="FEHS_books.html">B.Tech Fire and Enviroment, Health, Safety</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\computer_science_books.html">M.Tech Computer Science</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\computer_science_books.html">PHD.Computer Science</a>
                            <!--
                            <a href="SOS_BSC.html">BSC Books</a>
                            <a href="SOS_BCA.html">BCA Books</a>
                            <a href="SOS_MSC.html">MSC Books</a>
                            <a href="SOS_PHD.html">PHD Books</a>
                            <a href="SOM_BBA.html">BBA books</a>
                            <a href="SOM_BCOM.html">BCOM books</a>
                            <a href="SOM_BA.html">BA Books</a>
                            <a href="SOM_MBA.html">MBA Books</a>
                            <a href="SOM_PHD.html">PHD Management</a>
                            -->
                        </div>
                    </div>
                </th>
                <th>
                    <div class="dropdown">
                        <button class="dropbtn">Articles</button>
                        <div class="dropdown-content">
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\Quantum_computer_article.html">Quantum computers</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\block_chain.html">Block Chain technology</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\cloud_computing_VS_dicsripted_computing.html">Cloud computing VS Distributed Computing </a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\healthy_living.html">Healthy Living</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\medical_science.html">Medical Science</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\quantum_physics.html">Quantum Physics</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\computer_science.html">Computer Science</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\technology.html">Technology</a>
                        </div>
                    </div>
                </th>
                <th>
                    <div class="dropdown">
                        <button class="dropbtn">Research papers</button>
                        <div class="dropdown-content">
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\upcoing_theories_IH.html">Upcoming Theoires</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\mordern_science_IHL.html">Mordern Science</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\quantum_science_IHL.html">Quantum science</a>
                            <a href="C:\TURBOC3\BIN\PROJECT\.vscode\HTML_PRCTICE\medical_discooveries_IHL.html">Medical Discoveries</a>
                        </div>
                    </div>
                </th>
                <th>
                    <div class="dropdown">
                        <button class="dropbtn">Current Trends</button>
                        <div class="dropdown-content">
                            <a href="https://news.google.com/search?q=computer%20science&hl=en-IN&gl=IN&ceid=IN%3Aen">Computer Science</a>
                            <a href="https://news.google.com/search?q=software%20conpanies&hl=en-IN&gl=IN&ceid=IN%3Aen">Software Companies</a>
                            <a href="https://news.google.com/topics/CAAqJAgKIh5DQkFTRUFvSEwyMHZNRzFyZWhJRlpXNHRSMElvQUFQAQ?hl=en-IN&gl=IN&ceid=IN%3Aen">AI</a>
                            <a href="https://news.google.com/search?q=new%20discoveries&hl=en-IN&gl=IN&ceid=IN%3Aen">New discoveries</a>
                        </div>
                    </div>
                </th>
            </tr>
        </table>
    </center>
    <!--form here the descriptive part of the web page starts-->
    <p style="font-size:50px; font-family:'Lucida Sans'; text-align:center"><i>Here we represent your Branches</i></p>
    <p style="text-align:center; font-size:35px; color:rgb(10, 82, 10)"><strong>School Of Technology</strong></p>
    <!--CSE-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.Tech Computer Science Engineering</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Augmenting cutting edge skills is the core determination of GSFC University. To supplement and nourish these skills, strong industrial support is a vital agent. Students at GSFC University receive a unique opportunity in the form of hands-on training
        at industries besides the classroom learning that empower them for their career development in multiple ways. The Computer Science Engineering program at GSFC University emphasizes on providing core fundamental knowledge along with practical and
        hands-on experience and an exposure to entrepreneurship & research.<br><br>This program focuses on Holistic development of the students by participating in the co-curricular and extra-curricular activities organized through different Student Managed
        Clubs and Student Chapters Continuous Grooming of students by Developing Soft Skills, Preparing for Placements, Preparing for Competitive Exams by arranging special sessions and through Foundation Course & Bridge Course.<br><br>Computer Science
        & Engineering is continuously evolving and adapting to new developments in science and technology. The knowledge of the emerging technology is essential for any Computer Engineer in addition to the fundamental subjects of classical Computer Science
        Engineering
        <br><br>To impart the cutting edge knowledge Computer Science & Engineering program has revamped and offers three specializations in:<br><br> 1. Data science, Artificial intelligence and Machine Learning <br><br> 2. IOT and Automation <br><br>        3. Cyber Security
    </p>
    <a href="https://www.gsfcuni.edu.in/btech-computer-science-and-engineering-program">Know more!!!....</a>
    <!--Chemical-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.Tech Chemical Engineering </p>
    <p style="font-family:'Times New Roman'; font-size:20px;">The branch of Chemical Engineering deals with the chemical processes for manufacturing of different products, designing of equipment’s, fundamental understanding, and the technology of chemical, petroleum and petrochemicals, pharmaceuticals, fertilizers,
        foods and many other products.<br><br>The Chemical Engineering department at GSFC University focuses to develop Industry ready students for the futuristic areas in modeling and simulation, process control, reaction engineering, transfer operations,
        thermodynamics, renewable energy and so on. The department is well equipped with new state of art labs to boost up high quality research & learning activity. On the other hand, computational research activity of the department is also equally
        strong by the help of several software such as CHEMCAD, ASPEN Plus and MATLAB.
    </p>
    <a href="https://www.gsfcuni.edu.in/btech-chemical-engineering-program">Know more!!!....</a>
    <!--FESH-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.Tech Fire and Enviroment, health safety</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">GSFC University has started 4 years full time Bachelor degree program in Fire & Environment, Health, Safety. GSFC University is first private University to start this program in Gujarat in the year 2019.<br><br>GSFC University found that the subject
        of Fire & Safety has become very important in view of rapid industrialization, development of new technology and consequent enactment of various legislation for ensuring safety & security of the property & life. There are very few engineering
        colleges/institutes in India where the course in Fire & Safety courses are available with proper infrastructure facilities.<br><br>GSFC University being a CSR initiative of GSFC Ltd that has Fire station, Fire tenders, Skilled & professionals
        in the field of Fire & Environment, Health, Safety provides the right environment for creating Industry ready Fire & EHS engineers to the society.
    </p>
    <a href="https://www.gsfcuni.edu.in/btech-fire-and-safety-engineering-program">Know more!!!....</a>
    <!--M.Tech-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">M.Tech Computer Science</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">1. M.Tech (CSE) in Data Science, AI And ML<br><br> 2. M.Tech (CSE) in IoT & Automation<br><br>Augmenting cutting edge skills is the core determination of GSFC University. To supplement and nourish these skills, strong industrial support is a vital
        agent. Students at GSFC University receive a unique opportunity in the form of hands-on training at industries besides the classroom learning that empower them for their career development in multiple ways. The M.Tech Computer Science and Engineering
        program at GSFC University emphasizes on providing core fundamental knowledge along with practical and hands-on experience and an exposure to industrial centric dissertation projects.<br><br>To impart the cutting edge knowledge Computer Science
        & Engineering program has revamped and offers three specializations in:<br><br> 1. Data science, Artificial intelligence and Machine Learning<br><br> 2. IOT and Automation<br><br>State-of-the-art Research Laboratories such as, 1. Supercomputer
        Lab (PARAM Shavak DL-GPU) & Design IoT Lab, sponsored and supported by Gujarat Council on Science & Technology (GUJCOST), Department of Science & Technology ( DST), 2. Robotics & Automation Lab, 3. e-Yantra Lab setup in collaboration with IIT
        Bombay.
        <br><br>Specialized laboratories for each specializations opted as elective along with the laboratories for core subjects.<br><br>Digital Campus System and Digital Library to access e-resources. High Tech classrooms with Digital Podium and Well-Equipped
        Laboratories
    </p>
    <a href="https://www.gsfcuni.edu.in/mtech-computer-science-and-engineering-program">Know more!!!....</a>
    <!--PHD computer science-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">PH.D. Computer Science</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">The Ph.D. Computer Science and Engineering program at the School of Technology, GSFC University adheres to the guidelines set forth by the University Grants Commission (UGC). This program is strategically designed to cultivate students with a profound
        understanding of research methodologies and analytical acumen. By emphasizing rigorous training, we aim to nurture individuals who possess exceptional capabilities to pursue Postdoctoral research opportunities or embark on successful careers in
        both industry and the public service.
    </p>
    <a href="https://www.gsfcuni.edu.in/phd-computer-science-and-engineering-program">Know more!!!....</a>
    <hr>
    <p style="text-align:center; font-size:35px; color:rgb(10, 82, 10)"><strong>School Of Science</strong></p>
    <!--BSC bio technology-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.SC(HONS.) Biotechnology</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Embark on an awe-inspiring voyage where the infinite possibilities of science intertwine with the realms of cutting-edge technology and ground-breaking engineering. As the world bears witness to an extraordinary surge of progress on both the national
        and global frontiers, the thirst for deep comprehension and practical application of fundamental sciences has reached unprecedented heights. At GSFC University, our unwavering dedication resonates through our unwavering pledge to maintain unparalleled
        academic excellence, ensuring a remarkable educational experience that sets new benchmarks.<br><br>Welcome to the esteemed School of Science at GSFC University, where we proudly present an awe-inspiring B.Sc. Biotechnology Program, meticulously
        crafted to align with the visionary National Education Policy (NEP) 2020. This program has been ingeniously designed, drawing inspiration from the revered "Curriculum and Credit Framework for Undergraduate Programs" recommended by the UGC. It
        seamlessly integrates a flexible choice-based credit system and an invigorating multidisciplinary approach, igniting a true passion for learning.<br><br>The B.Sc. Biotechnology Program spans over eight semesters (four years), strategically laying
        a strong foundational understanding of subjects, while delving into practical applications and recent developments. Every semester, students have the unique opportunity to immerse themselves in industrial internships, acquiring both theoretical
        knowledge and hands-on experience.<br><br>Our specialized Biotechnology courses cater to the demands of a dynamic industrial landscape, setting the stage for prosperous careers in research and development, industries, and academic institutions.
        Furthermore, the institute may provide placement opportunities to our aspiring graduates.<br><br>Our B.Sc. Biotechnology Program offers an array of degree options, allowing students to customize their academic journey according to their aspirations:<br><br>•
        3 Year B.Sc. Biotechnology <br><br>• 4 Year B.Sc. Biotechnology-Honours <br><br>• 4 Year B.Sc. Biotechnology-Honours with Research<br><br>Our specialized Biotechnology courses cater to the demands of a dynamic industrial landscape, setting the
        stage for prosperous careers in research and development, industries, and academic institutions. Furthermore, the institute may provide placement opportunities to our aspiring graduates.<br><br>As an epitome of academic excellence, GSFC University
        offers a seamless transition for our students to pursue a Master's Degree. Upon completing the four-year B.Sc. program, students have the remarkable opportunity to enrol in a One-Year Master's Program at the prestigious School of Science, GSFC
        University, propelling their educational journey to greater heights.
    </p>
    <a href="https://www.gsfcuni.edu.in/bsc-hons-biotechnology">Know more!!!....</a>
    <!--BSC chemisrty-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.SC(HONS.) Chemistry </p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Embark on a transformative journey where the boundless potential of science merges with the realms of technology and engineering. As the world witnesses rapid advancements on the national and international stage, the demand for profound understanding
        and application of basic sciences has never been greater. At GSFC University, we stand unwaveringly committed to upholding exceptional academic standards.<br><br>Welcome to the esteemed School of Science at GSFC University, where we proudly present
        an awe-inspiring B.Sc. Chemistry Program, meticulously crafted to align with the visionary National Education Policy (NEP) 2020. This program has been ingeniously designed, drawing inspiration from the revered "Curriculum and Credit Framework
        for Undergraduate Programs" recommended by the UGC. It seamlessly integrates a flexible choice-based credit system and an invigorating multidisciplinary approach, igniting a true passion for learning.<br><br>The B.Sc. Chemistry Program spans over
        eight semesters (four years), strategically laying a strong foundational understanding of subjects, while delving into practical applications and recent developments. Every semester, students have the unique opportunity to immerse themselves in
        industrial internships, acquiring both theoretical knowledge and hands-on experience.<br><br>Our specialized chemistry courses cater to the demands of a dynamic industrial landscape, setting the stage for prosperous careers in research and development,
        industries, and academic institutions. Furthermore, the institute may provide placement opportunities to our aspiring graduates.<br><br>Our B.Sc. Chemistry Program offers an array of degree options, allowing students to customize their academic
        journey according to their aspirations:<br><br>• 3 Year B.Sc. Chemistry<br><br> • 4 Year B.Sc. Chemistry-Honours<br><br>• 4 Year B.Sc. Chemistry-Honours with Research<br><br>Upon completion of the third year, students have the option to exit with
        a prestigious B.Sc. Chemistry Degree. However, for those seeking to delve deeper into their chosen field, the fourth year presents two distinct paths to explore. The first option allows students to specialize in their discipline, pursuing an Honours
        Degree that delves into comprehensive and in-depth studies within their major. Alternatively, for those with a thirst for research and an unwavering curiosity, the Honours with Research option opens doors to further academic exploration.<br><br>As
        an epitome of academic excellence, GSFC University offers a seamless transition for our students to pursue a Master's Degree. Upon completing the four-year B.Sc. program, students have the remarkable opportunity to enrol in a one-year Master's
        program at the prestigious School of Science, GSFC University, propelling their educational journey to greater heights.<br><br>
    </p>
    <a href="https://www.gsfcuni.edu.in/bsc-hons-chemistry">Know more!!!....</a>
    <!--BSC micro biology-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.SC(HONS.) Microbiology</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Embark on an extraordinary odyssey where the limitless power of science converges with the realms of technology and engineering. As the world witnesses an unprecedented surge of breakthroughs on the national and global stage, the hunger for a profound
        grasp of fundamental sciences and their practical applications has reached unprecedented heights. At GSFC University, our unwavering dedication to excellence fuels our relentless pursuit of academic brilliance, setting us apart as torchbearers
        of exceptional educational standards.<br><br>Welcome to the esteemed School of Science at GSFC University, where we proudly present an awe-inspiring B.Sc. Microbiology Program, meticulously crafted to align with the visionary National Education
        Policy (NEP) 2020. This program has been ingeniously designed, drawing inspiration from the revered "Curriculum and Credit Framework for Undergraduate Programs" recommended by the UGC. It seamlessly integrates a flexible choice-based credit system
        and an invigorating multidisciplinary approach, igniting a true passion for learning.<br><br>The B.Sc. Microbiology Program spans over eight semesters (four years), strategically laying a strong foundational understanding of subjects, while delving
        into practical applications and recent developments. Every semester, students have the unique opportunity to immerse themselves in industrial internships, acquiring both theoretical knowledge and hands-on experience.<br><br>Our specialized Microbiology
        courses cater to the demands of a dynamic industrial landscape, setting the stage for prosperous careers in research and development, industries, and academic institutions. Furthermore, the institute may provide placement opportunities to our
        aspiring gradua<br><br>Our B.Sc. Microbiology Program offers an array of degree options, allowing students to customize their academic journey according to their aspirations:<br><br>• 3 Year B.Sc. Microbiology<br><br>• 4 Year B.Sc. Microbiology-Honours<br><br>•
        4 Year B.Sc. Microbiology-Honours with Research<br><br>Upon completion of the third year, students have the option to exit with a prestigious B.Sc. Microbiology Degree. However, for those seeking to delve deeper into their chosen field, the fourth
        year presents two distinct paths to explore. The first option allows students to specialize in their discipline, pursuing an Honours Degree that delves into comprehensive and in-depth studies within their major. Alternatively, for those with a
        thirst for research and an unwavering curiosity, the Honours with Research option opens doors to further academic exploration.<br><br>As an epitome of academic excellence, GSFC University offers a seamless transition for our students to pursue
        a Master's Degree. Upon completing the four-year B.Sc. program, students have the remarkable opportunity to enrol in a One-Year Master's Program at the prestigious School of Science, GSFC University, propelling their educational journey to greater
        heights.
        <br><br>
    </p>
    <a href="https://www.gsfcuni.edu.in/bsc-hons-microbiology">Know more!!!....</a>
    <!--BSC datascience-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.SC. Datascience</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">In the era of the upcoming generation, DATA emerges as the ultimate embodiment of power, holding within its grasp the keys to control the world and unlock boundless potential for the human race. A harmonious fusion of Mathematics, Statistics, and
        Computer Science forms an extraordinary toolkit, empowering us to navigate the intricacies of real-life challenges with unparalleled precision. Unlocking the language of data through the utilization of our analytical prowess opens the gateway
        to a realm of limitless career opportunities and newfound employability, propelling us towards unprecedented professional growth.<br><br>Step into the prestigious School of Science at GSFC University, where we unveil an extraordinary B.Sc. Data
        Science Program that will leave you captivated. Immerse yourself in a meticulously crafted educational experience, carefully calibrated to harmonize with the visionary National Education Policy (NEP) 2020. This ingeniously designed program draws
        inspiration from the revered "Curriculum and Credit Framework for Undergraduate Programs" recommended by the UGC, seamlessly blending a flexible choice-based credit system with a dynamic multidisciplinary approach. Get ready to ignite your inner
        flame of curiosity and embark on a riveting journey of true passion for learning.<br><br>The B.Sc. Data Science Program spans over eight semesters (four years), strategically laying a strong foundational understanding of subjects, while delving
        into practical applications and recent developments. Every semester, students have the unique opportunity to immerse themselves in industrial internships, acquiring both theoretical knowledge and hands-on experience.<br><br>Our specialized Data
        Science Courses cater to the demands of a dynamic industrial landscape, setting the stage for prosperous careers in research and development, industries, and academic institutions. Furthermore, the institute may provide placement opportunities
        to our aspiring graduates.<br><br>Our B.Sc. Data Science Program offers an array of degree options, allowing students to customize their academic journey according to their aspirations:<br><br>• 3 Year B.Sc. Data Science<br><br>• 4 Year B.Sc.
        Data Science-Honours<br><br>• 4 Year B.Sc. Data Science-Honours with Research<br><br>Upon completion of the third year, students have the option to exit with a prestigious B.Sc. Data Science Degree. However, for those seeking to delve deeper into
        their chosen field, the fourth year presents two distinct paths to explore. The first option allows students to specialize in their discipline, pursuing an Honours Degree that delves into comprehensive and in-depth studies within their major.
        Alternatively, for those with a thirst for research and an unwavering curiosity, the Honours with Research option opens doors to further academic exploration.<br><br>As an epitome of academic excellence, GSFC University offers a seamless transition
        for our students to pursue a Master's Degree. Upon completing the four-year B.Sc. program, students have the remarkable opportunity to enrol in a One-Year Master's Program at the prestigious School of Science, GSFC University, propelling their
        educational journey to greater heights.
    </p>
    <a href="https://www.gsfcuni.edu.in/bsc-data-science">Know more!!!....</a>
    <!--Bachelors in CA-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">Bachelor in Computer Applications</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Embark on a transformative journey through the Bachelor of Computer Applications (BCA) Program at GSFC University, a dynamic degree meticulously crafted to empower you with a strong foundational knowledge of computer applications, cutting-edge theories
        in information technology, and proficient programming skills. Immerse yourself in a comprehensive curriculum that explores diverse domains, including digital computer fundamentals, computational thinking, Linux/Unix Programming, C programming,
        data structures, Java Programming, database management systems, and security. With a clear purpose in mind, our program aims to provide you with the perfect platform to unleash your potential and emerge as industry-ready IT professionals, poised
        for unrivalled success in the ever-evolving technological landscape.<br><br>Step into the prestigious School of Science at GSFC University, where we unveil an extraordinary BCA Program that will leave you captivated. Immerse yourself in a meticulously
        crafted educational experience, carefully calibrated to harmonize with the visionary National Education Policy (NEP) 2020. This ingeniously designed program draws inspiration from the revered "Curriculum and Credit Framework for Undergraduate
        Programs" recommended by the UGC, seamlessly blending a flexible choice-based credit system with a dynamic multidisciplinary approach. Get ready to ignite your inner flame of curiosity and embark on a riveting journey of true passion for learning.<br><br>The
        BCA Program spans over eight semesters (four years), strategically laying a strong foundational understanding of subjects, while delving into practical applications and recent developments. Every semester, students have the unique opportunity
        to immerse themselves in industrial internships, acquiring both theoretical knowledge and hands-on experienc<br><br>Our specialized Computer Application Courses cater to the demands of a dynamic industrial landscape, setting the stage for prosperous
        careers in research and development, industries, and academic institutions. Furthermore, the institute may provide placement opportunities to our aspiring graduates.<br><br>Our BCA Program offers an array of degree options, allowing students to
        customize their academic journey according to their aspirations:<br><br>• 3 Year BCA<br><br> • 4 Year BCA-Honours<br><br> • 4 Year BCA-Honours with Research<br><br>Upon completion of the third year, students have the option to exit with a prestigious
        BCA Degree. However, for those seeking to delve deeper into their chosen field, the fourth year presents two distinct paths to explore. The first option allows students to specialize in their discipline, pursuing an Honours Degree that delves
        into comprehensive and in-depth studies within their major. Alternatively, for those with a thirst for research and an unwavering curiosity, the Honours with Research option opens doors to further academic exploration.<br><br>As an epitome of
        academic excellence, GSFC University offers a seamless transition for our students to pursue a Master's Degree. Upon completing the four-year B.Sc. program, students have the remarkable opportunity to enrol in a One-Year Master's Program in Data
        Science at the prestigious School of Science, GSFC University, propelling their educational journey to greater heights.<br><br>
    </p>
    <a href="https://www.gsfcuni.edu.in/bca-computer-application">Know more!!!....</a>
    <!--MSC biotechnology-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">M.SC. Biotechnology</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Science is the basic foundation of any technological and engineering creation. In view of the changing scenario at the national and international level in the field of Science and Technology, there is a great demand for basic sciences with considerable
        knowledge of its applications. GSFC University is committed to high academic standards.<br><br>The M.Sc. Biotechnology Program is designed for Four Semesters (Two Years) in such a way that a good basic foundation of subjects is laid and applications
        along with recent developments are covered. Students will also get theoretical and practical knowledge by undergoing industrial internship after every semester.<br><br>The more focused specialization course of biotechnology is designed to fullfill
        recent demands of industrial career. The M.Sc. Biotechnology Program provide an opportunity to make a career in R&D, Industries and Academic Institutions. Opportunity for the placement may be provided by the Institute.
    </p>
    <a href="https://www.gsfcuni.edu.in/msc-biotechnology">Know more!!!....</a>
    <!--MSC chemistry-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">M.SC. chemistry</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Science is the basic foundation of any technological and engineering creation. In view of the changing scenario at the national and international level in the field of Science and Technology, there is a great demand for basic sciences with considerable
        knowledge of its applications. GSFC University is committed to high academic standards.<br><br>The M.Sc. Chemistry Program is designed for Four Semesters (Two Years) in such a way that a good basic foundation of subjects is laid and applications
        along with recent developments are covered. Students will also get theoretical and practical knowledge by undergoing industrial internship after every semester.<br><br>The more focused specialization course of organic and analytical chemistry
        is designed in the 2 year of M.Sc. Chemistry program to fullfill recent demands of industrial career. The M.Sc. Chemistry Program provide an opportunity to make a career in R&D, Industries and Academic Institutions. Opportunity for the placement
        may be provided by the Institute.
    </p>
    <a href="https://www.gsfcuni.edu.in/msc-chemistry">Know more!!!....</a>
    <!--MSC Industrial microbiology-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">M.SC. Industrial Microbiology</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Science is the basic foundation of any technological and engineering creation. In view of the changing scenario at the national and international level in the field of Science and Technology, there is a great demand for basic sciences with considerable
        knowledge of its applications. GSFC University is committed to high academic standards.<br><br>The M.Sc. Industrial Microbiology Program is designed for Four Semesters (Two Years) in such a way that a good basic foundation of subjects is laid
        and applications along with recent developments are covered. Students will also get theoretical and practical knowledge by undergoing industrial internship after every semester.<br><br>The more focused specialization course of Industrial Microbiology
        is designed to full fill recent demands of industrial career. The M.Sc. Industrial Microbiology Program provide an opportunity to make a career in R&D, Industries and Academic Institutions. Opportunity for the placement may be provided by the
        Institute.
    </p>
    <a href="https://www.gsfcuni.edu.in/msc-industrial-microbiology">Know more!!!....</a>
    <!--MSC data science-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">M.SC. Data science</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">DATA is the new definition of power for the upcoming generation; this holds everything to control the world and, the human race can benefit a lot from the same. A unique combination of Mathematics, Statistics and Computer Science can serve as a toolkit
        for the proper implementation of the techniques for solving real-life problems. The language of data can be learnt by employing analytical skills; this creates better opportunities for career advancements as well as for fresh employment.<br><br>M.Sc.
        Data Science Program at GSFC University is a Degree which is designed for Four Semesters (Two Years) in such a way that advanced concepts of Mathematics and Statistics will be applied through Computer Programing to analyze big data. Students will
        also get theoretical and practical knowledge by undergoing industrial internship after every semester.<br><br>The M.Sc. Data Science Program provides an opportunity to make a career in R&D, Industries and Academic Institutions. Opportunity for
        the placement may be provided by the Institute.
    </p>
    <a href="https://www.gsfcuni.edu.in/msc-data-science">Know more!!!....</a>
    <!--PHD bio technology-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">PH.D. Bio Technology</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">School of Science, GSFC University offers its Ph.D. under the guidelines prescribed by the University Grants Commission (UGC). The structure of the program is designed to produce students with rigorous research and analytical skills, who are exceptionally
        well – equipped to go onto Postdoctoral research, or employment in industry and the public service.
    </p>
    <a href="https://www.gsfcuni.edu.in/phd-biotechnology">Know more!!!....</a>
    <!--PHD chemistry-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">PH.D. Chemistry</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">School of Science, GSFC University offers its Ph.D. under the guidelines prescribed by the University Grants Commission (UGC). The structure of the program is designed to produce students with rigorous research and analytical skills, who are exceptionally
        well – equipped to go onto Postdoctoral research, or employment in industry and the public service.
    </p>
    <a href="https://www.gsfcuni.edu.in/phd-chemistry">Know more!!!....</a>
    <!--phd micro biology-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">PH.D. Microbiology</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">School of Science, GSFC University offers its Ph.D. under the guidelines prescribed by the University Grants Commission (UGC). The structure of the program is designed to produce students with rigorous research and analytical skills, who are exceptionally
        well – equipped to go onto Postdoctoral research, or employment in industry and the public service.
    </p>
    <a href="https://www.gsfcuni.edu.in/phd-microbiology">Know more!!!....</a>
    <!--phd mathematics-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">PH.D. Mathematics</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">School of Science, GSFC University offers its Ph.D. under the guidelines prescribed by the University Grants Commission (UGC). The structure of the program is designed to produce students with rigorous research and analytical skills, who are exceptionally
        well – equipped to go onto Postdoctoral research, or employment in industry and the public service.
    </p>
    <a href="https://www.gsfcuni.edu.in/phd-mathematics">Know more!!!....</a>
    <!--pgd in industrial safety-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">PGD in Industrial Safety</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">The Fire & Safety as a subject has become very important in view of rapid industrialization and development of new technology and consequent enactment of various legislation for ensuring safety & security of the property & life. In view of the changing
        scenario at the national and international level in the field of Science and Technology, there is a great demand for Safety personnel in the Industries and construction sector as per Section 40B(2) Factories Act 1948.<br><br>However with recent
        incidents of fire in UPL,ONGC & various GIDC in Gujarat .There is are great demand for skilled and competent Safety Professionals . GSFC University is committed to high academic standards. Post Graduate Diploma in Industrial Safety ( PGDIS) is
        provided by GSFC University as one year Program. PGDIS Program is designed as per the needs of Safety Officers in Industries along with case study, seminars, safety audits & industrial visits. Students will also get theoretical and practical knowledge
        by undergoing industrial visits, Industry defined project. <br><br>The course of PGDIS is designed to full fill recent demands of industrial career. The Program provide an opportunity to make a career in construction industry, petrochemical &
        Oil & Gas, Process industries, Aviation & Marine industry. Opportunity for the placement may be provided by the Institute.
    </p>
    <a href="https://www.gsfcuni.edu.in/pg-diploma-industrial-safety">Know more!!!....</a>
    <hr>
    <p style="text-align:center; font-size:35px; color:rgb(10, 82, 10)"><strong>School Of Management Studies and Liberal Arts</strong></p>
    <!--BBA general-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">BBA/BBA(HONS.)-General</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">BBA programs aligned with the principles of NEP 2020 aim to provide students with a well-rounded education that equips them with the knowledge, skills, and mindset necessary to thrive in the rapidly evolving business landscape. However, specific implementation
        and alignment may vary across institutions. Educational institutions need to adapt their BBA programs in line with the broader objectives and spirit of NEP 2020 to ensure relevance and effectiveness in preparing students for the future.<br><br>The
        BBA program provides students with a comprehensive understanding of business principles, skills, and practices, preparing them for entry-level positions in business or further studies in specialized areas of business or related fields. The specific
        curriculum and structure of BBA programs may vary from one institution to another, but they generally aim to equip students with the knowledge and skills needed to succeed in the dynamic and competitive business environment.
    </p>
    <a href="https://www.gsfcuni.edu.in/bachelor-of-business-administration-bba">Know more!!!....</a>
    <!--BBA business analytics-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">BBA/BBA(HONS.)-Business Analytics</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">Business analytics is a process of making sense of data that can help companies make informed decisions on the future of business. Business analytics deals with the study, analysis and interpretation of big data of organisations whether, profit making
        or non-profit making. Business Analytics as a discipline is emerging as an important part of management science. In the Organisation, decision making process is buy and large data-driven.
    </p>
    <a href="https://www.gsfcuni.edu.in/bba-business-analytics">Know more!!!....</a>
    <!--BCOM-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.COM./B.COM.(HONS.)</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">B. Com/ B. Com (Hons) programs aligned with the principles of NEP 2020 aim to provide students with a well-rounded education that equips them with the knowledge, skills, and mindset necessary to thrive in the rapidly evolving business, commerce, and
        related fields. However, specific implementation and alignment may vary across institutions. Educational institutions need to adapt their B. Com/ B. Com (Hons) programs in line with the broader objectives and spirit of NEP 2020 to ensure relevance
        and effectiveness in preparing students for the future.<br><br>The program is designed to provide students with a comprehensive understanding of commerce and business management, preparing them for a broad array of career choices in banking, auditing,
        taxation, law, and business consultancy, among others. Furthermore, our B.Com. program will serve as an ideal foundation for those who aspire to pursue higher studies like MBA, CA, CFA, and other professional courses.<br><br>Specifically, in Gujarat,
        the state's rapid industrial development presents immense opportunities for B.Com. graduates. The state's GDP growth rate of approximately 11.2% in FY 2023-24, higher than the national average, is a testament to the burgeoning economic opportunities.
        These statistics manifest the promising employability prospects for B.Com. graduates in our state, which is home to numerous multinational corporations, SMEs, and startups.<br><br>
    </p>
    <a href="https://www.gsfcuni.edu.in/bachelor-of-commerce-bcom">Know more!!!....</a>
    <!--BA economics-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">B.A./B.A.(HONS.)-Economics</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">A Bachelor of Arts (B.A.) in Economics program offers students a comprehensive understanding of economic principles, theories, and methodologies. Spanning four years, this undergraduate degree equips students with analytical, critical thinking, and
        quantitative skills essential for analyzing economic phenomena and preparing them for diverse career opportunities in various sectors, including government, finance, consulting, research, and academia.<br><br>In the context of the national scenario,
        the Bachelor of Arts in Economics program is fast gaining traction in the realm of higher education. According to the All-India Survey on Higher Education (AISHE) 2023, economics has emerged as a preferred stream of study, gaining popularity due
        to its broad applications in policy-making, business strategy, and financial decision-making. This trend mirrors the rise in economic activities, digital transformation, and the growing importance of economic literacy in the current socioeconomic
        climate of India.<br><br>In the context of Gujarat, the state vibrant economic landscape, marked by its thriving industries and sectors such as manufacturing, agriculture, services, and information technology, has created a high demand for graduates
        well-versed in economics. With its strategic location and robust infrastructure, Gujarat has attracted substantial foreign direct investment (FDI), adding to the economic dynamism and creating a multitude of opportunities for economic professionals.
    </p>
    <a href="https://www.gsfcuni.edu.in/bachelor-of-arts-ba-economics">Know more!!!....</a>
    <!--MBA-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">MBA</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">The MBA program at GSFC University (GSFCU) is transforming the landscape of postgraduate education with its innovative approach. The program empowers tomorrow's leaders with the knowledge, skills, and connections to succeed in today's business landscape.
        Our MBA program is strategically crafted to cultivate exceptional business executives, managers, and entrepreneurs, equipped with a blend of theoretical knowledge and practical expertise to confidently tackle demanding industry tasks and embark
        on successful entrepreneurial journeys. Furthermore, we prioritize instilling a strong foundation of values, ethics, and a socially responsive attitude, shaping our graduates into responsible global citizens. At GSFCU, we believe in unleashing
        the full potential of MBA aspirants by challenging them to exceed their limits and cultivate exceptional problem-solving skills. Our program goes beyond traditional business management education, immersing students in advanced concepts and theories
        that sharpen their managerial prowess and decision-making abilities, taking their professional game to new heights.<br><br>With a systematic and well-planned approach to career growth, our postgraduate MBA degree program empowers aspiring minds
        to pursue their entrepreneurial ambitions with confidence. We understand the ever-evolving nature of today's business landscape, and our curriculum equips graduates with a unique skill set that combines time-tested wisdom with innovative thinking.
        At GSFCU, we nurture business management graduates who are equipped to tackle critical business challenges head-on and provide optimal solutions. Our students acquire the skills needed to navigate dynamic environments, identify opportunities,
        and deliver exceptional results. Through a perfect blend of theoretical knowledge and practical application, we shape our students into resourceful problem-solvers who can effectively address the demands of the business world. At the heart of
        the program lies a commitment to individual growth, learning, and development. The dedicated faculty and staff foster a supportive learning environment that encourages critical thinking, innovation, and collaboration. The program is designed to
        bridge the gap between academia and the business world, equipping graduates with the practical exposure and real-world insights needed to excel in their chosen careers.<br><br>Join us at GSFCU and embark on a transformative journey that will elevate
        your business acumen, unlock your entrepreneurial spirit, and position you as a sought-after professional capable of making a significant impact in the business landscape.
    </p>
    <a href="https://www.gsfcuni.edu.in/masters-of-business-administration-mba">Know more!!!....</a>
    <!--PHD management-->
    <p style="text-align:left; font-family:cursive; color:#a57952; font-size:30px;">PH.D Management</p>
    <p style="font-family:'Times New Roman'; font-size:20px;">The Ph.D. in Management program at GSFC University offers a comprehensive academic focus, encompassing specialized courses in research methodology, data analysis, and ethics. Scholars engage in cutting-edge research projects, exploring emerging trends
        and innovative approaches to management. With access to state-of-the-art facilities and resources, research scholars have the opportunity to conduct in-depth studies in various aspects of management. The program also emphasizes collaboration with
        industry partners, providing students with practical insights and real-world experience.<br><br>Aligned with UGC regulations and the National Education Policy 2020, it offers a structured curriculum that integrates insights from diverse fields
        into management research. Through rigorous coursework, mentorship from esteemed faculty, and hands-on research opportunities, scholars develop the analytical skills and expertise necessary to make significant contributions to the field of management.
    </p>
    <a href="https://www.gsfcuni.edu.in/phd-management">Know more!!!....</a>

    <footer>
        <p>&copy; 2024 Inhouse Library</p>
    </footer>
</body>

</html>
