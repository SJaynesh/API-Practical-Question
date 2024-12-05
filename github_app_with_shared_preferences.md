# GitHub User Search App with Shared Preferences in Flutter (50 Marks)

<br><br>

## `Objective:`

<br>

> **Create a Flutter app that allows users to search for GitHub users using the GitHub API, view detailed user profiles, display their repositories, and save starred users using shared preferences for quick access. Implement live search functionality to enhance the user experience.**

<br>

**API Information:** 
<br>

 * [User Search:](https://api.github.com/users/{username}) <br>
 * [User Repositories:](https://api.github.com/users/{username}/repos)

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

  - **c. User Details Screen (5 Marks):**
    
  > * **5 marks:**  A well-designed details screen that shows comprehensive user details (e.g., avatar, username, bio, followers, following, etc.).
  > * **3–4 marks:** Details screen is present but lacks some data or design improvements.
  > * **0–2 marks:** Details screen is missing or broken.

  - **d. User Repositories Screen (5 Marks):**
    
  > * **5 marks:** Display a list of the user's repositories (name, description, stars, forks).
  > * **3–4 marks:** Repositories are displayed but the layout is cluttered or lacks data.
  > * **0–2 marks:** Repositories are missing or not displayed correctly.

  - **e. Shared Preferences for Saving and Removing Starred Users  (10 marks):**
    
  > * **10 marks:** Proper implementation of shared preferences for storing and removing starred users. Data persists after app restarts.
  > * **7–9 marks:** Shared preferences work but with minor issues (e.g., incorrect updates).
  > * **4–6 marks:** Partial or incorrect implementation of shared preferences.
  > * **0–3 marks:** Shared preferences are not implemented or functional.

  - **f. Displaying Starred Users (5 marks):**
    
  > * **5 marks:** Saved movies are displayed neatly on the home screen when the app reopens.
  > * **3–4 marks:** Saved data is displayed, but there are minor issues in the UI or logic.
  > * **0–2 marks:** Saved data display is missing or non-functional.

   - **g. Remove Starred Users from Shared Preferences (5 marks):**
    
  > * **5 marks:** Removing users from saved preferences is fully functional and updates the UI correctly.
  > * **3–4 marks:** Remove functionality is present but has minor issues.
  > * **0–2 marks:** Remove functionality is missing or broken.

---

<br>

### `Features to Implement:`

  1. **Home Screen**:
     - Implement a search bar for live GitHub user search.
     - Display a list of users (avatar, username, and bio snippet) retrieved from the API.
     - Enable users to tap on a user to navigate to their details screen.
     - Include buttons for starring or unstarring users.

2. **User Details Screen**:
   - Show detailed information about the selected user (e.g., avatar, username, bio, followers, following).
   - Include a navigation option to view the user's repositories.
   - Provide a star/unstarring option to manage favorite users.

3. **Repositories Screen**:
   - Display the list of repositories for the selected user.
   - Show relevant details such as name, description, stars, and forks.

4. **Shared Preferences**:
   - Save starred users to shared preferences.
   - Allow users to remove users from the starred list.
   - Persist starred users across app sessions and display them on the home screen.

5. **UI/UX Enhancements**:
   - Ensure an intuitive, clean design for the app.
   - Show feedback (e.g., toast messages) when a movie is added or removed from favorites.
