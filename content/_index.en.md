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
      title: Self-Intro Slide
      text: |
        <div class="cc-slider" data-autoplay="true" data-interval="4200">
          <div class="cc-slider__track">
            <figure>
              <img src="https://images.unsplash.com/photo-1500576992153-0271099def59?auto=format&fit=crop&w=1600&q=80" alt="Hello sticker" style="height:360px;" />
              <figcaption>Hi, I’m Sookyung — JBNU Computer & AI junior.</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1600&q=80" alt="Code" style="height:360px;" />
              <figcaption>Building UX with React and TypeScript.</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1526378722419-350d4f3de0bb?auto=format&fit=crop&w=1600&q=80" alt="Database" style="height:360px;" />
              <figcaption>Applying DB design and normalization to projects.</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80" alt="Operating System" style="height:360px;" />
              <figcaption>Learning processes, threads, and synchronization.</figcaption>
            </figure>
            <figure>
              <img src="https://images.unsplash.com/photo-1522075469751-3a6694fb2f61?auto=format&fit=crop&w=1600&q=80" alt="Teamwork" style="height:360px;" />
              <figcaption>Growing with teammates and sharing what I learn.</figcaption>
            </figure>
          </div>
          <div class="cc-slider__dots"></div>
        </div>

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
