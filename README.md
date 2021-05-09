# CAPTCHA Generator using Machine Learning
Generative Adversarial Network trained to generate CAPTCHA Codes. 

Demo: https://dencim.github.io/CAPTCHA_Generator_ML/

Some Captcha codes created by the network:
![Demo 1](/images/demo1.jpg)  |  ![Demo 2](/images/demo2.jpg)
:-------------------------:|:-------------------------:
![Demo 3](/images/demo3.jpg)  |  ![Demo 4](/images/demo4.jpg)

## Architecture
The network was trained using the MNIST dataset and uses a Generative Adversarial Network as seen in the picture below. It outputs images similar to pictures it trained on but not identical. This is useful because it often generates an image that looks like a combination of multiple numbers or letters and would ideally be easy for humans to classify but difficult for a machine (a property CAPTCHA codes need). Since the network was trained to ideally generate difficult images, it is common to generate unreadable codes and sometimes codes that are too simple. To use effectively, one must generate multiple codes and manually pick good ones.

![Architecture](/images/arch.png)

