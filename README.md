# SignFusion: AI-Powered Multi-Modal Assistive System for Deaf, Mute and Blind Individuals
<p align="center">
  <img src="https://blogger.googleusercontent.com/img/a/AVvXsEhmrqv7GnqSPqSEdB2-jfhhsEo49RbHFKg_lWdkdcEDlJgN94Rf50Bsc-oU71cMlozHvNK9TyHY7wRKvx_0UdUuFILWxOtiRZZyV7LdPs_SxYirpjaddO2QDUd4lg7SS9JTEgwgmSksib0mY9u14RJ2B4HFX1sqkA4hOhhePe9owdGxCqAHVcDnNrFWJa8=w400-h204" alt="Project Preview" />
</p>

## Overview
SignFusion is a revolutionary AI-powered assistive technology designed to bridge communication gaps for deaf, mute, and blind individuals. This comprehensive system integrates real-time sign language recognition, AI-generated sign avatars, speech-to-text conversion, and smart Braille translation into a unified accessibility platform.

## Key Features

### For Deaf & Mute Users
- **Real-Time Sign Language to Text & Speech Conversion**
  - Uses computer vision to detect hand gestures
  - Converts sign language into spoken words and text in real-time
- **Text & Speech to AI-Generated Sign Language Avatar**
  - Creates human-like avatars that animate sign language
  - Works across digital platforms (YouTube, Netflix, social media)
- **Media Access On All Websites**
  - Facilitates group conversations in meetings and classrooms
  - Detect the presence of subtitles or closed captions (CC)
  - Extract the text from subtitles in real time
  - Translate the text into sign language using NLP
  - Display a 3D avatar on the screen that performs the sign language gestures, synced with the video playback

- **Multi-Person Communication Mode**
  - Facilitates group conversations in meetings and classrooms
- **Global Sign Language Translator**
  - Converts between ISL, ASL, BSL and other sign languages

### For Blind Users
- **AI-Powered Smart Braille Device**
  - Converts speech, text, and images into real-time Braille output
  - Features emotion detection through haptic feedback
  - Provides environmental sound awareness
- **AI-Based Image-to-Braille Conversion**
  - Describes visual content through tactile feedback
- **Navigation Assistance**
  - Uses LiDAR and AI for obstacle detection

## Technical Architecture

### Software Stack
- **Frontend**: React.js (Web), React Native (Mobile)
- **Backend**: Node.js with Express.js
- **Database**: MongoDB + Firebase
- **AI/ML**: TensorFlow.js, Python (for backend models)
- **Sign Recognition**: OpenCV + MediaPipe
- **APIs**: WebRTC, Google Speech-to-Text, Deep Learning NLP models


## Repository Structure

```
SignFusion/
├── backend/                  # Node.js server and API endpoints
│   ├── controllers/          # Business logic
│   ├── models/               # Database models
│   ├── routes/               # API routes
│   └── services/             # External service integrations
│
├── frontend/                 # Web application
│   ├── public/               # Static assets
│   └── src/                  # React components
│       ├── components/       # Reusable UI components
│       ├── pages/            # Application pages
│       ├── utils/            # Helper functions
│       └── App.js           # Main application component
│
├── mobile/                   # React Native application
│   ├── android/              # Android-specific code
│   ├── ios/                  # iOS-specific code
│   └── src/                  # Shared application code
│
├── ai-models/                # Trained AI models
│   ├── sign-language/        # Sign recognition models
│   ├── speech-processing/    # Speech-to-text models
│   └── braille-translation/  # Text-to-Braille models
│
├── hardware/                 # Braille device firmware
│   ├── firmware/             # Embedded code
│   └── schematics/           # Hardware designs
│
├── browser-extension/        # Chrome/Firefox extension
│   ├── content-scripts/      # Scripts injected into web pages
│   └── background/           # Extension service worker
│
├── docs/                     # Documentation
│   ├── architecture.md       # System architecture
│   ├── api-reference.md      # API documentation
│   └── user-guides/          # User documentation
│
└── tests/                    # Test suites
    ├── unit/                 # Unit tests
    └── integration/          # Integration tests
```

## Getting Started

### Prerequisites
- Node.js (v16+)
- Python (v3.8+)
- Firebase account
- Google Cloud credentials for speech APIs

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SignFusion.git
   cd SignFusion
   ```

2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

4. Set up environment variables (create `.env` files in each directory as needed)

5. Start the development servers:
   ```bash
   # In backend directory
   npm run dev
   
   # In frontend directory
   npm start
   ```

## Development Roadmap

### Phase 1: Core Functionality (Months 1-6)
- [ ] Complete sign language recognition models
- [ ] Implement basic AI avatar system
- [ ] Develop speech-to-text/text-to-speech integration
- [ ] Create initial browser extension prototype

### Phase 2:System Optimization (Months 7-12)
- [ ] Improve AI model accuracy
- [ ] Enhance avatar expressiveness
- [ ] Optimize for low-latency performance
- [ ] Conduct user testing with target communities

### Phase 3: Ongoing


## Contributing
We welcome contributions from the community! 

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Team
- Nitish Kumar (AI Specialist)
- Himanshu Kumar (Tech Lead)
- Jyoti Mishra (Frontend Developer)
- Harsh Gupta (AI Specialist)
- Dr. Saurabh Sharma (Advisor)
- Ms. Mandeep Kaur (Advisor)


This repository represents an ambitious project to create truly inclusive communication technology. We believe SignFusion has the potential to transform lives by breaking down barriers for individuals with hearing, speech, and visual impairments.
