# Face-detection

The program  is designed to perform face recognition using the `face_recognition` library in Python. It reads a set of images from a specified directory, encodes the faces in those images, and then uses a video stream (either from a webcam or a video file) to perform real-time face recognition.

Here are the instructions to run the program:

1. Ensure that you have the required libraries installed: `cv2`, `numpy`, `face_recognition`, and `os`. You can install these libraries using `pip install`.

2. Organize your images in a directory called "photos". Each subdirectory within the "photos" directory should contain images of a single person. The subdirectory name will be used as the person's name for identification.

3. Update the `video_path` variable in the code to specify the path of your video file. If you want to use the webcam, you can leave it as `0` to use the default webcam.

4. Save the updated code to a file with a `.py` extension (e.g., `main.py`).

5. Open a terminal or command prompt and navigate to the directory where you saved the code.

6. Run the program using the Python interpreter. For example, if you have Python installed in `C:\Python\python.exe`, you can run the following command:
   ```
   C:\Python\python.exe main.py
   ```

7. The program will start by encoding the faces in the images found in the "photos" directory. It will print "Encoding Complete" once the encoding process is finished.

8. After encoding, the program will start the video stream and perform real-time face recognition. The recognized faces will be displayed with their names on the video stream.

9. To exit the program, press `Enter` in the terminal or close the video window.

Make sure you have the correct image paths and video file path specified to avoid any file path errors.
