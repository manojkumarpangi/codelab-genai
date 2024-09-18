# **codelab-genai**

This project leverages **Google's Vertex AI** to generate text-based content dynamically based on user input. It uses an Express server to interact with Vertex AI and retrieve content, such as fun facts about a given animal, returning the result in HTML format.

I participated in a workshop hosted by Google Cloud, which focused on the capabilities of Vertex AI. Inspired by the insights gained from this workshop, I developed this project. It showcases how machine learning models, particularly Vertex AI's gemini-1.5-flash model, can be utilized to generate dynamic and engaging text responses based on user input. This project highlights the practical applications of natural language processing by leveraging the advanced capabilities of the Gemini-1.5-flash model to interact with and respond to various prompts.

## **Features**
- **Text Generation**: Uses Vertex AI to generate content based on a provided prompt.
- **Google Cloud Integration**: Seamlessly integrates with Google Cloud’s Vertex AI.
- **Dynamic Responses**: Enter an animal's name as a query parameter, and the app will return 10 fun facts about that animal in HTML format.

## **Getting Started**

### **Prerequisites**
- [Google Cloud Platform Account](https://cloud.google.com/) (with access to Vertex AI)
- Node.js 14.x or later
- `gcloud` SDK configured
- Required Node.js packages: `@google-cloud/vertexai`, `express`, `google-auth-library`

### **Setup and Installation**
1. **Clone the Repository**
   ```bash
   git clone https://github.com/manojkumarpangi/codelab-genai.git
   cd codelab-genai

2. **Install Dependencies**
   ```bash
   npm install
3. **Set up Google Cloud Authentication**
   ```bash
   gcloud auth application-default login
4. **Run the Application**
   ```bash
   npm start

## **Usage**
- After starting the app, open your browser and navigate to http://localhost:8080?animal=cat (or any animal name you choose).
- The app will return 10 fun facts about the animal in HTML format.
## **API Endpoints**
### **GET /**
- Description: Generates fun facts about the provided animal.
- Query Parameter: animal (optional) - Name of the animal for which to generate facts (default: dog).
- Response: Returns an HTML string with 10 fun facts about the animal.

  Example:
  ```bash
  GET http://localhost:8080?animal=cat

## **Acknowledgments**
- Google Cloud Vertex AI
- Open-source libraries and community
  
