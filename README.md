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


## Business Model Canvas (hipóteses)

| Bloco | Hipótese inicial |
|---|---|
| Segmentos de clientes | Hospitais gerais e especializados, públicos ou privados, com operação de refeições para pacientes internados.
| Proposta de valor | Centralizar pedidos e dar rastreabilidade às etapas entre Enfermagem, Nutrição, Cozinha e Entrega.
| Canais | Landing page, solicitação de demonstração e contato comercial direto.
| Relacionamento | Demonstração consultiva, implantação assistida e suporte.
| Fontes de receita | Assinatura SaaS por instituição; preço ainda não validado.
| Recursos-chave | Aplicação web, infraestrutura em nuvem, equipe de produto e conhecimento dos fluxos hospitalares.
| Atividades-chave | Desenvolver e manter o produto, apoiar a implantação e evoluir o fluxo.
| Parcerias-chave | A identificar com hospitais, profissionais de nutrição hospitalar e fornecedores de tecnologia.
| Estrutura de custos | Desenvolvimento, nuvem, suporte, segurança e aquisição de clientes. |

## Mega prompt e ajustes solicitados

O prompt de construção foi preparado no ChatGPT e enviado ao Lovable como **“NUTRILEITO — MVP”** (28/09). A especificação pediu um MVP web responsivo e demonstrável para gestão do fluxo de refeições hospitalares. O fluxo obrigatório é Paciente → Enfermagem → Nutrição → Cozinha → Nutrição (conferência final) → Entrega → Leito. O paciente não abre pedidos diretamente; profissionais fazem a avaliação nutricional; a aplicação deve priorizar dados fictícios, perfis de trabalho, rastreabilidade, histórico e apoio de IA sem decisões clínicas.

Depois, foi enviado ao Lovable o ajuste **“AJUSTE DE ESCOPO — MODELO DE NEGÓCIO E MVP”** para alinhar o produto ao desafio: landing page B2B, formulário para captar leads interessados em demonstração (não pedidos de refeição), e venda manual. O ajuste especifica campos do contato, confirmação ao enviar, ausência de checkout e apresentação do fluxo comercial.

Foi preparado ainda o prompt **“AJUSTE COMERCIAL — WHATSAPP PARA FECHAMENTO DA VENDA”**. Ele solicita botão para conversar pelo WhatsApp com mensagem pré-preenchida, etapas do lead até cliente e conversão reaproveitando os dados. **Esse último ajuste está anexado no chat do Lovable, mas não foi enviado/aplicado:** a tentativa foi bloqueada por falta de créditos. Assim, WhatsApp comercial e conversão de lead não são declarados como funcionalidades concluídas. Nenhum plano ou crédito pago foi adquirido.

## Testes e evidências

- A landing page publicada abriu sem autenticação em 01/10/2026 e apresenta a proposta, o fluxo e a solicitação de demonstração.
- A prévia do painel exibe tela de acesso à demonstração e orienta o uso de dados fictícios. O fluxo autenticado completo ainda não foi validado nesta entrega.
- Não foi realizado teste com hospitais ou usuários reais; não houve envio do formulário de lead.
- A revisão de segurança do Lovable ainda precisa ser executada e conferida. A mensagem do Lovable informa uma atualização rotineira de dependências, mas isso não equivale a uma revisão de segurança.
- A origem foi exportada como `nutrileito.zip`; a listagem do GitHub contém esse pacote e este README. Para facilitar a avaliação, recomenda-se extrair os arquivos fonte na raiz ou numa pasta `src/` em um próximo commit.
- Capturas de tela da landing page e do painel ainda precisam ser anexadas ao repositório.

## Checklist antes da submissão

- [x] Repositório público na conta do autor, com nome legível.
- [x] Aplicação publicada e landing page acessível pelo endereço acima.
- [x] README com problema, hipótese, mercado, Canvas e documentação dos prompts/ajustes.
- [ ] Validar o fluxo autenticado do painel com dados fictícios.
- [ ] Executar e registrar a revisão de segurança do Lovable.
- [ ] Anexar capturas de tela da aplicação e do painel.
- [ ] Extrair o ZIP para que os arquivos fonte fiquem navegáveis pelo GitHub.
- [ ] Validar a hipótese com pelo menos uma pessoa do público-alvo.

> Não usar dados reais de pacientes na demonstração. Os números TAM/SAM/SOM e o preço são estimativas, não validação de mercado.


## Resultado da revisão de segurança (01/10/2026)

A revisão aprofundada gratuita do Lovable concluiu sem apontar problemas específicos na lógica, permissões ou dados do aplicativo. O Lovable também informa que a verificação de dependências encontrou **2 alertas altos** no pacote `@tanstack/react-start` versão `1.168.60` (53 pacotes analisados). A correção automática foi bloqueada porque a conta está sem créditos e exige recarga; portanto, os alertas continuam pendentes e o resultado não deve ser entendido como aprovação de segurança. Não usar dados reais de pacientes.

Atualização do checklist: a revisão foi executada; falta resolver e revalidar os dois alertas de dependências.
