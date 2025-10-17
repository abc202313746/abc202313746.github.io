---
title: "Home"
type: landing
sections:
  - block: about.avatar
    section_id: about
    content:
      username: admin
      text: |
        <p class="justify-text" style="color: #FFC107;">
        👋 Hello! I'm <strong>SookYoung In</strong>, a university student aspiring to become a front-end developer.<br>
        I am particularly interested in technologies like React and TypeScript.<br>
        My goal is to create the best, most helpful web experiences for users.
        </p>
        
        Check out my [resumé](/uploads/resume.pdf) and portfolio below 😍
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
      title: "Projects"
      subtitle: ""
      count: 3
      page_type: project
      text: ""
    design:
      view: masonry
      columns: "2"

  - block: portfolio
    section_id: programming-languages
    content:
      title: "Programming Languages"
      subtitle: ""
      text: ""
      filters:
        folders:
          - languages
      count: 3
    design:
      view: compact
      columns: '3'


  - block: portfolio
    section_id: dream-goals
    content:
      title: "Dream Goals"
      subtitle: ""
      count: 3
      filters:
        folders:
          - goals
      text: ""
    design:
      view: showcase
      columns: "1"
    active: true
    weight: 50


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
      interval: '3500'

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

  - block: accomplishments
    section_id: goals
    content:
      title: Career Goals & Interests
      subtitle: ''
      text: ""
      date_format: Jan 2006
      items:
        - title: Frontend Development Expertise
          organization: Personal Goal
          date_start: '2024-01-01'
          date_end: ''
          description: '<span class="justify-text">Becoming proficient in modern frontend technologies, particularly React and TypeScript, to create intuitive and maintainable user interfaces. I aim to master component-based architecture, state management, and responsive design principles.</span>'
        - title: Full-Stack Development
          organization: Future Aspiration
          date_start: '2024-01-01'
          date_end: ''
          description: '<span class="justify-text">Expanding my skillset to include backend technologies and database management to become a well-rounded developer. I want to understand the complete web development lifecycle from database design to user interface.</span>'
        - title: Open Source Contribution
          organization: Community Goal
          date_start: '2024-01-01'
          date_end: ''
          description: '<span class="justify-text">Contributing to open source projects to give back to the developer community and improve my collaborative coding skills. I believe in the power of community-driven development and want to be part of it.</span>'
        - title: Problem-Solving Through Technology
          organization: Core Interest
          date_start: '2024-01-01'
          date_end: ''
          description: '<span class="justify-text">Using technology to solve real-world problems and create meaningful impact. I am particularly interested in developing applications that improve user experience and make complex tasks more accessible.</span>'

  - block: markdown
    content:
      title: ""
      text: |
        <div style="text-align: center; margin: 60px 0; padding: 40px 20px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 20px; color: white;">
          <h2 style="margin-bottom: 20px; font-weight: 700;">📄 Resume Download</h2>
          <p style="margin-bottom: 30px; font-size: 1.1rem; opacity: 0.9;">Check out my detailed experience and project information!</p>
          <a href="/uploads/resume.pdf" download="SookYoung_In_Resume.pdf" 
             style="display: inline-block; padding: 15px 40px; background: white; color: #667eea; text-decoration: none; border-radius: 50px; font-weight: 700; font-size: 1.1rem; transition: all 0.3s ease; box-shadow: 0 4px 15px rgba(0,0,0,0.2);"
             onmouseover="this.style.transform='translateY(-3px)'; this.style.boxShadow='0 6px 20px rgba(0,0,0,0.3)';"
             onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 4px 15px rgba(0,0,0,0.2)';">
            <i class="fas fa-download" style="margin-right: 10px;"></i>Download Resume
          </a>
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

        <div class="map-embed" style="margin-top:12px;">
          <iframe
            src="https://www.openstreetmap.org/export/embed.html?bbox=127.1240%2C35.8440%2C127.1340%2C35.8500&layer=mapnik&marker=35.8469%2C127.1295"
            width="100%"
            height="360"
            style="border:0;border-radius:8px;"
            loading="lazy"
          ></iframe>
        </div>
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