# SpaceX Launch Tracker App with Shared Preferences in Flutter (50 Marks)

<br><br>

## `Objective:`

<br>

> **Create a Flutter app that allows users to search for SpaceX launches using the SpaceX API, view detailed information about launches, and save favorite launches using shared preferences for quick access. Implement live search functionality to enhance the user experience.**

<br>

**API Information:** 
<br>

 * [SpaceX Launches API:](https://www.googleapis.com/books/v1/volumes?q=flowers+inauthor:keyes) <br>

---

### `Submission Requirements:`

<br>

* **Submission Format:** Provide a photo or video walkthrough of your app's functionality.
* **Total Marks: 50**

---

### `Marking Criteria:`

<br>

#### 1. Photo/Video Submission (5 marks):

  > * **5 marks:** Clear, detailed walkthrough covering the app's main features.
  > * **3–4 marks:** Video/photo provided but lacks coverage of some interactions or features.
  > * **0–2 marks:** Submission is unclear or incomplete.

#### 2. UI Implementation (10 marks):

  > * **10 marks:** Clean, intuitive design that presents launch data neatly. Good use of typography, layouts, and visuals.
  > * **8–9 marks:** Functional UI with minor layout or interaction issues. (e.g., minor alignment problems).
  > * **5–7 marks:** UI is basic but functional; significant room for improvement in design or interactivity.
  > * **0–4 marks:** UI is incomplete or poorly structured.

#### 3. Features Implementation (35 marks):

  -  **a. API Data Integration (10 marks):**
    
  > * **10 marks:** Correctly implemented API calls to fetch and display SpaceX launches using the http package. JSON data is parsed and displayed accurately.
  > * **7–9 marks:** API is functional but may have minor issues (e.g., incomplete data handling).
  > * **4–6 marks:** API integration is incomplete or displays incorrect data.
  > * **0–3 marks:** API calls are not implemented or have significant issues.

  - **b. Launch Details Screen (10 Marks):**
    
  > * **10 marks:**  A well-designed details screen that shows comprehensive launch details (e.g., mission name, date, rocket name, success/failure status, and launch site).
  > * **7-9 marks:** Details screen is present but lacks some data or design improvements.
  > * **4-6 marks:** Details screen is incomplete or displays incorrect data.
  > * **0–2 marks:** Details screen is missing or broken.

  - **d. Shared Preferences for Saving and Removing Favorite Launches (10 Marks):**
    
  > * **10 marks:** Proper implementation of shared preferences for storing and removing favorite launches. Data persists after app restarts.
  > * **7–9 marks:** Shared preferences work but with minor issues (e.g., incorrect updates).
  > * **4–6 marks:** Partial or incorrect implementation of shared preferences.
  > * **0–3 marks:** Shared preferences are not implemented or functional.

  - **c. Displaying Favorite Launches (5 marks):**
    
  > * **5 marks:** Saved Launches are displayed neatly on the home screen when the app reopens.
  > * **3–4 marks:** Saved Launches are displayed, but there are minor issues in the UI or logic.
  > * **0–2 marks:** Saved Launches display is missing or non-functional.

   - **e. Removing Favorite Launches (5 marks):**
    
  > * **5 marks:** Removing Launches from the saved list is fully functional and updates the UI correctly.
  > * **3–4 marks:** Remove functionality is present but has minor issues.
  > * **0–2 marks:** Remove functionality is missing or broken.

---

<br>

### `Features to Implement:`

  1. **Home Screen**:
     - Display a list of SpaceX launches (mission name, date, rocket name, and status) retrieved from the API.
     - Enable users to tap on a launch to navigate to its details screen.
     - Include buttons for liking or unliking launches.

2. **Launch Details Screen**:
   - Show detailed information about the selected launch (e.g., mission name, date, rocket name, success/failure status, and launch site).
   - Include a like/unlike button to manage favorite launches.

3. **Shared Preferences**:
   - Save liked launches to shared preferences.
   - Allow users to remove launches from the saved list.
   - Persist liked launches across app sessions and display them on the home screen.

4. **UI/UX Enhancements**:
   - Ensure an intuitive, clean design for the app.
   - Show feedback (e.g., toast messages) when a movie is added or removed from favorites.
