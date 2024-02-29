CBP26 HERITAGE-AND-CULTURE
Ideas that showcase the rich cultural heritage and traditions of India


Indian culture is a celebration of diversity that unites rich heritage. Through our website we want this culture richness to be known to the whole world.

Content:

Informative and engaging:
Provide accurate and well-researched information about the cultural and historical aspects of your chosen topic.
Present the information in an engaging way, using multimedia elements like images, and interactive maps.
Diverse and inclusive:
Represent the cultural and historical heritage of various communities and individuals.
Aim for diversity in terms of ethnicities, religions, languages, and perspectives.
Use inclusive language and avoid bias or stereotypes.
FEATURES:
Educational resources:Offer  educational materials for teachers and students.

Create a blog: Regularly publish articles, essays, or interviews related to your topic.
Promote cultural preservation to raise awareness about its importance.

Design:
Visually appealing and user-friendly:Use high-quality images, videos, and graphics to create a visually appealing website.
Ensure the website is well-organized and easy to navigate.
Make sure the website is responsive and adapts to different screen sizes.

HTML CODE LANDING PAGE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heritage & Culture</title>
    <link rel="stylesheet" href="hack.css">
</head>
<body>
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #007bff;
    color: #fff;
    text-align: center;
    padding: 2rem 0;
}

nav ul {
    list-style-type: none;
    text-align: center;
    background-color: #007bff;
    padding: 1rem 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    padding: 5px 10px;
    border-radius: 5px;
    transition: background-color 0.3s;
}

nav ul li a:hover {
    background-color: #0056b3;
}

main {
    </style>
    <header>
        <h1>Explore Heritage & Culture</h1>
        <p>Discover the rich tapestry of traditions and history from around the world.</p>
    </header>

  <nav>
        <ul>
            <li><a href="#introduction">Introduction</a></li>
            <li><a href="#history">History</a></li>
            <li><a href="#art">Art & Architecture</a></li>
            <li><a href="#festivals">Festivals</a></li>
            <li><a href="#traditions">Traditions</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

   <main>
        <section id="introduction">
            <h2>Introduction</h2>
            <p>Delve into the captivating world of heritage and culture, where stories of the past meet traditions of the present. Experience the diversity of human civilization through its art, architecture, festivals, and customs.</p>
           
  </section>

   <section id="history">
            <h2>History</h2>
            <p>Uncover the tales of civilizations, kingdoms, and empires that have shaped our world. From ancient Mesopotamia to the Renaissance era, explore the triumphs and tribulations of humanity's journey through time.</p>
            <img src="historyyy.webp" alt="History Image" width="100" height="100">
        </section>

  <section id="art">
            <h2>Art & Architecture</h2>
            <p>Marvel at the masterpieces of ancient artisans and the grandeur of architectural wonders. From the Pyramids of Giza to the Taj Mahal, behold the beauty and ingenuity of human creativity across different cultures and epochs.</p>
            <img src="R.jpg" alt="History Image" width="100" height="100">
        </section>

  <section id="festivals">
            <h2>Festivals</h2>
            <p>Celebrate the vibrancy of cultural festivals that bring communities together in joyous revelry. From colorful carnivals to solemn religious ceremonies, experience the rich tapestry of traditions that define our cultural identities.</p>
           
  </section>

   <section id="traditions">
            <h2>Traditions</h2>
            <p>Explore the customs and rituals passed down through generations, embodying the essence of heritage. Whether it's the Japanese tea ceremony or the Indian Diwali festival, delve into the practices that shape our sense of belonging and identity.</p>
            
   </section>

   <section id="contact">
            <h2>Contact</h2>
            <p>Reach out to us to share your stories, inquire about our services, or collaborate on cultural initiatives. We welcome your contributions and ideas as we continue to promote and preserve the richness of heritage and culture.</p>
                 </section>
    </main>

  <footer>
        <p>&copy; 2024 Heritage & Culture. All rights reserved.</p>
    </footer>
</body>
</html>



CSS CODE LANDING PAGE
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #007bff;
    color: #fff;
    text-align: center;
    padding: 2rem 0;
}


nav {
    background-color: #007bff;
}

nav ul {
    list-style-type: none;
    text-align: center;
    padding: 1rem 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    padding: 5px 10px;
    border-radius: 5px;
    transition: background-color 0.3s;
}

nav ul li a:hover {
    background-color: #0056b3;
}


main {
    padding: 20px;
}

section {
    margin-bottom: 40px;
}


img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
}


@media screen and (min-width: 768px) {
    body {
        font-size: 16px;
    }

  header {
        padding: 3rem 0;
    }

  nav ul {
        display: flex;
        justify-content: center;
    }

   nav ul li {
        margin: 0 20px;
    }

   main {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 40px;
    }
}


footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}


#introduction {
    background-color: #f0f0f0;
    padding: 40px;
    text-align: center;
}


#history {
    background-color: #fff;
    padding: 40px;
}

#history img {
    float: right;
    margin-left: 20px;
}


#art {
    background-color: #f0f0f0;
    padding: 40px;
}

#art img {
    float: left;
    margin-right: 20px;
}


#festivals {
    background-color: #fff;
    padding: 40px;
}


#traditions {
    background-color: #f0f0f0;
    padding: 40px;
}


#contact {
    background-color: #fff;
    padding: 40px;
}


a {
    color: #007bff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}


.button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.button:hover {
    background-color: #0056b3;
}


h1 {
    font-size: 36px;
}


h2 {
    font-size: 24px;
}


h3 {
    font-size: 18px;
}


small {
    font-size: 12px;
}


table {
    width: 100%;
    border-collapse: collapse;
}

th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
}

th {
    background-color: #f2f2f2;
    color: #333;
}

form {
    margin-bottom: 20px;
}

input[type="text"], input[type="email"], textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

textarea {
    resize: vertical;
}

input[type="submit"] {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

input[type="submit"]:hover {
    background-color: #0056b3;
}

@media screen and (min-width: 768px) {
    form {
        max-width: 500px;
        margin: 0 auto;
    }
}


@media screen and (max-width: 768px) {
    img {
        width: 100%;
    }
}
