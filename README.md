# 💸 App de de Finanças Pessoais de Fernando com Vibe Coding

PRD refinado no Copilot Web:

```

# PRD - FinanChat

## Visão Geral

O FinanChat é um aplicativo de gestão financeira pessoal baseado em conversa, permitindo que usuários registrem movimentações financeiras utilizando linguagem natural.

O sistema interpreta mensagens enviadas pelo usuário, classifica automaticamente receitas e despesas, acompanha metas financeiras e oferece recomendações simples para melhorar a saúde financeira.

O objetivo é reduzir a fricção encontrada nos aplicativos tradicionais de controle financeiro e incentivar a criação de hábitos financeiros consistentes.

---

## Problema

Muitas pessoas abandonam aplicativos de finanças devido à necessidade de preenchimento manual de formulários, categorização de gastos e análise de relatórios complexos.

Essas barreiras aumentam o esforço necessário para manter o controle financeiro e dificultam a continuidade do uso ao longo do tempo.

---

## Objetivo do Produto

Permitir que qualquer pessoa organize suas finanças por meio de conversas simples e intuitivas, sem necessidade de conhecimento prévio sobre educação financeira ou sistemas de gestão financeira.

---

## Público-Alvo

### Público Primário

Pessoas entre 18 e 45 anos que desejam organizar suas finanças pessoais pela primeira vez.

### Público Secundário

Usuários que atualmente utilizam planilhas ou aplicativos financeiros tradicionais e procuram uma solução mais prática e conversacional.

---

## Proposta de Valor

"Converse com suas finanças como conversa com um amigo."

O usuário não precisa preencher formulários, escolher categorias manualmente ou interpretar gráficos complexos.

Basta informar receitas e despesas de forma natural para receber acompanhamento financeiro automatizado.

---

# Princípios de Produto

## Simplicidade

Toda interação deve minimizar esforço e complexidade.

O usuário deve conseguir registrar uma movimentação financeira em poucos segundos utilizando linguagem natural.

## Educação Financeira

O sistema deve ensinar conceitos financeiros de forma leve, prática e contextualizada.

## Design Universal

O produto deve seguir princípios de Design Universal para garantir uma experiência acessível, intuitiva e inclusiva para o maior número possível de pessoas.

A interface deve atender usuários com diferentes níveis de experiência tecnológica, condições físicas, idades e conhecimentos financeiros.

### Diretrizes de Design Universal

- Linguagem simples e objetiva.
- Evitar termos financeiros complexos.
- Alto contraste para leitura.
- Fontes legíveis e escaláveis.
- Compatibilidade com leitores de tela.
- Navegação consistente e previsível.
- Ícones sempre acompanhados de texto.
- Feedback claro após cada ação.
- Não depender exclusivamente de cores para transmitir informações.
- Interface otimizada para dispositivos móveis.
- Fluxos com o menor número possível de etapas.
- Experiência adequada para usuários iniciantes e avançados.

### Requisitos de Acessibilidade

- Seguir diretrizes WCAG AA sempre que possível.
- Permitir navegação por teclado.
- Utilizar combinações de cores adequadas para usuários com daltonismo.
- Possuir descrições acessíveis para elementos interativos.
- Exibir mensagens de erro claras e orientadas à solução.

---

# Funcionalidades do MVP

## 1. Registro de Transações por Linguagem Natural

O usuário poderá registrar movimentações financeiras através de mensagens de texto.

### Exemplos

- "Gastei R$ 45 no almoço."
- "Recebi meu salário de R$ 4.500."
- "Paguei R$ 120 de internet."

### Resultado Esperado

O sistema identifica automaticamente:

- Valor
- Tipo da transação
- Categoria
- Data

---

## 2. Classificação Automática

O sistema deve classificar automaticamente as movimentações.

### Categorias Iniciais

- Alimentação
- Transporte
- Moradia
- Saúde
- Lazer
- Educação
- Salário
- Outros

O usuário poderá corrigir categorias quando necessário.

---

## 3. Dashboard Simplificado

O aplicativo deve apresentar indicadores principais de forma clara e fácil de entender.

### Informações Exibidas

- Saldo atual
- Receitas do mês
- Despesas do mês
- Principais categorias de gastos
- Evolução mensal

---

## 4. Metas Financeiras

Permitir a criação e acompanhamento de metas.

### Exemplos

- Guardar R$ 5.000
- Economizar R$ 300 por mês
- Criar reserva de emergência

### Informações Exibidas

- Percentual concluído
- Valor acumulado
- Valor restante
- Previsão de conclusão

---

## 5. Agente Financeiro

O sistema deve gerar recomendações automáticas com base no comportamento financeiro do usuário.

### Exemplos

- "Você gastou 25% mais com alimentação este mês."
- "Se reduzir R$ 10 por dia em delivery, poderá economizar cerca de R$ 300 por mês."
- "Sua meta de reserva de emergência está 70% concluída."

---

# Fluxo Principal do Usuário

## Primeiro Acesso

1. Criar conta.
2. Informar renda mensal aproximada.
3. Definir primeira meta financeira.
4. Iniciar conversa com o assistente.

## Uso Diário

1. Enviar mensagem em linguagem natural.
2. O sistema interpreta a transação.
3. A movimentação é registrada.
4. O dashboard é atualizado.
5. O Agente Financeiro gera insights quando apropriado.

---

# Telas do MVP

## Tela 1 - Onboarding

Objetivo:

Coletar informações iniciais do usuário.

Campos:

- Nome
- Renda mensal
- Objetivo financeiro principal

---

## Tela 2 - Chat Principal

Objetivo:

Permitir o registro de movimentações e interação com o Agente Financeiro.

Elementos:

- Histórico de conversa
- Campo de mensagem
- Sugestões rápidas
- Ações frequentes

---

## Tela 3 - Dashboard

Objetivo:

Fornecer visão geral da situação financeira.

Elementos:

- Saldo atual
- Receitas
- Despesas
- Categorias
- Evolução mensal

---

## Tela 4 - Metas Financeiras

Objetivo:

Permitir acompanhamento das metas.

Elementos:

- Lista de metas
- Percentual de progresso
- Valor acumulado
- Previsão de conclusão

---

## Tela 5 - Perfil e Configurações

Objetivo:

Gerenciar informações pessoais e preferências.

Elementos:

- Dados do usuário
- Configurações
- Preferências do assistente

---

# Fora do Escopo do MVP

As funcionalidades abaixo não devem ser implementadas na primeira versão:

- Open Finance
- Integração bancária automática
- Sincronização com cartão de crédito
- Investimentos
- Controle tributário
- Gestão financeira familiar
- Planejamento patrimonial

---

# Critérios de Sucesso

O MVP será considerado validado quando atingir os seguintes indicadores:

- 80% ou mais de classificação correta das transações.
- Tempo médio de registro inferior a 10 segundos.
- Pelo menos 50% dos usuários retornando após 7 dias.
- Pelo menos uma meta financeira criada por usuário.
- Avaliação positiva da experiência de uso por usuários iniciantes.

---

# Requisitos Não Funcionais

- Interface mobile-first.
- Linguagem em português do Brasil.
- Tempo de resposta inferior a 3 segundos.
- Arquitetura escalável.
- Design Universal como requisito obrigatório.
- Interface acessível e inclusiva.
- Experiência consistente em diferentes tamanhos de tela.

---

# Plano de Validação Inicial

## Hipótese Principal

Usuários preferem registrar despesas e receitas através de conversas em linguagem natural em vez de utilizar formulários tradicionais.

## Teste Inicial

Disponibilizar o MVP para um grupo entre 10 e 20 usuários.

## Métricas Avaliadas

- Número de transações registradas.
- Frequência de uso.
- Retenção semanal.
- Tempo médio de registro.
- Feedback qualitativo dos usuários.

---

# Entregável Esperado da IA

Ao utilizar este documento em plataformas de vibe coding, a IA deve gerar:

1. Arquitetura inicial do sistema.
2. Fluxo de navegação completo.
3. Wireframes das principais telas.
4. Estrutura inicial de banco de dados.
5. Componentes de interface.
6. Sistema de chat em linguagem natural.
7. Dashboard financeiro simplificado.
8. Sistema de metas financeiras.
9. Plano de validação do MVP.

A solução deve priorizar:

- Simplicidade.
- Design Universal.
- Acessibilidade.
- Experiência mobile-first.
- Facilidade de aprendizado.
- Baixa fricção para usuários iniciantes.

```
Interações com o Lovable:
> Crie um app de financas pessoais com base no seguinte PRD

