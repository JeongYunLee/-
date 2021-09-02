- 산림복지시설_draft.xlsx
    : 산림복지 서비스이용권 사용가능 시설안내(https://www.forestcard.or.kr/intro/useUtilize.do?menuId=1110100)를 기준으로 7개의 카테고리를 시트별로 정리
      누락된 주소 채우기, 중복제거 등의 전처리는 xlsx 파일에서 수작업으로 진행. 
      해당 데이터의 출처 및 수집방법은 'INFO' 시트 참고 
- 산림복지시설_final.xlsx
    : 산림복지시설_draft의 전처리 후 파일.
      추가로 누락된 주소 채우기, 중복제거 등의 전처리는 xlsx 파일에서 수작업으로 진행.
- df_latlng.xlsx
    : google API를 통해 해당 시설의 경도, 위도를 추출. 
      이후 folium 지도 시각화의 마크 표시할 때 사용. 
- 시도_행정구역.json
    : folium의 chropleth  지도 시각화 그릴 때 사용. 
      출처: https://neurowhai.tistory.com/350