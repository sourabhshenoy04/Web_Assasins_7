<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WebAssasins</title>
  <link rel="icon" type="image/x-icon" href="logo.jpg">
  <link rel="stylesheet" href="project.css">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css">

	
</head>
<body>
  <div>
  <nav>
    <img src="logo.jpg" alt="logo" align="left" height="50">
    
    <ul>
      <li><a href="#">What we do</a></li>
      <li><a href="#">Our Ideologies</a></li>
      <li><a href="#">Methodologies</a></li>
      <li><a href="#">Ideologies we follow</a></li>
    </ul>
  </nav>
  </div>
  <hr>
  <br>
  <div class="galleryContainer">
    <div class="slideShowContainer">
        <div id="playPause" onclick="playPauseSlides()"></div>
        <div onclick="plusSlides(-1)" class="nextPrevBtn leftArrow"><span class="arrow arrowLeft"></span></div>
        <div onclick="plusSlides(1)" class="nextPrevBtn rightArrow"><span class="arrow arrowRight"></span></div>
        <div class="captionTextHolder"><p class="captionText slideTextFromTop"></p></div>
        <div class="imageHolder">
            <img src="html.png">1366X768
            <p class="captionText">Caption Text-01</p>
        </div>
        <div class="imageHolder">
            <img src="csslogo2.png">
            <p class="captionText">Caption Text-02</p>
        </div>
        <div class="imageHolder">
            <img src="JavaScript-Logo.png">
            <p class="captionText">Caption Text-03</p>
        </div>
    </div>
    <div id="dotsContainer"></div>
</div>
<br>
<hr>
<!-- tools -->
<div class="container">
  <div class="details">
    <h2>Front-End Tools We use</h2>

  </div>
  <div class="main-box">
    <div class="box box-grey">
      <div class="image">
        <img src="html.png" width="100" height="100"alt="">
      </div>
      <h2>HTML</h2>
      <hr>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda labore.</p>
      <a href="#">Read More</a>
    </div>

    <div class="box box-red">
      <div class="icon">
        <img src="csslogo2.png" width="50" height="90"alt="">
      </div>
      <h2>CSS</h2>
      <hr>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda labore.</p>
      <a href="#" class="white-border">Read More</a>
    </div>
    
    <div class="box box-grey">
      <div class="icon">
        <img src="JavaScript-Logo.png" width="100" height="100"alt="">
      </div>
      <h2>Javascript</h2>
      <hr>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda labore.</p>
      <a href="#">Read More</a>
    </div>

  </div>

