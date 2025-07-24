# Gamers Connect

## Table of Contents

* [Overview](#overview)
* [Links](#links)
* [Deployment](#deployment)
* [Screenshots](#screenshots)
* [Milestones](#milestones)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Team](#team)

## Overview

Many gamers at the University of Hawaiʻi (UH) often struggle to find other players for their favorite games, organize gaming sessions, or discover local gaming events that match their interests. Existing platforms can be too broad or too specific, making it hard to build a consistent, local gaming community. This means missed chances for social interaction, competitive fun, and finding new gaming experiences right here on campus.

Gamers Connect is a user-friendly web application designed to solve this. It helps UH gamers easily find and connect with peers, set up gaming sessions, and discover local gaming events like tournaments and meetups. Users create a profile specifying their gaming interests, preferred platforms, and playstyles. By combining user-generated content with smart matching, Gamers Connect streamlines connections and keeps students informed about all the gaming action relevant to them at UH.

## Links

* **GitHub Organization:** [gamers-connect](https://github.com/gamers-connect)
* **Team Contract:** [Team Contract Document](https://docs.google.com/document/d/1XQ_xHaqVWyqSzzcVqWKELHGU4OY-igglRIU5d4aaR3E/edit?usp=sharing)

## Deployment

The Gamers Connect application is deployed and accessible at:

**🚀 [Live Application on Vercel](https://uh-gamers-connect.vercel.app/)**

## Screenshots

The following screenshots showcase the current state of the Gamers Connect application:

### Landing Page
![Landing Page](./screenshots/landingPage.png)
*The welcoming landing page that introduces users to Gamers Connect and its features*

### User Dashboard
![Dashboard](./screenshots/dashboard.png)
*Personalized dashboard showing recommended players, gaming sessions, and upcoming events*

### Find Players Page
![Find Players](./screenshots/findPlayers.png)
*Search and filter interface for discovering fellow UH gamers with similar interests*

### Events Page
![Events](./screenshots/events.png)
*Browse and discover local gaming tournaments, meetups, and community events*

### User Profile
![Profile](./screenshots/profile.png)
*User profile management for gaming preferences, platforms, and contact information*

## Milestones

### M1 - Project Foundation
**Project Page:** [M1 Milestone](https://github.com/orgs/gamers-connect/projects/1)

This milestone focused on establishing the basic project structure and core components.

### M2 - Feature Development
**Project Page:** [M2 Milestone](https://github.com/orgs/gamers-connect/projects/3)

This milestone focuses on implementing advanced features and user-generated content systems.

## User Guide

This section provides a walkthrough of the Gamers Connect user interface and its capabilities.

### Landing Page

This is the first thing users see. It introduces Gamers Connect, highlights its main benefits (like finding teammates or events), and has clear options to sign up or log in.

### User Dashboard (Home Page)

After logging in, users land here. It shows a personalized feed with:
* **Recommended Players:** Other UH gamers they might want to connect with based on shared interests
* **Upcoming Sessions:** Any gaming sessions they're part of or new ones relevant to them
* **Local Gaming Events:** A quick look at tournaments or meetups happening at UH or nearby
* **Community Posts:** Recent updates from their gaming groups

### User Profile Page

This is where users manage their gaming identity. They can:
* List their preferred games, platforms, and playstyles
* Set their location (e.g., "UH Mānoa Campus")
* Add a short bio and link to external gaming profiles like their Discord handle
* Adjust their notification settings

### Find Players & Groups

A dedicated page where users can search for other gamers or public groups. They can filter by game, playstyle, and even proximity (helpful for finding people on campus).

### Browse Events

A comprehensive directory of all listed local and online gaming events. Users can filter by game, type of event (tournament, meetup), and date.

### Game Pages

Individual pages for popular games showing a list of active players for that game and related upcoming events.

### Example Use Cases

**Finding a Valorant Teammate:** A new user signs up for Gamers Connect. In their profile, they select "PC" as their platform, "Competitive FPS" as their playstyle, and add Valorant as a primary game. Their User Dashboard immediately shows "Players Online" for Valorant who match their competitive preference. They send a connection request to a player with a similar profile, who accepts. They then coordinate a gaming session by connecting on Discord, which they found on the other player's profile.

**Discovering a Campus Tournament:** A user logs into Gamers Connect. Their User Dashboard highlights an "Upcoming Local Events" section. They see a "Valorant Tournament at the University of Hawaii iLab" listed. The user clicks on the tournament, views the details like date, time, and the registration link, and decides to attend.

## Developer Guide

This section provides information for developers wishing to use this code base as a basis for their own development tasks.

### Installation and Setup

```bash
# Clone the repository
git clone https://github.com/gamers-connect/[repository-name]
cd [repository-name]

# Navigate to the app directory
cd gamers-connect

# Install dependencies
npm install
npm install lucide-react 

# Run the development server
npm run dev
```

### Technology Stack

* **Framework:** Next.js 14+ with TypeScript
* **Styling:** CSS with Glassmorphism Design
* **Icons:** Lucide React
* **Deployment:** Vercel

### Design System

The application features a modern dark gradient theme with glassmorphism effects:
* **Color Scheme:** Dark gradient backgrounds with semi-transparent elements
* **Typography:** Clean, readable fonts with proper contrast
* **Interactive Elements:** Smooth hover effects and transitions
* **Layout:** Responsive grid systems and flexible containers

### Approach

Once a user sets up their profile with their gaming interests, preferred platforms, and location, Gamers Connect gathers and organizes information primarily through:

* **User-Generated Content:** Gamers can post their availability for games, create public or private gaming sessions, list local gaming events they're hosting or attending, and share reviews of games or local gaming spots
* **Community Forums/Groups:** Dedicated spaces allow users to discuss specific games, genres, or connect with other UH gamers in a general community setting
* **Curated Data:** Information relevant to the UH community, such as official campus gaming club events or publicly listed tournaments on campus

### Key Features

**Intelligent Matching and Filtering:**
* **Game & Genre Matching:** Connect users based on shared preferred games and platforms
* **Playstyle Compatibility:** Match users looking for casual, competitive, or cooperative play
* **Session Organization:** Tools to schedule gaming sessions, invite specific players, and set dates and times
* **Event Discovery:** Filter local gaming events by game, type, and date

**Admin Panel:**
* **Content Moderation:** Review user-submitted events or posts
* **User Management:** Handle accounts and user issues
* **Analytics:** View overall system activity and platform metrics

## Team

Gamers Connect is designed, implemented, and maintained by:

* [Kanta Saito](https://KantaS12.github.io/)
* [Reece Kakuni](https://bearsnuffle.github.io/) 
* [Anlon Mao](https://anlmao125.github.io/)
* [Jerome Demesillo](https://jeromedemesillo.github.io/)
