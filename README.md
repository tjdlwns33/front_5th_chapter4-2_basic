# 바닐라 JS 프로젝트 성능 개선
- url: https://d3ljbbwtad11if.cloudfront.net

## 성능 개선 보고서
1. 개선 이유
- 이미지 크기가 큼
- Uncaught TypeError: Cannot read properties of null (reading 'insertAdjacentElement') 오류 발생
- 이미지 alt 누락으로 인한 접근성 이슈

2. 개선 방법
- 이미지 확장자 변경(-> .webp)
- script에 defer로 실행 시점 조절
- 이미지 태그에 alt 속성 추가

3. 개선 후 향상된 지표

![스크린샷 2025-06-05 오후 4 23 16](https://github.com/user-attachments/assets/3486dcf5-d68e-4b1a-952f-ca60d0067b09)
![스크린샷 2025-06-05 오후 4 23 43](https://github.com/user-attachments/assets/c3d8d129-590e-42ff-aed8-2679d64f71d7)
