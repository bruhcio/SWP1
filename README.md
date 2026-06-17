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
