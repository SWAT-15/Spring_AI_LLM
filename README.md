# Spring AI LLM Application

A full-stack AI application built using **Spring Boot, Spring AI, and OpenAI APIs** that allows users to interact with a Large Language Model for **AI chat, image generation, and recipe generation** through simple prompt-based requests.

This project demonstrates how modern backend frameworks can integrate **LLM-powered capabilities** into real applications using REST APIs and structured prompt handling.

The backend is developed using **Spring Boot**, where REST controllers accept user prompts and route them through service layers that interact with the **OpenAI models via Spring AI**. The application supports three core features:

• **AI Chat Assistant** – users can send prompts and receive conversational responses from the LLM.  
• **Image Generation** – generates images based on text prompts using OpenAI image models.  
• **Recipe Generator** – dynamically creates cooking recipes from user-provided ingredients or dish ideas.

The system follows a clean backend architecture where requests flow from **REST Controllers → Service Layer → Spring AI → OpenAI Models → Response returned to client**.

## Tech Stack

- Java  
- Spring Boot  
- Spring AI  
- OpenAI API  
- REST APIs  
- Maven  
- Git / GitHub  

## Running the Project

• Clone the repository:
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git

• Navigate to the project directory:    cd project-folder

• Add your OpenAI API key in `application.properties`:    openai.api.key=YOUR_API_KEY

• Run the application:    mvn spring-boot:run

•  the server will start on:

http://localhost:8080

This project demonstrates how **AI capabilities such as conversational agents, generative image models, and structured content generation can be integrated into backend systems using Spring Boot and LLM APIs**, enabling developers to build intelligent applications powered by modern generative AI.

