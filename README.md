# HelpForYou
![homepage](https://user-images.githubusercontent.com/98030516/231335479-a9c47919-82b7-4e31-9b1e-26168c97ed73.jpeg)
## Inspiration
Speech impaired people use hand signs and gestures to communicate. Normal people face difficulty in understanding their language.As a result, **HelpForYou** is a system which recognizes the different signs, gestures and conveys the information to the normal people. It bridges the gap between physically challenged people and
normal people.
## How it Works
**HelpForYou** is a system which recognizes the different signs, gestures and conveys the information to  physically challenged people and normal people.
1. User have Sit in a well lit area , ensuring that permission for web cam is granted.
2. It recognizes hand movement of 24 English Alphabets.
3. Ensure that your hand is positioned within the square frame.
4. Press "." to close the webcam.
5. User can now his/her knowledge of sign language.                   
## Tech Stack Used
<img src="https://img.shields.io/badge/Python-ColourCode?logo=python&logoColor=yellow&style=ShieldStyle" />    <img src="https://img.shields.io/badge/HTML-ColourCode?logo=HTML&logoColor=orange&style=ShieldStyle" />    <img src="https://img.shields.io/badge/CSS-ColourCode?logo=CSS&logoColor=blue&style=ShieldStyle" />    <img src="https://img.shields.io/badge/flask-ColourCode?logo=flask&logoColor=yellow&style=ShieldStyle" />   <img src="https://img.shields.io/badge/javascript-ColourCode?logo=javascript&logoColor=orange&style=ShieldStyle" />

**Python** is the programming language used to create the emotion recognition . CV2, MediaPipe, NumPy, pickle and other libraries are also utilized. The model is build using the RandomForest approach . We have our dataset stored as model3.pkl, which comprises around 2400 photos, was utilized for model training and validation. 
  This model is deployed on a website created with **HTML** and **CSS** using the **flask framework**.
  
  ## Installation
  For using HELP FOR YOU web application , user have to follow some instructions:
  1. Clone the Repo
    git clone https://github.com/surabhi-paliwal/HelpForYou2.git
  ## Features
  1. Hand Recoginition - Recognizes the hand motion of the user using webcam.
  2. Test Knowledge of Signs - Recognizes user's hand motion and based on that shows user know sign language or not.
  3. About - It tells about the project.
  
  
