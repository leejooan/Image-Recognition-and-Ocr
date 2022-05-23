딥러닝을 활용해 의류 이미지 및 가격표를 입력으로 넣으면 옷의 종류와 색, 옷의 가격표를 읽고 가격을 알려주는 알고리즘입니다.

1) 홍콩 중문대학교 DeepFashion 데이터베이스를 기반으로 학습을 시켰으며 총 289,222장의 사진 중 일부만 사용했습니다.

![intro](https://user-images.githubusercontent.com/75022890/169817551-dad17b08-f8c6-4801-ad6f-9d6e186272b9.jpg)

2)사용한 multiclass classification 모델은 Vgg16을 사용했습니다.
![vgg16](https://user-images.githubusercontent.com/75022890/169818421-45e43692-bde0-486f-9dc1-9390382b6084.png)

3) 임의의 사진이 입력으로 들어오면 모델이 가격표라면 가격을 의상이라면 의상의 종류와 그 색을 판단해 알려줍니다.

![결과](https://user-images.githubusercontent.com/75022890/169817965-b89e615e-fe26-4365-ac01-d1329682b5c6.png)
