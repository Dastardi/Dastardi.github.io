---
layout: page
title: About Me
subtitle: Welcome to my world!
---

<style>
  /* Container for flex layout */
  .container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    text-align: center;
    padding: 0 -50%; /* Add padding to use more horizontal space */
  }
  
  /* Individual section styling */
  .section {
    flex: 1 1 calc(25% - 40px); /* Takes up roughly half the container width minus margin */
    margin: 20px; /* Adjust margin around sections */
  }
  
  /* Image styling within sections */
  .section img {
    width: 100px; /* Width of the images */
    height: 100px; /* Height of the images */
  }
  
  /* Heading styling within sections */
  .section h2 {
    font-size: 24px; /* Size of the section titles */
    margin-top: 10px; /* Space above the titles */
  }
  
  /* Paragraph styling within sections */
  .section p {
    font-size: 16px; /* Size of the paragraph text */
    color: #666; /* Color of the paragraph text */
  }
  
  /* Button styling */
  .button {
    display: inline-block; /* Makes the button inline-block for proper spacing */
    margin-top: 10px; /* Space above the button */
    padding: 10px 20px; /* Padding inside the button */
    background-color: #738573; /* Background color of the button */
    color: #fff; /* Text color of the button */
    text-decoration: none; /* Removes underline from the button text */
    border-radius: 5px; /* Rounds the corners of the button */
  }
  
  /* Button hover effect */
  .button:hover {
    background-color: #667566; /* Darker background color on hover */
  }
</style>

<div class="container">
  <!-- Education Section -->
  <div class="section" id="education">
    <img src="/assets/img/astronaut.jpeg" alt="Education">
    <h2>Education</h2>
    <p>Learn about my academic background and achievements.</p>
    <a href="/edu" class="button">Explore Education</a>
  </div>

  <!-- Career Section -->
  <div class="section" id="career">
    <img src="/assets/img/astronaut.jpeg" alt="Career">
    <h2>Career</h2>
    <p>Discover my professional journey and experiences.</p>
    <a href="/career" class="button">Explore Career</a>
  </div>

  <!-- Projects Section -->
  <div class="section" id="projects">
    <img src="/assets/img/astronaut.jpeg" alt="Projects">
    <h2>Projects</h2>
    <p>Check out the projects I have worked on over the years.</p>
    <a href="/projects" class="button">Explore Projects</a>
  </div>

  <!-- Resume Section -->
  <div class="section" id="resume">
    <img src="/assets/img/astronaut.jpeg" alt="Resume">
    <h2>Resume</h2>
    <p>View and download my professional resume.</p>
    <a href="/resume" class="button">Explore Resume</a>
  </div>
</div>
