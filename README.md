# 자연어정보분석 2주차 — 토큰화 알고리즘 탐구

**연세대학교 글로벌인재대학 응용정보공학 | 자연어정보분석 (GAI4008-01-00)**

## 실습 내용

| # | 주제 | 핵심 도구 |
|---|------|-----------|
| 1 | 토큰화 → 복원 라운드트립 | `tiktoken` |
| 2 | 이모지·특수문자 토큰화 실험 | `tiktoken` |
| 3 | 언어별 토큰 효율 비교 (한/영/중/일) | `tiktoken` |
| 4 | 한국어 형태소 분석 + 품사 태깅 | `kiwipiepy` |
| 5 | 나만의 BPE 토크나이저 직접 구현 | Pure Python |

## 파일

- `w02-tokenization-lab.ipynb` — 실습 노트북 (클린 버전)
- `w02-tokenization-lab-executed.ipynb` — 실행 결과 포함 버전

## 환경 설정

```bash
pip install tiktoken transformers kiwipiepy matplotlib
```

## 실행

Google Colab 또는 로컬 Jupyter에서 `w02-tokenization-lab.ipynb`를 열고 순서대로 실행하세요.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xide-projext/yonsei_nlp_2026_w02/blob/main/w02-tokenization-lab.ipynb)
