![image](https://github.com/chankimGH/opencv_11/assets/169237545/96f3b015-049f-48f0-9b2f-a311d5d8462d)# opencv_11

Number 1
구조 요소 행렬의 3가지 종류를 getStructuringElement() 함수에 대해 출력

![image](https://github.com/chankimGH/opencv_11/assets/169237545/f1168233-27bf-4dfe-aad8-4022961ac1fb)

Number 2
원본영상을 이진화 시킨 후 모폴로지연산을 이용하여
아래 결과처럼 글자 안과 밖의 모든 노이즈를 제거해보라.
![image](https://github.com/chankimGH/opencv_11/assets/169237545/ef44d3ab-3a2c-4588-aac2-362dd6ad68dd)


Number 3
원본영상을 이진화 시킨 후 아래 결과처럼 침식 또는
팽창연산을 이용하여 에지를 구하라.(캐니연산 사용하지 말것)

Number 4
원본영상(car.jpg)에서 번호판 영역을 4번째 영상처럼 하나의 흰색 블록으로 표시하고자 한다.
먼저 컬러영상을 그레이로 변환하고 그레이 영상에서 노이즈 제거를 위해 블러링(5x5 마스크) 적용하고 sobel 함수를 이용하여 수직방향의 에지(x축 방향 미분)만 검출한다(2번째 영상)
수직에지 영상을 이진화하고(3번째 영상) 마지막으로 닫기연산을 수행한다.
닫기연산시 구조요소행렬의 사이즈는 5행 32열로 가로방향으로 긴 사각형 형태의 마스크를 이용하여 숫자들을 하나의 객체로 합쳐준다
![image](https://github.com/chankimGH/opencv_11/assets/169237545/356b419d-a5b7-422e-920d-be532b40747b)
![image](https://github.com/chankimGH/opencv_11/assets/169237545/013b29a2-80d2-4220-9b9a-9649246d314a)
