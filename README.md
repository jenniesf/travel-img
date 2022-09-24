# travel-img-app
<h2>Table of Contents</h2>
<ol>
  <li><a href="#overview">Overview</a></li>
    <ol>
      <li><a href="#link">Link to webpage</a></li>
      <li><a href="#screenshot">Screenshot</a></li>
    </ol>
  <li><a href="#process">My Process</a></li>
    <ol>
      <li><a href="#builtWith">Built With</a></li>
      <li><a href="#howItWorks">How It Works</a></li>
      <li><a href="#whatILearned">What I Learned</a></li>
      <li><a href="#optimizations">Optimizations</a></li>
    </ol>
<!--    <li><a href="#development">Getting started with development</a></li>
    <ol>
      <li><a href="#development">Development</a></li>
   </ol> -->
   <li><a href="#author">Author</a></li>
    <ol>
      <li><a href="#author">Portfolio</a></li>
    </ol>
</ol>

<h2 id="overview">Overview</h2>

<h3>About</h3>
<p>
TravelGram is a fullstack CRUD social media application inspired by Instagram for users to share vacation photos and captions with friends and family. Users can create their own profiles and images are shared on a public feed. Users can also like photos/posts and add comments to posts. Users can delete their own photos/posts and comments. 

<br>
<h3 id="link">Link to webpage:</h3>
<a href="https://travalgramapp.herokuapp.com/">TravelGram application</a>

<h3 id="screenshot">Screenshots:</h3> 

<h3><ins>Landing page</ins></h3>

<img width="1266" alt="TG-landingpage-screenshot" src="https://user-images.githubusercontent.com/99220339/192113212-9c0849ef-3966-4d57-a833-662ab3a7aa95.png">

<h3><ins>User's profile page</ins></h3>

<img width="700" alt="travelgram-screenshot" src="https://user-images.githubusercontent.com/99220339/191644448-73456a8c-d826-477e-a5b7-84f2d1bc60cd.png">

<h3><ins>Register page</ins></h3>

<img width="650" alt="TG-register-screenshot" src="https://user-images.githubusercontent.com/99220339/192113302-8161f2f2-c896-4c9e-9cf7-8460a47535ab.png">

<h3><ins>Login page</ins></h3>

<img width="650" alt="TG-login-screenshot" src="https://user-images.githubusercontent.com/99220339/192113228-bd8a27eb-dba0-40b9-bb96-dcfbfeb2ca5e.png">


<h2 id="process">My Process</h2>
<h3 id="builtWith">Built With:</h3>

<h3 id="howItWorks">Technologies and Frameworks</h3>
<ul>
  <li>EJS</li>
  <li>MongoDB</li>
  <li>Node.js</li>
  <li>Express</li>
  <li>Bcryptjs</li>
  <li>Cloudinary</li>
  <li>Passport</li>
  <li>Bootstrap</li>
  <li>Tailwind</li>
  <li>Javascript</li>
</ul>

<h3 id="howItWorks">How It Works</h3>

<p>
I built a full-stack CRUD application for users to upload and share vacation photos. I was inspired by Instagram and I wanted to create a similar social media application experience. 

Upon loading the webpage, an unauthenticated user is directed to the home page and authenticated user is directed to their profile. The home page includes a snippet about the site and the user can either log in or register a new account.

Once authenticated or registered, the user is directed to their profile. Express session is utilize to store cookie and a session id in the user's browser to retrieve session information. On user's profile page, the user can upload images or go to the public feed. Feed is where users can view all vacation images shared on the site. Users can like and comment on their own and other users' posts. Users can delete their own comments or comments on their posts. 
</p>


<h3 id="whatILearned">What I Learned</h3> 
This was a fun project and I learned how to:
<br><br>
<ul>
  <li>Use Bootstrap framework and read and research documentation</li>
  <li>Use Express-session to use a cookie to store session id in browser</li>
  <li>Use Passport for user authentication</li>
  <li>Use Multer middleware for handling multipart/form-data to upload files</li>
  <li>Use Cloudinary to host user images</li>
</ul>

<h3 id="optimizations">Optimizations</h3>
There are many additional features I plan to include, such as the following items: 
<br><br>
<ul>
  <li>Add additional profile features, such as a user profile pictures and about me section</li>
  <li>Add friends list and search for friends feature</li>
  <li>Additional features in the user dashboard and styling to improve the overall UX/UI</li>
</ul>

<!-- <h2 id="development">Getting started with development</h2>
<h3 id="Development">Development</h3>
 -->

<h2 id="author">Author</h2>

<ul>
  <li>Portfolio: https://jcsf.netlify.app/</li>
</ul>