Resultado final no Lovable: https://chatta-financas.lovable.app

<img width="1920" height="916" alt="Captura de tela 2026-10-13 154715" src="https://github.com/user-attachments/assets/72ef078c-353b-499f-90fc-e457f1f706bd" />

# FinanChat

FinanChat é um aplicativo de finanças pessoais baseado em conversas, criado para simplificar o controle financeiro de usuários iniciantes.

Ao invés de utilizar formulários complexos ou planilhas, o usuário registra receitas e despesas utilizando linguagem natural, enquanto o sistema organiza automaticamente as informações e apresenta insights financeiros de forma simples e acessível.

---

## Principais Funcionalidades

### Registro de movimentações por linguagem natural

O usuário pode registrar receitas e despesas através de mensagens simples.

Exemplos:

- "Gastei R$ 30 no almoço"
- "Recebi R$ 100 pelo trabalho"
- "Paguei R$ 120 de internet"

O sistema interpreta automaticamente a informação e cria a transação financeira.

---

### Classificação automática de categorias

As movimentações são categorizadas automaticamente para facilitar a organização financeira.

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Salário
- Outros

O usuário também pode corrigir categorias diretamente pela interface.

---

### Dashboard financeiro simplificado

O painel principal apresenta uma visão geral da situação financeira do usuário.

