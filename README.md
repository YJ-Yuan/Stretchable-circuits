"dataAutomation" is for automatically computing on-off ratio, threshold voltage, gm/Wch and mobility. In addition to arrays and matricies, they will also output histograms

<img width="400" alt="Screenshot 2025-01-15 at 2 15 22 PM" src="https://github.com/user-attachments/assets/73dd2455-6dc5-4e0c-9b78-d249d7714184" />
<img width="400" alt="Screenshot 2025-01-15 at 2 17 02 PM" src="https://github.com/user-attachments/assets/eeeb6382-6b33-4faf-bc3d-3274013dc5eb" />

In the un-edited python Jupyter file, we deal with files like above. There are multiple folders with .xls files that we want to process. Those files are directly from Keithley 4200 and each file contains measured ID-VG curve of transistors of interest.

We create a folder called "automation", and put this Jupyter file into the folder. Run this file and it will copy files in the specified folders (chip1234 in this case) with .xls extension to the same director and rename them by adding their folder names.

Jupyter Lab dependencies required
