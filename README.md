PowerPoint Presentation Generator with GPT-3.5-turbo and DALL·E 3
This application generates PowerPoint presentations using OpenAI's GPT-3.5-turbo language model and DALL·E 3 image generation model. Users can input a topic and the number of slides they want, and the application will generate slide titles and content, along with relevant images, for the presentation.

Features
Topic Input: Users can enter the topic for the presentation.
Slide Number Input: Users can specify the number of slides they want in the presentation.
Presentation Generation: The application generates slide titles, content, and images based on the input topic and number of slides.
Download: Once the presentation is generated, users can download the PowerPoint file.
Prerequisites
Before running the application, make sure you have the following:

Python installed on your machine
OpenAI API key
Streamlit library
base64, pptx, requests, PIL, and dotenv Python libraries
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your_username/powerpoint-presentation-generator.git
Navigate to the project directory:

bash
Copy code
cd powerpoint-presentation-generator
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set up environment variables by creating a .env file in the project directory and adding the following:

plaintext
Copy code
OPENAI_API_KEY=your_openai_api_key
Usage
Run the application:

bash
Copy code
streamlit run main.py
Open your web browser and go to http://localhost:8501 to access the application.

Enter the topic for your presentation and the number of slides you want.

Click on the "Generate Presentation" button.

Once the presentation is generated, click on the download link to download the PowerPoint file.

License
This project is licensed under the MIT License.
