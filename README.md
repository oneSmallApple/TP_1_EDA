### 사람인 사이트에서 첫 번째 데이터 분석 팀 프로젝트 결과입니다.
* * *
사람인 웹 링크 : <https://www.saramin.co.kr/zf_user/>
* * *
### 코드 전개 
1. Selenium을 이용해 사람인 웹 사이트에서 데이터를 크롤링합니다.
2. 크롤링한 공고의 html 페이지 내에 특정 단어가 들어가있는 공고를 검색합니다
3. 검색할 특정 단어들은 총 6개 입니다.

    * 머신러닝/딥러닝 (ML/DL)
    * 로봇 설계 및 제작
    * ROS
    * 임베디드
    * 자율주행
    * 제어 
   
4. 각기 다른 검색된 단어가 들어있는 독립된 데이터프레임을 만듭니다
5. 독립된 데이터 프레임에서 반복되는 빈도가 높은 단어들을 검색합니다
6. 요구 학위와 요구 경력이 전체 채용 공고에서 얼마나 반복되는지 검색합니다
7. 검색된 공고들이 어떤 비율을 가지고 있는지 검색합니다
8. 공고의 근무지가 어디에 있는지 지도를 통해 알아봅니다
