🤖 AI Healthcare Chatbot with Vision and Voice
An intelligent AI-powered chatbot designed for healthcare applications. This chatbot supports voice input/output, image-based diagnosis (vision), and natural language communication, offering patients a seamless and interactive medical assistance experience.


🧠 Features

🔊 Voice Interaction: Understands and responds to voice queries using Speech Recognition and Text-to-Speech (TTS).

🖼️ Vision Module: Accepts medical image inputs for preliminary analysis and diagnosis.

💬 Text Chat: Natural language support using advanced LLMs.

🌐 Multimodal Interface: Combines voice, text, and images for comprehensive support.


🛠️ Gradio UI: Interactive user interface built with Gradio for easy accessibility.

| Component        | Tool/Library             | Purpose                                   |
| ---------------- | ------------------------ | ----------------------------------------- |
| LLM              | OpenAI / Groq API        | Natural Language Understanding & Response |
| TTS              | gTTS / ElevenLabs API    | Convert text responses to speech          |
| Voice Input      | SpeechRecognition, PyDub | Convert voice queries to text             |
| Vision Input     | OpenCV / Custom Model    | Image preprocessing and medical analysis  |
| UI               | Gradio                   | Interactive frontend                      |
| Env Config       | `.env`                   | Secure API key management                 |
| Audio Processing | `io`, `BytesIO`          | Buffering and stream handling             |
| Logging          | Python logging module    | Debugging and error tracking              |


📷 Sample Screenshot

![image](https://github.com/user-attachments/assets/570f3fe3-a3a5-4e51-ad32-be99f2813a87)

![image](https://github.com/user-attachments/assets/8c458687-399b-4d5f-81d2-66ae2b923a56)


📈 Use Cases

Preliminary symptom checking

Basic diagnosis via image (e.g., skin issues)

Voice-assisted patient interaction

Elderly-friendly virtual assistant


🔐 Security & Disclaimer

This project is for educational purposes only.

It is not a substitute for professional medical advice.

All data is processed locally or securely via APIs with encryption.
