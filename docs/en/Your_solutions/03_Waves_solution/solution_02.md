# 2. String Harmonics

## Problem Statement
A guitar string has a length of **64 cm** and a fundamental frequency (one antinode) of **330 Hz**. Our objective is to determine the speed of the wave on this string by analyzing the relationship between wavelength, frequency, and wave speed.

---

## Step-by-Step Solution

### 1. Identify Given Parameters and Unit Conversion
First, we list the known values. To ensure consistency in SI units, we must convert the length from centimeters to meters.
* Length of the string ($L$): $64 \text{ cm} = 0.64 \text{ m}$
* Fundamental frequency ($f_1$): $330 \text{ Hz}$
* Harmonic number ($n$): $1$ (Since it is the fundamental frequency with one antinode).

### 2. Determine the Wavelength ($\lambda$)
For a string fixed at both ends, the wavelength of the $n$-th harmonic is given by the formula:
$$\lambda_n = \frac{2L}{n}$$
Since we are dealing with the fundamental frequency (the first harmonic, $n=1$), the wavelength is exactly twice the length of the string:
$$\lambda = 2L = 2 \cdot 0.64 \text{ m}$$
$$\lambda = 1.28 \text{ m}$$
*Interpretation: In the fundamental mode, the string forms a single standing wave loop, which represents half of a full wavelength.*

### 3. Calculate the Wave Speed ($v$)
The relationship between wave speed, frequency, and wavelength is defined by the fundamental wave equation:
$$v = f \cdot \lambda$$
Substituting the given frequency and the calculated wavelength:
$$v = 330 \text{ Hz} \cdot 1.28 \text{ m}$$
$$v = 422.4 \text{ m/s}$$

### 4. Conclusion
The speed of the wave on this guitar string is **422.4 m/s**. This speed is determined by the tension of the string and its linear mass density.

---

## Graphical Interpretation (Optional for Discussion)
If we visualize the string's vibration:
* The **Nodes** are at both ends ($x=0$ and $x=0.64$).
* The **Antinode** (maximum amplitude) is exactly in the middle ($x=0.32$).
* The wave speed remains constant for higher harmonics unless the tension of the string is changed.
