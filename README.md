# Ex.07 Software Product Company Website
## Date:04/11/2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## index.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Ethical Hacking</title>

    <!-- font awesome cdn link -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
    />

    <!-- custom css link -->
    <link rel="stylesheet" type="text/css" href="css/style.css" />
  </head>
  <body>
    <!-- header section start -->
    <header class="header" id="nav">
      <div class="logo"><h1>Ethical Hacking</h1></div>

      <div class="links">
        <a href="#home">home</a>
        <a href="#team">team</a>
        <a href="#project">Products</a>
        <a href="#service">service</a>
        <a href="#contact">contact</a>
      </div>

      <div class="icons">
        <div class="fa-solid fa-right-to-bracket"></div>
        <div class="fa-solid fa-user"></div>
        <div class="fas fa-bars" id="menu-btn"></div>
      </div>
    </header>
    <!-- header section ends -->

    <!-- home section start -->

    <section class="home" id="home">
      <div class="content">
        <h1>Join to learn free Ethical Hacking</h1>
        <p>What are you waiting for</p>
        <a href="#" class="btn"><span>Join Now</span></a>
      </div>
    </section>
    <!-- home section ends -->

    <!-- team section start -->

    <section class="team" id="team">
      <h1 class="heading">meet our team</h1>
      <p class="paragraph">
        Top Ethical Hacking Professional
      </p>

      <div class="box-container">
        <div class="box">
          <img src="images/harish_image.jpg" />

          <div class="content">
            <div>
              <h3>Sriram</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/praveen1.jpg" />

          <div class="content">
            <div>
              <h3>Praveen</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/praveen.jpg" />

          <div class="content">
            <div>
              <h3>Praveen</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/suro.jpg" />

          <div class="content">
            <div>
              <h3>Surothaman</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/kishore.jpg" />

          <div class="content">
            <div>
              <h3>Kishore Kumar</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/Richard.jpg" />

          <div class="content">
            <div>
              <h3>RichardSon</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- team section ends -->

    <!-- project section start -->

    <section class="project" id="project">
      <h1 class="heading">Products</h1>
      <p class="paragraph">
        Basic to Advance Hacking Equipments
      </p>

      <div class="box-container">
        <div class="box">
          <img src="images/FlipperZero.png" />

          <div class="content">
            <div>
              <h3>FlipperZero</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/Raspberry Pi.png" />

          <div class="content">
            <div>
              <h3>Raspberry pi</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/wifi pineapple.png" />

          <div class="content">
            <div>
              <h3>WIFI Pineapple</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/rubber_ducky_800x.png" />

          <div class="content">
            <div>
              <h3>rubber Ducky</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/hackrf.png" />

          <div class="content">
            <div>
              <h3>HackRF one</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/badusb.png" />

          <div class="content">
            <div>
              <h3>BadUSB</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/deauther.png" />

          <div class="content">
            <div>
              <h3>WIFI Deauther Watch</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/keylogger.jpg" />

          <div class="content">
            <div>
              <h3>Hardware keylogger</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/ubertooth.webp" />

          <div class="content">
            <div>
              <h3>Ubertooth One</h3>
              <span>design / Product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/omg.webp" />

          <div class="content">
            <div>
              <h3>O.M.G Cable</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/crab.webp" />

          <div class="content">
            <div>
              <h3>product design</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/rfid.webp" />

          <div class="content">
            <div>
              <h3>RFID</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- project section ends -->

    <!-- service section start -->
    <section class="service" id="service">
      <h1 class="heading">Kali Linux</h1>
      <p class="paragraph">
		Best Kali Linux Tools
      </p>

      <div class="box-container">
        <div class="box">
          <i class="fa-brands fa-linux"></i>
          <h3>Nmap</h3>
          <p>
            Nmap is an open-source network scanner that is used to recon/scan
            networks. It is used to discover hosts, ports, and services along
            with their versions over a network.
          </p>
          <span class="fas fa-long-arrow-alt-right"></span>
        </div>

        <div class="box">
          <i class="fa-brands fa-linux"></i>
          <h3>Wireshark</h3>
          <p>
            Wireshark is a network security tool used to analyze or work with
            data sent over a network. It is used to analyze the packets
            transmitted over a network.
          </p>
          <span class="fas fa-long-arrow-alt-right"></span>
        </div>

        <div class="box">
          <i class="fa-brands fa-linux"></i>
          <h3>Metasploit Framework</h3>
          <p>
            Metasploit is an open-source tool that was designed by Rapid7
            technologies. It is one of the world’s most used penetration testing
            frameworks.
          </p>
          <span class="fas fa-long-arrow-alt-right"></span>
        </div>

        <div class="box">
          <i class="fa-brands fa-linux"></i>
          <h3>Aircrack-ng</h3>
          <p>
            Aircrack is an all in one packet sniffer, WEP and WPA/WPA2 cracker,
            analyzing tool and a hash capturing tool. It is a tool used for wifi
            hacking.
          </p>
          <span class="fas fa-long-arrow-alt-right"></span>
        </div>

        <div class="box">
          <i class="fa-brands fa-linux"></i>
          <h3>Wireshark</h3>
          <p>
            Wireshark is a network security tool used to analyze or work with
            data sent over a network. It is used to analyze the packets
            transmitted over a network.
          </p>
          <span class="fas fa-long-arrow-alt-right"></span>
        </div>

        <div class="box">
          <i class="fa-brands fa-linux"></i>
          <h3>Sqlmap</h3>
          <p>
            sqlmap is one of the best tools to perform SQL injection attacks. It
            just automates the process of testing a parameter for SQL injection
            and even automates the process of exploitation of the vulnerable
            parameter.
          </p>
          <span class="fas fa-long-arrow-alt-right"></span>
        </div>
      </div>
    </section>
    <!-- service section ends -->

    <!-- contact section start -->

    <section class="contact" id="contact">
      <h1 class="heading">contact us</h1>
      <p class="paragraph">feel free to contact us</p>

      <div class="row">
        <div class="content">
          <h1>let's talk</h1>
          <h3>darkwebnew@gmail.com</h3>
          <p>
			ALso Social Media Available For Further Information
          </p>

          <div class="icons">
            <a href="#" class="fab fa-facebook-f"></a>
            <a href="#" class="fab fa-instagram"></a>
            <a href="#" class="fa-solid fa-phone"></a>
			<a href="#" class="fa fa-at"></a>
          </div>
        </div>

        <div class="form">
          <form>
            <input type="text" name="" placeholder="your name" />
            <input type="email" name="" placeholder="your email" />
            <input type="text" name="" placeholder="subject" class="subject" />

            <textarea placeholder="your message"></textarea>

            <a href="#" class="btn"><span>send message</span></a>
          </form>
        </div>
      </div>
    </section>

    <!-- contact section ends -->

    <!-- footer section start -->
    <section class="footer">
      <div class="credit">
        created by <span>darkwebnew networks</span> | all rights reserved.
      </div>

      <div class="links">
        <a href="#">teams of use</a>
        <a href="#">privacy policy</a>
        <a href="#">cookie policy</a>
      </div>
    </section>
    <!-- footer section ends -->

    <!-- custom js link -->
    <script src="js/scripts.js"></script>
  </body>
