# PaperSlide

**Sua fábrica pessoal de apresentações** — uma aplicação web que transforma artigos científicos em PDF em apresentações de slides (`.pptx`) totalmente editáveis, por meio de um fluxo de consultoria assistida por IA.

---

## Autoria

**Pablo Gustavo Cogo Pochmann**

ORCID: [0000-0003-3944-7953](https://orcid.org/0000-0003-3944-7953)

LinkedIn: [linkedin.com/in/pablo-pochmann](https://www.linkedin.com/in/pablo-pochmann/)

Contato: pablo.pochmann@gmail.com

---

## Declaração de autoria e desenvolvimento independente

Esta obra (o software **PaperSlide**, doravante "a Obra") foi concebida e desenvolvida **por livre iniciativa pessoal do autor**, nas seguintes condições, aqui declaradas de forma expressa para fins de registro de autoria:

- Desenvolvida em **horário de folga, fora do expediente de trabalho**.
- **Sem qualquer demanda, encomenda, determinação ou orientação institucional** para a sua criação.
- Utilizando **conta pessoal** do autor nos serviços de IA empregados e **equipamento particular**, sem uso de recursos, meios, equipamentos ou infraestrutura de qualquer instituição.
- A Obra **não decorre da natureza das atribuições funcionais** do autor; trata-se de iniciativa criativa autônoma.

A eventual utilidade da Obra para contextos acadêmicos ou profissionais não altera o caráter independente e pessoal de sua criação. A presente declaração visa documentar a titularidade do autor sobre a Obra, nos termos da legislação brasileira de direitos autorais e de proteção de programas de computador (Lei nº 9.610/1998 e Lei nº 9.609/1998).

---

## O que é

O PaperSlide é uma aplicação de **arquivo único** (HTML + CSS + JavaScript, sem backend) que:

1. Recebe um ou mais artigos científicos em PDF.
2. Conduz uma análise assistida por IA do conteúdo.
3. Oferece ao usuário escolhas de refinamento (ângulo narrativo, estrutura, design).
4. Gera um arquivo `.pptx` **totalmente editável** — com layouts visuais ricos (estatísticas em destaque, cartões com ícones, fluxos de processo, tabelas, citações) e notas do orador completas.

O grande diferencial do PaperSlide é que a saída é um **PowerPoint nativo e editável**: o usuário mantém controle total sobre o resultado, podendo inserir figuras, adicionar slides e customizar todo o conteúdo — em oposição a soluções que entregam resultados fechados e não editáveis.

## Modos de trabalho

- **Rápido** — gera a apresentação completa em uma única etapa; consumo mínimo de IA, adequado a contas gratuitas.
- **Completo** — consultoria em cinco fases (Briefing → Evidências → Estrutura → Design Visual → Geração) com escolhas do usuário em cada etapa.

## Como usar

1. Abra o arquivo `paperslide-artifact.html` no link (https://pochmannbr.github.io/paperslide/paperslide-artifact.html).
2. Carregue um ou mais PDFs de artigos científicos.
3. Preencha o briefing (evento, público, duração, idioma).
4. Escolha o modo de trabalho.
5. Conduza o refinamento e, ao final, baixe o arquivo `.pptx`.

> A versão em artefato do Claude utiliza a conta Claude de quem a abre, sem necessidade de chave de API. Há também uma variante hospedável que utiliza chave de API própria do operador.

## Tecnologias

- HTML, CSS e JavaScript (sem dependências de build).
- [PptxGenJS](https://gitbrent.github.io/PptxGenJS/) para geração do `.pptx` no navegador.
- API de modelos de linguagem da Anthropic (Claude) para a análise e a geração de conteúdo.

## Citação

Se utilizar ou referenciar esta Obra, por favor cite:

> POCHMANN, P. G. C. *PaperSlide: Sua fábrica pessoal de apresentações.* 2026. Software. DOI: [a ser preenchido após o registro no Zenodo].

(O DOI será gerado automaticamente ao publicar uma *release* conectada ao Zenodo. Após o registro, substitua o marcador acima pelo DOI emitido.)

## Licença

Distribuído sob a licença **Creative Commons Atribuição–NãoComercial 4.0 Internacional (CC BY-NC 4.0)**. Consulte o arquivo [`LICENSE`](LICENSE) para os termos completos.

Em resumo: o uso, a cópia e a modificação (remix) são permitidos para **fins não comerciais**, desde que mantida a **atribuição ao autor original**. Para uso comercial, contate o autor.

---

*PaperSlide © 2026 Pablo Gustavo Cogo Pochmann. Todos os direitos reservados nos termos da licença acima.*
