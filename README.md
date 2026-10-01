# NutriLeito

**Gestão e rastreabilidade do fluxo de refeições hospitalares.**

O NutriLeito é um MVP de uma plataforma digital para organizar e acompanhar as etapas entre o pedido de refeição do paciente e a entrega no leito. Este projeto foi desenvolvido como parte do desafio da trilha Santander na DIO, usando ferramentas de inteligência artificial para transformar uma hipótese de negócio em um produto demonstrável.

- **Aplicação publicada:** [nutrileito.lovable.app](https://nutrileito.lovable.app)
- **Código-fonte exportado:** [nutrileito.zip](./nutrileito.zip)

## O problema

O fluxo de alimentação hospitalar envolve diferentes equipes. Quando pedidos, restrições alimentares, preparo, conferência e entrega são acompanhados por canais separados, podem surgir falhas de comunicação e dificuldade para saber em que etapa cada refeição está.

O projeto propõe centralizar essas informações e dar mais visibilidade ao andamento de cada pedido.

## Hipótese de negócio

Hospitais e instituições de saúde podem ter interesse em uma solução que centralize e rastreie o fluxo de refeições, ajude as equipes a acompanhar cada etapa e reduza falhas de comunicação.

Essa hipótese ainda precisa ser validada com profissionais e instituições do público-alvo.

## Como funciona

O fluxo pensado para o produto é:

1. O paciente informa à Enfermagem o que gostaria de comer.
2. A Enfermagem registra o pedido.
3. A Nutrição avalia o pedido considerando a dieta e as restrições registradas.
4. Após a liberação da Nutrição, a Cozinha prepara a refeição.
5. A Nutrição faz a conferência final.
6. A equipe de entrega leva a refeição ao leito e registra a conclusão.

O paciente não cria diretamente o pedido no sistema. A avaliação nutricional continua sob responsabilidade dos profissionais.

## O MVP

A versão demonstrativa reúne uma página de apresentação comercial e um painel para visualizar o fluxo operacional. Entre os elementos previstos no produto estão:

- solicitação de demonstração para potenciais clientes;
- acompanhamento dos pedidos por etapa;
- áreas de trabalho para Enfermagem, Nutrição, Cozinha, Conferência e Entrega;
- indicadores operacionais, histórico e auditoria;
- apoio de IA para consulta, sem tomar decisões clínicas;
- dados fictícios no ambiente de demonstração.

O funcionamento completo de cada fluxo deve ser testado antes de tratar esses itens como validados em uso real.

## Modelo de negócio — hipótese

O modelo a investigar é SaaS B2B para hospitais e instituições de saúde. A aquisição começaria com apresentação do produto e solicitação de demonstração. O contato comercial, a negociação e eventual pagamento podem ser conduzidos manualmente no início.

| Elemento | Hipótese inicial |
|---|---|
| Clientes | Hospitais e instituições de saúde |
| Proposta de valor | Centralizar e rastrear as etapas do fluxo de refeições |
| Canais | Página do produto, demonstrações e contato comercial direto |
| Relacionamento | Apresentação consultiva e acompanhamento comercial |
| Receita | Assinatura do sistema, a validar com potenciais clientes |
| Recursos e atividades | Produto digital, manutenção, suporte e evolução do fluxo |
| Custos | Desenvolvimento, infraestrutura, suporte e aquisição de clientes |
| Parceiros | A identificar durante a validação |

## Dimensionamento de mercado (TAM, SAM e SOM)

O cálculo abaixo é uma estimativa inicial em número de hospitais e receita recorrente potencial. A base usa hospitais gerais e especializados cadastrados no CNES; não inclui hospitais-dia isolados.

| Mercado | Definição usada | Hospitais | Receita anual ilustrativa* |
|---|---|---:|---:|
| **TAM** | Todos os hospitais gerais e especializados no Brasil | 6.468 | R$ 77,6 milhões |
| **SAM** | Hospitais nos sete estados que concentram cerca de 59% do total: SP, MG, BA, RJ, GO, PR e RS | 3.816 | R$ 45,8 milhões |
| **SOM** | Meta hipotética de alcançar 1% do SAM nos primeiros três anos | 38 | R$ 456 mil |

**Fonte e recorte:** o TCU, com dados do CNES de julho de 2024, identificou 6.468 hospitais gerais e especializados no Brasil e cerca de 59% deles nos sete estados indicados. [Relatório do TCU sobre hospitais gerais e especializados (dados do CNES, julho de 2024)](https://pesquisa.apps.tcu.gov.br/doc/acordao-completo/738/2025/Plen%C3%A1rio).

**Premissas próprias do cenário:** preço hipotético de **R$ 1.000 por hospital ao mês** (R$ 12.000 ao ano); SAM calculado como 59% de 6.468 (aproximadamente 3.816 hospitais); SOM calculado como 1% de 3.816 (aproximadamente 38 hospitais). As receitas são clientes × R$ 12.000 por ano.

Esses valores **não são previsão de vendas nem preço validado**. São um cenário para dimensionar a hipótese. O preço, a disposição a pagar, os critérios de compra e a capacidade real de atendimento precisam ser testados com hospitais. O SOM é uma meta inicial de penetração, não uma participação já conquistada.

## Uso de inteligência artificial

O ChatGPT foi usado como apoio na estruturação da ideia, da hipótese e das instruções de construção. O Lovable foi usado para criar e publicar o MVP. No produto, a IA é apresentada como apoio operacional; decisões clínicas e nutricionais permanecem com profissionais.

## Limites e próximos passos

- testar o fluxo completo com usuários;
- validar o contato comercial e a conversão de lead em cliente;
- entrevistar instituições do público-alvo e testar a hipótese de preço;
- revisar segurança e configuração antes de qualquer uso com dados reais;
- organizar o código-fonte em arquivos navegáveis no repositório.

> A demonstração é um MVP e deve usar apenas dados fictícios. Não insira informações reais de pacientes.

## Repositório

O código exportado está disponível em [nutrileito.zip](./nutrileito.zip). A aplicação publicada pode ser acessada em [nutrileito.lovable.app](https://nutrileito.lovable.app).
