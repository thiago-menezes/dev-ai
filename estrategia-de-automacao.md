# Estratégia de Automação

## Objetivo

Automatizar processos repetitivos do negócio para economizar tempo e escalar vendas sem aumentar proporcionalmente o trabalho manual.

---

## Áreas de Automação

### 1. Automação de Marketing

#### 1.1 Captura e Nutrição de Leads

**Fluxo Automatizado:**
```
Visitante → Landing Page → Formulário →
Email de Boas-Vindas (imediato) →
Entrega do Ebook (link de download) →
Sequência de 5-7 emails (próximos 10 dias) →
Oferta do Curso
```

**Ferramentas:**
- **ActiveCampaign** (recomendado - automações avançadas)
- **Mailchimp** (mais simples, grátis até 500 contatos)
- **ConvertKit** (focado em criadores)

**Sequência de Emails Automatizada:**

**Email 1 - Imediato (Boas-vindas + Ebook)**
- Assunto: "Seu ebook está aqui 📚"
- Conteúdo: Agradecimento + link download + apresentação rápida

**Email 2 - Dia 2 (Valor + Dica)**
- Assunto: "Já experimentou a Forma #1 do ebook?"
- Conteúdo: Aprofundar sobre commits com IA + link para vídeo no YouTube

**Email 3 - Dia 4 (História pessoal)**
- Assunto: "Como IA mudou minha forma de programar"
- Conteúdo: História de Thiago ou Rodolfo + resultados concretos

**Email 4 - Dia 6 (Social proof)**
- Assunto: "Veja o que desenvolvedores estão fazendo com IA"
- Conteúdo: Casos de uso, depoimentos, resultados

**Email 5 - Dia 8 (Antecipação)**
- Assunto: "Algo grande vem aí..."
- Conteúdo: Teaser do curso, o que vai aprender, quando lança

**Email 6 - Dia 10 (Oferta)**
- Assunto: "Portas abertas: [Nome do Curso]"
- Conteúdo: Apresentação completa, benefícios, oferta, CTA

**Email 7 - Dia 12 (Urgência)**
- Assunto: "Últimas horas para garantir [benefício]"
- Conteúdo: Reforçar oferta, adicionar urgência (desconto acaba, vagas limitadas)

---

#### 1.2 Agendamento de Posts em Redes Sociais

**Processo Manual (sem automação):**
- Criar post → Publicar → Repetir para cada rede → Demora horas por semana

**Processo Automatizado:**
- Criar 30 posts de uma vez → Agendar em todas as redes → Plataforma publica automaticamente

**Ferramentas:**
- **Buffer** (simples, interface limpa)
- **Later** (bom para Instagram)
- **Metricool** (completo, analytics)
- **Hootsuite** (corporativo, mais caro)

**Fluxo:**
1. Criar banco de 30 posts no Notion/Google Sheets
2. Preparar imagens no Canva
3. Agendar tudo em 1-2h (segunda de manhã)
4. Posts saem automaticamente durante o mês

**Benefícios:**
- Consistência (posts todo dia)
- Economia de tempo (faz tudo de uma vez)
- Melhor planejamento

---

#### 1.3 Retargeting Automatizado

**Conceito:** Mostrar anúncios para pessoas que já visitaram a landing page mas não compraram.

**Configuração:**
1. Instalar Facebook Pixel na landing page
2. Criar público personalizado: "Visitou landing mas não comprou"
3. Criar campanha de retargeting com oferta especial
4. Anúncios aparecem automaticamente para esse público

**Automação:**
- Visitou página → Não comprou em 24h → Anúncio 1 (lembrete)
- Visitou página → Não comprou em 3 dias → Anúncio 2 (desconto 10%)
- Visitou página → Não comprou em 7 dias → Anúncio 3 (último aviso)

**Ferramentas:**
- Facebook Ads Manager (pixel + públicos personalizados)
- Google Ads (remarketing tag)

---

### 2. Automação de Vendas

#### 2.1 Checkout e Pagamento

**Fluxo Automatizado:**
```
Clique em "Comprar" →
Página de checkout (plataforma) →
Preenche dados →
Pagamento processado automaticamente →
Email de confirmação (imediato) →
Acesso ao curso liberado (imediato) →
Email com login e senha
```

