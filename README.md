# Languages Used

- HTML
- CSS
- JAVASCRIPT

# ⏰ The 'Be Back At' Timer: Your Personal Timekeeper!
Ever need to know exactly when your break is over, or when the pizza will be ready? Look no further! This simple yet effective web-based timer is here to keep you on schedule, whether you're taking a quick five or a longer lunch.

## Super-Duper-Pomodoro-Tracker 

![CaptureEdited](https://user-images.githubusercontent.com/31016815/76986771-562d9b00-68ff-11ea-9e1c-a9666ccd0060.JPG)


## 🌟 Features
Quick Set Buttons: Pre-defined buttons for common time intervals. Need 20 minutes? Just click!

Custom Time Input: Enter any number of minutes you need for a truly personalized countdown.

Real-Time Display: Watch the seconds tick down directly on the page and even in your browser tab title!

"Be Back At" Time: Instantly see the exact time your timer will finish, so you can plan your triumphant return.

## 🎮 How to Use
It's super straightforward:

Click a Preset: Just hit one of the data-time buttons (e.g., "20 Min," "30 Min," "5 Min") to start a countdown.

Use the Custom Form: Enter your desired number of minutes into the input field and click "SET TIME."

The timer will begin, the display will update, and you'll know precisely when it's time to get back to business (or leisure!).

## 🚀 Get It Running
This is a classic HTML, CSS, and JavaScript project. You'll need an index.html file with your canvas and relevant display elements, and a linked style.css (for visuals) and script.js (for the code you provided).

Here’s a basic HTML structure you'd need:

```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="timer">
        <div class="timer__controls">
            <button data-time="20">20 Min</button>
            <button data-time="10">10 Min</button>
            <button data-time="5">5 Min</button>
            <form name="customForm">
                <input type="text" name="minutes" placeholder="Enter Minutes">
                <button type="submit">SET TIME</button>
            </form>
        </div>
        <div class="display">
            <h1 class="display__time-left"></h1>
            <p class="display__end-time"></p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>


Just drop the provided JavaScript into your script.js file, open index.html in your browser, and you're good to go!

Feel free to customize the styles, add new features, or even integrate it into a larger project. Happy time-keeping!
