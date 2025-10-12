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
        color: '#090a0b'
        text_color_light: true
        image:
          filename: space.jpg
          filters:
            brightness: 0.5
      css_class: d-flex fullscreen align-items-center

  - block: portfolio
    section_id: portfolio
    content:
      title: 프로젝트
      subtitle: ''
      page_type: project
    design:
      view: masonry
      columns: '1'

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

  - block: map
    section_id: contact
    content:
      title: 오시는 길
      text: 전북대학교 (Jeonbuk National University)
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
---