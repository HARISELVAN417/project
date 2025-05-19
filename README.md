# Project Responsive Web Design using Bootstrap
# Date:19-05-2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
Developed By:HARISELVAN S
Reg No:212224040103

page1.html:

<!DOCTYPE html>
<html>

<head>
    <title>foodapp</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="foodhome.css">
</head>

<body>
    <div id="section1">
        
        <div class="all d-flex flex-column justify-content-center">
            <div class="containerwww">
        <ul class="dropdowndrop">
            <li><a href="#">Home</a></li>
            <li><a href="#">ContactUs</a></li>
            <li><a href="#">List</a>
                <ul class="product1">
                    <li><a href="#">Veg</a></li>
                    <li><a href="#">Non-Veg</a>
                        <ul class="foodname">
                            <li onclick="display('sectionmenu')"><a href="#">Chicken Briyani</a></li>
                            <li><a href="#">Mutton Briyani</a></li>
                            <li><a href="#">Beef Briyani</a></li>
                            <li><a href="#">Chilli Chicken</a></li>
                            <li><a href="#">Beef Chilli</a></li>
                        </ul>
                    </li>
                    <li><a href="#">Chinese Foods</a></li>
                    <li><a href="#">American Noodels</a></li>
                    <li><a href="#">African Foods</a></li>
                </ul>
            </li>
            <li><a href="#">Logout</a></li>
            <li><a href="login.html">Login</a></li>
        </ul>
    </div>
            <div class="container253">
                <h1 class="main">FOOD APP</h1>
                <p class="para">order your food in low price and 24 hour service</p>
                <button class="button btn btn-primary" id="projectbrindhabutton" onclick="display('section2')">Get Started</button>
            </div>
        </div>
    </div>

    <div id="section2">
        <div class="bg-cont">
            <div class="cont1 d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/free-photo/top-view-delicious-eggplant-rolls-with-potatoes-fresh-vegetables-dark-background-dish-dinner-ripe-meal-food_140725-116130.jpg?t=st=1745128513~exp=1745132113~hmac=866693b2f7d4f4d2ff0089b2d1c1946b65f491bbd95cd5fd6df8b4cb93023ae7&w=1380" class="image">
                <h1 class="mh">FOODIE</h1>
            </div>
            <div class="cont2 d-flex flex-row justify-content-between">
                <h2 class="mh2 btn" onclick="display('section1')">Home</h2>
                <h2 class="mh2 btn" onclick="display('sectionmenu')">menu</h2>
                <h2 class="mh2 btn" onclick="display('section4')">Administration</h2>
                <h2 class="mh2 btn" onclick="display('section3')">Contact us</h2>
            </div>
            <div class="cont3">
                <h1 class="mh3">30% off This weekend</h1>
                <p class="para1">Todays offers are more,and exiting free foods and 30% discount offer available in this week,location:vellore,vaduganthangal,e.b.colony,tamlinadu.all are come and enjoy to taste the delicious foods</p>
            </div>
            <div class="overall-cont456 d-flex flex-row">
                <div class="cont4 d-flex flex-column">
                    <h2>Our New menu</h2>
                    <img src="https://img.freepik.com/free-photo/view-delicious-dish-food_23-2150777655.jpg?t=st=1745130040~exp=1745133640~hmac=3d6cb96fa4c27e062ea140328f5193b07a5fd1cadf998db2ac330d0137ed0917&w=1380" class="image2">
                    <p>Indulge in the rich aroma and irresistible flavors of our signature Biryani a timeless dish crafted with fragrant basmati rice, slow-cooked marinated meat or veggies, and a blend of authentic spices. Each spoonful is a celebration of tradition, taste, and love.</p>
                </div>
                <div class="cont5 d-flex flex-column">
                    <h2>OFFER</h2>
                    <img src="https://img.freepik.com/free-photo/delicious-food-table_23-2150857814.jpg?t=st=1745130354~exp=1745133954~hmac=93db52a7e13bf2fed21200de838638ed48a674f47cdf849dcd4f18817bdb83f6&w=1380" class="image2">
                    <p>Ah, you want content for a meal combo or full meal plate that includes all meals at one fixed rate perfect for a set menu or thali concept. Here's some catchy and appetizing content for that:</p>
                </div>
                <div class="cont6 d-flex flex-column">
                    <h2>Food Timing</h2>
                    <img src="https://img.freepik.com/free-photo/hands-holding-knife-fork-alarm-clock-plate-blue-background_169016-21525.jpg?t=st=1745130548~exp=1745134148~hmac=e406e15a2b7d7cf38c560433b8d2a6504838e4ae3e07217956d5f0d0c386d424&w=1380" class="image2">
                    <p>We serve delicious, freshly prepared meals every day from 10:00 AM to 4:00 PM, making it the perfect time for a hearty brunch, a fulfilling lunch, or a mid-day treat. During these hours, you can enjoy a variety of options including our popular All-in-One Meals, Biryani Specials, Roti & Curry Combos, and more</p>
                </div>
            </div>
            <h1 class="hari">Design and Developed by <span>Hariselvan S</span></h1>
        </div>
    </div>
    <div id="section3">
        <div class="adjust">
        <div class="contact-section">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required />
                <input type="email" placeholder="Your Email" required />
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
            <button class="backbutton1 btn btn-dark" onclick="display('section2')">Back</button>
        </div>
        </div>
    </div>
    <div id="section4">
        <div class="admin-container">
            <aside class="sidebar">
                <h2>Admin Panel</h2>
                <ul>
                    <li><a href="#" onclick="showCustomAlert()">Dashboard</a></li>
                    <li><a href="#" onclick="showCustomAlert()">Orders</a></li>
                    <li><a href="#" onclick="showCustomAlert()">Users</a></li>
                    <li onclick="display('sectionmenu')"><a href="#">Menu</a></li>
                    <li><a href="#" onclick="showCustomAlert()">Settings</a></li>
                    <li><a href="#" onclick="showCustomAlert()">Logout</a></li>
                </ul>
            </aside>
            <main class="main-content">
                <header>
                    <h1>Welcome, Admin</h1>
                </header>
                <section class="dashboard">
                    <div class="card">
                        <h3>Total Orders</h3>
                        <p>124</p>
                    </div>
                    <div class="card">
                        <h3>Total Users</h3>
                        <p>89</p>
                    </div>
                    <div class="card">
                        <h3>Revenue</h3>
                        <p>$2,350</p>
                    </div>
                </section>
            </main>
        </div>
        <button class="backbutton btn btn-dark" onclick="display('section2')">Back</button>
    </div>

    <div id="sectionmenu">
        <div class="favourite-places-bg-container">
            <h1 class="favourite-places-heading">Food Menu</h1>

            <div class="favourite-place-card-container d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/premium-photo/yummy-chicken-pulao-isolated-white-background_787273-55616.jpg?w=826" class="favourite-place-card-image" />
                <div>
                    <h1 class="favourite-place-card-heading">Chicken Briyani</h1>
                    <p class="favourite-place-card-description">
                        Slow-cooked for deep flavor,100% fresh ingredients,served hot with raita & salan,A taste that keeps you coming back for more!
                    </p>
                    <p class="favourite-place-card-heading">Rs.150</p>
                </div>
            </div>

            <div class="favourite-place-card-container d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/free-photo/side-view-baked-chicken-with-cucumber-lemon-seasoning-bread-table_141793-4757.jpg?t=st=1745395710~exp=1745399310~hmac=40381ed561ed5f15e602e0f67c4051210165c86fb087f95987dbf21cb5545716&w=1380" class="favourite-place-card-image" />
                <div>
                    <h1 class="favourite-place-card-heading">Tandhoori</h1>
                    <p class="favourite-place-card-description">
                        Authentic spices & marinades,Cooked in a real clay tandoor oven,Juicy inside, crisp & smoky outside,Served with mint chutney, lemon wedges & love!
                    </p>
                    <p class="favourite-place-card-heading">Rs.400</p>
                </div>
            </div>

            <div class="favourite-place-card-container d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/free-photo/delicious-food-table_23-2150857814.jpg?t=st=1745396269~exp=1745399869~hmac=44ad66dab997101c343cd217be4fac161372300a1c216d248c287144cfe4d4b2&w=1380" class="favourite-place-card-image" />
                <div>
                    <h1 class="favourite-place-card-heading">veg meals</h1>
                    <p class="favourite-place-card-description">
                        Steamed Rice with Ghee,Sambar, Rasam & Kootu,Variety of Poriyals & Curries,Fresh Curd, Pickles & Papad,Sweet Payasam to end on a sweet note!
                    </p>
                    <p class="favourite-place-card-heading">Rs.100</p>
                </div>
            </div>

            <div class="favourite-place-card-container d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/premium-photo/idly-idli-south-indian-main-breakfast-item-which-is-beautifully-arranged-aqua-color-plates_527904-2880.jpg?w=1380" class="favourite-place-card-image" />
                <div>
                    <h1 class="favourite-place-card-heading">Idly</h1>
                    <p class="favourite-place-card-description">
                        Idly, made fresh daily with perfectly fermented batter and steamed to soft, cloud-like perfection.Spicy Sambar,Coconut & Tomato Chutneys,A dash of homemade love
                    </p>
                    <p class="favourite-place-card-heading">Rs.20</p>
                </div>
            </div>
            <button class="backbutton btn btn-dark" onclick="display('section2')">Back</button>
        </div>
    </div>

    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  <script src="foodhome.js"></script>
