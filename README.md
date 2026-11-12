# 💸 App de Finanças Pessoais da Ana com Vibe Coding

PRD reavaliado no CopilotWeb:

# PRODUCT BRIEF

Crie um MVP de um aplicativo de finanças pessoais baseado em conversação chamado provisoriamente de "Agente Financeiro".

O objetivo é ajudar pessoas comuns a organizarem suas finanças através de linguagem natural, sem planilhas complexas, formulários extensos ou necessidade de conhecimento financeiro prévio.

A experiência principal deve ser tão simples quanto conversar com um amigo em um aplicativo de mensagens.

O produto deve transmitir:

- Simplicidade
- Confiança
- Clareza
- Acolhimento
- Educação Financeira

---

# PROBLEMA

Muitas pessoas desistem de controlar suas finanças porque os aplicativos atuais exigem muito esforço manual.

Principais dores:

- Cadastro de despesas demorado
- Interfaces complexas
- Excesso de gráficos difíceis de interpretar
- Pouca personalização
- Falta de orientação para iniciantes

O produto deve reduzir a fricção e incentivar o hábito financeiro através de uma experiência conversacional.

---

# PÚBLICO-ALVO

Usuários iniciantes em organização financeira.

Perfil:

- 18 a 45 anos
- Pouca experiência com aplicativos financeiros
- Desejam economizar dinheiro
- Buscam uma solução simples
- Possuem diferentes níveis de alfabetização digital

Não assumir conhecimento financeiro avançado.

---

# OBJETIVO DO MVP

Validar que usuários conseguem controlar suas finanças utilizando apenas conversação.

O usuário deve conseguir:

1. Registrar receitas.
2. Registrar despesas.
3. Criar metas financeiras.
4. Acompanhar sua evolução financeira.
5. Receber recomendações personalizadas.
6. Entender sua situação financeira sem treinamento prévio.

---

# FUNCIONALIDADE PRINCIPAL

A principal interface do produto deve ser um chat inteligente.

Exemplos de interação:

Usuário:
"Gastei R$ 35 no almoço."

Sistema:
✅ Despesa registrada.

Categoria: Alimentação
Valor: R$35

----------------

Usuário:
"Recebi R$ 2.500 de salário."

Sistema:
✅ Receita registrada.

Categoria: Salário
Valor: R$2.500

----------------

Usuário:
"Quero guardar R$ 3.000 para viajar."

Sistema:
Qual prazo deseja para atingir essa meta?

---

# FUNCIONALIDADES DO MVP

## 1. Registro Conversacional

Permitir registro através de linguagem natural.

Extrair automaticamente:

- Receita ou despesa
- Valor
- Categoria
- Data

Caso falte informação, solicitar apenas o dado necessário.

Exemplo:

Usuário:
"Gastei no mercado."

Sistema:
Qual foi o valor dessa compra?

---

## 2. Classificação Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Outros

A IA deve sugerir categorias automaticamente.

Caso exista dúvida, pedir confirmação.

---

## 3. Gestão de Metas

Permitir:

- Criar metas
- Editar metas
- Acompanhar progresso

Exibir:

- Nome da meta
- Valor alvo
- Valor acumulado
- Percentual concluído
- Prazo

---

## 4. Agente Financeiro

Criar um assistente financeiro educativo.

Funções:

- Interpretar hábitos de consumo
- Identificar padrões
- Apontar oportunidades de economia
- Incentivar metas financeiras

Exemplos:

"Você gastou 18% mais com alimentação este mês."

"Se economizar R$10 por dia poderá guardar cerca de R$300 por mês."

"Sua meta está 20% concluída."

Nunca utilizar linguagem crítica ou julgadora.

Sempre utilizar tom amigável e educativo.

---

## 5. Relatórios Simples

Criar relatórios fáceis de entender.

Mostrar:

- Total recebido
- Total gasto
- Saldo disponível
- Categorias com maior gasto
- Evolução mensal

Evitar jargões financeiros.

Preferir:

✅ Entrou
✅ Saiu
✅ Sobrou

Em vez de:

❌ Fluxo financeiro
❌ Resultado líquido
❌ Patrimônio líquido

---

# TELAS

## Tela 1 – Boas-vindas

Objetivo:

Explicar rapidamente o valor do produto.

Elementos:

- Mensagem de boas-vindas
- Benefícios principais
- Botão "Começar"

---

## Tela 2 – Onboarding

Fluxo simples com duração máxima de 1 minuto.

Coletar apenas:

- Nome
- Principal objetivo financeiro

---

## Tela 3 – Chat Principal

