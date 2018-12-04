---
layout: page
---

<h3><b>See In The Dark</b></h3>
Image Processing Project along with R. Shrinivas

[Link to project report](https://drive.google.com/file/d/197rulD8Zi53JZjOPDQwWhbxyBgTdWtoS/view?usp=sharing)

***Abstract*** — See In The Dark presents a method to reconstruct bright images from images shot in low-light conditions Due to limitations in exposure time and aperture size, images shot in low-light conditions have very little detail and poor SNR. Increasing their brightness leads to enhancement of noise in the image. Our project presents an end-to-end low-light image brightnening system using a Conditional Generative Adversarial Network (cGAN). We have implemented and trained the GAN ourselves, and have also proposed a modified ”soft” sigmoid activation function to prevent GAN collapse. We present the applications of low-light imaging, its challenges, traditional approaches and their limitations. Then we present our method - its architecture, dataset used and a summary of its results.
![](cGAN.png)
<p align="center"><em>Overview of our cGAN architecture</em></p>

<p align="center"><em>Few of our results - Low light image, result image, ground truth image</em></p>
<table>
	<tr>
		<td>Low light image</td>
		<td>Result image</td>
		<td>Ground truth image</td>
	</tr>
	<tr>
		<td><img src="dark1.png"></td>
		<td><img src="result1.png"></td>
		<td><img src="gt1.png"></td>
	</tr>
	<tr>
		<td><img src="dark2.png"></td>
		<td><img src="result2.png"></td>
		<td><img src="gt2.png"></td>
	</tr>
	<tr>
		<td><img src="dark3.png"></td>
		<td><img src="result3.png"></td>
		<td><img src="gt3.png"></td>
	</tr>
	<tr>
		<td><img src="dark4.png"></td>
		<td><img src="result4.png"></td>
		<td><img src="gt4.png"></td>
	</tr>
	<tr>
		<td><img src="dark5.png"></td>
		<td><img src="result5.png"></td>
		<td><img src="gt5.png"></td>
	</tr>
</table>