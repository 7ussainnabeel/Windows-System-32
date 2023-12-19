<!-- Windows-System-32 -->

<p align="center">
  <img src="https://encrypted-tbn3.gstatic.com/images q=tbn:ANd9GcTr8qItAiFw4YxlpCLOD9_0cfzyqb-6rSIBrvoawd7uQM6deoEI">
</p>

<h3><p align="center">Deleting Windows System32 Folder</p></h3>

This code attempts to delete the Windows System32 folder. The Windows System32 folder is a critical system directory that contains 32-bit libraries, drivers, and other essential components for the proper functioning of the operating system. Deleting this folder can lead to severe issues with your operating system.

It is important to note that running this code is not recommended and should only be done at your own risk.

<h3><p align="center">Requirements</p></h3>

- Python 3.6 or higher
- Admin rights to run this code (Windows only)

<h3><p align="center">How to Use</p></h3>

##(Windows)

1. Download the code and run it in a Python environment.
2. If a random number between 0 and 6 is equal to 1, the code will attempt to delete the Windows System32 folder.

Please remember to use this code responsibly and avoid running it in a production environment.

<h3><p align="center">Code Explanation</p></h3>

The code is written in Python and utilizes the `random` and `os` modules.

1. `import random` and `import os` import the necessary modules.
2. `random.seed(None)` sets the seed to the current system time, ensuring that a new random number sequence is generated each time the program is run.
3. `if random.randint(0,6) == 1:` checks if the random number generated is 1.
4. If the random number is 1, `os.remove("C:\Windows\System32")` is executed. This line of code attempts to delete the Windows System32 folder.

Please note that deleting the Windows System32 folder is not recommended as it can lead to severe issues with your operating system.

This Tool is made for educational purposes only. Do not attempt to violate the law with anything contained here. If this is your intention, then Get the hell out of here!
