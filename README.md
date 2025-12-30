# AP CS A PDF to JSON Converter

## Table of Contents
* [Description](#description)
* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [What I Learned](#what-i-learned)
* [Questions?](#questions)


## Description
A web-based tool that converts AP Computer Science A Free-Response Questions (FRQs) from PDF format to structured JSON. This tool is particularly useful for educators and students who want to programmatically analyze or work with AP CS A questions.

This application simplifies the extraction process, allowing users to focus on the content. It features:
* **Converts PDF FRQs:** Transforms PDF documents into structured JSON format.
* **Multi-Model Support:** Supports OpenAI, Anthropic, Groq, and Custom AI models.
* **Smart Extraction:** Handles multiple PDF formats, maintaining question integrity and formatting.
* **Real-time Feedback:** Provides immediate processing status and feedback.
* **Sequential Extraction:** Automatically identifies and extracts questions 1-4.


## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)

### 1. Open the Tool
Simply open the `index.html` file in your preferred web browser. No server installation is required for basic usage.

### 2. Upload and Configure
1. Upload an AP CS A FRQ PDF file.
2. Configure your preferred AI model and enter your API key.

### 3. Convert
Click "Convert PDF to JSON" to start the process. The tool will parse the PDF and extract the questions.

### 4. Output
View the structured JSON output on the screen and copy it to your clipboard for use in your applications.


## Contributing

Contributions are always accepted. Feel free to submit issues and enhancement requests!

---

## What I Learned
Creating this project provided valuable hands-on experience in:
- **Client-Side File Processing:** Handling file uploads and reading PDF data directly in the browser using JavaScript.
- **PDF Extraction:** Leveraging `PDF.js` to parse and extract structured text from complex PDF documents.
- **Regular Expressions:** Designing complex regex patterns to accurately identify and extract specific question formats and metadata.
- **Dynamic UI:** Building a responsive, real-time feedback interface without heavy frameworks (Vanilla JS).
- **JSON Data Structure:** Designing a robust schema for educational content to ensure interoperability.


## Questions?

![Developer Profile Picture](https://avatars.githubusercontent.com/u/60677452?s=460&v=4) 

For any questions, please contact me with the information below:

Email: <<Midouinmakendy@gmail.com>>