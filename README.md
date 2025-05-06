# 💄 Skin Analyzer Big Data Platform

### 피부타입 맞춤 화장품 추천을 위한 성분 · 리뷰 기반 분석 및 시각화 플랫폼

---

## 📌 프로젝트 개요

화장품 성분과 리뷰 데이터를 기반으로 피부타입별 선호 성분을 분석하고, 트렌드 및 추천 제품을 시각화하는 빅데이터 기반 플랫폼입니다.

- **데이터 수집**: 화장품 리뷰, 성분, 평점 (크롤링 또는 API)
- **데이터 처리**: PySpark + Hadoop
- **분석 시각화**: Streamlit + Plotly
- **배포**: Streamlit Cloud 또는 AWS Free Tier
- **CI/CD**: GitHub Actions + Docker

---

## 🧱 기술 스택

| 단계         | 기술                          |
|--------------|-------------------------------|
| 수집         | Python, BeautifulSoup / API   |
| 저장 및 처리 | PySpark, Hadoop (HDFS), Parquet |
| 분석         | PySpark, Pandas, NumPy        |
| 시각화       | Streamlit, Plotly             |
| 배포         | Streamlit Cloud / AWS EC2     |
| CI/CD        | GitHub Actions, Docker        |

---

## 🗂️ 디렉토리 구조 (예정)

```bash
skin-analyzer-bigdata/
├── data/                    # 크롤링된 원본 데이터
├── etl/                     # 수집/전처리 스크립트
├── analysis/                # 분석 로직 및 결과
├── web/                     # Streamlit 웹 대시보드
├── docker/                  # Docker 관련 설정
├── .github/workflows/       # GitHub Actions CI/CD
└── README.md
