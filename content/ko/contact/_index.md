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
      title: "🗺️ 전북대학교 위치"
      text: |
        전북대학교 공과대학 컴퓨터인공지능학부 위치입니다.
        
        <div style="margin: 20px 0; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
          <div id="map" style="height: 400px; width: 100%;"></div>
        </div>
        
        <script>
        // Leaflet 지도 라이브러리 로드
        if (!window.L) {
          const link = document.createElement('link');
          link.rel = 'stylesheet';
          link.href = 'https://unpkg.com/leaflet@1.9.4/dist/leaflet.css';
          document.head.appendChild(link);
          
          const script = document.createElement('script');
          script.src = 'https://unpkg.com/leaflet@1.9.4/dist/leaflet.js';
          script.onload = function() {
            initMap();
          };
          document.head.appendChild(script);
        } else {
          initMap();
        }
        
        function initMap() {
          // 전북대학교 좌표
          const jbnu = [35.8469, 127.1295];
          
          // 지도 생성
          const map = L.map('map').setView(jbnu, 16);
          
          // OpenStreetMap 타일 추가
          L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
            attribution: '© OpenStreetMap contributors'
          }).addTo(map);
          
          // 전북대학교 마커 추가
          L.marker(jbnu).addTo(map)
            .bindPopup('<b>전북대학교</b><br>컴퓨터인공지능학부<br>전북특별자치도 전주시')
            .openPopup();
        }
        </script>
        
        **📍 주소:** 전북대학교로 567, 전주시, 전북특별자치도 54896
    
    design:
      columns: '1'

  - block: contact
    content:
      title: "💬 연락처"
      text: |
        궁금한 점이 있으시면 언제든 연락주세요!
      
      contact_links:
        - icon: envelope
          icon_pack: fas
          name: 이메일 보내기
          link: 'mailto:isy0110@jbnu.ac.kr'
        - icon: github
          icon_pack: fab
          name: GitHub
          link: 'https://github.com/abc202313746'
        - icon: instagram
          icon_pack: fab
          name: Instagram
          link: 'https://www.instagram.com/insookyoung/'
    
    design:
      columns: '1'

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