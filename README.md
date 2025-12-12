# AI-Powered Trip Planning Demo

This project demonstrates how to use a Large Language Model (LLM) like Google Gemini to plan a detailed road trip from start to finish. Even if you're new to AI or programming, this example shows how powerful these tools can be.

## What are LLMs and CLIs?

*   **Large Language Model (LLM):** Think of this as a very advanced AI chatbot (like Google Gemini or ChatGPT). It can understand what you write and generate human-like text, code, and more.
*   **Command-Line Interface (CLI):** This is a text-based way to interact with a computer. Instead of clicking buttons, you type commands. It's a powerful way to automate tasks, and many LLMs offer a CLI for developers and power users.

## The Process: From Idea to Itinerary

This demo shows a clever, multi-step process to get a high-quality result from the AI.

### Step 1: The Basic Idea

Everything started with a simple text file, `instruction.txt`, outlining the basic requirements for a road trip: destination, dates, and what I wanted to do.

### Step 2: Creating the AI's "Prompt"

To get the best results, AIs often need detailed instructions in a structured format. Instead of figuring out this format myself, I used a clever trick: **I asked the AI to create its own instructions!**

I gave my simple `instruction.txt` to Gemini and asked it to generate a detailed prompt file for itself. The result is `GEMINI.md`, which contains the detailed instructions the AI will follow.

### Step 3: Generating the Travel Plan

With the detailed instructions ready in `GEMINI.md`, all that was left was to give Gemini a simple command:

```shell
Create the travel plan based on the instruction in @GEMINI.md.
```

### Step 4: The AI-Generated Itinerary

Gemini then generated a complete and organized travel plan, broken down into several files:

*   `CHANGELOGS.md`: A log of all the files the AI created or changed.
*   `POI.md`: A detailed list of interesting places (Points of Interest) for the trip.
*   `Trip Overview.md`: A high-level summary of the entire trip.
*   `Trip-Day-01-option-01.md`: A detailed, day-by-day itinerary.
*   `Trip-Day-02-option-01.md`: (and so on for each day)

This shows how you can "bootstrap" your way to a great result by using the AI to help you formulate the perfect request.
