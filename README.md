#**Task 2.1: Semantic HTML Conversation**

*Good Semantic version*

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
lfile:///C:/Users/JetCore%20Computers/Desktop/good%20semantic-html/contact%20form.html




###**Daily Challenges**
**Day 1: Five Tags Challenge**

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Review and Discussion Webinar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 600px;
            margin: 40px auto;
            padding: 20px;
            background-color: #f9f9f9;

        }
        article {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        details {
            margin-top: 20px;
            padding: 10px;
            background: #eeeeee;
            border-radius: 4px;
            cursor: pointer;
        }
        summary {
            font-weight: bold;
        }
        time {
            color: #666666;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <article>
        <h1>Monthly Book Club Review webinar</h1>
        <p>Published on: <time datetime="2026-06-22">June 22, 2026</time></p>
        
        <p>This month, our club focused on classic dystopian literature. We analyzed how authors predict the future, focusing heavily on technological surveillance and government control.</p>
        
        <blockquote>
            "Perhaps a lunatic was simply a minority of one." 
            <br>
            — <cite>1984</cite> by George Orwell
        </blockquote>

        <p>During our group discussion, we found that the main themes still mirror modern society. It is <mark>incredibly important</mark> to note how relevant these warnings remain today, especially regarding data privacy.</p>

        <details>
            <summary>Click here to view our meeting notes</summary>
            <ul>
                <li>Attendance: 10 members</li>
                <li>Next meeting date: July 4th</li>
                <li>Next book choice: <i>Freedom by Jonathan Franzen</i></li>
            </ul>
        </details>
    </article>

</body>
</html>




###**Task 2.3: Accessibility Audit**
*Accessibility-report.md link (https://github.com/alianjiku-cmd/accessibility-report.md)*

**Task 2.4: Multi-Page Portfolio Structure**
 
 **( 1.) index.html (Home) **  

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Home</title>
    <!-- Tailwind CSS for modern, responsive styling without writing heavy custom CSS -->
    <script src="https://jsdelivr.net"></script>
    <link href="https://cloudflare.com" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

    <!-- Navigation Bar -->
    <nav class="bg-white shadow-sm fixed w-full z-10 top-0 left-0">
        <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
            <a href="index.html" class="text-2xl font-bold text-indigo-600">Your Name</a>
            <div class="space-x-6 text-sm font-medium">
                <a href="index.html" class="text-indigo-600 border-b-2 border-indigo-600 pb-1">Home</a>
                <a href="about.html" class="text-gray-600 hover:text-indigo-600 transition">About</a>
                <a href="projects.html" class="text-gray-600 hover:text-indigo-600 transition">Projects</a>
                <a href="contact.html" class="text-gray-600 hover:text-indigo-600 transition">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="pt-32 pb-20 px-4 max-w-6xl mx-auto text-center">
        <h1 class="text-5xl md:text-6xl font-extrabold text-gray-900 mb-6">
            Hi, I'm <span class="text-indigo-600">Your Name</span>
        </h1>
        <p class="text-xl md:text-2xl text-gray-600 max-w-2xl mx-auto mb-10">
            I craft modern, responsive web experiences and build solutions that make a difference. 
        </p>
        <div class="space-x-4">
            <a href="projects.html" class="bg-indigo-600 text-white px-8 py-3 rounded-lg font-medium shadow-md hover:bg-indigo-700 transition">
                View My Work
            </a>
            <a href="contact.html" class="bg-white text-indigo-600 border border-indigo-200 px-8 py-3 rounded-lg font-medium hover:bg-gray-50 transition">
                Get in Touch
            </a>
        </div>
    </header>

    <!-- Brief Introduction Section -->
    <section class="bg-white py-20 px-4">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl font-bold mb-6 text-gray-900">A Little About Me</h2>
            <p class="text-gray-600 leading-relaxed text-lg mb-8">
                I am a passionate professional dedicated to turning complex problems into elegant, user-friendly digital realities. Whether I'm designing sleek interfaces or writing clean, scalable backend code, I always focus on delivering high-quality results. 
            </p>
            <a href="about.html" class="text-indigo-600 font-semibold hover:underline">
                Read my full story <i class="fas fa-arrow-right ml-1"></i>
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-12 text-center">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-center space-x-6 mb-6">
                <a href="#" class="hover:text-white"><i class="fab fa-github fa-lg"></i></a>
                <a href="#" class="hover:text-white"><i class="fab fa-linkedin fa-lg"></i></a>
                <a href="#" class="hover:text-white"><i class="fab fa-twitter fa-lg"></i></a>
            </div>
            <p>&copy; 2026 Your Name. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>


**(2.) about.html**

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me | Web Developer</title>
    <style>
        :root {
            --primary-color: #2563eb;
            --text-dark: #1f2937;
            --text-light: #4b5563;
            --bg-light: #f3f4f6;
            --white: #ffffff;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            margin: 0;
            padding: 0;
            background-color: var(--bg-light);
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        header {
            text-align: center;
            margin-bottom: 50px;
        }

        h1 {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.8rem;
            color: var(--primary-color);
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 8px;
            margin-top: 40px;
        }

        .card {
            background: var(--white);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }

        /* Skills Layout */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .skills-category h3 {
            margin-top: 0;
            color: var(--text-dark);
            font-size: 1.1rem;
        }

        .skills-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .skills-list li {
            background: var(--bg-light);
            padding: 8px 12px;
            border-radius: 4px;
            margin-bottom: 8px;
            font-size: 0.95rem;
            color: var(--text-light);
        }

        /* Timeline Layout */
        .timeline {
            position: relative;
            padding-left: 30px;
            border-left: 2px solid var(--primary-color);
        }

        .timeline-item {
            position: relative;
            margin-bottom: 30px;
        }

        .timeline-item::before {
            content: '';
            position: absolute;
            left: -37px;
            top: 5px;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: var(--primary-color);
            border: 2px solid var(--white);
        }

        .timeline-date {
            font-weight: bold;
            color: var(--primary-color);
            font-size: 0.9rem;
        }

        .timeline-title {
            font-size: 1.2rem;
            margin: 5px 0;
            font-weight: 600;
        }

        .timeline-company {
            font-style: italic;
            color: var(--text-light);
            font-size: 0.95rem;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>About Me</h1>
            <p>From the classroom to the codebase: My journey as a developer.</p>
        </header>

        <!-- Background Story -->
        <section class="card">
            <h2>My Background</h2>
            <p>Hi, I'm a passionate <strong>Website Developer</strong> with a foundational background as a <strong>Teacher</strong>, based in Nairobi, Kenya. My unique career path blends the clarity, patience, and structural communication of an educator with the technical problem-solving mindset required to build modern web solutions.</p>
            <p>Today, I specialize in planning, structuring, and creating comprehensive website layouts and models. My time in education enables me to closely listen to client goals, analyze requirements, and cleanly translate abstract ideas into functional, interactive digital solutions.</p>
        </section>

        <!-- Skills List -->
        <section class="card">
            <h2>Skills & Expertise</h2>
            <div class="skills-grid">
                <div class="skills-category">
                    <h3>Technical Skills</h3>
                    <ul class="skills-list">
                        <li>Website Modeling & Prototyping</li>
                        <li>UI/UX Layout Design</li>
                        <li>HTML5 & CSS3 Architecture</li>
                        <li>Responsive Web Structures</li>
                    </ul>
                </div>
                <div class="skills-category">
                    <h3>Transferable Soft Skills</h3>
                    <ul class="skills-list">
                        <li>Clear Communication & Presentation</li>
                        <li>Project Blueprint Planning</li>
                        <li>Problem-Solving & Logic</li>
                        <li>Patience & Client Empathy</li>
                    </ul>
                </div>
                <div class="skills-category">
                    <h3>Languages</h3>
                    <ul class="skills-list">
                        <li>English (Fluent)</li>
                        <li>Swahili (Native)</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Education & Experience Timeline -->
        <section class="card">
            <h2>Education & Experience</h2>
            <div class="timeline">
                
                <!-- Timeline Item 1: Web Dev at Cisco Connect -->
                <div class="timeline-item">
                    <div class="timeline-date">[Year Started] - Present</div>
                    <div class="timeline-title">Website Developer & Modeler</div>
                    <div class="timeline-company">Cisco Connect Company — Nairobi, Kenya</div>
                    <p>Designing, coding, and maintaining website-related models. Responsibilities include defining responsive website structures, building interactive prototypes, and shaping client concepts into optimized online assets.</p>
                </div>

                <!-- Timeline Item 2: Teaching -->
                <div class="timeline-item">
                    <div class="timeline-date">[Year Started] - [Year Ended]</div>
                    <div class="timeline-title">Teacher</div>
                    <div class="timeline-company">[The Monarch group of schools] — Nairobi, Kenya</div>
                    <p>Managed classrooms, developed curriculum maps, and simplified complex conceptual frameworks. This experience built the solid presentation and structured planning skills I rely on daily during development pipelines.</p>
                </div>

                <!-- Timeline Item 3: Education Background -->
                <div class="timeline-item">
                    <div class="timeline-date">[years of graduation (2013.2021,& 2026)]</div>
                    <div class="timeline-title">[AI Certificate, Food and Beverage Production and services craft certificate, a certificate in Teachers capacity building for online facilitation of learning & computer packages ]</div>
                    <div class="timeline-company"><div SOS="" Tech="" InstitutionSt="InstitutionSt" Anglican church of Kenya colledge,& Riara university=""></div></div>
                    <p>Acquired academic and technical methodologies that reinforced the logical discipline required for advanced software layout and system development.</p>
                </div>

            </div>
        </section>
    </div>

</body>


**(3.)projects.html**

**(4)contact.html**

