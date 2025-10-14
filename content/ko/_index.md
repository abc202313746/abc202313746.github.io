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

  - block: markdown
    content:
      title: ""
      text: |
        {{< slider items="/uploads/slide-1.jpg|React · TypeScript|컴포넌트 설계와 상태 관리로 유지보수성 높은 UI 구현; /uploads/slide-2.jpg|Learning by Building|작게 만들고 빠르게 개선하며 결과로 증명; /uploads/slide-3.jpg|Algorithms|복잡도 분석을 바탕으로 효율적인 로직과 최적화" height="360" autoplay="true" interval="4000" >}}



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