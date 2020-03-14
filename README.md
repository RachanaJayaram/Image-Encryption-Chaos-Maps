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

![Original Image](graphs/orig.png)


### Encrypted Images

### Image after Arnold Cat Encryption

![Arnold cat encryption](graphs/arnoldcatencryption.png )
### Image after Henon Map Encryption

![Henon Map Encryption](graphs/henonencryption.png )
### Image after Logistic Map Encryption

![Logistic Map Encryption](graphs/logisticencryption.png)

# Intensity Histogram


![Intensity Histogram - Original Image](graphs/arnoldcathist.png)

![Intensity Histogram - Arnold Cat](graphs/arnoldcatencryptionhist.png)

![Intensity Histogram - Henon Map](graphs/henonencryptionhist.png)

![Intensity Histogram - Logistic Map](graphs/logisticencryptionhist.png)

# Adjacent Pixel Autocorrelation


![Adjacent Pixel Autocorrelation - Original Image](graphs/arnoldcatauto.png)

![Adjacent Pixel Autocorrelation - Arnold Cat](graphs/arnoldcatencryptionauto.png)

![Adjacent Pixel Autocorrelation - Henon Map](graphs/henonencryptionauto.png) 

![Adjacent Pixel Autocorrelation - Logistic Map](graphs/logisticencryptionauto.png)

# Key Sensitivity
## Henon Map
### Original Image

![Original Image](graphs/orig.png)

### Encrypted with key = 20
![Arnold cat encryption](graphs/arn20.png)

### Decrypted with key = 19

![Arnold cat encryption](graphs/arn19.png)

## Arnold Cat
### Original Image

![Original Image](graphs/orig.png)

### Encrypted with key = 20
![Arnold cat encryption](graphs/arn20.png)

### Decrypted with key = 19

![Arnold cat Decryption](graphs/arn19.png)

## Henon Map
### Original Image

![Original Image](graphs/orig.png)

### Encrypted with key = (0.1, 0.1)
![Henon Map encryption](graphs/hen01.png)

### Decrypted with key = (0.1, 0.101)

![Henon Map Decryption](graphs/hen0101.png)

## Logistic Map
### Original Image

![Original Image](graphs/orig.png)

### Encrypted with key = "supersecretke"
![Logistic Map encryption](graphs/ssk.png)

### Decrypted with key = "supersecretke"

![Logistic Map Decryption](graphs/ssk_wrong.png)

