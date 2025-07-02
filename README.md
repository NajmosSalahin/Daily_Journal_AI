# Advanced Health Journal with AI Insights

## Overview

This project is an interactive web-based health journal designed to help users track various aspects of their daily well-being, from physical vitals and nutrition to mental health and productivity. It leverages AI (via the Gemini API) to provide insightful summaries of journal entries, daily recommendations, and guided journaling sessions, fostering deeper self-reflection and personal growth.

The application is built with a focus on a clean, responsive user interface using Tailwind CSS and vanilla JavaScript for dynamic functionality. All data is stored locally in the browser's Local Storage, ensuring privacy and quick access.

## Features

* **Comprehensive Journaling Form:** A detailed form with collapsible sections covering:
    * Personal Identification
    * Mental & Emotional Health
    * Sleep Tracking
    * Physical Vitals
    * Biological & Medical
    * Nutrition & Intake
    * Physical Activity & Fitness
    * Lifestyle & Environment
    * Habits, Productivity & Focus
* **AI-Powered Insights:**
    * **Journal Entry Summaries:** Generates a thoughtful, narrative summary of your day based on your filled-out entry, reflecting on connections between different health aspects.
    * **Daily Recommendations:** Provides personalized self-care activities, nutritional insights, and coping tips based on your journal data.
    * **Guided Journaling:** An interactive chat interface where AI asks open-ended follow-up questions to help you explore your thoughts and feelings deeper.
* **Saved Entries Management:**
    * View all past journal entries, sorted by date.
    * Search and filter entries by keywords or date.
    * Expand/collapse entries to view full details, including AI summaries and recommendations.
    * Delete individual entries.
    * Export all entries as a Markdown file for offline viewing or backup.
* **User-Friendly Interface:**
    * Intuitive tab-based navigation for "New Entry," "Saved Entries," and "Guided Journaling."
    * Responsive design for optimal viewing on various devices (desktop, tablet, mobile).
    * Custom scrollbars and smooth transitions for an enhanced user experience.
    * AI Help buttons for specific fields to explain why tracking certain metrics is important.
* **Local Storage:** All journal entries are securely saved in your browser's local storage, ensuring your data remains private and accessible only to you.

## Technologies Used

* **HTML5:** Structure of the web application.
* **Tailwind CSS:** For rapid and responsive styling.
* **JavaScript (Vanilla JS):** Core logic, DOM manipulation, form handling, and AI API interactions.
* **Marked.js:** For parsing and rendering Markdown content (especially for AI-generated text).
* **Google Fonts:** "Inter" and "Lora" for typography.
* **Gemini API:** For AI-powered text generation (summaries, recommendations, guided questions).

## Setup and Usage

This is a client-side HTML file, so no complex setup is required.

1.  **Download the file:** Save the `Moodtracker.html` file to your local machine.
2.  **Open in Browser:** Simply open the `Moodtracker.html` file in any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

The application will load directly, and you can start using it immediately. Your data will be saved automatically in your browser's local storage.

## Project Structure

The entire application is contained within a single `Moodtracker.html` file, which includes:

* **`<head>`:**
    * Meta tags for character set and viewport.
    * Title.
    * Links to Tailwind CSS and Google Fonts.
    * Script for Marked.js.
    * Inline `<style>` block for custom CSS.
* **`<body>`:**
    * Header section.
    * Tab navigation.
    * Main content areas for "New Entry," "Saved Entries," and "Guided Journaling."
    * AI Explanation Modal structure.
    * Main `<script>` block containing all JavaScript logic, including:
        * Local storage functions.
        * Dynamic form generation based on `formStructure`.
        * Form submission handling and AI integration.
        * Saved entries display and filtering logic.
        * AI explanation and recommendations functions.
        * Guided journaling chat logic.
        * Custom message box implementation.

## Contributing

As this is a self-contained personal project, direct contributions are not actively sought. However, feel free to fork the repository, experiment with the code, and adapt it to your needs!

If you find any bugs or have suggestions, please open an issue on the GitHub repository.
