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
  - block: markdown
    content:
      title: 커스텀 카드 예시
      text: |
        {{< card_overlay title="데이터베이스 설계" subtitle="전주 문화관광 통합" image="/project/database/featured.png" link="/project/database/" >}}
        
        {{< card_compact title="운영체제 핵심 개념" meta="C, 스케줄링, 동기화" image="/project/os/featured.png" link="/project/os/" >}}

  - block: markdown
    content:
      title: 이미지 슬라이더
      text: |
        {{< slider items="https://images.unsplash.com/photo-1518770660439-4636190af475|AI|Artificial Intelligence; https://images.unsplash.com/photo-1518779578993-ec3579fee39f|Code|Coding; https://images.unsplash.com/photo-1526378722419-350d4f3de0bb|Data|Data" >}}

  - block: markdown
    content:
      title: 9개 카드 그리드
      text: |
        <div class="row row-cols-1 row-cols-md-3 g-3">
          <div class="col">{{< card_compact title="DB 설계" meta="관계형 모델" image="/project/database/featured.png" link="/project/database/" >}}</div>
          <div class="col">{{< card_compact title="운영체제" meta="프로세스/스케줄링" image="/project/os/featured.png" link="/project/os/" >}}</div>
          <div class="col">{{< card_compact title="스택 계산기" meta="C++ 자료구조" image="/project/stack/featured.png" link="/project/stack/" >}}</div>
          <div class="col">{{< card_overlay title="DB 설계" subtitle="전주 문화관광" image="/project/database/featured.png" link="/project/database/" >}}</div>
          <div class="col">{{< card_overlay title="운영체제" subtitle="동기화/스레드" image="/project/os/featured.png" link="/project/os/" >}}</div>
          <div class="col">{{< card_overlay title="스택 계산기" subtitle="중위→후위" image="/project/stack/featured.png" link="/project/stack/" >}}</div>
          <div class="col">{{< card_compact title="DB 설계" meta="정규화" image="/project/database/featured.png" link="/project/database/" >}}</div>
          <div class="col">{{< card_compact title="운영체제" meta="교착상태" image="/project/os/featured.png" link="/project/os/" >}}</div>
          <div class="col">{{< card_compact title="스택 계산기" meta="스택 연산" image="/project/stack/featured.png" link="/project/stack/" >}}</div>
        </div>

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
        
        연락처: [GitHub](https://github.com/abc202313746) · [Instagram](https://www.instagram.com/insookyoung/)
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
---