# Ex09 Event Registration Web Application
# Date:17-05-2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
FRONT PAGE
HTML
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-compact-6-1">
<img src="images/logoo-2-2.png" class="logoo-2-2" alt="logoo-2" />
<p class="text-3"><span class="text-black">🌟 InnoVerse 2025 🌟</span></p>
<p class="text-4"><span class="text-black">Your Gateway to Innovation, Networking, and Fun!</span></p>
<p class="text-5"><span class="text-black">📅 Date: 15th May 2025  📍 Venue: Majastorium Hall  🕒 Time: 9am to 5pm</span></p>
</div>

</body>
</html>
CSS
@media (max-width: 768px) {
  .android-compact-6-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(244, 223, 223, 1);
}

REGISTARTION PAGE
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-compact-4-1">
<p class="text-2"><span class="text-black">REGISTERATION FORM</span></p>
<div class="rectangle-1-3"></div>
<div class="rectangle-3-4"></div>
<div class="rectangle-4-5"></div>
<div class="rectangle-5-6"></div>
<div class="rectangle-6-7"></div>
<div class="rectangle-7-8"></div>
<div class="rectangle-8-9"></div>
<div class="rectangle-9-10"></div>
<div class="rectangle-10-11"></div>
<p class="text-12"><span class="text-black">FULL NAME</span></p>
<p class="text-13"><span class="text-black">GENDER</span></p>
<p class="text-14"><span class="text-black">AGE</span></p>
<p class="text-15"><span class="text-black">REGISTER NUMBER</span></p>
<p class="text-16"><span class="text-black">DEPARTMENT</span></p>
<p class="text-17"><span class="text-black">MOBILE NUMBER</span></p>
<p class="text-18"><span class="text-black">Email ID</span></p>
<p class="text-19"><span class="text-black">EVENTS TO REGISTER</span></p>
<p class="text-20"><span class="text-black">REGISTER</span></p>
<img src="images/logoo-21.png" class="logoo-21" alt="logoo" />
</div>

</body>
</html>
CSS
:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.text-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-3-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-4-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-5-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-6-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-7-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-8-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-9-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-10-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 8px rgba(0,0,0,0.5);
  background-color: rgba(185, 52, 52, 1);
  border: 1px solid rgba(0, 0, 0, 1);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.logoo-21 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.android-compact-4-1 {
@media (max-width: 1440px) {
  .android-compact-4-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-compact-4-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(244, 223, 223, 1);
}

EVENTS PAGE
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-compact-5-1">
<p class="text-2"><span class="text-black">💡 Tech Talks</span></p>
<p class="text-3"><span class="text-black">🧠 Workshops &amp; Hackathons</span></p>
<p class="text-4"><span class="text-black">🎭 Cultural Performances</span></p>
<p class="text-5"><span class="text-black">⚽ Fun Games &amp; Competitions</span></p>
<p class="text-6"><span class="text-black">🎤 Open Mic &amp; Talent Show</span></p>
<p class="text-7"><span class="text-black">Prizes &amp; Perks:
  🏆 Exciting Cash Prizes
  📜 Participation Certificates
  🍴 Free Meals &amp; Goodies
  🤝 Networking Opportunities</span></p>
<p class="text-8"><span class="text-black">What’s in Store for You?</span></p>
<img src="images/logoo-1-9.png" class="logoo-1-9" alt="logoo-1" />
<p class="text-10"><span class="text-black">Events &amp; Activities</span></p>
</div>

</body>
</html>
CSS
:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.text-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.logoo-1-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 48px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.android-compact-5-1 {
@media (max-width: 1440px) {
  .android-compact-5-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-compact-5-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(244, 223, 223, 1);
}
CONTACT PAGE
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-compact-7-1">
<img src="images/logoo-2-2.png" class="logoo-2-2" alt="logoo-2" />
<p class="text-3"><span class="text-black">Contact &amp; Social Media</span></p>
<p class="text-4"><span class="text-black">
Contact Info:
  📧 Email: saveetha@email.com
  📱 Phone: [123-456-7890]
  🌐 Website: [www.innoverse2025.com]

</span></p>
<p class="text-5"><span class="text-black">Need Help? Get in Touch!</span></p>
</div>

</body>
</html>
CSS
:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.logoo-2-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 40px;
  text-decoration: underline;
  text-transform: none;
  color: var(--text-black);
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.android-compact-7-1 {
@media (max-width: 1440px) {
  .android-compact-7-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-compact-7-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(244, 223, 223, 1);
}
```
# OUTPUT:
![Screenshot 2025-05-13 091930](https://github.com/user-attachments/assets/83254ee8-6af9-4c85-a958-25b672f68f31)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
