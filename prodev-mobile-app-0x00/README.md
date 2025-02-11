## prodev-mobile-setup README

This README documents the steps involved in setting up a new Expo project using the latest Expo Router template and the observations made after running the `npm run reset-project` command.

**1. Project Scaffolding**

* **Navigate to Project Directory:**
  ```bash
  cd prodev-mobile-setup
  ```

* **Initialize Expo Project:**
  ```bash
  npx create-expo-app@latest . 
  ```
  This command initializes a new Expo project within the current directory using the latest Expo Router template.

**2. Modify Home Screen**

* **Open `app/(tabs)/index.tsx`:** Locate the file containing the default home screen component.
* **Change Welcome! text:** Modify the default text "Welcome!" to "**First App Created**".

**3. Run and Test**

* **Start Expo Development Server:**
  ```bash
  npx expo start
  ```
* **Scan QR Code:** 
    * **iOS:** Scan the QR code displayed in the terminal using your iPhone's Camera app.
    * **Android:** Scan the QR code using the Expo Go app. 

**4. Reset Project**

* **Run Reset Command:**
  ```bash
  npm run reset-project
  ```

**Observations from `npm run reset-project`:**

* **File Changes:** The `reset-project` script likely deletes or modifies files within the project, such as:
    * **Generated files:** Files automatically created during the initial project setup (e.g., temporary files, build artifacts).
    * **Configuration files:** Files that may contain sensitive information or temporary settings.
* **Project State:** The project is effectively reset to a clean state, similar to a fresh installation. This can be useful for troubleshooting, resolving conflicts, or starting a project from scratch.

**Note:** The specific behavior of the `reset-project` script may vary depending on its implementation within the project.

