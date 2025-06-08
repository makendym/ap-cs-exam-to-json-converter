# AP CS A PDF to JSON Converter

A web-based tool that converts AP Computer Science A Free-Response Questions (FRQs) from PDF format to structured JSON. This tool is particularly useful for educators and students who want to programmatically analyze or work with AP CS A questions.

## Features

- Converts PDF FRQs to structured JSON format
- Supports multiple AI models (OpenAI, Anthropic, Groq, Custom)
- Handles various PDF formats and question structures
- Extracts questions sequentially (1-4)
- Maintains question integrity and formatting
- Real-time processing feedback
- Copy JSON output to clipboard

## Usage

1. Open `index.html` in a web browser
2. Upload an AP CS A FRQ PDF
3. Configure your preferred AI model and API key
4. Click "Convert PDF to JSON"
5. View and copy the structured JSON output

## JSON Structure

The converter produces JSON in the following format:

```json
{
  "question": {
    "id": "",
    "description": "",
    "classes": [
      {
        "class_name": "",
        "fields": [
          {
            "name": "",
            "type": "",
            "visibility": "",
            "description": ""
          }
        ],
        "methods": [
          {
            "name": "",
            "return_type": "",
            "parameters": [{"name": "", "type": ""}],
            "visibility": "",
            "description": "",
            "part": "",
            "precondition": "",
            "implementation_task": "",
            "detailed_description": ""
          }
        ],
        "notes": [""]
      }
    ],
    "examples": [
      {
        "part": "",
        "examples": [
          {
            "description": "",
            "initial_state": "",
            "method_call": "",
            "result": "",
            "explanation": ""
          }
        ]
      }
    ],
    "topics": ["",""],
    "difficulty": ""
  }
}
```

## Supported AI Models

- OpenAI
  - GPT-4o (Recommended)
  - GPT-4o Mini
  - GPT-4 Turbo
  - GPT-3.5 Turbo

- Anthropic
  - Claude 3.5 Sonnet
  - Claude 3.5 Haiku
  - Claude 3 Opus

- Groq
  - Llama 3.1 70B
  - Llama 3.1 8B
  - Mixtral 8x7B

- Custom API Support

## Technical Details

- Built with vanilla JavaScript
- Uses PDF.js for PDF text extraction
- Supports various PDF formats and structures
- Handles sequential question extraction
- Maintains question context and formatting

## Question Extraction

The tool uses pattern matching to identify questions based on:
- Question numbers (1-4)
- Common question starters:
  - "This question"
  - "The"
  - "A"
  - "An"
  - "In"
  - "For"
  - "Users"
  - "Many"
  - "Consider"

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License.

## Acknowledgments

- PDF.js for PDF text extraction
- Various AI model providers for their APIs
- AP Computer Science A community for feedback and testing 