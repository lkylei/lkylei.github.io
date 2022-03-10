---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="row">
<div id="about" class="left">
I am a staff Machine Learning Engineer at PayPal. I am currently working on deep learning models, particular in transfer learning, few-shots learning and multi-task learning for NLP applications. I am passionate about applying deep learning algorithms to solve real-world problems.  Prior to that, I obtained my Ph.D in Computer Science and Engineering from Penn State University. I was working with Prof. Daniel Kifer and Prof. Zhenhui Li on machine learning algorithms in outlier detection & explanation, differential privacy and computational social science.
</div>
<div id="image" class="right">
<img class="center" width="100%" src="/images/homepage-removebg_crop.png">
</div>
</div>

<style>
.row {
  display: inline-flex;
}

.left {
  flex: 100%;
}

.right {
  flex: 0%;
}

@media screen and (max-width: 768px) {
.row {
   display: block;
}
.center {
  width: 60%;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  justify-content: center;
}

</style>

<script>
const about = document.getElementById('about');

const image = document.getElementById('image');

// ✅ Show hidden DIV on hover
about.addEventListener('mouseover', function handleMouseOver() {
  about.style.flex = '80%';
  image.style.flix= '20%';

  // 👇️ if you used visibility property to hide div
  // hiddenDiv.style.visibility = 'visible';
});

// ✅ (optionally) Hide DIV on mouse out
about.addEventListener('mouseout', function handleMouseOut() {
  about.style.flex = '100%';
  image.style.flix= '0%';

  // 👇️ if you used visibility property to hide div
  // hiddenDiv.style.visibility = 'hidden';
});
</script>

[homepage]: /images/homepage-removebg.png
{: width="300px"}

[pdf]: https://i.imgur.com/n1WLcBI.png
{: width="50px"}

[slide]: https://i.imgur.com/hQPyFHg.png
{: width="50px"}

[poster]: https://i.imgur.com/VNINQ4E.png
{: width="60px"}

[data]: https://i.imgur.com/Et7tJqY.png
{: width="50px"}

[code]: https://i.imgur.com/rMo1TrV.png
{: width="50px"}

[youtube]: https://i.imgur.com/9oPapf2.png
{: width="20px"}

[paypal]: https://i.imgur.com/t7Vpl6o.png
{: width="90px"}

[psu]: https://i.imgur.com/ymfHZg1.png
{: width="100px"}

[ntnu]: https://i.imgur.com/yz3EIhF.png
{: width="120px" style="margin:5px"}

---

Experience
======

![paypal]
* Member of Technial Staff. PayPal. San Jose. 2019.02 ~ Present
* Ph.D Intern. PayPal. San Jose. 2017.05 ~ 2017.08

Education
======

![psu]
* Ph.D. in Computer Science, Pennsylvania State University, University Park, PA, USA. 2012 ~ 2018

![ntnu]
* Bachelor in Computer Science and Information Engineering , National Taiwan Normal University, Taipei, Taiwan. 2008 ~ 2012


Publications
======

* Network spillovers and neighborhood crime: A computational statistics analysis of employment-based networks of neighborhoods. Corina Graif, Brittany Freelin, **Yu-Hsuan Kuo**, Hongjian Wang, Zhenhui Li, Daniel Kifer. **Justice Quarterly**, 2021. [![pdf]
](https://yzk5145.github.io/files/crime.pdf)
* Singling-Out vs. Blending-In: Outlier Detection and Differential Privacy in Data. **Yu-Hsuan Kuo**. The Pennsylvania State University, 2019 [![slide]
](https://yzk5145.github.io/files/thesis_slides_kuo.pdf)
* [A simple baseline for travel time estimation using large-scale trip data](https://dl.acm.org/doi/10.1145/3293317). Hongjian Wang, Xianfeng Tang, **Yu-Hsuan Kuo**, Daniel Kifer, and Zhenhui Li. ACM Transactions on Intelligent Systems and Technology (**TIST**), 2019 [![pdf]](https://dl.acm.org/doi/files/10.1145/3293317)
* [Differentially Private Hierarchical Count-of-Counts Histograms](https://dl.acm.org/doi/10.14778/3236187.3236202). **Yu-Hsuan Kuo**,  Cho-Chun Chiu, Daniel Kifer, Michael Hay, Ashwin Machanavajjhala. Proceedings of the International Conference on Very Large Data Bases (**VLDB**), 2018. [![pdf]](http://www.vldb.org/pvldb/vol11/p1509-kuo.pdf) [![slide]](https://yzk5145.github.io/files/vldb_slides.pdf) [![code]](https://github.com/yzk5145/coco)[![poster]](https://yzk5145.github.io/files/vldb_poster.pdf)
* [Detecting Outliers in Data with Correlated Measures](https://dl.acm.org/doi/10.1145/3269206.3271798). **Yu-Hsuan Kuo**, Zhenhui Li, Daniel Kifer. Proceedings of the International Conference on Information and Knowledge Management (**CIKM**), 2018. [![pdf]](https://dl.acm.org/doi/files/10.1145/3269206.3271798) [![slide]](https://yzk5145.github.io/files/cikm_slides.pdf) [![data]](https://github.com/yzk5145/outlier-detection)
* [A Simple Baseline for Travel Time Estimation using Large-Scale Trip Data](https://dl.acm.org/doi/abs/10.1145/2996913.2996943)**. Hongjian Wang, **Yu-Hsuan Kuo**, Daniel Kifer, Zhenhui Li. ACM International Conference on Advances in Geographic Information Systems (**SIGSPATIAL**), 2016. [![pdf]](https://yzk5145.github.io/files/travel-time.pdf)
* [Exploring Technological Trends for Patent Evaluation](https://ieeexplore.ieee.org/document/7058085). Shuting Wang, Wang-Chien Lee, Zhen Lei, Xianliang Zhang and **Yu-Hsuan Kuo**. The International Conference on Data Science and Advanced Analytics (**DSAA**), 2014 [![pdf]](https://yzk5145.github.io/files/trend.pdf)

Patents
======

* [Systems and Methods for Predicting and Providing Automated Online Chat Assistance](https://patentimages.storage.googleapis.com/e8/7f/9a/3e6c82bafaa878/US20210125025A1.pdf). **Yu-Hsuan Kuo**, Venkata Ramana Nadimpalli. Application Number: 16/665,709

# Selected Talks
* Predicting and Mining Customer's Intent: Challenges and Techniques. Stanford's Global Women in Data Science (WiDS) in the Eastern region. 2021.04 [![youtube]]()



Teaching
======

* CMPSC 465 Data Structure and Algorithms. Teaching Assistant at Penn State University. *Fall 2018*
* CMPSC/MATH 451 Numerical Computations. Teaching Assistant at Penn State University. *Fall 2013*
* Introduction to Programming in C. Teacher at the Affiliated Senior High School of National Taiwan Normal University. *Spring 2012*

Misc
======

* Mentor the Valley Consulting Group at UC Berkeley's campus on ``Market Research``.  Spring 2019.
* I am a principal cellist of PSU Campus Orchestra. Fall 2015 and Spring 2016.
