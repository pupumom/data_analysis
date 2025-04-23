# 셀프 주유소 vs 일반 주유소 유가 분석

서울시의 주유소 정보를 웹 크롤링하여 셀프 주유소와 일반 주유소의 유가 차이를 분석한 프로젝트입니다.

## 📌 주요 내용
- 오피넷 웹사이트 Selenium 기반 크롤링
- 주유소 상세 정보 수집 (주소, 브랜드, 휘발유/경유 가격, 위도/경도 등)
- 브랜드별, 주유형태별 유가 차이 시각화
- Folium을 활용한 지도 시각화

## 📊 사용 기술
- Python, Pandas, Selenium, BeautifulSoup
- Seaborn, Matplotlib, Folium

## 사용 데이터 설명
- **gu**: 주소가 속한 구
- **name**: 주유소 명
- **address**: 주소
- **brand**: 리트리 주유주
- **gasoline / diesel**: 휘발유 / 경유 가격 (int)
- **self**: 설프 주유소인지 여부
- **carwash, charging station, maintenance, shop, open_24**: 선택 서비스 요리 (Y/N)
- **lat / lng**: 위치

## 🔗 블로그 링크
👉 [Velog 글 보러가기](https://velog.io/@yeongdecember/Data-Analysis-셀프-주유소와-일반-주유소-간-유가-분석-feat.-웹크롤링)