</body>

</html>

page1.css:

.container253{
    background-color: #00000030;
    width: 700px;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    /* padding:50px; */
    display:block;
    margin:auto;
}

.all {
    background-image: url('https://plus.unsplash.com/premium_photo-1666432045848-3fdbb2c74531?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
    background-size: cover;
    height: 100vh;
    width: 100vw;
    /* padding:50px; */
    
}


.dropdowndrop{
    display: flex;
    list-style-type: none;
    justify-content: center;
    margin-top: 1px;
}
a{
    display: block;
    text-align: center;
    color: white;
    background-color: black;
    text-decoration: none;
    width: 310px;
    padding: 10px 0;
    font-size: 1.2rem;
}

a:hover {
    background-color: skyblue;
}

.product1 {
    list-style-type: none;
    display: none;
}

.dropdowndrop li:nth-child(3):hover .product1 {
    display: block;
    background-color:none;
}

.foodname {
    list-style-type: none;
    transform: translatex(312px) translatey(-45px);
    position: absolute;
    display: none;
}

.product1 li:nth-child(2):hover .foodname {
    display: block;
    
} 
.para {
    font-size: 40px;
    color: darkblue;

}

.main {
    font-size: 100px;
    color: rgb(9, 195, 220);
    text-align:center;
}

.button {
    color: black;
    background-color: #25b1cc;
    font-size: 30px;
    border-color: white;
    border-radius: 100px;
    animation-name: colorChange;
    animation-duration: 1s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    border: 0px;
    display:block;
    margin:auto;
}

.bg-cont {
    background-image: url("https://img.freepik.com/free-photo/slice-carrots-row-orange-background_23-2147927314.jpg?t=st=1745128315~exp=1745131915~hmac=81d063ff777a310327112cfd1c28afcbf203f13c6d0f2dfbbb9b4f1effd20c5f&w=740");
    background-size: cover;

}

.mh {
    color: white;
    font-weight: bold;
    font-size: 100px;
}

.image {
    height: 20%;
    width: 20%;
    border-radius: 50%;
}

.cont1 {
    padding: 10px;
}

.cont2 {
    background-color: #00000080;
}

.mh2 {
    color: white;
    font-size: 20px;
    margin: 5px;
}

.cont3 {
    background-image: url("https://img.freepik.com/free-photo/view-ready-eat-delicious-meal-go_23-2151431768.jpg?t=st=1745129261~exp=1745132861~hmac=40a5aa3cae67e1c09802f26acbca3be06d943d4a6ddefaedde9f67051dfbba9d&w=1380");
    background-size: cover;
    padding: 10px;
    border-radius: 25px;
    margin: 8px;
}

.mh3 {
    color: white;
}

.para1 {
    color: white;
}

.image2 {
    height: 50%;
    width: 100%;
}

.cont4 {
    background-color: #fdedec;
    border-radius: 10px;
    padding: 10px;
    margin: 10px;
}

.cont5 {
    background-color: #fdedec;
    border-radius: 10px;
    padding: 10px;
    margin: 10px;
}

.cont6 {
    background-color: #fdedec;
    border-radius: 10px;
    padding: 10px;
    margin: 10px;
}

.hari {
    font-size: 20px;
    color: white;
    padding: 50px;
    text-align: center;
}

span {
    color: red;
}

.contact-section {
    background-color: rgba(255, 255, 255, 0.85);
    height: 100vh;
    width: 100vw;
    padding: 100px;
    max-width: 600px;
    margin: 50px auto;
    margin-left: 50px auto;
    border-radius: 15px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    text-align: center;
}
.adjust{
    margin-left: 50%;
}
.contact-section h2 {
    margin-bottom: 20px;
    font-size: 2em;
    color: #004aad;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-form input,
.contact-form textarea {
    padding: 12px;
    font-size: 16px;
    border: 2px solid #004aad;
    border-radius: 10px;
    outline: none;
    transition: all 0.3s ease;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: #007bff;
    box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
}

.contact-form button {
    padding: 12px;
    font-size: 16px;
    background-color: #004aad;
    color: white;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    transition: background 0.3s ease;
}

.contact-form button:hover {
    background-color: #007bff;
}

.backbutton {
    display: block;
    margin: auto;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background-color: #f0f2f5;
    display: flex;
}

.admin-container {
    display: flex;
    width: 100%;
}

.sidebar {
    width: 220px;
    background-color: #004aad;
    color: white;
    height: 100vh;
    padding: 20px;
    position: fixed;
}

.sidebar h2 {
    margin-bottom: 30px;
    font-size: 24px;
}

.sidebar ul {
    list-style: none;
}

.sidebar ul li {
    margin-bottom: 20px;
}

.sidebar ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

.sidebar ul li a:hover {
    text-decoration: underline;
}

.main-content {
    margin-left: 220px;
    padding: 20px;
    width: calc(100% - 220px);
}

header h1 {
    margin-bottom: 30px;
}

.dashboard {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background-color: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    width: 200px;
    text-align: center;
}

.card h3 {
    margin-bottom: 10px;
    color: #004aad;
}

.card p {
    font-size: 24px;
    font-weight: bold;
}

.backbutton1 {
    display: block;
    margin: auto;
    margin-top: 10px;
}

.favourite-places-bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
    height: 100vh;
    background-size: cover;
    /* background-attachment: fixed; */
    overflow-y: auto;
}

.favourite-places-heading {
    color: #fff;
    font-size: 50px;
    font-weight: bold;
    padding: 24px;
    text-shadow: 0 0 5px #fff,
        0 0 10px #fff,
        0 0 20px #ff00ff,
        0 0 30px #ff00ff,
        0 0 40px #ff00ff,
        0 0 50px #ff00ff,
        0 0 60px #ff00ff;
    text-align: center;

}

.favourite-place-card-container {
    background-color: white;
    border-radius: 8px;
    padding: 16px;
    margin: 50px;
    background-attachment: fixed;
}

.favourite-place-card-heading {
    color: #0f0e46;
    font-family: "Roboto";
    font-size: 23px;
    font-weight: bold;
    text-align: center;
}

.favourite-place-card-description {
    color: #6c6b70;
    font-family: "Roboto";
    font-size: 13px;
    text-align: center;
}

.favourite-place-card-image {
    width: 80px;
    height: 100px;
}
.sss{
    background-color:black;
}

login.html:

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script src="https://kit.fontawesome.com/64d58efce2.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="login.css" />
    <title>Sign in & Sign up Form</title>
</head>

<body>
    <div class="container">
        <div class="forms-container">
            <div class="signin-signup">
                <form action="#" class="sign-in-form">
                    <h2 class="title">Sign in</h2>
                    <div class="input-field">
                        <i class="fas fa-user"></i>
                        <input type="text" placeholder="Username" />
                    </div>
                    <div class="input-field">
                        <i class="fas fa-lock"></i>
                        <input type="password" placeholder="Password" required />
                    </div>
                    <input type="submit" value="Login" class="btn solid" />
                    <p class="social-text">Or Sign in with social platforms</p>
                    <div class="social-media">
                        <a href="#" class="social-icon1">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="social-icon2">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="social-icon3">
                            <i class="fab fa-google"></i>
                        </a>
                        <a href="#" class="social-icon4">
                            <i class="fab  fa-linkedin-in"></i>
                        </a>
                    </div>
                </form>
                <form action="#" class="sign-up-form">
                    <h2 class="title">Sign up</h2>
                    <div class="input-field">
                        <i class="fas fa-user"></i>
                        <input type="text" placeholder="Username" required />
                    </div>
                    <div class="input-field">
                        <i class="fas fa-envelope"></i>
                        <input type="email" placeholder="Email" />
                    </div>
                    <div class="input-field">
                        <i class="fas fa-lock"></i>
                        <input type="password" placeholder="Password" required />
                    </div>
                    <input type="submit" class="btn" value="Sign up" />
                    <p class="social-text">Or Sign up with social platforms</p>
                    <div class="social-media">
                        <a href="#" class="social-icon1">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="social-icon2">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="social-icon3">
                            <i class="fab fa-google"></i>
                        </a>
                        <a href="#" class="social-icon4">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                    </div>
                </form>
            </div>
        </div>

        <div class="panels-container">
            <div class="panel left-panel">
                <div class="content">
                    <h3>Welocome To Foodie</h3>
                    <p>
                        Signup the foodie and ejoy the delicious foods and more exiting gifts
                    </p>
                    <button class="btn transparent" id="sign-up-btn">
                        Sign up
                    </button>
                </div>
                <img src="https://img.freepik.com/free-vector/vegetables-tray-lid-neon-sign_1262-19693.jpg?t=st=1746766182~exp=1746769782~hmac=4b6f8fb8f241c3beae1cee752f7f05d17258243977463ac60de85d1afa00278c&w=826" class="image" alt="not suppported" />
            </div>
            <div class="panel right-panel">
                <div class="content">
                    <h3>One of us ?</h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum
                        laboriosam ad deleniti.
                    </p>
                    <button class="btn transparent" id="sign-in-btn">
                        Sign in
                    </button>
                </div>
                <img src="https://img.freepik.com/free-vector/vegetables-tray-lid-neon-sign_1262-19693.jpg?t=st=1746766182~exp=1746769782~hmac=4b6f8fb8f241c3beae1cee752f7f05d17258243977463ac60de85d1afa00278c&w=826" class="image" alt="" />
            </div>
        </div>
    </div>
<script src="login.js"></script>
</body>

</html>

login.css:

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body,
input {
    font-family: "Poppins", sans-serif;
}

.container {
    position: relative;
    width: 100%;
    background-color: #fff;
    min-height: 100vh;
    overflow: hidden;
}

.forms-container {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
}

.signin-signup {
    position: absolute;
    top: 50%;
    transform: translate(-50%, -50%);
    left: 75%;
    width: 50%;
    transition: 1s 0.7s ease-in-out;
    display: grid;
    grid-template-columns: 1fr;
    z-index: 5;
}

form {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0rem 5rem;
    transition: all 0.2s 0.7s;
    overflow: hidden;
    grid-column: 1 / 2;
    grid-row: 1 / 2;
}

form.sign-up-form {
    opacity: 0;
    z-index: 1;
}

form.sign-in-form {
    z-index: 2;
}

.title {
    font-size: 2.2rem;
    color: #444;
    margin-bottom: 10px;
}

.input-field {
    max-width: 380px;
    width: 100%;
    background-color: #f0f0f0;
    margin: 10px 0;
    height: 55px;
    border-radius: 55px;
    display: grid;
    grid-template-columns: 15% 85%;
    padding: 0 0.4rem;
    position: relative;
}

.input-field i {
    text-align: center;
    line-height: 55px;
    color: #acacac;
    transition: 0.5s;
    font-size: 1.1rem;
}

.input-field input {
    background: none;
    outline: none;
    border: none;
    line-height: 1;
    font-weight: 600;
    font-size: 1.1rem;
    color: #333;
}

.input-field input::placeholder {
    color: #aaa;
    font-weight: 500;
}

.social-text {
    padding: 0.7rem 0;
    font-size: 1rem;
}

.social-media {
    display: flex;
    justify-content: center;
}

.social-icon1 {
    height: 46px;
    width: 46px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 0.45rem;
    color: #333;
    border-radius: 50%;
    border: 1px solid #333;
    text-decoration: none;
    font-size: 1.1rem;
    transition: 0.3s;
    background-image: url("https://f.hubspotusercontent30.net/hubfs/2235233/blog-import/2020/20-08-Aug/sm-icons-facebook-logo.png");
    background-size: cover;
}

.social-icon2 {
    height: 46px;
    width: 46px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 0.45rem;
    color: #333;
    border-radius: 50%;
    border: 1px solid #333;
    text-decoration: none;
    font-size: 1.1rem;
    transition: 0.3s;
    background-image: url("https://cdn0.iconfinder.com/data/icons/social-network-flat-4/512/x_icon-512.png");
    background-size: cover;
}

.social-icon3 {
    height: 46px;
    width: 46px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 0.45rem;
    color: #333;
    border-radius: 50%;
    border: 1px solid #333;
    text-decoration: none;
    font-size: 1.1rem;
    transition: 0.3s;
    background-image: url("https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Google_%22G%22_logo.svg/640px-Google_%22G%22_logo.svg.png");
    background-size: cover;
}

.social-icon4 {
    height: 46px;
    width: 46px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 0.45rem;
    color: #333;
    border-radius: 50%;
    border: 1px solid #333;
    text-decoration: none;
    font-size: 1.1rem;
    transition: 0.3s;
    background-image: url("https://f.hubspotusercontent30.net/hubfs/2235233/blog-import/2020/20-08-Aug/sm-icons-linkedin-in-logo.png");
    background-size: cover;
}

.social-icon:hover {
    color: #4481eb;
    border-color: #4481eb;
}

.btn {
    width: 150px;
    background-color: #5995fd;
    border: none;
    outline: none;
    height: 49px;
    border-radius: 49px;
    color: #fff;
    text-transform: uppercase;
    font-weight: 600;
    margin: 10px 0;
    cursor: pointer;
    transition: 0.5s;
}

.btn:hover {
    background-color: #4d84e2;
}

.panels-container {
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0;
    left: 0;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}

.container:before {
    content: "";
    position: absolute;
    height: 2000px;
    width: 2000px;
    top: -10%;
    right: 48%;
    transform: translatey(-50%);
    background-image: linear-gradient(-45deg, #4481eb 0%, #04befe 100%);
    /* background-color:blue; */
    transition: 1.8s ease-in-out;
    border-radius: 50%;
    z-index: 6;
}

.image {
    width: 100%;
    transition: transform 1.1s ease-in-out;
    transition-delay: 0.4s;
    border-radius: 400px;
}

.panel {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: space-around;
    text-align: center;
    z-index: 6;
}

.left-panel {
    pointer-events: all;
    padding: 3rem 17% 2rem 12%;
}

.right-panel {
    pointer-events: none;
    padding: 3rem 12% 2rem 17%;
}

.panel .content {
    color: #fff;
    transition: transform 0.9s ease-in-out;
    transition-delay: 0.6s;
}

.panel h3 {
    font-weight: 600;
    line-height: 1;
    font-size: 1.5rem;
}

.panel p {
    font-size: 0.95rem;
    padding: 0.7rem 0;
}

.btn.transparent {
    margin: 0;
    background: none;
    border: 2px solid #fff;
    width: 130px;
    height: 41px;
    font-weight: 600;
    font-size: 0.8rem;
}

.right-panel .image,
.right-panel .content {
    transform: translateX(800px);
}

/* ANIMATION */

.container.sign-up-mode:before {
    transform: translate(100%, -50%);
    right: 52%;
}

.container.sign-up-mode .left-panel .image,
.container.sign-up-mode .left-panel .content {
    transform: translateX(-800px);
}

.container.sign-up-mode .signin-signup {
    left: 25%;
}

.container.sign-up-mode form.sign-up-form {
    opacity: 1;
    z-index: 2;
}

.container.sign-up-mode form.sign-in-form {
    opacity: 0;
    z-index: 1;
}

.container.sign-up-mode .right-panel .image,
.container.sign-up-mode .right-panel .content {
    transform: translateX(0%);
}

.container.sign-up-mode .left-panel {
    pointer-events: none;
}

.container.sign-up-mode .right-panel {
    pointer-events: all;
}

@media (max-width: 870px) {
    .container {
        min-height: 800px;
        height: 100vh;
    }

    .signin-signup {
        width: 100%;
        top: 95%;
        transform: translate(-50%, -100%);
        transition: 1s 0.8s ease-in-out;
    }

    .signin-signup,
    .container.sign-up-mode .signin-signup {
        left: 50%;
    }

    .panels-container {
        grid-template-columns: 1fr;
        grid-template-rows: 1fr 2fr 1fr;
    }

    .panel {
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
        padding: 2.5rem 8%;
        grid-column: 1 / 2;
    }

    .right-panel {
        grid-row: 3 / 4;
    }

    .left-panel {
        grid-row: 1 / 2;
    }

    .image {
        width: 200px;
        transition: transform 0.9s ease-in-out;
        transition-delay: 0.6s;
    }

    .panel .content {
        padding-right: 15%;
        transition: transform 0.9s ease-in-out;
        transition-delay: 0.8s;
    }

    .panel h3 {
        font-size: 1.2rem;
    }

    .panel p {
        font-size: 0.7rem;
        padding: 0.5rem 0;
    }

    .btn.transparent {
        width: 110px;
        height: 35px;
        font-size: 0.7rem;
    }

    .container:before {
        width: 1500px;
        height: 1500px;
        transform: translateX(-50%);
        left: 30%;
        bottom: 68%;
        right: initial;
        top: initial;
        transition: 2s ease-in-out;
    }

    .container.sign-up-mode:before {
        transform: translate(-50%, 100%);
        bottom: 32%;
        right: initial;
    }

    .container.sign-up-mode .left-panel .image,
    .container.sign-up-mode .left-panel .content {
        transform: translateY(-300px);
    }

    .container.sign-up-mode .right-panel .image,
    .container.sign-up-mode .right-panel .content {
        transform: translateY(0px);
    }

    .right-panel .image,
    .right-panel .content {
        transform: translateY(300px);
    }

    .container.sign-up-mode .signin-signup {
        top: 5%;
        transform: translate(-50%, 0);
    }
}

@media (max-width: 570px) {
    form {
        padding: 0 1.5rem;
    }

    .image {
        display: none;
    }

    .panel .content {
        padding: 0.5rem 1rem;
    }

    .container {
        padding: 1.5rem;
    }

    .container:before {
        bottom: 72%;
        left: 50%;
    }

    .container.sign-up-mode:before {
        bottom: 28%;
        left: 50%;
    }
}

```
# OUTPUT:
![Screenshot 2025-05-19 212319](https://github.com/user-attachments/assets/14e86783-94a2-4cc0-ac4e-1fb0afe1c5b2)

![Screenshot 2025-05-19 212332](https://github.com/user-attachments/assets/0d2f2c7a-fe83-4deb-82de-a9d685694225)

![Screenshot 2025-05-19 212345](https://github.com/user-attachments/assets/10d4644c-2e85-4ae8-8e76-ff80ad184e6f)

![Screenshot 2025-05-19 212508](https://github.com/user-attachments/assets/9e4ffcad-6c47-454e-b68f-db91f96c9436)


![Screenshot 2025-05-19 212414](https://github.com/user-attachments/assets/33e26270-d0c7-42af-a765-01ea78f65782)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
