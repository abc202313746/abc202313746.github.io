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
      page_type: project
    design:
      view: masonry
      columns: '1'
  - block: markdown
    content:
      title: 빠른 액션
      text: |
        <div class="d-flex flex-wrap gap-2">
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="#top"><i class="fas fa-arrow-up me-2"></i>Top</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="/project/"><i class="fas fa-layer-group me-2"></i>프로젝트</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="/uploads/resume.pdf"><i class="fas fa-file-alt me-2"></i>이력서(PDF)</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="mailto:isy0110@jbnu.ac.kr"><i class="fas fa-envelope me-2"></i>연락하기</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="tel:+821045440797"><i class="fas fa-phone me-2"></i>전화걸기</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="https://maps.google.com/?q=35.8469,127.1295" target="_blank" rel="noopener"><i class="fas fa-map-marker-alt me-2"></i>위치(지도)</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="/en/"><i class="fas fa-globe me-2"></i>한국어/English</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="https://jbnu.macs.or.kr" target="_blank" rel="noopener"><i class="fas fa-external-link-alt me-2"></i>학과 홈페이지</a>
        </div>
  - block: markdown
    content:
      title: 자기소개 슬라이드
      text: |
        <div class="cc-slider" data-autoplay="true" data-interval="4200">
          <div class="cc-slider__track">
            <figure>
              <img src="https://images.unsplash.com/photo-1500576992153-0271099def59?auto=format&fit=crop&w=1600&q=80" alt="Hello sticker" style="height:360px;" />
              <figcaption>안녕하세요! 전북대 컴퓨터·AI 3학년 인숙영입니다.</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1600&q=80" alt="Code" style="height:360px;" />
              <figcaption>프론트엔드 React TypeScript 로 사용자 경험을 만듭니다.</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1600&q=80" alt="Database" style="height:360px;" />
              <figcaption>데이터베이스 설계와 정규화를 프로젝트에 적용.</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80" alt="Operating System" style="height:360px;" />
              <figcaption>운영체제 핵심 프로세스·스레드·동기화 학습.</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1522075469751-3a6694fb2f61?auto=format&fit=crop&w=1600&q=80" alt="Teamwork" style="height:360px;" />
              <figcaption>팀과 함께 성장하며 배운 것을 공유합니다.</figcaption>
            </figure>
          </div>
          <div class="cc-slider__dots"></div>
        </div>
  - block: markdown
    content:
      title: 커스텀 카드 예시
      text: |
        {{< card_overlay title="데이터베이스 설계" subtitle="전주 문화관광 통합" image="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1200&q=80" link="/project/database/" >}}
        
        {{< card_compact title="운영체제 핵심 개념" meta="C, 스케줄링, 동기화" image="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80" link="/project/os/" >}}

  - block: markdown
    content:
      title: 이미지 슬라이더
      text: |
        <div class="cc-slider" data-autoplay="true" data-interval="3500">
          <div class="cc-slider__track">
            <figure>
              <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80" alt="AI" />
              <figcaption>Artificial Intelligence</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1600&q=80" alt="Code" />
              <figcaption>Coding</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1600&q=80" alt="Data" />
              <figcaption>Data</figcaption>
            </figure>
          </div>
          <div class="cc-slider__dots"></div>
        </div>

  - block: markdown
    content:
      title: 9개 카드 그리드
      text: |
        <div class="row row-cols-1 row-cols-md-3 g-3">
          <div class="col">{{< card_compact title="DB 설계" meta="관계형 모델" image="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1200&q=80" link="/project/database/" >}}</div>
          <div class="col">{{< card_compact title="운영체제" meta="프로세스/스케줄링" image="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80" link="/project/os/" >}}</div>
          <div class="col">{{< card_compact title="스택 계산기" meta="C++ 자료구조" image="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1200&q=80" link="/project/stack/" >}}</div>
          <div class="col">{{< card_overlay title="DB 설계" subtitle="전주 문화관광" image="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1200&q=80" link="/project/database/" >}}</div>
          <div class="col">{{< card_overlay title="운영체제" subtitle="동기화/스레드" image="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80" link="/project/os/" >}}</div>
          <div class="col">{{< card_overlay title="스택 계산기" subtitle="중위→후위" image="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1200&q=80" link="/project/stack/" >}}</div>
          <div class="col">{{< card_compact title="DB 설계" meta="정규화" image="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1200&q=80" link="/project/database/" >}}</div>
          <div class="col">{{< card_compact title="운영체제" meta="교착상태" image="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80" link="/project/os/" >}}</div>
          <div class="col">{{< card_compact title="스택 계산기" meta="스택 연산" image="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1200&q=80" link="/project/stack/" >}}</div>
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