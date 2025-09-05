🖐️ Virtual Calculator using Hand Gestures

A gesture-controlled Virtual Calculator built with Python, OpenCV, and Mediapipe.
Instead of clicking physical buttons, you can use your hand and finger gestures to type, delete, and calculate in real time.

🚀 Features

✋ Hand tracking using Mediapipe

👆 Gesture-based input (pinch = click)

🔢 Fully functional calculator (supports +, -, *, /, (), decimal, delete, clear, equals)

🎥 Real-time video overlay with OpenCV

⚡ Lightweight & runs on CPU

🛠️ Tech Stack

Python 3.8+

OpenCV

Mediapipe

NumPy

Math & Time (standard Python libraries)

📂 Project Structure
Virtual-Calculator/
│── calculator.py      # Main program
│── README.md          # Project documentation

⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/virtual-calculator.git
cd virtual-calculator


Install dependencies:

pip install opencv-python mediapipe numpy

▶️ Usage

Run the calculator:

python calculator.py


Controls:

Move your index finger to hover over buttons

Pinch with thumb & index finger to click

"C" → Clear

"DEL" → Delete last character


🔮 Future Improvements

Add scientific functions (sin, cos, log, etc.)

Support multi-hand interaction

Improve UI with better styling
"=" → Evaluate expression

Press q or Esc to quit.
