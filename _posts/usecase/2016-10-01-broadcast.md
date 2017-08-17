---
layout: article
title: ライブ配信
excerpt: 
image:
  teaser: thumbnail/broadcast_400x250.png
categories: skyway
tags: skyway webrtc image character usecase
---

{% include video.html id='lNdmz1jq8M4' %}

従来、ストリーミング技術が担ってきたライブ配信の分野にも使われて始めています。

HLS (HTTP Live Streaming) 等のストリーミング技術と比べると、

- 遅延が少ない (従来技術は数十秒以上の遅延があった)
- インタラクティブなコミュニケーションが可能 (質疑応答など)

のメリットがあります。

ゲーム実況やお絵かきのライブ配信などに活用されています。

<hr>

関連ユーザ事例

<div class="tiles">
{% for post in site.tags.broadcast %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
