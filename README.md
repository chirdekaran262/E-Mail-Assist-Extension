# MailAssist: AI-Powered Email Reply Generator

MailAssist is a Chrome extension that integrates seamlessly with Gmail to provide AI-powered email reply generation. With a Spring Boot backend and Gemini API integration, MailAssist ensures intelligent, context-aware email replies to save time and boost productivity.

---

## 🚀 Features

- **AI-Powered Replies**: Generate professional, context-aware email replies using the Gemini AI API.
- **Gmail Integration**: Automatically detects Gmail's compose window and adds an "AI Email Writer" button.
- **Backend Integration**: Built with Spring Boot for efficient handling of AI requests.
- **User-Friendly**: Minimalistic design with a focus on usability.

---

## 🛠 Installation

### Backend Setup

1. Clone the backend repository:
   ```bash
   git clone https://github.com/chirdekaran262/E-Mail-Assist-Extension.git
   cd email-writer-sb
   ```
2. Build and run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```
3. Ensure the backend is running on `http://localhost:8081`.

### Chrome Extension Setup

1. Clone or download this repository (frontend).
2. Open Chrome and navigate to `chrome://extensions`.
3. Enable **Developer mode** (top-right corner).
4. Click **Load unpacked** and select the extension's folder.
5. Open Gmail to start using MailAssist!

---

## 📄 Usage

1. Open Gmail and click "Compose" to start a new email.
2. Find the **"AI Email Writer"** button in the compose window.
3. Click the button to generate a reply:
   - The email content is sent to the backend.
   - Gemini API processes the content to generate a reply.
   - The AI-generated response is displayed in the compose window.

---

## 📂 File Structure

### Frontend

- **`manifest.json`**: Chrome extension metadata and permissions.
- **`content.js`**: Logic for injecting the "AI Email Writer" button into Gmail.
- **`content.css`**: Styling for the extension's UI elements.
- **`icons/`**: Icons for branding the extension.

### Backend

- **Spring Boot Application**: Provides endpoints for handling AI requests.
- **Gemini API Integration**: Connects with the AI API for reply generation.

---

## 🌟 Technologies Used

- **Frontend**: Chrome Extension (Manifest V3), JavaScript, CSS.
- **Backend**: Spring Boot, Java.
- **AI Integration**: Gemini API.

---

## 🔧 Configuration

### Backend (Spring Boot)

1. Add your Gemini API key in `application.properties`:
   ```properties
   gemini.api.key=your-api-key
   gemini.api.url=https://gemini-api-endpoint
   ```
2. Modify any other configurations as needed.

---

## 🔮 Future Enhancements

- Advanced tone customization for replies.
- Support for multiple languages.
- Integration with additional email platforms.

---

## 📝 License

This project is licensed under the MIT License. Feel free to use and modify it.

---

## 📧 Contact

For support or inquiries, contact `chirdekaran262@gmail.com`.
