# fitfusion
fitnessclub

Home page view :

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fit Fusion</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
    <style>
    .logo{
        background-size: cover;
        height: 55px;
        width: 55px;
        border-radius: 30px;
    }
    .club-name {
  font-weight: bold;
  color:black;
  margin-left: 12px;
}
    .pa{
        font-weight: bold;
        font-family: Arial, Helvetica, sans-serif;
    }
    .card{
        text-align: center;
        padding: 15px;
        border-radius: 12px;
        color: white;
    }
    .card4{
        text-align: center;
        padding: 15px;
        border-radius: 12px;
        margin: 25px;
    }
    .card-title{
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    .card-title2{
      font-style: italic;
      color: black;
    }
    .card-title3{
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        color: black;
    }
    .quote{
        font-style: italic;
    }
    .custom-margin-top {
     margin-top: 10%; 
}
.custom-margin-top2{
     margin-top: 3%; 
}
.team-members {
  margin-top: 20px;
}

.profile-pic {
  width: 30vh;
  height: 30vh;
  border-radius: 50%;
  margin: 10px;
  transition: transform 0.3s ease-in-out;
}

.profile-pic:hover {
  transform: scale(1.1);
  z-index: 1;
}

.profile-name {
  display: none;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 16px;
  color: #fff;
  background-color: rgba(0, 0, 0, 0.5);
  padding: 5px 10px;
  border-radius: 10px;
}

.profile-pic:hover + .profile-name {
  display: block;
}

.shadow-card {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease-in-out;
}

.shadow-card:hover {
  transform: translateY(-10px);
}

.footer {
  margin-top: 45px;
  width: 100%;
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px;
}

.footer ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
}

.footer li {
  margin-right: 20px;
}

.footer a {
  color: #fff;
  text-decoration: none;
}

.footer a:hover {
  color: #ccc;
}

.footer i {
  margin-right: 10px;
}
.about-us-desc{
  color: black;
}
.profile{
  height: 30vh;
  width: 30vh;
  background-size: cover;
  border-radius: 35px;
}
.top{
  margin: 20px;
}
.highlight{
  font-weight: bold;
}
.video-container {
    border-radius: 13px;
    overflow: hidden;
  }
  #video {
    border-radius: 13px;
  }
  #mute-button {
    position: absolute;
    top: 10px;
    right: 10px;
    z-index: 1;
    background-color: #fff;
    color: #333;
    border: none;
    padding: 5px 10px;
    font-size: 16px;
    cursor: pointer;
  }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-warning fixed-top">
      <a class="navbar-brand" href="#"><img src="fit fusion.jpg" class="logo"><span class="club-name">Fit Fusion</span></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav mx-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#"><p class="pa">Home</p> <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about-us-desc"><p class="pa">About us</p></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><p class="pa">Get Started</p></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="challenges.html"><p class="pa">Challenges</p></a>
            </li>
          </ul>
        </div>
      </nav>
