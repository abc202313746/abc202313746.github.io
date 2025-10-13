# Homepage
type: landing
title: "인숙영의 포트폴리오"
sections:
  - block: hero
    content:
      title: "인숙영 · 포트폴리오"
      text: "프론트엔드(React/TS) & 전공 과제(DB/OS/자료구조)"
      primary_action:
        text: "프로젝트 보기"
        url: "/project/"
      secondary_action:
        text: "게시글 보기"
        url: "/post/"

  - block: slider
    content:
      slides:
        - title: "React · TypeScript"
          subtitle: "프론트엔드 프로젝트"
          image:
            filename: uploads/slider-react.svg
        - title: "DB · OS · 자료구조"
          subtitle: "수업/실습 정리"
          image:
            filename: uploads/slider-class.svg
        - title: "Learning by Building"
          subtitle: "아이디어에서 데모까지"
          image:
            filename: uploads/slider-math.svg

  - block: collection
    content:
      title: "프로젝트"
      count: 9
      filters:
        folders: ["project"]
      sort: "date"
    design:
      view: card
      columns: 3