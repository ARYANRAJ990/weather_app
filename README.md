# Weather App

This is a simple Flutter application that displays the current temperature of your location and allows you to search for the temperature of other cities.

## How to Run the Project

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    ```
    Replace `<repository-url>` with the URL of your repository.

2. **Open Android Studio**:
    - Launch Android Studio on your computer.

3. **Import the project**:
    - Go to `File` > `Open` and navigate to the location where you cloned the repository.
    - Select the project folder to open it.

4. **Build the APK**:
    - Open the terminal in Android Studio and run the following command:
    ```sh
    flutter build apk --split-per-abi
    ```
    This will build the APK files for different ABIs.

## Description of the APK File

1. **Download the APK file**:
    - Transfer the generated APK file to your Android device.

2. **Grant location permission**:
    - When you open the app for the first time, it will ask for location permission. Grant the permission to allow the app to access your current location.

3. **Current location temperature**:
    - The first screen of the app will display the temperature of your current location.

4. **Icons on the top right corner**:
    - There are two icons on the top right corner of the first screen.

5. **Search another city's temperature**:
    - The right top icon is for searching the temperature of another city. Tapping this icon will redirect you to the second page.

6. **Enter city and get weather**:
    - On the second page, enter the name of the city and click the button labeled "Get Weather". This will redirect you back to the first screen and display the temperature of the searched city.

7. **Reset to current location**:
    - The left top icon on the first screen is for resetting the location. Tapping this icon will reset the location and display the temperature of your current location again.