<div class="container">
    <div  class="row">
        
        <div class="card bg-dark col-xl-12 custom-margin-top">
            <h5 class="card-title">Welcome to Fit Fusion</h5>
            <p class="quote">"fitness is not just a goal ! its a life style."</p>
        </div>
        <div class="card col-xl-12 custom-margin-top2 shadow-card">
          <h5 class="card-title2">Club members :</h5>
            <div class="team-members">
            </div>
                <div class="row justify-content-center">
                  <div class="col-3">
                    <a href="#saketh">
                      <img src="sak.jpg" class="profile-pic" alt="John">
                      <span class="profile-name">Saketh</span>
                    </a>
                  </div>
                  <div class="col-3">
                    <a href="#Dibjoti">
                      <img src="dib.jpg" class="profile-pic" alt="Jane">
                      <span class="profile-name">Dibjoti</span>
                    </a>
                  </div>
                  <div class="col-3">
                    <a href="#akshay">
                      <img src="akshay.jpg" class="profile-pic" alt="Mike">
                      <span class="profile-name">Akshay</span>
                    </a>
                  </div>
                  <div class="col-3">
                    <a href="#yeshwanth">
                      <img src="yesh.jpg" class="profile-pic" alt="Emily">
                      <span class="profile-name">Yeshwanth</span>
                    </a>
                  </div>
                  <div class="col-3">
                    <a href="#kanth">
                      <img src="kanth.jpg" class="profile-pic" alt="Emily">
                      <span class="profile-name">Kanth</span>
                    </a>
                  </div>
                  <div class="col-3">
                    <a href="#lohith">
                      <img src="lohit.jpg" class="profile-pic" alt="Emily">
                      <span class="profile-name">Lohith reddy</span>
                    </a>
                  </div>
                  <div class="col-3" >
                    <a href="#kathu">
                      <img src="kathu.jpg" class="profile-pic" alt="Emily">
                      <span class="profile-name">Kathyayani</span>
                    </a>
                  </div>
                  <div class="col-3" >
                    <a href="#jishi">
                      <img src="jish.jpg" class="profile-pic" alt="Emily">
                      <span class="profile-name">Jishitha</span>
                    </a>
                  </div>


                </div>
                
              </div>
        </div>
        <div class="card bg-light col-xl-12 custom-margin-top2 shadow-card " id="about-us-desc">
          <h5 class="card-title3 text-center">About Us</h5>
          <p class="about-us-desc"> Fit Fusion is more than just a fitness club – it's a 
            community focused on helping individuals transform their lives, both physically and mentally.
            We believe that fitness isn't a one-size-fits-all approach. That's why we offer personalized 
            challenges, expert-led training in various disciplines like bodybuilding, yoga, powerlifting, 
            and more. Our mission is to inspire and motivate members to make fitness a lifestyle, not just a goal.
             With a mix of cutting-edge workouts, accessible diet plans, and holistic wellness strategies, Fit Fusion 
             is here to help you unlock your full potential. Whether you're aiming to bulk, cut, or simply improve your 
             overall well-being, we’re with you every step of the way.</p>
        </div>
    </div>

    <div class="row justify-content-center top">
      <div class="col-md-3" id="saketh">
        <a href="#" style="text-decoration: none;">
          <div class="card4 shadow-card" style="background-color: #ADD8E6; box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);">
            <img src="sak.jpg" class="profile" alt="saketh">
            <p class="card-text" style="padding: 20px; color: black;"> <span class="highlight">Hi, I am Saketh.</span>  
              I do calisthenics, which requires strength and focus. I am 
              highly motivated and always seeking to learn and share my new skills. 
              My goal is to inspire and support people to achieve their own goals, whether
               in fitness or personal growth. Together, we can push our limits and accomplish great things!</p>
          </div>
        </a>
      </div>
      <div class="col-md-3" id="Dibjoti">
        <a href="#" style="text-decoration: none;">
          <div class="card4 shadow-card" style="background-color: #ADD8E6; box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);">
            <img src="dib.jpg" class="profile" alt="dibjyoti">
            <p class="card-text" style="padding: 20px; color: black;"> <span class="highlight"> Hi, I'm Dibjyoti.</span> Strength training is my passion,
               and I always strive to be innovative in everything I do. I'm constantly pushing myself to achieve something big.
                With strong leadership qualities, I aim to support and guide people who are determined to train their bodies and stay
                 disciplined on their fitness journey. </p>
          </div>
        </a>
      </div>
      <div class="col-md-3" id="akshay">
        <a href="#bio-jane" style="text-decoration: none;">
          <div class="card4 shadow-card" style="background-color: #ADD8E6; box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);">
            <img src="akshay.jpg" class="profile" alt="akshay">
            <p class="card-text" style="padding: 20px; color: black;">
              <span class="highlight">Hi, I'm Akshay.</span> Fitness endurance training is my passion, and I thrive on pushing my limits .
               My energy is boundless, and I believe that creating a disciplined mindset is an art, one that shapes both the body and mind.
               My goal is to inspire others to embrace discipline 
                and push beyond what they thought was possible.</p>
          </div>
        </a>
      </div>
      <div class="col-md-3" id="yeshwanth">
        <a href="#bio-jane" style="text-decoration: none;">
          <div class="card4 shadow-card" style="background-color: #ADD8E6; box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);">
            <img src="yesh.jpg" class="profile" alt="Yeshwanth">
            <p class="card-text" style="padding: 20px; color: black; "> <span class="highlight">I’m Yashwanth</span> and I’ve knowledge about powerlifting ,Powerlifting 
              training focuses on developing maximum strength 
              and high weights to build raw strength. A typical powerlifting program includes progressive overload, where weight
               is gradually increased over time to challenge the muscles and nervous system. 
              I’ll help you guys with it </p>
          </div>
        </a>
      </div>
      <div class="col-md-3" id="kanth">
        <a href="#bio-jane" style="text-decoration: none;">
          <div class="card4 shadow-card" style="background-color: #ADD8E6; box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);">
            <img src="kanth.jpg" class="profile" alt="kanth">
            <p class="card-text" style="padding: 20px; color: black;"> <span class="highlight">Hi, I’m Kanth.</span>I'm deeply passionate about body transformation and
               the art of shaping my physique. My mission is to assist those who are striving for their own body transformations. I’m here to support and guide people, helping them unlock their potential and achieve the 
               changes they desire. Let's transform together!</p>
          </div>
        </a>
      </div>
      <div class="col-md-3" id="lohith">
        <a href="#bio-jane" style="text-decoration: none;">
          <div class="card4 shadow-card" style="background-color: #ADD8E6; box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);">
            <img src="lohit.jpg" class="profile" alt="lohith">
            <p class="card-text" style="padding: 20px;  color: black; "> <span class="highlight">Hi, I'm Lohith.</span> I’m passionate about bodybuilding and love the process 
              of shaping my body into a man-made machine. I’m constantly pushing my potential and staying active .
               My goal is to support others in 
              their journey towards physical transformation, helping them push their limits and achieve greatness. </p>
          </div>
        </a>
      </div>
      <div class="col-md-3" id="kathu">
        <a href="#abkathu" style="text-decoration: none;">
          <div class="card4 shadow-card" style="background-color: #ADD8E6; box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);">
            <img src="kathu.jpg" class="profile" alt="kathu">
            <p class="card-text" style="padding: 20px; color: black;"><span class="highlight">Hi, I’m Kathyayani</span>. I have a deep passion for yoga and flexibility.
               I love exploring different movements and finding balance in both body and mind. My focus is on encouraging others 
               to embrace their journey, no matter where they start. I’m excited to connect and inspire others
                to find joy in movement! </p>
          </div>
        </a>
      </div>
      <div class="col-md-3" id="jishi">
        <a href="#bio-emily" style="text-decoration: none;">
          <div class="card4 shadow-card" style="background-color: #ADD8E6; box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);">
            <img src="jish.jpg" class="profile" alt="jish">
            <p class="card-text" style="padding: 20px; color: black;"> <span class="highlight">Hi, I’m Jishitha!</span> I’m really passionate about weight lifting and the
               journey it entails. I’ve learned that it’s not just about building strength; it’s also about growth and confidence. 
              . I believe that everyone can find their 
              place in the gym, no matter their experience level. I’m excited to share this journey and support one another
               to reach our goals. </p>
          </div>
        </a>
      </div>
    </div>
    <div class="row justify-content-center">
      <div class="col-md-6">
        <div class="video-container">
          <video id="video" width="100%" height="400" controls>
            <source src="fitfusion.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
          <button id="mute-button" onclick="toggleMute()">Mute</button>
        </div>
      </div>
    </div>

