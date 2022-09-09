# Blind-Vision-project
### It is a summer training project to help the blind handle their money using computer vision technique.
![gitHub](https://user-images.githubusercontent.com/91850794/184735876-78767aeb-c6d6-4a0a-851e-034111e65e91.png)

### 1) Idea of the project:
We worked on the Egyptian currencies to do the following:

1- Help the blind by computer vision accompained with sound technique to distinguish among:
  * 50-piasteres
  * 1-pound 
  * 5-pounds
  * 10-pounds
  * 20-pounds
  * 50-pounds
  * 100-pounds
  * 200-pounds
 
<img src="https://user-images.githubusercontent.com/91850794/183764305-372bdbf9-892f-474c-9a24-a3bf2df55d38.jpg" width="200" height="200"/>

2- Help the blind calculate their net amount of money they have.

_________________________________________________________________________________________________________________________________________

### 2) Language & Libraries used: 
- Language:

  * python
  
- Libraries:

  * openCV (Open Source Computer Vision Library)
  * gtts (Google Text-to-Speech Library) 
  * playsound (Python Libraries for playing audios)
  * Numpy (Python Library deals with arrays & matrices)
  * inflect (Python string transformation library to transform numbers to text)
  * os (Python library to interact with the operating system)

_________________________________________________________________________________________________________________________________________

### 3) Algorithms used:

* ORB (Oriented FAST and Rotated BRIEF) : an openCV built-in algorithm to help in object detection by extracting sets of keypoints and descriptors from the image.
* BF (Brute Force): an openCV built-in algorithm to help in object recognition throug matching the descriptors of the two images and find the best match.
_________________________________________________________________________________________________________________________________________

### Team Members:
- contributors:
  * Ebrahim Sayedelahl
  * Moaz Mostafa
  * Mohamed Radwan
  * Omar Allam
  * Yahia Omar
  * Ziad Helmy

- Supervisors:
  * Eng / Aya Nagy 
_________________________________________________________________________________________________________________________________________

### How to use the project:
  1. Make sure to have one folder contais (images_folder & source_code_file)
  2. Open the source code with a notebook-supported editor.
  3. Run the first cell only once in order to load the audios.
  3. Run the second cell "main project cell" as many times as you want.
  4. After running:
     - press "w" key on keyboard to read a currency. "press "w" at each time you read a new currency.
     - press "q" to accumulate all currencies you have read and exit the running process.
            Note: those keys (w,q) will be replaced with buttons at the corner of the mobile phone when the application is ready.
