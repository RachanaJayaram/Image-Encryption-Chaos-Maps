# Image Encryption using Chaos Maps
This is a project in cryptography that involves implementing image encryption using various chaos maps and comparing their merits based on key sensitivity, adjacent pixel autocorrelation and intensity histograms. The chaos maps implemented were - Arnold cat maps, Henon maps and Logistic chaos maps.
<br>

<b> What are chaos maps? </b>
<br>
Chaotic systems are a simple sub-type of nonlinear dynamical systems. They contain a few interacting parts which follow simple rules, but these systems are characterized by a very sensitive dependence on their **initial conditions**. Despite their deterministic simplicity, over time these systems can display and divergent behavior.

<br>

**Why Chaos Maps for encryption?**
<br>
Traditional encrypting mechanisms AES and RSA exhibit some drawbacks
and weakness when it comes to encryption of digital images 
  and high computing

*   Large computational time for large images
*   High computing power for large images
Consequently, there might be better techniques for image encryption.

<br>

A few chaos based algorithms provide a good combination of speed, high security complexity, low computational overheads 
Moreover, **certain** chaos-based and other dynamical systems based algorithms have many important properties such as 

*   sensitive dependence on initial parameters
*   pseudorandom properties
*   ergodicity
*   non periodicity
# Images
### Original Image

![Original Image](https://drive.google.com/uc?id=1Djfm4PqE7Su4WqEdZKiGL-8HtrbVBuMm "Original Image")


### Encrypted Images

### Image after Arnold Cat Encryption

![Arnold cat encryption](graphs/arnoldcatencryption.png "Arnold cat encryption")
### Image after Henon Map Encryption

![Henon Map Encryption](graphs/henonencryption.png "Arnold cat encryption")
### Image after Logistic Map Encryption

![Logistic Map Encryption](graphs/logisticencryption.png "Arnold cat encryption")

### Original Image

![Original Image](https://drive.google.com/uc?id=1Djfm4PqE7Su4WqEdZKiGL-8HtrbVBuMm "Original Image")

# Intensity Histogram

### Intensity Histogram - Original Image

![Intensity Histogram - Original Image](graphs/arnoldcathist.png "Intensity Histogram - Original Image")
### Intensity Histogram - Arnold Cat

![Intensity Histogram - Arnold Cat](graphs/arnoldcatencryptionhist.png "Intensity Histogram - Arnold Cat")
### Intensity Histogram - Henon Map

![Intensity Histogram - Henon Map](graphs/henonencryptionhist.png "Intensity Histogram - Henon Map")
### Intensity Histogram - Logistic Map

![Intensity Histogram - Logistic Map](graphs/logisticencryptionhist.png "Intensity Histogram - Logistic Map")