**Plataforma faz tudo:**
- Processa cartão de crédito
- Gera boleto
- Libera acesso
- Envia emails transacionais

**Ferramentas (Plataformas de Curso):**
- **Kiwify**
- **Hotmart**
- **Plataforma de alta credibilidade** (a pesquisar)

**Importante:** Integração com plataforma de email (via Zapier/webhooks) para adicionar comprador em lista separada.

---

#### 2.2 Upsell/Cross-sell Automatizado

**Depois da Compra:**
- Cliente compra curso → Página de "Obrigado" →
  - Oferta adicional (One-Time Offer): "Quer mentoria 1-on-1 por mais R$497?" (30% convertem)

**Durante o Curso:**
- Cliente completa 50% → Email automático:
  - "Parabéns! Quer acelerar ainda mais? [Módulo avançado ou consultoria]"

**Ferramentas:**
- Plataforma de curso (se suportar)
- ActiveCampaign (automação baseada em tags/eventos)
- Zapier (conectar plataforma com email)

---

#### 2.3 Recuperação de Carrinho Abandonado

**Problema:** Pessoa adiciona ao carrinho mas não finaliza compra.

**Solução Automatizada:**
```
Abandono do carrinho →
Email 1 (1h depois): "Esqueceu algo?" →
Email 2 (24h depois): "Ainda interessado? Aqui está 10% de desconto" →
Email 3 (3 dias depois): "Última chance - desconto expira hoje"
```

**Taxa de recuperação típica:** 15-30%

**Ferramentas:**
- Kiwify/Hotmart (têm isso nativo)
- ActiveCampaign (se checkout próprio)

---

### 3. Automação de Conteúdo

#### 3.1 Geração de Conteúdo com IA

**Processo:**
1. **Input:** Tópico + estilo + público-alvo
2. **IA gera:** Post completo (LinkedIn, Instagram, Twitter)
3. **Revisão rápida:** Ajustar tom e adicionar toque pessoal
4. **Agendar:** Via Buffer/Later

**Ferramentas:**
- ChatGPT (com prompts estruturados)
- Claude
- Copy.ai (específico para marketing)
- Jasper (pago, focado em copy)

**Exemplo de prompt:**
```
Crie um post para LinkedIn sobre "Como usar IA para fazer commits profissionais".

Público: Desenvolvedores júnior
Tom: Educativo, amigável, sem jargões
Formato: Hook + explicação + exemplo + CTA
Tamanho: 150-200 palavras
```

---

#### 3.2 Reaproveitamento de Conteúdo

**1 Aula em Vídeo →:**
- Transcrição (via Rev.com ou Descript)
- Post no blog (artigo baseado na transcrição)
- 5 posts para LinkedIn (principais pontos)
- 10 tweets (quotes + dicas)
- 3 carrosseis Instagram
- 2 Reels (cortes de 30s)

**Ferramentas de Automação:**
- **Descript**: Transcrição + edição de vídeo
- **OpusClip**: Corta vídeos longos em shorts virais automaticamente
- **Repurpose.io**: Publica 1 vídeo em múltiplas plataformas

---

### 4. Automação de Suporte

#### 4.1 Chatbot para Dúvidas Frequentes

**Onde:** Landing page, área de membros

**Função:**
- Responder perguntas comuns (preço, duração, requisitos)
- Coletar lead (email) se não souber responder
- Direcionar para suporte humano se necessário

**Ferramentas:**
- **Manychat** (focado em redes sociais)
- **MobileMonkey**
- **Intercom** (completo, mas caro)
- **Tidio** (bom custo-benefício)

**FAQ Automatizada:**
- "Quanto custa?" → Bot responde com preço
- "Posso parcelar?" → Bot responde "Sim, 12x no cartão"
- "Tem certificado?" → Bot responde "Sim, após conclusão"

---

#### 4.2 Tickets de Suporte Automatizados

**Sistema:**
- Aluno envia dúvida (email ou formulário)
- Sistema cria ticket automaticamente
- Categoriza (técnico, pagamento, acesso)
- Direciona para pessoa certa
- Aluno recebe confirmação automática

