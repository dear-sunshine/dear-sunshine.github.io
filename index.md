## Navigation
* [Overview](#overview)
* [Project Mockups](#project-mockups)
* [Project Milestones](#project-milestones)
* [Developer Guide](#developer-guide)
* [Team](#team)
* [Organization](#organization)

## Overview

Many people experience feelings of isolation or sadness and could benefit from positive, uplifting messages to brighten their day. While social media allows for sharing updates, it lacks a dedicated space where users can anonymously send and receive encouragement within a supportive community. Dear Sunshine addresses this gap by providing a platform where users can receive kind messages in response to what they've shared or vented about on the board.

## Project Mockups
<div class="container">
  <div class="content">
    <h2>Home Page</h2>
    <img src="./dear-sunshine-front-page.png">
    <p>The main page displays featured letters and a call-to-action for users to “Write a Letter” or “Read a Letter.” The page encourages engagement with inspiring quotes or uplifting messages.</p>
  </div>
</div>

<div class="container">
  <div class="content">
    <h2>Sign Up/Sign In</h2>
    <img src="./dear-sunshine-front-page.png">
  </div>
</div>

<div class="container">
  <div class="content">
    <h2>Sign Out</h2>
    <img src="./sign-out.png">
  </div>
</div>

<div class="container">
  <div class="content">
    <h2>Home Page with Login</h2>
    <p>The main page displayed once the user is logged in. They will gain access to the other pages where they can write or read a letter.</p>
  </div>
</div>

<div class="container">
  <div class="content">
    <h2>Write Letter</h2>
    <img src="./write-letter.png">
    <p>A page where users can compose and post their letters to the letter board, offering encouragement or sharing their thoughts.</p>
  </div>
</div>

<div class="container">
  <div class="content">
    <h2>Letter Board</h2>
    <img src="./letter-board.png">
    <p>Displays a collection of anonymous letters that users can filter by subject, such as “School” or “Friendship.” Users can respond to letters on this page or send a virtual cheer by clicking “Send Sunshine.”</p>
  </div>
</div>

<div class="container">
  <div class="content">
    <h2>Mental Health Resources</h2>
    <p>A page with helpful links and contact information for mental health resources, including helplines and local organizations.</p>
  </div>
</div>

<div class="container">
  <div class="content">
    <h2>Profile</h2>
    <p>This page allows users to view and edit their profile, including personal information and activity history on the platform.</p>
  </div>
</div>

## Project Milestones
<h3>[M1 Issues](https://github.com/orgs/dear-sunshine/projects/3)</h3>
M2
M3

## Developer Guide
1. [Install PostgreSQL](https://www.postgresql.org/download/).
2. Create a database for your application. $ createdb dear-sunshine
3. Go to [https://github.com/dear-sunshine/dear-sunshine](https://github.com/dear-sunshine/dear-sunshine). Click the "Use this template" button.
4. `cd` into the directory of your local copy of the repository and install third party libraries with `npm install`.
5. Create a `.env` file from the `sample.env`.
6. Run the Prisma migration `npx prisma migrate dev` to set up the PostgreSQL tables.
7. Seed the database with the `/config/settings.development.json` data using `npx prisma db seed`.
8. Run the app with `npm run dev`.
9. If all goes well, the template application will appear at [http://localhost:3000](http://localhost:3000).

## Team
Dear is designed, created and built by [Casey Caro](https://kmiks.github.io/), [Isabelle Castro](https://icastro808.github.io/), [Lucas Corriero](https://lucascorriero.github.io/) and [Tiffany Duong](https://tiffanyduong1.github.io/).

## Organization
GitHub: [Dear Sunshine](https://github.com/dear-sunshine/dear-sunshine.github.io)
