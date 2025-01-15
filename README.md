# Virtual Guide Project

This repository showcases the conceptual design and workflow of the **Virtual Guide Project**, an AI-powered system that enables real-time, multilingual voice interaction and wheelchair control for individuals requiring assistive technologies. The project demonstrates advanced natural language processing (NLP) and speech technologies to create an interactive and accessible virtual assistant.

---

## Objective

The **Virtual Guide Project** aims to:
- Provide a multilingual virtual assistant for real-time interaction.
- Enable seamless communication in the user’s native language.
- Integrate with assistive technologies (e.g., wheelchair control) for enhanced functionality and independence.

---

## Key Features

1. **Multilingual Voice Interaction**:
   - Users can speak in their native language, and the system responds in the same language.
2. **Query Handling**:
   - The assistant processes user queries and provides spoken responses.
3. **Assistive Technology Integration**:
   - Generates motion commands for wheelchair navigation based on user instructions.
4. **Pipeline Architecture**:
   - Leverages multiple AI models from Speech Lab if IIT Madras (ASR, MT, TTS, and a Chatbot) for smooth interaction.

---

## Workflow and Architecture

### **System Overview**

1. **Voice Input**:
   - Users record their speech/query using a tablet's voice recorder.
2. **ASR/STT**: 
   - The Automatic Speech Recognition (ASR) model converts speech into text and extracts the intended query.
3. **Machine Translation (MT)**:
   - The text query is translated into English, as the chatbot is trained in English.
4. **Chatbot**:
   - Processes the input query and provides:
     - A spoken response for the user.
     - A command for wheelchair motion, if required.
5. **MT (Response)**:
   - The chatbot’s response is translated back into the user’s input language.
6. **TTS**:
   - Text-to-Speech (TTS) converts the translated text into speech, which is spoken back to the user.

---

### **System Flowchart**
Below is the visual representation of the system’s architecture:
![Flowchart](media/flowchart.png)

---

## Example Workflow

1. **User Query**:
   - The user asks a question in their native language (e.g., Tamil).
2. **Response and Action**:
   - The system:
     - Responds to the query in Tamil.
     - If instructed, sends a motion command to the wheelchair.

**Example**:
- User Query: "இருமலைக்கான மருந்து என்ன?" (*What is the medicine for a cold?*)
- System Response: Provides an answer in Tamil and moves the wheelchair, if instructed.

---

## Technologies Used 

- **ASR (Automatic Speech Recognition)**:
  - Converts user speech into text.
- **Machine Translation (MT)**:
  - Translates between the user's native language and English.
- **Chatbot**:
  - Processes queries and generates text responses.
- **TTS (Text-to-Speech)**:
  - Converts text responses into speech in the user’s native language.

---

## Visuals and Demonstrations

- **Example System Output**:
  - ![System Interaction](media/system-demo.png)
- **Integrated Wheelchair Motion**:
  - ![Wheelchair Motion](media/wheelchair-motion.png)

### **Video Demonstrations**
- [![Watch the Demo](media/video-thumbnail.png)]([https://www.youtube.com/your-video-link](https://youtu.be/Wlsy0SmorPY?si=hALWZ2q75e7fI-X_))
- ![LinkedIn](https://img.shields.io/badge/LinkedIn-Demo-blue?logo=linkedin) [Watch Demo]([https://www.linkedin.com/posts/your-post-link1](https://www.linkedin.com/feed/update/urn:li:activity:7084514250777399296?utm_source=share&utm_medium=member_android))

## In the Media

This project has received recognition in the media for its innovative approach:

- Featured in **Times of India**: [Read the Article]([https://www.timesofindia.com/your-article-link](https://m-timesofindia-com.cdn.ampproject.org/c/s/m.timesofindia.com/india/iit-madras-is-trying-to-create-more-ranchos/amp_articleshow/101325210.cms))


---

## Future Enhancements

- Expand language support for better inclusivity.
- Integrate advanced models for improved speech and language understanding.
- Develop a user-friendly interface for widespread adoption.

---

## Disclaimer

This repository highlights the workflow, visuals, and use cases of the **Virtual Guide Project**. The core models and APIs remain proprietary and are not included in this repository.
