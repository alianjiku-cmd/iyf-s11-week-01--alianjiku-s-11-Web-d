** # Task 1.1: Environment Setup **

*Completion Checklist*
. VS Code installed
. Live Server installed
. Prettier installed
. HTML CSS Support installed
.Chrome & Firefox installed
. GitHub account created
. Git installed
. Repository iyf-s10-week-01-{your-github-username} created
. Screenshot taken and saved

** ## Task 1.2: DevTools Exploration **
*Website 1: https://example.com*

**1.	What HTML tags are used on the page?**
  * HTML tags are as follows:*
    (* html, head, title, meta, style, body, div, h1 p,and  a*)

**2.What is the page title?**

   *The Page title is Example Domain*

 **3. How many headings are there?**
    *One heading*

**Website 3:  Wikipedia**
1.*	Identify 5 different HTML elements*
   HTML elements are:
     (a.) header
     (b.) nav
     (c.) h1
     (d.) img
     (e.) footer
2.*	Find a form element and list its inputs*
 *Form inputs*
 *Form inputs are as listed below*
-search input
-hidden input
- submit button
3.	*A screenshot of the Elements panel*
  <img width="1280" height="1169" alt="image" src="https://github.com/user-attachments/assets/ecdc393a-181c-4c58-a33e-71b196125418" />



**Task 1.3: My First Webpage** (index.html)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>- Iam Alice</title>
</head>
<body>
    <h1>Alice</h1>
 <p>Hi am a student</p>
<img src="https://i.ebayimg.com/images/g/RGwAAOSwcd9nSlvf/s-l1600.webp">
 <section>
    <h2>My hobbies </h2>
    <p>I like to play football and basketball</p>
 </section>

 <footer>
    <p>copyright &copy; Alice. All rights reserved.</p>
 </footer>
</body>
</html>


###**Lesson 2 Tasks**
Task 2.1: Semantic HTML 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <style>
        body {
            margin: 0;
            font-family: calibri, sans-serif;
        
        }

        header {
            background: #f3f1f1;
            text-align: left;
            padding: 50px 20px;
        }

        /* Logo Design */
        .logo-box {
            position: relative;
            width: 250px;
            height: 250px;
            margin: 0 ;
        }

        .center-square {
            position: absolute;
            width: 70px;
            height: 70px;
            background: #3b5cff;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        .corner {
            position: absolute;
            width: 70px;
            height: 70px;
            border: 20px solid #e85b6a;
        }

        .top-left {
            top: 20px;
            left: 20px;
            border-right: none;
            border-bottom: none;
        }

        .top-right {
            top: 20px;
            right: 20px;
            border-left: none;
            border-bottom: none;
        }

        .bottom-left {
            bottom: 20px;
            left: 20px;
            border-right: none;
            border-top: none;
        }

        .bottom-right {
            bottom: 20px;
            right: 20px;
            border-left: none;
            border-top: none;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo-box">
            <div class="center-square"></div>
            <div class="corner top-left"></div>
            <div class="corner top-right"></div>
            <div class="corner bottom-left"></div> 
            <div class="corner bottom-right"></div>
        </div>
    </header>
</body>
</html>

