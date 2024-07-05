# Dyslexia-Friendly Content Generation Tool
## Project Overview
This project assists individuals with dyslexia by transforming standard text into a more readable format tailored to varying levels of dyslexia severity: High, Medium, and Low. The tool leverages Google's Generative AI (gemini-pro) to generate customized outputs, enhancing readability and comprehension for users. Additionally, it fetches relevant images to complement the content, providing a richer user experience.

## Key Features
### User Input
#### Text Entry: Users can input any text they wish to convert into a dyslexia-friendly format.
#### Dyslexia Level Selection: Users can specify the severity level of dyslexia (High, Medium, Low), influencing the complexity of the modifications made by the AI.
### AI-Powered Content Generation
#### Custom Outputs: The core functionality is powered by Google's gemini-pro model, which generates a modified version of the input text based on the selected dyslexia level.
#### Expert Guidance: The model acts as a dyslexia expert, ensuring that the output is appropriately adjusted for the user’s needs.
#### Error Handling: The function includes robust error handling, providing user-friendly messages if issues arise during content generation.
### Dyslexia-Friendly Font
#### Readability Enhancement: The tool displays the modified text using the "OpenDyslexic" font, which is specifically designed to improve readability for individuals with dyslexia.
### Randomization
#### Input Text Variability: The tool can randomly select from a list of predefined input texts, adding variability to the content generation process.
#### Dyslexia Level Selection: The dyslexia level can also be randomly selected to test the tool under different conditions.
### Image Generation
#### Relevant Images: The tool uses the Unsplash API to fetch relevant images based on the input text, enhancing the visual appeal and understanding of the content.
### Google Sheets Integration
#### Data Storage: The project uses the gspread library to save user inputs, AI-generated outputs, and relevant image URLs to a Google Sheet.
#### Tracking and Analysis: This feature enables users to track their interactions and corresponding results over time, supporting easy sharing and collaborative review of the generated content.
#### Flexible Management: The tool can either retrieve an existing worksheet or create a new one, ensuring flexibility in data management.
