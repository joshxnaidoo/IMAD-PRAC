# Weather App README

## Objective

This weather app was developed as part of a team effort for a local weather organization. The objective was to design an application that provides users with relevant weather information for the week, along with detailed insights for each day. The app needed to be user-friendly, visually appealing, and efficient in gathering and presenting weather data.

## Requirements

The organization provided the following requirements for the application:

1. **Splash Screen:**
   - Display developer's name, surname, and student number.
   - Include a logo.
   - Provide an option to navigate to the main screen.

2. **Main Screen:**
   - Display relevant information about the weekly weather.
   - Keep the interface simple yet informative.
   - Allow users to insert or clear data as needed.

3. **Summary Screen:**
   - Summarize the data collected from the main screen.
   - Present a detailed summary of the weekly weather data.
   - Provide a technical view with progress circles and percentages for temperature averages.
   - Include a calendar and clock for additional information.

## Approach

### Splash Screen:
I took a unique approach to the splash screen, aiming for a classy and eye-catching design. Utilizing colors associated with different weather conditions, such as blue for rainy weather and yellow for sunny days, I created a visually appealing yet straightforward interface.

### Main Screen:
The main screen displays the days of the week along with their respective minimum and maximum temperatures. To maintain simplicity, I included a button for easy navigation to the summary screen.

### Summary Screen:
For the final screen, I opted for a more technical view, focusing on presenting the data in a concise and analytical manner. I used progress circles to represent temperature averages and included a calendar and clock for additional context.

## Conclusion

The weather app meets the organization's requirements by providing users with a seamless experience for accessing and understanding weekly weather data. With its unique design elements and user-friendly interface, the app offers a valuable tool for staying informed about weather forecasts.

Pseudocode:

# Pseudocode for Weather App

# Pseudocode for Weather App

## Splash Screen Logic:
1. Display splash screen with developer's information and organization's logo.
2. Wait for user interaction.
3. If user taps on the screen, navigate to the main screen.

## Main Screen Logic:
1. Initialize weekly weather data.
2. Display main screen with days of the week and their respective minimum and maximum temperatures.
3. Provide options for user interaction:
   - Insert data: Allow users to input or modify weather information.
   - Clear data: Allow users to reset all weather data to default.
   - View details: Allow users to navigate to the summary screen.

## Summary Screen Logic:
1. Calculate average temperatures for the week based on the collected data.
2. Present a detailed summary of the weekly weather conditions:
   - Display average temperatures.
   - Provide breakdowns of weather conditions (e.g., overcast, sunny, rainy).
   - Show additional contextual information such as the calendar and current time.

## Code Implementation:

### Splash Screen (WeatherActivity):
1. Display splash screen layout with developer's information and organization's logo.
2. Wait for user interaction.
3. If user taps on the screen, navigate to the main screen.

### Main Screen (MainActivity2):
1. Initialize weekly weather data.
2. Display main screen layout with days of the week and their respective minimum and maximum temperatures.
3. Handle user interaction:
   - Insert data: Allow users to input or modify weather information.
   - Clear data: Reset all weather data to default.
   - View details: Navigate to the summary screen.

### Summary Screen (MainActivity3):
1. Calculate average temperatures for the week based on the collected data.
2. Present summary screen layout with:
   - Average temperatures displayed prominently.
   - Breakdowns of weather conditions.
   - Additional contextual information such as the calendar and current time.

### Model (WeeklyWeather):
1. Define a data structure to represent weekly weather information:
   - Properties: Day of the week, minimum temperature, maximum temperature.
   - Methods: Constructor to initialize data.

### Layouts:
1. Define XML layouts for each screen:
   - activity_welcome.xml (Splash Screen)
   - activity_main.xml (Main Screen)
   - activity_details.xml (Summary Screen)

screenshots of each screen and error messages:

<img width="590" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/a1f4518f-0b37-40eb-8608-5234a0a9c86c">
<img width="590" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/a1f4518f-0b37-40eb-8608-5234a0a9c86c">

<img width="587" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/03d3c89b-fc05-44fe-9327-52eb958f4e82">
<img width="587" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/03d3c89b-fc05-44fe-9327-52eb958f4e82">
<img width="591" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/00c0e8a7-77ff-4c0d-9dc3-b7cef494c1a2">
<img width="588" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/1bad0735-e3c7-4674-b58d-88d98266a226">
<img width="590" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/0b21b2a2-9df8-41b3-9be2-3b1e23fa2a94">

now for their activity xml:

<img width="556" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/0aa9fb3e-c8eb-4d69-abf7-f26fa059542b">
\<img width="571" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/70954067-72e7-446e-8cd4-0c168393d65f">
<img width="559" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/df407af2-7639-4591-a588-1cc0e4bb08a3">
<img width="580" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/96023e7d-d2f1-4006-82c4-980ca10ed3c1">
<img width="580" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/96023e7d-d2f1-4006-82c4-980ca10ed3c1">

<img width="559" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/df407af2-7639-4591-a588-1cc0e4bb08a3">

<img width="571" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/70954067-72e7-446e-8cd4-0c168393d65f">

<img width="556" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/0aa9fb3e-c8eb-4d69-abf7-f26fa059542b">

<img width="590" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/0b21b2a2-9df8-41b3-9be2-3b1e23fa2a94">

<img width="588" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/1bad0735-e3c7-4674-b58d-88d98266a226">

<img width="591" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/00c0e8a7-77ff-4c0d-9dc3-b7cef494c1a2">
<img width="571" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/950092af-72eb-4a07-ad89-3ab28d7c47cd">
<img width="557" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/cd9c5e63-2c12-4d76-a8af-acbfc89f62a6">
<img width="552" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/a1a09827-1b0c-4acd-a58f-d051774f2dea">
<img width="560" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/4d080482-6263-42d1-8a99-f54c5f94991f">
<img width="583" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/bc490be7-8091-4fff-a607-9e553b509a17">
<img width="572" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/15cd4bbc-6afd-4dc2-8f0a-9b4f787f64a1">
<img width="572" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/15cd4bbc-6afd-4dc2-8f0a-9b4f787f64a1">

<img width="583" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/bc490be7-8091-4fff-a607-9e553b509a17">

<img width="560" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/4d080482-6263-42d1-8a99-f54c5f94991f">

<img width="552" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/a1a09827-1b0c-4acd-a58f-d051774f2dea">

<img width="557" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/cd9c5e63-2c12-4d76-a8af-acbfc89f62a6">

<img width="571" alt="image" src="https://github.com/joshxnaidoo/IMAD-PRAC/assets/169088214/950092af-72eb-4a07-ad89-3ab28d7c47cd">
[Presentation.pdf](https://github.com/user-attachments/files/15766343/Presentation.pdf)
[Presentation.pdf](https://github.com/user-attachments/files/15766343/Presentation.pdf)

link for Github:https://github.com/joshxnaidoo/IMAD-PRAC/tree/main
adroid studio link: C:\Users\User\AndroidStudioProjects\weatherapp\app


