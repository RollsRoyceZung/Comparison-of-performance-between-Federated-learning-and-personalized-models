# Comparison-of-performance-between-Federated-learning-and-personalized-models

## Abstract
With the development of artificial intelligence technology, there are many references to the importance of data security
as a basis for learning. In this paper, we designed the MNIST classification model using two conventional centralized
learning algorithms and federated learning algorithms (FedAvg, CFL). It shows the research direction of next-generation
machine learning for performance comparison and data privacy protection by classification time and accuracy.
Keywords: AI, Machine Learning, Federated Learning, FedAvg, Personalization Federated Learning, Clustered Federated
Learning, Clustering

### How to Run
!git clone https://github.com/guobbin/PFL-MoE.git </br> 
!pip install pillow==6.2.1 </br>
!pip install thop </br>
%cd PFL-MoE </br>
!pip install -r requirements.txt </br>
Run - Clestering Federated Learning Machine Learning </br>
!python main_local.py --dataset=cifar --model=lenet --epochs=100 --gpu=0 --num_users=10 --alpha 0.5 --num_channels=3 </br>
!python main_fed.py --dataset=cifar --model=lenet --epochs 30 --gpu 0 --lr 0.01 --num_users 10 --frac 0.1 --alpha 0.5
