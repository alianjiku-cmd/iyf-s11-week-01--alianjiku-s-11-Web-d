###**Task 2.1: Semantic HTML Conversation**

*GOOD Semantic version*

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


###**Task 2.2: Building a Contact Form**

    
       <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Me!</title>
</head>
<body>

    <form>
        <!Alice Wanjiku Murungaruh
        <label>Alice Wanjiku Murungaruh:</label>
     <input type="My contact list" >
        <br><br>

        <!-- alianjiku@gmail.com-->
        <label>Email:alianjiku@gmail.com</label>
        <input type="email" value="alianjiku@gmail.com" >
        <br><br>

        <!-- Phone -->
        <label>Phone (0715511031):</label>
        <input type="tel">
        <br><br>

        <!-- contact form  -->
        <label>web development:</label>
        <select>
            <option>Pick a choice!</option>
            <option>Saying Hello</option>
            <option>Ask a Question</option>
            <option>Report a Bug</option>
        </select>
        <br><br>

        <!-- Message -->
        <label>Message (50+ characters):</label>
        <textarea required minlength="50"></textarea>
        <br><br>

        <!-- Newsletter -->
        <input type="checkbox" id="news">
        <label for="news">Subscribe to Newsletter?</label>
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Send Message</button>
    </form>

</body>
</html> 

