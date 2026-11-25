
# 🎧 WAVECUT — AUDIO CUTTER

> **Cut audio. Keep the moment. Edit sound. Your way.**

> Explore audio editing through an interactive browser-based audio cutter. Trim audio files, preview selected sections, apply fade-in and fade-out effects, and export your edited audio in real time.

> A lightweight audio editing application built using HTML, CSS, and JavaScript — all inside one standalone HTML file.

---

## ✨ Features

### 🎧 Audio Import

Load and work with audio files directly from your device:

- Import audio files from your computer.
- Supports MP3, WAV, M4A, AAC, OGG and other browser-supported formats.
- Drag and drop audio files into the application.
- Display audio file information.
- View file size, channel count and sample rate.
- Process audio locally inside the browser.

### 🌊 Waveform Visualization

Explore your audio through an interactive waveform:

- Real-time waveform visualization.
- Highlighted audio selection region.
- Visible start and end markers.
- Interactive waveform editing.
- Visual representation of audio signals.
- Easy identification of selected audio sections.

### ✂️ Audio Cutting and Trimming

Precisely select the audio section you want:

- Set custom start and end times.
- Adjust trim points using range controls.
- Enter exact timestamps manually.
- Select audio sections visually.
- Preview the selected audio before exporting.
- View the selected audio duration.

### 🎚️ Audio Effects

Customize the selected audio using basic audio effects:

- **Fade In** — Gradually increase audio volume at the beginning.
- **Fade Out** — Gradually decrease audio volume at the end.
- Adjust fade duration using sliders.
- Preview the edited audio before exporting.

### ▶️ Playback Controls

Control audio playback directly inside the application:

- ▶️ Play the selected audio section.
- ⏸️ Pause playback.
- ⏹️ Stop playback.
- Preview the trimmed section.
- Listen to the selected audio before exporting.

### 📥 Audio Export

Export your edited audio directly to your device:

- Export trimmed audio as WAV.
- Automatically generate downloadable audio files.
- Preserve the original audio file.
- Process selected audio samples.
- Download the edited audio locally.

### 🎨 Visualization and Interface

- Modern dark-themed interface.
- Interactive waveform workspace.
- Smooth audio playback controls.
- Responsive application layout.
- Clean and user-friendly editing environment.
- Simple and accessible editing controls.

---

## 📂 Project Structure

```text
WaveCut_Audio_Cutter/
│
├── WaveCut_Audio_Cutter.html    ← Complete web application
├── README.txt                   ← Project documentation
├── README.md                    ← GitHub documentation
└── LICENSE                      ← Project license
```

The complete application is contained in a single HTML file, including:

