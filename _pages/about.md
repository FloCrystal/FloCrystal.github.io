---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div>
<a href="https://flocrystal.github.io/">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&text=Hi,%20I'm%20Ning%20Jiang,%20江宁&fontAlign=50&fontSize=50" 
    alt="Hi, I'm Ning Jiang, 江宁" 
    style="width: 100%; height: auto;"
  >
</a>
</div>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a master's student majoring in Control Science and Engineering at [<img src="../images/NEFU_FLAG.png" alt="NEFU Logo" style="width: 20px; height: auto; vertical-align: middle; margin-right: 5px;">Northeast Forestry University](https://www.nefu.edu.cn/), advised by Prof. [Yining Xie (NEFU, 谢怡宁)](https://ccec.nefu.edu.cn/info/1237/4302.htm).  

My research interests include continual learning and person re-identification. I am still in the initial learning stage of my scientific research and have strong self-motivation. 

If you are seeking any form of **academic cooperation**, please feel free to email me at `jiangning@nefu.edu.cn`

Currently, my total number of citations on Google Scholar is over 200. <a href='https://scholar.google.com/citations?user=XfKD8e8AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FFloCrystal%2Fflocrystal.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations">


# 🔥 News
<style>
/* News section scroll window styles (scoped) */
.news .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.news .scroll-window::-webkit-scrollbar { width: 8px; }
.news .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
</style>



