# Experiment 8 – Implement Menus and WebView in Android

## Student Details

* **Name:** Mohammed Kaif Ulla
* **USN:** 25MCAR0226
* **Experiment No.:** 8
* **Title:** Implement Menus and WebView in an Android Application

---

## 1. Aim

To develop an Android application that demonstrates the implementation of an Options Menu and WebView. The application allows users to browse websites, search for information, navigate between web pages, refresh pages, and access menu options within the application.

## 2. Technologies Used

* Android Studio
* Kotlin Programming Language
* XML for User Interface Design
* Android WebView
* Android Options Menu
* Android SDK

## 3. Description

This application is a simple web browser called **Web Explorer**. It uses Android WebView to display web pages inside the application without opening a separate browser.

Users can enter website addresses or search queries, visit Google and Wikipedia, navigate backward and forward, refresh pages, and view experiment details through the Options Menu.

## 4. Features

1. **WebView:** Displays websites inside the Android application.
2. **Address/Search Bar:** Accepts website URLs and search queries.
3. **GO Button:** Opens the entered website or performs a Google search.
4. **Home Button:** Opens Google.
5. **Wikipedia Button:** Opens Wikipedia.
6. **Back Button:** Navigates to the previous web page.
7. **Forward Button:** Navigates to the next web page.
8. **Refresh Button:** Reloads the current website.
9. **About Option:** Displays experiment and student details.
10. **Exit Option:** Closes the application.
11. **Loading Status:** Displays the page-loading status.

## 5. Implementation

### 5.1 Android Options Menu

The Options Menu is created using an XML menu resource named `main_menu.xml`. It provides options such as Home, Wikipedia, Refresh Page, About this Experiment, and Exit.

The menu actions are handled in `MainActivity.kt` using the following methods:

* `onCreateOptionsMenu()`
* `onOptionsItemSelected()`

### 5.2 WebView

WebView is an Android component used to display web pages inside an application. In this project, it loads websites such as Google and Wikipedia and supports website navigation.

### 5.3 Address Bar and Search

The address bar accepts a website URL or search text. If the user enters a website address, the application opens the website. If the user enters search text, it displays Google search results.

### 5.4 Navigation History

The Back and Forward buttons use WebView's browsing history to navigate between previously visited pages.

### 5.5 Refresh Functionality

The Refresh button reloads the currently displayed web page using the WebView reload functionality.

### 5.6 About Dialog

The About option displays information about the experiment and student details.

## 6. Important Files

| File Name               | Description                                             |
| ----------------------- | ------------------------------------------------------- |
| `MainActivity.kt`       | Contains the main application logic and event handling. |
| `activity_main.xml`     | Defines the application user interface.                 |
| `main_menu.xml`         | Defines the Options Menu items.                         |
| `AndroidManifest.xml`   | Contains application configuration and permissions.     |
| `bg_address.xml`        | Defines the address bar background style.               |
| `bg_button_primary.xml` | Defines the primary button background.                  |
| `bg_button_light.xml`   | Defines the light button background.                    |

## 7. Steps to Run the Application

1. Clone or download this repository from GitHub.
2. Open Android Studio.
3. Select **Open** and choose the project folder.
4. Allow Gradle to sync and download the required dependencies.
5. Connect an Android device or start an emulator.
6. Click the **Run** button to build and launch the application.
7. Use the address bar, navigation buttons, and Options Menu to test the features.

**Note:** An active internet connection is required to load online websites.

## 8. Test Cases

| Test Case           | Expected Result                               |
| ------------------- | --------------------------------------------- |
| Open Home           | Google opens inside WebView.                  |
| Open Wikipedia      | Wikipedia opens inside WebView.               |
| Search a topic      | Google search results are displayed.          |
| Enter a website URL | The requested website opens.                  |
| Press Back          | The previous web page opens if available.     |
| Press Forward       | The next web page opens if available.         |
| Press Refresh       | The current web page reloads.                 |
| Select About        | Experiment and student details are displayed. |
| Select Exit         | The application closes.                       |

## 9. Output Screenshots

### Screenshot 1: Main Application Interface

**Output:**

<!-- Insert the main application screenshot here -->

<br><br><br><br><br><br><br><br>

### Screenshot 2: Website Display in WebView

**Output:**

<!-- Insert the WebView screenshot here -->

<br><br><br><br><br><br><br><br>

### Screenshot 3: Options Menu

**Output:**

<!-- Insert the Options Menu screenshot here -->

<br><br><br><br><br><br><br><br>

### Screenshot 4: About Experiment Dialog

**Output:**

<!-- Insert the About dialog screenshot here -->

<br><br><br><br><br><br><br><br>

---

## 10. Expected Output

The application displays a Web Explorer interface containing an address/search bar, navigation buttons, a WebView, loading status, and an Options Menu.

Users can browse websites, search for information, navigate between pages, refresh websites, and access additional options within the Android application.

## 11. Result

The Android application demonstrating **Menus and WebView** was developed successfully. The application supports website loading, search functionality, navigation history, menu handling, page refreshing, and displaying experiment details.

## 12. Conclusion

This experiment helped in understanding the implementation of Android Options Menus and WebView. It also demonstrated how to design a user-friendly interface and handle user interactions using Kotlin and XML.

---

## Submitted By

**Name:** Mohammed Kaif Ulla

**USN:** 25MCAR0226

**Experiment No.:** 8

**Experiment Title:** Implement Menus and WebView in an Android Application
