---
layout: splash
permalink: /
hidden: true
feature_row_profile:
    - image_path: /assets/images/profile.png
      alt: "profile"
      title: "안녕하세요,<br> David Park입니다."
      excerpt: "개발자입니다"
projects:
    - url: /assets/images/unsplash-gallery-image-1.jpg
      image_path: /assets/projects_thumbnail/projects-gsshop.png
      alt: "GSSHOP MSA 방송구조개선"
    - url: /assets/images/unsplash-gallery-image-2.jpg
      image_path: /assets/projects_thumbnail/projects-cosmos.png
      alt: "COSMOS 신칸센종합시스템"
    - url: /assets/images/unsplash-gallery-image-3.jpg
      image_path: /assets/projects_thumbnail/projects-kpa.png
      alt: "KPA1959 한국토지도시계획학회"
---

&nbsp;
&nbsp;
{% include feature_row id="feature_row_profile" type="profile" %}
## Latest Works
{% include gallery id="projects" %}

## Latest Posts
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}