# MOCK TOTVS BUILDER CLIENT
Projeto utilizado para executa o **mock-totvs-builder**

# Documentação do Mock Totvs Builder
A documentação está disponível em: <ENDEREÇO-DO-GITRUB>

# Preparando as Entidades
1. Criar uma arquivo de configuração para cada entidade que será utilizada;
2. Na documentação do **mock-totvs-builder** está o detalhamento de como criar estes arquivos;
3. Estes arquivos devem ser salvos na pasta **"data"** deste projeto.

# Iniciando o Serviço
1. Executar o comando **npm i** para instalar as dependências do projeto (executar somente a primeira vez);
2. Executar o comando **nodemon index.js** para carregar o serviço;
3. Deverá apresentar a mensagem **listen on 3000**;
4. O serviço estará disponível no caminho:<br>http://localhost:3000/<br>Onde serão apresentadas todas as entidades configuradas na pasta **"data"** deste projeto.
- **Obs**: A aplicação faz load automático das alterações após salvar, não é necessário reiniciar o serviço quando for realizada alguma alteração no arquivo de configuração da entidade.
