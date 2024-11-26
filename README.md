<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eddah Kemuma's Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Eddah Kemuma's Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#interests">Interests</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about" class="container">
        <h2>About Me</h2>
        <img src="1000032487.jpg" alt="Eddah Kemuma" class="profile-image">
        <p>My name is Eddah Kemuma, I am 20 years old. I am a university student at Meru University currently a second year pursuing a Bachelor of Science in Information Technology.</p>
    </section>
    

    <section id="education" class="container">
        <h2>Education</h2>
        <p>2011-2018: Ichuni Primary School</p>
        <p>2019-2022: St Angela Sengera Girls High School</p>
        <p>Currently: Meru University, pursuing a Bachelor of Science in Information Technology.</p>
    </section>

    
    <section id="interests" class="container">
         <h2>Interests</h2> <div class="interest-card">
             <h3>Web Development</h3> 
             <p>Creating dynamic and responsive websites using the latest technologies like HTML, CSS, JavaScript, and frameworks like React and Angular.</p>
             </div> <div class="interest-card"> 
                <h3>Mobile Application Development</h3> 
                <p>Building user-friendly mobile applications for both Android and iOS platforms using tools like Flutter and React Native.</p> 
            </div> <div class="interest-card">
                 <h3>UI/UX Design</h3> 
                 <p>Designing intuitive and engaging user interfaces to enhance user experience through tools like Adobe XD and Figma.</p>
                 </div>
                 </section>

                 
    <section id="contact" class="container">
        <h2>Contact</h2>
        <form action="#">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Eddah Kemuma</p>
    </footer>
</body>
</html>

style.css


body {
    font-family: Arial, sans-serif;
    background-color: #87CEEB; /* Light blue background */
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: 0 auto;
    overflow: hidden;
}

header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
    border-bottom: 4px solid #66ccff; /* Light blue border */
}

header h1 {
    margin: 0;
    font-size: 36px;
}

header nav {
    margin-top: 10px;
}

header ul {
    padding: 0;
    list-style: none;
}

header ul li {
    display: inline;
    margin: 0 10px;
}

header ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 16px;
}

header ul li a:hover {
    text-decoration: underline;
}

section {
    padding: 20px;
    margin: 20px 0;
    background: #fff;
    border: 1px solid #e0e0e0;
    border-radius: 10px;
}

section h2 {
    color: #FFC0CB; /* Pink headings */
    font-size: 28px;
    margin-bottom: 20px;
}

section p {
    font-size: 18px;
    color: hsl(259, 82%, 41%);
}

#about {
    background-color: hsl(326, 32%, 52%); /* Light pink background */
}

#education {
    background-color: #b5e016; /* Light pinkish background */
}

#interests {
    background-color: hsl(135, 100%, 50%); /* Gold background */
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin: 5px 0;
}

form input,
form textarea {
    margin: 5px 0;
    padding: 10px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    padding: 10px;
    font-size: 18px;
    background-color: #0da3ed;
    color: #d80d0d;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background-color: #2a10f3;
}

footer {
    text-align: center;
    padding: 20px;
    background: hsl(196, 94%, 51%);
    color: #fff;
    position: relative;
    bottom: 0;
    width: 100%;
}
.profile-image {
    width: 300px; 
    height: 300px; 
    border-radius: 50%;
    display: block;
    margin: 20px auto;
}

