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

### Dimensionamento de mercado

TAM, SAM e SOM ainda precisam ser calculados com fontes e premissas documentadas. O próximo passo é definir o perfil de instituição atendível, estimar o número de clientes potenciais e validar um ticket de assinatura. Este README não apresenta números sem fonte ou validação.

## Uso de inteligência artificial

O ChatGPT foi usado como apoio na estruturação da ideia, da hipótese e das instruções de construção. O Lovable foi usado para criar e publicar o MVP. No produto, a IA é apresentada como apoio operacional; decisões clínicas e nutricionais permanecem com profissionais.

## Limites e próximos passos

- testar o fluxo completo com usuários;
- validar o contato comercial e a conversão de lead em cliente;
- entrevistar instituições do público-alvo;
- pesquisar fontes e premissas para TAM, SAM e SOM;
- revisar segurança e configuração antes de qualquer uso com dados reais;
- organizar o código-fonte em arquivos navegáveis no repositório.

> A demonstração é um MVP e deve usar apenas dados fictícios. Não insira informações reais de pacientes.

## Repositório

O código exportado está disponível em [nutrileito.zip](./nutrileito.zip). A aplicação publicada pode ser acessada em [nutrileito.lovable.app](https://nutrileito.lovable.app).
