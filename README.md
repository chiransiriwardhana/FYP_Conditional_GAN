#  Final year project Conditional GAN
 This is Conditional Generative Adversarial Network for removing noises from NIC images
 
 
 Output images at epoch 300
 ![image_at_epoch_0300](https://user-images.githubusercontent.com/47823522/146335467-aa869831-b36a-44b9-9a1a-3e724c8a5a4c.png)
                                            Fig.1
 
 
 Output images at epoch 3
 
 
 ![image_at_epoch_0003_edited](https://user-images.githubusercontent.com/47823522/146335429-1d21ab07-aef3-4274-bbb1-d4c152e9d087.png)
 
 
                                            Fig.2
 
An example of noisy image and corresponding generated(noise-less) image. In this images, gray color in bottom image corresponds to synthetic noise, I added.So, This CGAN removes   synthetic noise added at pre-processing stage. When training to remove sysnthetic noise, CGAN model network weights are adjuested. So if we provide new image like fig 4, it removes noises in fig 4.


![noise_rmoving](https://user-images.githubusercontent.com/47823522/146335518-4d041b9c-7b2b-4133-8da9-686f25092ff9.png)
                                            Fig.3

![original](https://user-images.githubusercontent.com/47823522/146336746-3f8fe519-a89a-4a2d-8d2e-caded221b5bc.PNG)
                                            Fig.4
