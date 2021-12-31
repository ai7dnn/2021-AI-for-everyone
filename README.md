# 2021-AI-for-everyone
4차 산업혁명 시대의 인공지능

## 자료 내려 받는 방법
1. 깃 설치한 경우, 다음 명령으로
`$ git clone https://github.com/ai7dnn/2021-AI-for-everyone.git`

2. 압축파일로 내려 받아 풀기
![image](https://user-images.githubusercontent.com/70050528/147514339-94382d39-5787-4d16-a202-309964f5a534.png)

## 참고 도서
딥러닝 머신러닝을 위한 파이썬 넘파이
https://github.com/zerosum99/numpy_itple

## 고등학교 AI 교과서 및 AI 기초 수학
- 고등학교 인공지능 기초 (길벗출판사)
https://textbook.gilbut.co.kr/book/index.html#p=1

- 고등학교 인공지능 수학 (씨마스)
https://www.cmass21.co.kr/ebook/H1/ingongjineung-suhag_ebook/ingongjineung-suhag_ebook.html

- 고등학교 인공지능과 피지컬 컴퓨팅 (금성출판사)
https://file.kumsung.co.kr/text/ebook/2015re/pre2020/h_computing/webview/index.html

- 일반인 위한 인공지능 수학
http://matrix.skku.ac.kr/math4ai-intro/

## 인공지능 체험 및 영상
- Neural Net for Handwritten Digit Recognition in JavaScript
http://myselph.de/neuralNet.html

- 딥러닝 이해(유튜브 영상)
https://www.youtube.com/watch?v=aircAruvnKk![image](https://user-images.githubusercontent.com/70050528/147711062-4f6152e4-b43a-4ae1-94ab-8d9d0a7d90a0.png)

## Colab 한글 처리 방법
#### 1. 다음 실행 후 2번은 다시 시작하여 실행

- APT(Advanced Packaging Tool)로 폰트 설치 실행  
`!apt -qq -y install fonts-nanum`  
`import matplotlib as mpl`  

- 폰트 매니저의 메서드로 다시 폰트를 구성
- 폰트 구성 후 '다시 실행'해야 재설정된 폰트가 반영  
`mpl.font_manager._rebuild()`  

#### 2. 위를 실행 후 다음은 다시 시작하여 실행

- 한글 폰트를 선명하도록 하는 파워명령어  
`%config InlineBackend.figure_format = 'retina'`  
`import matplotlib as mpl`  
`import matplotlib.pyplot as plt`  

- 한글 폰트 지원  
`plt.rc('font', family='NanumBarunGothic')`  
- 음수 부호 지원  
`mpl.rcParams['axes.unicode_minus'] = False`


