{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}
{% assign url_hindex = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio_hindex.json" %}
{% assign url_i10 = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio_i10.json" %}

<p style="text-align:justify">
<i class="fas fa-quote-left fa-2x fa-pull-left fa-border" aria-hidden="true"></i>

I work at Chengdu University of Traditional Chinese Medince  as a Distinguished associate researcher now in Chengdu.
If you are seeking any form of academic cooperation, please feel free to email me at [zhangpengfei@cdutcm.edu.cn] or [feifeihappy55@163.com].
  
I graduated from the <a href='https://scai.swjtu.edu.cn/web/page-module.html?mid=496DC5D75016E9F1'>School of Computing and Artificial Intelligence</a>, Southwest Jiaotong University with a Ph.D., 
under the supervision of <a href='https://faculty.swjtu.edu.cn/litianrui/zh_CN/index.htm'>Tianrui Li (Prof.)</a>. 
Prior to this, I received the M. Sc. degree  at the <a href='https://www.gxmzu.edu.cn/'>Guangxi Minzu University</a>.  My research interests are broad, including  granular computing, information fusion and data mining, 
especially on outlier detection and feature selection. Now, I mainly engaged in the research of AI and the integration of traditional Chinese and Western medicine.

<i class="fas fa-quote-right fa-2x fa-pull-right fa-border" aria-hidden="true"></i>
</p>

- <i>Citation statistics:</i>
<a href='https://scholar.google.com/citations?user=auw5EKcAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
\|
<a href='https://scholar.google.com/citations?user=auw5EKcAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url_hindex | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=h-index"></a>
\|
<a href='https://scholar.google.com/citations?user=auw5EKcAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url_i10 | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=i10-index"></a>
