# Smart Habit Tracker 📊

A modern and powerful habit tracking web application built with **HTML, CSS, and JavaScript**. Track your daily routines, monitor progress with interactive charts, and develop consistent habits efficiently.

## 🌟 Features

### 📊 Visual Analytics

* **Progress Charts**: Clean donut charts showing daily completion percentage
* **Bar Charts**: Weekly and monthly progress visualization
* **Pie Charts**: Habit distribution by category
* **Streak Analysis**: Track your longest streaks and current progress

### 🎯 Habit Management

* **CRUD Operations**: Add, edit, and delete habits easily
* **Categories**: Organize habits by Health, Productivity, Learning, Mindfulness, Social, Creativity, and more
* **Flexible Frequency**: Daily, weekly, or custom day scheduling
* **Target Tracking**: Set specific targets with units (e.g., 8 glasses of water)

### 📅 Calendar View

* **Monthly Calendar**: Visual representation of daily progress
* **Progress Indicators**: View completion rates for each day
* **Easy Navigation**: Switch between months quickly

### 📱 Modern UI/UX

* **Responsive Design**: Works smoothly on desktop, tablet, and mobile
* **Modern Gradients**: Attractive color themes
* **Smooth Animations**: Clean interactions and transitions
* **Automatic Theme Support**: Supports dark and light system modes

### 💾 Data Management

* **Local Storage**: All habit data is saved locally in your browser
* **Export Feature**: Download your habit data as JSON backup
* **Import Feature**: Restore data easily from backup files
* **Cross-Device Transfer**: Move habits between different devices or browsers
* **Demo Data Included**: Preloaded habits for demonstration

## 🚀 Getting Started

### Option 1: Open Directly

1. Download the project files (`index.html`, `styles.css`, `script.js`)
2. Open `index.html` in any web browser
3. Start tracking your habits immediately

### Option 2: Run on Local Server

1. Open terminal in the project folder
2. Start a local server:

   * **Python:** `python -m http.server 8080`
   * **Node.js:** `npx serve -p 8080`
   * **VS Code:** Use the Live Server extension
3. Open `http://localhost:8080` in your browser

## 📋 How to Use

### Add a Habit

1. Click **Add Habit**
2. Enter habit details:

   * **Habit Name**
   * **Description (optional)**
   * **Category**
   * **Frequency**
   * **Target & Unit**
3. Click **Save Habit**

### Track Daily Progress

1. Go to the **Dashboard**
2. Click the completion circle next to a habit
3. Your charts update instantly

### View Analytics

1. Open the **Analytics** section
2. See:

   * Monthly progress
   * Habit category distribution
   * Streak analysis

### Calendar Overview

1. Open the **Calendar tab**
2. View monthly habit progress
3. Navigate between months

## 🎨 Customization

### Add New Categories

Edit the JavaScript file:

```javascript
const icons = {
    health: '🏃',
    productivity: '📈',
    learning: '📚',
    mindfulness: '🧘',
    custom: '🎯'
};
```

### Change Theme Colors

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --success-color: #10b981;
    --danger-color: #ef4444;
}
```

## 📊 Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **Chart.js** for analytics charts
* **Font Awesome** for icons
* **Google Fonts** for typography

## 🔧 Technical Details

### Browser Support

* Chrome
* Firefox
* Safari
* Edge

### Storage

* Uses **localStorage**
* No backend server required
* All data stays on your device

### Performance

* Lightweight and fast
* Mobile-friendly design
* Optimized for quick loading

## 🎯 Sample Habits

The project includes example habits such as:

* 💧 Drink 8 glasses of water
* 📚 Read for 30 minutes
* 🏃 Exercise regularly

You can remove them and add your own habits.

## 🔄 Data Management

### Export Data

Download a JSON backup of all habits.

### Import Data

Restore habits using a previously saved JSON file.

### Transfer Between Devices

1. Export data on Device A
2. Transfer JSON file
3. Import it on Device B

## 🌟 Tips for Habit Building

1. Start with a few simple habits
2. Be consistent rather than perfect
3. Track progress daily
4. Review analytics for motivation
5. Keep backups of your habit data

## 📝 License

This project is open source and free to use for learning and personal projects.

## 🚀 Build Better Habits

Stay consistent, track progress, and improve your daily routine with **Smart Habit Tracker**.
