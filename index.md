---
layout: default
title: "Home"
---

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <!-- Profile Photo on the left -->
  <div style="flex: 1; text-align: center;">
    <img src="images/my-photo.jpg" alt="Your Photo" style="border-radius: 50%; width: 200px; height: 200px; border: 2px solid #ccc;">
  </div>

  <!-- Text and Title on the right -->
  <div style="flex: 2; padding-left: 20px;">
    <h1 style="margin: 0; font-size: 32px;">Stanley Zhu</h1>
    <p style="font-size: 18px; color: #333; margin-top: 10px;">Undergraduate student at University of Wisconsin-Madison</p>
    <p style="font-size: 16px; color: #555;">optional description goes here...</p>
  </div>
</div>

<div style="margin-top: 20px;">
  <h3>About Me</h3>
  <p>
    I am a [Your Year, e.g., third-year] Computer Science PhD student in the [Your Research Groups or Departments] 
    at [Your University]. I am fortunate to be advised by [Your Advisors]. My research interests include:
    [List of Interests].
  </p>
  <p>
    I completed my undergraduate degree in Computer Science at [Your Undergraduate Institution], where I worked 
    with [Your Advisors or Mentors]. Before starting my PhD, I worked as a [Your Past Role or Job Title] at 
    [Your Previous Organization].
  </p>
</div>

<div style="display: flex; gap: 20px; margin-top: 30px;">
  <!-- Email Button -->
  <a href="mailto:your-email@example.com" 
     style="text-decoration: none; 
            color: #007bff; 
            border: 2px solid #007bff; 
            padding: 10px 20px; 
            border-radius: 5px; 
            font-weight: bold;
            transition: background-color 0.3s, color 0.3s;">
     Email
  </a>

  <!-- PGP Button -->
  <a href="files/pubkey.text" 
     style="text-decoration: none; 
            color: #007bff; 
            border: 2px solid #007bff; 
            padding: 10px 20px; 
            border-radius: 5px; 
            font-weight: bold;
            transition: background-color 0.3s, color 0.3s;">
     PGP Key
  </a>

  <!-- CV Button -->
  <a href="files/cv.pdf" 
     style="text-decoration: none; 
            color: #007bff; 
            border: 2px solid #007bff; 
            padding: 10px 20px; 
            border-radius: 5px; 
            font-weight: bold;
            transition: background-color 0.3s, color 0.3s;">
     Vita
  </a>
</div>

<style>
  a:hover {
    background-color: #007bff; /* Solid blue background on hover */
    color: white; /* Change text color to white */
  }
</style>
