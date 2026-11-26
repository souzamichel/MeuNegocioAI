# 🧭 Etapa 1 — Ideação e Análise Comparativa de Dores

Este documento registra o processo inicial de descoberta e avaliação de ideias de negócio para a construção de um **MVP (Produto Mínimo Viável)** com apoio de Inteligência Artificial (DIO Agent como co-founder + Lovable para prototipação).

---

## 🎯 Diretriz do Desafio para Escolha da Ideia

O objetivo não é construir uma plataforma completa logo no início, e sim lançar um **MVP enxuto** que prove uma **tese de negócio real** usando:
- **Landing page** explicando a proposta de valor;
- **Formulário** para o cliente montar seu pedido ou plano;
- **WhatsApp** como canal de fechamento manual da venda;
- **Painel de administração** com leads, clientes, entregas e lembretes.

> **Regra de ouro do MVP:** marketplace aberto (dois lados) e pagamento integrado ficam para depois que a tese for confirmada com clientes reais. No começo, o operacional nos bastidores pode (e deve) ser manual.

---

## 💡 Ideias Levantadas

### Opção 1 — Plataforma de Prestadores de Serviço em Domicílio ("Uber/iFood de Serviços")
- **Descrição da ideia:** Conectar usuários/clientes a prestadores de serviço em domicílio em categorias como pintura, acabamento, serviços gerais, limpeza, entre outros.
- **Funcionamento imaginado:** O cliente pode publicar/solicitar um serviço para receber propostas de diferentes prestadores, ou escolher e acionar diretamente um ou mais prestadores para realizar o atendimento.

### Opção 2 — Entregas Domésticas Direcionadas (Água, Gás e Itens Essenciais)
- **Descrição da ideia:** Serviço de entrega recorrente ou sob demanda para residências, cobrindo itens essenciais da rotina doméstica como água mineral, gás de cozinha e insumos similares.
- **Diferencial imaginado:** Direcionamento pensado para quem cuida da casa (como trabalhadoras domésticas ou responsáveis pela gestão residencial) e para clientes que não desejam fazer a compra diretamente no espaço ou canal de atendimento do vendedor.

### Opção 3 — Cotação e Entrega de "Ranchos" (Compras em Grande Quantidade / Atacarejo)
- **Descrição da ideia:** Serviço voltado a clientes que desejam fazer compras mensais ou em grande volume em mercados e atacadões com mais facilidade e melhor custo-benefício do que aplicativos como o iFood.
- **Funcionamento imaginado:** O cliente monta uma lista de produtos (genérica ou específica) e solicita orçamento aos estabelecimentos para entrega em domicílio. Os estabelecimentos podem cadastrar seus produtos para exibir o valor final já na cotação, ficando a entrega (gratuita ou paga) por conta de cada estabelecimento.

---

## 🧠 Análise Estratégica (Visão de Co-founder)

### ⚠️ Ponto de Atenção Comum: A Armadilha do Marketplace no Dia 1
Na forma idealizada (visão de longo prazo), todas as três ideias têm características de **marketplace de dois lados** (atrair clientes **e** cadastrar prestadores/estabelecimentos simultaneamente). Para um MVP, isso gera o clássico problema do *"ovo e da galinha"* e aumenta muito o esforço técnico e comercial antes mesmo de provar que o cliente realmente compra.

A saída estratégica é aplicar o modelo **Concierge / Mágico de Oz** no MVP: o cliente usa uma experiência digital simples e real, enquanto a intermediação com prestadores, distribuidoras ou mercados acontece **manualmente nos bastidores via WhatsApp**.

---

### 📊 Quadro Comparativo

