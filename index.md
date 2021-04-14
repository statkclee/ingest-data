---
layout: page
title: 다양한 데이터 가져오기
---

> ### AI is a Superpower {.callout}
>
> "AI is a superpower!!!", 인공지능을 체득하면 슈퍼파워를 손에 쥘 것이다. [Andrew Ng](https://twitter.com/andrewyng/status/728986380638916609)
>
> 금수저, 은수저 슈퍼파워를 받은 사람과 기계학습을 통달한 흑수저들간의 무한경쟁이 드뎌 시작되었다. 물론, 
> 금수저를 입에 물고 기계학습을 통달한 사람이 가장 유리한 출발을 시작한 것도 사실이다.

![Tim Berners-Lee [5-star deployment scheme for Open Data](https://www.w3.org/DesignIssues/LinkedData.html)](fig/5-star-steps.png)

## 학습목차 

- [데이터 가져오기: `pins`](ingest-data.html)
    - [`fs` 로컬파일](ingest-data-fs.html)
    - **광학문자인식(OCR, Optical Character Recognition)**
        - [검정배경 흰색글자 인식](ocr-white-character.html)
        - [문자 분리(character segmentation)](ocr-white-segmentation.html)
        - [기계판독 가능한 테이블(표)](ocr-table.html)
        - [애비(Abbyy): Access Abbyy Cloud OCR from R](ocr-abbyy.html)
        - **[문자인식(OCR) - `tesseract`](ingest-ocr.html)**
        - [PPT 장표 - OCR `tesseract`](ingest-ocr-ppt.html)
- **[PDF 문서](ds-extract-pdf.html)**
    - [이미지 PDF 파일 데이터 추출](ds-extract-text-from-pdf.html)
    - [PDF 감옥에서 데이터를 탈출시키다.](ds-extract-text-from-pdf-survey.html)
    - [기계판독 가능한 PDF 문서에서 표추출](pdf-extract-table.html)
    - [~~기계판독~~ **불**가능한 PDF 문서에서 표추출](pdf-image-extract-table.html)
    - [문서(`tika`)](ingest-tika.html)
        - [CV 제작](create-cv.html)
    - [PDF &rarr; 워드 - 리브레오피스(LibreOffice)](libreOffice-pdf-word.html)
- **웹(Web)**
    + **[웹 데이터](https://statkclee.github.io/data-science/ds-webdata.html)**
        - [웹 스크래핑(Web Scraping)](https://statkclee.github.io/data-science/data-scraping.html)
        - [R 팬텀JS (phantomJS) - 방송3사 시청률 경쟁 그리고 JTBC 손석희 앵커](https://statkclee.github.io/data-science/ds-phantomJS.html)
        - [아마존 알렉사 웹정보(웹API) - KBO 프로야구 웹사이트](https://statkclee.github.io/data-science/data-webapi-aws-alexa.html)
        - [아마존 알렉사 웹정보(웹API) - 인터넷 쇼핑(쿠팡, 위메프, 티몬)](https://statkclee.github.io/data-science/data-webapi-social-shopping.html)
        - [아마존 알렉사 웹정보(웹API) - 대한민국 주요 정당](https://statkclee.github.io/data-science/data-webapi-party.html)
        - [아마존 웹 서비스(AWS) - EC2 사양과 가격](https://statkclee.github.io/data-science/ds-aws-webservice.html)
    + [네이버 인물정보](naver-people-info.html)
    + **웹 크롤링**
        - [정적 웹페이지(표) - 대학순위](static-webpage-table.html)
        - [정적 웹페이지(표) - 지방선거(2018)](static-webpage-table-2018.html)
        - [동적 웹페이지 - `RSelelinum`](dynamic-webpage-selenium.html)
        - [동적 웹페이지 - iMac](dynamic-webpage-imac.html)
        - [크롤링 자동화 - Azure/AWS](crawl-automation.html)
    + [텍스트 RSS 피드](ingest-rss.html)
    + 연관검색어
        + [네이버](http://statkclee.github.io/politics/naver-related-search.html)
        + [다음](daum-related-search.html)
        + [구글 제안(Google Suggest)](google-suggest.html)
    - **공공데이터**
        - [선관위 지방선거(2018) - POST, 로컬, 도커](election-post-docker.html)
        - [속초시 CCTV](cctv-sokcho.html)
    - [구글 스프레드쉬트(Google Spreadsheets)](ingest-google-sheets.html)    
- [데이터베이스 (SQL)](https://statkclee.github.io/data-science/) &larr; **관계형 데이터베이스(RDBMS)**
- **API(Application Programming Interface)**
    - [API](ingest-api.html)
- [사물인터넷(IoT) - `mqtt`](ingest-mqtt.html)
    - [IoT 센서 - JSON](ingest-iot-json.html)
- 소프트웨어 카펜트리
    + [파이썬 - 웹에 있는 데이터 작업](http://statkclee.github.io/web-data-python/)
        * [데이터 입수](http://statkclee.github.io/web-data-python/01-getdata.html)
        * [CSV 데이터 처리](http://statkclee.github.io/web-data-python/02-csv.html)
        * [오류(Error) 처리와 일반화](http://statkclee.github.io/web-data-python/03-generalize.html)
        * [시각화](http://statkclee.github.io/web-data-python/04-visualize.html)
        * [데이터 게시](http://statkclee.github.io/web-data-python/05-makedata.html)
        * [데이터를 찾을 수 있게 만들기](http://statkclee.github.io/web-data-python/06-findable.html)
- **소셜(SNS)**
    + [~~페이스북(Facebook)~~](ingest-facebook.html)
    + [트위터(Twitter)](ingest-twitter.html)
        - [트위터 데이터 과학](ingest-twitter-data-science.html)
    + [인스타그램(Instagram)](ingest-instagram.html): 파이썬 크롤러, 셀레이움
    + [~~유튜브(Youtube)~~](ingest-youtube.html)
    + [~~네이버, 다음 뉴스~~](ingest-news.html)
- [GitHub 저장소 - 데이터 사이언스](ingest-github-repo.html)
    + [`GitHub` 데이터 분석: 프로젝트 평가](ingest-data-github-data-analysis.html)
- [직사각형이 아닌 데이터 - `JSON`, `XML`](non-rectangular-to-dataframe.html)
    + [`JSON`, `XML` &rarr; 데이터프레임](dataframe-to-xml-json.html)
- [**논문**](ingest-bibtex.html)
    + [`dimensions.ai` API](ingest-dimensions-ai.html)

### [xwMOOC 오픈 교재](https://statkclee.github.io/xwMOOC/)

