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
   
 
