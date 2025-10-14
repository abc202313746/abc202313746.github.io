---
# Homepage
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
      title: Projects
      subtitle: ''
      count: 9
      page_type: project
      filters:
        folders: ["project"]
      text: ""
    design:
      view: card
      columns: '3'
  - block: slider
    content:
      text: ""
      slides:
        - title: "React · TypeScript"
          content: "Maintainable UIs through component design and state management"
          background:
            image:
              filename: /uploads/1_unsplash.jpg
        - title: "Learning by Building"
          content: "Start small, iterate fast, and prove with results"
          background:
            image:
              filename: /uploads/2_unsplash.jpg
        - title: "Algorithms"
          content: "Efficiency via complexity analysis and focused optimizations"
          background:
            image:
              filename: /uploads/3_unsplash.jpg
    design:
      is_fullscreen: false
      slide_height: '420px'
      interval: 0

  - block: experience
    section_id: experience
    content:
      title: Experience
      subtitle: ''
      text: ""
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
      title: ""
      text: |
        {{< fab >}}
---