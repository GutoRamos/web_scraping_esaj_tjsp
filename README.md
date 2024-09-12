# web_scraping_esaj_tjsp
Este repositório contém um script em Python para automatizar o acesso e a navegação no portal do Tribunal de Justiça de São Paulo (TJSP). Utiliza a biblioteca Selenium para fazer login, navegar pelos menus e realizar consultas processuais. Ideal para automação de tarefas repetitivas no portal do TJSP.
Funcionalidades
Instalação Automática do ChromeDriver: Utiliza a biblioteca chromedriver_autoinstaller para garantir que a versão correta do ChromeDriver esteja instalada e configurada.
Login Automatizado: Realiza o login no portal do TJSP com as credenciais fornecidas.
Navegação no Menu: Automatiza a navegação pelo menu do portal para acessar a seção de consultas processuais.
Realização de Consultas: Clica no botão "Consultar" para iniciar uma nova consulta processual.
Requisitos
Python 3.x: O script é compatível com Python 3.x.

Bibliotecas: As seguintes bibliotecas Python devem ser instaladas:

selenium
chromedriver_autoinstaller
Instale as bibliotecas necessárias usando pip
pip install selenium chromedriver_autoinstaller o script para iniciar a automação do processo de login e navegação no portal TJSP:

bash
Copiar código
python web_scraping_esaj_tjsp.py
Estrutura do Código
Instalação e Configuração: Configuração do ambiente do Selenium e do ChromeDriver.
Login: Automatiza o login no portal usando as credenciais fornecidas.
Navegação: Clica no menu e acessa a página de consultas processuais.
Consulta Processual: Clica no botão "Consultar" para realizar uma nova consulta.
Contribuições
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.
