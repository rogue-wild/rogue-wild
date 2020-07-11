<body>
    <div class="grid-2">
        <div class="section-1">
            <i class="fas fa-code fa-5x white"></i>
            <h2>Vishnu Bhagwat</h2>
            <p>Delhi, India.</p>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-github"></i></a>
        </div>
        <div class="section-2">
            <h2>About</h2>
            <p>I'm an under-graduate student, studying Computer Science in GGSIPU. I'm also a Technology Enthusiast who greatly admires open source software development.</p>
            <h2>Skills</h2>
            <p><ul>
                <li>Python</li>
                <li>C++</li>
                <li>C</li>
                <li>HTML</li>
                <li>CSS</li>
            </ul></p>
            <h2>Projects</h2>
            <a href="#">Project 1</a>
            <a href="#">Project 2</a>
            <a href="#">Project 3</a>
            <a href="#">Project 4</a>
            <a href="#">Project 5</a>
            <h2>Contact</h2>
            <p>vishnu.bhagwat007@gmail.com</p>
        </div>
    </div>
    <style>
    /* global */
@import url('https://fonts.googleapis.com/css?family=Roboto');

.grid-2{
    display: grid;
    grid-template-columns: repeat(2,1fr);
}

body{
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
    background-color: #101214;
    color: #7A7C80;

}

h2,.white{
    color: #fff;
}

a{
    color: #7A7C80;
    text-decoration: none;
}
/* section 1 */
.section-1{
    padding-top: 40vh;
    padding-left: 20vw;
    text-align: center;
}

.section-1 p{
    font-size: 1.1rem;
    padding-bottom: 10px;
    margin:0;
}

.section-1 h2{
    font-size: 1.7rem;
    margin-bottom: 10px;
}

.section-1 a{
    font-size: 1.5rem;
    padding: 10px;
}
/* section 2 */
.section-2{
    padding-top: 20vh;
    width: 70%;
}

.section-2 h2{
    font-size: 1.7rem;
    margin-bottom: 10px;
}

.section-2 p{
    font-size: 1.1rem;
    padding-bottom: 10px;
    margin:0;
}

.section-2 a{
    display: block;
    padding: 5px;
    font-size: 1.2rem;
    padding-left: 0;
    width: 100px;
}
/* animations / utilities */
.section-2 a:hover{
    font-size: 1.3rem;
    color: #fff;
    cursor: pointer;
    transition: 0.2s;
}

.section-1 a:hover{
    color: #fff;
    cursor: pointer;
    transition: 0.3s;
}

.white:hover{
    position: relative;
    padding-left: 10px;
}

/* media queres */
@media(max-width:780px){
    .grid-2{
        grid-template-columns: 1fr;
    }
    .section-1{
        padding:0;
        padding-top: 5rem;
    }
    .section-2{
        padding: 0;
        padding-left: 1.5rem;
        padding-top: 2rem;
    }
}
    </style>
</body>
</html>
