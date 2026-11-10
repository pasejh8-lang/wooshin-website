# 우신공업 홈페이지 및 모션 그래픽

회사소개서와 기존 홈페이지 자료를 바탕으로 제작한 반응형 정적 홈페이지입니다.

## 실행

이 폴더에서 실행하세요. 별도 패키지 설치는 필요하지 않습니다.

```powershell
python -m http.server 9127 --bind 0.0.0.0
```

- 홈페이지: http://localhost:9127/
- 하트 모션: http://localhost:9127/heartbeat.html
- 야구공과 비둘기: http://localhost:9127/baseball-dove.html
- 자동차와 배기음: http://localhost:9127/exhaust-drive.html

같은 네트워크에서는 컴퓨터의 IP 주소와 9127 포트로 접속합니다.

## 음원 및 이미지

- 클래식: 바흐 BWV 846, Kimiko Ishizaka 연주, CC0. MUSIC-LICENSE.txt 참고.
- 자동차 화면의 현재 음원: Harley-Davidson Sportster, demodave 녹음, CC0. HARLEY-AUDIO-LICENSE.txt 참고.
- BMW M4 음원은 이전 버전의 자료이며 현재 재생되지 않습니다. BMW-M4-AUDIO-LICENSE.txt 참고.
- 자동차 이미지는 AI 생성 실사풍 이미지입니다. 실제 BMW나 할리데이비슨 차량 및 우신공업 제품 성능을 나타내지 않습니다.
- 로고·회사 및 제품 사진: 우신공업 공식 홈페이지 및 제공 자료.
- 디자인 참고: Fabrica (MIT), FABRICA-LICENSE.txt 참고.

배경음악과 엔진음은 방문자가 버튼을 눌러 재생합니다. 문의 폼 서버는 없으며 전화와 지도 링크를 제공합니다.
