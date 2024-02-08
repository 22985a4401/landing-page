# landing-page
octanet service first task for creating landing page
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content=
		"width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="index.css">
	<title>Landing Page</title>
</head>

<body>
	<nav>
		<div class="heading">Landing Page</div>
		<span class="sideMenuButton"
			onclick="openNavbar()">
			☰
		</span>

		<div class="navbar">
			<ul>
				<li><a href="#Home">Home</a></li>
				<li><a href="#">About</a></li>
				<li><a href="#">Sign Up</a></li>
			</ul>
		</div>
	</nav>

	<!-- Side navigation bar for 
		responsive website -->
	<div class="sideNavigationBar"
		id="sideNavigationBar">
		<a href="#" class="closeButton"
			onclick="closeNavbar()">
			
		</a>
		<a href="#">Home</a>
		<a href="#">About</a>
		<a href="#">Sign Up</a>
	</div>

	<!-- Content -->
	<div class="line" id="Home">
		<div class="side1">
			<h1>OctaNet</h1>
		</div>
		<div class="side2">
			<img src=
"https://media.geeksforgeeks.org/wp-content/cdn-uploads/20220401124017/HTML-Tutorial.png"
				width="500">
		</div>
	</div>

	<section class="about" id="My Projects">
		<div class="content">
			<div class="title">
				<span>Courses</span>
			</div>
			<div class="boxes">
				<div class="box">
					<div class="topic">
						<a href="" target="_blank">
							DSA
						</a>
					</div>
					<p>
						The term DSA stands for Data 
						Structures and Algorithms. As 
						the name itself suggests, it 
						is a combination of two 
						separate yet interrelated 
						topics.
					</p>
				</div>
				<div class="box">

					<div class="topic">
						<a href="" target="_blank">
							HTML
						</a>
					</div>
					<p>
						HTML stands for HyperText 
						Markup Language. It is used 
						to design web pages using 
						the markup language.
					</p>
				</div>

				<div class="box">
					<div class="topic">
						<a href="" target="_blank">
							Javascript
						</a>
					</div>
					<p>
						JavaScript (JS) is the most 
						popular lightweight, interpreted 
						compiled programming language.
					</p>
				</div>
			</div>
		</div>
	</section>

	<section class="contact" id="contact">
		<div class="content">
			<div class="title"><span>Sign Up</span></div>
			<div class="contactMenu">
				<div class="input1">
					<div class="label1">Your Name</div>
					<div class="input2">
						<input type="text"
							placeholder="Enter your Name here">
					</div>
					<div class="label1">
						<label>Your Email</label>
					</div>
					<div class="input2">
						<input type="text"
							placeholder="Enter your Email here">
					</div>
					<div class="label1">
						<label>Your Password</label>
					</div>
					<div class="input2">
						<input type="text"
							placeholder="Enter your Password here">
					</div>
					<div class="button">
						<button>Sign Up</button>
					</div>
				</div>
				<div class="input3">
					<div class="rightside1">
						<div class="title1">
							<span>
								Contact Us
							</span>
						</div>
						<div class="content1">
							Address: Bengaluru , India Bhubaneswar , India Phone: +91 7789001085 Email: support@octanet.
						</div>
						<div class="title1">
							<span>More Information</span>
						</div>
						<div class="content1">
							Thanking octanet services for providing 
							free internship for the student in order
							to developing student resume in strong 
							manner and also providing hands on experience
							for the students.
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- Footer section -->
	<footer>
		<div class="footer">
			<span>
				Created By
				<a href="https://octanet.in/"
					target="_blank">
					Octanet
				</a>
			</span>
		</div>
	</footer>
	<script src="index.js"></script>
</body>

</html>