</div>
<br>
<div class="container">
  <div class="details">
    <h2>Back-End Tools We use</h2>

  </div>
  <div class="main-box">
    <div class="box box-grey">
      <div class="icon">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAK0AAABsCAMAAAAvxcJgAAAAYFBMVEVPW5P///9OWpJZZJg1RYdIVZDf4eoyQoZFUo5LWJHn6e9BT42KkLM7Soo/TYzY2uW3u89ibJ3Gydmytsz5+fuQlreBiK7x8vZ1fqeXnbtveKTR0+C+wdQpO4OrsMieo7+HAvuJAAAERklEQVR4nO2c27KqMAyGOdtSQDkooi58/7fctEmLstkXYRFnnN3/Sq1pv0mTNMUZgzr+HtVBLKNvkYyDOAq+RZGnZZOn5ZOn5ZOn5ZOn5ZOn5ZOn5ZOn5ZOn5ZOn5ZOn5ZOn5ZOn5ZOn5dN/TxulRvtOilPvTivjc6HFsWP704pnqJXJXWcF7U9bPQztQ+w6K2h32kgeDe3zK2hl3BvaK0ea7U97M7Cd+IosE4OhzQ97Tmq1O23ZQJJVe05qtZFWJa8qhXRzJLmhvfzAiErlv40+RCueeTbr2AxXe3bZJMtxZCxihfOrMVsYCWombqS9hwtlNwW0l24xkrfgRFvaZnXHWn2AVsb5kjYMx1IPpc+/R3Ipg9nrb3qWH6Ct/143DAu9r+qxMtJoF2JpW+hCCoZNtOllbeFel9gyWxnJ48m54rxmlJNiYROtOsFKz2F4jo+j3eHzdNgm8HKc1J4aDJjuJl1pyxZGJOduok0gX04HIYSqZNzCwvfSxUiijFLwdHeVrrSNxkjJGEOmoUTuFtpIgGMKcEskf6AOZKk9yTLcX+wetW+joH/15WQUvn2VjVbegO5myztuch5HFbw6YQOWDi5u0+scFGAEVTCThOW30KbnOXeMsKWdPli0i2I0b49q7h/cajaOuWktg+tg3cKy7iFOMXVKgNdNA2bm3fUPOMYeCQqTzC18gJA8lhK2u09xysNcLBQkXOvgMNjv3FlWdo7hDepULdpFGcCADpkqfE2yaeEyXODz0L4yGGECTSS2XUR/iQIyS8zHn2vS7WFxY663KTCEbgsVMHYywppqvV6dXICj13tnhI2RCxou2goOg8yGrYwhMh5Tr/Ve2pBI17MSysbd7rv19Yl02dxAq4ChhXUiiYUzrCX2Dz3GiG3VBu1byMzRGlXZIpyYaC3DWaXpdIQGNcJORygeXUfcXXuhnFwtazAqrBH2uifujhFPsm64Xi/D2NieSztUwHY3GCMY4Lo3w9LWnd+N8oC2Np3WJtm7unrKbTHvvBYmWZb8q13sYuJVh06r2rV1L0J3OzaA4ZsJuFCfItVak95fqc9z6LTJ8nqld/T2ejtIcGo1t2qHlatRTr2VbaEtl9fEMB9Ls6MKkizHzMFY1fUsEmtGH7ihyxoWzkH3x3CNMatUaz5qbbtYmLfHKf0sONhk2ijY8niETGvbRXXQSsrq5clHZT5z+yvgK3J+plvCJ8mrESutgCS7k7JZQHVoyIG6EN23eJqSFk7xJPs0bZRiolOKTyQh1n/9TJdKa9vFgJLQtoWpfvs0k0prH3z8UBbBk6wjGa2JSmtb1oSyCDbppEcHqyLTQr6Q7ieBgCP49z+ckOP2on+5O9e0c8gYFUSjFdErmBFx3U1GK/rvf5VmlKflk6flk6flk6flk6flk6flk6flk6flk6flk6flk6flk6flk6flk6flk6b9qn/X+ap/LvoD77Q6xBptHdQAAAAASUVORK5CYII=" height="100"width="100" alt="">
      </div>
      <h2>PHP</h2>
      <hr>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda labore.</p>
      <a href="#">Read More</a>
    </div>

    <div class="box box-red">
      <div class="icon">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRjfVpHWsxI7_YtZ9JllCCftZzimhf1rmB3S0-4HdF3bA&s" height="100" width="100" alt="">
      </div>
      <h2>SQL</h2>
      <hr>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda labore.</p>
      <a href="#" class="white-border">Read More</a>
    </div>
    
    <div class="box box-grey">
      <div class="icon">
        <img src="https://w7.pngwing.com/pngs/609/443/png-transparent-django-original-logo-icon.png" height="100" width="100" alt="">
      </div>
      <h2>DJango</h2>
      <hr>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda labore.</p>
      <a href="#">Read More</a>
    </div>

  </div>

</div>
<!-- testimonials -->
<br>
<hr>
<div class="outerdiv">
        <h1 align="left">What do our testimonials say?</h1>
  <div class="innerdiv">
    <!-- div1 -->
    <div class="div1 eachdiv">
      <div class="userdetails">
        <div class="imgbox">
          <img src="https://raw.githubusercontent.com/RahulSahOfficial/testimonials_grid_section/5532c958b7d3c9b910a216b198fdd21c73112d84/images/image-daniel.jpg" alt="">
        </div>
        <div class="detbox">
          <p class="name">Daniel Clifford</p>
          <p class="designation">Verified Graduate</p>
        </div>
      </div>
      <div class="review">
        <h4>I received a job offer mid-course, and the subjects I learned were current, if not more so, in the company I joined. I honestly feel I got every penny’s worth.</h4>
      <p>“ I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a transition and have heard some people who had an amazing experience here. I signed up for the free intro course and found it incredibly fun! I enrolled shortly thereafter. The next 12 weeks was the best - and most grueling - time of my life. Since completing the course, I’ve successfully switched careers, working as a Software Engineer at a VR startup. ”</p>
      </div>
    </div>
    <!-- div2 -->
    <div class="div2 eachdiv">
      <div class="userdetails">
        <div class="imgbox">
          <img src="https://raw.githubusercontent.com/RahulSahOfficial/testimonials_grid_section/5532c958b7d3c9b910a216b198fdd21c73112d84/images/image-jonathan.jpg" alt="">
        </div>
        <div class="detbox">
          <p class="name">Jonathan Walters</p>
          <p class="designation">Verified Graduate</p>
        </div>
      </div>
      <div class="review">
        <h4>The team was very supportive and kept me motivated</h4>
      <p>“ I started as a total newbie with virtually no coding skills. I now work as a mobile engineer for a big company. This was one of the best investments I’ve made in myself. ”</p>
      </div>
    </div>
    <!-- div3 -->
    <div class="div3 eachdiv">
      <div class="userdetails">
        <div class="imgbox">
          <img src="https://raw.githubusercontent.com/RahulSahOfficial/testimonials_grid_section/5532c958b7d3c9b910a216b198fdd21c73112d84/images/image-kira.jpg" alt="">
        </div>
        <div class="detbox">
          <p class="name dark">Kira Whittle</p>
          <p class="designation dark">Verified Graduate</p>
        </div>
      </div>
      <div class="review dark">
        <h4>Such a life-changing experience. Highly recommended!</h4>
        <p>“ Before joining the bootcamp, I’ve never written a line of code. I needed some structure from professionals who can help me learn programming step by step. I was encouraged to enroll by a former student of theirs who can only say wonderful things about the program. The entire curriculum and staff did not disappoint. They were very hands-on and I never had to wait long for assistance. The agile team project, in particular, was outstanding. It took my learning to the next level in a way that no tutorial could ever have. In fact, I’ve often referred to it during interviews as an example of experience. It certainly helped me land a job as a full-stack 100% recommend! ”</p>
      </div>
    </div>
    <!-- div4 -->
    <div class="div4 eachdiv">
      <div class="userdetails">
        <div class="imgbox">
          <img src="https://raw.githubusercontent.com/RahulSahOfficial/testimonials_grid_section/5532c958b7d3c9b910a216b198fdd21c73112d84/images/image-jeanette.jpg" alt="">
        </div>
        <div class="detbox">
          <p class="name dark">Jeanette Harmon</p>
          <p class="designation dark">Verified Graduate</p>
        </div>
      </div>
      <div class="review dark">
        <h4>An overall wonderful and rewarding experience</h4>
      <p>“ Thank you for the wonderful experience! I now have a job I really enjoy, and make a good living while doing something I love. ”</p>
      </div>
    </div>
    <!-- div5 -->
    <div class="div5 eachdiv">
      <div class="userdetails">
        <div class="imgbox">
          <img src="https://raw.githubusercontent.com/RahulSahOfficial/testimonials_grid_section/5532c958b7d3c9b910a216b198fdd21c73112d84/images/image-patrick.jpg" alt="">
        </div>
        <div class="detbox">
          <p class="name">Patrick Abrams</p>
          <p class="designation">Verified Graduate</p>
        </div>
      </div>
      <div class="review">
        <h4>Awesome teaching support from TAs who did the bootcamp themselves. Getting guidance from them and learning from their experiences was easy.</h4>
      <p>“ The staff seem genuinely concerned about my progress which I find really refreshing. The program gave me the confidence necessary to be able to go out in the world and present myself as a capable junior developer. The standard is above the rest. You will get the personal attention you need from an incredible community of smart and amazing people. ”</p>
      </div>
    </div>
  </div>
