# KaliYuga' Library of Historic AI Tools
A collection of all the open-source AI tools I can wrest from the jaws of possible internet oblivion. Based on my post found [here](https://archive.is/D7qgR#selection-793.0-819.13): 

**Table of Contents**
1. The Big Sleep
2. VQGAN + Clip
2a. VQGAN+CLIP with Video Features
3. Clip-Guided Diffusion
4. Styledream Notebook
5. Pixray PixelDraw
6. Real-ESRGAN Practical Image Restoration
7. ruDALLE 
8. Looking Glass AI
9. JAX Clip-Guided Diffusion 
10. CLIP Guided Deep Image Prior
11. Disco Diffusion 
12. Disco Diffusion Turbo 
------

###### 1. The Big Sleep

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/242NqmKZ2GF2uWUi5oKVz9WVYAuWeysCEcQL2Ry4iDJXTZ8SB9CoN6cJEYgStNqDAcvjs.png)
***A Beautiful House*** *by BigSleep*

> **Description:** The original Clip-guided AI Colab tool; uses [Clip](https://openai.com/blog/clip/) to guide [BigGAN](https://paperswithcode.com/method/biggan). Fairly outdated, but absolutely foundational to the entire art field.
**Author**: Ryan Murdock ([advadnoun](https://twitter.com/advadnoun) on Twitter)
**[Notebook Link](https://colab.research.google.com/drive/1NCceX2mbiKOSlAd_o7IU7nA9UskKN5WR)**
-------------------------
###### 2. VQGAN + Clip

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/AK3dd7kqJJm3zX9rPGkS5dJ3nDsg7aERMfasPfoqKcKHRkEdmfpAminfMBUCxzP.png)
***Gordian Gallery*** *by KaliYuga, 2021*
> **Description:** ~~By far the most widely-used of the Clip-guided methods~~ [**Edit April 2022**: very few people still seem to use this tool, but it's a foundational and very important one]; uses Clip to guide [VQGAN](https://www.analyticsvidhya.com/blog/2021/07/understanding-taming-transformers-for-high-resolution-image-synthesis-vqgan/).
**Author:** Katherine Crowson ([RiversHaveWings](https://twitter.com/RiversHaveWings) on twitter)
**[Notebook Link](https://colab.research.google.com/drive/1go6YwMFe5MX6XM9tv-cnQiSTU50N9EeT#scrollTo=g7EDme5RYCrt)** (The notebook is in Spanish, but is easily translated to English using Chrome).
------------------
###### 2a. VQGAN+CLIP with Video Features
> **Description:** What it says on the tin! VQGAN + Clip with added video features and also some really good demystifications of parameters. 
**Author:** @jotakrevs 
**[Notebook Link](https://colab.research.google.com/drive/1gkLw_nJNAjEWAflAXRvK2BiMGYKIosnJ?usp=sharing)**
-------------------------

###### 3. Clip-Guided Diffusion

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/AK7sQBYLsfm6vzSRjXBJJ1P9rvqFmZeXK2yeNX4Rkv5qmXwnH8SUir9mrjtavqE.png)
***Psychic Sermon in the Temple of the Mind*** *by KaliYuga, 2021*
> **Description:** Produces absolutely unbelievable results, but very slow and resource-heavy. Uses Clip to guide a [Diffusion model](https://lilianweng.github.io/lil-log/2021/07/11/diffusion-models.html).
>**Author:** Katherine Crowson ([RiversHaveWings](https://twitter.com/RiversHaveWings) on twitter)
>**[Notebook Link](https://colab.research.google.com/drive/12a_Wrfi2_gwwAuN3VvMTwVMz9TfqctNj)**

-----------------------
###### 4. Styledream Notebook

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/AK3eaNPY1DdSbXWJnoZHTHvJzbY7Pw6iNECgn4n9L7FQErgoPamy8Cg2Zcnspk8.jpg)
***Portraits of DC heroes in the style of Alex Ross*** *by [.hack//HAMBRE](https://twitter.com/hambrehoy/status/1444992504605118468?s=20)

> **Description:** Portraits only! Clip-guided [StyleGAN](https://en.wikipedia.org/wiki/StyleGAN) model.
>**Author:** Ariel Ekgren ([ArYoMo](https://twitter.com/ArYoMo) on twitter)
>**[Notebook Link](https://colab.research.google.com/github/ekgren/StructuredDreaming/blob/main/colabs/Structured_Dreaming_Styledreams.ipynb)**
--------------
##### 5. Pixray PixelDraw

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/EoCbSoG2P5fu6H83YhCSrRLuNMJ5B2aRdQKF27AwEJPzLgfom4FD2WHbrB2fwStP7Wy.png)
***A synthwave great white shark*** *by [Viktor Alm](https://twitter.com/ViktorAlm)*

> **Description:** A fork of [NerdyRodent's fork](https://colab.research.google.com/drive/1ZAus_gn2RhTZWzOWUpPERNC0Q8OhZRTZ) of RiversHaveWings'VQGAN + Clip Notebook; uses VQGAN + Clip to produce pretty impressive pixel art. 
>**Author:**[Dribnet](https://twitter.com/dribnet)
>**[Notebook Link](https://colab.research.google.com/github/ekgren/StructuredDreaming/blob/main/colabs/Structured_Dreaming_Styledreams.ipynb)**
**Extra!** You can also start with an initial image in a [different version of Pixray](https://colab.research.google.com/github/dribnet/clipit/blob/master/demos/PixelDrawer_Init_Image.ipynb); if you use an image originally created by pixray, the results can be pretty trippy! For example:

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/EoCgjEYPP8zAScAqgCRe6Yi5MXnxcnc37xJiPP3msaHktL9bQDKooQtHhMwfEy1eoJ9.png)
*Via the Colab Notebook's demo params*

>Other bits and pieces of this project can be found [here](https://github.com/ViktorAlm/clipit/blob/master/demos/README.md).
-------------
##### 6. Real-ESRGAN Practical Image Restoration

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/Ep1Zm71k9b9FqjYTZAzLitFpZirKkFC88Gbv6J1SKPGcAZke5SbmEo4JmPXdn9rvBKX.png)
*Examples via the Colab Notebook*

> **Description:** A demo of [Real-ESRGAN](https://arxiv.org/abs/2107.10833),which repairs many types of image degradation and also upscales the image 4x.
>**Authors:** Xintao Wang, Liangbin Xie, Chao Dong, Ying Shan
>**[Notebook Link](https://colab.research.google.com/drive/1k2Zod6kSHEvraybHl50Lys0LerhyTMCo)**
-------------
##### 7. ruDALLE

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/23uQi7iSs1MA5X7Npek2FSn3mqwagxuNLvKC94oRrtDfw8CNVyX43fR7wkAcybW8YRLsK.png)

> **Description:** A Fully-Trained, Accessible, Multi-Billion-Parameter Answer to OpenAI's DALL-E Model (in Russian)
**Authors:**  [Sber AI](https://github.com/sberbank-ai) and [Sber Devices](https://sberdevices.ru/)
**[Notebook Link](https://colab.research.google.com/drive/1wGE-046et27oHvNlBNPH07qrEQNE04PQ?usp=sharing)**
**Bonus:** [A faster Colab notebook for free users](https://colab.research.google.com/drive/1hISCwHyTBj7WwO4LK_pPcEf0I1vyMk6g?)
-------------
##### 8. Looking Glass AI

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/23uR9bgbqCTNB8vPkzDToHjbtyvx6XYrv6BPJkW4FAjt3KyRpgpxfgp8tVj7v9pFvga3x.png)
*"Untitled" by KaliYuga, 2021*
> **Description:** An Accessible One-Shot Finetuner For RuDalle
**Authors:**  [AI_Curio](https://twitter.com/ai_curio) and Others
**[Notebook Link](https://colab.research.google.com/drive/15vFLeepkSTr1qd4xs31g9kMEiwkWP0sh)**
-------------
##### 9. JAX Clip-Guided Diffusion

https://files.peakd.com/file/peakd-hive/kaliyuga/Ep3eMa4ioSQuG7mfrXBzwPsDe9wuNCG9sznjSWSE9eVHNXr8duCE4EN3fxbHZ8zAgdx.png
*By KaliYuga, February 2022*
> **Description:** [Via Gituhub] "The models are denoising diffusion probabilistic models (https://arxiv.org/abs/2006.11239), which are trained to reverse a gradual noising process, allowing the models to generate samples from the learned data distributions starting from random noise."
**Authors:**  [Katherine Crowson](https://twitter.com/rivershavewings) and [John David Pressman](https://twitter.com/jd_pressman)
**[Notebook Link](https://colab.research.google.com/drive/1tgM0sI6suaaBEfYZwMEDzgsjnizuf5UC)**
-------------
##### 10. CLIP Guided Deep Image Prior

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/AJdEeeCypMCuCFuTfNqyr388GFrveLEhYRwGLEFTVbce59xZZgHPKC3MxvRfX8T.png)
*By KaliYuga, February 2022*
> **Description:** Creates soft, print-like images quite unlike what you generally get out of other CLIP-guided diffusion models
**Authors:**  [Daniel Russell](@danielrussruss), based on work by [Katherine Crowson](https://twitter.com/rivershavewings) and [Ryan Murdock](https://twitter.com/advadnoun)
**[Notebook Link](https://colab.research.google.com/drive/1_oqIK8A67EgtJDdfsuJojc5ukNzirdle)**
-------------
##### 11. Disco Diffusion

![image.png](https://files.peakd.com/file/peakd-hive/kaliyuga/24244MjV8agKh57NNn43YaD4pv51zbwoneuYbtQL4boXN8cfBEtJuWzqB9xMREZe3WxiM.png)
*By KaliYuga, March 2022*
> **Description:** My daily drive; Very high quality image results very quickly; comes fully loaded with 3D animation capabilities and the latest Clip models. 
**Authors:**  [Somnai](https://twitter.com/Somnai_dreams) and [Adam Letts](https://twitter.com/gandamu_ml)
**[Notebook Link](https://colab.research.google.com/github/alembics/disco-diffusion/blob/main/Disco_Diffusion.ipynb)**
------------
##### 12. Disco Diffusion Turbo
https://twitter.com/KaliYuga_ai/status/1502057904693723137?s=20&t=MLWq2-K9-Rc7Bu5IN9wZWg

> **Description:** A fork of Disco which speeds up and cleans up 3D animation significantly. I also use this all the time! 
**Author:**  [Chris Allen](https://twitter.com/zippy731)
**[Notebook Link](https://colab.research.google.com/github/zippy731/disco-diffusion-turbo/blob/main/Disco_Diffusion_v5_Turbo_%5Bw_3D_animation%5D.ipynb)**
**Bonus** by Chris Allen Notebook: [Wiggle Standalone Keyframe Generator](https://colab.research.google.com/github/zippy731/wiggle/blob/main/Wiggle_Standalone_5_0.ipynb); lets you generate keyframe instructions that give you fine control over Turbo's motion.
