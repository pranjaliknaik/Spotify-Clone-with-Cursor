# Spotify Clone with Cursor

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-workspace-cursor)

**Author:** Pranjali  
**Email:** learn.pranjalinaik@gmail.com

---

![Image](http://learn.nextwork.org/thankful_white_lucky_bicho_papao/uploads/ai-workspace-cursor_s2q3upload)

---

## Introducing Today's Project!

We are going to build a clone of Spotify with the help of AI, especially Cursor Chat. We will add, modify and debug code using AI.

### Key tools and concepts

The tools I used were the Cursor chat (Agent and Ask) mode. 
Key concepts I learnt include cloning, context window cursor indexing, how to control context window and indexing, npm, cursor planning, and dependencies.

### Personal reflection

This project took me approximately 2-3 hours. The most challenging part was getting the queue feature exactly as I wanted. It was most rewarding to the feature work end-to-end.

### Why I did this project

I did this project today because I wanted to explore something that is out of my area of expertise. This project met my goals by piquing my interest in AI-assisted development.

---

## Setting Up the Cursor IDE

In this step, we will be downloading the Cursor app and create an account on cursor.

![Image](http://learn.nextwork.org/thankful_white_lucky_bicho_papao/uploads/ai-workspace-cursor_s1q2upload)

### How Cursor differs from other AI coding tools

Cursor integrates chat in the IDE itself, making everything available in the same application so that we don't have to switch between multiple applications.

### Getting the starter code

Now we are going to download the starter files of the Spotify clone from GitHub. Later, we will use this code as a base and build on top of it.

### Cloning the project from GitHub

Running the Git Clone command will copy/clone the intented repository to your local machine.

---

## Exploring the Codebase with AI

In this step, I'm going to explore the existing codebase using AI chat because before modifying the code, I need to understand what's in the code.

### The NextSound web app

This web app lets users discover music through a hero carousel and multiple sections. There are also mini player cards which the user can sift through. 

### Running the app locally

In this step, I'm going to install NextSound's dependencies because we need to run the application locally.

---

## Creating a Brand New Feature

In this step, I'm going to plan and implement a queue feature with the help of the Cursor agent because we are providing a functionality to the user to manage their upcoming songs.

### Prompting Cursor

The key requirements in my prompt were -
1. Add an "Add to Queue" button on each song tile. I.e. When a user clicks the "Add to Queue" button, a panel should open from the right-hand side of the screen that shows the queue in a vertical list.
2. Users should be able to add songs to this queue panel.
3. Show the currently playing song prominently.
4. Allow users to reorder or remove songs from the queue.
5. Make it easily accessible but not intrusive to the main experience. It should feel natural and intuitive for managing what plays next.


![Image](http://learn.nextwork.org/thankful_white_lucky_bicho_papao/uploads/ai-workspace-cursor_s4q5upload)

### Designing the Queue feature

To build a new queue feature, I prompted the Cursor Agent to add two buttons (play and add to queue) to the song cards. This allows the user to either add the song to the queue or play it right away.

### Troubleshooting and iterating

In this step, I'm going to fix any errors and any UI issues using screenshots because I want to create a queue feature that is operational end-to-end.

### Debugging with Cursor

I ran into an issue where when I click on a card, the song just starts playing. Also, no side panel was displayed to confirm the song was added to the queue. There was no queue button visible so that the user could access the queue at any time. 
I solved it by telling Cursor to add two buttons for play and add to queue on each song card. I mentioned that after adding the song to the queue, the add to queue button should turn into a tick and then a cancel. This way, the user could remove a song from the queue from both the song card and the queue panel.

---

## Managing AI Context

In this secret mission, I will learn to control Cursor's context by excluding certain files using a .cursorignore file. We will also control indexing by using a .cursorindexingignore file.

![Image](http://learn.nextwork.org/thankful_white_lucky_bicho_papao/uploads/ai-workspace-cursor_s6q4upload)

### Performance and security benefits

Managing context improves performance by using less data processing for faster responses and improves security by restricting AI's access to sensitive and confidential files. 

### Comparing .cursorignore and .cursorindexingignore

.cursorignore hides the mentioned files completely from cursor to avoid access and indexing while .cursorindexingignore only skips the files mentioned for indexing while keeping access for occasional access.

---

---
