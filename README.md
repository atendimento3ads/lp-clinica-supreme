# LP · Clínica Supreme (geral)

Protótipo visual da landing page geral da Clínica Supreme (Goiânia). Tarefa no 3ADS Flow: **[CLÍNICA SUPREME] LP GERAL**.

- **Preview:** https://atendimento3ads.github.io/lp-clinica-supreme/
- **Status:** protótipo para validação interna. Sem integração de formulário, planilha, WhatsApp automático ou mensuração.
- **Página:** `index.html` (HTML + CSS + JS em arquivo único, sem framework). Imagens em `images/`.

## Fontes do conteúdo

| Insumo | Origem |
|---|---|
| Copy | Google Docs "LP \| Clínica Supreme" (Drive da clínica › LP-Artigos-Extras › LP), usada literalmente |
| Hierarquia e regras de conteúdo | Subtarefa "Briefing copy: conteúdo e hierarquia de comunicação" |
| Navegação, CTAs e mobile | Subtarefa "Briefing: experiência visual + caminhos de navegação" |
| Perguntas e regras do formulário | Subtarefa "Briefing desenvolvimento de formulário + integrações" |
| Identidade e fotos | PDF institucional "SUPREME CLINIC.pdf" e LP Full Body Experience (repo `lp-full-body-experience`) |
| Referências externas | clinicarenascenza.com · drluizeduardoramos.atemdigital.com.br |

## Identidade aplicada

- Dourado oficial do logo `#A77F1F` (extraído do PDF). Para texto sobre fundo claro usa-se `#7A5C16` (contraste AA).
- Fundos: preto quente `#15120F`, papel `#F8F5F0`, papel 2 `#F1ECE3`.
- Tipografia: Playfair Display (títulos, itálico nas palavras de destaque) + Poppins (corpo e interface), as mesmas da LP Full Body.

## Formulário (protótipo)

Fluxo de 5 perguntas + contato, uma por vez, com progresso, voltar sem perder respostas, área visível e editável,
6 caminhos condicionados à área, campo de cidade/UF para "Outra cidade", máscara e validação de WhatsApp com DDD,
consentimento desmarcado, estado de envio e tela de confirmação com "Continuar no WhatsApp".

- CTAs de área (`data-area="derm|tec|nutri|cir|care"`) preenchem a área e começam na pergunta 2. CTA geral começa na pergunta 1.
- `?simular=erro` na URL mostra o estado de falha de gravação (dados preservados + "Tentar novamente").

## Pendências antes da publicação

Marcadas na página em laranja/itálico:

1. CRM, RQE, títulos e informação sobre mentoria dos dois médicos (observação em vermelho na copy).
2. Responsável técnico, CRM/RQE, CNPJ e demais informações legais do rodapé.
3. Link da Política de Privacidade e texto do consentimento (validação da clínica).
4. Horário de atendimento (o briefing pede horários acessíveis sem formulário; não veio na copy).
5. Autorização de uso das fotos (todas vieram do PDF institucional da clínica).
6. Definição do Natural Lift, estrutura cirúrgica e condições do Supreme Care (briefing pede confirmação da clínica).

Desenvolvido por **3ADS**.
