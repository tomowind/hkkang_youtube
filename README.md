# hkkang-youtube

[강환국님 유튜브](https://www.youtube.com/channel/UCSWPuzlD337Y6VBkyFPwT8g/videos) 중 파이썬으로 백테스트 할 수 있는 부분들을 구현해 보고 있습니다.

* [5. 라이브 백테스트! 소형주/저 PBR 투타전략 아직도 먹히나?](notebooks/5-live-backtest.ipynb): French Database 에서 받은 25 개국 데이터로 소형주+저PBR 이 먹히는지 1990~2018년 자료로 백테스트
* [7. 실전타임: 한국시장에서 버핏류 주식을 찾아보자](notebooks/7-buffett-korea.ipynb): 퀀트킹 자료로 저평가 \* 0.4 \+ 우량주 \* 0.4 \+ 변동성 \* 0.2 로 순위를 매겨봄
* [9. 모멘텀의 오묘한 세계(2) - 1990-2018년 라이브 백테스트](notebooks/9-momentum-backtest.ipynb): French Database 에서 받은 25개국 자료로 소형주+고모멘텀이 먹히는지 1990~2018년 자료로 백테스트
* [11. 저평가 우량주 모멘텀주 발굴 실습](notebooks/11-value-quality-momentum-korea.ipynb): 퀀트킹 자료로 저평가\*0.4 \+ 모멘텀\*0.4 \+ 우량주\*0.2 로 순위를 매겨봄
* [20. 나라면 이런 거 사겠다 (1) - NCAV](notebooks/20-ncav-korea.ipynb): 퀀트킹 자료로 NCAV 전략을 구현하여 (8가지: 중국안됨 + 청산가치 > 시가총액 + 낮은 부채비율 ...) 로 한국기업 순위를 매겨봄
* [26. 나라면 이런 거 사겠다(2) - 대형주 짬뽕전략](notebooks/26-big-mix-korea.ipynb): 퀀트킹 자료로 저평가\*0.4 \+ 모멘텀\*0.4 \+ 우량주\*0.2 \+ 대형주만으로 순위를 매겨봄
* [32. 나라면 이런 거 사겠다(3) - 행복전략](notebooks/32-dividend-happy-korea.ipynb): 퀀트킹 자료로 PCR 상위 30% \+ 배당성향 35~75% \+ 시가배당률 높은 기업들 순위를 매겨봄
* [40. 전세계에서 통하는 만능 전략 - 11월 매수, 4월 매도](notebooks/40-nov-to-apr.ipynb): stooq \+ fred 자료로 KOSPI \+ 한국금리를 받아서, 11월 매수 \+ 4월 매도가 한국에서 먹히는지 측정. AQR Data Library 에서 데이터를 받아 세계 각국에서 11월 매수 \+ 4월 매도가 먹히는지 측정
* [43. 상승장과 하락장을 구분하는 비법!! - 평균모멘텀스코어](notebooks/43-average-momentum.ipynb): stooq \+ fred 자료로 KOSPI \+ 한국금리를 받아서, 11월 매수 \+ 4월 매도 + 평균 모멘텀 사용한 효과 알아보기
