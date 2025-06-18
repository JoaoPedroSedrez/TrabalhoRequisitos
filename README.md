# TrabalhoRequisitos
Trabalho Final de Engenharia de Requisitos - 3 Semestre


a) Definição do Problema e Escopo do Produto:
o Descrição geral da ideia do sistema.
o Objetivos principais.
o Escopo (ações o que estarão incluídas no produto de software).


- Projeto visa solucionar a necessidade da falta de organização financeiro em companhias como mercados, lanchonetes, clínicas odontológicas, petshop, lojas de varejo, restaurantes, hospitais, etc.


-  O objetivo do produto é o controle financeiro de empresas, sendo capaz de registrar o movimento financeiro, independente do porte e segmento.

  
- Organizar receitas e despesas, manter todo o controle do que é entrada e saída da carteira da empresa. Registrar mensalmente e apontar áreas de maiores investimentos, gastos e lucros. Relatórios e gráficos de acordo com o período estipulado, seja semanal, mensal, trimestral, semestral, anual, etc. Mnater histórico de todas as transações feitas.

a) Definição do Problema e Escopo do Produto
Descrição Geral da Ideia do Sistema
O sistema tem como objetivo auxiliar pequenos empresários, como donos de restaurantes, a controlarem suas finanças de forma prática e organizada. Atualmente, muitos utilizam planilhas para registrar receitas, despesas e investimentos, o que torna o processo manual, propenso a erros e difícil de visualizar. O sistema pretende substituir essas planilhas com uma solução automatizada, acessível via web, com dashboards, relatórios e gráficos que facilitam o entendimento financeiro do negócio.

Objetivos Principais
Substituir planilhas manuais por um sistema automatizado e confiável.

Oferecer visão clara e detalhada das finanças (receitas, despesas, saldo, valores guardados e investimentos).

Permitir acompanhamento por período (diário, semanal, mensal, anual).

Facilitar a análise com relatórios e gráficos dinâmicos.

Ajudar empresários na tomada de decisões financeiras.

Escopo (Funcionalidades incluídas no sistema)
Cadastro de receitas, despesas, valores guardados e investimentos.

Criação, edição e exclusão de categorias personalizadas.

Dashboard com visão geral da saúde financeira.

Relatórios financeiros com filtros por data, categoria e tipo.

Fechamento de períodos (dia, semana, mês, ano).

Histórico financeiro com busca por descrição e categoria.

Gráficos e indicadores visuais para facilitar análises.

Sistema responsivo (acesso via desktop e mobile).

b) Levantamento de Requisitos
Técnicas Utilizadas
Entrevista simulada com stakeholder (pequeno empresário).

Brainstorming com grupo de desenvolvimento.

Análise de processos manuais existentes em planilhas.

Resumo da Entrevista (Simulada)
O usuário relatou que atualmente utiliza planilhas separadas para diferentes tipos de movimentações (receitas, despesas, investimentos). Tem dificuldades em gerar relatórios, visualizar o desempenho financeiro por períodos e identificar padrões. Deseja um sistema simples, visual e acessível via navegador.

Resumo do Brainstorming
Durante o brainstorming, foram levantadas necessidades como:

Interface visual com dashboards e gráficos.

Facilidade na consulta por categorias e períodos.

Automatização do fechamento de períodos.

Histórico detalhado e seguro.

Responsividade para uso no celular e computador.

Registro dos Requisitos Coletados
Cadastro de receitas, despesas, valores guardados e investimentos.

Criação e gerenciamento de categorias personalizadas.

Geração de relatórios com filtros por data, categoria e tipo de movimentação.

Dashboard com visão geral da saúde financeira.

Visualização dos dados por períodos: diário, semanal, mensal, anual.

Fechamento de ciclos financeiros.

Histórico detalhado com busca por descrição e categoria.

Gráficos e indicadores visuais.

Acesso web responsivo (desktop e mobile).

Interface limpa, simples e objetiva.

Criptografia de dados financeiros.

Tempo de resposta de até 3 segundos.

c) Classificação e Organização dos Requisitos
Requisitos Funcionais (RF)
Código	Descrição
RF01	Permitir o cadastro de receitas, despesas, valores guardados e investimentos.
RF02	Permitir criação, edição e exclusão de categorias personalizadas.
RF03	Gerar relatórios financeiros detalhados com filtros por data, categoria e tipo.
RF04	Exibir um dashboard com visão geral da saúde financeira do negócio.
RF05	Permitir visualização e acompanhamento de dados por período (dia, semana, mês, ano).
RF06	Permitir o fechamento de períodos financeiros com arquivamento automático.
RF07	Exibir gráficos e indicadores visuais sobre movimentações financeiras.
RF08	Permitir consulta ao histórico financeiro com busca por descrição e categoria.
RF09	Tornar o sistema acessível via web, de forma responsiva para desktop e mobile.

Requisitos Não Funcionais (RNF)
Código	Descrição
RNF01	O sistema deve ter interface simples, limpa e intuitiva.
RNF02	O tempo de resposta do sistema deve ser de no máximo 3 segundos.
RNF03	O sistema deve ser responsivo, funcionando em diferentes dispositivos.
RNF04	O sistema deve garantir segurança dos dados com criptografia RSA.
RNF05	O sistema deve permitir fácil manutenção e atualizações futuras.
RNF06	O sistema deve realizar backup automático das informações financeiras.
RNF07	O sistema deve seguir boas práticas de usabilidade e acessibilidade.
RNF08	A arquitetura do sistema deve permitir escalabilidade para múltiplos usuários.

📊 Matriz de Rastreabilidade dos Requisitos
Código	Requisito	Objetivo(s) Relacionado(s)	RNF Relacionado(s)
RF01	Cadastro de receitas, despesas, valores guardados e investimentos.	OBJ1, OBJ2	RNF01, RNF02, RNF03
RF02	Criação, edição e exclusão de categorias personalizadas.	OBJ1, OBJ2	RNF01, RNF02
RF03	Relatórios detalhados com filtros por data, categoria e tipo.	OBJ3, OBJ4	RNF01, RNF02
RF04	Dashboard com visão geral da saúde financeira.	OBJ2, OBJ4	RNF01, RNF03
RF05	Acompanhamento por períodos: diário, semanal, mensal, anual.	OBJ2, OBJ3	RNF01, RNF02
RF06	Fechamento de ciclos financeiros.	OBJ2, OBJ3	RNF01, RNF05
RF07	Gráficos e indicadores visuais.	OBJ4, OBJ5	RNF01, RNF07
RF08	Consulta ao histórico financeiro detalhado.	OBJ3, OBJ5	RNF01, RNF02, RNF04
RF09	Sistema web responsivo (desktop e mobile).	OBJ1, OBJ2	RNF03, RNF08

Legenda de Objetivos (OBJ):

OBJ1: Substituir planilhas manuais por sistema automatizado.

OBJ2: Oferecer visão clara e organizada das finanças.

OBJ3: Acompanhar resultados por períodos.

OBJ4: Facilitar análises com relatórios e gráficos.

OBJ5: Auxiliar na tomada de decisões.
