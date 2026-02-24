##App de Finanças Pessoais da Brenda (Meu Money) com Vibe Coding:

## PRD Refinado no Copilot Web

````markdown
### 1. Contexto
O aplicativo busca simplificar o controle financeiro por meio de interações em linguagem natural. Em vez de formulários e planilhas, o usuário conversa com um “Agente Financeiro” que registra gastos, sugere economias e ajuda a acompanhar metas.

### 2. Problema
- Apps atuais exigem muita entrada manual.
- Pouca personalização e experiência engessada.
- Usuários iniciantes desistem rapidamente por falta de praticidade.
**Oportunidade:** criar uma experiência fluida, acessível e personalizada, baseada em conversas, que incentive o usuário a manter o hábito de organizar suas finanças.

### 3. Público-Alvo
- Pessoas que estão começando a organizar suas finanças.
- Usuários que buscam praticidade e simplicidade.
- Jovens adultos e iniciantes em educação financeira.

### 4. Funcionalidades-Chave
- Registro de gastos via chat em linguagem natural.
- Classificação automática das transações (alimentação, transporte, lazer etc.).
- Metas financeiras: definir objetivos e acompanhar progresso.
- Agente Financeiro: dicas de economia personalizadas.
- Relatórios simples e visuais: gráficos e resumos adaptados ao perfil do usuário.
- Análise de estilo de vida e movimentações:
  - Avaliar hábitos de consumo e padrões de gastos.
  - Gerar recomendações individuais para melhorar a saúde financeira.
  - Sugerir formas de investir melhor e administrar recursos de acordo com o perfil do usuário.
  - Criar uma experiência única e personalizada para cada cliente.

### 5. Design Universal, Estética e Acessibilidade
- Estética convidativa, amigável e inteligente, transmitindo confiança ao usuário.
- Uso de cores que reforcem segurança, clareza e assertividade, como azuis, verdes e tons neutros equilibrados.
- Design minimalista, com elementos visuais limpos e intuitivos, remetendo a apps de finanças, mas com liberdade para ser mais diversificado e moderno.
- Design universal e acessível, garantindo que todas as pessoas possam usar com facilidade:
  - Compatibilidade com leitores de tela.
  - Contraste adequado e tipografia legível.
  - Navegação simples e inclusiva.
- Experiência consistente em diferentes dispositivos (mobile e desktop).

### 6. Segurança e LGPD
- Proteção de dados sensíveis: todas as informações financeiras e de estilo de vida dos clientes devem ser armazenadas de forma segura, com criptografia em trânsito e em repouso.
- Conformidade com a LGPD: coleta e uso de dados devem respeitar a legislação brasileira de proteção de dados, garantindo transparência e consentimento do usuário.
- Privacidade como prioridade: nenhuma informação pessoal ou financeira pode ser compartilhada sem autorização explícita.
- Cibersegurança: implementação de boas práticas como autenticação forte, monitoramento de acessos e prevenção contra vazamentos.

#### 6.1 Requisitos Técnicos Mínimos de Segurança
- Criptografia: TLS/SSL em trânsito e AES-256 em repouso.
- Autenticação: multifator (MFA), gestão de sessões seguras e RBAC.
- Proteção contra ataques: IDS/IPS, firewall, prevenção contra SQL Injection, XSS e CSRF.
- LGPD: consentimento explícito, opção de exclusão de dados, transparência em políticas.
- Backups: automáticos, criptografados e com plano de recuperação de desastres.
- Auditoria: logs detalhados, revisões periódicas e relatórios de conformidade.

### 7. Exemplos de Interação do Agente Financeiro
**Registro de gasto:**  
- Usuário: “Gastei R$ 80 em um jantar ontem.”
- Agente: “Anotado! Esse gasto foi classificado como alimentação. Você gostaria de adicionar uma meta para reduzir gastos com restaurantes este mês?”

**Análise de estilo de vida:**  
- Usuário: “Sim, quero gastar menos com restaurantes.”
- Agente: “Percebi que, nos últimos 3 meses, seus gastos com alimentação fora de casa aumentaram 20%. Se ajustarmos sua meta para R$ 300 mensais, você pode economizar cerca de R$ 150 por mês. Essa economia pode ser direcionada para um fundo de emergência ou para começar a investir em renda fixa.”

**Recomendações personalizadas:**  
- Usuário: “Gostei da ideia. Como posso investir esse valor?”
- Agente: “Com base no seu perfil de gastos e estilo de vida, sugiro começar com investimentos de baixo risco, como CDBs ou Tesouro Direto. Se mantiver essa disciplina, em 12 meses terá acumulado aproximadamente R$ 1.800.”

**Relatórios e motivação:**  
- Usuário: “Quero acompanhar meu progresso.”
- Agente: “Aqui está um relatório simples: você já economizou R$ 200 este mês em comparação ao anterior. Parabéns! Esse é um ótimo começo para construir uma vida financeira mais saudável.”

