# Disappearify 🎩✨  
*Transform into invisibility with the power of OpenCV!*

---

## 📜 **Project Description**  
**Disappearify** is a computer vision project that creates a magical invisibility effect using a camera feed. When a person wears a specific cloak, the cloak becomes transparent, seamlessly blending with the background, making it appear as though you can see through it.

Using Python and OpenCV, this project achieves the effect by identifying the cloak's color in the HSV color space and cleverly masking it with a previously captured background frame.

---

## 📂 **Features**  
- Real-time invisibility effect.  
- Adjustable HSV values through trackbars for dynamic cloak color selection.  
- Simple and intuitive setup using Python and OpenCV.  

---

## 🚀 **Getting Started**  

### **Prerequisites**  
Ensure you have the following installed on your system:
- Python (>= 3.8)
- OpenCV (4.10.0.84)
- NumPy (1.26.4)

### **Installation**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/disappearify.git
   cd disappearify

2. Install all dependencies:
    ```bash
    pip install -r requirements.txt

### 📋 **Usage**
1. Run the scipt:
    ```bash
    python disappearify.py

2. Adjust the HSV values using the sliders to detect the cloak's color.

3. Enjoy the magical invisibility effect!
4. Press 'q' to quit the application.

### 🎨 **Customization**
*  Modify the default HSV values in the script for different cloak colors:
   ```bash
   cv2.createTrackbar("upper_hue", "bars", 110, 180, hello)
   cv2.createTrackbar("lower_hue", "bars", 68, 180, hello)

### 🤝 **Contributors**
- Mitkumar Patel -  [MitPatel24](https://github.com/MitPatel24)
