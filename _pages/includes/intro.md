{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# <img src='images/android-chrome-192x192.png' style='height: 1em;'> About Me

I am Yudong Zhang (张宇东), a PhD candidate in the Department of Electronic Engineering at Tsinghua University, under the supervision of Professor [Wang Yu (汪玉)](https://web.ee.tsinghua.edu.cn/wangyu/en/). I completed my bachelor's degree in the same department at Tsinghua University in 2020, advised by Professor [Chen Jiansheng (陈健生)](https://jschenthu.weebly.com/).

My research focuses on enhancing the safety and efficiency of vision-language models. To date, I have authored or co-authored 10 peer-reviewed papers, including 4 first-author publications in academic conferences such as AAAI, ACM Multimedia (ACMMM), and NAACL, with <a href='https://scholar.google.com/citations?user=6bsN3RYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> citations to date.

Currently, I am an intern at Tencent's Hunyuan team, where I contribute to the development of large language model pre-training technologies.

If you are interested in academic collaboration or would like to discuss potential research opportunities, please feel free to reach out via email [zhangyd16@mails.tsinghua.edu.cn](mailto:zhangyd16@mails.tsinghua.edu.cn).

I am seeking job opportunities for June 2026.