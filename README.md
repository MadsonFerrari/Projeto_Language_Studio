# Madson Ferrari

Olá pessoal, eu sou Madson Ferrari, Engenheiro eletricista, pós graduado em Mecatrônica pela UFRJ e entusiasta pela área de informática, programação e Innovation

## Você pode me encontrar aqui:

[![Perfil DIO](https://img.shields.io/badge/-Meu%20Perfil%20na%20DIO-0077B5?style=for-the-badge&logo=gitbook&logoColor=white)](https://www.dio.me/users/madson_ferrari)

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=30A3DC)](https://www.linkedin.com/in/MadsonFerrari/)

[![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@MadsonFerrari)

# Análise de sentimentos com Language Studio


- A primeira etapa foi assitir ao módulo de Análise de texto do curso da DIO dentro do bootcamp AI-900


- Acessar o [Portal Azure](https://portal.azure.com) usando as credenciais
Selecionei **+Create a resource**
- Procurar e selecionar **Azure AI Services** ,clicar em CREATE e colocar os seguintes ajustes:
    - **Subscription:** *Sua conta do Azure*
    - **Resource group:** *Nome do Recurse Group*
    - **Region:** *East US 2*
    - **Name:** *Nome desejado*

    - **Price Tear:** *Standard S0*
    - **Box de termos:** *Selecionada*

- Selecione **Review + create** e então selecione **Create**.
Espere a criação do espaço de trabalho (levou alguns minutos) 

Depois de criado acessar o [portal do Language Cognitive] (https://language.cognitive.azure.com/home)

## Reconhecimento de Texto com Language Studio

Após criar o recurso e fazer o Deploy, basta escolher no Language Studio.

**Esta parte pode demorar alguns minutos pois o recurso demora para aparecer na lista**

Para teste de Sentimento eu preparei um texto com várias sentenças sobre o opinião de um cliente em um restaurante.

![Imagem](https://github.com/MadsonFerrari/Projeto_Reconhecimento_Facial/blob/main/inputs/Exemplo%20de%20texto.jpeg)

Basta carregar o texto na opção **Browse for a file** e pronto. O Vision Studio retorna o texto com alta detecção. Neste caso com 98% de acerto.

Note que apenas a segunda abreviação de "para" (p/) não foi reconhecida devido à barra ter ficado muito pequena sendo confundida com a letra "i" minúscula

## Reconhecimento de Faces com Azure Vision Studio

- Neste caso, como já estava criado o recurso, basta voltar ao vision Studio, na coluna Featured

- Selecionar o recurso **detect face in an image**

- Marcar a caixa que diz que este recurso vai usar **visionStudioTest** do Azure

- Usei uma imagem minha para testar a detecção de face
![Imagem de teste](https://github.com/MadsonFerrari/Projeto_Reconhecimento_Facial/blob/main/inputs/Visita%20Senai.png)

- Depois disto o software faz tudo sozinho e com perfeição

- Veja o resultado na imagem abaixo:

![Face reconhecida na Imagem](https://github.com/MadsonFerrari/Projeto_Reconhecimento_Facial/blob/main/Screens/Detected%20Face.PNG)


## Considerações finais

### As ferramentas do Azure demonstraram que estão preparadas para o uso em diversos projetos e que conseguem um acerto muito alto tanto na detecção de faces como de texto. Isto mostra que os desenvolvedores possuem recursos inimagináveis para desenvolver aplicações de altíssimo nível e precisão.


