[閱讀繁體中文版](./README-zh-tw.md)

# AI-Powered Trip Planning: A Simple Guide

This project shows how an AI, like Google's Gemini, can plan a detailed road trip for you. It's a peek into how you can work with AI to get exactly what you want, even if you don't know how to code.

## What is an AI Assistant?

Imagine you have a super-smart assistant. You can give it tasks by talking or typing. In this project, we use a text-based AI assistant called a **Command-Line Interface (CLI)**. Instead of clicking buttons on a screen, you give it written commands. It's a bit like texting someone to get things done.

The "brain" behind this assistant is a **Large Language Model (LLM)**, the same technology that powers AI chatbots like Gemini or ChatGPT.

## The Journey: From a Simple Idea to a Full Itinerary

We planned a road trip from Los Angeles to Phoenix. Here’s how we used the AI assistant to do it, in just a few steps.

### Step 1: The Basic Idea

We started with a simple note, like a rough draft in a notebook. This file, [instruction.txt](./instruction.txt), had the basic details: where we wanted to go, when, and for how long.

### Step 2: Teaching the AI to Be a Great Trip Planner

To get a really good travel plan, you need to give the AI clear and detailed instructions. But what's the best way to do that? Instead of guessing, we used a clever trick: **we asked the AI to write its own instructions!**

We gave our simple [instruction.txt](./instruction.txt) note to the AI and said: *"Turn this into a perfect set of instructions for an AI trip planner."*

The AI created a new file, [GEMINI.md](./GEMINI.md), which is a detailed blueprint for what a perfect trip plan should look like. It defined the structure, what files to create, and how to organize everything.

### Step 3: Putting the AI to Work

With the blueprint ready, we just had to give the final command:

*"Now, create the travel plan using the instructions in `GEMINI.md`."*

### Step 4: The Result - A Perfect Itinerary

The AI followed its own instructions and generated a complete travel package:

*   [POI.md](./POI.md): A list of interesting places to visit (Points of Interest).
*   [Trip Overview.md](./Trip%20Overview.md): A summary of the whole trip.
*   [Trip-Day-01-option-01.md](./Trip-Day-01-option-01.md) (and others): A detailed plan for each day of the journey.
*   [CHANGELOGS.md](./CHANGELOGS.md): A log of all the files it created.

This process shows that you don't have to be an expert to get great results from an AI. You can guide it, and even ask it to help you improve your own requests.

## Why is the `GEMINI.md` file so useful?

Think of [GEMINI.md](./GEMINI.md) as the "rulebook" for our trip planning. By creating this rulebook, we ensure the AI is consistent every time we interact with it.

For example, if we later want to change one part of the trip (like adding a stop on Day 2), the AI will look at the rulebook and know it needs to update the daily plan, the trip overview, and maybe even the list of points of interest—all automatically. It keeps everything organized and prevents the AI from forgetting our original goals.
