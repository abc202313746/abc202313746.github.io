---
title: 연락처 및 위치
summary: 인숙영과 연락하기. 연락처 정보, 위치 세부사항, 그리고 전북대학교 오시는 길을 안내합니다.
type: landing
date: 2024-01-01
translationKey: contact
image:
  filename: 'uploads/justin-lim-tloFnD-7EpI-unsplash (1).jpg'
  caption: '연락처 및 위치'
searchable: true

sections:
  - block: hero
    content:
      title: "연락처 및 위치"
      text: |
        <div class="justify-text">
        전북대학교 컴퓨터인공지능학부 인숙영과 연락하는 방법과 위치 정보를 안내합니다.
        </div>
    design:
      background:
        gradient_start: '#7c4dff'
        gradient_end: '#651fff'
        text_color_light: true
      spacing:
        padding: ['60px', '0', '60px', '0']

  - block: features
    content:
      title: "연락처 정보"
      items:
        - name: "📧 이메일"
          description: "**isy0110@jbnu.ac.kr**"
          icon: envelope
          icon_pack: fas
        - name: "📍 위치"
          description: "**전북대학교 공과대학**<br>전주시, 전북특별자치도 54896"
          icon: map-marker-alt
          icon_pack: fas
        - name: "🏫 소속"
          description: "**전북대학교(JBNU)**<br>Jeonbuk National University<br>컴퓨터인공지능학부"
          icon: university
          icon_pack: fas
    design:
      columns: '3'
      view: card
      background:
        color: 'white'

  - block: markdown
    content:
      title: "🗺️ 캠퍼스 지도"
      text: |
        <div class="map-container" style="margin: 20px 0; border-radius: 12px; overflow: hidden; box-shadow: 0 8px 25px rgba(124, 77, 255, 0.15);">
          <iframe 
            src="https://www.openstreetmap.org/export/embed.html?bbox=127.1240%2C35.8440%2C127.1340%2C35.8500&layer=mapnik&marker=35.8469%2C127.1295"
            width="100%" 
            height="450" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy">
          </iframe>
        </div>
        
    design:
      background:
        color: '#f8f9ff'
      spacing:
        padding: ['40px', '0', '40px', '0']

  - block: features
    content:
      title: "🔗 소셜 미디어"
      items:
        - name: "GitHub"
          description: "프로젝트 및 코드 저장소"
          icon: github
          icon_pack: fab
          link: "https://github.com/abc202313746"
        - name: "Instagram"
          description: "일상 및 학습 기록"
          icon: instagram
          icon_pack: fab
          link: "https://www.instagram.com/insookyoung/"
        - name: "Email"
          description: "직접 연락하기"
          icon: envelope
          icon_pack: fas
          link: "mailto:isy0110@jbnu.ac.kr"
    design:
      columns: '3'
      view: card
      background:
        color: 'white'
---