# An analysis of Image Cryptosystem
The goal of the research paper is to encrypt and decrypt images of different sizes using the RSA , chaos based RSA and the AES algorithm. We will analyze the efficiency of encryption 
and decryption. In addition to the efficiency, we will analyze if there is any data lost in the decrypted images i.e if the decrypted gray or color image comes 
out to be exactly as the corresponding original image. 

# Our Goal
This project will use different images with same size and dimention to encrypt and decrypt using two algorithms, traditional RSA and Chaos-based RSA. It will find the encryption time and decryption time of those images. Then it will compare the time, space and security complexity of each algorithm based on the generated data. Lastly, it will give the most efficient algorithm to encrypt and decrypt images.


# Our Findings


![Our RSA Encrypted System](https://github.com/farahh001/CSc-486-ComplexityTheory-Final-Project/blob/main/images/RSA_ENC_DEC.png)

Here is the demonstation of the above image, the sender encrypted an image using a public key that is known to all, then the encrypted image send to the receiver. After that the receiver decrypt the image with the private key, which is known only by the owner.

![Size Comaparison](https://github.com/farahh001/CSc-486-ComplexityTheory-Final-Project/blob/main/images/RSAvsChaos.png)


The above graph shows the comparison between the original image size and encrypted image size using the regular RSA algorithm and the Chaos-based RSA algorithm. When the image is encrypted, the size of the image gets larger. And overall, the Chaos-based RSA takes more space than the regular RSA.


![Encryption](https://github.com/farahh001/CSc-486-ComplexityTheory-Final-Project/blob/main/images/TimingEnc.png)

Above graph illustrate the time comparison between regular RSA and the Chaos-based RSA. The images that we used, we got that the result that Chaos-based algorithm takes much less time than the regular RSA.


![Decryption](https://github.com/farahh001/CSc-486-ComplexityTheory-Final-Project/blob/main/images/TimingDec.png)

The graph shows the decrypted time of the regular RSA method and the Chaos-based RSA method. For this, experiment, we used the same encrypted images with the same size (250 x 250) and dimension (2D). And we got the result that the Chaos-based RSA algorithm takes much less time than regular RSA. That means the Chaos-based RSA algorithm is faster in decryption.
