---
title: "인숙영의 포트폴리오 - 전북대학교 컴퓨터공학부"
description: "전북대학교 컴퓨터공학부 인숙영의 포트폴리오. 프론트엔드 개발자 지망생으로 React, TypeScript, 데이터베이스 설계, 운영체제, 자료구조 프로젝트를 소개합니다."
keywords: "인숙영, SookYoung In, 전북대학교, 컴퓨터공학부, 프론트엔드 개발자, React, TypeScript, 포트폴리오, 데이터베이스 설계, 운영체제, 자료구조"
type: landing
image:
  filename: 'uploads/og-image.png'
  caption: '인숙영의 포트폴리오'
searchable: true
tags: ["인숙영", "SookYoung In", "전북대학교", "전북대", "Jeonbuk National University", "JBNU", "컴퓨터공학부", "컴퓨터인공지능학부", "프론트엔드", "React", "TypeScript", "전주", "전북특별자치도"]
sections:
  - block: about.avatar
    section_id: about
    content:
      username: admin
      text: ""
    design:
      background:
        color: ""
        text_color_light: false
        image:
          filename: ""
          filters:
            brightness: 0.5
      css_class: d-flex fullscreen align-items-center

  - block: portfolio
    section_id: portfolio
    content:
      title: "프로젝트"
      subtitle: ""
      count: 3
      page_type: project
      text: ""
    design:
      view: card
      columns: "3"

  - block: markdown
    section_id: programming-languages
    content:
      title: "할 수 있는 언어"
      subtitle: ""
      text: |
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; margin: 30px 0;">
          <a href="/languages/python/" style="text-decoration: none; color: inherit;">
            <div style="padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: #f9f9f9; transition: all 0.3s ease; cursor: pointer;" onmouseover="this.style.transform='translateY(-3px)'; this.style.boxShadow='0 6px 20px rgba(124, 77, 255, 0.15)'; this.style.borderColor='#7c4dff';" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'; this.style.borderColor='#e0e0e0';">
              <div style="display: flex; align-items: center; margin-bottom: 12px;">
                <span style="font-size: 2rem; margin-right: 12px;">🐍</span>
                <h3 style="color: #7c4dff; margin: 0; font-size: 1.2rem; font-weight: 600;">파이썬 (Python)</h3>
              </div>
              <p style="margin: 0; color: #666; line-height: 1.5; font-size: 0.95rem;">파이썬 데이터 분석 및 시각화 프로젝트</p>
            </div>
          </a>
          
          <a href="/languages/c-language/" style="text-decoration: none; color: inherit;">
            <div style="padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: #f9f9f9; transition: all 0.3s ease; cursor: pointer;" onmouseover="this.style.transform='translateY(-3px)'; this.style.boxShadow='0 6px 20px rgba(124, 77, 255, 0.15)'; this.style.borderColor='#7c4dff';" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'; this.style.borderColor='#e0e0e0';">
              <div style="display: flex; align-items: center; margin-bottom: 12px;">
                <span style="font-size: 2rem; margin-right: 12px;">🔧</span>
                <h3 style="color: #7c4dff; margin: 0; font-size: 1.2rem; font-weight: 600;">C언어 (C Language)</h3>
              </div>
              <p style="margin: 0; color: #666; line-height: 1.5; font-size: 0.95rem;">C언어 커스텀 메모리 할당자 구현</p>
            </div>
          </a>
          
          <a href="/languages/java/" style="text-decoration: none; color: inherit;">
            <div style="padding: 20px; border: 1px solid #e0e0e0; border-radius: 8px; background: #f9f9f9; transition: all 0.3s ease; cursor: pointer;" onmouseover="this.style.transform='translateY(-3px)'; this.style.boxShadow='0 6px 20px rgba(124, 77, 255, 0.15)'; this.style.borderColor='#7c4dff';" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'; this.style.borderColor='#e0e0e0';">
              <div style="display: flex; align-items: center; margin-bottom: 12px;">
                <span style="font-size: 2rem; margin-right: 12px;">☕</span>
                <h3 style="color: #7c4dff; margin: 0; font-size: 1.2rem; font-weight: 600;">자바 (Java)</h3>
              </div>
              <p style="margin: 0; color: #666; line-height: 1.5; font-size: 0.95rem;">객체지향 작업 관리 시스템</p>
            </div>
          </a>
        </div>
    design:
      background:
        color: 'white'
      spacing:
        padding: ['40px', '0', '40px', '0']

  - block: portfolio
    section_id: portfolio-showcase
    content:
      title: "프로젝트 쇼케이스"
      subtitle: ""
      count: 3
      page_type: project
      text: ""
    design:
      view: showcase
      columns: "1"

  - block: portfolio
    section_id: portfolio-masonry
    content:
      title: "프로젝트 갤러리"
      subtitle: ""
      count: 3
      page_type: project
      text: ""
    design:
      view: masonry
      columns: "2"

  - block: slider
    content:
      text: ""
      slides:
        - title: "React · TypeScript"
          content: "컴포넌트 설계와 상태 관리로 유지보수성 높은 UI를 구현"
          background:
            image:
              filename: "/uploads/1_unsplash.jpg"
        - title: "실습을 통한 학습"
          content: "작게 만들고 빠르게 개선하며 결과로 증명"
          background:
            image:
              filename: "/uploads/2_unsplash.jpg"
        - title: "알고리즘"
          content: "복잡도 분석을 바탕으로 효율적인 로직과 최적화"
          background:
            image:
              filename: "/uploads/3_unsplash.jpg"
    design:
      is_fullscreen: false
      slide_height: "420px"
      interval: "3500"

  - block: experience
    section_id: experience
    content:
      title: "경력"
      subtitle: ""
      text: ""
      date_format: "2006년 1월"
      items:
        - title: "동아리 활동"
          company: "Koala"
          location: "전북대학교"
          date_start: "2024-03-02"
          date_end: "2024-06-20"
          description: "알고리즘 문제 해결 능력과 논리적 사고력을 기르기 위해 동아리 활동에 참여."
        - title: "SW 멘토링 멘티"
          company: "Online"
          location: "전북대학교"
          date_start: "2024-09-11"
          date_end: "2024-12-13"
          description: "선배 멘토와의 상호작용을 통해 실무 기술 역량을 강화하는 멘토링 프로그램에 참여."

  - block: accomplishments
    section_id: goals
    content:
      title: "진로 목표 및 관심사"
      subtitle: ""
      text: ""
      date_format: "2006년 1월"
      items:
        - title: "프론트엔드 개발 전문성"
          organization: "개인 목표"
          date_start: "2024-01-01"
          date_end: ""
          description: '<span class="justify-text">React와 TypeScript를 중심으로 한 모던 프론트엔드 기술에 능숙해져서 직관적이고 유지보수가 용이한 사용자 인터페이스를 만드는 것이 목표입니다. 컴포넌트 기반 아키텍처, 상태 관리, 반응형 디자인 원칙을 마스터하고 싶습니다.</span>'
        - title: "풀스택 개발자로 성장"
          organization: "미래 포부"
          date_start: "2024-01-01"
          date_end: ""
          description: '<span class="justify-text">백엔드 기술과 데이터베이스 관리까지 포함하여 균형 잡힌 개발자가 되고자 합니다. 데이터베이스 설계부터 사용자 인터페이스까지 웹 개발의 전체 생명주기를 이해하고 싶습니다.</span>'
        - title: "오픈소스 기여"
          organization: "커뮤니티 목표"
          date_start: "2024-01-01"
          date_end: ""
          description: '<span class="justify-text">오픈소스 프로젝트에 기여하여 개발자 커뮤니티에 환원하고 협업 코딩 스킬을 향상시키고 싶습니다. 커뮤니티 주도 개발의 힘을 믿으며 그 일부가 되고 싶습니다.</span>'
        - title: "기술을 통한 문제 해결"
          organization: "핵심 관심사"
          date_start: "2024-01-01"
          date_end: ""
          description: '<span class="justify-text">기술을 활용하여 실제 문제를 해결하고 의미 있는 영향을 만들어내는 것에 관심이 있습니다. 특히 사용자 경험을 개선하고 복잡한 작업을 더 접근하기 쉽게 만드는 애플리케이션 개발에 관심이 많습니다.</span>'

  - block: contact
    section_id: contact
    content:
      title: "위치"
      text: |
        전북대학교

        [GitHub](https://github.com/abc202313746) · [Instagram](https://www.instagram.com/insookyoung/)
        연락처: [010-4544-0797](tel:+821045440797)
        이메일: [isy0110@jbnu.ac.kr](mailto:isy0110@jbnu.ac.kr)

        <div class="map-embed" style="margin-top:12px;">
          <iframe
            src="https://www.openstreetmap.org/export/embed.html?bbox=127.1240%2C35.8440%2C127.1340%2C35.8500&layer=mapnik&marker=35.8469%2C127.1295"
            width="100%"
            height="360"
            style="border:0;border-radius:8px;"
            loading="lazy"
          ></iframe>
        </div>
      map:
        provider: OpenStreetMap
        zoom: 15
        center:
          lat: 35.8469
          lng: 127.1295
        markers:
          - title: "전북대학교"
            lat: 35.8469
            lng: 127.1295

  - block: markdown
    content:
      text: |
        {{< fab >}}
---