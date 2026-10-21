---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
kernelspec:
  display_name: Python 3
  language: python
  name: python3
title: Sandbox
abstract: ""
authors:
  - name: Charlih Chen
exports:
  - format: typst
    template: lapreprint-typst
    output: _build/exports/typst/
---

# Sandbox

## test1

## Future people AKA. 未来人

| No | Name | Year From | Alternative name | Soical media | Account name | Country | Appeared in |
|----|-----|------------|-----------------|--------------|--------------|--------|-------------|
| 1 | 國分玲 (Rina Kunitsuki) | 2058 | 2058未来人 | Twitter or SNS | bV6eBJOQc7bUvgO | Japan | 2019-2020 |
| 2 | KFK | 2048 | 2048未来人 |  | | Japan | |
| 3 | 2062 | Yomino Yuna | 2062未来人 | 2ch (日本論壇) |  | Japan | 2012 |
| 4 | John Titor | 2036 | 2036未来人  |  | | | 2000 |
| 5 | 2370 | 2370 | 2370未来人 |   | | | 2024 |
| 6 | 2582 | 2582 | 2582未来人 |   | | | 2024 |

## A=B database (A=B.json)

### JSON#1 (A.json)
| A | eq2(B) | tag1 | tag2 | tag3 | tag4 | tag5 |
|---|--------|------|------|------|------|------|
| Chinese | 中文 | English to Chinese | 英中翻譯 | dictionary | 字典 | noun |

### JSON#2 (Email.json)
| Email | Username | Frist name | Last name | | | |
|-------|----------|------------|-----------|-|-|-|
| A | eq2(B) | tag1 | tag2 | tag3 | tag4 | tag5 |
| jdoe@email.com | jdoe | John | Doe | | | |

### JSON#3 (SubmitDate.json)
| Submit date | By | AB |  | | | |
|-------|----------|------------|-----------|-|-|-|
| A | eq2(B) | tag1 | tag2 | tag3 | tag4 | tag5 |
| ThatDay() | jdoe@email.com | **Chinese** & **中文** | | | | |

JSON#2 submits the JSON#1 on JSON#3

### JSON#4 (Rating.json)

(Rating scale: -1, 0, 1 AKA Wrong(-1), No comment(0), Correct(1))

| Rating | AB | By | Note for the AB | | | |
|-------|----------|------------|-----------|-|-|-|
| A | eq2(B) | tag1 | tag2 | tag3 | tag4 | tag5 |
| -1 or 0 or 1 |  **Chinese** & **中文** |  jroe@mail.net | A is not equal to B, please correct it. Thank you. | | | |

JSON#2 rates the JSON#1. If rate is -1, JSON#2 will write the correcting note on the "Note for the AB".

### Diagram of the AB databse

<img width="1256" height="781" alt="image" src="https://github.com/user-attachments/assets/047220a7-38a6-4770-847b-81cda6467278" />

### A=B files relationship

<img width="1506" height="537" alt="image" src="https://github.com/user-attachments/assets/e3e688f2-53b8-4d9d-bcd0-1d9e7416e204" />

A.json 檔案設計為初始為空，並由使用者群體共同建構－全球最終使用者都是導入來源。

## Free tier SQL DB host service

| Service         | Database Engine              | Free Storage                   | Key Limit           | Always-On            | Best For                                                              |
|-----------------|------------------------------|--------------------------------|---------------------|----------------------|-----------------------------------------------------------------------|
| **Supabase**    | PostgreSQL                   | 500 MB DB + 1 GB File          | 50k MAUs            | Pauses after 7 days  | Full-stack apps needing auth, storage, and realtime                   |
| **Neon**        | PostgreSQL                   | 0.5 GB                         | 190 compute hrs/mo  | Cold starts (~500ms) | Developers who want serverless Postgres and git-like branching        |
| **Turso**       | libSQL (SQLite)              | 9 GB                           | 1B row reads/mo     | Yes                  | Read-heavy, globally distributed apps needing low latency             |
| **CockroachDB** | PostgreSQL (wire-compatible) | 10 GiB                         | 50M Request Units   | Scales to zero       | Apps that need enterprise-grade resilience and horizontal scale       |
| **TiDB Cloud**  | MySQL (compatible)           | 5 GiB (row) + 5 GiB (columnar) | 50M RUs, 5 clusters | Yes                  | Data-intensive apps needing real-time analytics on transactional data |