- HTML structure
- CSS styling
- JavaScript audio processing logic
- Audio decoding functionality
- Waveform visualization
- Audio playback controls
- Trim selection controls
- Fade-in and fade-out processing
- WAV encoding and export functionality
- File download functionality

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rsamwilson2323-cloud/WaveCut_Audio_Cutter.git
```

### 2️⃣ Open the Project Folder

```bash
cd WaveCut_Audio_Cutter
```

### 3️⃣ Run the Application

Open `WaveCut_Audio_Cutter.html` in any modern web browser.

**Windows users:** Double-click the HTML file to launch the audio cutter in your default browser.

✅ No installation process required.

---

## 📦 Requirements

```text
HTML5             Application structure
CSS3              Styling and responsive layout
JavaScript        Audio processing and interaction
Canvas            Waveform visualization
Web Audio API     Audio decoding and playback
Modern Browser    Chrome, Edge, Firefox, etc.
```

**No additional dependencies are required.**

- No Python
- No Node.js
- No npm packages
- No database
- No backend server
- No external libraries

---

## 🚀 Live Demo

You can publish WAVECUT using GitHub Pages.

**Repository:**

https://github.com/rsamwilson2323-cloud/WaveCut_Audio_Cutter

**Application file:**

https://github.com/rsamwilson2323-cloud/WaveCut_Audio_Cutter/blob/main/WaveCut_Audio_Cutter.html

To publish the application:

1. Open the repository's **Settings → Pages**.
2. Under Build and deployment, select **Deploy from a branch**.
3. Select the `main` branch.
4. Choose `/ (root)` as the publishing folder.
5. Click **Save**.

GitHub Pages will generate a website URL after publishing completes.

---

## ▶️ Usage

### 🎧 1. Load an Audio File

1. Open the application.
2. Click **Choose audio file**.
3. Select an audio file from your device.
4. Alternatively, drag and drop the audio file into the upload area.
5. Wait for the waveform to load.

### ✂️ 2. Select the Audio Section

1. Adjust the start and end controls below the waveform.
2. Click the waveform to move the nearest trim point.
3. Enter exact timestamps in the START and END fields if needed.
4. Check the selected audio duration.

### ▶️ 3. Preview Your Selection

1. Click the Play button.
2. Listen to the selected audio section.
3. Use Stop to stop playback.
4. Adjust the trim points if necessary.

### 🎚️ 4. Apply Audio Effects

Experiment with the available fade controls:

- Increase Fade In to gradually raise the volume at the beginning.
- Increase Fade Out to gradually reduce the volume at the end.
- Adjust the fade duration using the sliders.
- Preview your changes before exporting.

### 📥 5. Export the Edited Audio

1. Click **Export trimmed audio**.
2. The application processes the selected audio.
3. The edited audio is automatically downloaded.
4. Your exported audio is saved in WAV format.

---

## 🧠 Audio Processing Behind the Application

WaveCut demonstrates several fundamental audio processing concepts.

| Audio Concept | Description |
|---|---|
| Audio Decoding | Converts supported audio files into browser-readable audio data |
| Waveform Rendering | Visually represents audio signals |
| Audio Trimming | Selects a specific portion of an audio file |
| Sample Processing | Processes individual audio samples |
| Fade In | Gradually increases audio volume |
| Fade Out | Gradually decreases audio volume |
| WAV Encoding | Converts processed samples into WAV format |
| Audio Playback | Plays selected audio sections |

### Mathematical Representation

**Audio Selection:**

```text
Selected Duration = End Time - Start Time
```

**Fade-In:**

```text
gain = currentSample / fadeInSamples
```

**Fade-Out:**

```text
gain = remainingSamples / fadeOutSamples
```

**Audio Output:**

```text
outputSample = inputSample × gain
```

These calculations help process the selected audio and apply gradual volume changes during fade effects.

---

## 🛠️ Key Technical Details

| Feature | Implementation |
|---|---|
| Frontend | HTML5 |
| Styling | CSS3 |
| Application Logic | Vanilla JavaScript |
| Audio Processing | Web Audio API |
| Audio Decoding | AudioContext |
| Waveform Rendering | HTML Canvas |
| Audio Playback | AudioBufferSourceNode |
| Audio Trimming | Sample-based selection |
| Fade Effects | Sample volume processing |
| Audio Encoding | WAV (16-bit PCM) |
| File Download | Blob and URL APIs |
| Backend | Not required |
| Database | Not required |

---

## 📌 Important Notes

- WAVECUT is designed for audio trimming and basic audio editing.
- The application uses browser-based audio processing.
- Audio files are processed locally and are not uploaded to a server.
- Supported input formats depend on browser audio decoding capabilities.
- The exported audio is saved in WAV format.
- Exported WAV files may be larger than compressed audio formats such as MP3.
- Large audio files may require significant memory and processing time.
- Actual performance depends on the browser and device capabilities.
- The application is not a complete professional digital audio workstation.

---

## 🚀 Future Improvements

- 🎵 Add MP3 export functionality.
- 🔍 Introduce zoomable waveform visualization.
- ✂️ Add audio splitting and multiple clip editing.
- 🔊 Add volume adjustment and normalization.
- 🎛️ Introduce equalizer controls.
- 🔁 Add loop playback functionality.
- ⏪ Implement undo and redo editing.
- 🎼 Add multiple audio file merging.
- 🎙️ Introduce microphone audio recording.
- 📱 Improve mobile touch controls.
- ⌨️ Add keyboard shortcuts.
- 📊 Display detailed audio statistics.
- 🎚️ Introduce additional audio effects.

---

## ⚠️ Disclaimer

This project is intended for educational and personal use. It demonstrates fundamental audio editing concepts through an interactive browser-based application.

**WAVECUT is a lightweight audio editing tool, not a professional digital audio workstation.**

Audio format support depends on the browser's Web Audio API implementation. The application exports selected audio sections in WAV format.

---

## 👨‍💻 Author

**Sam Wilson**

🌐 GitHub: https://github.com/rsamwilson2323-cloud

💼 LinkedIn: https://www.linkedin.com/in/sam-wilson-14b554385/

---

## 📜 License

This project is distributed under the license provided in the repository's LICENSE file.

---

<div align="center">

### 🎧 WAVECUT

**Cut audio. Keep the moment.**

*Built with HTML, CSS, and JavaScript.*

</div>