### 8. Entregável da IA
- Plano de MVP com:
  - Principais telas (chat, relatórios, metas, análise personalizada).
  - Recursos mínimos necessários (NLP para entender linguagem natural, categorização automática, motor de recomendações personalizadas, geração de relatórios).
  - Esboço de validação inicial (testes com usuários iniciantes e com necessidades diversas, feedback sobre clareza, acessibilidade, relevância das recomendações e percepção de segurança).
- Linguagem acessível e educativa, em português.

### 9. Critérios de Sucesso do MVP
1. Registro de gastos via chat: usuários conseguem registrar gastos em linguagem natural sem dificuldade; sistema entende corretamente pelo menos 80% das entradas simples.
2. Classificação automática: transações categorizadas de forma clara e coerente; usuários não precisam corrigir manualmente a maioria das classificações.
3. Metas e relatórios: usuários definem metas básicas e entendem relatórios simples; relatórios são compreendidos por iniciantes.
4. Personalização e recomendações: dicas relevantes com base no estilo de vida; pelo menos 70% dos usuários relatam que as recomendações são úteis.
5. Experiência de uso: feedback positivo sobre clareza, acessibilidade e estética; percepção de design convidativo e confiável.
6. Segurança e confiança: usuários sentem que seus dados estão protegidos; MVP demonstra conformidade básica com LGPD.

````

## Interações com o Lovable

**Prompt enviado:**  
> Crie um App de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}  

**Problemas identificados:**  
> O aplicativo não está funcional. Preciso que tenha uma parte para cadastrar o usuário, com login e senha, para que cada usuário tenha uma experiência personalizada no app. O nome do app é Meu Money, e o agente financeiro não está funcionando corretamente: não está sendo responsivo e também não está registrando gastos nem criando metas automaticamente, de acordo com a conversa com o usuário.

Preciso que isso seja ajustado. Também não está sendo possível criar metas manualmente. Lembrando que o app também precisa ter um design universal, acessível para todos que o utilizarem.

**Resultado final no Lovable:**  
https://meumoneyfinance.lovable.app

<img width="1297" height="840" alt="app 8" src="https://github.com/user-attachments/assets/862309e8-974c-42ec-aa84-f5b89f57b8ed" />

---

## Funcionalidades do Meu Money

### 1. Autenticação e Segurança
- Cadastro com nome, e-mail e senha  
- Login seguro com e-mail e senha  
- Recuperação de senha via e-mail  
- Rotas protegidas: cada usuário acessa apenas seus próprios dados  
- Conformidade com LGPD e práticas de cibersegurança  

### 2. Agente Financeiro com IA
- Entende linguagem natural usando Lovable AI (Gemini)  
- Registra gastos automaticamente a partir de frases como “Gastei R$ 80 em um jantar”  
- Cria metas financeiras quando solicitado (“Quero economizar R$ 500 este mês”)  
- Dá dicas personalizadas com base nos dados reais do usuário  
- Histórico de conversas salvo no banco de dados  

### 3. Metas Financeiras
- Criação manual de metas com formulário completo  
- Acompanhamento visual do progresso com barras  
- Possibilidade de adicionar valores diretamente às metas  

### 4. Dashboard e Transações
- Dados reais integrados ao banco de dados  
- Gráficos dinâmicos:  
  - Pizza para gastos por categoria  
  - Barras comparando receita vs despesa  
- Registro manual de transações com categorias  
- Exibição de saldo atual, receita mensal, despesas e economia  
- Histórico de transações recentes  

### 5. Design e Acessibilidade
- Interface convidativa, amigável e inteligente  
- Uso de cores que transmitem segurança, clareza e confiança  
- Design minimalista, mas diversificado, remetendo a apps de finanças  
- Labels acessíveis em todos os campos  
- Contraste adequado e navegação por teclado  
- Responsivo para mobile e desktop  

### 6. Experiência Personalizada
- Análise de estilo de vida e movimentações financeiras  
- Recomendações individuais para melhorar a saúde financeira  
- Sugestões de investimento e administração de recursos adaptadas ao perfil do usuário  
- Relatórios simples e motivacionais  
- Dicas diárias para incentivar hábitos financeiros saudáveis  

---

## Reflexão

**O que funcionou bem?**  
Como os créditos diários do Lovable acabaram em apenas duas interações, ter polido o PRD no Microsoft Copilot antes de enviar para o Lovable foi fundamental. Dessa forma, foi possível criar um protótipo completo e funcional.

**O que não funcionou como o esperado?**
Esperava ter mais interações gratuitas com o Lovable, porém acabaram não sendo necessárias no final do projeto, por já ter refinado o PRD antes.

**O que aprendeu sobre conversar com IAs?**
Que é preciso ser assertivo, ter uma noção completa dos seus objetivos e descrevê-los o mais detalhadamente possível e de forma objetiva.

# Esse foi o meu projeto criado para o Bootcamp CAIXA - Inteligência Artificial na Prática, fornecido pela empresa DIO.  
Segui as instruções do desafio e criei este protótipo de um app de finanças para validação da ideia.
