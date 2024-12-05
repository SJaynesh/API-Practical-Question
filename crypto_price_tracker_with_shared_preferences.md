# Crypto Price Tracker App with Shared Preferences in Flutter (50 Marks)

<br><br>

## `Objective:`

<br>

> **Create a Flutter app that fetches cryptocurrency price data from the CoinGecko API, allows users to view cryptocurrency details, and save their favorite cryptocurrencies using shared preferences for quick access.**

<br>

**API Information:** 
<br>

 * [Cryptocurrency Prices:](https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd)

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

  > * **10 marks:** Clean, intuitive design that presents cryptocurrency data neatly. Good use of typography, layouts, and visuals.
  > * **8–9 marks:** Functional UI with minor layout or interaction issues. (e.g., minor alignment problems).
  > * **5–7 marks:** UI is basic but functional; significant room for improvement in design or interactivity.
  > * **0–4 marks:** UI is incomplete or poorly structured.

#### 3. Features Implementation (35 marks):

  -  **a. API Data Integration (10 marks):**
    
  > * **10 marks:** Correctly implemented API calls for fetching cryptocurrency prices and details using the http package. JSON data is parsed and displayed accurately.
  > * **7–9 marks:** API is functional but may have minor issues (e.g., incomplete data handling).
  > * **4–6 marks:** API integration is incomplete or displays incorrect data.
  > * **0–3 marks:** API calls are not implemented or have significant issues.
  
  - **b. Crypto Details Screen (10 Marks):**
    
  > * **10 marks:** A well-designed details screen that shows comprehensive cryptocurrency details (e.g., name, current price, market cap, 24-hour change, and logo).
  > * **7-9 marks:** Details screen is present but lacks some data or design improvements.
  > * **4–6 marks:** Details screen is incomplete or displays incorrect data.
  > * **0-3 marks:** Details screen is missing or broken.

  - **c. Shared Preferences for Saving and Removing Favorite Cryptos (10 marks):**
    
  > * **10 marks:** PProper implementation of shared preferences for storing and removing favorite cryptocurrencies. Data persists after app restarts.
  > * **7–9 marks:** Shared preferences work but with minor issues (e.g., incorrect updates).
  > * **4–6 marks:** Partial or incorrect implementation of shared preferences.
  > * **0–3 marks:** Shared preferences are not implemented or functional.

  - **d. Displaying Favorite Cryptos (5 marks):**
    
  > * **5 marks:** Saved cryptocurrencies are displayed neatly on the home screen when the app reopens.
  > * **3–4 marks:** Saved cryptocurrencies are displayed, but there are minor issues in the UI or logic.
  > * **0–2 marks:** Saved cryptocurrencies display is missing or non-functional.

   - **e. Remove Cryptos from Shared Preferences (5 Marks):**
    
  > * **5 marks:** Removing cryptocurrencies from favorites is fully functional and updates the UI correctly.
  > * **3–4 marks:** Remove functionality is present but has minor issues.
  > * **0–2 marks:** Remove functionality is missing or broken.

---

<br>

### `Features to Implement:`

  1. **Home Screen**:
     - Fetch and display a list of cryptocurrencies (name, logo, current price, 24-hour price change) retrieved from the API.
     - Allow users to select a cryptocurrency to view its detailed information.
     - Include buttons for liking or unliking cryptocurrencies.

2. **Crypto Details Screen**:
   - Display detailed information about the selected cryptocurrency (e.g., name, logo, current price, market cap, 24-hour change, etc.).
   - Provide an option to like/unlike the cryptocurrency and manage favorite cryptos.

3. **Shared Preferences**:
   - Save liked cryptocurrencies to shared preferences.
   - Allow users to remove cryptocurrencies from the liked list.
   - Persist liked cryptocurrencies across app sessions and display them on the home screen.

4. **UI/UX Enhancements**:
   - Ensure an intuitive, clean design for the app.
   - Show feedback (e.g., toast messages) when a movie is added or removed from favorites.
