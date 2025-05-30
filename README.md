# Netflips - A Netflix-Style Clone with AI Suggestions

A Netflix-style clone built with HTML, Tailwind CSS, and JavaScript, featuring AI-powered content suggestions via the Gemini API to recommend similar titles.

## Features

* **Netflix-Inspired UI:** Dark theme, familiar layout with a hero section and horizontally scrolling content carousels.
* **Dynamic Content Loading:** Movie and show data is loaded from a JavaScript object (simulating an API).
* **Responsive Design:** Adapts to various screen sizes.
* **Header:** Sticky header that changes appearance on scroll.
* **Hero Section:** Displays a featured movie/show with title, description, and action buttons.
* **Content Carousels:** Organizes content into categories like "Trending Now," "Sci-Fi Adventures," etc.
* **✨ AI-Powered Suggestions:** Click a button on a movie/show card to get AI-generated suggestions for similar fictional titles using the Google Gemini API.
* **Modal Dialogs:**
    * Displays AI-generated suggestions.
    * Shows more information about a selected movie/show.
* **Basic Interactivity:** Hover effects on cards, clickable elements.

## Technologies Used

* **HTML5:** For the basic structure of the web pages.
* **Tailwind CSS:** For utility-first styling and responsive design.
* **JavaScript (ES6+):** For dynamic content rendering, interactivity, and API integration.
* **Google Gemini API:** For generating AI-powered content suggestions.
* **Google Fonts (Inter):** For typography.

## How to Run Locally

1.  **Clone the repository (if it's on GitHub):**
    ```bash
    git clone <https://github.com/NotAbhayKumar/NetFlips>
    cd <NetFlips>
    ```
    Alternatively, if you just have the HTML file:
2.  **Save the Code:**
    * Ensure you have the complete HTML code (which includes the CSS within `<style>` tags and JavaScript within `<script>` tags).
    * Save this code in a file named `index.html` (or any other `.html` name) on your local machine.
3.  **Open in Browser:**
    * Navigate to the directory where you saved the `index.html` file.
    * Double-click the `index.html` file, or right-click and choose "Open with" your preferred web browser (e.g., Chrome, Firefox, Edge).

  ## Gemini API Setup (for AI Suggestions)

To enable the "Suggest Similar ✨" feature, you need a Google Gemini API key:

1.  **Get an API Key:**
    * Visit [Google AI Studio](https://aistudio.google.com/) and create an API key.
2.  **Add the API Key to the Code:**
    * Open the `index.html` file (or your main HTML file).
    * Locate the JavaScript section towards the bottom of the file.
    * Find the following line within the `fetchAISuggestions` function:
        ```javascript
        const apiKey = ""; // Left empty as per instructions
        ```
    * Replace the empty string `""` with your actual Gemini API key:
        ```javascript
        const apiKey = "YOUR_ACTUAL_API_KEY";
        ```
    * Save the file.

**Note:** You will need an active internet connection for the AI suggestion feature to work.

## To-Do / Future Enhancements

* [ ] Implement actual video playback.
* [ ] Add user authentication.
* [ ] Create a "My List" functionality.
* [ ] Develop a more detailed movie/show details page/modal.
* [ ] Implement search and filtering capabilities.
* [ ] Fetch content from a real backend API or database instead of a static JS object.
* [ ] Add more sophisticated carousel controls (next/previous buttons).
* [ ] Explore other Gemini API integrations (e.g., generating plot summaries, character backstories).

## License

This project is licensed under the **MIT License**.
