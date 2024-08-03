# Medication-Advisor-using-conversational-AI-chat-GPT
Medication Advisor using conversational AI chat GPT
Medication Advisor is a web application that provides medication advice based on user input about their symptoms. This application leverages the OpenAI API to generate medication recommendations and related advice.

Table of Contents
1 Features

2 Installation

3 Usage

4 Project Structure

5 API Key
 
6 Contributing

1 Features
>Symptom Input: Users can input their symptoms to receive medication advice.
Medication and Advice Output: The application displays medication recommendations and additional advice based on the input symptoms.

>Image Generation: Generates relevant images based on the medication advice.
Responsive Design: The UI is designed to be user-friendly and responsive across different devices.

2 Installation
> Clone the Repository:
git clone https://github.com/your-username/medication-advisor.git
cd medication-advisor

> Install Dependencies:
This project does not require any backend dependencies. Ensure you have an internet connection to fetch the OpenAI API.



3Usage

> Open the HTML File:
Open index.html in your web browser.

> Input Symptoms:
Enter your symptoms in the provided textarea and click the "Get Medication Advice" button.

 >View Recommendations:
The application will display the medication recommendations and advice. An image relevant to the medication will also be generated.

4 Project Structure

medication-advisor/
├── index.html
├── index.css
└── index.js


>index.html: The main HTML file that defines the structure of the web application.
>index.css: The CSS file for styling the web application.
>index.js: The JavaScript file that contains the logic for fetching medication advice and generating images.

5 API Key
To use this application, you need an OpenAI API key. Replace the placeholder API key in index.js with your own API key.

const apiKey = "your-openai-api-key";

6 Contributing

Contributions are welcome! Please fork this repository and submit pull requests with any improvements or bug fixes.
