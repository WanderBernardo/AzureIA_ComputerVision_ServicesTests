# Azure Inteligência Artificial(IA) - Visão Computacional: Testes de recursos/serviçoes
Objetivo é apresentar recursos/serviço de Inteligência Artificial utilizando Foto, Foto com Texto, Descrevendo o que tem na foto etc.

### Ferramentas utilizadas:
- Portal Studio Vision : https://portal.vision.cognitive.azure.com/

### Pontos Importantes:
- Caso esteja realizando apenas um prática de estudo, no final excluir tudo que foi construído nesse laboratório. Desta forma, minimiza o risco de ser cobrado algum valor. Lembre-se você está em um ambiente real de produção.
- Documentação:
    + https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html
    + https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html
    + https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html

### Orientação Geral
- Todos os testes vai precisar do seu aceito que estará utilizando o resource criado. Isso quer dizer que vai ser cobrado.
![image](https://github.com/user-attachments/assets/3d77e0dd-db28-4a24-a2ec-688d752e70ee)

- Os testes são bem intuitivo e a propria ferramenta tras alguns exemplos e você pode selecionar alguma imagem propria. O resultado fica logo em baixo:
![image](https://github.com/user-attachments/assets/101fb7ce-7f99-463b-954c-79c4f897dd09)

- Os testes realizados neste material foram com imagem proprias. Não utilizei os exemplos da ferramenta.

### Teste 01 - Identificar pessoas na foto:
1 - Selecionar ``` Face  ```, depois ``` Detect faces in an image  ```
![image](https://github.com/user-attachments/assets/96ca218a-65af-4c9d-8b3d-6b3ee62b534e)

![image](https://github.com/user-attachments/assets/010e5ef0-7bd3-4cf3-8404-5f7759863f30)


### Teste 02 - Identificar texto na foto:
![image](https://github.com/user-attachments/assets/30df6005-95c3-4cba-8be6-d59778a506e6)

![image](https://github.com/user-attachments/assets/3261747b-c442-43ac-b5bc-3b0d7576c0f4)


### Teste 03 - Descrevendo a imagem/foto:
![image](https://github.com/user-attachments/assets/1ce9c879-e482-40f6-bf07-2b59738bdfd0)

![image](https://github.com/user-attachments/assets/47e418f5-a1d4-43a9-b451-9d20cf8d4543)


### Ferramenta suporta:
- Integração com aplicações
   * https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/quickstarts-sdk/identity-client-library?tabs=windows%2Cvisual-studio&pivots=programming-language-csharp
   * https://github.com/Azure-Samples/azure-ai-vision/tree/main/face
- Letura de texto na imagem/foto:
   * Diversos idiomas
   * Escrito a mão
   * Formulários e já transformar em banco de dados
- Gera arquivo JSON com o resultado


