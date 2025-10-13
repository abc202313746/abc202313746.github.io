---
title: "인숙영의 포트폴리오"
type: landing
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


`  - block: slider
-    content:
-      items:
-        - title: "React · TypeScript"
-          subtitle: "관심 있는 언어"
-          image:
-            filename: uploads/slider-react.jpg
-        - title: "DB · OS · 자료구조"
-          subtitle: "수업/실습 정리"
-          image:
-            filename: uploads/slider-class.jpg
-        - title: "Learning by Building"
-          subtitle: "아이디어에서 데모까지"
-          image:
-            filename: uploads/slider-math.jpg
+  - block: slider
+    content:
+      slides:
+        - title: "React · TypeScript"
+          content: "프론트엔드 프로젝트"     
+          background:
+            image:
+              filename: slider-react.jpg     
+        - title: "DB · OS · 자료구조"
+          content: "수업/실습 정리"
+          background:
+            image:
+              filename: slider-class.jpg
+        - title: "Learning by Building"
+          content: "아이디어에서 데모까지"
+          background:
+            image:
+              filename: slider-math.jpg


  - block: markdown
    content:
      title: ""
      text: |
        {{< slider items="/uploads/slider-react.svg|React · TypeScript|프론트엔드 프로젝트; /uploads/slider-class.svg|DB · OS · 자료구조|수업/실습 정리; /uploads/slider-math.svg|Learning by Building|아이디어에서 데모까지" height="360" autoplay="true" interval="4000" >}}

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
---