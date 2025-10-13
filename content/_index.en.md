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

  - block: collection
    content:
      title: Projects
      count: 9
      filters:
        folders: ["project"]
    design:
      view: card
      columns: 3
  - block: slider
    content:
      slides:
        - title: "Frontend Portfolio"
          content: "React · TypeScript"
          background:
            image:
              filename: unsplash-frontend.svg
        - title: "Database & OS"
          content: "Course Projects"
          background:
            image:
              filename: unsplash-systems.svg
        - title: "Learning by Building"
          content: "From idea to demo"
          background:
            image:
              filename: unsplash-build.svg

  # Fallback slider via shortcode (renders even if block: slider is skipped)
  - block: markdown
    content:
      title: ""
      text: |
        {{< slider items="/uploads/unsplash-frontend.svg|Frontend Portfolio|React · TypeScript; /uploads/unsplash-systems.svg|Database & OS|Course Projects; /uploads/unsplash-build.svg|Learning by Building|From idea to demo" height="360" autoplay="true" interval="4000" >}}

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
