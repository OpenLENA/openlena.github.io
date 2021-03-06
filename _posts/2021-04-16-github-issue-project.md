---
title: "GitHub Issue & Project"
classes: wide
toc: true
categroies:
  - Blog
tags:
  - Blog
---

## Issue
프로젝트 내부적으로 Issue 를 통해 요구사항 / 진적사항 관리가 가능하며,
사용자들이 문의를 올리거나, Bug 리포팅하는 공간으로도 사용이 가능하다. 
Github 에서 Issue 번호가 생성되면. Pull Request 부터, Release Note 작업까지 해당 번호를 다양한 방식으로 연동하여 사용할 수 있다.

### Template
GitHub Settings 의 Features 에서 Issue 에 대한 Template 설정이 가능하다. Template 을 설정하면 issue 생성시 자동으로 Template 에 작성한 형식이 붙여진다.
설정한 내용은 '/.github/ISSUE_TEMPLATE/' 디렉토리에서 확인이 가능하다. 원하는 템플릿을 자유롭개 생성 가능하며, 이슈 유형에 따라 label, assignees 를 지정할 수 있다.

### Label
Issue 마다 Label(bug, enhancement ...) 을 지정할 수 있다. Github 에서 제공하는 Label 이 맘에 들지 않는경우 언제든 추가 생성이 가능하다.
Label 을 잘 달아두면, Release Note 작성시 자동으로 Label 에 따라 이슈를 분기하여 작성이 가능하고. 추후 Issue 검색시에도 용이하다.

### Milestone
Milestone 을 생성하고 Issue 를 맵핑하면 진적률 관리가 가능하다. Issue 가 많아질 경우 Issue 화면만으로 진척률을 관리하기는 어렵다.
Milestone 을 꼭 장성하여 관리하는것이 좋다.

## Project
Kanban 보드를 작성하여 프로젝트의 전체 현황을 파악할 수 있다.
Project 에 생성한 Card 들을 Issue 로 변환할 수 있으며, 반대로 Issue 를 Kanban 보드에 등록할수도 있다.