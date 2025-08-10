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

Many gamers at the University of Hawaiʻĭ (UH) often struggle to find other players for their favorite games, organize gaming sessions, or discover local gaming events that match their interests. Existing platforms can be too broad or too specific, making it hard to build a consistent, local gaming community. This means missed chances for social interaction, competitive fun, and finding new gaming experiences right here on campus.

Gamers Connect is a user-friendly web application designed to solve this. It helps UH gamers easily find and connect with peers, set up gaming sessions, and discover local gaming events like tournaments and meetups. Users create a profile specifying their gaming interests, preferred platforms, and playstyles. By combining user-generated content with smart matching, Gamers Connect streamlines connections and keeps students informed about all the gaming action relevant to them at UH.

## Links

* **GitHub Organization:** [gamers-connect](https://github.com/gamers-connect)

  * [gamers-connect](https://github.com/gamers-connect/gamers-connect) – Main app repository
  * [gamers-connect.github.io](https://github.com/gamers-connect/gamers-connect.github.io) – Project homepage and documentation
* **Team Contract:** [Team Contract Document](https://docs.google.com/document/d/1XQ_xHaqVWyqSzzcVqWKELHGU4OY-igglRIU5d4aaR3E/edit?usp=sharing)

## Deployment

The Gamers Connect application is deployed and accessible at:

**🚀 [Live Application on Vercel](https://uh-gamers-connect.vercel.app/)**

## Screenshots

The following screenshots showcase the current state of the Gamers Connect application:

### Login Page

![Login Page](/login2.png)
*Secure login screen to access all Gamers Connect features.*

### Signup Page

![Signup Page](/signup2.png)
*Register a new account with your gaming preferences and platform.*

### User Dashboard

![Dashboard](/dashboard2.png)
*Personalized hub showing recommended players, upcoming sessions, and local events.*

### Find Players

![Find Players](/find_player.png)
*Search and filter interface to discover compatible UH gamers.*

### Events Page

![Events Page](/events2.png)
*Browse tournaments, meetups, and gaming activities hosted by the UH community.*

### User Profile

![User Profile](/profile_card.png)
*Display and edit profile with platforms, games, bio, and connection options.*

## Milestones

### M1 - Project Foundation

**Project Page:** [M1 Milestone](https://github.com/orgs/gamers-connect/projects/1)

This milestone focused on establishing the basic project structure and core components.

### M2 - Feature Development

**Project Page:** [M2 Milestone](https://github.com/orgs/gamers-connect/projects/3)

This milestone focused on implementing advanced features and user-generated content systems.

✅ All issues for M2 are completed — nothing remains in **Backlog** or **In Progress**.

### M3 - Final Feature Completion

**Project Page:** [M3 Milestone](https://github.com/orgs/gamers-connect/projects/4)

This milestone initiates the final phase of development.
🔄 Every team member currently has at least one issue **In Progress**, and one or more issues in the **Backlog**, ensuring that work is evenly distributed and ongoing.

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

## Community Feedback

To evaluate Gamers Connect’s usability, features, and overall user experience, five community members were invited to test the application.

Overall, participants responded positively, describing the interface as **clean, intuitive, and visually appealing**. The **presence indicators** and **player-finding functionality** were highlighted as particularly useful for quickly identifying and connecting with other gamers. Performance during testing was reported as **smooth and responsive**, even when navigating between multiple features.

Some testers suggested **clearer onboarding instructions** to help first-time users quickly understand how to get started, as well as **more customization options for user profiles** to better express individual gaming styles. These suggestions have been noted for future development.

In summary, the feedback reinforced the platform’s potential to become a regular part of the UH gaming community’s activities. Testers expressed interest in using Gamers Connect once additional features—such as enhanced onboarding, richer customization, and expanded event options—are implemented.

## Developer Guide

This section provides information for developers wishing to use this code base as a basis for their own development tasks.

### Installation and Setup

```bash
# 1. Clone the repository
git clone https://github.com/gamers-connect/gamers-connect.git
cd gamers-connect

# 2. Install dependencies
npm install

# 3. Install UI and utility libraries
npm install lucide-react
npm install react-hot-toast

# 4. Install backend-related packages
npm install @prisma/client prisma bcryptjs jsonwebtoken zod

# 5. Install TypeScript type definitions for backend libraries
npm install -D @types/bcryptjs @types/jsonwebtoken

# 6. Set up Prisma (after you’ve configured your schema and .env file)
npx prisma generate

# 7. Run the development server
npm run dev

# 8. (Optional) Set up Playwright for end-to-end testing
npm install --save-dev playwright@latest
npx playwright install
```

> ✅ Be sure to create a `.env` file in the root of your project with your database connection and any secrets (e.g., JWT secret).

Example `.env`:

```dotenv
DATABASE_URL=postgresql://USER:PASSWORD@HOST:PORT/DATABASE
JWT_SECRET=your_jwt_secret_here
```

### Technology Stack

* **Framework:** Next.js 14+ with TypeScript
* **Styling:** CSS with Glassmorphism Design
* **Icons:** Lucide React
* **Database & ORM:** PostgreSQL + Prisma
* **Deployment:** Vercel
* **Testing:** Playwright (optional)

### Design System

The application features a modern dark gradient theme with glassmorphism effects:

* **Color Scheme:** Dark gradient backgrounds with semi-transparent elements
* **Typography:** Clean, readable fonts with proper contrast
* **Interactive Elements:** Smooth hover effects and transitions
* **Layout:** Responsive grid systems and flexible containers

### Contribution Guidelines

We follow conventional commits and GitHub Flow:

* Create a new branch for each issue.
* Use descriptive commit messages.
* Open a pull request referencing the issue.

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
