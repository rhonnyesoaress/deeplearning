# Deep Learning: lista de exercícios

Lista de exercícios da disciplina de **Deep Learning** (UFPB), resolvida em um único notebook: `ListaDeepLearning.ipynb`.

## Questões

| Questão | Problema | Abordagem |
|---|---|---|
| Aproximação de função | Regressão de uma função não linear | MLP (scikit-learn), 3 camadas ocultas, Adam com learning rate adaptativo |
| California Housing | Prever o valor de imóveis | MLP para regressão, com curvas de erro e de validação |
| Titanic | Prever sobrevivência | MLP para classificação, com tratamento de nulos sem vazamento de dados |
| 3 e 4: Fashion-MNIST | Classificar 10 tipos de roupa | MLP x CNN, com visualização dos filtros, mapas de ativação e erros do modelo |
| 5: Autoencoders | Reconstruir e limpar imagens | Autoencoder convolucional com diferentes tamanhos de espaço latente e denoising autoencoder |

**Destaque:** o denoising autoencoder reduziu o erro de reconstrução (MSE) de 0,0837 na imagem com ruído para 0,0196.

**Stack:** Python · TensorFlow/Keras · scikit-learn · Pandas · Matplotlib
