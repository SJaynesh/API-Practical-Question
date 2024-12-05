# Movie Finder App with Shared Preferences in Flutter (50 Marks)

<br><br>

## `Objective:`

<br>

> **Develop a Flutter app that allows users to search for movies using the OMDB API, view movie details, and save their favorite movies using shared preferences for quick access. Implement live search functionality and display the movie poster, title, and other details on a separate details screen.**

<br>

**API Endpoint for Country Data :** 
<br>

 * [Multiple Movie Search:](https://www.omdbapi.com/?s=moviename&apikey=APIkey) <br>
 * [Single Movie Search:](https://www.omdbapi.com/?t=moviename&apikey=APIkey)

---

### `Submission Requirements:`

<br>

* **Submission Format:** Provide a photo or video walkthrough of your app's functionality.
* **Total Marks: 50**

---

### `Marking Criteria:`

<br>

#### 1. Photo/Video Submission (5 marks):

  > * **5 marks:** Clear, comprehensive video/photo that showcases the app's core features and functionality.
  > * **3–4 marks:** Video/photo provided but missing some key interactions or features.
  > * **0–2 marks:** Submission is incomplete or unclear.

#### 2. UI Implementation (10 marks):

  > * **10 marks:** Clean, intuitive design that presents movie data neatly. Good use of typography, layouts, and visuals.
  > * **8–9 marks:** Functional UI with minor layout or interaction issues. (e.g., minor alignment problems).
  > * **5–7 marks:** UI is basic but functional; significant room for improvement in design or interactivity.
  > * **0–4 marks:** UI is incomplete or poorly structured.

#### 3. Features Implementation (35 marks):

  -  **a. API Data Integration (10 marks):**
    
  > * **10 marks:** Correctly implemented API calls for live search and movie details using the http package. JSON data is parsed and displayed accurately.
  > * **7–9 marks:** API is functional but may have minor issues (e.g., incomplete data handling).
  > * **4–6 marks:** API integration is incomplete or displays incorrect data.
  > * **0–3 marks:** API calls are not implemented or have significant issues.
  
  - **b. Live Search Feature (5 Marks):**
    
  > * **5 marks:** Real-time search feature implemented with results updating as the user types.
  > * **3–4 marks:** Search works but has delays or minor functionality issues.
  > * **0–2 marks:** Search functionality is missing or non-functional.

  - **c. Movie Details Screen (5 Marks):**
    
  > * **5 marks:**  A well-designed details screen that shows comprehensive movie details (e.g., title, year, genre, plot, actors, poster).
  > * **3–4 marks:** Details screen is present but lacks some data or design improvements.
  > * **0–2 marks:** Details screen is missing or broken.

  - **d. Shared Preferences for Saving and Removing Favorite Movies  (10 marks):**
    
  > * **10 marks:** Proper implementation of shared preferences for storing and removing liked movies. Data persists after app restarts.
  > * **7–9 marks:** Shared preferences work but with minor issues (e.g., incorrect updates).
  > * **4–6 marks:** Partial or incorrect implementation of shared preferences.
  > * **0–3 marks:** Shared preferences are not implemented or functional.

  - **e. Displaying Saved Data (5 marks):**
    
  > * **5 marks:** Saved movies are displayed neatly on the home screen when the app reopens.
  > * **3–4 marks:** Saved data is displayed, but there are minor issues in the UI or logic.
  > * **0–2 marks:** Saved data display is missing or non-functional.

   - **f. Remove Movies from Shared Preferences (5 marks):**
    
  > * **5 marks:** Removing movies from saved preferences is fully functional and updates the UI correctly.
  > * **3–4 marks:** Remove functionality is present but has minor issues.
  > * **0–2 marks:** Remove functionality is missing or broken.

---

<br>

### `Features to Implement:`

  1. **Home Screen**:
     - Implement a search bar for live movie search using the OMDB API.
     - Display a list of movies (title, poster, and release year) retrieved from the API.
     - Enable users to tap a movie to navigate to its details screen.
     - Include buttons for saving or removing movies as favorites.

2. **Movie Details Screen:**:
   - Show detailed information about the selected movie (title, year, genre, plot, actors, and poster).
   - Provide a save/remove option to manage favorite movies.

3. **Shared Preferences**:
   - Save favorite movies to shared preferences.
   - Allow users to remove movies from the favorite list.
   - Persist favorite movies across app sessions and display them on the home screen.

4. **UI/UX Enhancements**:
   - Ensure an intuitive, clean design for the app.
   - Show feedback (e.g., toast messages) when a movie is added or removed from favorites.
