# Rubika-s-project-
<!DOCTYPE html>

<html>

<head>

    <title>Profile-picture</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            padding: 0;

            background-color: #84a6e9;

        }



        header {

            background-color: #941919;

            color: #fff;

            text-align: center;

            padding: 2rem 0;

            position: relative; /* Add this */

        }



        .header-content h1 {

            font-size: 2.5rem;

        }



        /* Add styles for the round profile picture */

        .profile-picture {

            width: 100px; /* Adjust the size as needed */

            height: 100px;

            border-radius: 75%; /* Create a circular shape */

            object-fit: cover; /* To ensure the image fills the circular area */

            position: center; /* Add this */

            top: 75px; /* Adjust top position as needed */

            left: 75px; /* Adjust left position as needed */

        }



        nav {

            background-color: #333;

            color: #fff;

            text-align: center;

        }



        nav ul {

            list-style-type: none;

            padding: 0;

        }



        nav ul li {

            display: inline;

            margin: 0 20px;

        }



        nav ul li a {

            text-decoration: none;

            color: #fff;

        }



        .section-content {

            background-color: #fff;

            padding: 2rem;

            margin: 1rem;

            border-radius: 20px;

            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

            text-align: justify;

        }



        .download-button {

            background-color: #333;

            color: #fff;

            padding: 0.5rem 1rem;

            text-decoration: none;

            border-radius: 20px;

            display: inline-block;

            margin-top: 10px;

            align-self: center;

        }



        .download-button:hover {

            background-color: #555;

        }



        footer {

            text-align: center;

            padding: 1rem 0;

            background-color: #333;

            color: #fff;

        }



        ul {

            list-style-type: disc;

            padding-left: 20px;

        }

    </style>

</head>

<body>

    <header>

        <div class="header-content">

            <!-- Add your profile picture here -->

            <img src="Shreema.jpeg" alt="Profile Picture" class="Profile-picture">

            <h1>DURGA DIVYASHREE G</h1>

            <p>MSC COMPUTER SCIENCE </P>

        </div>

    </header>



    <nav>

        <ul>

            <li><a href="#about">About</a></li>

            <li><a href="#education">Education</a></li>

            <li><a href="#skills">Skills</a></li>

            <li><a href="#projects">Projects</a></li>

            <li><a href="#resume">Resume</a></li>

           

        </ul>

    </nav>



    <section id="about">

        <div class="section-content">

            <h2>About</h2>

            <p>ENTHUSIASTIC AND KNOWLEDGEABLE FRESHER WITH PRACTICALSKILLS EAGER TO CONTRIBUTE TO A COMPANY SUCCESS.POSSESSES A STRONG WILLINGNESS TO LEARN AND DEVELOPPROFESSIONAL CAPABILITIES IN DYNAMIC WORK ENVIRONMENT.<a href="https://techtrainer20.github.io/git_con2/" traget="_target"></a></p>

        </div>

    </section>



    <section id="education">

        <div class="section-content">

            <h2>Education</h2>

            <p>QUAID E MILLATH GOVERNMENT COLLEGE FOR WOMENS -MSC COMPUTER SCIENCE</p>   

        </div>

    </section>



    <section id="skills">

        <div class="section-content">

            <h2>Skills</h2>

            <ul>

                <li>Python</li>

                <li>Internet of Things</li>

                <li>Java</li>

                <li>Html</li>

                <li>ML & AI</li>

                <li>Autocad</li>

                <li>Ms office</li>

                <li>Java script</li>

            </ul>

        </div>

    </section>



    <section id="projects">

        <div class="section-content">

            <h2>Projects</h2>

            <ul>

                <li>DETECTION OF CYBER ATTACK IN NETWORK TRAFFIC USING MACHINE LEARNING ALGORITHM</li>

                <li>LIBRARY MANAGEMENT SYSTEM</li>

                <li>RAILWAY MANAGEMENT SYSTEM</li>

                 <!-- Add more project links here -->

            </ul>

        </div>

    </section>



    <section id="resume">

    

        <div class="section-content">

            <center>

            <a href="DURGA DIVYASHREE G.pdf" target="_blank" class="download-button">Download Resume</a>

        </center>

        </div>

        

    </section>



    <footer>

        <p>&copy; DURGA DIVYASHREE G</p>

    </footer>



    <script>

        // Smooth scrolling to section when clicking on navigation links

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {

            anchor.addEventListener('click', function(e) {

                e.preventDefault();



                const targetId = this.getAttribute('href').substring(1);

                const targetElement = document.getElementById(targetId);



                if (targetElement) {

                    window.scrollTo({

                        top: targetElement.offsetTop,

                        behavior: 'smooth'

                    });

                }

            });

        });

    </script>

</body>

</html>
