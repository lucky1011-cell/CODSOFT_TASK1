# CODSOFT_TASK1
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PORTFOLIO</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <nav>
        <a class="me" href="#">SELF INTRODUCTION</a>
        <a href="#">ABOUT </a>
        <a href="#">SERVICE</a>
        <a href="#">BLOG</a>
        <a href="#">CONTACT</a>
    </nav>
    <br>

    <header>
        <div class="you">
            <div class="hero-content">
                <p><i>Hello, <strong>My Name Is :</strong></i></p>
                <h1 id="lucky">Aditya Kumar Chaurasiya</h1> <br>
                <p>Proficient in <span>HTML,CSS,Javascript and React JS</span>with experience in windows and
                    linuxenvironment commited to delivering organisational growth,goals and objectives through the use
                    of technology.
                </p>
                <br><br>
                <h2>Frontend Developer</h2>
                <button id="btn">Read More &rarr;</button>
            </div>
            <img src="https://i.pinimg.com/736x/8d/58/85/8d58853d6d97f69dc66a3d9d3ab7be73.jpg"
                alt="https://i.pinimg.com/736x/f9/d6/c4/f9d6c4fbc39d340becdb9cc9d24e89b8.jpg" </div>
    </header>

    <main>
        <section>
            <div class="about">
                <h2>About Me</h2>
                <br>
                <p>Hello! I am Aditya, a passionate frontend developer with expertise in HTML, CSS, JavaScript, and
                    React JS. I
                    have experience working in both Windows and Linux environments and am committed to delivering
                    organizational growth, goals, and objectives through the use of technology.</p>
            </div>
        </section>

        <section>
            <div class="projects">
                <h2>Projects</h2>
                <br>
                <p><span>
                        Smart Custom Navigation :- </span><br>
                    A Custom Navigation system for UIET with indoor & outdoor maps.
                </p>
                <br>
                <p><span>AgraSaarthi :- </span><br>
                    A Voice Based AI for farmers with hyperlocal guidance and mandi forecasts.
                </p>
            </div>
        </section>

        </section>
        <div class="skill">
            <h2>Skills</h2>
            <br>
            <div class="skills-wrapper"><span class="skills">HTML</span><span class="skills">CSS</span><span
                    class="skills">JavaScript</span><span class="skills">React JS</span></div>
            Problem Solving</span>
        </div>
        </div>
        </section>

        <section>
            <div class="contact">
                <h2>Contact Me</h2>
                <p><Strong>Email:</Strong>&nbsp;adityakumarchaurasiya@gmail.com</p>
                </p>
                Phone Number: &nbsp;+91 798 722 2222</p>
                <p>Instagram</p>
            </div>

        </section>
    </main>

    <footer>
        <div class="foot">
            <p id="Copy">
                Copyright &copy; 2026 &nbsp;&nbsp; | &nbsp;&nbsp; All Rights Reserved &nbsp;&nbsp; |
                &nbsp;&nbsp; FRONTEND</p>
        </div>
    </footer>
</body>

</html>
* {
    margin: 0;
    box-sizing: border-box;
}

body {
    background-color: white;
    font-family: Arial, sans-serif;
    overflow-x: hidden;
}

/* Navigation - Responsive implementation */
nav {
    background-color: black;
    min-height: 60px;
    padding: 0 15px 5%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px 40px;
    position: sticky;
    top: 0;
    z-index: 1000;
}

nav a {
    text-decoration: none;
    color: antiquewhite;
    font-size: larger;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #ff6347;
    /* Change to your desired hover color */
}

/* Header / Hero Section */
.you {
    padding: 40px 10%;
    background-color: maroon;
    color: antiquewhite;
    min-height: 400px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 30px;
    flex-wrap: wrap;
}

.hero-content {
    flex: 1;
    min-width: 280px;
}

#lucky {
    padding-top: 20px;
    font-size: 2.5rem;
}

.you h2 {
    margin-top: 15px;
}

.you p {
    font-size: 1.2rem;
    line-height: 1.6;
    margin-top: 15px;
}

.you span {
    color: black
}

#btn {
    background-color: black;
    color: black;
    padding: 15px 30px;
    margin-top: 30px;
    border: none;
    cursor: pointer;
    font-size: 1rem;
    transition: background-color 0.3s ease;
}

#btn:hover {
    background-color: #ff6347;
    /* Change to your desired hover color */
}

/* Profile Image */
.you img {
    max-width: 100%;
    height: 380px;
    object-fit: cover;
}

/* Main Sections Styling */
.about {
    text-align: center;
    padding-top: 50px;
}

.about p {
    border: grey solid 1px;
    padding: 35px;
    margin: 20px auto;
    max-width: 800px;
    width: 90%;
    box-shadow: 12px 12px 12px black;
    background-color: antiquewhite;
    line-height: 1.6;
}

.projects {
    text-align: center;
    padding-top: 50px;
}

.projects p {
    border: grey solid 1px;
    padding: 35px;
    margin: 20px auto;
    max-width: 800px;
    width: 90%;
    box-shadow: 12px 12px 12px black;
    background-color: antiquewhite;
    line-height: 1.6;
}

.projects span {
    font-size: 32px;
    color: blueviolet;
    font-weight: bold;
}

.skill {
    text-align: center;
    padding-top: 50px;
}

.skills-wrapper {
    margin-top: 30px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 0 10px;
}

.skills {
    border: 1px solid grey;
    padding: 20px 30px;
    border-radius: 36px;
    background-color: lightblue;
    color: black;
    display: inline-block;
    font-size: 1.2rem;
}

.skill span {
    border: black solid 1px;
}

.Contact {
    padding-top: 20px;
    font-size: 1.2rem;
}

.Contact p {
    padding-top: 20px;
    font-size: 1.2rem;
}

/* Footer Styling */
footer {
    background-color: rgb(36, 35, 35);
    color: antiquewhite;
    text-align: center;
    min-height: 200px;
    padding: 40px 20px;
    position: relative;
    margin-top: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
}

#Copy {
    font-size: larger;
}

/* Breakpoints for Responsiveness */

/* Tablets and medium screens */
@media screen and (max-width: 992px) {
    .you {
        padding: 45px 5%;
        justify-content: center;
        text-align: center;
    }

    .you img {
        height: 320px;
    }

    .about p,
    .projects p {
        width: 92%;
        margin-left: auto;
        margin-right: auto;
    }
}

/* Mobile devices */
@media screen and (max-width: 767px) {
    nav {
        flex-direction: column;
        gap: 15px;
        padding: 15px 0;
        align-items: center;
    }

    nav a {
        font-size: 1.1rem;
    }

    .you {
        padding: 30px 20px;
        flex-direction: column-reverse;
    }

    .you img {
        height: 260px;
        max-width: 100%;
        margin-right: 0;
    }

    #lucky {
        font-size: 2rem;
        padding-top: 10px;
    }

    .you h2 {
        font-size: 1.5rem;
    }

    #btn {
        width: 100%;
        margin-top: 20px;
    }

    .about p,.projects p {
        padding: 25px;
        width: 95%;
        margin-left: auto;
        margin-right: auto;
        font-size: 1rem;
        box-shadow: 6px 6px 6px black;
    }

    .projects span {
        font-size: 24px;
    }

    .skills {
        padding: 12px 20px;
        font-size: 0.95rem;
    }

    #Copy {
        font-size: 1rem;
    }
}

















</body>

</html>