<div class="news" markdown="1">
<div class="scroll-window" markdown="1">
- **2026.01**: &nbsp;🎉🎉 One paper have been accepted by <strong style="color: #990000;">ICLR 2026</strong>! <a href='https://arxiv.org/abs/2505.24449'>Evolving Knowledge Injection</a>!
- **2025.09**: &nbsp;🎉🎉 Our new paper has been accepted by **Sensors**!
- **2024.06**: &nbsp;📣📣 I received my B.E. degree from [Anhui Polytechnic University (AHPU)](https://www.ahpu.edu.cn/), awarded the Outstanding Graduate!
- **2022.10**: &nbsp;🎉🎉 Our new paper has been accepted by **Agriculture**!

</div>
</div>

<script>
(function() {
  function setNewsScrollWindowHeight() {
    var container = document.querySelector('.news .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('li');
    if (!firstLi) return; // fallback to CSS default max-height
    var liRect = firstLi.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = liRect.height + (marginTop + marginBottom);
    var target = perItem * 9; // show ~9 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setNewsScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setNewsScrollWindowHeight, 150);
  });
})();
</script>



# 📝 Publications 
*: Co-First Author (Equal Contribution)

![Agriculture](https://img.shields.io/badge/Agriculture-green) [An Attention Mechanism-Improved YOLOv7 Object Detection Algorithm for Hemp Duck Count Estimation](https://www.mdpi.com/2077-0472/12/10/1659) Kailin Jiang\*, Tianyu Xie, Rui Yan, Xi Wen, Danyang Li\*, Hongbo Jiang, **Ning Jiang**, Ling Feng, Xuliang Duan, Jianjun Wang <b style="color: #ff0000;">【ESI Highly Cited Paper, Editor’s Choice Articles】</b>


![Sensors](https://img.shields.io/badge/Sensors-cyan) [TE-TransReID: Towards Efficient Person Re-Identification via Local Feature Embedding and Lightweight Transformer](https://www.mdpi.com/1424-8220/25/17/5461) Xiaoyu Zhang, Rui Cai, **Ning Jiang**, Minwen Xing, Ke Xu, Huicheng Yang, Wenbo Zhu,  Yaocong Hu

# 📝 Preprints


<style>
/* Section title with blue accent bar */
h2 {
  border-left: 4px solid #4285F4;
  padding-left: 12px;
  margin-left: -16px;
  color: #333;
}
/* Preprints section styles (scoped) */
.preprint { font-family: "Times New Roman", Times, serif; font-size: 0.96em; }
.preprint .bibliography { list-style: none; margin: 0; padding: 0; }
.preprint .bibliography li { margin: 10px 0; }
.preprint .pub-row {
  display: flex;
  gap: 12px;
  align-items: flex-start;
  background: #fff;
  border: 1px solid #eee;
  border-radius: 12px;
  padding: 14px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.06);
  max-width: 900px;
  margin-left: auto;
  margin-right: auto;
}
.preprint .pub-row .abbr.pub-thumb {
  position: relative;
  flex: 0 0 320px;
  max-width: 320px;
  padding: 0 15px; /* keep original padding intent */
}
.preprint .pub-row .abbr.pub-thumb img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 10px 16px rgba(0,0,0,0.12);
}
.preprint .pub-row .abbr.pub-thumb .badge {
  position: absolute;
  top: -8px;
  left: -8px;
  background: #e74d3c;
  color: #fff;
  padding: 4px 8px;
  border-radius: 6px;
  font-weight: 700;
}
.preprint .pub-content { flex: 1 1 auto; padding-left: 4px; }
.preprint .title { font-size: 1.14rem; font-weight: 700; line-height: 1.35; }
.preprint .author { font-size: 0.98rem; }
.preprint .periodical { font-size: 0.96rem; }
.preprint .links a { font-size: 12px !important; }
.preprint .links { margin-top: 10px; display: flex; gap: 10px; flex-wrap: wrap; }
.preprint .pub-button {
  font-family: "Times New Roman", Times, serif;
  background: #fff;
  color: #333;
  border: 1px solid #ddd;
  border-radius: 0;
  padding: 8px 14px;
  font-size: 1rem;
  text-decoration: none;
  box-shadow: 0 4px 12px rgba(0,0,0,0.12);
  transition: transform .05s ease, box-shadow .2s ease, border-color .2s ease;
}
.preprint .pub-button:hover {
  transform: translateY(-1px);
  box-shadow: 0 10px 18px rgba(0,0,0,0.16);
  border-color: #bbb;
  text-decoration: none;
}
.preprint .title a { color: #2a72d4; text-decoration: none; }
.preprint .title a:hover { text-decoration: underline; color: #1e5bb8; }
/* Scroll window to show only a few items initially */
.preprint .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.preprint .scroll-window::-webkit-scrollbar { width: 8px; }
.preprint .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
@media (max-width: 640px) {
  .preprint .pub-row { flex-direction: column; }
  .preprint .pub-row .abbr.pub-thumb { max-width: 100%; flex-basis: auto; }
  .preprint .scroll-window { max-height: 420px; }
}
</style>

<div class="preprint" markdown="1">
<div class="scroll-window">
<ul class="bibliography">

{% for link in site.data.preprint.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr pub-thumb" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width: 100%; height: auto;">
    {% endif %}
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div>
  <div class="col-sm-9 pub-content" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.paper | default: '/404.html' }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em class="conference-name">{{ link.conference }}</em>
      </div>
    <div class="links">
      <a href="{{ link.paper | default: '/404.html' }}" class="pub-button paper" role="button" target="_blank">Paper</a>
      <a href="{{ link.code | default: '/404.html' }}" class="pub-button code" role="button" target="_blank">Code</a>
      <a href="{{ link.website | default: '/404.html' }}" class="pub-button website" role="button" target="_blank">Website</a>
      
<!--      
      {% if link.github_folks %} 
      <a target="_blank" href ="https://github.com/{{ link.github_stars }}"><img alt="GitHub forks" align="right" src="https://img.shields.io/github/forks/{{ link.github_folks }}?style=social"></a>
      {% endif %}
      {% if link.github_stars %} 
      <a target="_blank" href ="https://github.com/{{ link.github_stars }}"><img alt="GitHub stars" align="right" src="https://img.shields.io/github/stars/{{ link.github_stars }}?style=social"></a>
      {% endif %}
-->
      
</div>
</div>
</div>
</li>



{% endfor %}

</ul>
</div>
</div>

<script>
(function() {
  function setScrollWindowHeight() {
    var container = document.querySelector('.preprint .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('.bibliography > li');
    var firstRow = container.querySelector('.pub-row');
    if (!firstRow || !firstLi) return;
    var rowRect = firstRow.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = rowRect.height + (marginTop + marginBottom);
  var target = perItem * 3.5; // show ~3.5 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setScrollWindowHeight, 150);
  });
})();
</script>








<!--
*: Co-First Author (Equal Contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/paper_overview/MMEVOKE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When Large Multimodal Models Confront Evolving Knowledge: Challenges and Pathways](https://arxiv.org/abs/2505.24449)

Kailin Jiang\*, Yuntao Du\*, Yukai Ding, Yuchen Ren, **Ning Jiang**, Zhi Gao, Zilong Zheng, Lei Liu, Bin Li, Qing Li.【2025.3】<br>
[![arXiv](https://img.shields.io/badge/Arxiv-2505.24449-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2505.24449) [![Dataset](https://img.shields.io/badge/%F0%9F%A4%97%20Dataset-EVOKE-blue)](https://huggingface.co/datasets/kailinjiang/EVOKE)   [![code](https://img.shields.io/badge/Code-EVOKE-blue?logo=github)](https://github.com/EVOKE-LMM/EVOKE)  [![website](https://img.shields.io/badge/Website-EVOKE-orange?logo=homepage)](https://evoke-lmm.github.io/) [![Slides](https://img.shields.io/badge/%F0%9F%93%8A%20Slides-EVOKE-BF55EC)](https://evoke-lmm.github.io/EVOKE/slides/When%20Large%20Multimodal%20Models%20Confront%20Evolving%20Knowledge%20Challenges%20and%20Pathways.pdf)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/paper_overview/KORE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[KORE: Enhancing Knowledge Injection for Large Multimodal Models via Knowledge-Oriented Augmentations and Constraints]()

Kailin Jiang, Hongbo Jiang, **Ning Jiang**, Zhi Gao, Jinhe Bi, Yuchen Ren, Bin Li, Yuntao Du, Lei Liu, Qing Li.【2025.9】<br>
[![arXiv](https://img.shields.io/badge/Arxiv-2510.19316-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2510.19316) [![Dataset](https://img.shields.io/badge/%F0%9F%A4%97%20Dataset-KORE-blue)](https://huggingface.co/datasets/kailinjiang/KORE-74K)  [![Model](https://img.shields.io/badge/%F0%9F%A4%97%20Model-KORE-blue)](https://huggingface.co/collections/kailinjiang/kore-68c54e73b6a19eece0fff381) [![code](https://img.shields.io/badge/Code-KORE-blue?logo=github)](https://github.com/KORE-LMM)  [![website](https://img.shields.io/badge/Website-KORE-orange?logo=homepage)](https://kore-lmm.github.io/) [![Slides](https://img.shields.io/badge/%F0%9F%93%8A%20Slides-KORE-BF55EC)](https://kore-lmm.github.io/KORE/slides/KORE.pdf)
</div>
</div>
-->

# 💡 Invention Patents
As these works are patented in China, all these names are directly translated from Chinese.

<div style="max-height: 300px; overflow: auto; font-size: 15px;">
	<ul>
		<li><strong><a href="https://www.patentguru.com/cn/search?q=CN121121638A" target="_blank">Crowd Counting Method Based on Visual State Space Models and Cross-modal Feature Disentanglement</a></strong> (Public, 2025-12-12)<br>
		   Inventor: Yaocong Hu, Xiaoyu Zhang, Rui Cai, <strong><u>Ning Jiang</u></strong>, Minwen Xing, Ke Xu, Wenbo Zhu, Jixing Zhao</li>
		<li><strong><a href="https://www.patentguru.com/cn/CN119445107A" target="_blank">Road Semantic Segmentation Method Based on Lightweight Multi-scale Fusion Transformer</a></strong> (Public, 2025-02-14)<br>
		   Inventor: Yaocong Hu, Mengbo Jia, Pindeng Wang, <strong><u>Ning Jiang</u></strong>, Xiao Liu, Jinwen Hong, Guoyang Wan, Ke Xu, Huicheng Yang</li>
	</ul>
</div>
<!-- <div style="margin-top: 5px; font-size: small; margin-bottom: 0px;">⬆ Scrollable</div>  -->


<span class='anchor' id='honors'></span>


# 📰 Peer Review
- Computers and Electronics in Agriculture Reviewer
  
# 🎖 Honors and Awards

<style>
/* News section scroll window styles (scoped) */
.news .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.news .scroll-window::-webkit-scrollbar { width: 8px; }
.news .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
</style>



<div class="news" markdown="1">
<div class="scroll-window" markdown="1">
- **2025.12** China International College Students' Innovation Competition 2025 - **National Bronze Award**.
- **2024.09** Outstanding Undergraduate Thesis Award by the Anhui Provincial Automation Society.
- **2024.05** Outstanding Graduate of Regular Higher Education Institutions in Anhui Province.
- **2023.09** Top 100 University Students of Anhui Province.
- **2023.04** China International“Internet Plus” College Students’ Innovation and Entrepreneurship Competition - **National Bronze Award**.
- **2022.05** American College Mathematical Contest in Modeling - **Meritorious Winner**.
</div>
</div>

<script>
(function() {
  function setNewsScrollWindowHeight() {
    var container = document.querySelector('.news .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('li');
    if (!firstLi) return; // fallback to CSS default max-height
    var liRect = firstLi.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = liRect.height + (marginTop + marginBottom);
    var target = perItem * 9; // show ~9 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setNewsScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setNewsScrollWindowHeight, 150);
  });
})();
</script>

# 📖 Educations
- **2025.09 - 2028.06**, Master of Control Science and Engineering, Northeast Forestry University, Harbin, China. Supervised by Prof. [Yining Xie](https://ccec.nefu.edu.cn/info/1237/4302.htm).
- **2020.09 - 2024.06**, Bachelor of Automation, Anhui Polytechnic University, Wuhu, China. Supervised by Prof. [Yaocong Hu](https://cee.ahpu.edu.cn/_s31/2023/0918/c2103a200999/page.psp), Prof. [Wei Zhang](https://www.ahpu.edu.cn/slxy/2018/0331/c2715a100596/page.htm), and Dr. [Ke Xu](https://sic.ahpu.edu.cn/2025/0905/c11037a254562/page.htm).


# 🎼 My Favorite Music 
### _Music begins when the language ends._  
<div style="text-align:right;">——Claude Debussy</div>

<script>
  // 页面加载完成后设置音量
  document.addEventListener('DOMContentLoaded', function() {
    var audios = document.getElementsByClassName('myAudio');
    for (var i = 0; i < audios.length; i++) {
                audios[i].volume = 0.3; // 设置音量为30%
            }
  });
</script>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">声生不息·华流季 第7期</div><img src='images/music/孤雏.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[孤雏](https://www.bilibili.com/video/BV1jJvfB7EUL/)
  
李佳薇

<i>声生不息·华流季 第7期</i>

<audio class="myAudio" loop controls>
  <source src="music/孤雏.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">歌手2025 第13期</div><img src='images/music/月半小夜曲.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[月半小夜曲](https://www.bilibili.com/video/BV14wtszKEfB/)
  
BENI/刘惜君

<i>歌手2025 第13期</i>

<audio class="myAudio" loop controls>
  <source src="music/月半小夜曲.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">I AM GLORIA</div><img src='images/music/天空没有极限.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[天空没有极限](https://www.bilibili.com/video/BV1HVeTz4E1E/)
  
G.E.M. 邓紫棋

<i>I AM GLORIA</i>

<audio class="myAudio" loop controls>
  <source src="music/天空没有极限.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">春弦</div><img src='images/music/春弦.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[春弦](https://www.bilibili.com/video/BV1at4y1m7pj/)
  
塞壬唱片-MSR/横山克

<i>春弦</i>

<audio class="myAudio" loop controls>
  <source src="music/春弦.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">东京人寿</div><img src='images//music/东京人寿.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[东京人寿](https://www.bilibili.com/video/BV1UQNdeVETA/) [[🎥 Music Video]](https://y.qq.com/n/ryqq/mv/i0035051z2c)
  
容祖儿

<i>东京人寿</i>

<audio class="myAudio" loop controls>
  <source src="music/东京人寿.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">我们在中场相遇</div><img src='images//music/慢慢喜欢你.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[慢慢喜欢你](https://www.bilibili.com/video/BV1aC411a7Vr/) [[🎥 Music Video]](https://y.qq.com/n/ryqq/mv/l0025kq6ltn)
  
莫文蔚

<i>我们在中场相遇</i>

<audio class="myAudio" loop controls>
  <source src="music/慢慢喜欢你.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Urban Emotions</div><img src='images//music/樱花树下.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

  
[樱花树下](https://www.bilibili.com/video/BV1CT4y1N7PW/) [[🎥 Music Video]](https://y.qq.com/n/ryqq_v2/mv/c0017jd2fd5)
  
张敬轩

<i>Urban Emotions</i>

<audio class="myAudio" loop controls>
  <source src="music/樱花树下.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Binary</div><img src='images//music/喜帖街.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[囍帖街](https://www.bilibili.com/video/BV1PE411P7Qu/) [[🎥 Music Video]](https://y.qq.com/n/ryqq_v2/mv/r0036wb3o3q)
  
谢安琪

<i>Binary</i>

<audio class="myAudio" loop controls>
  <source src="music/喜帖街.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Grace & Charm</div><img src='images//music/前世.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[前世](https://www.bilibili.com/video/BV1J14yzyEa6/) [[🎥 Music Video]](https://y.qq.com/n/ryqq_v2/mv/w0012yu6xcz)
  
陈慧琳

<i>Grace & Charm</i>

<audio class="myAudio" loop controls>
  <source src="music/前世.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">呼吸</div><img src='images//music/词不达意.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[词不达意](https://www.bilibili.com/video/BV1mX4y1h7ye/) [[🎥 Music Video]](https://y.qq.com/n/ryqq_v2/mv/u0017z9zwxw)
  
林忆莲

<i>呼吸</i>

<audio class="myAudio" loop controls>
  <source src="music/词不达意.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</div>
</div>



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map Widget</title>
    <style>
        .map-container {
            width: 300px; 
            margin: 0 auto; 
            text-align: center; 
        }
        .map-container iframe {
            width: 100%; 
            height: 300px; 
        }
    </style>
</head>
<body>
    <div class="map-container">
<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=pBU5rAO3iBww8iWD4RJPnHsAq6uM9LcNALrf0nliRMs&cl=ffffff&w=a"></script>
    </div>
</body>
</html>
