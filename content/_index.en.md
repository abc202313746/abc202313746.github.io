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
      text: ""
    design:
      view: card
      columns: '3'
  - block: slider
    content:
      text: ""
      slides:
        - title: "Frontend Portfolio"
          content: "Building delightful UX with React and TypeScript"
          background:
            image:
              filename: unsplash-coffee-keyboard.jpg
        - title: "Collaboration"
          content: "Growing via code reviews and pairing"
          background:
            image:
              filename: unsplash-developer-desk.jpg
        - title: "Learning by Building"
          content: "From idea to demo"
          background:
            image:
              filename: slider-math.svg
    design:
      slide_height: '300px'
      slide_min_width: '90%'

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