<footer class="footer bg-dark text-white">
  <div class="container">
    <div class="row">
      <div class="col-md-4">
        <h5>Follow us on social media</h5>
        <ul class="list-inline">
          <li class="list-inline-item ">
            <a href="#" target="_blank">
              <i class="fab fa-instagram fa-2x"></i>
            </a>
          </li>
          <li class="list-inline-item">
            <a href="#" target="_blank">
              <i class="fab fa-whatsapp fa-2x"></i>
            </a>
          </li>
          <li class="list-inline-item">
            <a href="#" target="_blank">
              <i class="fab fa-facebook fa-2x"></i>
            </a>
          </li>
          <li class="list-inline-item">
            <a href="#" target="_blank">
              <i class="fab fa-twitter fa-2x"></i>
            </a>
          </li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5>Copyright</h5>
        <p>&copy; 2023 Fit Fusion. All rights reserved.</p>
      </div>
      <div class="col-md-4">
        <h5>Contact us</h5>
        <p>Phone: 123-456-7890</p>
        <p>Email: <a href="mailto:info@fitfusion.com">info@fitfusion.com</a></p>
      </div>
    </div>
  </div>
</footer>
<script>
  let video = document.getElementById("video");
  let muteButton = document.getElementById("mute-button");

  function toggleMute() {
    if (video.muted) {
      video.muted = false;
      muteButton.textContent = "Mute";
    } else {
      video.muted = true;
      muteButton.textContent = "Unmute";
    }
  }
