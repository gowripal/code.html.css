# code.html.css
#html

<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/72325a2426.js" crossorigin="anonymous"></script>
</head>

<body>
    <div class="mainbg">
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <a class="navbar-brand gedit" href="#">G.</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto">
                    <a class="nav-link active" href="#homesection" onclick="display('sectionmain')">Home <span class="sr-only">(current)</span></a>
                    <a class="nav-link" href="#aboutmesection" onclick="display('sectionaboutme')">About Me</a>
                    <a class="nav-link" href="#prijectssection" onclick="display('sectionpro')">Projects</a>
                    <a class="nav-link" href="#recentblogssection">Recent Blogs</a>
                    <a class="nav-link" href="#knowntechnologiessection" onclick="display('sectionknowntech')">Known Technologies</a>
                    <a class="nav-link" href="#testimoniaalssection">Testimonial</a>
                </div>
            </div>
        </nav>
        <div id="sectionmain">
            <div class="container">
                <div class="row">
                    <div class="col-12 col-md-5 ">
                        <div>
                            <img src="https://res.cloudinary.com/dcvgt03ez/image/upload/v1683398083/3D7978B1-C952-4CB3-B371-07FEDA5C109C_1_105_c_qxdtgw.jpg" class="mineedit m-4" />
                        </div>
                    </div>
                    <div class="col-12 col-md-5 mt-5">
                        <h1>Hey , I am <span class="namee">Gowri Sankar Reddy</span></h1>
                        <p>I am a Frontend Developer. </p>
                        <button onclick="display('sectioncontact')">Contact me</button>
                    </div>
                </div>
            </div>
        </div>
        <div id="sectioncontact" class="contact-bg">
            <div class="container">
                <div class="row">
                    <div class="co-12 col-md-6">
                        <div>
                            <i class="fa-brands fa-whatsapp iconedit"></i>
                            <p>9963106328</p>
                        </div>
                    </div>
                    <div class="co-12 col-md-6">
                        <div>
                            <i class="fa-brands fa-linkedin iconedit"></i>
                            <p>gsr20</p>
                        </div>
                    </div>
                    <div class="co-12 col-md-6 ">
                        <div>
                            <i class="fa-solid fa-envelope iconedit"></i>
                            <p>palnatigowrisakarreddy@gmail.com</p>
                        </div>
                    </div>
                    <div class="co-12 col-md-6">
                        <div> <i class="fa-solid fa-location-dot iconedit"></i>
                            <p>Hyderabad</p>
                        </div>
                    </div>
                </div>
                <button onclick="display('sectionmain')">back</button>
            </div>
        </div>
        <div id="sectionaboutme">
            <h1 class="p-3">GSR</h1>
            <p class="p-2">Gowri Sankar Reddy<br />
                23 years old</p>
            <button onclick="display('sectionmain')">back</button>
        </div>
        <div id="sectionpro">
            <h1 class="p-3">Project-1</h1>
            <p class="p-2">Build my own Website</p>
            <button onclick="display('sectionmain')">back</button>
        </div>
        <div id="sectionknowntech">
            <h1 class="p-3">Technologies</h1>
            <p class="p-2">CSS , HTML , SQL , PYTHON , AWS , DEVOPS</p>
            <button onclick="display('sectionmain')">back</button>
        </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>

#css

@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.mainbg {
    background-color: black;
    background-size: cover;
    height: 100vh;
}

.gedit {
    border-style: solid;
    border-color: #4b6cc1;
    padding: 5px;
}

.connttt {
    text-align: center;
}

.mineedit {
    height: 190px;
    width: 190px;
    border-radius: 100px;
}

h1 {
    font-style: Roboto;
    font-size: 25px;
    color: white;
}

p {
    color: #9aa5b1;
    font-size: 15px;
    font-style: roboto;
}

button {
    background-color: #4b6cc1;
    color: white;
    border-style: none;
    border-radius: 7px;
    padding: 5px;
}

.namee {
    color: #4b6cc1;
}

.contact-bg {
    background-color: black;
    height: 100vh;
    padding: 15px;
    color: black;
}

.iconedit {
    background-color: grey;
    height: 30px;
    padding-top: 6px;
    text-align: center;
    width: 30px;
    border-radius: 20px;
}

.abttme {
    color: blue;
}
