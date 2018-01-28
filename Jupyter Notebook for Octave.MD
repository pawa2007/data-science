#### Instructions for activating the Octave kernel in Jupyter Notebook in Windows 10 with Anaconda3

1. Install the [Octave kernel for Jupyter](https://github.com/calysto/octave_kernel)
2. Set the **OCTAVE_EXECUTABLE** environment variable in the **C:\Anaconda3\cwp.py** file by adding the following under the line containing
    ```
    env['CONDA_PREFIX'] = prefix
    env['OCTAVE_EXECUTABLE'] = 'C:\\Octave\\Octave-4.2.1\\bin\\octave-cli-4.2.1.exe'
    ```
3. Start Jupyter
