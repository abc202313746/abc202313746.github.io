---
title: "SookYoung In - Computer Science Student Portfolio"
description: "SookYoung In (인숙영) - Computer Science Student at Jeonbuk National University. Frontend Developer Portfolio featuring React, TypeScript, Database Design, Operating Systems, and Data Structures projects."
keywords: "SookYoung In, 인숙영, Jeonbuk National University, 전북대학교, Computer Science, Frontend Developer, React, TypeScript, Portfolio"
# Homepage
type: landing
image:
  filename: 'uploads/og-image.png'
  caption: 'SookYoung In Portfolio'
searchable: true
tags: ["SookYoung In", "인숙영", "Jeonbuk National University", "전북대학교", "전북대", "JBNU", "Computer Science", "Computer AI", "Frontend", "React", "TypeScript", "Jeonju", "Jeonbuk State"]
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
      count: 3
      page_type: project
      filters:
        folders: ["project"]
      text: ""
    design:
      view: card
      columns: '3'

  - block: markdown
    section_id: programming-languages
    content:
      title: "Programming Languages"
      subtitle: ""
      text: |
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin: 30px 0;">
          <div style="padding: 25px; border: 2px solid #7c4dff; border-radius: 12px; background: linear-gradient(135deg, #f8f9ff 0%, #ffffff 100%); box-shadow: 0 4px 15px rgba(124, 77, 255, 0.1); transition: transform 0.3s ease;" onmouseover="this.style.transform='translateY(-5px)'" onmouseout="this.style.transform='translateY(0)'">
            <div style="display: flex; align-items: center; margin-bottom: 15px;">
              <span style="font-size: 2.5rem; margin-right: 15px;">🐍</span>
              <h3 style="color: #7c4dff; margin: 0; font-size: 1.4rem; font-weight: 700;">Python</h3>
            </div>
            <p style="margin: 0; color: #555; line-height: 1.6; font-size: 1rem;">
              <strong>Python Data Analysis and Visualization Project</strong><br>
              <span style="color: #777; font-size: 0.9rem;">A comprehensive data analysis project utilizing Python's powerful libraries including Pandas, NumPy, and Matplotlib. This project demonstrates proficiency in data manipulation, statistical analysis, and creating insightful visualizations to derive meaningful insights from complex datasets.</span>
            </p>
          </div>
          
          <div style="padding: 25px; border: 2px solid #7c4dff; border-radius: 12px; background: linear-gradient(135deg, #f8f9ff 0%, #ffffff 100%); box-shadow: 0 4px 15px rgba(124, 77, 255, 0.1); transition: transform 0.3s ease;" onmouseover="this.style.transform='translateY(-5px)'" onmouseout="this.style.transform='translateY(0)'">
            <div style="display: flex; align-items: center; margin-bottom: 15px;">
              <span style="font-size: 2.5rem; margin-right: 15px;">🔧</span>
              <h3 style="color: #7c4dff; margin: 0; font-size: 1.4rem; font-weight: 700;">C Language</h3>
            </div>
            <p style="margin: 0; color: #555; line-height: 1.6; font-size: 1rem;">
              <strong>Custom Memory Allocator Implementation in C</strong><br>
              <span style="color: #777; font-size: 0.9rem;">A low-level programming project implementing a custom memory allocator in C, demonstrating deep understanding of memory management, pointer manipulation, and system-level programming. This project showcases efficient memory allocation strategies and optimization techniques for improved performance.</span>
            </p>
          </div>
          
          <div style="padding: 25px; border: 2px solid #7c4dff; border-radius: 12px; background: linear-gradient(135deg, #f8f9ff 0%, #ffffff 100%); box-shadow: 0 4px 15px rgba(124, 77, 255, 0.1); transition: transform 0.3s ease;" onmouseover="this.style.transform='translateY(-5px)'" onmouseout="this.style.transform='translateY(0)'">
            <div style="display: flex; align-items: center; margin-bottom: 15px;">
              <span style="font-size: 2.5rem; margin-right: 15px;">☕</span>
              <h3 style="color: #7c4dff; margin: 0; font-size: 1.4rem; font-weight: 700;">Java</h3>
            </div>
            <p style="margin: 0; color: #555; line-height: 1.6; font-size: 1rem;">
              <strong>Object-Oriented Task Management System</strong><br>
              <span style="color: #777; font-size: 0.9rem;">A full-featured task management application built with Java, applying object-oriented programming principles including inheritance, polymorphism, and encapsulation. The system features user authentication, task scheduling, and data persistence using file I/O operations.</span>
            </p>
          </div>
        </div>
    design:
      background:
        color: 'white'
      spacing:
        padding: ['40px', '0', '40px', '0']

  - block: portfolio
    section_id: portfolio-showcase
    content:
      title: "Project Showcase"
      subtitle: ""
      count: 3
      page_type: project
      text: ""
    design:
      view: showcase
      columns: "1"

  - block: portfolio
    section_id: portfolio-masonry
    content:
      title: "Project Gallery"
      subtitle: ""
      count: 3
      page_type: project
      text: ""
    design:
      view: masonry
      columns: "2"
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