# 2026 하반기 Physical AI 동향

모델이 몸을 얻은 뒤 무엇이 달라지는지를, 알고리즘의 성능보다 **반복 실행·검증·복구·운영 비용**의 관점에서 설명하는 한국어 동향서다.

이 저장소는 두 층으로 구성된다.

1. **원책** — Physical AI의 기술 지형과 2026년 하반기부터 2030년까지의 변화를 9개 장으로 설명한다.
2. **심화 리딩 가이드** — 원책의 각 장에 직접 연결되는 논문을 20편씩, 총 180편 선정해 질문·핵심 구조·읽는 이유·적용 경계·원책과의 연결을 해설한다.

## 바로 읽기

### 원책

- [웹에서 바로 읽기](https://gisbi-kim.github.io/physical-ai-trends-2026/)
- [PDF 내려받기](./physical-ai-trends-2026.pdf)
- [LaTeX 원문](./physical-ai-trends-2026.tex)

### 심화 리딩 자료

- [180편 논문 목록과 원문 링크](./reading-materials/paper-catalog/README.md)
- [심화 리딩 가이드 웹에서 바로 읽기](https://gisbi-kim.github.io/physical-ai-trends-2026/reading-materials/guidebook/)
- [심화 리딩 가이드 PDF](./reading-materials/guidebook/physical-ai-deep-reading-guide.pdf)
- [심화 리딩 가이드 Markdown](./reading-materials/guidebook/physical-ai-deep-reading-guide.md)
- [심화 리딩 가이드 LaTeX](./reading-materials/guidebook/physical-ai-deep-reading-guide.tex)
- [리딩 자료 구성 안내](./reading-materials/README.md)

## 원책과 리딩 가이드의 관계

원책은 Physical AI를 빠르게 조망하는 개론서다. 심화 리딩 가이드는 원책의 문장을 논문 수준의 근거와 논쟁으로 내려 읽기 위한 두 번째 책이다.

논문은 단순히 주제별로 모으지 않았다. 각 장의 주장에 대해 다음 역할이 균형을 이루도록 구성했다.

- 개념과 문제 설정을 잡는 **기초 연구**
- 시스템의 모듈과 인터페이스를 보여주는 **구조 연구**
- 정량 결과와 실제 배포 조건을 확인하는 **실험 연구**
- 실패, 안전, 일반화 한계를 드러내는 **비판 연구**
- 데이터·버전·검증·복구를 다루는 **운영 연구**

각 논문 해설은 다음 다섯 질문에 답한다.

1. 이 연구가 푸는 질문은 무엇인가.
2. 핵심 구조와 주장은 무엇인가.
3. 이 장에서 왜 읽어야 하는가.
4. 결과를 어디까지 믿을 수 있는가.
5. 원책의 어떤 논지와 연결되는가.

## 9개 장과 180편의 읽기 지도

| 장 | 원책의 질문 | 심화 리딩의 초점 | 논문 |
|---:|---|---|---:|
| 1 | 왜 지금 Physical AI인가 | 기반 모델, 물리 일관성, 폐루프, 신뢰 가능한 반복 실행 | 20 |
| 2 | 명령을 로봇 행동으로 바꾸는 법 | VLA, 계층형 정책, 확산·플로 행동, 실시간 제어 | 20 |
| 3 | 로봇은 무엇을 보고 있다고 믿는가 | 3D·BEV·점유, 공간 기억, 촉각, 센서 융합 | 20 |
| 4 | 기억하고 상상하고 계획하는 로봇 | 월드모델, 장기 메모리, 과업·동작 계획, 실패 복구 | 20 |
| 5 | 몸이 달라지면 지능도 달라진다 | 조작, 휴머노이드, 보행, 항법, 자율주행, UAV, 기체 전이 | 20 |
| 6 | 데이터는 쌓는 것이 아니라 운영하는 것이다 | 시연·인간 영상·합성 데이터, 데이터 혼합, 현장 적응 | 20 |
| 7 | 한 대의 로봇에서 하나의 조직으로 | 다중 로봇 협력, 공유 상태, 통신 장애, 버전·책임 경계 | 20 |
| 8 | 데모를 제품으로 바꾸는 법 | 평가, 강건성, 안전 보증, 효율, 실패 감지와 복구 | 20 |
| 9 | 2026년 하반기에서 2030년까지 | 정책 코어, 세계 상태, 메모리, 제어기, 검증기, 운영 로그 | 20 |
| **합계** |  | **중복 없는 공개 논문 180편** | **180** |

## 권장 사용법

1. 원책에서 관심 장의 문제 설정과 결론을 읽는다.
2. [논문 목록](./reading-materials/paper-catalog/README.md)에서 제목·저자·연도·베뉴 또는 공개 상태를 확인한다.
3. 각 논문의 초록 링크와 PDF 링크를 통해 원문으로 이동한다.
4. [심화 리딩 가이드 웹 뷰어](https://gisbi-kim.github.io/physical-ai-trends-2026/reading-materials/guidebook/)에서 질문과 적용 경계를 먼저 확인한 뒤 논문을 읽는다.
5. 서로 다른 역할의 논문을 비교해 한 편의 성능 수치가 아니라 시스템 전체의 증거를 판단한다.

연구자는 2–6장의 모델·인지·계획·기체·데이터 축을, 제품 책임자는 7–8장의 조직·검증·복구 축을, 경영·기술 전략 담당자는 1장과 9장의 전환 신호를 먼저 읽을 수 있다.

## 논문 링크와 PDF 정책

이 저장소에는 제3자 논문 PDF를 커밋하지 않는다.

- 논문 목록은 제목, 전체 저자, arXiv 최초 공개 연도, 베뉴 또는 공개 상태, arXiv 초록, 공개 PDF 링크를 제공한다.
- 링크는 각 출판사와 공개 저장소의 이용 조건을 따른다.
- 논문의 공개 상태, 버전, 베뉴 표기는 시간이 지나며 달라질 수 있다.
- 심화 가이드의 해설은 원문을 대체하지 않으며, 결과의 적용 범위는 각 논문의 실험 조건을 기준으로 판단해야 한다.

리딩셋 구성 과정에서는 기준일 당시 공개된 180편의 PDF, 총 3,664쪽을 내려받아 파일 헤더·페이지 수·크기·SHA-256을 로컬에서 확인했다. 이 검증용 원문 파일과 해시는 저장소 배포 대상에 포함하지 않는다.

## 선정 및 해설 기준

- **기준일:** 2026-07-26
- **구성:** 9개 장 × 20편
- **고유 논문:** 180편
- **연결 원칙:** 논문의 제목 키워드가 아니라 원책의 주장, 시스템 역할, 실패 조건과의 직접 연결
- **근거 우선순위:** arXiv 메타데이터의 journal reference·DOI·공식 comment를 우선하고, 베뉴를 확인할 수 없는 경우에는 `arXiv preprint`로 구분
- **해설 경계:** 보고된 결과와 저자의 주장, 이 저장소의 해석을 혼동하지 않도록 질문·핵심·읽는 이유·한계·연결을 분리

이 자료는 2026년 하반기 연구·산업 동향을 정리한 스냅샷이다. 이후 논문 개정, 정식 출판, 철회, 링크 변경은 [논문 목록](./reading-materials/paper-catalog/README.md)의 후속 갱신 대상이다.

## 로컬 빌드

두 책 모두 XeLaTeX를 사용한다. TeX Live와 문서에 지정된 한글·라틴 글꼴이 설치된 환경에서 다음과 같이 빌드할 수 있다.

```powershell
latexmk -xelatex -interaction=nonstopmode physical-ai-trends-2026.tex
latexmk -xelatex -interaction=nonstopmode reading-materials/guidebook/physical-ai-deep-reading-guide.tex
```

원책은 `Noto Sans`, `NanumMyeongjo`, `NanumGothic`을 사용한다. 심화 가이드는 `DejaVu Sans`, `Noto Serif CJK KR`, `Noto Sans CJK KR`을 사용한다.

## 저장소 구조

```text
.
├─ README.md
├─ index.html
├─ physical-ai-trends-2026.tex
├─ physical-ai-trends-2026.pdf
└─ reading-materials/
   ├─ README.md
   ├─ paper-catalog/
   │  └─ README.md
   └─ guidebook/
      ├─ index.html
      ├─ physical-ai-deep-reading-guide.md
      ├─ physical-ai-deep-reading-guide.tex
      └─ physical-ai-deep-reading-guide.pdf
```

GitHub Pages의 루트 주소는 원책을, [`/reading-materials/guidebook/`](https://gisbi-kim.github.io/physical-ai-trends-2026/reading-materials/guidebook/)은 심화 리딩 가이드를 브라우저 PDF 뷰어로 연다.