Tela mais importante da aplicação.

Elementos:

- Histórico de mensagens
- Campo de entrada
- Sugestões rápidas

Sugestões:

- Registrar gasto
- Registrar receita
- Criar meta
- Ver resumo

Inspirada em aplicativos modernos de mensagens.

---

## Tela 4 – Histórico

Lista de movimentações.

Filtros:

- Hoje
- Semana
- Mês

Informações:

- Categoria
- Valor
- Data

---

## Tela 5 – Metas

Visualização das metas financeiras.

Mostrar:

- Progresso
- Valor acumulado
- Prazo
- Percentual atingido

---

## Tela 6 – Relatórios

Dashboard simples.

Mostrar:

- Gastos por categoria
- Evolução dos gastos
- Saldo mensal

Visual limpo e intuitivo.

---

# DESIGN UNIVERSAL

Todo o produto deve ser criado seguindo os princípios do Design Universal.

O aplicativo deve oferecer uma ótima experiência para o maior número possível de pessoas, independentemente de:

- Idade
- Escolaridade
- Experiência tecnológica
- Limitações visuais
- Limitações motoras
- Limitações cognitivas

Projetar para inclusão desde a primeira versão.

---

# ACESSIBILIDADE

Seguir padrões WCAG AA.

Implementar:

- Navegação por teclado
- Compatibilidade com leitores de tela
- Alto contraste
- Estados de foco visíveis
- Labels acessíveis
- Texto redimensionável
- Botões grandes para dispositivos móveis

Nunca depender apenas de cor para transmitir informação.

Todos os feedbacks devem possuir texto explícito.

---

# UX WRITING

Toda comunicação deve ser:

- Conversacional
- Simples
- Humana
- Educativa
- Motivadora

Evitar:

- Linguagem corporativa
- Jargões financeiros
- Mensagens robotizadas

O sistema deve parecer um mentor financeiro amigável.

---

# DIRETRIZES DE DESIGN

Estilo visual:

- Mobile First
- Minimalista
- Moderno
- Limpo
- Acolhedor

Referências visuais:

- WhatsApp
- Nubank
- Duolingo
- Microsoft Copilot

Utilizar:

- Muito espaço em branco
- Hierarquia visual clara
- Componentes simples
- Tipografia altamente legível
- Interface intuitiva

Modo claro e modo escuro.

---

# STACK TECNOLÓGICA

Utilizar:

- React
- TypeScript
- Tailwind CSS
- Supabase

Estruturar para permitir futuras integrações com:

- IA generativa
- Open Finance
- Assistente por voz

---

# REQUISITOS NÃO FUNCIONAIS

O usuário deve ser capaz de:

- Registrar uma despesa em menos de 10 segundos.
- Criar uma meta em menos de 1 minuto.
- Entender o status de suas finanças em menos de 30 segundos.

Priorizar simplicidade ao invés de quantidade de funcionalidades.

---

# FORA DO ESCOPO DO MVP

Não implementar nesta versão:

- Integrações bancárias
- Open Finance
- Cartões de crédito
- Investimentos
- Planejamento tributário
- Importação de extratos
- Assistente por voz

---

# CRITÉRIOS DE SUCESSO

O MVP será considerado validado quando:

- Usuários conseguirem registrar gastos por linguagem natural.
- Pelo menos 70% das transações forem classificadas corretamente.
- Pelo menos 40% dos usuários criarem uma meta financeira.
- Os usuários perceberem o aplicativo como mais simples que aplicativos financeiros tradicionais.

---

# ENTREGA ESPERADA

Gerar uma aplicação completa com:

- Arquitetura organizada
- Banco de dados estruturado
- Interface responsiva
- Componentes reutilizáveis
- Dados demonstrativos
- Navegação funcional
- Design Universal
- Acessibilidade nativa
- Experiência Mobile First

A experiência deve transmitir simplicidade, clareza, confiança e incentivar hábitos financeiros saudáveis para iniciantes.
Resultado no Lovable:https://lovable.dev/projects/940d6d3a-8e79-4481-a161-6e23a553a5f1?magic_link=mc_d46ed686-a3b5-41e8-a1ca-60dc113352e8
Resumo do que o app faz:<img width="398" height="2268" alt="image" src="https://github.com/user-attachments/assets/c888d7a4-d8bd-4f10-8831-90f672ae1ca6" />
O que não funcionou bem: eram poucos créditos gratuitos na Lovable então era algo mais lento e pousado.
O que aprendi: com um bom prompt o resultado fica melhor, aprendendo a estruturar.



  
