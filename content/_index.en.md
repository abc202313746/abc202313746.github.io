---
# Homepage
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
      title: Projects
      subtitle: ''
      page_type: project
    design:
      view: masonry
      columns: '1'
  - block: markdown
    content:
      title: Quick Actions
      text: |
        <div class="d-flex flex-wrap gap-2">
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="#top"><i class="fas fa-arrow-up me-2"></i>Top</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="/en/project/"><i class="fas fa-layer-group me-2"></i>Projects</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="/uploads/resume.pdf"><i class="fas fa-file-alt me-2"></i>Resumé (PDF)</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="mailto:isy0110@jbnu.ac.kr"><i class="fas fa-envelope me-2"></i>Contact</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="tel:+821045440797"><i class="fas fa-phone me-2"></i>Call</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="https://maps.google.com/?q=35.8469,127.1295" target="_blank" rel="noopener"><i class="fas fa-map-marker-alt me-2"></i>Map</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="/"><i class="fas fa-globe me-2"></i>Korean/English</a>
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="https://jbnu.macs.or.kr" target="_blank" rel="noopener"><i class="fas fa-external-link-alt me-2"></i>Department</a>
        </div>
  - block: markdown
    content:
      title: Image Slider
      text: |
        {{< slider items="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80|Operating System|xv6 OS; https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1600&q=80|Database|DB Design; https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1600&q=80|Frontend|Frontend Demo; https://images.unsplash.com/photo-1500576992153-0271099def59?auto=format&fit=crop&w=1600&q=80|Hello|Intro" height="360" autoplay="true" interval="4000" >}}

  - block: experience
    section_id: experience
    content:
      title: Experience
      subtitle: ''
      date_format: Jan 2006
      items:
        - title: Club Member
          company: Koala
          location: Jeonbuk National University
          date_start: '2024-03-02'
          date_end: '2024-06-20'
          description: 'Participated in club activities to cultivate algorithmic problem-solving abilities and logical thinking.'
        - title: SW Mentoring Mentee
          company: Online
          location: Jeonbuk National University
          date_start: '2024-09-11'
          date_end: '2024-12-13'
          description: 'Participated in a mentoring program to enhance practical technical skills through interaction with a senior mentor.'

  - block: markdown
    content:
      title: 9-Card Grid
      text: |
        <div class="row row-cols-1 row-cols-md-3 g-3">
          <div class="col">{{< card_compact title="DB Design" meta="Relational Model" image="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1200&q=80" link="/en/project/database/" >}}</div>
          <div class="col">{{< card_compact title="Operating System" meta="Processes/Scheduling" image="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80" link="/en/project/os/" >}}</div>
          <div class="col">{{< card_compact title="Stack Calculator" meta="C++ Data Structure" image="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1200&q=80" link="/en/project/stack/" >}}</div>
          <div class="col">{{< card_overlay title="DB Design" subtitle="Jeonju Culture" image="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1200&q=80" link="/en/project/database/" >}}</div>
          <div class="col">{{< card_overlay title="Operating System" subtitle="Threads/Sync" image="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80" link="/en/project/os/" >}}</div>
          <div class="col">{{< card_overlay title="Stack Calculator" subtitle="Infix → Postfix" image="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1200&q=80" link="/en/project/stack/" >}}</div>
          <div class="col">{{< card_compact title="DB Design" meta="Normalization" image="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1200&q=80" link="/en/project/database/" >}}</div>
          <div class="col">{{< card_compact title="Operating System" meta="Deadlock" image="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80" link="/en/project/os/" >}}</div>
          <div class="col">{{< card_compact title="Stack Calculator" meta="Stack Ops" image="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1200&q=80" link="/en/project/stack/" >}}</div>
        </div>

  - block: contact
    section_id: contact
    content:
      title: Contact
      text: |
        Jeonbuk National University
        
        Contact: [GitHub](https://github.com/abc202313746) · [Instagram](https://www.instagram.com/insookyoung/)
        Phone: [010-4544-0797](tel:+821045440797)
        Email: [isy0110@jbnu.ac.kr](mailto:isy0110@jbnu.ac.kr)
      map:
        provider: OpenStreetMap
        zoom: 15
        center:
          lat: 35.8469
          lng: 127.1295
        markers:
          - title: Jeonbuk National University
            lat: 35.8469
            lng: 127.1295
  - block: markdown
    content:
      text: |
        {{< fab >}}
---
