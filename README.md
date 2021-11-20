# (`Pipeline`) Automatize as etapas de Machine Learning

**Mas afinal, o que é pipeline de ML?**

Um pipeline de Machine Learning é um fluxo de trabalho executável de forma independente de uma tarefa completa de aprendizado de máquina. As subtarefas são encapsuladas como uma série de etapas no pipeline. 

Os pipelines devem se concentrar em tarefas de aprendizado de máquina, como:

- Preparação de dados, incluindo importação, validação e limpeza, mudanças irreversíveis e transformação, normalização e preparo dos dados;
- Configuração de treinamento, incluindo argumentos de parametrização, filePaths e configurações de log/relatório;
- Treinamento e validação de forma eficiente e repetida. 
    - A eficiência pode vir da especificação de subconjuntos de dados específicos, diferentes recursos de computação de hardware, processamento distribuído e monitoramento de progresso.
- Implantação, incluindo controle de versão, dimensionamento, provisionamento e controle de acesso.

As etapas independentes permitem que vários cientistas de dados funcionem no mesmo pipeline ao mesmo tempo, sem sobrecarregar os recursos de computação. As etapas separadas também facilitam o uso de diferentes tipos/tamanhos de computação para cada etapa.

Depois que o pipeline é criado, muitas vezes, há mais ajustes finos no loop de treinamento do pipeline. Quando você executa novamente um pipeline, a execução pula para as etapas que precisam executar novamente, como um script de treinamento atualizado. As etapas que não precisam ser executadas novamente são ignoradas.

Então vamos ver na prática quais são as etapas de um projeto de machine learning e como podemos otimizá-las.

Segue o link do [notebook](https://colab.research.google.com/drive/1jexdompYoeQl0qVYj5RDnLujQRSmsMna#scrollTo=ZL-KVMWTu0tC).
