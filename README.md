# Multi-class Classification

Welcome to this Notebook of Multi class Classification of Hand Sign! In this Notebook, we will work on a multi-class classification problem. We will be using the [Sign Language MNIST](https://www.kaggle.com/datamunge/sign-language-mnist) dataset, which contains 28x28 images of hands depicting the 26 letters of the english alphabet. To perform Multi-Class Classification we will using CNN(We can also used pretrained models or other Neural Network, it depends upons which models performs better).

Lets have a look at the hand sign.

![](https://i0.wp.com/2.bp.blogspot.com/-kuTY54z70KE/WJs5MW735qI/AAAAAAAAG7c/kfeK6bzIHIEeQgME1j-e-RfzlC0vse3igCLcB/s1600/SignLanguage.gif?ssl=1)

# Description of the Sign-Language MNIST Problem (American Sign Language)

> - American Sign Language (ASL) is a complete, natural language that has the same linguistic properties as spoken languages, with grammar that differs from English. 
> - ASL is expressed by movements of the hands and face. 
> - It is the primary language of many North Americans who are deaf and hard of hearing, and is used by many hearing people as well. 
> - The dataset format is patterned to match closely with the classic MNIST. 
> - Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). 
> - The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. 
> - The original hand gesture image data represented multiple users repeating the gesture against different backgrounds. > - The Sign Language MNIST data came from greatly extending the small number (1704) of the color images included as not cropped around the hand region of interest. 
> - To create new data, an image pipeline was used based on ImageMagick and included cropping to hands-only, gray-scaling, resizing, and then creating at least 50+ variations to enlarge the quantity

![](https://www.researchgate.net/profile/Al-Akoum-2/publication/281580679/figure/fig1/AS:669020042821663@1536518216759/The-26-hand-signs-of-the-ASL-Language.png)

