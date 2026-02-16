# content-creation-automations
This repo contains two workflows: one for creating video using reddit stories, the other is for clipping long form content to shorts.. both use completely free tools

> 💝 **Enjoying this free resource?** If you find this collection valuable, consider [buying me a coffee](https://ko-fi.com/nodeshare) to support continued development and updates!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W51MGK1Q)

---

Two powerful automation workflows for content creators who want to produce engaging videos without monthly subscription fees. Everything runs locally or uses free services with generous limits.

## Overview

After spending countless hours hitting paywalls on automation tools, I built these workflows from scratch and I'm sharing them completely free. No contributions, modifications, or redistribution allowed—these are provided as-is for personal use.

---

## 📹 Workflow #1: Story-To-Video Pipeline

Transform Reddit stories into polished, ready-to-upload videos automatically.

### How It Works

**Stage 1: Story Collection & Processing**
- Fetches Reddit stories and filters by upvotes
- Saves to Google Sheets for tracking
- Processes each story through Groq LLMs for quality validation
- Converts stories into optimized scripts using Gemini (YouTube/TikTok format)

**Stage 2: Scene Generation**
- Intelligently splits stories into logical scenes
- Generates background images for each scene using Cloudflare Flux Schnell (loose rate limits)
- Creates natural-sounding narration with locally hosted Kokoro TTS

**Stage 3: Video Assembly**
- Uses NCA-toolkit to merge images and voiceovers
- Applies professional video effects
- Concatenates all scenes into final video
- Supports scene regeneration and sound effect integration

**Stage 4: Multi-Platform Optimization**
- Automatically generates metadata for 7 social platforms
- Upload remains manual (auto-upload services require payment)

### See It In Action

Check out videos created with this workflow: [YouTube Channel](https://youtube.com/@theaivoice-m7k?si=Pcmm_KmoF71aaLbN)

---

## Workflow #2: Video Clipping Pipeline

Automatically extract viral moments from long-form content and turn them into engaging shorts.

### How It Works

**Stage 1: Video Acquisition**
- Submit YouTube URL via Telegram bot
- Automatically downloads video
- Splits into 5-minute segments for optimal processing

**Stage 2: Viral Moment Detection**
- Transcribes audio using Groq Whisper API
- Analyzes content with Gemini to identify high-engagement moments
- Generates precise timestamps for viral clips

**Stage 3: Clip Production**
- Uses NCA-toolkit to extract and process clips
- Adds professional captions automatically
- Delivers finished clips directly via Telegram

---

## Key Features

- **100% Free to Run**: No subscription fees or hidden costs
- **Local Processing**: Most operations run on your machine
- **Generous API Limits**: Free-tier services with ample quotas
- **Full Documentation**: Complete setup guides and customization instructions included
- **Production Ready**: These workflows power real, active content channels

---

## Download & Setup

All workflow files are included in this repository.
Full documentation, setup guides, and customization tips are included in the package.

---

## Why I Built This

Every automation tool I found had a paywall. I spent months building these workflows, and I believe creators should have access to powerful tools without breaking the bank. These workflows are my contribution to the content creation community.

---

## Support & Custom Work

If these workflows helped you start or grow your channel, tips and contributions help me continue building and sharing free tools for the community.

**Need something custom?** I'm available for tailored automation setups specific to your channel's needs.

**Contact:** [thefreeaiautomationhelp@gmail.com](mailto:thefreeaiautomationhelp@gmail.com)

---

## Technical Stack

- **LLMs**: Groq (quality checks), Gemini (script generation & analysis)
- **TTS**: Kokoro (locally hosted)
- **Image Generation**: Cloudflare Flux Schnell
- **Video Processing**: NCA-toolkit
- **Transcription**: Groq Whisper API
- **Storage**: Google Sheets
- **Delivery**: Telegram Bot
 
![](https://komarev.com/ghpvc/?djulTrb)
