# Controle_venda_VCR
 APP gerenciar vendas
<!---Esses são exemplos. Veja https://shields.io para outras pessoas ou para personalizar este conjunto de escudos. Você pode querer incluir dependências, status do projeto e informações de licença aqui--->
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
<img src="img.png" alt="exemplo imagem">
> Uma aplicação web de controle de venda desenvolvida durante o curso de Python no Senac de America em paralelo as aulas para melhorar e aumentar meu conhecimento. O APP vai receber e armazenar as vendas. testando

### Lista de tarefas
Segue a lista de tarefas a serem desenvolvidas no projeto:
- [X] Pré-requisitos
    - [X] Instalar o Python
    - [X] Instalar Visual Studio Code
- [X] Pré-requisitos
    - [X] Instalar o Python
    - [X] Instalar Visual Studio Code
- [X] Criar e ativar o ambiente virtual
```
    python -m venv .\venv\
    venv\Scripts\activate 
```
- [X] Inatalar Django
```
    python -m pip install django==3.2
```
- [X] Criar o projeto Controle_Venda_vcr
```
    django-admin.py startproject Controle_Venda_VCR_Project
```
- [X] Subir o servidor e testar o projeto
```
    abrir pasta projeto
        cd Controle_Venda_VCR_Project
    executtar projeto no servidor
        python manager.py runserver

```
- [X] Alterar o idioma do projeto `pt-br`
    - Abrir o arquivo settings.py e na linha 106 LANGUAGE_CODE = `en-us` alterar para `pt-br`
- [X] Alterear timexone do projeto para `America/Sao_Paulo`
    - Abrir o arquivo settings.py e na linha 108 TIME_ZONE = 'America/Sao_Paulo'
- [] Criar o APP Controle_de_Vendas
- [] Registrar o APP
- [] Configurar rota Inicial (index)
- [] Criar a view para a rota inicial 
- [] Cria o  arquivo index.html
## 📝 Licença
Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.
[⬆ Voltar ao topo](#nome-do-projeto)<br>