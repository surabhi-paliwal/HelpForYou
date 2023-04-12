# HelpForYou

## Introductry Screen
![homepage](https://user-images.githubusercontent.com/98030516/231335479-a9c47919-82b7-4e31-9b1e-26168c97ed73.jpeg)
## Inspiration
Speech impaired people use hand signs and gestures to communicate. Normal people face difficulty in understanding their language.As a result, **HelpForYou** is a system which recognizes the different signs, gestures and conveys the information to the normal people. It bridges the gap between physically challenged people and
normal people.
                 
## Tech Stack Used
<img src="https://img.shields.io/badge/Python-ColourCode?logo=python&logoColor=yellow&style=ShieldStyle" />    <img src="https://img.shields.io/badge/HTML-ColourCode?logo=HTML&logoColor=orange&style=ShieldStyle" />    <img src="https://img.shields.io/badge/CSS-ColourCode?logo=CSS&logoColor=blue&style=ShieldStyle" />    <img src="https://img.shields.io/badge/flask-ColourCode?logo=flask&logoColor=yellow&style=ShieldStyle" />   <img src="https://img.shields.io/badge/javascript-ColourCode?logo=javascript&logoColor=orange&style=ShieldStyle" />

**Python** is the programming language used to create the sign recognition model. CV2, MediaPipe, NumPy, pickle and other libraries have also been utilized. The model is built using RandomForest approach. We have our model stored as model3.pkl. Our dataset comprises of around 2400 photos, which were utilized for model training and validation. 
  This model is deployed on a website created with **HTML** and **CSS** using the **flask framework**.
  
  ## Installation
  For using HELP FOR YOU web application , user have to follow some instructions:
  1. Clone the Repo
     ```sh
     git clone https://github.com/surabhi-paliwal/HelpForYou2.git
     ```
 2. Install packages
    ```sh
     pip install package_name
     ```
 
 ## How it Works
**HelpForYou** is a system which recognizes the different signs, gestures and conveys the information to  physically challenged people and normal people.
1. Sit in a well lit area, ensuring that permission for web cam has been granted.
2. It recognizes hand movement of 24 English Alphabets (excluding J and Z as their signs are not static).
3. Ensure that your hand is positioned within the square frame.
4. Press "." to close the webcam.
5. Press "esc" key to make a word.
6. You can now practice sign language.  


  ## Features
  1. Hand Recoginition - Recognizes ASL hand gestures of the user using webcam.
  2. Practice Signs - Recognizes user's hand gestures and based on which user can create words practice sign language.
  3. About - It tells about the project.
  
  ## Instruction page
  ![instruction](https://user-images.githubusercontent.com/98030516/231341880-eb8f8978-b848-4d1c-881c-ccd52a1677ac.png)
  ## Signing words
  ![demo](https://user-images.githubusercontent.com/98030516/231341920-e737b8d7-5e52-4b43-8709-cb9c5aecfec7.png)
  ## Moving to next word
  ![Sign Target Words](https://user-images.githubusercontent.com/91132355/231346982-5b10dab0-5048-4f8f-9338-01b0537f3a86.png)
  ## About Us
  ![aboutus](https://user-images.githubusercontent.com/98030516/231341957-ed0d59cf-599a-4242-8842-337d0fcdc52d.png)



  
  
