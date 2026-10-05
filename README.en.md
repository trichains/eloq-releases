<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/images/eloq-wordmark-dark.png">
  <img src="docs/images/eloq-wordmark-light.png" alt="eloQ" width="200">
</picture>

### Your real-time copilot for interviews and meetings

eloQ listens to the conversation, writes it down, notices the question and suggests an answer on a transparent window, right where you are already looking.

[![Latest release](https://img.shields.io/github/v/release/trichains/eloq-releases?style=flat-square&label=latest&color=7c5cf0)](https://github.com/trichains/eloq-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/trichains/eloq-releases/total?style=flat-square&color=7c5cf0)](https://github.com/trichains/eloq-releases/releases)
![Windows 10/11](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=flat-square&logo=windows&logoColor=white)
![macOS 13+ Apple Silicon](https://img.shields.io/badge/macOS-13%2B%20Apple%20Silicon-111111?style=flat-square&logo=apple&logoColor=white)
![Free demo](https://img.shields.io/badge/demo-free-2ea44f?style=flat-square)

**English** · [Português (Brasil)](README.md)

<br>

[**⬇ Download eloQ**](https://github.com/trichains/eloq-releases/releases/latest) &nbsp;·&nbsp; [Product page](https://trichains.dev/eloq) &nbsp;·&nbsp; [Mind map walkthrough](https://trichains.dev/eloq/mapa-mental.html)

<br>

<img src="docs/images/overlay-transparente.webp" alt="The eloQ window floating, transparent, above a video call" width="760">

<sub>The call in the background is an illustration. The eloQ window is real.</sub>

</div>

---

## What is eloQ?

You are in an interview, a sales call or an important meeting. Someone asks something you were not ready for. eloQ is the helper sitting next to you: it hears the question, checks what has been said so far (and the documents you gave it) and **suggests an answer in a small window on top of everything else**. You glance at it, keep eye contact and answer in your own words.

It is a desktop app for **Windows** and **macOS**, with the interface in **Brazilian Portuguese and English**.

## Highlights

| | |
|---|---|
| 🎙️ **Hears both sides** | Your microphone becomes **YOU** and the system audio becomes **THE OTHER PERSON**, transcribed separately, each with the provider you prefer. |
| 🧠 **Notices the question** | Questions are recognized by rules in Portuguese and English, not by AI: predictable, instant and free of API calls. |
| ✍️ **Suggests, does not invent** | Before asking the model, eloQ checks the question against the conversation and your documents. If it refers to something nobody established, it stays quiet instead of making things up. The **Context used** panel shows where each answer came from. |
| 🪟 **Transparent, always on top** | A frameless window you can fade from 15% to 100% opacity, to read comfortably or keep eye contact. |
| ⌨️ **You are in control** | The question appears and you press **SPACE** (or **Answer now**) to get the suggestion. Prefer hands-free? You can turn on automatic answers in the settings. |
| 🎧 **Record and review** | Record the meeting, then replay it with a waveform, playback speed and the transcript synced to the audio. |
| 🌍 **Live translation** | Translate the transcript and the answers during the meeting, with a choice of translation providers. |
| 📌 **Action items and bookmarks** | The app extracts tasks, lets you pin key moments and splits the meeting into topics for a quick review. |
| 📄 **Documents per meeting** | Resume, job description and notes become context for that meeting only, isolated from the others. |

## Screenshots

<table>
  <tr>
    <td width="50%"><img src="docs/images/tela-entrevista.webp" alt="Live interview: transcript on the left, detected question and suggested answer on the right"></td>
    <td width="50%"><img src="docs/images/tela-gravacao.webp" alt="Recorded meeting with waveform, playback speed and synced transcript"></td>
  </tr>
  <tr>
    <td align="center"><b>Live interview</b><br><sub>Both sides transcribed, the question detected and the suggested answer next to it.</sub></td>
    <td align="center"><b>Recording and playback</b><br><sub>Waveform, speed control and the transcript synced to the audio.</sub></td>
  </tr>
  <tr>
    <td><img src="docs/images/tela-inicio.webp" alt="Home screen with meeting context and active providers"></td>
    <td><img src="docs/images/tela-configuracao.webp" alt="First-run setup assistant"></td>
  </tr>
  <tr>
    <td align="center"><b>Home</b><br><sub>Meeting context (resume, job description, notes) and the active providers for each channel.</sub></td>
    <td align="center"><b>First-run setup</b><br><sub>A seven-step assistant to leave with transcription and answers working.</sub></td>
  </tr>
</table>

<sub>The interview conversation in the screenshots is a fictional example.</sub>

## Download

Get the installer for your system from the **[latest release](https://github.com/trichains/eloq-releases/releases/latest)**:

| System | File to download | Requirements |
|---|---|---|
| **Windows** | `eloQ_<version>_x64-setup.exe` | Windows 10 or 11, 64-bit |
| **macOS** | `eloQ_<version>_aarch64.pkg` | macOS 13 or later, **Apple Silicon** (M1 or newer) |

> There is no Linux build and no Intel Mac build at the moment.

The other files in each release (`latest.json`, `.nsis.zip` and `.sig`) are used by the **automatic updater** on Windows. You do not need to download them.

### Install on Windows

1. Run `eloQ_<version>_x64-setup.exe`. It installs for your user only, no administrator rights needed.
2. If Windows SmartScreen shows a warning, click **More info** and then **Run anyway**.
3. Open eloQ. New versions are downloaded and installed automatically, and every update is cryptographically signed.

### Install on macOS

1. Open `eloQ_<version>_aarch64.pkg` and follow the Installer.
2. On the first run the Mac may say the app is from an **unidentified developer**, because eloQ does not have Apple signing yet. Go to **System Settings → Privacy & Security** and click **Open Anyway**. This is needed only once, and you do not have to turn off any system protection.
3. Open **eloQ** from **Applications**. When asked, allow **microphone** and **screen & system audio recording** access, so eloQ can hear both sides of the call.
4. Reinstalling or updating replaces the app but keeps your data and saved keys.

> Automatic updates on macOS have not arrived yet. When a new version comes out, download the new `.pkg` and install it over the old one.

## Getting started

1. **Run the setup assistant.** A seven-step guide that gets transcription and answers working on the first run.
2. **Pick your providers.** One for transcribing and one for answering, local or cloud. Paste your own API key where one is needed. Keys are stored in the Windows Credential Manager or the macOS Keychain.
3. **Add context (optional).** Drop in your resume, the job description or notes for that meeting.
4. **Start the meeting** and keep your video call open as usual. eloQ listens to both sides.
5. **Press SPACE** when a question comes up, and glance at the suggestion. Use **Answer now** if you prefer the button.

## From audio to the answer on screen

```
 microphone ──┐                                   ┌─ guard: is the question grounded
              ├─▶ transcription ─▶ turns and ─▶   │   in the conversation?
 system audio ┘   per channel      questions      └─▶ model (with queue and fallback) ─▶ answer on screen
```

1. **Two-channel capture.** Microphone as YOU, system audio as THE OTHER PERSON (WASAPI loopback on Windows, ScreenCaptureKit on macOS).
2. **Per-channel transcription.** Each channel can use a different provider, local or cloud.
3. **Turns and question detection.** Speech is grouped into turns and the question is recognized by rules, with no AI call.
4. **Context with a safeguard.** The prompt is built from the transcript and your documents. If the question depends on something never said, the model is not called.
5. **Model with a queue and fallback.** **Answer now** jumps ahead of automatic answers. If a provider fails or hits its limit, the request moves to the next one, with an honest notice on screen.
6. **Overlay and Focus window.** The answer streams in and can be shortened, adapted or translated.

## Works with the providers you choose

| | Local (on your computer) | Cloud (with your own key) |
|---|---|---|
| **Transcription** | Whisper.cpp, Sherpa-ONNX, ONNX Runtime, Parakeet | Deepgram, Groq Whisper, Azure Speech, OpenAI Whisper API |
| **Answers (LLM)** | Ollama, LM Studio | OpenAI, Anthropic, Gemini, Groq, OpenRouter |
| **Translation** | OPUS-MT (works offline) | Microsoft, Google, DeepL, or an AI model |

## Privacy: you choose

eloQ **has no server of its own for audio or text** and uses **your own API keys**. You decide, channel by channel, whether to keep everything on your computer or use a cloud service for quality.

| If you choose... | What happens |
|---|---|
| **Everything local** (Whisper.cpp, Sherpa-ONNX, Parakeet, Ollama, LM Studio, OPUS-MT) | Audio and text **never leave your computer**. |
| **Cloud transcription** (Deepgram, Groq, Azure, OpenAI) | The audio is sent to the provider to be transcribed. |
| **Cloud answers** (OpenAI, Anthropic, Gemini, Groq, OpenRouter) | The conversation and documents for that question are sent to the provider to write the answer. |
| **Keys, history and recordings** | Stay only on your machine (Credential Manager or Keychain, and a local database). |
| **License** | Only your email and a hashed installation id go to the license server. **Audio, transcript and prompts never do.** |

When you use a cloud provider, the privacy policy and retention settings of **your account** with them apply. It is worth checking before a sensitive conversation. Want maximum privacy? Combine local transcription and local answers.

## Demo and full version

- **Demo (free).** Download, install and try eloQ in a real conversation. It has limits on meeting length and number of answers, and some features (such as recording, export and cloud providers) belong to the full version.
- **Full version.** Unlocked by license. You activate it with a code sent to your email, and each license works on a limited number of devices (a Windows PC and a Mac can share the same one).

Questions, or interested in using eloQ with your team? **[Get in touch](https://trichains.dev/contact)**.

## Known limits

- **macOS** has no Apple signing yet and no automatic updates.
- A **yes/no question** with no question word and no "?" does not trigger an automatic answer. Press **SPACE** and eloQ answers anyway.
- No build for **Linux** or **Intel Macs**.
- The source code is **private**. Only the installers are public.

## Use it responsibly

eloQ is a thinking aid, not a replacement for you. Check the rules of your interview, school or company, and the laws about recording conversations where you live, before you use it. Tell the people involved when recording is required.

## FAQ

<details>
<summary><b>Is eloQ free?</b></summary>

You can download it and use the Demo for free. The full version is unlocked by license. For details, see the [product page](https://trichains.dev/eloq) or [get in touch](https://trichains.dev/contact).
</details>

<details>
<summary><b>Does it answer by itself?</b></summary>

By default, no: you press **SPACE** (or **Answer now**) when you want a suggestion. There is an option in the settings to turn on automatic answers, and even then eloQ answers at most once per question.
</details>

<details>
<summary><b>Can the other person see the eloQ window?</b></summary>

On Windows, stealth mode excludes the window from screenshots, recordings and screen sharing. This depends on the system and on the screen sharing app, so test it before an important call. Please follow the rules of the context where you use eloQ.
</details>

<details>
<summary><b>Is my audio sent to eloQ servers?</b></summary>

No. eloQ has no server of its own for audio or text. With local providers, nothing leaves your computer. If you pick a cloud provider to transcribe or answer, the content goes to that provider, and the rules of your account with them apply. See [Privacy](#privacy-you-choose).
</details>

<details>
<summary><b>Is the code open source?</b></summary>

No. The source code is private and this repository contains only installers and release metadata.
</details>

<details>
<summary><b>How do I update?</b></summary>

On Windows, updates are downloaded and installed automatically. On macOS, download the latest `.pkg` from the [releases page](https://github.com/trichains/eloq-releases/releases/latest) and install it over the old one.
</details>

## Report a problem

Found a bug or have a suggestion? [Open an issue](https://github.com/trichains/eloq-releases/issues) with your system (Windows or macOS and version), the eloQ version and what happened. **Please do not paste API keys, audio or private conversations.**

## About this repository

This repository only holds the **official eloQ installers** and the release metadata used by the automatic updater. The application's source code is maintained privately, so pull requests with code are not accepted here.

<br>

<div align="center">

<sub>Made by <a href="https://trichains.dev">Cristhian Almeida</a>. Provider names and trademarks belong to their owners and do not imply partnership.</sub>

</div>