</div>
<br>
<hr>

<!-- contact -->
<div class="container">
	<div class="row">
			<h1>Contact Us</h1>
	</div>
	<div class="row">
			<h4 style="text-align:center">We'd love to hear from you!</h4>
	</div>
	<div class="row input-container">
			<div class="col-xs-12">
				<div class="styled-input wide">
					<input type="text" required />
					<label>Name</label> 
				</div>
			</div>
			<div class="col-md-6 col-sm-12">
				<div class="styled-input">
					<input type="text" required />
					<label>Email</label> 
				</div>
			</div>
			<div class="col-md-6 col-sm-12">
				<div class="styled-input" style="float:right;">
					<input type="text" required />
					<label>Phone Number</label> 
				</div>
			</div>
			<div class="col-xs-12">
				<div class="styled-input wide">
					<textarea required></textarea>
					<label>Message</label>
				</div>
			</div>
			<div class="col-xs-12">
				<div class="btn-lrg submit-btn">Send Message</div>
			</div>
	</div>
</div>


<!-- footer -->
<footer class="footer-distributed">

  <div class="footer-left">
      <img src="logo.jpg" height="100%" width="100%">

    <p class="footer-links">
      <a href="#">What we do</a>
      |
      <a href="#">Our Ideologies</a>
      |
      <a href="#">Methodologies</a>
      |
      <a href="#">Ideologies we follow</a>
      |
      <a href="#">Contact Us</a>
    </p>

    <p class="footer-company-name">© 2023 Web Assasins IT Solutions Pvt. Ltd.</p>
  </div>

  <div class="footer-center">
    <div>
      <i class="fa fa-map-marker"></i>
        <p><span>N.M.A.M Institute of Technology
                Karkala,Nitte
        </p>
    </div>
    <div>
      <i class="fa fa-envelope"></i>
      <p><a href="mailto:webassasins.com">webassasins@gmail.com</a></p>
    </div>
  </div>
  <div class="footer-right">
    <p class="footer-company-about">
      <span>About the company</span>
      We offer multiple services like Web Development, App Development, Social Media Management, Graphic Designing with latest technologies.</p>
    <div class="footer-icons">
      <a href="#"><i class="fa fa-facebook"></i></a>
      <a href="#"><i class="fa fa-twitter"></i></a>
      <a href="#"><i class="fa fa-instagram"></i></a>
      <a href="#"><i class="fa fa-linkedin"></i></a>
      <a href="#"><i class="fa fa-youtube"></i></a>
    </div>
  </div>
</footer>
</body>
</html>
</body>
</html>
