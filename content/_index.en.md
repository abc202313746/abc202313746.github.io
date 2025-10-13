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
  - block: slider
    content:
      items:
        - title: "Frontend Portfolio"
          subtitle: "React · TypeScript"
          image:
            filename: uploads/unsplash-frontend.svg
        - title: "Database & OS"
          subtitle: "Course Projects"
          image:
            filename: uploads/unsplash-systems.svg
        - title: "Learning by Building"
          subtitle: "From idea to demo"
          image:
            filename: uploads/unsplash-build.svg

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

  - block: collection
    content:
      title: Projects
      count: 9
      filters:
        folders: ["project"]
    design:
      columns: 3
      view: card

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
