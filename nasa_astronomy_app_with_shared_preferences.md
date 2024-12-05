# NASA Astronomy Data App with Shared Preferences in Flutter (50 Marks)

<br><br>

## `Objective:`

<br>

> **Develop a Flutter app that allows users to fetch and display daily astronomy data using the NASA API, view detailed information on a separate screen, and save their favorite data using shared preferences for quick access. No live search is required.**

<br>

**API Information:** 
<br>

 * [NASA Astronomy Picture of the Day API:](https://api.nasa.gov/mars-photos/api/v1/rovers/curiosity/photos?sol=1000&api_key=JM1pH4LAuI5an0piy7i7TEmxmYiyJTdjOPivH9y9) <br>

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

  > * **10 marks:** Clean, intuitive design that presents astronomy data neatly. Good use of typography, layouts, and visuals.
  > * **8–9 marks:** Functional UI with minor layout or interaction issues. (e.g., minor alignment problems).
  > * **5–7 marks:** UI is basic but functional; significant room for improvement in design or interactivity.
  > * **0–4 marks:** UI is incomplete or poorly structured.

#### 3. Features Implementation (35 marks):

  -  **a. API Data Integration (10 marks):**
    
  > * **10 marks:** Correctly implemented API call to fetch daily astronomy data using the http package. JSON data is parsed and displayed accurately.
  > * **7–9 marks:** API is functional but may have minor issues (e.g., incomplete data handling).
  > * **4–6 marks:** API integration is incomplete or displays incorrect data.
  > * **0–3 marks:** API calls are not implemented or have significant issues.

  - **b. Astronomy Details Screen (10 Marks):**
    
  > * **10 marks:**  A well-designed details screen that shows comprehensive astronomy details (e.g., title, date, explanation, image/video).
  > * **7–9 marks:** Details screen is present but lacks some data or design improvements.
  > * **4–6 marks:** Details screen is incomplete or has major issues.
  > * **0–3 marks:** Details screen is missing or broken.

  - **c. Shared Preferences for Saving and Removing Astronomy Data (10 marks):**
    
  > * **10 marks:** Proper implementation of shared preferences for storing and removing liked astronomy data. Data persists after app restarts.
  > * **7–9 marks:** Shared preferences work but with minor issues (e.g., incorrect updates).
  > * **4–6 marks:** Partial or incorrect implementation of shared preferences.
  > * **0–3 marks:** Shared preferences are not implemented or functional.

  - **d. Displaying Saved Data (5 marks):**
    
  > * **5 marks:** Saved astronomy data is displayed neatly on the home screen when the app reopens.
  > * **3–4 marks:** Saved data is displayed, but there are minor issues in the UI or logic.
  > * **0–2 marks:** Saved data display is missing or non-functional.

   - **e. Remove Astronomy from Shared Preferences (5 marks):**
    
  > * **5 marks:** Removing Astronomy from saved preferences is fully functional and updates the UI correctly.
  > * **3–4 marks:** Remove functionality is present but has minor issues.
  > * **0–2 marks:** Remove functionality is missing or broken.

---

<br>

### `Features to Implement:`

  1. **Home Screen**:
     - Display a list of daily astronomy data fetched from the NASA API (e.g., title and image thumbnail).
     - Enable users to tap an item to navigate to its details screen.
     - Include buttons for saving or removing items as favorites.

2. **Astronomy Details Screen:**:
   - Show detailed information about the selected item (e.g., title, date, explanation, and full-sized image or video).
   - Provide a save/remove option to manage favorite data.

4. **Shared Preferences**:
   - Save favorite astronomy data to shared preferences.
   - Allow users to remove data from the favorite list.
   - Persist favorite data across app sessions and display them on the home screen.

5. **UI/UX Enhancements**:
   - Ensure an intuitive, clean design for the app.
   - Show feedback (e.g., toast messages) when a movie is added or removed from favorites.
