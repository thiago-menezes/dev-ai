# Solução: Plataforma “Ateliê Inteligente”

## Conceito
Marketplace de encomendas personalizadas de crochê que guia o cliente desde o briefing inspirado por fotos até a peça entregue. A plataforma divide a experiência em três camadas: vitrine inspiracional, fluxo inteligente de pedido e cockpit de produção para artesãs.

## Paleta e Ambientes
- **Terracota Principal** `#CB6A3B`: aplicada a botões primários, ícones de ação e destaques de títulos.
- **Terracota Profunda** `#A64F24`: usada em estados ativos/hover e cards premium de artesãs.
- **Verde Pistache** `#9ED47C`: cor de feedback positivo, barras de progresso e badges de sustentabilidade.
- **Neutro Claro** `#F9F5EF`: fundo predominante, garantindo aspecto artesanal/minimal.
- **Cinza Areia** `#D9CEC2`: divisórias, contornos suaves e textos auxiliares.

Manter proporção aproximada de 60% fundo claro, 25% terracotas, 10% pistache e 5% cinzas para equilíbrio visual.

## Fluxo do Usuário (Cliente)
1. **Entrada Inspiracional**: grid com fotos de peças, filtros por ocasião/estilo e CTA “Briefing Guiado”.
2. **Briefing com IA**:
   - upload de foto ou texto;
   - perguntas sequenciais (medidas, preferências de fio/cor);
   - IA gera resumo visual (wirecard + paleta sugerida) e estimativa inicial.
3. **Match de Artesãs**: cards com foto, estilo, SLA médio, avaliações e botão “Convidar”.
4. **Checkout Seguro**: divisão do pagamento (entrada + saldo), contrato simplificado e cronograma.
5. **Acompanhamento**: timeline com marcos (“Início”, “Costura”, “Acabamento”, “Envio”) e mensagens automatizadas.

## Fluxo do Usuário (Artesã)
1. **Painel de Demandas**: cards com pedidos abertos + status; filtros por data e complexidade.
2. **Workspace**: cada pedido possui checklist, cálculo automático de fios e sugestão de preço/tempo baseada em histórico.
3. **Estoque e Insumos**: módulo opcional para lançar materiais e alertas de reposição.
4. **Comunicação**: chat centralizado com templates gerados via IA (agradecimento, solicitação de medida, envio).

## Diretrizes de Interface
- **Tipografia**: títulos em uma serif elegante (ex: Playfair Display) destacando o toque artesanal; corpo em sans humanista (ex: Work Sans) para legibilidade.
- **Cards**: bordas de 8px, sombras suaves com cor `rgba(166,79,36,0.15)` para manter a sensação tátil.
- **Fotografia**: fundo neutro ou tecidos; aplicar overlays terracota 15% nos banners para unir o set.
- **Componentes Chave**:
  - **Card de Artesã**: avatar redondo, selo pistache “Top Seller” e botão terracota com ícone de agulha.
  - **Timeline**: círculos pistache preenchidos para etapas concluídas, outlines terracota para próximas.
  - **Painel de IA**: bloco lateral com título pistache e destaque terracota no CTA “Aplicar sugestão”.

## Entregáveis Visuais Requeridos
- **Landing page** com hero dividido (foto macro de crochê + copy), seção “Como funciona”, depoimentos e CTA primário terracota.
- **Tela Briefing** (desktop + mobile) mostrando o wizard e o resumo gerado pela IA.
- **Dashboard da Artesã** com três estados: sem pedidos, pedido em andamento e entrega concluída.
- **Sistema de ícones** minimalistas (agulha, linha, fita métrica, carrinho) alinhados à paleta.

## Experiências Dinâmicas
- Microinterações em pistache para confirmar ações (ex: check-in de etapa).
- Badge terracota pulsante para novas mensagens.
- Skeleton screens em tons areia para carregamentos.

## Resultado Esperado
Uma interface que transmite carinho artesanal com confiabilidade tecnológica, reduz o atrito na comunicação e deixa claro, visualmente, em que etapa cada peça está. O designer deve equilibrar textura e minimalismo, usando os tons terracota e verde pistache como assinatura da marca.
