<div align="center">

# SWP1 Graph App

A small WSGI practice project that renders a quadratic graph from query parameters.

![Status](https://img.shields.io/badge/status-coursework-0A1317?style=for-the-badge)
![Language](https://img.shields.io/badge/language-Python-0064E0?style=for-the-badge)
![Topic](https://img.shields.io/badge/topic-WSGI%20%2B%20graph-444950?style=for-the-badge)

</div>

---

## Overview

SWP1 is a small Python web programming exercise. It reads query parameters, computes a quadratic function, draws a graph with Matplotlib, and serves a simple HTML response through a WSGI-style `application` function.

## What It Shows

- Basic WSGI request/response structure
- Query string parsing
- Quadratic function visualization
- Matplotlib graph generation
- Separation between HTML template and application logic

## Structure

| File | Role |
| --- | --- |
| `graph.py` | WSGI application and graph generation logic |
| `template.py` | HTML template |
| `environ.py` | Environment/request practice file |

## Note

This is a learning exercise for Python web basics and visualization, not a deployed web service.

---

## 한국어 버전

# SWP1 Graph App

query parameter를 받아 이차함수 graph를 그리는 작은 WSGI 실습 프로젝트입니다.

## 개요

SWP1은 Python web programming 기초를 연습한 프로젝트입니다. query parameter를 읽고, quadratic function을 계산한 뒤, Matplotlib으로 graph를 생성하고 WSGI-style `application` function을 통해 간단한 HTML response를 제공합니다.

## 보여주는 내용

- 기본 WSGI request/response structure
- query string parsing
- quadratic function visualization
- Matplotlib graph generation
- HTML template과 application logic 분리

## 구조

| 파일 | 역할 |
| --- | --- |
| `graph.py` | WSGI application 및 graph generation logic |
| `template.py` | HTML template |
| `environ.py` | environment/request practice file |

## 참고

deployed web service가 아니라 Python web basics와 visualization을 위한 learning exercise입니다.
