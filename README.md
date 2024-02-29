<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PortFolio Website Design</title>
     <!-- css Files -->
     <link rel="stylesheet" href="style.css">
     <script src="https://kit.fontawesome.com/3443a4ca80.js" crossorigin="anonymous"></script>
</head> 
<body>
    <div id="header">
        <div class="contener">
            <nav>
                <img src="images/logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a> </li>
                    <li><a href="#about">About</a> </li>
                    <li><a href="#services ">Services</a> </li>
                    <li><a href="#porfolio ">Experince</a> </li>
                    <li><a href="#contact ">Contact</a> </li>
                    <i class="fas fa-times"  onclick="Closemenu()"></i>
                </ul>
                <i class="fas fa-bars" onclick="Openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>Graphics Designer</p>
                <h1> Hi, I am <span>Poonam</span><br> Waghere From India</h1>
            </div>
        </div>
    </div>
    <!-- ----------------------------------About------------------------------ -->
    <div id="about">
        <div class="contener">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/poonam.png">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>To seek the challenging position in Software industry that needs 
                        innovation, creativity, dedication and enable me to continue to 
                        work in a challenging and fast paced environment, leveraging 
                        my current knowledge and fostering creativity with many learning 
                        opportunities.which provides additional information about my skills. 
                        If you require any additional information then please contact me</p>

                        <div class="tab-title">
                            <p class="tab-links active-link" onclick="opentab('Skills')">Skills</p>
                            <p class="tab-links"onclick="opentab('Experience')">Experience</p>
                            <p class="tab-links"onclick="opentab('Education')">Education</p> 
                        </div>
                    
                        <div class="tab-contents active-tab" id="Skills">
                            <ul>
                                <li><span>UI/UX</span><br>Designing Web/App interface</li>
                                <li><span>Web Developemnt</span><br>Designinng Website Developer</li>
                                <li><span>Corel Draw</span><br>Designing Marketing Advertising </li>
                                <li><span>Graphics Designer</span><br>Designing Layout of web and App<br> Making Pamphlet, Logo, Brochure</li>
                                <li><span>Marketing</span><br> Digital Marketing Posters</li>
                            </ul>
                        </div>
                        <div class="tab-contents" id="Experience">
                            <ul>
                                <li><span>Afcks Technologies </span><br>Designing Web/App interface</li>
                                <li><span>Vitthal Multimedia</span><br>Creative associate</li>
                                <li><span>Vitthal multimedia</span><br>Digital marketing</li>
                                <li><span>vithal multimedia</span><br>Designing Layout of web and App<br> Making Pamphlet, Logo, Brochure</li>
                                <li><span>vitthal multimedia</span><br> To create Digtal Marketing Posters</li>
                            </ul>
                        </div>
                        <div class="tab-contents" id="Education">
                            <ul>
                                <li><span>B.E (2015)</span><br>Electronic and Telecommunication Engineering</li>
                                <li><span>Dip(2011)</span><br>Computer Engineering</li>
                                <li><span>SSC(2008)</span><br>State Board</li>

                                <li><span>Course(2016)</span><br>Advances Excel</li>
                                <li><span>(2019)</span><br>VBA</li>
                                
                            </ul>
                        </div>
                </div>
            </div>
        </div>
    </div>


    <!-- -----------------------Services--------------------- -->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fas fa-code"></i>
                    <h2>Graphics Designer</h2>
                    <p> Brochures, rack cards & booklets,Business cards, 
                        letterhead & envelopes,Logos and branded elements,
                        Posters, banners and signage,
                        Social media graphics & digital marketing ads,
                        Email marketing graphics.</p>
                        <a href="#">Learn More></a>
                </div>
                <div>
                    <i class="fas fa-crop-alt"></i>
                    <h2>Web Designer</h2>
                    <p> Layout of website, Making Poster for web, and adjustment size using photoshop
                        Social media graphics & digital marketing ads,
                        Email marketing graphics.</p>
                        <a href="#">Learn More></a>
                </div>
                <div>
                    <i class="fab fa-app-store"></i>
                    <h2>Digital Marketing</h2>
                    <p> Available to businesses of all sizes,
                        Grow your business on and off Marketing
                        Quick and simple execution.</p>
                        <a href="#">Learn More></a>
                </div>
               
            </div>

        </div>
    </div>
    <!-- --------------------------------My PortFolio----------------------- -->
    <div id="porfolio">
        <div class="contener">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="images/2.jpg">
                    <div class="layer">
                        <h3>Social Media</h3>
                        <p>this is the social media Advertising</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/final Purification1.jpg">
                    <div class="layer">
                        <h3>Personal Client</h3>
                        <p>water Purifiation clients</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/New Seperate.jpg">
                    <div class="layer">
                        <h3>Personal Client</h3>
                        <p>water Purifiation clients</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/3.jpg">
                    <div class="layer">
                        <h3>Personal Client</h3>
                        <p>water Purifiation clients</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/4.jpg">
                    <div class="layer">
                        <h3>Personal Client</h3>
                        <p>water Purifiation clients</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/1.jpg">
                    <div class="layer">
                        <h3>Personal Client</h3>
                        <p>water Purifiation clients</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
            </div>
            <a href="#"class="btn">See More</a>
        </div>
    </div>

<!-- -----------------------Contact------------------------- -->

<div id="contact">
    <div class="contener">
        <div class="row">
            <div class="contact-left">

                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-solid fa-paper-plane"></i>  poonamk117@gmail.com</p>
                <p><i class="fa-solid fa-phone-volume"></i>  9823119769</p>
                <div class="social-icons">
                    <a href="https://www.facebook.com/"><i class="fa-brands fa-facebook"></i></a>
                    <a href="https://www.instagram.com/"><i class="fa-brands fa-instagram"></i></a>
                    <a href="https://web.whatsapp.com/"><i class="fa-brands fa-whatsapp"></i></a>
                    <a href="https://www.linkedin.com/feed/"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="https://twitter.com/home"><i class="fa-brands fa-twitter"></i></a>
                </div>
                <a href="images/Curriculum Vitae (POONAM).pdf" download class="btn btn2">Download CV</a>
            </div>
            
            <!-- -------------------------------Form--------------------- -->

            <div class="contact-right">
                <form>
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type=" email" name="email" placeholder="Your Email ID" required>
                    <textarea name="messege"  rows="6" placeholder="Your Messege"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>copyright @ poonam. made with <i class="fas fa-heart"></i>  by this websites</p>
    </div>
</div>


    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname){
            for(tablink of tablinks){
                tablink.classList.remove("active-link");    
            }
            for(tabcontent of tabcontents){
                tabcontent.classList.remove("active-tab"); 
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");

        }
    </script>
    <script>
        var sidemenu= document.getElementById("sidemenu");

        function Openmenu(){
            sidemenu.style.right= "0";
        }
        function Closemenu(){
            sidemenu.style.right= "-200px";
        }
    </script>

</body>
</html>
