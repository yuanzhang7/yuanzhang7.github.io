---
layout: homepage
---

<h1 id="about-me"></h1>

<h2 style="margin: 60px 0px 10px;">YUAN ZHANG</h2>

I am currently a Ph.D. student in the Department of Computer Science at [Southeast University](https://www.seu.edu.cn), Nanjing. I am now supervised by [Dr.Huazhu Fu](https://hzfu.github.io/) at ASTAR in Singapore. I am supervised by [Prof. Guanyu Yang](https://cse.seu.edu.cn/2023/1024/c23024a469548/page.htm) for doctoral studies. Prior to this, I achieved master's degree at Imperial College London supervised by [Dr Andrew Scott](https://www.imperial.ac.uk/people/a.scott07) and bachelor's degree at Northwestern Polytechinical University. 

My research lies at the intersection of **Deep Learning** and **Artificial Intelligence in Medicine** -- with a special focus on dealing with the tough task in **Computational Pathology**. My research interests include **Medical Image Analysis**, **Multi-modal Fusion**, **Federated Learning**, and **Generation Model**, etc.

{% include_relative _includes/news.md %}

{% include_relative _includes/awards.md %}

{% include_relative _includes/publications.md %}

{% include_relative _includes/contact.md %}

{% include_relative _includes/services.md %}

<span id="cv-link" onclick="showPdf()">CV</span>

<script>
function showPdf() {
  var pdfViewer = document.createElement('object');
  pdfViewer.data = './assets/files/CV_YuanZhang.pdf';
  pdfViewer.type = 'application/pdf';
  pdfViewer.width = '100%';
  pdfViewer.height = '600px';
  
  document.getElementById('cv-link').innerHTML = '';
  document.getElementById('cv-link').appendChild(pdfViewer);
}
</script>
