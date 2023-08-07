# Dados_Cases
# Projeto Case 1 
# Indicadores de Satisfação dos Clientes

1. Customer Satisfaction Score (CSAT)
2. Tempo Médio de Atendimento
3. Tempo Médio de Espera
4. Tempo de Resposta Inicial
5. FCR (Fist call resolution)

# Melhorias Propostas com Indicadores de Satisfação

1. Integração de Sistemas de comunicação e CRM (Customer Relationship Management) para oferecer um serviço personalizado e aprimorar as conexões entre entre clientes e empresas.

2. Integração de chatbots para ajudar a automatizar o processo de atendimento e as solicitações dos clientes, uso da Inteligência Artificial, analytics e dados para agir com base em informações coletadas e melhorar a experiência dos clientes. Informações coletadas geram dados e material necessário para monitorar e medir as atividades.

3. As métricas geram dados e insights a partir de processos automatizados de análises. Com esses dados é possível tomar decisões estrátegicas, aprimorar serviços de atendimento e oferta de produtos com qualidade e confiabilidade aos clientes.


# Projeto Case 2

# Práticas Inovadoras para Gerenciamento de Acessos

- Criar Usuários Individuais
- Requerer senhas fortes
- Usar multiplos respostas de autenticação
- Revisar regularmente os usuários criados
- Investir em ferramentas de gestão de acessos

# Projeto Case 5

# Consulta SQL de usuários cadastrados nos últimos 30 dias

-- o comando select contém o nome do campo que será retornado, o (*) é usado quando desejamos trazer todos os campos

SELECT User * FROM "users_e-mails"

-- O comando WHERE serve para filtrar registros que serão retornados 

WHERE data BETWEEN NOW ()-INTERVAL 30 DAY AND NOW()

