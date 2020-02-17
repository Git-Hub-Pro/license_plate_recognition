# license_plate_recognition
간단하게 요약하면 가우시안 필터링과 윤곽선 추출을 한 후, 표지판의 특징을 이용하여 후보 리스트들을 만든 후(브루트 포스 알고리즘 by 재귀함수을 활용)
그리고 한국어 trained data를 추가한 tesseract 라이브러리를 활용하여 이미지를 문자열로 변환을 한다.

# 주요 라이브러리
OPENCV,numpy, matplotlib, pytesseract

# 주의 사항
colab 환경은 running이 되는 동안 파일이 추가되고 설치가 됨으로 계속하여 실행을 해주어야 한다.
