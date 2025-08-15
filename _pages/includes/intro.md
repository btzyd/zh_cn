{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# <img src='images/android-chrome-192x192.png' style='height: 1em;'> 个人简介 {#about}

我是张宇东，[清华大学电子工程系](https://www.ee.tsinghua.edu.cn/)的[NICS-EFC实验室](https://nicsefc.ee.tsinghua.edu.cn/)的博士生，导师是[汪玉教授](https://web.ee.tsinghua.edu.cn/wangyu/en/)。我于2020年在[清华大学电子工程系](https://www.ee.tsinghua.edu.cn/)获得学士学位，导师是[陈健生教授](https://jschenthu.weebly.com/)。

我的研究重点是提升视觉语言模型的安全性和效率。迄今为止，我已发表了11篇论文，其中5篇以第一作者身份发表在AAAI、ACM-MM和NAACL等学术会议上，这些论文的引用次数为<a href='https://scholar.google.com/citations?user=6bsN3RYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>。

我目前是腾讯混元团队的实习生，导师是[孙兴武](https://scholar.google.com/citations?user=rjC51OsAAAAJ)和[谢若冰](https://ruobingxie.github.io/)。我专注于大型语言模型的预训练。

如果您对学术合作感兴趣或希望探讨潜在的研究机会，请随时通过电子邮件联系我[zhangyd16@mails.tsinghua.edu.cn](mailto:zhangyd16@mails.tsinghua.edu.cn)。

我将于2026年6月毕业，正在寻找工作机会。