</html>

```
## scripts.js
```
let navbar = document.querySelector('.links');

let header = document.querySelector('header');

document.querySelector('#menu-btn').onclick = () =>{
	navbar.classList.toggle('active');
	header.classList.toggle('active');
}

function change() {
	var nav = document.getElementById('nav');

	var value=window.scrollY;

	if (value>80) 
	{
		nav.classList.add('nav-change');
	}
	else
	{
		nav.classList.remove('nav-change');
	}
}

window.addEventListener('scroll',change);
```
## OUTPUT:
![Screenshot (111)](https://github.com/surothaaman/softweb/assets/133313653/ca15c63b-25b1-47f8-807e-ac6f2497ad4d)
![Screenshot (101)](https://github.com/surothaaman/softweb/assets/133313653/59a891dc-8b33-409c-af5b-f7eff45dad49)
![Screenshot (97)](https://github.com/surothaaman/softweb/assets/133313653/92046e45-f3ef-4109-ad4b-2750531eeb0d)

![Screenshot (99)](https://github.com/surothaaman/softweb/assets/133313653/a4dcad5e-ade2-44da-918c-c888168f4b56)
![Screenshot (100)](https://github.com/surothaaman/softweb/assets/133313653/d883e5b1-a754-449f-9898-0843fb56216a)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
