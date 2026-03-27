# <p align="center">Sahwira Inzwa</p>
<p align="center">
  <img src="https://github.com/marknature/Sahwira_Inwa/blob/main/sahwira%20inzwa%20logo.jpg" alt="sahwira inzwa logo" width="200"/>
</p>

<p align="center">
  <strong>Bridging the communication gap between deaf individuals and non-signers through AI-powered Shona translation.</strong>
</p>

## 🌟 Project Overview
**Sahwira Inzwa** is an AI-driven application designed to translate sign language gestures into **audible Shona speech** in real time. By leveraging computer vision and natural language processing, the system enables inclusive, natural communication, reducing the high costs and limited availability of human interpreters in Zimbabwe.

[Watch demo](project.mp4)

## 🚀 Key Features
*   **Real-time Gesture Recognition:** Uses computer vision to detect and interpret hand movements instantly.
*   **Localized Audio Output:** Specifically tailored to produce natural Shona voice output, a language often overlooked by global English-centric technologies.
*   **Hand Landmark Tracking:** Utilizes **Google MediaPipe** to track 21 specific hand joints and fingertips for high precision.
*   **Sentence Logic:** Includes intelligent processing that adds characters to a sentence only when a gesture is held steadily for 2 seconds, with support for spaces and deletions.
*   **Intuitive UI:** Designed with accessibility in mind, featuring a large camera preview and simple playback controls.

## 🛠️ Tech Stack
*   **Artificial Intelligence:** Scikit-learn (Random Forest Classifier), TensorFlow/PyTorch.
*   **Computer Vision:** MediaPipe, OpenCV.
*   **Backend:** Python, Flask.
*   **Frontend:** Next.js (App Router), React, TypeScript, Tailwind CSS.
*   **Speech Technology:** Google Cloud Speech API, Shona Text-to-Speech (TTS), gTTS.

## 📂 System Architecture
The system follows a streamlined pipeline to ensure low latency (<2 seconds):
1.  **Input:** Live video feed captured via smartphone or laptop camera.
2.  **Detection:** MediaPipe identifies 21 landmarks and extracts a 42-dimension feature vector.
3.  **Classification:** A trained ML model predicts the gesture meaning.
4.  **Translation:** Text is mapped to its Shona equivalent.
5.  **Synthesis:** A TTS engine generates the audible Shona speech.

## 👥 The Development Team
This project was developed by a multi-disciplinary team at **Africa University**:
*   **Project Manager:** Nyasha Chibwe
*   **AI Engineer:** Tapiwa Mukoyi
*   **Systems Architect:** Danielle Kangausaru
*   **Systems Integration Specialist:** Andy Mutswatiwa
*   **Applied Scientist & Documentation:** Mark Chindudzi
*   **Systems Integration & Test Engineer:** Ruvarashe Celeste Motsi
*   **Technical Writer & Lead Researcher:** Makomborero Gwanzura
*   **Embedded Systems Engineer:** Taropafadzwa Kaseke
*   **Additional Contributors:** Nyasha Chinganyama, Mudiwa Tumbare, Kudzai Ndanga, Craig Mugova, Jenovic Nyembo, Angelina Chicupe Satchixinga, and Emmanuel.

## 📈 Future Roadmap
*   **Multi-language Support:** Expand beyond Shona to include Ndebele and other local languages.
*   **Reverse Translation:** Develop speech-to-sign functionality for full two-way communication.
*   **Offline Mode:** Enable AI model support for areas with limited internet connectivity.
*   **Vocabulary Expansion:** Move from basic alphabetic signs to full sign language vocabulary.

## 📜 Acknowledgements
Special thanks to **Africa University** and the local deaf communities who participated in user testing to confirm the system's effectiveness in reducing communication barriers.
