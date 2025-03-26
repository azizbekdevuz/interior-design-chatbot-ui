# Interior Design FAQ and Survey Chatbot UI

A responsive and interactive chatbot UI implementation for interior design consultation, featuring both an FAQ system and a multi-step survey for collecting user preferences.

## 📌 Live Demo

[View Live Demo](https://your-vercel-deployment-url.vercel.app/)

![Chatbot Screenshot](screenshot.png)

## 🎯 Project Overview

This project is an implementation of a UI design for an interior design company's chatbot system with two main functionalities:

1. **FAQ Consultation Chatbot**: Provides service-related information through a guided Q&A format
2. **Interior Design Survey Chatbot**: Collects user preferences through a 4-step survey process

## ✨ Features

### General Features

- Responsive design that works on mobile, tablet, and desktop
- Smooth animations and transitions
- Accessible UI with proper contrast and focus states
- Clean, modern interface aligned with interior design aesthetics

### FAQ Chatbot

- Categorized FAQ system
- Conversational format with predefined Q&A
- Related question suggestions
- Easy navigation between questions
- Visual distinction between questions and answers

### Interior Design Survey

- 4-step survey process with progress indicator
- Multiple question types:
  - Image/card selection for style preferences
  - Multi-select options for furniture choices
  - Free text input for specific preferences
  - Date/time selection for appointment scheduling
- Form validation
- Personal information collection with privacy consent

## 🛠️ Technical Implementation

This project is built with:

- React
- TypeScript
- CSS (with custom properties for theming)

### Project Structure

```
src/
├── components/
│   ├── ChatbotApp.tsx    # Main chatbot component
│   └── ChatbotApp.css    # Chatbot styles
├── App.tsx               # Sample website with chatbot integration
├── App.css               # Website styles
└── index.tsx             # Entry point
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v14+)
- npm or yarn

### Installation

1. Clone this repository
```bash
git clone https://github.com/yourusername/interior-design-chatbot-ui.git
cd interior-design-chatbot-ui
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
npm start
# or
yarn start
```

4. Open your browser and visit `http://localhost:3000`

## 📱 Responsive Design

The chatbot UI is designed to work across all device sizes:

- **Mobile**: Full-screen interface with optimized touch interactions
- **Tablet**: Semi-expanded interface with adaptive layouts
- **Desktop**: Fixed-width container with hover effects

## 🎨 Customization

The design uses CSS custom properties (variables) for easy customization:

```css
:root {
  /* Primary Colors */
  --primary: #4FD1C5;
  --secondary: #4A5568;
  
  /* You can customize all colors and other design tokens */
}
```

## 🔄 Integration

### Adding to your website

The chatbot can be easily integrated into any React website:

```jsx
import ChatbotApp from './components/ChatbotApp';

function YourWebsite() {
  return (
    <div>
      {/* Your website content */}
      <ChatbotApp />
    </div>
  );
}
```

### Connecting to backend services

The chatbot is designed to be connected to backend services for:

- Fetching FAQ data
- Storing survey responses
- Managing appointment scheduling
- User data processing

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- Design inspiration from modern interior design websites
- Icons and visual elements from [placeholder for your sources]

---

This implementation is a demonstration of UI design capabilities for a job application project. The full requirements included creating a UI design for a consultation chatbot with FAQ functionality and a multi-step survey system for interior design preferences.
