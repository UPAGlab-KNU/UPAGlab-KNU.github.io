---
layout: page
permalink: /people/
title: people
description: Members of UPAG Lab
nav: true
nav_order: 4
---

<style>
.member-card {
  display: flex;
  align-items: flex-start;
  gap: 2rem;
  padding: 1.5rem 0;
  border-bottom: 1px solid var(--global-divider-color);
}
.member-card:last-child {
  border-bottom: none;
}
.member-photo {
  flex-shrink: 0;
  width: 160px;
}
.member-photo img {
  width: 100%;
  border-radius: 50%;
  aspect-ratio: 1 / 1;
  object-fit: cover;
}
.member-info {
  flex: 1;
}
.member-info h3 {
  margin-top: 0;
  margin-bottom: 0.3rem;
}
.member-meta {
  color: var(--global-text-color-light);
  font-size: 0.95rem;
  margin-bottom: 0.8rem;
}
.member-info ul {
  margin-bottom: 0.5rem;
}
@media (max-width: 576px) {
  .member-card {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  .member-photo {
    width: 140px;
  }
}
</style>

## 석사과정 (M.A. Students)

<div class="member-card">
  <div class="member-photo">
    <img src="{{ '/assets/img/kal_bongsu.svg' | relative_url }}" alt="갈봉수">
  </div>
  <div class="member-info">
    <h3>갈봉수 (Kal Bongsu)</h3>
    <div class="member-meta">석사과정 1년차 · M.A. Student (1st year)</div>
    <p><strong>연구 주제:</strong> 네트워크 공간분석 (Network Spatial Analysis)</p>
    <p>도시 내 다양한 네트워크(교통, 사회 등)의 구조와 공간적 특성을 분석하여 도시 현상을 이해하고자 합니다.</p>
    <p><strong>관심 분야:</strong> Network Spatial Analysis · Urban Geography · GIS</p>
    <p>📧 [이메일주소]</p>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="{{ '/assets/img/yoo_yewon.svg' | relative_url }}" alt="유예원">
  </div>
  <div class="member-info">
    <h3>유예원 (Yoo Yewon)</h3>
    <div class="member-meta">석사과정 1년차 · M.A. Student (1st year)</div>
    <p><strong>연구 주제:</strong> 스마트도시 (Smart City)</p>
    <p>데이터와 기술이 도시 운영과 시민의 삶에 어떻게 통합되는지를 공간적 관점에서 탐구합니다.</p>
    <p><strong>관심 분야:</strong> Smart City · Urban Data Analytics · GIS</p>
    <p>📧 [이메일주소]</p>
  </div>
</div>
