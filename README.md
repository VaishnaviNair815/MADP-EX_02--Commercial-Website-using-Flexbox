# Ex02 Commercial Website
## Date: 11.08.2025
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pet Paradise</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>🐾 Pet Paradise 🐾</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#gallery">Gallery</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home">
    <h2>🐾 Welcome to Pet Paradise 🐾</h2>
    <p>🐶🐱 Your one-stop destination for all things pets! We love animals and are here to make them feel happy and healthy. 🐰🦜</p>
    
    <p>At Pet Paradise, we believe every furry, feathery, and scaly friend deserves love and care. 🐢🐹</p>
    <ul>
        <li>🐕 Premium pet food and treats</li>
        <li>🐩 Grooming and spa services</li>
        <li>🦜 Toys and accessories for all pets</li>
        <li>🐾 Veterinary care and advice</li>
    </ul>
    <p>Whether you have a playful puppy, a curious kitten, a chatty parrot, or a gentle rabbit, we’ve got something special for them. 💖</p>
    </section>

<section id="services">
    <h2>✨ Our Services ✨</h2>
    <div class="service-card">
        <h3>✂️ Pet Grooming</h3>
        <p>🛁 From baths to haircuts, we make sure your pets look their best.</p>
    </div>
    <div class="service-card">
        <h3>🩺 Veterinary Care</h3>
        <p>💊 Expert health checkups and treatments for your furry friends.</p>
    </div>
    <div class="service-card">
        <h3>🐕‍🦺 Pet Training</h3>
        <p>📚 Behavioral training and obedience classes for all breeds.</p>
    </div>
    <div class="service-card">
        <h3>🏡 Pet Boarding</h3>
        <p>🛏️ Safe and comfortable stays for your pets while you're away.</p>
    </div>
    <div class="service-card">
        <h3>❤️ Pet Adoption</h3>
        <p>🐾 Find your perfect companion and give a pet a loving home.</p>
    </div>
    <div class="service-card">
        <h3>📸 Pet Photography</h3>
        <p>🐕 Capture adorable moments with professional pet photo shoots.</p>
    </div>
</section>

    <section id="gallery">
        <h2>Our Lovely Pets</h2>
        <div class="gallery">
            <img src="golden-retriever-tongue-out.jpg"alt="Dog">
            <img src="file-20250226-32-jxjhmy.avif" alt="Cat">
            <img src="rabbi.jpg" alt="Rabbit">
            <img src="download.jpg" alt="Parrot">
            <img src="live-fish.jpg" alt="Fish">
            <img src="Hamster-thumbnail.webp" alt="Hamster">
            <img src="sheep.jpg" alt="Sheep">
            <img src="call-duck-695733614-67f4fc458cf92.jpg" alt="Duck">
            <img src="images.jpg" alt="Gunia pig">
            <img src="images (1).jpg"alt="Cow">
            
        </div>
    </section>
    <section id="contact" class="contact-section">
    <div class="contact-container">
        <h2>📬 Contact Us</h2>
        <p class="contact-info">We’d love to hear from you! Reach out via email, phone, or the form below.</p>
        <p><strong>Email:</strong> info@petworld.com</p>
        <p><strong>Phone:</strong> +91 98765 43210</p>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>
    </section>
    <footer>
        <p>© 2025 Pet Paradise | Designed by Vaishnavi </p>
    </footer>
</body>
</html>
```
style.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(to bottom, #ffecd2, #fcb69f);
}

header {
    background-color: #ff6f61;
    padding: 15px;
    text-align: center;
    color: white;
}

nav a {
    margin: 0 15px;
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

section {
    padding: 30px;
    text-align: center;
}
#home {
    max-width: 900px;
    margin: 30px auto;
    background: #fff5e1;
    border-radius: 15px;
    padding: 25px;
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    border: 3px solid #ff9f68;
}

#home h2 {
    color: #ff6f61;
    margin-bottom: 15px;
    font-family: "Poppins", sans-serif;
}

#home ul {
    text-align: left;
    max-width: 600px;
    margin: 0 auto;
    padding-left: 20px;
}

#home li {
    margin: 8px 0;
    font-size: 1.1em;
}

#home p {
    font-size: 1.1em;
    line-height: 1.6;
}

.service-card {
    background: white;
    padding: 15px;
    margin: 15px auto;
    max-width: 400px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 15px;
}

.gallery img {
    width: 100%;
    border-radius: 10px;
    height: 200px;
    object-fit: cover;
}


footer {
    background-color: #ff6f61;
    color: white;
    text-align: center;
    padding: 10px;
}
```
## OUTPUT
<img width="1893" height="871" alt="Screenshot 2025-08-11 201123" src="https://github.com/user-attachments/assets/1395ee22-e8ae-4f2f-b1e1-e210a25c6ab3" />
<img width="1891" height="1025" alt="Screenshot 2025-08-11 201202" src="https://github.com/user-attachments/assets/a988bcb7-d0bd-44a6-8968-07fbd488bff3" />
<img width="1899" height="1013" alt="Screenshot 2025-08-11 201324" src="https://github.com/user-attachments/assets/c331ce44-a2b4-4c2c-ab52-bd3d851e5f49" />
## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
