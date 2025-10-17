DENSENET 121 - 2:
10 Épocas
Total de imagens no diretório Healthy: 1272
Total de imagens no diretório Sick: 776
Total de imagens: 2048

Tamanho do conjunto de treino: 1430
Tamanho do conjunto de validação: 309
Tamanho do conjunto de teste: 309

CUDA disponível: True
Dispositivo atual: 0
Nome da GPU: NVIDIA GeForce RTX 2060
PyTorch está rodando na GPU? True
cuda:0
Epoch 1/10 | Train Loss: 1.0767 | Val Loss: 2.7699 | Val Acc: 47.57% | Train Samples: 1430 | Val Samples: 309

Epoch 2/10 | Train Loss: 0.2675 | Val Loss: 3.4724 | Val Acc: 64.08% | Train Samples: 1430 | Val Samples: 309

Epoch 3/10 | Train Loss: 0.2388 | Val Loss: 0.4308 | Val Acc: 78.32% | Train Samples: 1430 | Val Samples: 309

Epoch 4/10 | Train Loss: 0.1558 | Val Loss: 0.6091 | Val Acc: 79.94% | Train Samples: 1430 | Val Samples: 309

Epoch 5/10 | Train Loss: 0.1134 | Val Loss: 0.9974 | Val Acc: 71.52% | Train Samples: 1430 | Val Samples: 309

Epoch 6/10 | Train Loss: 0.1799 | Val Loss: 0.6103 | Val Acc: 78.32% | Train Samples: 1430 | Val Samples: 309

Epoch 7/10 | Train Loss: 0.0735 | Val Loss: 0.5582 | Val Acc: 82.52% | Train Samples: 1430 | Val Samples: 309

Epoch 8/10 | Train Loss: 0.0668 | Val Loss: 0.6046 | Val Acc: 83.82% | Train Samples: 1430 | Val Samples: 309

Epoch 9/10 | Train Loss: 0.0886 | Val Loss: 0.6055 | Val Acc: 79.61% | Train Samples: 1430 | Val Samples: 309

Epoch 10/10 | Train Loss: 0.0822 | Val Loss: 0.9212 | Val Acc: 81.55% | Train Samples: 1430 | Val Samples: 309

Relatório de Classificação:
               precision    recall  f1-score   support

     Healthy       0.74      0.94      0.82       193
        Sick       0.81      0.44      0.57       116

    accuracy                           0.75       309
   macro avg       0.77      0.69      0.70       309
weighted avg       0.76      0.75      0.73       309

Acurácia no Teste: 75.08%