html
How the code for Horiseon website was edited in html.
First space was eliminated in charset. Horiseon was added to the title. Changed the header Div to a Section, and all elements were given an <h1> tag. Eliminated div class= from the elements within the section.
  
Turned div=class Hero in a a section, and eliminated spaces in closing text. Created a section for benefits, and eliminated spaces in the text. 

Took off img from the closing image tags. Also, eliminated the / from the image tags. Added alt= attributes to images. Changed the Div tag for the footer into a footer tag.

css
Removed the selector . from the header, and added font-size:xxlarge. Removed the <h1> tags. Eliminated the selector from the footer and footer <h2> tag. Added position:fixed to footer <h2>.

<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8"/>
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horiseon</title>
</head>

<body>
    <header>Horiseon</header>
        <section>
            <h1>
                <a href="#search-engine-optimization">Search Engine Optimization</a>
                </h1>
            <h1>
                <a href="#online-reputation-management">Online Reputation Management</a>
                </h1>
            <h1>
                <a href="#social-media-marketing">Social Media Marketing</a>
                </h1>
        </section>

    <section>
    <div class="hero"></div>
        <div id="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left"/>
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        <div id="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right"/>
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        <div id="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left"/>
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
    </div>

    <section>
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="lead-generation"/>
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="brand-awareness"/>
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="cost-management" >
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </div>
    </section>
 
    <footer>
        <p>Made with ❤️️ by Horiseon</p>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
</body>

</html>

css
* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

body {
    background-color: #d9dcd6;
}

header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
    font-size:xx-large;
}

header {
    display: inline-block;
    font-size: 48px;
}

header {
    color: #d9dcd6;
    float: left;
}

section div {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
    float: left;
}

header div ul {
    list-style-type: none;
}

header div ul li {
    display: inline-block;
    margin-left: 25px;
}

a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}

.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}

.float-left {
    float: left;
    margin-right: 25px;
}

.float-right {
    float: right;
    margin-left: 25px;
}

.content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

.benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.search-engine-optimization {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img {
    max-height: 100px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing {
    margin-bottom: 20px;
    font-size: 36px;
}

footer {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
}

footer h2 {
    position: fixed;
    font-size: 20px;
}

