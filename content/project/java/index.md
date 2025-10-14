---
title: 자바 (Java)
summary: 객체지향 작업 관리 시스템
authors: []
tags: [Java, 객체지향, 작업관리, OOP, 시스템설계]
categories: [Programming Languages]
date: '2024-01-01T00:00:00Z'
slides:
  theme: white
  highlight_style: dracula

# Featured image
image:
  caption: 'Object-Oriented Task Management System'
  focal_point: ''
  preview_only: false
  filename: featured.png

# Projects (optional).
projects: []
searchable: true
---

<div class="justify-text">
자바로 구축된 완전한 기능의 작업 관리 애플리케이션으로, 상속, 다형성, 캡슐화를 포함한 객체지향 프로그래밍 원칙을 적용했습니다. 사용자 인증, 작업 스케줄링 및 파일 I/O 작업을 통한 데이터 영속성 기능을 제공합니다.

## 주요 기능

### 👤 사용자 관리
- **사용자 인증**: 로그인/로그아웃 시스템
- **권한 관리**: 역할 기반 접근 제어
- **프로필 관리**: 사용자 정보 수정

### 📋 작업 관리
- **작업 생성**: 새로운 작업 추가
- **작업 수정**: 기존 작업 편집
- **상태 관리**: 진행 상황 추적
- **우선순위 설정**: 중요도별 분류

### ⏰ 스케줄링
- **날짜 관리**: 마감일 설정 및 알림
- **반복 작업**: 주기적 작업 자동 생성
- **캘린더 뷰**: 시각적 일정 관리

## 객체지향 설계

### 🏗️ 클래스 구조
- **User 클래스**: 사용자 정보 캡슐화
- **Task 클래스**: 작업 데이터 모델
- **TaskManager 클래스**: 작업 관리 로직
- **FileHandler 클래스**: 데이터 영속성

### 🔄 OOP 원칙 적용
- **상속**: 공통 기능의 재사용
- **다형성**: 인터페이스 기반 설계
- **캡슐화**: 데이터 보호 및 은닉
- **추상화**: 복잡성 감소

## 기술 스택

- **언어**: Java 11+
- **IDE**: IntelliJ IDEA, Eclipse
- **빌드 도구**: Maven, Gradle
- **테스팅**: JUnit 5
- **데이터 저장**: 파일 I/O (JSON, CSV)

## 핵심 클래스 구조

### Task 클래스
```java
public class Task {
    private String id;
    private String title;
    private String description;
    private Priority priority;
    private Status status;
    private LocalDateTime dueDate;
    
    // Constructor, getters, setters
}
```

### TaskManager 인터페이스
```java
public interface TaskManager {
    void addTask(Task task);
    void updateTask(String id, Task task);
    void deleteTask(String id);
    List<Task> getAllTasks();
}
```

## 학습 성과

이 프로젝트를 통해 자바의 객체지향 프로그래밍 원칙을 실제 애플리케이션에 적용하는 방법을 학습했으며, 대규모 소프트웨어 설계의 기초를 다질 수 있었습니다.
</div>
