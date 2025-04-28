# Aidoll

AIdoll is a Raspberry Pi-based interactive virtual idol system designed to engage users through real-time voice conversations, powered by AWS cloud services.

🏆 Winner of the AWS Generative AI Hackathon Taiwan 2025
![pic](https://github.com/user-attachments/assets/5e30b5fa-1f37-4f1d-96bd-ed2da4fe3bf5)



## 🚀 Features
- 🎤 Voice Interaction: Captures user speech and transcribes it to text using AWS Transcribe.
- 🧠 Contextual AI Responses: Generates personalized, context-aware replies through AWS Bedrock Claude 3 Sonnet.
- ☁️ Cloud Storage Integration: Utilizes AWS S3 for storing user audio recordings and captured images.
- 📱 Mobile App Connection: Supports real-time interaction via a custom-developed mobile app.
- 🔧 Hardware Integration: Integrates with Raspberry Pi modules for audio recording and image capturing.

## System architecture
The system integrates edge computing, cloud AI services, and mobile interfaces to enable real-time multimodal interactions:  
![cloud_arch](https://github.com/user-attachments/assets/2f0a038a-5548-4fc8-b61b-579effd13e76)  
![arch](https://github.com/user-attachments/assets/2ab860e7-5238-47db-9223-680c0f10be5a)  


## File Structure

```
.
├── AwsBot.py               # Main bot controller
├── main.py                 # Entry point for Pi system
├── awsServices/            # AWS service wrappers
│    ├── AudioTranscriber.py
│    ├── awsChatBot.py
│    └── awsImageToText.py
├── piModules/              # Raspberry Pi device modules
│    ├── Picam.py           # Camera control module
│    └── Recorder.py        # Microphone recording module
├── config/                 # System configuration
│    └── system_prompt.py
├── resources/can_audio/    # Pre-recorded audios
├── test/                   # Testing scripts
├── tmp/                    # Temporary storage
└── README.md
```

🌐 Technologies Used  
- AWS Bedrock (Claude 3 Sonnet)
- AWS Transcribe
- AWS S3
- Raspberry Pi 4
- Python 3
- Kivy Mobile App


👨‍💻 Contributors  
CHIN-WEI(William) Lin — Raspberry Pi system architecture, device control, cloud service integration, multimodal interaction  
LEE MAN-HO — Full-stack development, AWS integration
