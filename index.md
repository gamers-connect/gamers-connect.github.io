# Gamers Connect

## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Continuous Integration](#continuous-integration)
* [Walkthrough videos](#walkthrough-videos)
* [Example enhancements](#example-enhancements)
* [Team](#team)

## Overview

Many gamers at the University of Hawaiʻi (UH) often struggle to find other players for their favorite games, organize gaming sessions, or discover local gaming events that match their interests. Existing platforms can be too broad or too specific, making it hard to build a consistent, local gaming community. This means missed chances for social interaction, competitive fun, and finding new gaming experiences right here on campus.

Gamers Connect is a user-friendly web application designed to solve this. It helps UH gamers easily find and connect with peers, set up gaming sessions, and discover local gaming events like tournaments and meetups. Users create a profile specifying their gaming interests, preferred platforms, and playstyles. By combining user-generated content with smart matching, Gamers Connect streamlines connections and keeps students informed about all the gaming action relevant to them at UH.

## Deployment

*(To be added later)*

## User Guide

This section provides a walkthrough of the Gamers Connect user interface and its capabilities.

### Landing Page

This is the first thing users see. It will introduce Gamers Connect, highlight its main benefits (like finding teammates or events), and have clear options to sign up or log in.

### User Dashboard (Home Page)

After logging in, users land here. It'll show a personalized feed with:
* Recommended Players: Other UH gamers they might want to connect with based on shared interests.
* Upcoming Sessions: Any gaming sessions they're part of or new ones relevant to them.
* Local Gaming Events: A quick look at tournaments or meetups happening at UH or nearby.
* Community Posts: Recent updates from their gaming groups.

### User Profile Page

This is where users manage their gaming identity. They can:
* List their preferred games, platforms, and playstyles.
* Set their location (e.g., "UH Mānoa Campus").
* Add a short bio and link to external gaming profiles like their Discord handle.
* Adjust their notification settings.

### Find Players & Groups

A dedicated page where users can search for other gamers or public groups. They can filter by game, playstyle, and even proximity (helpful for finding people on campus).

### Browse Events

A comprehensive directory of all listed local and online gaming events. Users can filter by game, type of event (tournament, meetup), and date.

### Game Pages (Simplified)

Basic pages for popular games showing a list of active players for that game and related upcoming events.

### Use Case: Finding a Valorant Teammate

A new user signs up for Gamers Connect. In their profile, they select "PC" as their platform, "Competitive FPS" as their playstyle, and add Valorant as a primary game. Their User Dashboard immediately shows "Players Online" for Valorant who match their competitive preference. They send a connection request to a player with a similar profile, who accepts. They then coordinate a gaming session by connecting on Discord, which they found on the other player's profile.

### Use Case: Discovering a Campus Tournament

A user logs into Gamers Connect. Their User Dashboard highlights an "Upcoming Local Events" section. They see a "Valorant Tournament at the University of Hawaii iLab" listed. The user clicks on the tournament, views the details like date, time, and the registration link, and decides to attend.

## Community Feedback

*(To be added later)*

## Developer Guide

This section provides information of interest to developers wishing to use this code base as a basis for their own development tasks.

### Approach

Once a user sets up their profile with their gaming interests, preferred platforms, and location, Gamers Connect will gather and organize information primarily through:
* **User-Generated Content:** Gamers can post their availability for games, create public or private gaming sessions, list local gaming events they're hosting or attending (like a Valorant tournament in the iLab), and even share quick reviews of games or local gaming spots.
* **Community Forums/Groups:** Dedicated spaces will allow users to discuss specific games, genres, or simply connect with other UH gamers in a more general community setting.
* **Curated Data (Basic):** We'll focus on information relevant to the UH community, such as official campus gaming club events or publicly listed tournaments on campus.

### Intelligent Matching and Filtering

* **Game & Genre Matching:** Connect users based on shared preferred games (e.g., Valorant, Overwatch, Super Smash Bros.) and platforms (PC, PlayStation, Xbox, Mobile).
* **Playstyle Compatibility:** Allow users to specify if they're looking for casual, competitive, or cooperative play, and then match them with others who want the same experience.
* **Session Organization:** Provide simple tools to schedule gaming sessions, including inviting specific players and setting dates and times.
* **Event Discovery:** Users can easily filter local gaming events by game, type, and date, making it simple to find what's happening on or near campus.

The system will prioritize showing opportunities that are current and highly relevant to a user's profile. Users can also customize their notification preferences to get alerts when new players are looking for groups or when new events are posted.
Admins will have basic tools to monitor user-generated content for appropriateness and manage game categories to keep things organized.

### Admin Panel

A simple backend for administrators to:
* Moderate Content: Review user-submitted events or posts.
* Manage Users: Handle accounts if needed.
* View Basic Analytics: See overall system activity.

## Development History

*(To be added later)*

## Continuous Integration

*(To be added later)*

## Walkthrough videos

*(To be added later)*

## Example enhancements

Once the core features are solid, here are some simple ideas to expand the project:
* **Basic Notifications:** Implement notifications via text or email for new session invites or event updates.
* **Calendar Integration (Manual):** Provide a simple "Add to Calendar" button that lets users download an .ics file to manually import events into their personal calendar (like Google Calendar).
* **Event Feedback:** Allow users to leave a star rating or a short comment on events they attended (e.g., "Great tournament, well organized!").
* **Basic Voice Chat Integration (Placeholder):** Instead of full in-app voice chat, simply provide a space within a session's details for users to share a Discord voice channel link for easy communication.

## Team

Gamer Connect is designed, implemented, and maintained by [Kanta Saito](https://KantaS12.github.io), [Cam Moore](https://cammoore.github.io/), [Cam Moore](https://cammoore.github.io/), and [Cam Moore](https://cammoore.github.io/).
