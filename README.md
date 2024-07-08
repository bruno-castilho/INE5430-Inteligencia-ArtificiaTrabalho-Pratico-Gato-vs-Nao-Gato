# INE5430-Inteligencia-ArtificiaTrabalho-Pratico-Gato-vs-Nao-Gato
## Pre-Requesito
[python>=3.10.12](https://www.python.org/downloads/)

## Instalação
Inicialize as dependecias:
```bash
  pip install numpy h5py scikit-learn seaborn matplotlib tensorflow
```


## Execução

### Regressão Logística
- Teste1
  - Utilizando 10 imagens do conjunto de testes.
  `python3 RegrecaoLogistica/Teste1.py`
- Teste2
  - Utilizando 80 imagens do conjunto de testes.
  `python3 RegrecaoLogistica/Teste2.py`
- Teste3
  - Utilizando 209 imagens do conjunto de testes.
  `python3 RegrecaoLogistica/Teste3.py`

### Redede camada rasa

- Teste1
  - Camadadeentrada:64x64x3 vetores.
  - Camadaintermediária:100 neurônios com função de ativação sigmoid.
  - Camadadesaída:1 neurônio com função de ativação sigmoid.
  `python3 RedeDeCamadaRasa/Teste1.py`
- Teste2
  - Camadadeentrada:64x64x3 vetores.
  - Camadaintermediária:200 neurônios com função de ativação sigmoid.
  - Camadadesaída:1 neurônio com função de ativação sigmoid.
  `python3 RedeDeCamadaRasa/Teste2.py`
- Teste3
  - Camadadeentrada:64x64x3 vetores.
  - Camadaintermediária:100 neurônios com função de ativação ReLU.
  - Camadadesaída:1 neurônio com função de ativação sigmoid.
  `python3 RedeDeCamadaRasa/Teste3.py`
- Teste4
  - Camadadeentrada:64x64x3 vetores.
  - Camadaintermediária:200 neurônios com função de ativação ReLU.
  - Camadadesaída:1 neurônio com função de ativação sigmoid.
  `python3 RedeDeCamadaRasa/Teste4.py`
