# 🤝 Acordo de Cooperação Técnica

## 📌 Definição:
Instrumento de cooperação para a execução de ações de interesse recíproco e em regime de mútua colaboração, a título gratuito, sem transferência de recursos ou doação de bens, no qual o objeto e as condições da cooperação são ajustados de comum acordo entre as partes.

**Atenção!** Acordos de Cooperação Técnica (ACTs) só poderão ser celebrados entre órgãos públicos (de qualquer esfera - municipal, estadual e federal), consórcios públicos ou serviços sociais autônomos estabelecidos por lei (SSAs, como o [Servas](https://www.almg.gov.br/legislacao-mineira/texto/LEI/22607/2017/?cons=1), por exemplo).

## 🏛️ Regulamentação:
Capítulo III - Das Parcerias sem Transferências de Recursos - do [Decreto Federal nº 11.531/2023](https://www.planalto.gov.br/ccivil_03/_ato2023-2026/2023/decreto/d11531.htm).

## 🎯 Objetivos
- Executar políticas públicas de interesse recíproco em mútua colaboração.
- Potencializar capacidades institucionais através da cooperação técnica.
- Facilitar parcerias sem necessidade de repasse de recursos.
- Promover sinergia entre diferentes esferas da administração pública.
- Fomentar iniciativas baseadas em colaboração técnica e operacional.

## 🛠️ Ideias para aplicação no Iepha-MG:
Desde que haja interesse mútuo e viabilidade técnica, um Acordo de Cooperação Técnica pode servir para:

1. Cooperação técnica em projetos de inventário e preservação do patrimônio.
2. Intercâmbio de conhecimentos especializados em restauro e conservação.
3. Desenvolvimento conjunto de metodologias de gestão patrimonial.
4. Parcerias para capacitação e qualificação de servidores.
5. Compartilhamento de expertise em digitalização de acervos.
6. Projetos colaborativos de educação patrimonial.
7. Cooperação em pesquisas sobre patrimônio cultural mineiro.

## ✅ Pode:
**Características do instrumento:**
- Estabelecer cooperação técnica sem transferência de recursos.
- Formalizar parcerias baseadas em interesse recíproco.
- Combinar esforços, conhecimentos e capacidades técnicas.
- Compartilhar experiências, metodologias e boas práticas.

**Partes que podem celebrar** (art. 25 do Decreto nº 11.531/2023):
- Órgãos e entidades da administração pública federal, estadual, distrital e municipal.
- Serviços sociais autônomos.
- Consórcios públicos.

## ❌ Não pode:
⚠️ **Limitações:**  
- Não envolve transferência de recursos públicos (art. 24, parágrafo único).
- Não envolve doação de bens materiais.
- Não substitui procedimentos de contratação quando há fornecimento oneroso.

⚠️ **Características específicas:**  
- As despesas relacionadas à execução não configuram transferência de recursos, devendo correr à conta de cada parte (art. 24, parágrafo único).
- Instrumento exclusivamente gratuito.
- Não gera obrigações financeiras entre as partes.

## 📋 Celebração
Decisão discricionária da administração pública baseada em análise de interesse comum e viabilidade da cooperação técnica.

## 🪪 Documentação
Por se tratar de instrumento sem transferência de recursos, dispensa documentação complexa, sendo necessários apenas:
- Identificação das partes
- Descrição clara do objeto da cooperação
- Definição das responsabilidades de cada parte
- Prazo de vigência
> Não é obrigatório, mas é boa prática constar um plano de trabalho simplificado, com ações objetivas visando ao cumprimento do objeto da cooperação, prazos para início e término de cada ação, responsáveis pela ação e fonte de comprovação (documentos, fotografias, relatórios, publicações etc. que atestem a realização daquela atividade).

## 🔒 Prestação de contas
Não é exigida prestação de contas financeira, uma vez que o instrumento não envolve transferência de recursos. Pode ser estabelecida apresentação de relatórios técnicos sobre as atividades desenvolvidas, conforme acordado entre as partes.

**Conteúdo sugerido para relatórios técnicos:**
- Descrição das atividades realizadas
- Resultados alcançados na cooperação
- Benefícios mútuos obtidos
- Produtos ou conhecimentos desenvolvidos
- Avaliação qualitativa da parceria

## 🔍 Saiba mais!
Modelos e documentos de referência podem ser encontrados no nosso [Repositório de Parcerias](https://lucasfainblat.github.io/manual.appi/paginas/repositorio/README.html).

## ↔️ Fluxograma para celebração e execução de Acordo de Cooperação Técnica
Todos os procedimentos do fluxograma referem-se ao [Decreto Federal nº 11.531/2023](https://www.planalto.gov.br/ccivil_03/_ato2023-2026/2023/decreto/d11531.htm). Diferentes formas das caixinhas significam diferentes setores responsáveis por cada atividade, conforme legenda.

<div class="mermaid">
flowchart TD
    A_LEG@{ shape: lean-r, label: "Área Técnica Demandante" }
    B_LEG@{ shape: rect, label: "Gabinete" }
    C_LEG@{ shape: rounded, label: "Setor de Contratos e Convênios" }
    D_LEG@{ shape: trap-b, label: "Assessoria Jurídica" }
    E_LEG@{ shape: diamond, label: "Pergunta/Decisão" }
</div>

<div class="mermaid">
flowchart TD
    A@{ shape: lean-r, label: "Solicitar cooperação técnica" } --> B@{ shape: rect, label: "Analisar solicitação"}
    B --> C@{ shape: diamond, label: "Cooperação é viável e de interesse recíproco?"}
    C -- Não --> D@{ shape: rect, label: "Justificar negativa à área técnica por e-mail"}
    D --> FIM@{ shape: dbl-circ, label: "Fim do fluxo"}
    C -- Sim --> E@{ shape: rect, label: "Desenvolver/revisar minuta do Acordo de Cooperação Técnica"}
    E --> F@{ shape: lean-r, label: "Analisar minutas"}
    F --> G@{ shape: diamond, label: "Minutas validadas?"}
    G -- Não --> E
    G -- Sim --> H@{ shape: rect, label: "Encaminhar processo ao setor de Contratos e Convênios"}
    H --> I@{ shape: rounded, label: "Instruir processo no SEI"}
    I --> J@{ shape: diamond, label: "Necessária análise jurídica? (negativo se for minuta padrão já analisada previamente)"}
    J -- Não --> L@{ shape: rect, label: "Assinar Acordo de Cooperação Técnica"}
    J -- Sim --> K@{ shape: trap-b, label: "Análise jurídica"}
    K --> M@{ shape: rounded, label: "Promover ajustes e anexar nota saneadora"}
    M --> L
    L --> N@{ shape: lean-r, label: "Executar ações de cooperação conforme acordado"}
    N --> O@{ shape: diamond, label: "Havia previsão de relatório técnico?"}
    O -- Sim --> P@{ shape: lean-r, label: "Elaborar relatório técnico das atividades"}
    O -- Não --> FIM
    P --> Q@{ shape: diamond, label: "Compromissos foram cumpridos adequadamente?"}
    Q -- Sim --> FIM
    Q -- Não --> R@{ shape: rounded, label: "Adotar medidas cabíveis conforme acordo"}
    R --> FIM
</div>

<script type="module">
      import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
    
      mermaid.initialize({ startOnLoad: true });
</script>

##### [⬅️ Voltar à página inicial](https://lucasfainblat.github.io/manual.appi)
