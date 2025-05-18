# 🧠 Safe-AI-FMnist

EfficientNet 구조를 기반으로 FashionMNIST 데이터셋을 분류하는 PyTorch 기반 사용자 정의 CNN 모델입니다.  
경량화된 모델임에도 불구하고 높은 정확도를 유지하며, 성능 향상을 위한 다양한 기법들을 적용해 보았습니다.

---
## Authors

- **박기정**
- **신성섭** 
- **오하연** 
---

## 📌 프로젝트 개요

- **데이터셋**: [FashionMNIST](https://github.com/zalandoresearch/fashion-mnist)
- **모델 구조**: EfficientNet 스타일의 `MBConv` 블록을 사용한 사용자 정의 CNN
- **학습 방식**: AdamW 옵티마이저 + CosineAnnealing 학습률 스케줄러 적용
- **목표**: 경량 CNN으로 의류 이미지 분류 정확도 향상 및 확장 가능성 탐색

---
## FMist Dataset 특징 요약
The Fashion MNIST dataset is a collection of 28x28 grayscale images, categorized into 10 classes:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot
