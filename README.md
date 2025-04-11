# 🧠 FaceEmotion.AI

FaceEmotion.AI is a powerful web application that uses real-time facial emotion recognition to assess your mental health over a 20-second session. Based on your emotional trends, it provides personalized recommendations including:

- 📚 Self-help books  
- 🎥 Motivational or calming videos  
- 🎵 Mood-boosting music  
- 🧘‍♂️ Yoga and mindfulness exercises



## 🚀 Features

- 🔍 **Real-time facial emotion tracking** (per second for 20 seconds)
- 📈 **Emotion graph visualization**
- 🧘‍♀️ **Mental health summary**
- 📖 Curated **books**, **videos**, **music**, and **yoga** based on emotional profile
- 🔒 No data stored — privacy-first experience

## 📦 Tech Stack

- **Frontend:** HTML, CSS, JavaScript, React.js
- **Backend:** Node.js / Express.js (optional for recommendations)
- **AI/ML:** TensorFlow.js / face-api.js (emotion recognition)
- **Visualization:** Chart.js or Recharts
- **APIs:** YouTube, Spotify, Book APIs (Google Books, etc.)

## 📸 How It Works

1. Allow webcam access (no data stored).
2. The app scans your face for **20 seconds**, capturing emotion every second.
3. It classifies emotions like happy, sad, angry, neutral, surprised, etc.
4. Based on the emotional pattern, it:
   - Assesses mental state
   - Suggests **relevant content**
5. Offers a **calming experience** to support mental well-being.

## 📷 Emotion Categories Detected

- 😊 Happy  
- 😢 Sad  
- 😡 Angry  
- 😮 Surprised  
- 😐 Neutral  
- 😟 Disgust / Fear (if model supports it)

## 🛠️ Setup Instructions

```bash
git clone https://github.com/yourusername/FaceEmotionAI.git
cd FaceEmotionAI
npm install
npm start

