---
# Homepage (Korean)
type: landing
sections:
  - block: about.avatar
    section_id: about
    content:
      username: admin
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
      title: 프로젝트
      subtitle: ''
      count: 9
      page_type: project
    design:
      view: card
      columns: '3'
  

  - block: slider
    content:
      slides:
        - title: "자기소개"
          content: "전북대 컴퓨터인공지능학부 3학년, 프론트엔드 지향"
          background:
            image:
              filename: unsplash-frontend.svg
        - title: "협력"
          content: "코드 리뷰와 페어 프로그래밍, 팀과 함께 성장"
          background:
            image:
              filename: unsplash-systems.svg
        - title: "관심사"
          content: "React/TypeScript · 데이터 모델링 · 시스템 이해"
          background:
            image:
              filename: unsplash-build.svg

  # Fallback slider via shortcode (renders even if block: slider is skipped)
  - block: markdown
    content:
      title: ""
      text: |
        {{< slider items="/uploads/unsplash-frontend.svg|자기소개|전북대 컴퓨터·AI 3학년, 프론트엔드 지향; /uploads/unsplash-systems.svg|협력|코드 리뷰와 페어 프로그래밍, 팀과 함께 성장; /uploads/unsplash-build.svg|관심사|React/TypeScript · 데이터 모델링 · 시스템 이해" height="360" autoplay="true" interval="4000" >}}

  
  

  - block: experience
    section_id: experience
    content:
      title: 경력
      subtitle: ''
      date_format: Jan 2006
      items:
        - title: 동아리 활동 (Club Member)
          company: Koala
          location: 전북대학교
          date_start: '2024-03-02'
          date_end: '2024-06-20'
          description: '알고리즘 문제 해결 능력과 논리적 사고력을 기르기 위해 동아리 활동에 참여.'
        - title: SW 멘토링 멘티 (Mentee)
          company: Online
          location: 전북대학교
          date_start: '2024-09-11'
          date_end: '2024-12-13'
          description: '선배 멘토와의 상호작용을 통해 실무 기술 역량을 강화하는 멘토링 프로그램에 참여.'

  - block: contact
    section_id: contact
    content:
      title: 오시는 길
      text: |
        전북대학교 (Jeonbuk National University)
        
        [GitHub](https://github.com/abc202313746) · [Instagram](https://www.instagram.com/insookyoung/)
        전화: [010-4544-0797](tel:+821045440797)
        이메일: [isy0110@jbnu.ac.kr](mailto:isy0110@jbnu.ac.kr)
      map:
        provider: OpenStreetMap
        zoom: 15
        center:
          lat: 35.8469
          lng: 127.1295
        markers:
          - title: 전북대학교
            lat: 35.8469
            lng: 127.1295
  - block: markdown
    content:
      text: |
        {{< fab >}}
---