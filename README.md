# Weather App with genAI

This is a React-based weather application that provides users with information about the current weather in their location. It leverages the power of generative AI by using GPT-3.5 Turbo to enhance the user experience. Users can ask for advice on what to wear, and the app provides them with the temperature in Celsius, Fahrenheit, or Kelvin, depending on their region, along with a short description of what to wear based on the weather.


![Weather App](/imgs/im2.PNG)

## Features

- Get real-time weather information based on the user's location
- Utilize the OpenWeather API to fetch weather data
- Enhance user experience with generative AI using GPT-3.5 Turbo
- Provide temperature in Celsius, Fahrenheit, or Kelvin based on user preference
- Suggest appropriate clothing based on the weather conditions

![Weather App](/imgs/im1.PNG)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/weatherApp-with-genAI.git
    ```

2. Install the dependencies:

    ```bash
    cd weatherApp-with-genAI
    npm install
    ```

3. Set up the OpenWeather API:

    - Sign up for an account on [OpenWeather](https://openweathermap.org/) and obtain an API key.
    - Create a `.env` file in the root directory of the project.
    - Add the following line to the `.env` file, replacing `<YOUR_API_KEY>` with your actual API key:
      ```bash
      VITE_OWM=<YOUR_API_KEY>
      ```
    - Sign up for an account on [OpenAI](https://openai.com/) and obtain an API key.
    - Create another `.env` file in the root directory of the project.
    - Add the following line to the `.env` file, replacing `<YOUR_OPENAI_API_KEY>` with your actual API key:
      ```bash
      VITE_OPENAI=<YOUR_OPENAI_API_KEY>
      ```

4. Start the application:

    ```bash
        npm run dev 
    ```

5. Open your browser and navigate to [http://localhost:5175/](http://localhost:5175/) to view the app.

## Acknowledgements

This application was built based on the LinkedIn course: [Build a JavaScript AI App with React and the OpenAI API](https://www.linkedin.com/learning/build-a-javascript-ai-app-with-react-and-the-openai-api).

## License

This project is licensed under the [MIT License](LICENSE).