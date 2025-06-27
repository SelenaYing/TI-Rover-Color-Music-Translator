# TI-Rover-Color-Music-Translator 🎨 🎵
A hands-on educational tool that uses the TI-Rover to play music using color codes.

This project programs the **TI-Rover** to detect RGB color values and play a **C note** based on those colors. It’s designed as a **hands-on educational tool** to help students explore topics such as **color theory**, **music composition**, and **introductory programming**.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🎯 Project Goal

To create a fun, interactive, and minimal-setup experience for students and educators that:

- Teaches color combinations, music composition, robotics, and programming
- Introduces core programming and sensor logic
- Encourages curiosity across STEAM (Science, Technology, Engineering, Arts, Math)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧩 Problem Breakdown

### 1. Accurate Color-to-Music Mapping  
- Smooth transition from **color detection** to **sound playback**
- Filters out noise and prevents accidental double-play using a **white card buffer**

### 2. User-Friendly Design  
- Plug-and-play interface
- Requires minimal user setup or calibration

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔨 Project Tasks

### ✅ Completed
- Tested RGB readings across various shades and lighting conditions

### 🔧 In Progress
- Determining optimal card width for reliable detection
- Implementing white buffer logic to prevent skipped or repeated notes
- Fine-tuning detection accuracy and timing
- Improving real-time feedback for users
  
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Folder Structure

- `/code` – Program files for the TI-Rover and helper modules
- `/docs` – Testing logs, setup instructions, and development notes
- `/media` – Images, diagrams, and demo clips

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧪 How It Works

### 🧰 Setup
1. Prepare 8 colored cards (excluding white).
2. A **white card** is used between notes to signal a transition and avoid repeats.
3. Run the program and follow the on-screen instructions.
4. Assign each colored card to a note in the **C major scale**.
5. The program reads RGB values and maps each to a corresponding note.

### 🎼 Play
1. Arrange your color cards in the desired music sequence (on a white background).
2. Maintain a consistent **card width** and **spacing** between colors (details in `/docs/setup-instructions.md`).
3. Run the playback mode to hear your composed melody.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📸 Demo

> ![demo](media/demo-video.gif)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📜 License

This project is licensed under the [MIT License](LICENSE).

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🤝 Contributing

Feedback, collaboration, and improvements are welcome!  
Feel free to open an issue or submit a pull request.
