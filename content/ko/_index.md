---
# Homepage (Korean)
type: landing
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
      title: 프로젝트
      subtitle: ''
      count: 9
      page_type: project
      text: ""
    design:
      view: card
      columns: '3'


  - block: slider
    content:
      text: ""
      slides:
        - title: "집중과 몰입"
          content: "깔끔한 코드로 만드는 사용자 경험"
          background:
            image:
              filename: 1_unsplash.jpg
        - title: "풀스택 비주얼라이제이션"
          content: "데이터부터 경험까지"
          background:
            image:
              filename: 2_unsplash.jpg
        - title: "디테일한 코드"
          content: "직접 만들어보며 배우기"
          background:
            image:
              filename: 3_unsplash.jpg
    design:
      is_fullscreen: false
      slide_height: '420px'
      interval: 0



  - block: experience
    section_id: experience
    content:
      title: 경력
      subtitle: ''
      text: ""
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