# 🌞 Sunspots (태양 흑점 분석)

태양 흑점 데이터를 수집하고 분석하는 Python 프로젝트입니다.

## 📋 개요

이 프로젝트는 태양 흑점의 활동 패턴을 분석하고 시각화하는 데 중점을 두고 있습니다. 역사적 태양 흑점 데이터를 활용하여 태양 활동의 주기성과 트렌드를 파악합니다.

## ✨ 주요 기능

- 📊 **데이터 분석**: 태양 흑점 데이터의 통계 분석
- 📈 **시각화**: 다양한 차트를 통한 데이터 시각화
- 🔄 **패턴 인식**: 태양 활동의 주기성 감지
- 💾 **데이터 처리**: 효율적인 데이터 전처리 및 정제

## 🚀 빠른 시작

### 요구사항

- Python 3.8 이상
- pip 패키지 매니저

### 설치

```bash
# 저장소 클론
git clone https://github.com/ppck75/sunspots.git
cd sunspots

# 의존성 설치
pip install -r requirements.txt
```

### 기본 사용법

```python
from sunspots import analyze

# 데이터 분석
result = analyze.perform_analysis()

# 결과 시각화
analyze.visualize(result)
```

## 📁 프로젝트 구조

```
sunspots/
├── README.md                 # 프로젝트 설명 (이 파일)
├── requirements.txt          # Python 의존성
├── sumspots/                 # 메인 패키지
│   ├── __init__.py
│   ├── analyze.py           # 분석 모듈
│   ├── visualize.py         # 시각화 모듈
│   └── data/                # 데이터 디렉토리
└── tests/                   # 테스트 코드
```

## 📚 사용 예제

### 데이터 로드 및 분석

```python
from sumspots import data_loader, analyzer

# 데이터 로드
sunspot_data = data_loader.load_data()

# 기본 통계
stats = analyzer.get_statistics(sunspot_data)
print(f"평균: {stats['mean']}")
print(f"최대값: {stats['max']}")
```

### 시각화

```python
from sumspots import visualizer

# 시계열 그래프
visualizer.plot_timeseries(sunspot_data)

# 주기성 분석 그래프
visualizer.plot_periodicity(sunspot_data)
```

## 🤝 기여

이 프로젝트에 기여하고 싶으신 분들을 환영합니다!

1. 이 저장소를 포크(Fork)하세요
2. 기능 브랜치를 만드세요 (`git checkout -b feature/AmazingFeature`)
3. 변경사항을 커밋하세요 (`git commit -m 'Add some AmazingFeature'`)
4. 브랜치에 푸시하세요 (`git push origin feature/AmazingFeature`)
5. Pull Request를 열어주세요

## 📖 문서

자세한 사용법과 API 문서는 [Wiki](https://github.com/ppck75/sunspots/wiki)를 참고해주세요.

## 🐛 이슈 및 피드백

문제가 발생하거나 개선 제안이 있으신 경우:
- [이슈 트래커](https://github.com/ppck75/sunspots/issues)에서 이슈를 생성해주세요
- 또는 [토론](https://github.com/ppck75/sunspots/discussions)에서 의견을 나누어주세요

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 LICENSE 파일을 참고하세요.

## 🔗 참고 자료

- [NOAA 태양 흑점 데이터](https://www.solarserver.com)
- [태양 활동 주기](https://solarscience.msfc.nasa.gov)
- [Python 과학 계산 라이브러리](https://scipy.org)

## 📧 문의

질문이나 제안사항이 있으시면 이슈를 등록하거나 discussions에서 연락주세요.

---

**마지막 업데이트**: 2026년 5월 5일
