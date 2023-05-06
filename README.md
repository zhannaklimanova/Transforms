## Project Overview
The goal of this project was to better understand the Fourier Transform (FT) algorithm through hands-on implementation, testing, and analysis. The code was initially written to work in a local desktop computer in order to take advantage of integrated development environment development (IDE) debugging tools. It was then transferred into a Google Colab notebook for better visualization and portability. The *transforms.ipynb* file contains discussion sections of the algorithms and test results, as well as the associated code and execution outputs.<br>
The *transform.ipynb* is composed of several parts:<br>
1. **Imports**: installs necessary dependancies, mounts the drive, and establishes the path of all external files used by the notebook.
2. **Data**: contains the custom generated test waveforms as well as the triangle.wav and trumpet.wav file attributes.
3. **Discrete Fourier Transform (DFT)**: explains the algorithm and implements the initial, slow version using the formula. The DFT is then optimized using Numpy arrays. Simple tests are conducted to ensure the custom implementations are performing on-par with the Numpy versions.
4. **Fast Fourier Transform (FFT)**: explains and implements the algorithms. Conducts tests with the generated waveforms from the Data section. Compares results with those of the Numpy FFT.
5. **Runtime Comparisons**: compares the runtime of the DFT and FFT algorithms.
6. **Minimalist Filter Experiment**: very bare-bones filtering idea implementation that computes the DFT, removes a certain number of frequency values based on the provided level, and returns the final waveform by running the inverse FFT.
7. **Short-Time Fourier Transform (STFT)**: version of the STFT algorithm which is tested on a waveform that decays as a function of time.
8. **Future Work**: briefly discusses how the project can be further extended.
9. **Sources**: lists utilized sources.
