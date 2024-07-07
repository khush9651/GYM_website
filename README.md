# Gym Website Frontend

## Overview

This project is a modern, responsive frontend website for a gym. It provides information about the gym's services, trainers, membership plans, and contact details. The website is designed to be user-friendly and visually appealing, making it easy for visitors to find the information they need and sign up for memberships.

## Features

- **Homepage**: Overview of the gym, its facilities, and services.
- **About Us**: Information about the gym's history, mission, and team.
- **Services**: Details about the different services offered, including personal training, group classes, and nutrition plans.
- **Trainers**: Profiles of the gym's trainers, including their qualifications and specializations.
- **Membership Plans**: Information about different membership options and pricing.
- **Contact Us**: Contact form and contact details for the gym.
- **Responsive Design**: The website is fully responsive and works well on desktops, tablets, and mobile devices.

## Technologies Used

- **HTML5**: Structure and content of the website.
- **CSS3**: Styling and layout.
- **JavaScript**: Interactive features and functionality.
- **Bootstrap**: Responsive design and components.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/gym-website-frontend.git
   cd gym-website-frontend
   ```
2. **Open the project:**
   Open the index.html file in your web browser to view the homepage.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Agbalumo&family=Balsamiq+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Hubballi&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FITNESS</title>
    <style>
        /* CSS reset */
        body {
            font-family: "Roboto", sans-serif;
            font-weight: 400;
            font-size: 14px;
            font-style: normal;
            color: #72a7a1;
            margin: 0px;
            padding: 0px;
            background: url('img/img2.jpg');
        }
        .left {
            display: inline-block;
            /* border: 2px solid red; */
            position: absolute;
            left: 34px;
            top: 20px;
        }
        .left img {
            width: 53px;
            border-radius: 128px;
            padding: 4px 19px;
            filter: invert(100%);  /*convert black image to white and white to black  */
        }
        .left div {
            text-align: center;
            font-size: 18px;
            color:#ecfeff;;
        }
        .mid {
            display: block;
            width: 55%;
            margin: 20px auto;
            /* border: 2px solid black; */
            top: 20px;
        }
        .right {
            display: inline-block;
            /* border: 2px solid pink; */
            position: absolute;
            right: 34px;
            top: 20px;
        }
        .navbar {
            display: inline-block;
        }
        .navbar li {
            color: white;
            font-size: 25px;
            list-style: none; /* Add this to remove the default list style */
            display: inline; /* Add this to display list items horizontally */
        }
        .navbar li a {
            color: white;
            text-decoration: none;
            padding: 11px 18px;
            font-size: 20px;
        }
        .navbar li a:hover, .navbar li a.active {
            color: #88cdc6;
            text-decoration: blink;
        }
        .btn{
            font-family: "Roboto", sans-serif;
            margin: 14px 0px;
            color: white;
            padding: 4px 14px;
            border: 13px black;
            border-radius: 8px;
            font-size: 17px;
            cursor: pointer;
            background-color: #741c1c;
        }
        .btn:hover{
            background-color: #72a7a1;
        }
        .container{
            border: 2px solid white;
            margin: 142px 75px;
            padding: 41px 41px;
            width: 31%;
            border-radius: 28px;
        }
        .form-group input{
            text-align: center;
            display: block;
            width: 323px;
            border: 5px solid white;
            padding: 2px 2px;
            margin: 11px auto;
            font-size: 13px;
            border-radius: 4px;
            font-family: "Roboto", sans-serif;
            
        }
        .container button{
            display: block;
            width: 82%;
            margin: auto;
            padding: 4px 0px;
            font-size: 14px;
        }
        .container h1 {
            text-align: center;
            font-size: 21px;
            color: #5ed5d5;
        }
        div.container{
            padding-left: 47px;
            padding-bottom: 77px;
        }
        .form-group input::placeholder {
            color: black;
        }
        
    </style>
</head>
<body>
    <header class="header">
        <!-- Left box for logo -->
        <div class="left">
            <img src="img/gym.jpg" alt="">
            <div>Fitness</div>
        </div>
        <!-- Mid box for navigation -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Fitness calculator</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>
        <!-- Right box for buttons -->
        <div class="right">
            <button class="btn">Call Us </button>
            <button class="btn">Email Us</button>
        </div>
    </header>
    <div class="container">
        <h1>Join the best gym of DELHI</h1>
        <form action="no action.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Locality">
            </div>
            <button class="btn">Submit</button>

        </form>
    </div>
</body>
</html>
```

## Usage

### Open the website:

- Open `index.html` in your web browser to view the homepage.

### Navigate through the website:

- Use the navigation bar to explore different sections of the website, such as About Us, Services, Trainers, Membership Plans, and Contact Us.

## Contact Form:

- Fill out the contact form in the Contact Us section to send a message to the gym.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

## Fork the repository:

- Click the "Fork" button at the top right of the repository page.

### Clone your fork:

```bash
git clone https://github.com/yourusername/gym-website-frontend.git
cd gym-website-frontend
```

### Create a new branch:

```bash
git checkout -b feature/your-feature-name
```

### Make your changes and commit them
```bash
git commit -m "Add your message here"
```

### Push your changes to your fork
```bash
git push origin feature/your-feature-name
```

## Create a pull request
Open a pull request from your forked repository to the main repository.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or inquiries, please contact Khushi at khush9651@gmail.com.