**Ferramentas:**
- **Zendesk** (completo)
- **Freshdesk** (tem free tier)
- **Help Scout** (simples e eficiente)
- **Discord** (comunidade + bots)

---

#### 4.3 Base de Conhecimento (FAQ)

**Automação:**
- Aluno faz pergunta → Sistema sugere artigos relacionados automaticamente
- Reduz 50-70% dos tickets

**Ferramenta:**
- Notion (público, grátis, fácil)
- Help Scout Docs
- GitBook

---

### 5. Automação Financeira

#### 5.1 Reconciliação de Vendas

**Automação:**
- Venda é feita → Plataforma registra
- Dados vão automaticamente para planilha (Google Sheets) via Zapier
- Atualiza dashboard de receita em tempo real

**Ferramentas:**
- Zapier: Kiwify → Google Sheets
- Google Data Studio: Dashboard visual
- Conta Azul / Omie (contabilidade)

---

#### 5.2 Emissão de Notas Fiscais

**Manual:** Emitir NF para cada venda = horas por semana

**Automatizado:**
- Venda confirmada → Sistema emite NF automaticamente → Envia por email

**Ferramentas:**
- **Nuvem Shop** (integrações)
- **eNotas**
- **NFE.io**

---

### 6. Automação de Onboarding de Alunos

#### Fluxo Automatizado Pós-Compra

**Email 1 - Imediato (Boas-vindas)**
```
Assunto: Bem-vindo ao [Nome do Curso]! 🎉

Conteúdo:
- Acesso ao curso: [link]
- Login: [email]
- Senha: [gerada ou instruções]
- Primeiros passos: assista ao vídeo de boas-vindas
- Junte-se à comunidade: [link Discord]
```

**Email 2 - Dia 1 (Motivação + Primeira Aula)**
```
Assunto: Pronto para começar? Aqui está sua primeira missão

Conteúdo:
- Como aproveitar melhor o curso
- Assista ao Módulo 1 hoje
- Dica: não pule etapas!
```

**Email 3 - Dia 3 (Checkpoint)**
```
Assunto: Como você está? Alguma dúvida?

Conteúdo:
- Verificar progresso
- Oferecer ajuda
- Link para suporte/comunidade
```

**Email 4 - Dia 7 (Engajamento)**
```
Assunto: Você já está em 20% do curso? 🚀

Conteúdo:
- Progresso esperado
- Incentivo
- Próximas aulas
```

**Emails periódicos:** A cada 2 semanas, check-in automático.

---

### 7. Automação de Comunidade

#### Discord com Bots

**Automações:**
1. **Novo aluno** → Bot dá boas-vindas + atribui role "Aluno"
2. **Aluno completa módulo** → Bot comemora + atribui badge
3. **Pergunta no canal** → Bot sugere threads relacionadas
4. **Inatividade de 7 dias** → Bot envia DM: "Sentimos sua falta!"

**Bots úteis:**
- **MEE6** (boas-vindas, níveis, moderação)
- **Dyno** (moderação automática)
- **Carl-bot** (reaction roles, auto-responder)

---

### 8. Automação de Analytics

#### Dashboards Automáticos

**Métricas Importantes:**
- Vendas diárias / semanais / mensais
- Número de leads capturados
- Taxa de conversão (landing page)
- Engajamento em redes sociais
- Progresso médio dos alunos
- NPS (satisfação)

**Ferramenta:**
- **Google Data Studio** (grátis, conecta com tudo)
  - Integra: Google Analytics + Facebook Ads + Planilhas + Plataforma de curso

**Atualização:** Automática, em tempo real

**Benefício:** Ver métricas de relance, tomar decisões rápidas

---

### 9. Automação de Feedback

#### Coleta Automática de Avaliações

**Trigger:** Aluno completa 100% do curso

**Automação:**
```
Conclusão do curso →
Email automático (1 dia depois):
"Parabéns! O que achou do curso?" →
Link para formulário (Typeform / Google Forms) →
Se nota >= 9: Pede depoimento em vídeo / texto →
Se nota < 7: Pede sugestões de melhoria
```

**Ferramentas:**
- Typeform (formulários bonitos)
- Google Forms (grátis)
- NPS automatizado (Delighted, SurveyMonkey)

---

