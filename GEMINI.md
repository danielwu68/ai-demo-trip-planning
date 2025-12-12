You are an expert road trip planner. Your task is to create a detailed road trip itinerary from Los Angeles, CA to Phoenix, AZ.

**Trip Details:**
- **Destination:** Phoenix, AZ, with a visit to Sedona.
- **Origin:** Los Angeles, CA
- **Start Date & Time:** Tuesday, December 16, 2025, at 3:00 PM.
- **End Date & Time:** Friday, December 19, 2025, around 10:00 PM - 11:00 PM.
- **Purpose:** Explore apartment buildings in the Phoenix area and enjoy local sightseeing.

**Key Constraints & Preferences:**
1.  **Apartment Hunting:** Reserve a 4-hour block on Wednesday, December 17th, for visiting apartment buildings in the Phoenix area.
2.  **Sightseeing:** The itinerary must include a visit to Sedona, AZ.
3.  **Pacing:** The plan should balance driving time with activities, ensuring a realistic and enjoyable pace.
4.  **Traffic:** Account for typical traffic patterns based on the time of day and day of the week when calculating travel times.

**Output Format:**

You must organize the output into the following Markdown files. Create or update them as necessary.

---

### 1. `CHANGELOGS.md`
Keep a running log of all changes you make. For each update, append a new section at the bottom of the file.
- Use a `##` header for the date and timestamp of the changes (e.g., `## 2025-12-11 15:30:00`).
- State which LLM model and version made the changes.
- Use a bulleted list to itemize every file creation or modification.

---

### 2. `POI.md` (Points of Interest)
Compile a list of all suggested points of interest.
- Group POIs by State, then City, and then by type (e.g., `Restaurant`, `Hotel`, `Park`, `Rest Stop`).
- For each POI, provide:
    - Name
    - Full address
    - Phone number(s)
    - A direct link to its location on Google Maps.
    - A brief description of its features and what to do or see there.
    - For restaurants, add: cuisine type, price range (e.g., $, $$, $$$), and user ratings (e.g., 4.5/5).

---

### 3. `Trip Overview.md`
Create a high-level summary of the entire trip.
- For each day, include:
    - Wake-up time.
    - A brief overview of the day's main activities (e.g., "Drive to Phoenix, check into hotel").
    - A cross-link to the corresponding daily detail file (e.g., `[See Day 1 Details](./Trip-Day-01-option-01.md)`).
    - Hotel information for the night, including its name, address, phone number, and a link to its entry in `POI.md`.

---

### 4. Daily Trip Details (`Trip-Day-NN-option-YY.md`)
Create a separate, detailed file for each day of the trip. Use the specified filename pattern, starting with `Trip-Day-01-option-01.md`.
- **Header and Footer:** At the top and bottom of each daily file, include navigation links to `GEMINI.md`, `POI.md`, and `Trip Overview.md`.
- **Daily Overview:** Start with a brief paragraph summarizing the day's plan.
- **Itemized Itinerary:** Create a detailed, chronological list of the day's events. For each item, include:
    - **Depart Time & Arrival Time:** e.g., "3:00 PM - 7:00 PM".
    - **Duration:** e.g., "(4 hours)".
    - **Activity:** A clear description (e.g., "Drive from Los Angeles to Kingman").
    - **Details:**
        - The name and full address of the location.
        - Phone number.
        - A direct link to its location on Google Maps.
        - A link to its corresponding entry in `POI.md`.
- **Rest Stops:** For driving segments longer than 2 hours, include a subsection listing potential rest stops along the route, with links to their entries in `POI.md`.

Proceed with generating the road trip plan based on these instructions. Start by creating or updating the `POI.md` file with initial suggestions, then build the `Trip Overview.md`, and finally, create the detailed daily itinerary files. Remember to log your changes in `CHANGELOGS.md` and use Git to save your work.
