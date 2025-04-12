---
permalink: /
title: "Renyuan Liu (刘稔远)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a third year undergraduate student from [Gaungzhou University](https://www.gzhu.edu.cn/xxgk/xxjj.htm). My research interest includes robotics, neuron networks, machine vision, motion perception and bio-inspired systems.

I am very fortunate to be advised by [Prof. Qinbing Fu](https://scholar.google.com/citations?hl=zh-CN&user=YIte1M8AAAAJ) of Machine Life and Intellegence Research Centre, Guangzhou University. 

You can find my CV here: [Renyuan's Curriculum Vitae](../assets/CV_RenyuanLiu.pdf).

[Github](https://github.com/Ryannnice) / [Wechat](../images/WeChat.png) / [Instagram](https://www.instagram.com/ren_yvan/)





## 🌍 Visitor Map

<div id="visitor-map" style="height: 400px; border-radius: 10px; margin-top: 2em;"></div>

<script>
  const map = L.map('visitor-map').setView([20, 0], 2);

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '© OpenStreetMap contributors'
  }).addTo(map);

  // 聚类组
  const markers = L.markerClusterGroup();

  // 加载组织或历史访问数据
  fetch('/leaflet_dist/org-locations.js')
    .then(response => response.text())
    .then(js => {
      eval(js); // 里面定义了 locations 数组
      locations.forEach(loc => {
        const marker = L.marker([loc.lat, loc.lon]).bindPopup(loc.name);
        markers.addLayer(marker);
      });
      map.addLayer(markers);
    });

  // 当前访客位置
  fetch('https://ipapi.co/json')
    .then(res => res.json())
    .then(data => {
      const lat = data.latitude, lon = data.longitude;
      const marker = L.marker([lat, lon]).bindPopup(`👋 You are here: ${data.city}, ${data.country_name}`);
      marker.addTo(map).openPopup();
      map.setView([lat, lon], 4);
    });
</script>

