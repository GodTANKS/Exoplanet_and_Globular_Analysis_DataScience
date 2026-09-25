# 🪐 외계행성계 탐사 · ✨ 구상성단 데이터사이언스 실습

실제 천문 데이터를 **Google Colab에서 바로 실행**하며 배우는 데이터 기반 천문학 실습 자료입니다.  
두 실습 모두 **Google Colab용 Notebook**으로 제공하며, Python을 처음 접하는 학생·예비교사·교사도 설명을 따라가며 사용할 수 있도록 구성되어 있습니다.

> **처음 오셨다면:** 아래의 **Colab에서 바로 실행** 링크를 누르는 방법이 가장 쉽습니다.  
> 별도의 Python 설치가 필요하지 않습니다.

---

## 🚀 1분 빠른 시작

### A. 외계행성계 탐사
**[▶ Colab에서 외계행성 실습 바로 열기](https://colab.research.google.com/github/GodTANKS/Exoplanet_and_Globular_Analysis_DataScience/blob/main/%EC%99%B8%EA%B3%84%ED%96%89%EC%84%B1%EA%B3%84%20%ED%83%90%EC%82%AC_%EB%B6%84%EC%84%9D%20%EC%BD%94%EB%93%9C.ipynb)**

1. 위 링크를 누릅니다.
2. Google 계정으로 로그인합니다.
3. Colab 메뉴에서 **런타임 → 모두 실행** 또는 셀 왼쪽의 ▶ 버튼을 위에서부터 순서대로 누릅니다.
4. 데이터 업로드 단계가 나오면 이 저장소의 `exoplanet.eu_catalog_2022.csv`를 업로드합니다.
5. 그래프와 분석 결과를 확인하면서 Notebook 안의 탐구 질문을 따라갑니다.

### B. 구상성단 분포로 우리은하 중심 찾기
**[▶ Colab에서 구상성단 실습 바로 열기](https://colab.research.google.com/github/GodTANKS/Exoplanet_and_Globular_Analysis_DataScience/blob/main/%EA%B5%AC%EC%83%81%EC%84%B1%EB%8B%A8_%EB%B6%84%EC%84%9D%20%EC%BD%94%EB%93%9C.ipynb)**

1. 위 링크를 누릅니다.
2. Google 계정으로 로그인합니다.
3. Notebook 셀을 위에서부터 순서대로 실행합니다.
4. 데이터 업로드 단계가 나오면 `globular_clusters_list.csv`를 업로드합니다.
5. 2D·3D 분포와 수치 분석을 이용해 우리은하 중심을 추론합니다.

---

## 📥 실습 파일 다운로드

Colab에서 바로 실행하거나, 실습에 필요한 **Notebook과 CSV가 함께 들어 있는 ZIP 파일**을 내려받을 수 있습니다.

### 🪐 외계행성계 탐사

- **[🚀 Colab에서 실행](https://colab.research.google.com/github/GodTANKS/Exoplanet_and_Globular_Analysis_DataScience/blob/main/%EC%99%B8%EA%B3%84%ED%96%89%EC%84%B1%EA%B3%84%20%ED%83%90%EC%82%AC_%EB%B6%84%EC%84%9D%20%EC%BD%94%EB%93%9C.ipynb)**
- **[📥 Colab용 파일 다운로드](https://raw.githubusercontent.com/GodTANKS/Exoplanet_and_Globular_Analysis_DataScience/main/downloads/exoplanet-colab.zip)** — Notebook + 외계행성 CSV
- **형식:** Google Colab용 Notebook (`.ipynb`)

### ✨ 구상성단으로 우리은하 중심 찾기

- **[🚀 Colab에서 실행](https://colab.research.google.com/github/GodTANKS/Exoplanet_and_Globular_Analysis_DataScience/blob/main/%EA%B5%AC%EC%83%81%EC%84%B1%EB%8B%A8_%EB%B6%84%EC%84%9D%20%EC%BD%94%EB%93%9C.ipynb)**
- **[📥 Colab용 파일 다운로드](https://raw.githubusercontent.com/GodTANKS/Exoplanet_and_Globular_Analysis_DataScience/main/downloads/globular-cluster-colab.zip)** — Notebook + 구상성단 CSV
- **형식:** Google Colab용 Notebook (`.ipynb`)

### 📦 전체 자료

- **[📦 저장소 전체 ZIP 다운로드](https://github.com/GodTANKS/Exoplanet_and_Globular_Analysis_DataScience/archive/refs/heads/main.zip)**

> 개별 `.ipynb` raw 링크 대신 ZIP 다운로드를 제공하므로, 버튼을 누르면 Notebook의 JSON 내용이 브라우저에 펼쳐지지 않고 실습 파일을 바로 받을 수 있습니다.

---

## 🔭 무엇을 배우나요?

### 🪐 외계행성계 탐사
- 적경·적위 기반 외계행성계 공간 분포
- 발견 연도별 탐사 특징
- 외계행성 질량과 항성까지 거리
- 탐사 방법과 질량·공전궤도 장축반경의 관계
- 실제 카탈로그의 결측값 확인과 데이터 정제
- 천문 좌표와 데이터 시각화

### ✨ 구상성단 탐구
- X·Y·Z 좌표 기반 2D·3D 공간 분포
- 구상성단의 공간적 집중도 탐색
- 분포 중심을 이용한 우리은하 중심 위치 추론
- 이상치 확인과 데이터 재처리
- 원본 데이터와 재처리 데이터의 비교

---

## 📁 주요 파일

| 파일 | 용도 |
|---|---|
| `외계행성계 탐사_분석 코드.ipynb` | 외계행성계 탐사 Colab Notebook |
| `exoplanet.eu_catalog_2022.csv` | 외계행성 분석 데이터 |
| `구상성단_분석 코드.ipynb` | 구상성단 분포 분석 Colab Notebook |
| `globular_clusters_list.csv` | 구상성단 분석 데이터 |
| `requirements.txt` | 로컬 Python 실행 시 필요한 패키지 목록 |

---

## 🧭 실습 흐름

**문제 설정 → 데이터 수집 → 데이터 탐색 → 데이터 처리 → 데이터 분석·표현 → 결과 해석**

코드를 단순히 실행하는 데서 끝나지 않고,  
**“이 데이터에서 무엇을 알 수 있는가?”**를 질문하고 그래프와 수치 결과를 해석하는 데 초점을 둡니다.

---

## 💻 실행 환경 안내

- **실행 환경:** Google Colab
- **파일 형식:** `.ipynb`
- **데이터:** 각 다운로드 ZIP에 필요한 CSV 포함

---

## ❓ 처음 실행할 때 자주 묻는 질문

**Q. CSV 파일을 찾지 못한다는 오류가 나옵니다.**  
A. Notebook에서 요구하는 CSV 파일을 Colab 세션에 업로드했는지 확인하세요. 파일명은 바꾸지 않는 것이 가장 안전합니다.

**Q. Colab 세션이 초기화됐습니다.**  
A. Colab은 일정 시간이 지나면 업로드한 파일이 사라질 수 있습니다. CSV를 다시 업로드하고 셀을 처음부터 실행하세요.

**Q. Python을 몰라도 할 수 있나요?**  
A. 가능합니다. 먼저 결과를 실행·관찰한 뒤, 변수와 그래프 옵션을 조금씩 바꾸어 보는 방식으로 시작하는 것을 권장합니다.

---

## 📄 관련 연구

논문 PDF는 코드 저장소에 중복 보관하지 않고 **통합 논문 모음**에서 관리합니다.

**[📚 통합 논문 모음에서 보기](https://GodTANKS.github.io/astronomy-data-science/papers/)**


---

## 🌐 통합 연구·교육 플랫폼

**AI · 데이터 사이언스로 탐구하는 천문학**  
https://GodTANKS.github.io/astronomy-data-science/

기존 연구 아카이브:  
https://sites.google.com/view/astronomydatascience/

---

## 📌 사용 안내

교육 및 연구 목적으로 활용할 경우 관련 논문과 원자료 출처를 함께 표기해 주세요.

---

## 📘 교육·학습 목적 이용 조건

이 저장소에서 **공개된 코드·노트북·교육 자료**는 원저자·원본 저장소·관련 논문 출처를 명시하는 조건으로 **교육·학습 및 비상업적 연구 목적의 복제·수정·재배포가 가능합니다.**

**상업적 판매·유료 서비스·출처 삭제·타인의 독창적 연구 결과인 것처럼 사용하는 행위는 허용하지 않습니다.**

자세한 조건: [EDUCATIONAL_USE_NOTICE.md](EDUCATIONAL_USE_NOTICE.md)

