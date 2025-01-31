<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <meta name="viewport" content="Personal Profile Page of Sahil Pawar">
    <link rel="stylesheet" href="style.css" type="text/css">
    <link rel="icon" href="">
    <link href='https://fonts.googleapis.com/css?family=Poppins' rel='stylesheet'>
   
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

<style>
    html {
        scroll-behavior: smooth; /* Enables smooth scrolling */
    }
    /* Add your custom styles here if needed */
</style>

</head>
<body>
    <center>
        <header class="h11">
            <h1 class="header-title" style="font-family:cursive;">Sahil Ashok Pawar</h1>
            <div class="a2">
                <a href="#" class="nav-link">Home</a>
                <a href="#contact" class="nav-link">Contact Me</a>
                <button type="button" class="btn">
                    <a href="https://drive.google.com/file/d/1fzLmMKd0w_gENfBp2DMZ8bMcbsp0fNLL/view" class="resume-button">Download Resume</a>
                </button>
            </div>
        </header>
        
        <header>
            <h1 class="h111">Hello I am Sahil Pawar</h1>
            <h4 class="typing" id="typingEffect"></h4>
            <h2><b>Welcome to my world!</b></h2>
            
         </header>
         <script>
            const typingElement = document.getElementById("typingEffect");
            const textToType = "Student of Information Technology";
            
            let index = 0;
        
            function typeText() {
                if (index < textToType.length) {
                    typingElement.innerHTML += textToType.charAt(index);
                    index++;
                    setTimeout(typeText, 100); // Adjust the speed by changing 100 (milliseconds)
                } else {
                    // Reset after typing is complete and restart typing
                    setTimeout(() => {
                        index = 0;
                        typingElement.innerHTML = '';  // Clear the text
                        typeText();  // Restart typing
                    }, 2000); // Wait 1 second before restarting
                }
            }
        
            // Start typing the text
            typeText();

            
        </script>
        

     <section>
        <h1>About Me</h1>
        <p>I am second year IT student.I am pursuing B.Tech in Information Technology <br>from Sanjivani College of Engineering Kopargaon</p>
        <img src="assets/img/sahil phto.jpg" alt="Sahil Profile" width="300">
     </section><hr>
     
            
    
    <section>
       
        <h1>Contact Information</h1>
        <p>Let's Connect</p>
        <p>
            <a href="https://www.linkedin.com/in/sahil-pawar-004382297?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">
                <i class="fab fa-linkedin icon-size"></i> 
            </a><h4>LinkedIn</h4> 
            <a href="mailto:sahil9356926077@gmail.com" target="_self">
                <i class="fas fa-envelope icon-size"></i> 
            </a> <h4>Email Me</h4>
            <a href="https://github.com/sahil-9356" target="_blank">
                <i class="fab fa-github icon-size"></i> 
            </a><h4>GitHub</h4>
        </p>
       
    </section><hr>
    
     <section>
        <h2>My Projects</h2>
        <div class="projects-container">
            <div class="project-column">
                <img src="assets/img/Top-10-Computer-Science-Project-Ideas-in-2024-and-Beyond.jpg" alt="Project 1" class="project-image">
                <div class="project-title"><a href="https://github.com/sahil-9356/Web-Development" target="_blank">Web Development Making Webpages</a></div>
                <div class="project-description">It involves web development using HTML, CSS, and JavaScript.</div>
            </div>
            <div class="project-column">
                <img src="assets/img/Top-Considerations-in-Mobile-App-Development-Projects.jpg" alt="Project 2" class="project-image">
                <div class="project-title"><a href="https://github.com/sahil-9356/Admin-App" target="_blank">App Develpment-Admin App</a></div>
                <div class="project-description">This project focuses on creating a dynamic admin app using Kotlin,XML in Adroid Studio.</div>
            </div>
            <div class="project-column">
                <img src="assets/img/product-jpeg-500x500.webp" alt="Project 3" class="project-image">
                <div class="project-title"><a href="">Project 3</a></div>
                <div class="project-description">A mobile app project developed using Flutter for cross-platform deployment.</div>
            </div>
        </div>
    </section><hr>

    <section>
        <h2>My Skills</h2>
        <div class="skills-container">
            <div class="skill-column">
                <div class="skill-title">Web Development</div>
                <div class="skill-description">Frontend Knowledge</div>
            </div>
            <div class="skill-column">
                <div class="skill-title">Graphic Design</div>
                <div class="skill-description">Making Posters,Image Editing.</div>
            </div>
            <div class="skill-column">
                <div class="skill-title">Photography</div>
                <div class="skill-description">Capuring new moments and preserve that moments.</div>
            </div>
        </div>
        <div class="marquee-container">
            <div class="marquee-images">
                <img src="https://miro.medium.com/v2/resize:fit:1200/1*V-Jp13LvtVc2IiY2fp4qYw.jpeg" alt="Skill 1" />
                <img src="assets/img/unnamed.jpg" alt="Skill 2" />
                <img src="assets/img/530171_716709.webp" alt="Skill 3" />
            </div>
        </div>
        
    </section><hr>
    <section>
        <fieldset>
            <legend>Personal Contact</legend>
            <h1>Contact Me</h1>
            <form  id="contact" action="https://api.web3forms.com/submit" method="POST">

                <input type="hidden" name="access_key" value="38189167-02be-4da4-a427-4af79e6d490a">


                <label for="name">Name</label>
                <input type="text" id="name" name="name" placeholder="Your Name" required><br><br>
                
                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
                <label for="phone">Phone NO</label>
                <input type="text" id="phone" name="phone" placeholder="Phone no." required><br><br>
                
                <label for="message">Message</label>
                <textarea name="message"  id="message" placeholder="Send Message" required></textarea><br><br>

                <div class="g-recaptcha" data-sitekey="Y"></div><br>

                <script src="https://www.google.com/recaptcha/api.js" async defer></script>
               
                
                
                <button type="submit" class="button">Send Message</button>
                <input type="reset" class="button1" value="Reset">
            </form>
        </fieldset>
    </section>
    <hr>
    

    <footer><p>&copy Owned by Sahil Pawar</p></footer>
    </center>
</body>
</html>
