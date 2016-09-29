---
layout: article
title: ファイル共有
excerpt: 
image:
  teaser: thumbnail/fileshare_400x250.png
categories: skyway
tags: skyway webrtc character usecase
---

<a href="https://share.skyway.io/" target="_blank" class="btn-info">Demo: SkyShare</a>

WebRTCは、映像や音声だけでなく、データ送信もP2Pで行うことができます。

従来のように、一度サーバにデータをアップロードする必要がなく、P2Pで直接通信し、end-to-endで暗号化されているため、手軽で安全にデータを送ることができます。

BitTorrentやWinnyのようなファイル共有サービスや分散DL、Web会議での資料の送付など、様々な用途に活用できます。

<hr>

関連ユーザ事例

<div class="tiles">
{% for post in site.tags.fileshare %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->