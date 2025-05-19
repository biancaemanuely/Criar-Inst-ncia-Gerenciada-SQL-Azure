🌐 Desafio DIO - Configuração de Banco de Dados no Azure
Este repositório foi criado como parte do desafio proposto pela Digital Innovation One (DIO). O objetivo é documentar a experiência prática com a plataforma Microsoft Azure, focando na configuração de instâncias de Banco de Dados e no uso de recursos da nuvem de forma eficiente.

📌 Objetivo do Desafio
Praticar a criação e configuração de uma instância de banco de dados no Microsoft Azure.

Consolidar os aprendizados das vídeo-aulas em um ambiente real.

Utilizar o GitHub como ferramenta de documentação e portfólio técnico.

Criar um material de apoio para estudos e futuras implementações.

🧾 O que é uma Máquina Virtual (VM)?
Uma Máquina Virtual (VM) é um ambiente isolado que simula um computador físico, permitindo executar sistemas operacionais e aplicativos como se fosse uma máquina real. No Azure, as VMs são usadas para uma variedade de propósitos, como testes, desenvolvimento, servidores web, bancos de dados e mais.

🚀 Passo a Passo: Criação de Instância de Banco de Dados no Azure
1. Acesse o Azure
Vá até: https://portal.azure.com

Faça login com sua conta.

2. Criar recurso de Banco de Dados
Clique em "Criar um recurso"

Selecione "Banco de Dados SQL" ou outro tipo, conforme necessário

3. Informações básicas
Nome do servidor: nome único global

Autenticação: escolha senha ou autenticação mista

Localização: escolha a região mais próxima

Grupo de recursos: crie um novo ou escolha um existente

4. Configuração do banco
Nome do banco: insira um nome representativo

Escolha a camada de desempenho (DTU ou vCore)

Defina redundância e backup conforme o objetivo

5. Regras de firewall
Autorize o IP da sua máquina local para acesso

Configure regras adicionais se necessário

6. Conexão com o banco
Após provisionado, clique em "Ir para o recurso"

Copie a string de conexão

Use ferramentas como Azure Data Studio, SSMS ou DBeaver para conectar

📝 Anotações e Dicas
🔐 Segurança: Nunca compartilhe suas strings de conexão com senhas públicas.

📊 Monitoramento: Use o painel de métricas para acompanhar o desempenho do banco.

💡 Custo: Monitore o uso para evitar cobranças indesejadas, especialmente em ambientes de testes.

