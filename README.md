### 📦 Sistema de Gestão de Stock em Python

- Este projeto consiste num programa simples de gestão de stock desenvolvido em Python, que funciona através de um menu interativo no terminal. O sistema permite ao utilizador controlar materiais e respetivas quantidades de forma prática.

### 🔧 Funcionalidades

- O programa oferece as seguintes operações:

- Adicionar material: Permite inserir um novo material no stock, definindo uma quantidade inicial. Caso o material já exista, o sistema avisa o utilizador.

- Consultar stock: Possibilita verificar a quantidade disponível de um material específico.

- Atualizar stock: Permite adicionar ou remover unidades de um material existente. O sistema valida se existe quantidade suficiente antes de permitir remoções.

- Exibir stock geral: Mostra todos os materiais registados juntamente com as suas quantidades atuais, organizados em formato de tabela.

- Sair do programa: Encerra a execução do sistema.

### 🧠 Funcionamento

- O stock é armazenado numa estrutura de dados do tipo dicionário (dict), onde:

- A chave corresponde ao nome do material

- O valor corresponde à quantidade disponível

- O programa corre num ciclo contínuo (while True), apresentando o menu ao utilizador até que este escolha sair.

### ▶️ Como executar

- Certifica-te de que tens o Python instalado.

- Executa o ficheiro no terminal:

- python nome_do_ficheiro.py

- Segue as instruções apresentadas no menu.
