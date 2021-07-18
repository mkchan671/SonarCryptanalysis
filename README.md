<!-- PROJECT SHIELDS -->
[![LinkedIn][linkedin-shield]][linkedin-url]

# Active acoustic cryptanalysis on smartphone
<!-- TABLE OF CONTENTS 
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>
-->

<!-- ABOUT THE PROJECT -->
## About The Project
Final Year Project during study for BScEng Computer Science in City University of Hong Kong

What is Active acoustic cryptanalysis?

A normal side channel attack, is to collect signal emit from victim source, in a passive methodology. In Active form, there will be a device to emit a designated signal to collect the victim's interaction data. After collecting the interaction data, the data will be anaylsed, could be assisted Machine Learning.

This project was inspired from [SonarSnoop](https://arxiv.org/abs/1808.10250) a research study on acoustic system of a smartphoe can be turned into a mobile sonar system; researchers from Cornell University have proven that sensitive information like lock patterns could be stolen on air.

2 movements could be analysed from the developed system:

1. Air/Off-screen gesture:
<img src="https://github.com/mkchan671/SonarCryptanalysis/blob/a3892bdb8a4a83a186b33c55dbc928b27bdbcc93/Air%20gesture.gif">
The propagated signal analysed by mobile app only.

2. PIN code stealing/guessing:

After victim input the pin

<img src="https://github.com/mkchan671/SonarCryptanalysis/blob/37d63571cb963b98f794fd6e52caac08cae5b0f0/pin-input.gif">

Server will received and prcossed the data, and return prediction from trained model

<img src="https://github.com/mkchan671/SonarCryptanalysis/blob/17f17865516830d3868a486a27b852a29ffb43c5/Pin-Prediction.png">

### Built With

This project was majorly depends on:
Mobile App:
* Android studio - Java

Machine Learning Server side:
Hardware used during Data colleting stage:
* Samsung Galaxy S7
* [NVIDIA Jetson Nano 2GB Developer Kit](https://developer.nvidia.com/embedded/jetson-nano-2gb-developer-kit)

Python IDE:
* Jupyter

Python packages used:
Web server:
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)

Signal Processing (Raw audio -> image -> feature extraction):
* [Librosa - Audio Processing](https://librosa.org/)
* [Numpy](https://numpy.org)
* [OpenCV](https://opencv.org/)

Dataset manipulation:
* [Pandas](https://pandas.pydata.org/)

Machine Learning data analysis tools:
* [Scikit-learn](https://scikit-learn.org/stable/)

System Overview:
<p>
<img src="https://github.com/mkchan671/SonarCryptanalysis/blob/41b0fe5b200a868935947c3425d3c77835315b49/SystemOverview.jpg">
<!--
<!-- GETTING STARTED --
## Getting Started


### Prerequisites


### Installation


<!-- USAGE EXAMPLES --
## Usage
-->

<!-- CONTACT -->
## Contact
Robert Chan- [LinkedIn: robchan3](https://www.linkedin.com/in/robchan3/) - [E-mail: mkchan671@hotmail.com.hk](mailto:mkchan671@hotmail.com.hk)
<!-- ACKNOWLEDGEMENTS 
## Acknowledgements-->
<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]:https://www.linkedin.com/in/robchan3/
