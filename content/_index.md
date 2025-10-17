---
title: "인숙영의 포트폴리오 - 전북대 컴퓨터인공지능공학부"
description: "전북대 컴퓨터인공지능공학부 인숙영의 포트폴리오 소개합니다."
keywords: "인숙영, SookYoung In, 전북대학교, 컴퓨터공학부, 프론트엔드 개발자, React, TypeScript, 포트폴리오, 데이터베이스 설계, 운영체제, 자료구조"
type: landing
image:
  filename: 'uploads/og-image.png?v=2'
  caption: '인숙영의 포트폴리오'
searchable: true
sections:
  - block: about.avatar
    section_id: about
    content:
      username: admin
      text: |
        <p class="justify-text" style="color: #FFC107;">
        👋 안녕하세요! 저는 프론트엔드 개발자를 희망하는 대학생, 제 이름은 <strong>인숙영</strong>입니다.<br>
        특히 React와 TypeScript 기술에 관심이 많습니다.<br>
        저의 목표는 사용자에게 도움이 되는 최고의 웹사이트를 구현하는 것입니다.
        </p>
        
        아래에서 제 [이력서](/uploads/resume.pdf)와 포트폴리오를 확인해보세요 😍
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
      view: masonry
      columns: "2"

  - block: portfolio
    section_id: programming-languages
    content:
      title: "할 수 있는 언어"
      subtitle: ""
      text: ""
      filters:
        folders:
          - languages
      count: 3
    design:
      view: compact
      columns: '3'

  - block: portfolio
    section_id: dream-goals
    content:
      title: "꿈꾸는 목표"
      subtitle: ""
      count: 3
      filters:
        folders:
          - goals
      text: ""
    design:
      view: showcase
      columns: "1"

  - block: slider
    content:
      text: ""
      slides:
        - title: "React · TypeScript"
          background:
            image:
              filename: "/uploads/1_unsplash.jpg"
        - title: "Coding my style"
          background:
            image:
              filename: "/uploads/2_unsplash.jpg"
        - title: "Algorithm"
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

  - block: markdown
    content:
      title: ""
      text: |
        <div style="text-align: center; margin: 60px 0; padding: 40px 20px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 20px; color: white;">
          <h2 style="margin-bottom: 20px; font-weight: 700;">📄 이력서 다운로드</h2>
          <p style="margin-bottom: 30px; font-size: 1.1rem; opacity: 0.9;">저의 상세한 이력과 프로젝트 정보를 확인해보세요!</p>
          <a href="/uploads/resume.pdf" download="인숙영_이력서.pdf" 
             style="display: inline-block; padding: 15px 40px; background: white; color: #667eea; text-decoration: none; border-radius: 50px; font-weight: 700; font-size: 1.1rem; transition: all 0.3s ease; box-shadow: 0 4px 15px rgba(0,0,0,0.2);"
             onmouseover="this.style.transform='translateY(-3px)'; this.style.boxShadow='0 6px 20px rgba(0,0,0,0.3)';"
             onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 4px 15px rgba(0,0,0,0.2)';">
            <i class="fas fa-download" style="margin-right: 10px;"></i>이력서 다운로드
          </a>
        </div>

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