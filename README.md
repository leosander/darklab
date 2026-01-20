# 🚀 DarkLAB - AI Automation Platform

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
![License](https://img.shields.io/badge/license-Proprietary-red.svg)

**Automated AI Content Generation using Claude AI and Google Labs**

[📥 Download for Windows](#-download) • [💬 Discord Community](https://discord.gg/munMZEBMw5)

[English](#-user-manual)

</div>

---

## 📥 Download

### Windows Installation

1. Download the latest release from the [Releases](../../releases) page
2. Extract the ZIP file to your desired location
3. Run `DarkLAB.exe`
4. Follow the setup instructions below

---

## ⚠️ Important Security Notice

This application is developed in Python. Since this is independent software without a Digital Signature, **Windows Defender or SmartScreen may mistakenly flag it as a potential threat**. This is a common **"False Positive"**.

### ✅ Safety Guarantee

This tool is **completely clean and safe**. If you scan it with specialized antivirus software such as Kaspersky, Bitdefender, or ESET, it will be recognized as **SAFE**.

**Please select "Run anyway" or add the file to your exception list to proceed.**

---

## 🎯 Introduction

**DarkLAB** is a powerful desktop automation platform that combines:

- 🤖 **Claude AI**: Intelligent prompt generation from audio or text
- 🎬 **Google Labs VEO3**: Automated video generation
- 🖼️ **Google Labs Imagen**: Automated image generation
- ⚡ **Batch Processing**: Process hundreds of prompts automatically
- 🔄 **Auto-Retry**: Intelligent error handling and automatic retry mechanisms
- 📊 **Real-time Progress**: Monitor automation progress in real-time

### System Requirements

- **OS**: Windows 10/11 (64-bit)
- **RAM**: 4GB minimum (8GB recommended)
- **Storage**: 1GB free space
- **Internet**: Stable connection required
- **Google Account**: Access to Google Labs (VEO3/Imagen)
- **Claude API Key**: Anthropic API key for prompt generation

---

## 🚀 Quick Start

### 1. Initial Setup

#### Login

1. Launch the application
2. Login with your account credentials
3. The main interface will load

#### Add Google Account

1. Go to **⚙️ Settings** tab
2. Navigate to **Google Accounts** section
3. Click **➕ Add Account**
4. Log in with your Google account in the browser window
5. The account will be saved automatically

**Account Requirements:**
- **For Images**: Regular Gmail account (free)
- **For Videos**: Gmail account with Google One Pro/Ultra plan required

#### Configure Claude API

1. Go to **⚙️ Settings** → **General Settings**
2. Enter your **Claude API Key** (from Anthropic)
3. Click **💾 Save**

#### General Settings

Configure in **⚙️ Settings** → **General Settings**:

| Option | Description | Recommended |
|--------|-------------|-------------|
| **Output Folder** | Save location for generated content | `./output` |
| **Max Threads** | Concurrent processing threads | 3-5 |
| **Retry Count** | Automatic retries on error | 2 |

---

## 📝 Prompts Automation

Generate AI prompts automatically from audio or text using Claude AI.

### Audio-to-Prompts

Convert audio narration into text prompts for video/image generation.

**Usage:**
1. Go to **✨ Prompts** tab
2. Select **Audio** mode
3. Upload your audio file (MP3, WAV, etc.)
4. Configure settings:
   - Language detection
   - Transcription model
5. Click **▶️ Generate Prompts**
6. Claude AI will process the audio and generate prompts

### Text-to-Prompts

Generate prompts from text input using Claude AI.

**Usage:**
1. Go to **✨ Prompts** tab
2. Select **Text** mode
3. Enter or paste your text content
4. Configure prompt generation settings
5. Click **▶️ Generate Prompts**
6. Review and edit generated prompts if needed

### Batch Processing

Process multiple audio files or text inputs:

1. Import multiple files/texts
2. Configure batch settings
3. Start automation
4. Monitor progress in real-time
5. All prompts saved automatically

---

## 🎬 Video Generation (Flow)

Automated video generation using Google Labs VEO3.

### Creating Video Automation

1. Go to **🎥 Flow** tab
2. Click **➕ New Automation**
3. Configure automation:

**Basic Settings:**
- **Name**: Automation name
- **Project Folder**: Where videos will be saved
- **Prompts**: Select prompts to use (from Prompts tab)

**Video Settings:**
- **Aspect Ratio**: 16:9 / 9:16 / 1:1
- **Resolution**: 720p / 1080p
- **Model**: VEO3 Fast / Standard
- **Outputs per Prompt**: 1-4 videos per prompt

**Advanced Settings:**
- **Threads**: Number of parallel videos (depends on account plan)
- **Min Wait Time**: Delay between prompts (seconds)
- **Max Wait Time**: Maximum delay (seconds)
- **Reference Images**: Optional reference images for video generation

4. Click **▶️ Start Automation**
5. Monitor progress in real-time

### Automation Management

**View Active Automations:**
- See all running automations
- Real-time progress updates
- Video count and status

**Automation Details:**
- View all prompts in automation
- See video status (pending, processing, completed, failed)
- Download completed videos
- Retry failed videos

**Status Types:**
- **Pending**: Waiting to be processed
- **Processing**: Currently generating
- **Completed**: Successfully generated
- **Failed**: Generation failed (can retry)

### Retry Failed Videos

1. Go to **🎥 Flow** tab
2. Select automation with failed videos
3. Click **🔄 Retry Failed**
4. Choose retry options:
   - Retry all failed videos
   - Retry selected videos only
5. Automation will retry with intelligent error handling

---

## 🖼️ Image Generation

Automated image generation using Google Labs Imagen.

### Creating Image Automation

1. Go to **🎥 Flow** tab
2. Click **➕ New Automation**
3. Select **Image Generation** mode
4. Configure automation:

**Image Settings:**
- **Model**: Imagen / Nano Banana
- **Aspect Ratio**: 1:1 / 16:9 / 9:16
- **Resolution**: 720p / 1080p
- **Outputs per Prompt**: 1-4 images per prompt
- **Reference Images**: Optional reference images

5. Click **▶️ Start Automation**
6. Monitor progress in real-time

### Image Automation Features

- **Batch Processing**: Process multiple prompts automatically
- **Reference Images**: Use up to 10 reference images (model dependent)
- **Auto-Retry**: Automatic retry on failures
- **Progress Tracking**: Real-time progress updates

---

## ⚙️ Settings

### Google Accounts

Manage Google accounts for content generation.

**Add Account:**
1. Click **➕ Add Account**
2. Browser window opens
3. Log in with Google account
4. Account saved automatically

**Account Management:**
- View all accounts
- See account status (Ready/Error)
- Edit account settings
- Delete accounts
- Configure proxy (optional)

### General Settings

**Output Configuration:**
- Default output folder
- File naming conventions
- Auto-organize by project

**Processing Settings:**
- Max concurrent threads
- Retry count
- Delay between requests
- Timeout settings

**API Configuration:**
- Claude API key
- API endpoint settings

---



## ❓ FAQ

### Q: How many videos/images can I generate?
**A:** Depends on your Google account plan:
- **Free accounts**: Limited by Google quota
- **Pro/Ultra accounts**: Higher limits, better for video generation

### Q: Can I use multiple Google accounts?
**A:** Yes! Add multiple accounts in Settings. The system will distribute work across accounts.

### Q: How long does video generation take?
**A:** Typically 2-5 minutes per video, depending on:
- Video resolution (720p faster than 1080p)
- Google Labs server load
- Your account plan

### Q: What file formats are supported?
**A:**
- **Videos**: MP4 (H.264)
- **Images**: JPG, PNG, WebP
- **Audio**: MP3, WAV, M4A (for prompt generation)

### Q: Can I pause/resume automations?
**A:** Currently, automations run until completion. You can cancel and restart if needed.

### Q: Where are files saved?
**A:** Files are saved in the project folder you specify when creating the automation. Default location is `./output/`

### Q: How does the retry system work?
**A:** The system automatically retries failed items up to 2 times. It waits for other items to finish before retrying to avoid conflicts.

### Q: Can I edit prompts after generation?
**A:** Yes! You can edit prompts in the Prompts tab before using them in automations.

---

## 💬 Community & Support

- **Discord**: [Join our community](https://discord.gg/munMZEBMw5)
- **Issues**: Report bugs and request features
- **Documentation**: Check the user manuals above

---

## 📝 License

This software is proprietary. All rights reserved.

---

## 🙏 Acknowledgments

- Anthropic for Claude AI
- Google Labs for VEO3 and Imagen APIs
- All contributors and beta testers

---

<div align="center">

**Made with ❤️ by the DarkLAB Team**

[⬆ Back to Top](#-darklab---ai-automation-platform)

</div>
