# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

정적 웹페이지: 구일고등학교 학부모동아리 "티핑포인트"에서 제작하는 행운을 잡아라 룰렛 이벤트 페이지. Canvas를 사용한 인터랙티브 룰렛 게임으로, 학생들이 즐길 수 있는 재미있는 이벤트입니다.

## Tech stack

- 순수 HTML/CSS/JS 정적 페이지. 빌드 도구, 프레임워크, 패키지 매니저 없음.
- 브라우저에서 index.html을 직접 열어 확인 가능해야 한다 (별도 서버/빌드 과정 불필요).

## Structure

- `index.html` — 단일 진입점. 페이지 전체 콘텐츠가 이 파일에 위치.
- `assets/` — CSS, JS, 이미지 등 정적 리소스.

## Deployment

- Git으로 버전 관리하며 GitHub Pages로 배포할 예정.
