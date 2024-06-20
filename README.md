  **Face Recognition-Based Attendance System**
This project is a face recognition-based attendance system. It uses your device's camera to register and recognize faces, and automatically marks attendance by identifying faces


**Clone:**
git clone <repository-url> 

**installation of dependent packages:**

pip install -r requirements.txt

**Execute:** python3 attendance.py



 **Project Flow & Explanation**
**Register a New Student:**

Click on the "Register New Student" button.
A small window will pop up where you need to enter your ID and name.
Click on the "Take Image" button.

**Capture Images:**

A camera window will pop up, which will detect your face and take up to 50 images (you can change the number of images).
These images will be stored in the TrainingImage folder.
The more images you provide, the better the system will perform in recognizing the face.

**Train the Model:**

Click on the "Train Image" button.
The system will train the model by converting all the images into numeric format for the computer to understand.
This process may take some time depending on your system's performance.

**Automatic Attendance:**

Click on the "Automatic Attendance" button.
Enter the subject name.
The system will use the trained model to recognize faces and mark attendance.
A .csv file will be created for each subject, storing attendance records.

**View Attendance:**

Click on the "View Attendance" button.
Attendance records will be displayed in a tabular format.








