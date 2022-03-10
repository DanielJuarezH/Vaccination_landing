<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vaccination</title>
    <link rel="stylesheet" href="../CSS/LandingStyle.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <script>
        jQuery("#button").click(function() {
        jQuery("#infodiv").toggle();
        });
    </script>
</head>
<body>
    <nav class="navBar">
        <a href="" class="logo">Vaccination</a>
        <ul class="navLinks">
            <li class="navItem"><a href="#dataBase">Database</a></li>
            <li class="navItem"><a href="#education">Education</a></li>
            <li class="navItem"><a href="#news">News</a></li>
            <li class="navItem"><a href="#regulation">Regulation</a></li>
            <li class="navItem"><a href="#hoaxBuster">Hoax Buster</a></li>
        </ul>
    </nav>
    <div class="containerFightVirus">
        <div class="subconFightVirus">
            <h1>Fight Virus With Vaccines</h1>
            <p>Let's stop this pandemic by killing the virus with a vaccine, don't let yourself and your family get infected</p>
            <div class="twoFacts">
                <span><i class="fa-solid fa-shield iconYellow"></i>Best Protection</span>
                <span><i class="fa-solid fa-star iconYellow"></i>Selected Vacciness</span>    
            </div>
        </div>
        <div class="subconNurseImage">
            <img src="../Images/vaccine_image.jpeg" alt="Nurse holding vaccine">
        </div>
    </div>  
    <form action="">
        <fieldset class="schedulevaccine">
            <legend><i class="fa-solid fa-clock iconBlueMain"></i>Schedule your vaccinations</legend>
            <fieldset class="scheduledetails">
                <div class="locationsBox"> 
                    <label for="locations"><i class="fa-solid fa-location-dot iconBlueSecondary"></i>Location</label>
                    <input list="locations" id="location" name="location">
                    <datalist id="locations">
                        <option value="Adams County">
                        <option value="Alamosa County">
                        <option value="Arapahoe County">
                        <option value="Archuleta County">
                        <option value="Baca County">
                        <option value="Bent County">
                        <option value="Boulder County">
                        <option value="City and County of Broomfield">
                        <option value="Chaffee County">
                        <option value="Cheyenne County">
                    </datalist>
                </div>
                <div class="appointmentBox">
                    <label for="appointmentDate"><i class="fa-solid fa-calendar-days iconBlueSecondary"></i>Date</label>
                    <input type="date" name="appointmentDate" id="appointmentDate">
                </div>    
                <div class="vaccineBox">
                    <label for="vaccineType"><i class="fa-solid fa-pen iconBlueSecondary"></i>Vaccine Type</label>
                    <select name="vaccineType" id="vaccineType">
                        <option value="astraZeneca">AstraZeneca</option>
                        <option value="moderna">Moderna</option>
                        <option value="pfizer">Pfizer</option>
                        <option value="sinovac">Sinovac</option>
                    </select>
                </div>
                <div class="submitBox">
                    <input type="submit" value="Submit">
                </div>
            </fieldset>
        </fieldset>
    </form>
    <div class="containerWhy">
        <div class="subconWhy">
            <h2>Why shuould I vaccine?</h2>
            <p>In order to avoid any doubts about getting the COVID-19 vaccine, identify the following 4 benefits of COVID-19 vaccination:</p>
        </div>
        <div class="subconempty">
        </div>
    </div>
    <div class="containerReasons">
        <div class="subconReasons">
            <span><i class="fa-solid fa-sliders iconBlueSecondary"></i></span>
            <h3>Minimize the spread of viruses</h3>
            <p>Vaccine has been proven effective to prevent someone from getting infected with Coronavirus</p>
        </div>
        <div class="subconReasons">
            <span><i class="fa-solid fa-shield iconBlueSecondary"></i></span>
            <h3>Forming antibodies</h3>
            <p>COVID-19 vaccine proven to help shape antobody response for immune system</p>
            
        </div>
        <div class="subconReasons">
            <span><i class="fa-solid fa-user-group iconBlueSecondary"></i></span>
            <h3>Protecting people nearby</h3>
            <p>The benefits of COVID-19 vaccination are the vaccine that we get can also help protect people around us</p>
        </div>
        <div class="subconReasons">
            <span><i class="fa-solid fa-chart-line iconBlueSecondary"></i></span>
            <h3>Creating group immunity</h3>
            <p>COVID-19 vaccinationis also benefitial for creating group immunity or herd immunity</p>
        </div>
    </div>
    <div class="containerPreparations">
        <div class="subconImagePreparations">
            <img src="https://c.pxhere.com/images/34/a9/d02ffb9abad6a99234315ccd6809-1630679.jpg!d" srcset="https://c.pxhere.com/images/34/a9/d02ffb9abad6a99234315ccd6809-1630679.jpg!d" alt="Girl with mask">
        </div>
        <div class="subconPreparations">
            <h2>Preparations Before Vaccine</h2>
            <p>The succes of vaccines is strongly influenced by the streght of the body's immune system. Therefore, there are several things that can be tried to make the COVID-19 vaccine work:</p>
            <div class="contPreparationsList">
                <div class="subconPreparationsList">
                    <span><i class="fa-solid fa-shield iconBlueSecondary"></i>Avoid Alcoholic beverages</span>
                </div>
                <div class="subconPreparationsList">
                    <span><i class="fa-solid fa-square-xmark iconBlueSecondary"></i>Avoid Stress</span>
                </div>
                <div class="subconPreparationsList">
                    <span><i class="fa-solid fa-utensils iconBlueSecondary"></i>Eat healthy food</span>
                </div>
                <div class="subconPreparationsList">
                    <span><i class="fa-solid fa-moon iconBlueSecondary"></i>Get enough sleep</span>
                </div>
                <div class="subconPreparationsList">
                    <span><i class="fa-solid fa-heart-pulse iconBlueSecondary"></i>Excercise or physical activity</span>
                </div>
            </div>
        </div>
    </div>
    <div class="containerEmergency">
        <div class="subconEmergency">
            <h2>Emergency Contact</h2>
            <p>Contact one of the contacts below if you or your family feel unwell and have similar symptomps such as COVID-19, make sure you also take care of yourself before reporting to us:</p>
            <div class="subconContactInfo">
                <div class="subconContactType">
                    <span><i class="fa-solid fa-phone iconBlueSecondary"></i></span>
                    <h3>Call</h3>
                    <br><p>720-332-3200</p>
                    <button>Call Now</button>
                </div>
                <div class="subconContactType">
                    <span><i class="fa-solid fa-comment-dots iconBlueSecondary"></i></span>
                    <h3>Chat</h3>
                    <br><p>720-332-3200</p>
                    <button>Chat Now</button>
                </div>
                <div class="subconContactType">
                    <span><i class="fa-solid fa-video iconBlueSecondary"></i></span>
                    <h3>Video Call</h3>
                    <br><p>720-332-3200</p>
                    <button>Video Call Now</button>
                </div>
                <div class="subconContactType">
                    <span><i class="fa-solid fa-envelope iconBlueSecondary"></i></span>
                    <h3>Message</h3>
                    <br><p>720-332-3200</p>
                    <button>Message Now</button>
                </div>
            </div>        
        </div>
        <div class="subconImageContact">
            <img src="https://c.pxhere.com/images/1d/bb/d69a7139d8be2d9af3724ca32455-1602270.jpg!d" srcset="https://c.pxhere.com/images/1d/bb/d69a7139d8be2d9af3724ca32455-1602270.jpg!d" alt="Laptop and phone Image">
        </div>        
    </div>
    <footer>
        <div class="footerTopLeft">
            <div class="footertext">
                <a href="#home" class="logo">Vaccination</a>
                <p>Our goal is to help the world free from the ongoing pandemic</p>
            </div>
            
        </div>
        <div class="footerTopRight">
            <div class="subconFooter">
                <span>About</span>
                <ul class="footerLinks">
                    <li><a href="#abooutus">About US</a></li>
                    <li><a href="#features">Features</a></li>
                    <li><a href="news">News & Blog</a></li>
                </ul>
            </div>
            <div class="subconFooter">
                <span>Company</span>
                <ul class="footerLinks">
                    <li><a href="#howwework">How We Work?</a></li>
                    <li><a href="capital">Capital</a></li>
                    <li><a href="secutity">Security</a></li>
                </ul>
            </div>
            <div class="subconFooter">
                <span>Support</span>
                <ul class="footerLinks">
                    <li><a href="#faqs">FAQs</a></li>
                    <li><a href="supportcenter">Support Center</a></li>
                    <li><a href="contact">Contact US</a></li>
                </ul>
            </div>
        </div>
        <div class="footerBottomLeft">
            <p>@2021 Vaccination. All right reserved</p>
        </div>
        <div class="footerBottomRight">
            <div class="footertc">
                <a href="t&c">Terms & Agreements</a>
                <a href="#privacypolicy">Privacy Policy</a>
            </div>
        </div>
    </footer>
</body>    
</html>
