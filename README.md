# Fullstack Interview Tasks

This repository contains two separate interview tasks for fullstack candidates. Each task is an independent project that can be run separately. 

## Tasks Overview

### Task 1: Node.js Application
- **Type**: Simple Node.js application
- **Description**: Using JavaScript programming language, please write a script that monitors youtube by searching for a specific keyword and outputs results to the console. Please describe how you offer to set-up such monitoring.

### Task 2: Next.js Application
- **Type**: Full Next.js application with Mantine UI
- **Description**: Create a simple website using Next.js, where you can provide one or more Youtube video Id’s and fetch the last 20 comments from each of these videos. Fetched information should be stored in the MongoDB database, so if a user provides the same video id in a period of 24h then information should be fetched from the database, not from Youtube API. You can use a free cluster of Pricing
Information about comments should be parsed and provided in the website page (you can choose how it can be displayed). If information was fetched from the database then additional message should be displayed that information is fetched not from Youtube API
We expect the code to be clean. Both tasks should have a Readme with setup and execution instructions.

## Repository Structure

This repository contains two distinct projects:

```
fullstack-task/
├── 1st Task/          # Simple Node.js application
├── 2nd Task/          # Full Next.js application
└── README.md          # This file
```

## Prerequisites

Both tasks require:
- **Node.js**: Version 20 or later (LTS recommended)
- **Package Manager**: npm or yarn

## Notes for Candidates

- Each task is completely independent - you can work on them in any order
- Each task has its own `package.json` and dependencies
- Both tasks should be runnable independently without affecting each other
- Push back both directories to repository when finished

## Questions?

If you have any questions about the tasks or setup, please reach out to karolis.bliodnieks@surfsharkteam.com.

