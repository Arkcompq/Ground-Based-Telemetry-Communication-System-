Ground-based telemetry systems facilitate the remote transmission of sensor or control data between fixed 
terrestrial stations such as weather observatories, industrial plants, or centralized control hubs. These 
systems typically operate over RF or wireless links, which are vulnerable to interference, noise, and 
bandwidth constraints. Unlike satellite-based communication, terrestrial systems must address more 
localized and persistent signal degradation. To ensure reliable data transfer under such conditions, efficient 
modulation and encoding techniques are essential. This project explores methods to improve the resilience 
and accuracy of ground telemetry systems. 

To achieve reliable communication, the project incorporates Pulse Code Modulation (PCM) for digitizing 
analog sensor data and Quadrature Phase Shift Keying (QPSK) for bandwidth-efficient modulation. PCM 
converts analog signals, such as temperature or pressure readings, into binary sequences suitable for digital 
processing and transmission. QPSK, a digital modulation scheme, enhances spectrum efficiency by 
transmitting two bits per symbol, thus reducing bandwidth requirements. This integration helps in 
overcoming noise and channel limitations. The system is evaluated in a simulated Additive White 
Gaussian Noise (AWGN) environment to mimic real-world channel conditions. 

The study compares two models: a basic PCM-only system and an enhanced PCM+QPSK system, both 
implemented and analyzed using Scilab. By comparing Bit Error Rate (BER) and Mean Squared Error 
(MSE) across the two systems, we assess the improvement offered by modulation. The PCM+QPSK 
model demonstrates better performance under noisy conditions, validating the advantage of combining 
digital modulation with traditional encoding. Using Scilab allows for accurate simulation without 
hardware dependencies, making it ideal for educational and research-focused telemetry system 
development. 