</script>

</body>
</html>



Challenges page:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fit Fusion Club Challenges</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f8f9fa;
        }
        .card {
            margin: 15px;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .btn-back {
            margin-top: 20px;
        }
        h1, h3 {
            text-align: center;
            padding-top: 10px;
        }
        .btn-back a {
            color: white;
            text-decoration: none;
        }

.card-body {
    padding: 20px;
}

h1 {
    font-size: 2.5rem;
    font-weight: bold;
}

footer {
    width: 100%;
}

.btn-warning {
    font-weight: bold;
    border-radius: 8px;
}

.card-title {
    font-weight: bold;
}

.card-text {
    font-size: 1rem;
}

    </style>
</head>
<body class="bg-light">
    <!-- Go Back Button -->
    <div class="container my-4">
        <a href="home.html" target="_self" class="btn btn-warning">Go Back</a>
    </div>

    <!-- Title Section -->
    <div class="container text-center my-4">
        <h1 class="bg-dark text-light py-3 rounded">Fit Fusion Club: Fitness Challenges</h1>
    </div>

    <!-- Cards Section -->
    <div class="container mt-4">
        <div class="card bg-light">
            <div class="card-body">
                <h3 class="card-title bg-dark text-light p-2">Easy to Moderate Challenges</h3>
                <p class="card-text">
                    1. 7-Day Yoga Challenge: Practice yoga for 20-30 minutes every day, focusing on flexibility and mindfulness.<br>
                    2. 10,000 Steps a Day for 10 Days: Track your steps and hit at least 10,000 every day.<br>
                    3. Plank Challenge: Hold a plank for a minimum of 30 seconds on day 1, increasing by 10 seconds daily for 14 days.<br>
                    4. Hydration Challenge: Drink at least 3 liters of water every day for 14 days.<br>
                    5. Bodyweight Circuit Challenge: Perform 3 sets of squats, push-ups, lunges, and sit-ups every day for 10 days.<br>
                    6. 5-Minute Meditation Challenge: Spend 5 minutes daily focusing on deep breathing and mindfulness for 7 days.<br>
                </p>
            </div>
        </div>

        <div class="card bg-light">
            <div class="card-body">
                <h3 class="card-title bg-dark text-light p-2">Intermediate Challenges</h3>
                <p class="card-text">
                    7. 21-Day Strength Challenge: Rotate between upper-body, lower-body, and core workouts, 6 days a week, for 3 weeks.<br>
                    8. 30-Day Push-Up Challenge: Start with 10 push-ups on day 1, adding 2 more each day, reaching 70 push-ups on day 30.<br>
                    9. 30-Day Squat Challenge: Do 50 squats on day 1, adding 5 squats per day until you reach 200 on day 30.<br>
                    10. Outdoor Running Challenge: Run 3 km every day for 14 days, gradually increasing pace or distance.<br>
                    11. Burpee Challenge: Start with 20 burpees, adding 5 more every day for 14 days.<br>
                    12. Sugar-Free Challenge: Eliminate all added sugars from your diet for 30 days.<br>
                    13. Core Focus Challenge: Perform a core workout (planks, sit-ups, Russian twists, etc.) every day for 15 days.<br>
                </p>
            </div>
        </div>

        <div class="card bg-light">
            <div class="card-body">
                <h3 class="card-title bg-dark text-light p-2">Intense & Crazy Challenges</h3>
                <p class="card-text">
                    14. 75 Hard Challenge: 2 workouts a day (one outdoors) for 75 days. Drink 1 gallon of water daily. Follow a diet with no cheat meals or alcohol. Read 10 pages of a non-fiction book. Take a progress picture every day.<br>
                    15. Murph Challenge: Complete a 1-mile run, 100 pull-ups, 200 push-ups, 300 squats, and finish with another 1-mile run. Try to finish it in under 45 minutes.<br>
                    16. 50/50 Challenge: 50 push-ups and 50 squats every hour for 8 hours.<br>
                    17. 1,000 Reps Challenge: Complete a mix of exercises (push-ups, squats, sit-ups, etc.) totaling 1,000 reps in a single day.<br>
                    18. Death by Burpees: Start with 1 burpee in the first minute, then 2 in the second minute, 3 in the third, and so on. Keep going until you can't complete the number of burpees in the given minute.<br>
                    19. 5K Every Day for a Week: Run a 5K (3.1 miles) every single day for 7 days.<br>
                    20. No Rest Challenge: Perform a high-intensity circuit workout (e.g., burpees, mountain climbers, squats) without any rest periods, increasing the total time each day over 14 days.<br>
                    21. Bodyweight 1,000 Challenge: Complete 1,000 total reps of a combination of exercises (push-ups, squats, sit-ups, burpees) in one session.<br>
                </p>
            </div>
        </div>

        <div class="card bg-light">
            <div class="card-body">
                <h3 class="card-title bg-dark text-light p-2">Similar to 75 Hard but with a Twist</h3>
                <p class="card-text">
                    22. 45 Hard Challenge: 1 workout a day for 45 days. Drink 3 liters of water daily. Follow a healthy diet with 1 cheat day per week. Meditate for 10 minutes daily. Take a progress picture every week.<br>
                    23. 60-Day Mental & Physical Reset: 1 workout a day for 60 days (any type). 10 minutes of daily journaling or gratitude practice. No alcohol or junk food for 60 days. Daily stretching routine for at least 15 minutes.<br>
                </p>
            </div>
        </div>

        <div class="card bg-light">
            <div class="card-body">
                <h3 class="card-title bg-dark text-light p-2">Fun & Team-Based Challenges</h3>
                <p class="card-text">
                    24. Partner Workout Challenge: Pair up with a buddy and complete 7 days of team workouts together, push each other to the limit!<br>
                    25. Fitness Bingo: Create a bingo card with various exercises and health challenges. Complete a full row or column in 30 days.<br>
                    26. Charity Run Challenge: Run a total of 50 km over 30 days and donate to a charity of your choice at the end.<br>
                    27. Virtual Marathon Challenge: Complete a marathon distance (42.2 km) over 10 days, tracking your progress daily.<br>
                    28. Buddy Calisthenics Challenge: Partner up and try to complete advanced bodyweight exercises together (muscle-ups, planche holds, etc.) over a 14-day period.<br>
                </p>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-light py-3 text-center">
        <p>Fit Fusion Club &copy; 2024</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