| Critério | Opção 1: Prestadores em Domicílio | Opção 2: Entregas Domésticas (Água/Gás) | Opção 3: Cotação de Rancho / Atacarejo |
| :--- | :--- | :--- | :--- |
| **Força da dor** | Alta (achar profissional confiável dá trabalho) | Alta (itens indispensáveis que acabam sempre) | Muito alta (fila, peso e preço alto em apps comuns) |
| **Recorrência natural** | Baixa a média (serviços pontuais, exceto limpeza) | **Altíssima** (semanal/mensal previsível) | **Alta** (mensal/quinzenal com ticket alto) |
| **Concorrência / Diferencial** | Muito disputado (GetNinjas, Habitissimo, indicações) | Concorrência local desorganizada; diferencial na conveniência e recorrência | **Diferencial claro** frente ao iFood (foco em volume + comparação de preço) |
| **Risco no MVP** | Escopo muito variável e risco de qualidade do prestador | Margem unitária menor; precisa de combos ou assinatura | Cadastrar catálogo e preço em tempo real de vários mercados é inviável no MVP |
| **Encaixe no formato do desafio** | Médio (exige nichar bem o tipo de serviço) | **Excelente** (encaixa direto com planos, entregas e lembretes) | **Muito bom** (lista no formulário + cotação manual no WhatsApp + recompra) |

---

### 🔍 Detalhamento e Como Enxugar Cada Opção para um MVP

#### 1. Serviços em Domicílio
- **Pontos fortes:** Dor amplamente reconhecida e ticket médio interessante em serviços de reforma/acabamento.
- **Desafios iniciais:** Alta variação de orçamento (cada obra/reparo exige visita ou avaliação técnica) e dificuldade de controlar a qualidade de terceiros.
- **Versão MVP enxuta:** Em vez de um marketplace aberto para todas as categorias, nichar em **pequenos reparos residenciais ("marido de aluguel") ou limpeza avulsa/recorrente**. O cliente descreve o serviço no formulário, recebe atendimento via WhatsApp e a operação aciona manualmente uma rede fechada de 3 a 5 profissionais de confiança.

#### 2. Entregas Domésticas (Água, Gás e Essenciais)
- **Pontos fortes:** Demanda inevitável e previsível, baixa barreira para testar com vizinhos/conhecidos e aderência natural ao painel de **entregas e lembretes** (ex.: avisar antes do gás ou da água acabarem).
- **Desafios iniciais:** Margem unitária baixa em pedidos isolados; o modelo fica muito mais saudável com assinatura/recorrência ou combos residenciais (água + gás + limpeza básica).
- **Versão MVP enxuta:** O cliente monta no formulário a frequência ou kit da casa (e pode indicar quem recebe no local). O fechamento acontece via WhatsApp e o pedido é repassado manualmente a 1 ou 2 distribuidoras parceiras do bairro.

#### 3. Cotação e Entrega de Rancho (Mercados e Atacadões)
- **Pontos fortes:** Resolve uma dor muito concreta onde o iFood não entrega bom custo-benefício (compras grandes de família/mês). Tem ticket médio alto e ótimo potencial de recorrência mensal.
- **Desafios iniciais:** Manter preços atualizados de dezenas de mercados integrados no app exige integrações de ERP e acordo comercial complexo — fora de escopo para um MVP.
- **Versão MVP enxuta:** O cliente monta sua lista de rancho no formulário (escolhendo um kit-base por tamanho da família ou listando itens genéricos/específicos). A solicitação entra no painel admin; nos bastidores, o operador faz a cotação manual em 2 ou 3 mercados/atacadões locais (ou via encartes/contatos) e envia o orçamento fechado pelo WhatsApp para aprovação e agendamento da entrega.

---

## 🏁 Síntese da Recomendação Inicial

- **Opção 3 (Cotação de Rancho):** Destaca-se pela **diferenciação clara de proposta de valor** e forte apelo em portfólio, atacando um espaço mal atendido pelos aplicativos de delivery tradicionais.
- **Opção 2 (Água, Gás e Essenciais Domésticos):** Destaca-se pela **simplicidade operacional, altíssima recorrência** e encaixe imediato com o conceito de assinatura, entregas programadas e lembretes.
- **Opção 1 (Prestadores de Serviço):** Viável se for fortemente **nichada** em uma única categoria padronizável para evitar a complexidade de um marketplace generalista.

### ⏭️ Próximo Passo
Definir oficialmente **uma única ideia vencedora** para avançar para a **Etapa 2**: estimativa de mercado (**TAM, SAM e SOM**), **Business Model Canvas**, **tese do MVP** e definição explícita do que ficará **manual de propósito**.
