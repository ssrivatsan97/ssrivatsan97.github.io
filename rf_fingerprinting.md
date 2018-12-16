---
layout: page
---

<h3><b> RF Fingerprinting Based Authentication for Bluetooth Low Energy </b></h3>
Internship project in the [Energy Efficient Circuits and Systems group](http://www-mtl.mit.edu/researchgroups/icsystems/) at the Massachusetts Institute of Technology<br/>
Mentored by Mohamed Radwan Abdelhamid, [Prof. Anantha Chandrakasan](https://mtlsites.mit.edu/users/anantha/index.html)

[Link to project presentation](rf_fingerprinting.pdf)
Several IoT devices operate under energy constraints because of limited battery life. This is important in applications such as in-body medical sensors where the battery cannot be replaced. To save energy, the group has developed a BLE-compliant wake-up receiver. This receiver stays in a low-power dormant state until it is woken up when it receives a fixed sequence of bits called the wake-up pattern. Such a receiver is vulnerable to a battery drainage attack where a rogue transmitter repeatedly sends the wake-up pattern to drain the receiver's battery. We attempt to use RF fingerprinting as a low-power method to authenticate the transmitter, and accept wake-up patterns from authorized transmitters only. 

My implementation has a signal preprocessing stage where the received RF signal is downconverted to IF, downsampled and then a Continuous Wavelet Transform (CWT) is applied. A neural network with a single hidden layer is used to classify the transmitter from the extracted features. To reduce the energy consumption of the authentication system, the weights and features were quantized to 8 bits without loss in accuracy. Other methods such as Principal Component Analysis (PCA) and Convolutional Neural Networks (CNN) were also experimented with. Achieved an average classification accuracy of around 90% when trained and tested on 10 BLE transmitters.