# Signal Processing Projects

The purpose of the smoothing operation is removing small details during object extraction, filling the small gaps in curves or lines. Also, decreasing the noise effect is one of the main purposes of smoothing. Noises might occur because of the image sensor, digital camera, etc. Sudden changes among the pixels are observable more easily. In general, denoising an image is nothing but applying a low pass filter to remove the rapid changes. Low pass filters allow low frequencies and attenuate high frequencies. Rapid changes among the pixels are indicated as high-frequency components, that's why low pass filters have to be applied to remove these high-frequency components or noises. Since images are 2D signals, filters which are called kernels have to be thought of as 2D signals. Convolution is nothing but sweeping the kernel on the image and multiplying each pixel with the corresponding kernel pixel. After that, summing all the multiplication and dividing the result of the sum by the summation of each kernel coefficient to normalize the result. Below \( w \) is the kernel and \( f(x,y) \) is the original image [[1]](https://en.wikipedia.org/wiki/Kernel_(image_processing)).

## Contents

1. [Creating LPF without Butter Function](#1-creating-lpf-without-butter-function)
2. [Derivative Function](#2-derivative-function)
3. [Frequency Modulation](#3-frequency-modulation)
4. [High Pass and Low Pass Filter](#4-high-pass-and-low-pass-filter)
5. [Integration of a Signal](#5-integration-of-a-signal)
6. [Linearity](#6-linearity)
7. [Modulation and Demodulation](#7-modulation-and-demodulation)
8. [Quantization with Different Levels](#8-quantization-with-different-levels)
9. [Sampling](#9-sampling)
10. [Sampling and Interpolation](#10-sampling-and-interpolation)
11. [SSB Amplitude Modulation with Audio Signal](#11-ssb-amplitude-modulation-with-audio-signal)

## 1. Creating LPF without Butter Function

This file demonstrates how to create a low-pass filter (LPF) without using the built-in Butterworth filter function. It includes the theory and implementation details for designing a basic LPF.

## 2. Derivative Function

This file explains how to calculate the derivative of a signal. It covers both the theoretical background and practical implementation for deriving a signal in the time domain.

## 3. Frequency Modulation

This file covers frequency modulation (FM), a technique used to encode information in a carrier wave by varying its frequency. The document includes examples and explanations of FM theory and applications.

## 4. High Pass and Low Pass Filter

This file explains the concepts and implementations of high-pass and low-pass filters. It includes the design principles, mathematical formulations, and example implementations.

## 5. Integration of a Signal

This file provides information on how to integrate a signal. It covers numerical methods for signal integration and includes practical examples and code implementations.

## 6. Linearity

This file discusses the concept of linearity in signal processing. It includes theoretical explanations and examples demonstrating linear and nonlinear systems.

## 7. Modulation and Demodulation

This file explains the processes of modulation and demodulation. It includes various techniques for modulating and demodulating signals, along with examples and practical applications.

## 8. Quantization with Different Levels

This file covers the quantization process, which involves converting a continuous range of values into a finite range of discrete values. It includes examples of quantization with different levels and the effects on signal quality.

## 9. Sampling

This file discusses the sampling process, which involves converting a continuous signal into a discrete signal by taking samples at regular intervals. It includes theoretical background and practical examples of signal sampling.

## 10. Sampling and Interpolation

This file explains the concepts of sampling and interpolation in signal processing. It includes methods for reconstructing a continuous signal from its samples and practical examples.

## 11. SSB Amplitude Modulation with Audio Signal

This file covers Single Sideband (SSB) amplitude modulation using an audio signal. It includes theoretical explanations and practical examples for implementing SSB modulation.

## Getting Started

To explore the contents of this repository, navigate to the relevant file and review the code and explanations provided. Each file includes detailed information on its specific topic, along with practical examples and implementation details.


