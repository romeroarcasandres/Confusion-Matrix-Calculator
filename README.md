# Confusion Matrix Calculator

A modern, web-based tool for calculating machine learning model performance metrics from confusion matrix values. Get instant precision, recall, F1 score, and accuracy calculations.

## ✨ Features

### 🔢 **Flexible Input Options**
- **Direct entry** - Enter TN, FP, FN, TP values individually
- **Auto-calculation** - Provide totals and partial values to auto-calculate missing ones
- **Smart validation** - Ensures all values are valid before calculating
- **Multiple combinations** - Enter data in the way that's most convenient for you

### 📊 **Comprehensive Metrics**
- **Precision** - Measures the accuracy of positive predictions
- **Recall (Sensitivity)** - Measures the ability to find all positive instances
- **F1 Score** - Harmonic mean of precision and recall
- **Accuracy** - Overall correctness of the model

### 🎯 **Instant Calculations**
- **Real-time updates** - Modify values and recalculate instantly
- **No clearing needed** - Update any value and click Calculate to refresh
- **Visual results** - Clear, color-coded display of all metrics
- **Formula transparency** - See exactly how each metric is calculated

### 📋 **Easy Export**
- **Copy to clipboard** - One-click copy in tab-separated format
- **Table-ready** - Paste directly into Excel, Google Sheets, or any spreadsheet
- **Complete data** - Includes Total Records, TN, FP, FN, TP
- **Quick documentation** - Perfect for reports and presentations

### 🎨 **Modern User Experience**
- **Beautiful interface** - Gradient design with smooth animations
- **Color-coded labels** - Green (TN), Orange (FP), Red (FN), Blue (TP)
- **Responsive design** - Works perfectly on desktop and mobile
- **Clear visualization** - Professional cards for each metric

## 🌐 Live Demo

**[Try it now!](https://yourusername.github.io/confusion-matrix-calculator/)**

## 💻 Getting Started

### Option 1: Use Online (Recommended)
1. Visit the [live demo](https://yourusername.github.io/confusion-matrix-calculator/)
2. Enter your confusion matrix values
3. Click "Calculate" to see all metrics instantly!

### Option 2: Download and Run Locally
```bash
# Download the HTML file
wget https://raw.githubusercontent.com/yourusername/confusion-matrix-calculator/main/confusion-matrix-calculator.html

# Open in any modern browser
open confusion-matrix-calculator.html
```

### Option 3: Clone Repository
```bash
git clone https://github.com/yourusername/confusion-matrix-calculator.git
cd confusion-matrix-calculator
# Open confusion-matrix-calculator.html in your browser
```

## 📱 Browser Compatibility

- ✅ **Chrome 60+** - Full support
- ✅ **Firefox 55+** - Full support  
- ✅ **Safari 12+** - Full support
- ✅ **Edge 79+** - Full support
- ✅ **Mobile browsers** - iOS Safari, Chrome Mobile

## 🎓 How to Use

### Basic Usage (All 4 Values)
1. Enter TN (True Negatives): e.g., 1802
2. Enter FP (False Positives): e.g., 2220
3. Enter FN (False Negatives): e.g., 240
4. Enter TP (True Positives): e.g., 358
5. Click "Calculate"

### Smart Usage (With Totals)
1. Enter Total Negatives: e.g., 4022
2. Enter Total Positives: e.g., 598
3. Enter TP: e.g., 358
4. Enter TN: e.g., 1802
5. Click "Calculate" - FP and FN are auto-calculated!

### Update Values
1. Change any input value
2. Click "Calculate" again
3. Results update instantly - no need to clear!

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks, no dependencies
- **Client-side processing** - All calculations happen in your browser
- **Secure** - Your data never leaves your device
- **Lightweight** - Single file, instant loading
- **No installation** - Works immediately in any modern browser

### Supported Calculations

- [x] **Precision** = TP / (TP + FP) × 100
- [x] **Recall** = TP / (TP + FN) × 100
- [x] **F1 Score** = 2 × (Precision × Recall) / (Precision + Recall)
- [x] **Accuracy** = (TP + TN) / Total × 100
- [x] **Auto-calculation** from partial values + totals
- [x] **Input validation** for non-negative numbers
- [x] **Real-time recalculation** without clearing

## 📄 License

This project is licensed under the Attribution-NonCommercial 4.0 International License - see the [LICENSE](LICENSE) file for details.