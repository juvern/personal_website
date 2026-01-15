---
layout: home
title: Projects
permalink: /projects/
---

<div class="home-hero">
  <h1 class="home-name">Projects</h1>
  <p class="home-tagline">Things I've built and working on</p>
</div>

<div class="home-body">
  <h2>Launch School</h2>
  <p><em>September 2025 – Present</em></p>
  <p>Working through <a href="https://launchschool.com/">Launch School</a>'s mastery-based software engineering program. I wanted a proper foundation in backend development instead of duct-taping tutorials together. AI is eating the world, which makes understanding fundamentals more important, not less.</p>
  <p>The program is depth-first — each course ends with a rigorous interview assessment (live coding and concept explanations) before you can move on. I've completed Python, object-oriented design, networking fundamentals, and networked applications.</p>
  <p><strong>Topics covered:</strong> Python, OOP, networking protocols, SQL, relational databases</p>

  <h2>Coach Payments Processor</h2>
  <p><em>September 2025</em></p>
  <p>Built a Streamlit app to automate coach payment processing. I needed to calculate hours worked from booking data, generate individual payment reports, and send them to coaches each month. Although it didn't take me too long, it was tedious and boring. Now it only takes minutes.</p>
  <p>The app processes booking CSVs from multiple venues, calculates payments, generates GoCardless import files, and emails personalized reports to each coach with their specific bookings attached.</p>
  <p><strong>Built with:</strong> Python, Streamlit, Gmail API</p>

  <h2>Email Auto-Labeler</h2>
  <p><em>July 2025</em></p>
  <p>Built a machine learning system that automatically categorises and archives Gmail emails. I was constantly overwhelemed by my inbox  newsletters, promotions, and notifications cluttering my inbox and this reduced my anxiety significantly. </p>
  <p>The system uses a trained classifier to predict email categories with confidence scoring — only labeling when it's sure. It runs as a scheduled Cloud Run job, processing new emails and archiving everything except what needs attention.</p>
  <p>I could have just set up labels and rules in Gmail, but this was more fun.</p>
  <p><strong>Built with:</strong> Python, Gmail API, scikit-learn, Google Cloud Run</p>

  <h2>AI Support Agent</h2>
  <p><em>July 2025</em></p>
  <p>Built an Outlook add-in that drafts customer support email replies using OpenAI.</p>
  <p>The add-in reads email content directly in Outlook, generates contextually appropriate replies with the right tone and policies, and inserts them into the compose window. Includes customizable prompts for different scenarios.</p>
  <p><strong>Built with:</strong> JavaScript, Office.js, OpenAI API</p>

  <h2>Newsletter Generator</h2>
  <p><em>August 2025</em></p>
  <p>Built a Streamlit app that turns tennis course data into formatted HTML newsletters. As a <a href="https://clubspark.lta.org.uk/VamosTennis/">tennis coaching operator</a>, I was spending too much time manually formatting new courses. This automates the whole process.</p>
  <p>The app parses an export of course data and uses OpenAI to generate descriptions. It outputs clean HTML ready for email platforms.</p>
  <p><strong>Built with:</strong> Python, Streamlit, OpenAI API</p>
  <p><a href="https://github.com/juvern/vt_newsletter_generator">View on GitHub</a></p>



  <h2>Tennis Course Creator</h2>
  <p><em>July 2025</em></p>
  <p>Instead of manually creating dozens of courses each term through the web interface, this reads course data from a CSV and creates them programatically.</p>
  <p><strong>Built with:</strong> Python</p>


</div>

<p class="last-edited">Last updated January 2025</p>
