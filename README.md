# Weather Application

This is a simple weather application that fetches and displays current weather information for a city using the OpenWeatherMap API. It allows users to enter the name of a city and get the weather details, such as temperature, humidity, weather description, and an emoji representing the weather condition.

## Features

- **City-based Weather Search:** Allows users to input any city name and retrieve weather details.
- **Temperature Display:** Shows the current temperature in Celsius.
- **Humidity Level:** Displays the current humidity of the city.
- **Weather Description:** Provides a brief description of the weather (e.g., clear sky, broken clouds, etc.).
- **Weather Emojis:** Shows an emoji that matches the current weather conditions (e.g., ☀️ for clear skies, 🌧️ for rain).

## Technologies Used

- **HTML5:** For the webpage structure.
- **CSS3:** For the styling and layout, including background design and responsive layout.
- **JavaScript (ES6):** To fetch weather data from the API and handle the display logic.
- **OpenWeatherMap API:** The API used to fetch real-time weather data based on the user's city input.

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/suhas-m-v/Weather-Application.git
    ```

2. Open the project directory:
    ```bash
    cd weather-app
    ```

3. Make sure you have a valid API key from OpenWeatherMap. Replace the `apikey` variable in the `weather.js` file with your key:
    ```javascript
    const apikey = "your_api_key_here";
    ```

4. Run the project:
   - Open the `index.html` file in a web browser to use the application.

## Usage

1. Enter the name of a city into the input field.
2. Click the **Get Weather** button.

The weather information will be displayed on the card below the form, including:
- The temperature in Celsius.
- The humidity percentage.
- A description of the weather (e.g., broken clouds, clear sky).
- A corresponding emoji to visually represent the weather.

## Code Explanation

- **HTML:** Contains the basic structure of the web application. The form allows users to input a city and fetch weather information.
- **CSS:** Styled with a background image and custom fonts to make the UI visually appealing. Cards are used to display the weather information.
- **JavaScript:**
    - Fetches weather data using the fetch API.
    - Processes the data and updates the UI dynamically.
    - Handles errors by showing appropriate messages.
    - Maps weather conditions to emojis for a more intuitive user experience.
When you open the application, the app will display something like:
![Weather-App Example](https://github.com/suhas-m-v/Weather-Application/blob/6420fc9baf7af7504919d489e438cda9164628e5/Screenshot%202024-10-08%20140456.png)

## Contribution

If you wish to contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new feature branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License.

## Contact Information

For any inquiries or feedback, feel free to contact:

- **Your Name:** [mvsuhas2004@gmail.com](mailto:YourEmail@example.com)  
- **GitHub:** [https://github.com/suhas-m-v](https://github.com/your-username)