Indicadores disponíveis:

- Saldo atual
- Receitas do mês
- Despesas do mês
- Principais categorias de gastos
- Evolução financeira mensal

---

### Visualização dos maiores gastos

O sistema identifica automaticamente onde o usuário mais gastou durante o mês, ajudando a compreender hábitos financeiros e oportunidades de economia.

---

### Evolução mensal

Gráficos simples permitem acompanhar a evolução das receitas e despesas ao longo dos meses.

Essa visualização facilita a identificação de tendências e mudanças no comportamento financeiro.

---

### Histórico de movimentações

O usuário pode consultar as transações registradas recentemente.

Cada movimentação apresenta:

- Descrição
- Tipo (receita ou despesa)
- Data
- Categoria
- Valor

---

### Edição rápida de categorias

Caso uma movimentação seja categorizada incorretamente, o usuário pode ajustá-la diretamente na lista de transações.

---

### Exclusão de movimentações

Transações podem ser removidas facilmente em caso de erro no lançamento.

---

### Sistema de metas financeiras

O aplicativo possui uma área dedicada ao acompanhamento de objetivos financeiros.

Exemplos:

- Reserva de emergência
- Compra de equipamentos
- Viagens
- Projetos pessoais

Cada meta pode apresentar progresso, valor acumulado e acompanhamento da evolução.

---

### Agente Financeiro Inteligente (Planejado)

O FinanChat foi projetado para evoluir para um assistente financeiro inteligente capaz de gerar recomendações personalizadas com base no comportamento do usuário.

Exemplos:

- Alertas sobre aumento de gastos.
- Sugestões de economia.
- Acompanhamento de metas.
- Insights financeiros personalizados.

---

## Design Universal

O FinanChat segue princípios de Design Universal para oferecer uma experiência acessível ao maior número possível de usuários.

Alguns princípios adotados:

- Linguagem simples e objetiva.
- Interface intuitiva.
- Alto contraste para leitura.
- Navegação consistente.
- Compatibilidade com dispositivos móveis.
- Acessibilidade para diferentes perfis de usuários.
- Baixa curva de aprendizado.

---

## Objetivo do Projeto

Democratizar o controle financeiro pessoal através de uma experiência conversacional simples, intuitiva e acessível, permitindo que qualquer pessoa organize suas finanças sem conhecimento técnico ou financeiro avançado.

## Reflexão

### O que funcionou bem?
O refinamento do PRD feito previamente no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.

### O que não funcionou como esperado?
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.

### O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa, quanto mais detalhes e clareza você dá, melhor a interação.