### 10. Automação de Afiliados

#### Programa de Afiliados Automatizado

**Fluxo:**
1. Influencer se cadastra
2. Recebe link de afiliado automaticamente
3. A cada venda, sistema calcula comissão
4. Pagamento automático todo dia 10 (Stripe, PayPal)

**Plataforma:**
- Kiwify/Hotmart (já incluem programa de afiliados nativo)
- Rewardful (se plataforma própria)
- FirstPromoter

**Automação de Materiais:**
- Afiliado se cadastra → Recebe kit de marketing automaticamente (banners, textos, vídeos)

---

## Stack de Ferramentas Recomendadas

### Essenciais (Início)
1. **Email Marketing**: ActiveCampaign ou Mailchimp
2. **Landing Page**: Framer ou Next.js
3. **Agendamento Social**: Buffer
4. **Plataforma Curso**: Kiwify ou alternativa
5. **Automação**: Zapier (conecta tudo)

### Intermediárias (Crescimento)
6. **CRM**: HubSpot (free tier)
7. **Analytics**: Google Data Studio
8. **Suporte**: Freshdesk
9. **Comunidade**: Discord + bots

### Avançadas (Escala)
10. **CDP**: Segment (centraliza dados)
11. **A/B Testing**: Google Optimize
12. **Personalização**: Dynamic Yield

---

## Zapier: O Hub de Automação

### Integrações ("Zaps") Úteis

**1. Nova venda → Adicionar em planilha**
- Trigger: Kiwify - Nova venda
- Action: Google Sheets - Add row

**2. Novo lead → Enviar para email marketing**
- Trigger: Landing page (Typeform/Webflow)
- Action: ActiveCampaign - Add contact

**3. Conclusão de curso → Enviar NPS**
- Trigger: Plataforma - Curso 100%
- Action: Typeform - Send form

**4. Abandono de carrinho → Notificar**
- Trigger: Kiwify - Checkout abandonado
- Action: Email - Enviar sequência

**5. Novo aluno → Adicionar no Discord**
- Trigger: Kiwify - Nova venda
- Action: Discord - Add role

---

## Cronograma de Implementação

### Mês 1 (Novembro)
- [ ] Configurar email marketing (ActiveCampaign)
- [ ] Criar sequência de boas-vindas (ebook)
- [ ] Instalar Facebook Pixel
- [ ] Configurar agendamento de posts (Buffer)

### Mês 2 (Dezembro)
- [ ] Criar sequência de vendas (7 emails)
- [ ] Configurar retargeting
- [ ] Automatizar onboarding pós-compra
- [ ] Criar 3 Zaps essenciais

### Mês 3 (Janeiro)
- [ ] Chatbot na landing page
- [ ] Dashboard de analytics
- [ ] Automação de feedback/NPS
- [ ] Programa de afiliados

---

## ROI de Automação

### Tempo Economizado (Estimativa Mensal)

| Tarefa | Manual | Automatizado | Economia |
|--------|--------|--------------|----------|
| Enviar emails para leads | 10h | 0.5h | 9.5h |
| Postar em redes sociais | 15h | 2h | 13h |
| Processar vendas | 5h | 0h | 5h |
| Suporte (FAQ) | 20h | 8h | 12h |
| Onboarding de alunos | 8h | 1h | 7h |
| Emitir NFs | 4h | 0h | 4h |
| **TOTAL** | **62h** | **11.5h** | **50.5h/mês** |

**Economia anual:** ~600 horas = 25 dias de trabalho

---

## Checklist de Automação

### Antes do Lançamento
- [ ] Email marketing configurado
- [ ] Sequência de nurturing criada
- [ ] Landing page com captura de email
- [ ] Pixel de rastreamento instalado
- [ ] Agendamento de posts configurado

### Pós-Lançamento
- [ ] Onboarding automatizado
- [ ] Suporte com FAQ/chatbot
- [ ] Retargeting ativo
- [ ] Recuperação de carrinho
- [ ] Dashboard de métricas

### Crescimento
- [ ] Programa de afiliados
- [ ] Upsell/cross-sell
- [ ] NPS automatizado
- [ ] Comunidade com bots

---

**Última atualização**: 8 de Novembro de 2025
