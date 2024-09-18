# **codelab-genai**

This project leverages **Google's Vertex AI** to generate text-based content dynamically based on user input. It uses an Express server to interact with Vertex AI and retrieve content, such as fun facts about a given animal, returning the result in HTML format.

I attended a workshop organized by **Google Cloud** where they discussed the usage of **Vertex AI**, and that is where I got the inspiration to create this project. This project demonstrates the power of machine learning models and their ability to interact with natural language, generating dynamic responses based on user input.

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
  
