<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Final HTML Project</title>
    <link rel="stylesheet" href="bootstrap.css">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <style>
        /* Custom Font */
        @font-face {
            font-family: manga;
            src: url('mangat.ttf');
        }

        /* General Typography */
        h1, h2, h3, p {
            font-family: manga;
            text-align: center;
        }

        h1 {
            font-size: 60px;
        }

        h2 {
            font-size: 40px;
        }

        h3 {
            font-size: 20px;
        }

        /* Background and Overall Layout */
        body {
            background-image: url('bg/bg1.png');
            background-size: auto 100%;
            background-repeat: repeat-x;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Navbar Styling */
        .navbar {
            background-color: #f3f3f3; /* Light grey background */
        }

        .navbar-brand {
            color: #333333; /* Dark grey color for brand */
        }

        .navbar-nav .nav-link {
            color: #808080; /* Grey color for nav links */
        }

        .navbar-nav .nav-link:hover {
            color: black; /* Black color on hover */
        }

        /* Jumbotron and Header */
        .jumbotron-color {
            background-color: rgba(255, 255, 255, 0.9); /* Semi-transparent white */
            margin-top: 20px;
            padding: 20px;
            border: solid 2px black;
        }

        /* Background Colors Section */
        .bg-colors {
            background-color: #808080;
            padding-top: 10px;
            padding-bottom: 10px;
        }

        /* Cards and Content Sections */
        .card {
            margin-top: 20px;
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .card-background {
            background-image: url('bg/home_bg.png');
            background-size: cover;
            background-position: center;
            height: 200px; /* Adjust height as needed */
            position: relative;
            border-radius: 5px;
        }

        .card-background h1 {
            color: white;
            font-size: 40px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 0px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
		
		html {
			scroll-behavior: smooth;
		}
		
    </style>
</head>

<body>

    <div class="container">
        <div class="container-fluid bg-colors">
            <div class="container">
                <div class="jumbotron jumbotron-color">
                    <h1>PROJECT: DATABASE</h1>
                    <h3>Welcome to Ken Lester Taupo's Project Database!</h3>

                    <nav class="navbar navbar-expand-lg navbar-expand-md">
                        <a class="navbar-brand" href="#home">Home</a>
                        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav ml-auto">
                                <li class="nav-item">
                                    <a class="nav-link" href="#projects">Projects</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#github">GitHub</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#about">About</a>
                                </li>
                            </ul>
                        </div>
                    </nav>

                </div>
            </div>

            <div class="container">
                <p>This is my archive for all the projects I made in ITEC87!</p>

                <div class="row">
                    <div class="col-md-12">
                        <h2>This is made using Bootstrap 4!</h2>
                        <hr class="mt-2 mb-3" />
                    </div>
                </div>

                <div class="card p-2 m-3">
                    <div class="card-background">
                        <h1 id="home">Home</h1>
                    </div>
                </div>

                <div class="container p-3">
                    <div class="card p-4" id="projects">
                        <div class="text-center">
                            <h2>Projects</h2>
                        </div>
                    </div>
                    <div class="row mt-4">
                        <div class="col-md-6">
                            <div class="card">
                                <img src="fg/card1.png" class="card-img-top p-2 rounded" alt="Image 1">
                                <div class="card-body">
                                    <h5 class="card-title" style="text-align: center;">Bootstrap Resume</h5>
                                    <button class="btn btn-primary btn-block" data-toggle="modal" data-target="#customModal1">Read more</button>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="card">
                                <img src="fg/card2.png" class="card-img-top p-2 rounded" alt="Image 2">
                                <div class="card-body">
                                    <h5 class="card-title" style="text-align: center;">Sari-sari Store</h5>
                                    <button class="btn btn-primary btn-block" data-toggle="modal" data-target="#customModal2">Read more</button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row mt-4">
                        <div class="col-md-6">
                            <div class="card">
                                <img src="fg/card3.png" class="card-img-top p-2 rounded" alt="Image 3">
                                <div class="card-body">
                                    <h5 class="card-title" style="text-align: center;">Certificate of Registration</h5>
                                    <button class="btn btn-primary btn-block" data-toggle="modal" data-target="#customModal3">Read more</button>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="card">
                                <img src="fg/card4.png" class="card-img-top p-2 rounded" alt="Image 4">
                                <div class="card-body">
                                    <h5 class="card-title" style="text-align: center;">Restaurant</h5>
                                    <button class="btn btn-primary btn-block" data-toggle="modal" data-target="#customModal4">Read more</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="container p-3">
                    <div class="card p-4" id="github">
                        <div class="text-center">
                            <h2>GitHub</h2>
                        </div>
                    </div>

                    <div class="card" style="background-color:white">
                        <img src="bg/github.png" class="card p-1" alt="github image" style="max-width: 100%; height: auto; display: block; margin: 0;">
                        <div class="container p-1">
                            <a href="https://github.com/safeart02" target="_blank" class="btn btn-block btn-primary" type="button">Check out my GitHub!</a>
                        </div>
                    </div>
                </div>

                <div class="container p-3">
                    <div class="card p-4" id="about">
                        <div class="text-center">
                            <h2>About</h2>
                        </div>
                    </div>
                </div>

                <div class="container">
                    <div class="card p-2" style="background-color:white;">
                        <div class="row">
                            <div class="col-sm-4">
                                <img src="fg/coder.png" alt="weird" style="width:100%">
                            </div>
                            <div class="col-sm pt-4">
                                <p>"Hi! My name is Ken Lester Taupo and this is my archive! I hope you liked the archive I made! It is primarily using Bootstrap 4 as the format for the styles and it really helped 
                                    me in making this site pretty quick!"</p>
                                <p>-someone who looks like they didn't get enough sleep.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="modal fade" id="customModal1" tabindex="-1" role="dialog" aria-labelledby="customModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document" style="max-width: 90%;">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="customModalLabel">Custom Modal Title</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <span aria-hidden="true">&times;</span>
                </button>
            </div>
            <div class="modal-body">
                <iframe src="https://rawcdn.githack.com/safeart02/Bootstrap-Resume/3bbddf71757465b6e3621d84751ec54130c566e9/RESUME/resume.html" style="width: 100%; height: 80vh; border: none;"></iframe>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                <!-- Additional buttons or actions if needed -->
            </div>
        </div>
    </div>
</div>

    <div class="modal fade" id="customModal2" tabindex="-1" role="dialog" aria-labelledby="customModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document" style="max-width: 90%;">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="customModalLabel">Custom Modal Title</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <span aria-hidden="true">&times;</span>
                </button>
            </div>
            <div class="modal-body">
                <iframe src="https://rawcdn.githack.com/safeart02/SariSariStore/ca38008fe2a2d602db487ab3ae760b9c2cace9b2/taupo_kenlester_sarisaristore_act/sarisariStore.html" style="width: 100%; height: 80vh; border: none;"></iframe>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                <!-- Additional buttons or actions if needed -->
            </div>
        </div>
    </div>
</div>



    <div class="modal fade" id="customModal3" tabindex="-1" role="dialog" aria-labelledby="customModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document" style="max-width: 90%;">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="customModalLabel">Custom Modal Title</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <span aria-hidden="true">&times;</span>
                </button>
            </div>
            <div class="modal-body">
                <iframe src="https://rawcdn.githack.com/safeart02/COR/3058989abf7eb80c0778b80b09441d42c30551ca/COR/COR.html" style="width: 100%; height: 80vh; border: none;"></iframe>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                <!-- Additional buttons or actions if needed -->
            </div>
        </div>
    </div>
</div>

    <div class="modal fade" id="customModal4" tabindex="-1" role="dialog" aria-labelledby="customModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document" style="max-width: 90%;">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="customModalLabel">Custom Modal Title</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <span aria-hidden="true">&times;</span>
                </button>
            </div>
            <div class="modal-body">
                <iframe src="https://rawcdn.githack.com/safeart02/Restaurant/1fd1646b88885e27e85c8e3949123919206fc48f/Restaurant/Taupo_Restaurant.html" style="width: 100%; height: 80vh; border: none;"></iframe>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                <!-- Additional buttons or actions if needed -->
            </div>
        </div>
    </div>
</div>
	
	<!-- Add this script after your modal HTML -->
<script>
$(document).ready(function() {
    // Function to load external content into modal body
    function loadResumeIntoModal() {
        // URL of the external HTML file
        var resumeUrl = 'https://rawcdn.githack.com/safeart02/Bootstrap-Resume/3bbddf71757465b6e3621d84751ec54130c566e9/RESUME/resume.html';
        
        // Fetch the HTML content
        $.get(resumeUrl, function(data) {
            // On success, replace the modal body with the fetched content
            $('.modal-body').html(data);
        });
    }

    // Call the function to load resume into modal body
    loadResumeIntoModal();
});
</script>


    <footer>
        <p>&copy; 2024 Ken Lester Taupo. All rights reserved.</p>
    </footer>

</body>

</html>
