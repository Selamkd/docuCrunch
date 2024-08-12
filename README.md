# Docucrunch (Document Summariser Application)

## Project overview 

DocuCrunch is a web app that enables users to upload PDF documents or paste raw text in order to receive a summarised version. 

The app leverages two AI models:

- A121: used for summarising articles
- Hugging Face model : used for summarising meeting minutes

## Project structure 
- **Front-end**:  Developed in React.
  
   Handles user interaction, PDF upload, and displays summarised text.
     
- **Back-end**: Developed in Spring Boot and Python.
  
     Provides REST API endpoints for text extraction and summarisation.
  
     Makes API calls to the AI models (A121 and Hugging Face)

 ## Setup instructions

  ### Requirements 
  - Node.js
  - Java11+
  - Maven

## Front-end setup 
1. Clone the repository:

   `https://github.com/Selamkd/docuCrunch.git`
2. Change directory to docucrunch-front-end:

   `cd front-end/docucrunch-front-end`
3. Run the application:
 
   `npm run dev`
 ## Back-end setup 


1. Change directory to DocuCrunchBackEnd:

   `cd back-end/DocuCrunchBackEnd`
2. Build the project:
 
   `mvn clean install`
3. Run the application:
   
   `mvn spring-boot:run`
   
 
