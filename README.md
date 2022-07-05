# **KNU 인공 지능 특강(ABRLaboratory)**

---
## 1. 목적
- Deep Learning 의 이론 및 코딩 실습
  - Neural Network 인 Perceptron 이해 및 Backpropagation 이해
  - Computer Vision 의 한 축인 Convolution Neural Network (CNN) 이론 이해
  - Pytorch 에서의 Deep learning 학습 코딩 실습 및 이해
    - Training, Validation and Test
    - Transfer learning
    - Python Template for Deep learning
  - 대용량 데이터 학습을 위한 Multi-GPU 활용에 대한 이해 (Distributed Data Parallel in Pytorch)

---
## 2. 강의 계획
- 대상: 인공 지능에 관심이 있는 학생
- 준비물: 노트북
- 참여 학생은 Google Colab 을 사전에 설정 필요 
- 각 수업 후, 강의 내용을 기반한 한 과제 있으며, 참여 학생 중에서 2명씩 교대로 발표
  - 4주차 08.08은 하지 못한 과제를 하기 위해 휴강함
  - 5주차 이후에 각 주차별 과제의 정답을 올릴 예정
- 6주차 08.22은 배운 내용을 토대로 Term Project 제안 및 발표
- 08.22부터 08.30까지 Term Project 준비 기간
- 08.31에 각자 준비한 Term Project 발표 및 평가
### 강의 목차
|      Week      |     Date      |                                  Title                                  | Lecturer |
|:--------------:|:-------------:|:-----------------------------------------------------------------------:|:--------:|
|    **1 주차**    |     07.18     |                     [What is the Deep Learning?]()                      |   장준호    |
|    **1 주차**    |     07.20     |            [How to code the Deep Learning? – 01 Training]()             |   박형근    |
|    **1 주차**    |     07.22     |           [How to code the Deep Learning? – 02 Validation]()            |   박태원    |
|                |               |                                                                         |          |
|    **2 주차**    |     07.25     |             [How to code the Deep Learning? – 03 Dataset]()             |   배준현    |
|    **2 주차**    |     07.27     |              [How to Train a Deep Neural Network better]()              |   이정헌    |
|    **2 주차**    |     07.29     |      [What is the Convolution Neural Network (CNN) – 01 Operate]()      |   배준현    |
|                |               |                                                                         |          |
|    **3 주차**    |     08.01     |       [What is the Convolution Neural Network (CNN) – 02 Model]()       |   이준원    |
|    **3 주차**    |     08.03     | [What is the Convolution Neural Network (CNN) – 03 Pre-trained Model]() |   배준현    |
|    **3 주차**    |     08.05     |            [Transfer Learning by using Pre-trained Model]()             |   권도영    |
|                |               |                                                                         |          |
|    **4 주차**    |     08.08     |                         **Do overdue homework**                         |    -     |
|    **4 주차**    |     08.10     |                  [Object Detection based on the CNN]()                  |   장준호    |
|    **4 주차**    |     08.12     |                    [Segmentation based on the CNN]()                    |   권도영    |
|                |               |                                                                         |          |
|    **5 주차**    |     08.17     |             [Distributed Data Parallel (DDP) in Pytorch]()              |   권도영    |
|    **5 주차**    |     08.19     |             [Distributed Data Parallel (DDP) in Pytorch]()              |   권도영    |
|                |               |                                                                         |          |
|    **6 주차**    |     08.22     |                      **Proposal the Term Project**                      |    -     |
|  **6 & 7 주차**  | 08.22 ~ 08.30 |                      **Term Project Preparation**                       |    -     |
|    **7 주차**    |     08.31     |                      **Present the Term Project**                       |    -     |


## 3. 기타
- 본 Repository 는 2022년 여름 하계 인공 지능 특강에서 활용한 실습 코드 저장소
- 강의자: 각자 맡은 수업에 필요한 실습 코드, 주석 및 README 파일 작성을 요청함
- 실습 코드의 Python 및 패키지 버전
  - Python >= 3.8
  - Pytorch >= 1.11