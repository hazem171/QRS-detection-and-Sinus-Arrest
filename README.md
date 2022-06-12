# QRS-detection-and-Sinus-Arrest

Implementing the QRS detection method given in Lecture 5. The QRS function takes as inputs the ECG signal to process and the moving average window size N. The function returns a vector that contains the timestamps of the R wave and a vector that contains the corresponding RR intervals. Applying the function to the ECG signal provided in the file “DataN.txt”. The sampling rate of this ECG signal is 256 Hz.
The ECG of a patient with Sinus Arrest is provided in the file “Data2.txt”. Implementing a function to find the timestamps at which a beat should have been recorded (missing beats). The function takes as inputs the ECG signal to process and the moving average window size N. The function returns the timestamps of missing beats. Applying the function to the ECG signal provided in the file “Data2.txt” with the best N obtained from QRS function. The sampling rate is 256 Hz. 

Attached files: 
• A figure showing the first 1500 samples of the ECG signal before and after noise filtering named “Before_After_Filter.jpg”.
• A figure showing the first 1500 samples of the ECG signal with an “*” marking the detected R waves for N = 10  named “DetectedR_10.jpg” 
• A figure showing the first 1500 samples of the ECG signal with an “*” marking the detected R waves for N = 15 named “DetectedR_15.jpg”
• A figure showing the first 1500 samples of the ECG signal with an “*” marking the detected R waves for N = 25 named “DetectedR_25.jpg”
• A figure showing the first 1500 samples of the ECG signal with an “*” marking the detected R waves for N = 25 but without noise filtering named “Unfiltered_25.jpg”. 
• A plot of the RR intervals with Beat number on the x-axis and RR interval in msec on the y-axis in the case of N = 25 named “RR.jpg” 
• A text file that shows the timestamps of missing beat(s) (the sample number at which the R wave should have been present) named “MissingBeats.txt” 
