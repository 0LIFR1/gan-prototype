# Generative Adversarial Networks (GAN) prototype

<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>    
    <li><a href="#about-the-project">About the Project</a></li>
    <li><a href="#implementation">Implementation</a></li>
    <li><a href="#built-with">Built With</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

Project: Training and education<br>
Status: Prototype based on [Deep Learning Cookbook.](https://www.oreilly.com/library/view/deep-learning-cookbook/9781491995839/)

**Summary**:<br>
Generating new icons using deep nets by training two networks, one to generate icons and another to distinguish between generated icons and real icons. The competition between the two leads to better results.

## Implementation

Main tasks:
- Get large set of icons for training, extracted from the Mac application Icons8
- Converting the icons to a Tensor representation by concatenating and normalizing them
- Generate icons using a variational autoencoder
- Improve the autoencoder’s performance by using data augmentation
- Building a Generative Adversarial Network (image generator and an image discriminator working together)
- Training Generative Adversarial Networks (TensorFlow framework to run both networks together)
- Showing the icons the GAN produces by adding an icon renderer after each epoch


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- BUILT WITH -->
## Built With

[![Python][python-shield]][python-url] [![Keras][keras-shield]][keras-url] [![Scikit-learn][scikit-learn-shield]][scikit-learn-url] [![Tensorflow][tensorflow-shield]][tensorflow-url] [![Numpy][numpy-shield]][numpy-url] [![Matplotlib][matplotlib-shield]][matplotlib-url]

<!-- Logo examples
<div>
	<code><img height="50" src="https://user-images.githubusercontent.com/25181517/183914128-3fc88b4a-4ac1-40e6-9443-9a30182379b7.png" alt="Jupyter Notebook" title="Jupyter Notebook" /></code>
	<code><img height="50" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png" alt="Python" title="Python" /></code>
</div>
-->

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[linux-shield]: https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black
[linux-url]: https://www.linux.org/ 
[rstudio-shield]: https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white
[rstudio-url]: https://posit.co/
[jupyter-shield]: https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white
[jupyter-url]: https://jupyter.org/
[python-shield]: https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue
[python-url]: https://www.python.org/
[scikit-learn-shield]: https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white
[scikit-learn-url]: https://scikit-learn.org/stable/
[apache-hadoop-shield]: https://img.shields.io/badge/Apache%20Hadoop-6CF?logo=apachehadoop&logoColor=fff&style=for-the-badge
[apache-hadoop-url]: https://hadoop.apache.org/
[spark-shield]: https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=#E35A16
[spark-url]: https://spark.apache.org/
[cassandra-shield]: https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apache%20cassandra&logoColor=white
[cassandra-url]: https://cassandra.apache.org/_/index.html
[pandas-shield]: https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white
[pandas-url]: https://pandas.pydata.org/docs/index.html
[numpy-shield]: https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white
[numpy-url]: https://numpy.org/
[matplotlib-shield]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[matplotlib-url]: https://matplotlib.org/
[tensorflow-shield]: https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white
[tensorflow-url]: https://www.tensorflow.org/
[keras-shield]: https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white
[keras-url]: https://keras.io/
