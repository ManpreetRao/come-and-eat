<h1>Come and Eat!</h1>
<hr>
Come and Eat! is a website created to facilitate community cooking sessions on a weekly basis. It offers an opportunity to learn how to cook while making personal connections with local community members based in London. 

The purpose of the website is to give the users the ability to sign up for the sessions and access any important information about upcoming events, which would be the venue location, pricing, dates and food menu. 

My goal was to create an easily understandable layout that would allow anyone to use the site successfully, since the sessions are open to anyone and everyone from the community.

<h2>Colour Palette</h2>
<img src="/assets/images/coolors.png" alt="The colour palette used on the website">
<br>
Using the site 'Coolors' I was able to create a colour palette to use throughout the website. I focused on warm colours such as red and yellow. This was to mimic a lot of the existing food companies' branding, but to also create a warm and welcoming environment with the deeper colours. #66101F and #FFB20F were used the most across the website as they provided a a good contrast that was still easy to look at. 
<br>
<img src="/assets/images/MultiDeviceMockUp.jpg" alt="Multi Device Mock-Up">

<h2>Features</h2>
<ul>
    <li>Navigation</li>
    <img src="/assets/images/nav_bar.jpg" alt="Screenshot of the navigation bar">
    <br>
    The Navigation is at the top of each page. The logo, which has been created with the use of Google Fonts, is located at the top left and redirects the user to the Home page if clicked. On the top right, the menu items are listed: Home, About Us, Join Us and Contact Us.
    These navigation links are set in a dark colour on a light background, with text shadowing to add extra contrast for better accessibiity.
    These navigation links provide a clea directory for the user to understand how to interact with the site in order to achieve their desired result. 
    <li>Hero Image</li>
    <img src="/assets/images/hero_img.jpg" alt="Screenshot of the hero image and text">
    <br>
    The hero image is a colourful array of dishes on a long table, with people coming around from all sides to eat together. This image encompases what 'Come and Eat!' aims to achieve with the website, which is for people to interact with eachother through the shared experience of food. The text on top of the hero image acts as an invitation to  the user and acts as a short summary of what the website wants to offer within the first glance at the page.
    <li>Reasons to Join</li>
    <img src="/assets/images/reasons.jpg" alt="Screenshot of the reasons columns and call to action">
    <br>
    Reasons to join are topped with icons sourced from FontAwesome and set against a dark background to show the user that this is a new section of the page. The aim is to give the user a reason to stay on the website, as well as to consider signing up to the sessions. This section is brought to a conclusion with the listing of the price and a call to action in the form of a "button" that redirects the user to the 'Join Us' page.  
    <li>Footer</li>
    <img src="/assets/images/footer.jpg" alt="Screenshot of the footer">
    <br>
    The footer, like the header, has a light background colour to make it obvious that the user has reached the end of the page. It is has a simplistic design, only displaying large icons, sourced from FontAwesome, to Facebook, Instagram, Twitter and TikTok with text to signify that these are social links. When clicked, the icons will take the user to a new tab for the respective social media site. 
    <li>About Us</li>
    <img src="/assets/images/about_us.jpg" alt="Screenshot of the About Us Page">
    <br>
    The About As page follows the same colour blocking as the Home page to allow for a feeling of consistency all along the website. This section offers more in-depth reasoning as to why the user should sign up to the sessions. 
    This page also carries the same "button" as the Home page to encourage the user to visit the Join Us page.
    <li>Join Us</li>
    <img src="/assets/images/join_us.jpg" alt="Screenshot of the Join Us page">
    <br>
    The Join Us page has been split into 2 columns.
    The first colum holds a table with the next month's events. In the table the user will be able to see all of the most useful information points, such as the venue location, food items and date. The table has a semi-transparent background to allow it to stand out against the page, but not affect the text visibility.
    The second column holds the form that users can sign up to the session with. This form has a simple layout, so as not to deter less technologically advanced users, and has field validation in the form of required fields. 
    <li>Contact US</li>
    <img src="/assets/images/contact_us.jpg" alt="Screenshot of the Contact Us page">
    <br>
    The Contact Us page has the same 2-column layout at the Join Us page, but on the left-hand side the user can find vital contact information points. On the right, there is another form, this time for genreal enquiries, but it keeps the same field validation rules and collects the name, phone number and email information of the users as a means to get back in touch. All of these points on the page are accompanied by matching icons, to make the page's contents easy to understand from even a glance.
</ul>

<h2>Testing</h2>
<ul>
    <li>I tested this page on Chrome, Firefox and Safari at different screen sizes</li>
    <li>I confirmed that the website was responsive and was able to function on all standard screen sizes without compromising the design</li>
    <li>I confirmed that the field validation on the forms were working</li>
    <img src="/assets/images/form_email.jpg" alt="Screenshot of the form validation working on an email imput field">
</ul>

<h2>Validator Testing</h2>
<ul>
    <li>HTML
        <li>
        One error was identified by the official W3C validator
        <br>
        <img src="/assets/images/HTML_error_flagging.jpg" alt="HTML error shown in W3C validator">
        <br>
        I went into my index.html file and removed the closing div tab that had been created on line 47.
        </li>
    </li>
    <li>CSS
        <li>No errors were identified by the official W3C validator</li>
    </li>
        </li>Accesibility
        <li>
        My site was confirmed to be accessible when I ran it through Lighthouse in devtools.
        <img src="/assets/images/LighthouseAccessibility.jpg" alt="Accessibility scores shown in Ligthouse">
        </li>
    </li>

<h2>Bugs</h2>
After deploying my website, I found that my 'Join Us' and 'Contact Us' pages were not showing the full content when viewed at a screen width smaller than 300px. 
To fix this, I added 'auto' to the height styling for each section and amended the text style. This made it possible to see the content of all the pages at any size.

<h2>Features for the future</h2>
I would like to add more online options for the sessions next time, with links to streaming and online calling services for the user to recieve email ivitations to once they've filled the form out.

<h2>Deployment</h2>

I deployed the site to GitHub by accessing the repository I had created for the project, going into settings and choosing the main branch to deploy from in the Pages section. 
Any edits I made since the deployment had been committed to the repository.

The link to the website can be found here - <a href="https://manpreetrao.github.io/come-and-eat/index.html" rel="noopener" target="_blank" aria-label="Visit Come and Eat! (opens in a new tab)">Come and Eat!</a>

<h2>Resources and credits</h2>
<ul>
    <li>Coding
        <ul>
            <li>Code Institute HTML & CSS Basics course material</li>
            <li>W3Schools- specifically for the text shadows, column creation and active field outlining</li>
        </ul>   
    </li>
    <li> Validation
        <ul>
            <li>W3C HTML Validation Service</li>
            <li>W3C CSS Validation Service</li>
        </ul>
    <li>Styling
        <ul>
            <li>Font Awesome</li>
            <li>Google Fonts</li>
            <li>Coolors</li>
        </ul>
    </li>
    <li>Images
        <ul>
            <li>Adobe Stock- for the hero image</li>
            <li>Pexel</li>
            <li>Pixaby</li>
            <li>Freepik</li>
        </ul>
    </li>
</ul>



