# Water Sort Puzzle

워터 소트 퍼즐 (물 색깔 정리 게임) — 아이폰/PC 브라우저에서 바로 플레이.

https://aheen222-png.github.io/water-sort-puzzle/

## 소리

- 붓는 소리(`assets/pour.mp3`, 0.40초)는 실제 물 따르는 녹음입니다.
  원본: Freesound 414077 "Water To Glass" by Black_River_Phonogram — CC0 1.0 (퍼블릭 도메인).
  https://freesound.org/people/Black_River_Phonogram/sounds/414077/
  원본 10초 녹음에서 4.30~4.70초 구간을 잘라 80Hz 하이패스, 15ms 페이드 인, 100ms 페이드 아웃,
  피크 -1dBFS로 정리했습니다. `assets/pour.wav`는 mp3 디코딩이 실패할 때 쓰는 같은 소리의 WAV입니다.
- 나머지 효과음(선택·완료·우승·실패)과 병마개 소리는 Web Audio 합성음입니다.
