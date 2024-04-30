# desafio_machinelearning

Passo a passo para criar e configurar um modelo de previsão com pontos de extremidade no Azure ML:

1.	Criar um modelo de Machine Learning:
•	Desenvolva e treine seu modelo de Machine Learning usando bibliotecas como scikit-learn, TensorFlow, PyTorch, etc.
•	Certifique-se de salvar seu modelo em um formato compatível, como pickle (.pkl) para modelos do scikit-learn ou SavedModel para modelos TensorFlow.

2.	Configurar um ambiente de Azure Machine Learning:
•	Crie uma conta no Azure e acesse o portal do Azure.
•	Crie um recurso de Azure Machine Learning e um workspace.

3.	Carregar o modelo no Azure ML:
•	Use a interface do Azure ML ou a SDK do Python para carregar seu modelo treinado no workspace do Azure ML.

4.	Implantar o modelo como um serviço web:
•	Selecione o modelo carregado e crie um serviço de inferência (Web Service) no Azure ML.
•	Escolha o tipo de serviço web (por exemplo, ACI - Azure Container Instances).

5.	Testar o serviço web localmente:
•	Use a SDK do Azure ML para enviar solicitações para o serviço web localmente e verificar se ele está respondendo corretamente.

6.	Obter os pontos de extremidade do serviço web:
•	Após o serviço web estar funcionando corretamente localmente, implante-o no Azure.
•	No portal do Azure, vá para o serviço web implantado e copie os pontos de extremidade (URLs) fornecidos.
