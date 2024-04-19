# 💫 Sobre o Laboratório:
O AISE Lab (Artificial Intelligence and Software Engineering Laboratory) é liderado pela Professora Juliana Alves Pereira e tem como missão avançar a pesquisa e o desenvolvimento nas áreas de inteligência artificial e engenharia de software. Nosso laboratório é focado em criar e compartilhar conhecimentos científicos e tecnológicos que impulsionam a inovação em diversos campos aplicados da IA.<br>Este repositório serve como um espaço central para armazenar e gerenciar os códigos desenvolvidos nas pesquisas realizadas no AISE Lab. Aqui, promovemos a colaboração, a revisão de código, e a disseminação de nossos trabalhos acadêmicos e projetos experimentais.


# 💻 Tecnologias:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

# Preparando o ambiente de desenvolvimento
Obs: nosso ambiente é feito no vscode, então o baixe antes de continuar lendo. A IDE da jetbrains pycharm também pode ser usado, porem seus plugins não são mencionados nesse arquivo, tente encontrar por contra plugins análogos.

## Ambiente para propósitos gerais
- Use o plugin autoDocstring

> É de suma importância que todo código feito esteja completa ou parcialmente documentado. O autodocstring irá deixar toda documentação padronizada no padrão google, o melhor atualmente.
![alt text](image.png)

- Baixe o git
> Git é uma ferramenta de versionamento de código que ira ser utilizada durante toda extenção do projeto, você pode estudar um pouco mais sobre essa ferramenta nesse link: https://www.freecodecamp.org/portuguese/news/tutorial-de-git-e-github-controle-de-versao-para-iniciantes/


- Pluin github copilot
> Copilot é uma ótima ferramenta para auto complete, além disso o mesmo também serve como uma integração do chat gpt no vscode. Siga os passos de (https://dev.to/twizelissa/how-to-enable-github-copilot-for-free-as-student-4kal)
![alt text](image-1.png)

- Revise conceitos de Orientação a objetos
(https://www.devmedia.com.br/principais-conceitos-da-programacao-orientada-a-objetos/32285)
> Orientação a objetos é um ótimo método para organizar e reutilizar código 

- Revise design patterns e conceitos do SOLID
(https://refactoring.guru/pt-br)
> Design patterns são bem interessantes para ajudar na manutenibilidade e adaptação do código a novas features e adaptação de nos módulos já existentes.


## Ambiente para trabalhar com DL e ML

- Utilizar o plugin do jupyter
> É muito importante utilizar uma IDE integrada com o jupyter, isso se da porque o jupyter é uma ferramenta excelente, mas por si só não possui high light, o que dificulta e atrasa a produção de código.
![alt text](image-2.png) 

- Criação de virtual environments

	   #criação de venv com o nome desejado, geralmente colocando como nome a biblioteca principal, ou especificamente as que causam problemas
	   python -m venv <nome_venv>
	   
	   #ativação da venv(Windows)
	   <nome_venv>//Scripts//Activate.ps1
	   
	   #ativação venv(Linux)
	   source <nome_venv>/bin/activate
	   
> Algumas bibliotecas possuem muitas versões de de bibliotecas específicas, então antes de utilizar o pip install global crie venvs destinadas a um conjunto de bibliotecas.

- Instalação do tensorflow com gpu

        python3 -m pip install tensorflow[and-cuda]

        # Verify the installation:
        
        python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
		
> O tensorflow é uma biblioteca que algumas vezes cria diversos problemas de ambiente, ela deve ser instalada em uma venv. Se seu computador não possuir gpu não faça essa instalação.

