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

GOOD Semantic version

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alice's Electronics Shop</title>
</head>
<body>

    <header>
        <div class="logo">My Site</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <article>
            <h1>Welcome to My Site</h1>
        
            <section>
                <h2>My Career</h2>
                <p>I am Alice. I am an electronics sales person.</p>
            </section>
          
            <section>
                <h2>Products and Services</h2>
                <h3>The major items I sell</h3>
                <p>I deal with laptops, phones, hard disks, extension cables, and more.</p>
                
                <h3>Delivery Policy</h3>
                <p>I deliver the electronics to your doorstep at a delivery cost of Sh. 1,500. Items are paid for once they are delivered.</p>
            </section>
        </article>

        <aside>
            <section class="widget">
                <h2>Developer Profile</h2>
     
        </aside>
    </main>

    <footer>
        <figure>
            <img src="https://ebayimg.com" alt="Featured electronic products layout">
            <figcaption>Our featured electronics inventory</figcaption>
        </figure>
    </footer>

</body>
</html>
