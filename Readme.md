# AI Virtual Keyboard
In this project I am going to create a virtual key board based on Artificial Intelligence (AI).
I will write the code step by step so it is easy to follow.
I will also look at how we can run this program to operate applications like a notepad.

## Features
* Can track your hand in real-time
* Can write text in writer redactor based on your hand activity

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/virtual_keyboard.git`
2. Install all the requirements
`run libraries.bat` or
`pip install -r requirements.txt`
3. Run the program
`python main.py`

## Help
You might face issue with webcam not showing and you get errors.
To solve it just change the value in this line (for example to `1`).
`cap = cv2.VideoCapture(0)`
Increment this number until you see your webcam.

## Hand Landmarks
<img src="https://github.com/paveldat/gesture_volume_control_v2/blob/main/img/HandLandmarks.png">

## Keyboard
<img src="https://github.com/paveldat/virtual_keyboard/blob/main/img/keyboard.png">

Where:

"<" - BACKSPACE

" " - SPACE

## Click
In order to simulate a click, you need to connect the index and middle fingers on your hand. An example of a valid click is shown in the image below.

<img src="https://github.com/paveldat/drag_and_drop/blob/main/img/click.png">

## Result
![Alt Text](https://github.com/paveldat/virtual_keyboard/blob/main/img/result.gif)

## Result using notepad
![Alt Text](https://github.com/paveldat/virtual_keyboard/blob/main/img/result_notepad.gif)