# PowerPoint Presentation Generator with GPT-3.5-turbo and DALL·E 3

<img src="presentation generator 1.png">

This application generates PowerPoint presentations using OpenAI's GPT-3.5-turbo language model and DALL·E 3 image generation model. Users can input a topic and the number of slides they want, and the application will generate slide titles and content, along with relevant images, for the presentation.

## Features

- **Topic Input**: Users can enter the topic for the presentation.
- **Slide Number Input**: Users can specify the number of slides they want in the presentation.
- **Presentation Generation**: The application generates slide titles, content, and images based on the input topic and number of slides.
- **Download**: Once the presentation is generated, users can download the PowerPoint file.

## Prerequisites

Before running the application, make sure you have the following:

- Python installed on your machine
- OpenAI API key
- Streamlit library
- base64, pptx, requests, PIL, and dotenv Python libraries

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/rizwaniscoder/powerpoint-presentation-generator.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd powerpoint-presentation-generator
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**

    Create a `.env` file in the project directory and add the following:

    ```plaintext
    OPENAI_API_KEY=your_openai_api_key
    ```

## Usage

1. **Run the application:**

    ```bash
    streamlit run main.py
    ```

2. **Access the application:**

    Open your web browser and go to `http://localhost:8501`.

3. **Enter the topic and number of slides:**

    - Enter the topic for your presentation in the provided text input.
    - Specify the number of slides you want using the number input field.

4. **Generate the presentation:**

    Click on the "Generate Presentation" button.

5. **Download the presentation:**

    Once the presentation is generated successfully, a download link will appear. Click on the link to download the PowerPoint file.

## License

This project is licensed under the [MIT License](LICENSE).
