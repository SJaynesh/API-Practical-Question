# Book Explorer App with Shared Preferences in Flutter (50 Marks)

<br><br>

## `Objective:`

<br>

> **Create a Flutter app that allows users to search for books using the Google Books API, view detailed information about books, and save favorite books using shared preferences for quick access. Implement live search functionality to enhance the user experience.**

<br>

**API Information:** 
<br>

 * [Book Search API:](https://www.googleapis.com/books/v1/volumes?q=flowers+inauthor:keyes) <br>

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
    
  > * **10 marks:** Correctly implemented API calls for live book search and book details using the http package. JSON data is parsed and displayed accurately.
  > * **7–9 marks:** API is functional but may have minor issues (e.g., incomplete data handling).
  > * **4–6 marks:** API integration is incomplete or displays incorrect data.
  > * **0–3 marks:** API calls are not implemented or have significant issues.
  
  - **b. Live Search Feature (5 Marks):**
    
  > * **5 marks:** Real-time book search feature implemented with results updating as the user types.
  > * **3–4 marks:** Search works but has delays or minor functionality issues.
  > * **0–2 marks:** Search functionality is missing or non-functional.

  - **c. Book Details Screen (10 Marks):**
    
  > * **10 marks:**  A well-designed details screen that shows comprehensive book details (e.g., title, author, description, cover image, and publisher).
  > * **7-9 marks:** Details screen is present but lacks some data or design improvements.
  > * **4-6 marks:** Details screen is incomplete or displays incorrect data.
  > * **0–2 marks:** Details screen is missing or broken.

  - **d. Shared Preferences for Saving and Removing Favorite Books (10 marks):**
    
  > * **10 marks:** Proper implementation of shared preferences for storing and removing favorite books. Data persists after app restarts.
  > * **7–9 marks:** Shared preferences work but with minor issues (e.g., incorrect updates).
  > * **4–6 marks:** Partial or incorrect implementation of shared preferences.
  > * **0–3 marks:** Shared preferences are not implemented or functional.

  - **e. Displaying Favorite Books (5 marks):**
    
  > * **5 marks:** Saved books are displayed neatly on the home screen when the app reopens.
  > * **3–4 marks:** Saved books are displayed, but there are minor issues in the UI or logic.
  > * **0–2 marks:** Saved books display is missing or non-functional.

   - **f. Removing Favorite Books (5 marks):**
    
  > * **5 marks:** Removing books from the saved list is fully functional and updates the UI correctly.
  > * **3–4 marks:** Remove functionality is present but has minor issues.
  > * **0–2 marks:** Remove functionality is missing or broken.

---

<br>

### `Features to Implement:`

  1. **Home Screen**:
     - Implement a search bar for live book name search.
     - Display a list of books (title, author, cover image, and short description) retrieved from the API.
     - Enable users to tap on a book to navigate to its details screen.
     - Include buttons for liking or unliking books.

2. **Book Details Screen**:
   - Show detailed information about the selected book (e.g., title, author, description, publisher, and cover image).
   - Include a like/unlike button to manage favorite books.

3. **Shared Preferences**:
   - Save liked books to shared preferences.
   - Allow users to remove books from the saved list.
   - Persist liked books across app sessions and display them on the home screen.

4. **UI/UX Enhancements**:
   - Ensure an intuitive, clean design for the app.
   - Show feedback (e.g., toast messages) when a movie is added or removed from favorites.
