# Visualizing CNN Layer Outputs
2021 hufs deep learning course
## CNN을 이용한 음식 이미지 인식
> 참고 사이트 : https://www.kaggle.com/kutaykutlu/99-9-acc-resnet50-inceptionv3-vgg16
## 파일 설명
* data : 학습시킬 때 사용하는 이미지
* test_data : 테스트 할 때 사용하는 이미지
* cnn_visualization.ipynb : 학습시키는 코드 및 수행결과
## 1. Model
![model](https://user-images.githubusercontent.com/52366841/125264930-4da47380-e33f-11eb-81ee-bb2cd37a310d.PNG)
## 2. Predict result
![predict1](https://user-images.githubusercontent.com/52366841/125371746-5f782c00-e3bc-11eb-9752-c0944acb5e8a.PNG)
![predict2](https://user-images.githubusercontent.com/52366841/125371943-dd3c3780-e3bc-11eb-9755-7a6ec1acf0d5.PNG)

## 3. Visualizing을 위한 모델 정의 (activation_model)
![code](https://user-images.githubusercontent.com/52366841/125371774-7a4aa080-e3bc-11eb-965c-1fe8cf14701a.PNG)

## 4. 결과

## 4-1. Visualizing activations

### conv2d_1
![conv_2d_1](https://user-images.githubusercontent.com/52366841/125371796-8898bc80-e3bc-11eb-8644-9c70a193aae2.PNG)

### conv2d_2
![conv2d_2](https://user-images.githubusercontent.com/52366841/125371812-90586100-e3bc-11eb-849c-7ccb115412e7.PNG)

### maxpool_1
![max_pool1](https://user-images.githubusercontent.com/52366841/125371831-9bab8c80-e3bc-11eb-867c-ad0111d98e8e.PNG)

### maxpool_2
![max_pool2](https://user-images.githubusercontent.com/52366841/125371854-a9f9a880-e3bc-11eb-96fa-5fdc5d641535.PNG)

<br>

## 4-2. Visualizing filters
![filter1](https://user-images.githubusercontent.com/52366841/125371885-bbdb4b80-e3bc-11eb-9b65-0e6e6aadd0fe.PNG)

![filter2](https://user-images.githubusercontent.com/52366841/125371909-c5fd4a00-e3bc-11eb-9226-033a5f24cc55.PNG)

![filter3](https://user-images.githubusercontent.com/52366841/125371922-cc8bc180-e3bc-11eb-8fd3-f68c2e4e7b0f.PNG)

<br>


