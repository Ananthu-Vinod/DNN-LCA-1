
# OFDM Symbol Detection Using Deep Learning

---

## Project Title
OFDM Symbol Detection Using Deep Neural Network (DNN)

---

## Project Description
This project focuses on detecting Orthogonal Frequency Division Multiplexing (OFDM) symbols using Deep Learning techniques. Traditional OFDM detection methods rely on mathematical models, whereas this project implements a Deep Neural Network (DNN) to improve symbol detection performance in noisy channel conditions.

---

## Objectives
- To simulate an OFDM communication system
- To generate modulated OFDM symbols
- To introduce channel noise
- To train a Deep Neural Network for symbol detection
- To evaluate detection performance

---

## Methodology

1. **Bit Generation**  
   Random binary bits are generated.

2. **QPSK Modulation**  
   Bit pairs are mapped into QPSK symbols.

3. **OFDM Symbol Formation**  
   Symbols are assigned to subcarriers using IFFT.

4. **Channel Noise Addition**  
   AWGN noise is introduced using SNR values.

5. **Feature Preparation**  
   Real and imaginary parts are separated.

6. **Deep Neural Network Model**  
   - Dense layers
   - Activation functions
   - Backpropagation training

7. **Prediction & Detection**  
   Model predicts transmitted symbols.

---

## Technologies Used

- Python  
- Google Colab  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## System Parameters

- Number of Subcarriers: 64  
- Modulation Scheme: QPSK  
- Channel Model: AWGN  
- Samples Generated: 10,000  

---

## Results

The Deep Neural Network successfully learns to detect OFDM symbols under noisy conditions. Detection accuracy improves with training epochs and optimized network parameters.

---

## Applications

- Wireless Communication Systems  
- 5G / 6G Networks  
- Software Defined Radio  
- AI-based Receivers  

---

## Future Scope

- CNN / RNN based detection  
- Real-time SDR implementation  
- MIMO-OFDM detection  
- Low SNR optimization  

---

## Authors

**Ananthukrishna Vinod**\
**Gayatri Kale**\
BTech Electronics & Communication Engineering (AIML)
