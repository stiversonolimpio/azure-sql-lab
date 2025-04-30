 Desafio: Criando e Configurando uma Instância de Banco de Dados no Microsoft Azure

 Descrição do Desafio

Este desafio teve como objetivo praticar a criação e configuração de uma instância de **Banco de Dados SQL** usando os serviços oferecidos pela plataforma **Microsoft Azure**.

Durante o laboratório, explorei os conceitos de banco de dados gerenciado, entendi como provisionar, acessar e gerenciar uma instância SQL e documentei tudo aqui para servir como material de apoio para estudos futuros — e quem sabe ajudar outras pessoas também!

---

 Objetivos de Aprendizagem

- Praticar o uso do portal Azure na criação de um banco SQL
- Compreender as opções de configuração de segurança, desempenho e escalabilidade
- Aprender a acessar o banco via SQL Server Management Studio (SSMS)
- Documentar todo o processo de forma organizada usando o GitHub

---

 Etapas Realizadas

1. Acesse o [portal do Azure](https://portal.azure.com)
2. Vá em **"Instâncias de banco de dados SQL"** e clique em **"Criar"**
3. Configure:
   - Nome da instância e do banco
   - Grupo de recursos
   - Usuário administrador e senha
   - Localização e camada de preço (para testes, use a camada gratuita ou básica)
4. Crie um **servidor lógico** (caso não exista)
5. Habilite **"Permitir serviços do Azure e IPs locais"** para conexão
6. Finalize e aguarde a criação da instância
7. Acesse o banco com o SSMS ou Azure Data Studio

Dicas de Estudo

Configuração de firewall:** necessário liberar seu IP para conseguir conectar ao banco fora do portal.
Camadas de serviço:** escolha com cuidado; para testes, a camada **DTU Basic** ou **vCore Servidorless** ajuda a economizar.
Backups automáticos** são incluídos nos bancos gerenciados — menos dor de cabeça!

 Estrutura do Repositório
 
  Experiência Pessoal

Achei bem interessante entender como funciona um banco de dados gerenciado, especialmente a parte de não precisar lidar com a instalação do SQL Server manualmente. Configurar as opções de segurança e escalabilidade no portal também foi bem tranquilo. É uma ferramenta muito útil, principalmente para quem vai trabalhar com aplicações que dependem de dados o tempo todo.

---

 Recursos Oficiais e Complementares

- [Início Rápido: Criar Instância Gerenciada de SQL no Azure (Microsoft Docs)](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-create-quickstart)
- [Guia Markdown GitHub](https://guides.github.com/features/mastering-markdown/)
- [GitHub Docs](https://docs.github.com/)

---

