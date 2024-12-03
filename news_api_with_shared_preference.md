# News Data API with Shared Preferences in Flutter (50 marks)

<br><br>

## `Objective:`

<br>

> **Create a News app by using an API. Provide category-wise news headlines to the user. Also, store the news article which you liked with the current date and time into your local storage using shared preferences and show them into different screen by pressing a button from AppBar.**

<br>

**API Endpoint for Country Data :** 
<br>
 * [News Data]([https://restcountries.com/v3.1/all](https://newsapi.org/docs/endpoints/sources)) 

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

  > * **10 marks:** Clean, user-friendly interface that presents country data in an organized way. Good use of layouts, typography, and styling.
  > * **8–9 marks:** Functional UI but with minor UI/UX issues (e.g., minor alignment problems).
  > * **5–7 marks:** UI is present but needs improvements in layout or user interaction.
  > * **0–4 marks:** UI is incomplete or hard to navigate.

#### 3. Features Implementation (35 marks):

  -  **a. API Data Integration (10 marks):**
    
  > * **10 marks:** Correct implementation of the API call using the http package. Proper parsing of JSON data and displaying it in a ListView.
  > * **7–9 marks:** API call is functional but may have minor issues (e.g., missing error handling).
  > * **4–6 marks:** API call works but data is not parsed or displayed correctly.
  > * **0–3 marks:** API call is not implemented or has significant issues.
  
  - **b. Displaying News Data with category wise (5 marks):**
    
  > * **5 marks:** News data is displayed in an with category wise organized, visually appealing format (e.g., using ListTile, Card, or Container).
  > * **3–4 marks:** Data is displayed, but layout is cluttered or not fully optimized.
  > * **0–2 marks:** Data display is missing or incorrectly implemented.

  - **c. User Selection and Navigation (5 marks):**
    
  > * **5 marks:** Correct implementation of navigation to the details screen when a news item is selected. The details screen displays comprehensive information about the news item.
  > * **3–4 marks:** Navigation works, but the details screen is missing some data or has layout issues.
  > * **0–2 marks:** Navigation or details screen implementation is missing or broken.

  - **d. Shared Preferences for Saving and Removing News Details (10 marks):**
    
  > * **10 marks:** Correct implementation of shared preferences to save and remove a user's selected news. Data persists after the app is closed and reopened.
  > * **7–9 marks:** Shared preferences implementation works, but may lack additional data validation or minor functionality issues.
  > * **4–6 marks:** Shared preferences are partially implemented or not integrated correctly.
  > * **0–3 marks:** Shared preferences are not used or implemented incorrectly.

  - **e. Liked News Headlines (5 marks):**
    
  > * **5 marks:** Click on the news link and Liked News Headlines will work perfectly.
  > * **3–4 marks:** Click on the news link, but it may not be integrated seamlessly or visually appealing.
  > * **0–2 marks:** Click on the news link is missing or not functioning.

   - **f. Remove News data from Shared Preferences (5 marks):**
    
  > * **5 marks:** Proper implementation of removing a saved news's details from shared preferences, with the app reflecting this change upon reopening.
  > * **3–4 marks:** Remove functionality is present but may have minor UI/UX issues.
  > * **0–2 marks:** Remove functionality is missing or not working.

---

<br>

### `Features to Implement:`

  1. **Home Screen**:
     - Display a list of countries retrieved from the API.
     - Each country should show its name, capital, and flag.
     - Allow users to tap on a country to navigate to its details screen.
     - Provide buttons or interactions for saving or removing a preferred country from shared preferences.

2. **Country Details Screen**:
   - Display comprehensive information about the selected country, such as population, region, languages, and more.

3. **Shared Preferences**:
   - Save the user's preferred country using shared preferences.
   - Remove a preferred country from shared preferences.
   - Show the saved country data on the home screen when the app is reopened.

4. **UI/UX Enhancements**:
   - Implement an intuitive and user-friendly layout that includes buttons for saving and removing preferences.
   - Display a message when a country is successfully saved or removed from shared preferences.
