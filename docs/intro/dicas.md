# 💎 Dicas

Aqui você encontra orientações práticas que podem facilitar muito o trabalho de quem quer celebrar, executar ou prestar contas de uma parceria.

## Etapas de uma parceria

=== "Fluxo resumido"

    ```mermaid
    %%{init: { 'flowchart': { 'htmlLabels': true, 'wrappingWidth': 900 }, 'maxTextSize': 90000 }}%%
    flowchart TD
        A1["<b>1. Análise técnica</b><hr>A unidade demandante manifesta à APPI do IEPHA-MG o desejo de celebrar uma parceria.<br>A APPI, então, vai avaliar se a proposta faz sentido, se está alinhada com as políticas do IEPHA-MG e se é viável na prática."]
        A2["<b>2. Chamamento público (ou dispensa)</b><hr>É a etapa de abertura para seleção de parceiros (quando for necessário, de acordo com a legislação aplicável e o caso concreto),<br>garantindo transparência e igualdade de oportunidades."]
        A3["<b>3. Celebração do instrumento jurídico</b><hr>Formalização e assinatura da parceria por meio de contrato, termo, acordo<br>ou outro instrumento previsto em lei."]
        A4["<b>4. Execução e acompanhamento</b><hr>Colocar em prática o que foi acordado e acompanhar o andamento,<br>monitorando prazos, resultados e recursos."]
        A5["<b>5. Prestação de contas</b><hr>Conferir se os resultados foram alcançados e o objeto foi cumprido.<br>Se necessário, conforme legislação, registrar como os recursos e atividades foram aplicados,<br>garantindo transparência e responsabilidade."]
        
        A1 --> A2
        A2 --> A3
        A3 --> A4
        A4 --> A5

        classDef default stroke:#333,stroke-width:1px,fill:#f8f8f8,rx:6,ry:6,font-size:20px;
    ```

=== "Prazos (sem chamamento)"

    | Cenário                | Fases consideradas                | Estimativa (dias úteis) | Estimativa (dias corridos, aprox.) |
    |------------------------|-----------------------------------|--------------------------|-----------------------------------|
    | Sem chamamento público | Análise técnica + Celebração      | 66                       | 92                                |

    ---

    ```mermaid
    %%{init: { 'flowchart': { 'htmlLabels': true }, 'maxTextSize': 90000 }}%%
    flowchart LR
        A1["<b>1. Análise técnica (46 dias úteis)</b><hr>• Protocolo (0d)<br>• Triagem (5d)<br>• Análises técnicas interna e externa + alterações (14d)<br>• Nota técnica (5d)<br>• Alterações + instrução processual (7d)<br>• Nota jurídica (10d)<br>• Nota saneadora (5d)"]
        A2["<b>2. Celebração (20 dias úteis)</b><hr>• Manifestação técnica e jurídica externa (se for o caso: 10d)<br>• Assinatura e publicação (10d)"]
        A3["<b>3. Execução</b>"]
                
        A1 --> A2
        A2 --> A3
        
        classDef default stroke:#333,stroke-width:1px,fill:#f8f8f8,rx:6,ry:6,font-size:13px;
    ```
    
    ---


    ```mermaid
    %%{init: { "theme": "forest", "gitGraph": { "mainBranchName": "Análise Técnica" } }}%%
        gitGraph
          commit id: "Mês 1"
          commit id: "Mês 2"
          branch "Celebração"
          commit id: "Mês 3"
          branch "Execução"
          commit id: "Vigência"
          checkout "Análise Técnica"
    ```

=== "Prazos (com chamamento)"

    | Cenário                | Fases consideradas                             | Estimativa (dias úteis) | Estimativa (dias corridos, aprox.) |
    |------------------------|------------------------------------------------|--------------------------|-----------------------------------|
    | Com chamamento público | Análise técnica + Chamamento + Celebração      | 94                       | 132                               |

    ---

    ```mermaid
    %%{init: { 'flowchart': { 'htmlLabels': true }, 'maxTextSize': 90000 }}%%
    flowchart LR
        B1["<b>1. Análise técnica (69 dias úteis)</b><hr>• Protocolo (0d)<br>• Triagem (15d)<br>• Análise técnica interna (10d)<br>• Alterações internas (5d)<br>• Consulta pública (10d)<br>• Alterações externas (2d)<br>• Nota técnica (5d)<br>• Alterações + instrução do processo (7d)<br>• Nota jurídica (10d)<br>• Nota saneadora/publicação (5d)"]
        B2["<b>2. Chamamento público (15 dias úteis)*</b><hr>• Recebimento e seleção de propostas (≥5d)<br>• Recursos, contrarrazões e homologação (≥5d)<br>• Habilitação e recursos (≥5d)"]
        B3["<b>3. Celebração (10 dias úteis)</b><hr>• Convocação dos selecionados (≥2d)<br>• Assinatura (3d)<br>• Publicação (5d)"]
        B4["<b>4. Execução</b>"]

        B1 --> B2
        B2 --> B3
        B3 --> B4
        classDef default stroke:#333,stroke-width:1px,fill:#f8f8f8,rx:6,ry:6,font-size:13px;
    ```

    ---


    ```mermaid
    %%{init: { "theme": "forest", "gitGraph": { "mainBranchName": "Análise Técnica" } }}%%
        gitGraph
          commit id: "Mês 1"
          commit id: "Mês 2"
          branch "Chamamento"
          commit id: "Mês 3"
          branch "Celebração"
          commit id: "Mês 4"
          branch "Execução"
          commit id: "Vigência"
          checkout "Análise Técnica"
    ```

=== "Quadro de resumo"

    | Etapa                                     | Ator Responsável                               | Documento Principal                                                                 | Prazo                                                                                  |
    |-------------------------------------------|------------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
    | 1. Protocolo e Registro Inicial           | Unidade demandante                             | • Ofício<br>• Memorando<br>• Carta de Intenções                                     | N/A                                                                                    |
    | 2. Triagem Preliminar                     | APPI                                           | • Minuta de instrumento jurídico<br>• Edital                                        | • ≤ 5 dias úteis (sem cham.)<br>• ≤ 15 dias úteis (com cham.)                      |
    | 3. Análise Técnica Interna                | Unidade demandante e áreas técnicas do IEPHA   | • Minuta revisada do instrumento<br>• Edital                                        | • ≤ 5 dias úteis (sem cham.)<br>• ≤ 10 dias úteis (com cham.)                          |
    | 4. Alterações (se houver)                 | APPI                                           | Minuta validada                                                                      | • ≤ 2 dias úteis (sem cham.)<br>• ≤ 5 dias úteis (com cham.)                           |
    | 5. Análise Técnica Externa / Consulta Pública | Entidade parceira ou APPI (se chamamento)   | Minuta revisada com sugestões                                                        | • ≤ 5 dias úteis (sem cham.)<br>• ≤ 10 dias úteis (com cham.)                          |
    | 6. Alterações (se houver)                 | APPI                                           | Minuta validada                                                                      | ≤ 2 dias úteis                                                                         |
    | 7. Manifestação Técnica Interna           | APPI                                           | Nota técnica                                                                         | ≤ 5 dias úteis                                                                         |
    | 8. Alterações (se houver)                 | APPI                                           | • Minuta revisada<br>• Encaminhamento à GLCC                                        | ≤ 2 dias úteis                                                                         |
    | 9. Instrução do processo                  | GLCC                                           | Processo SEI instruído                                                               | ≤ 5 dias úteis                                                                         |
    | 10. Análise Jurídica                      | Procuradoria Jurídica                          | Parecer jurídico                                                                     | ≤ 10 dias úteis                                                                        |
    | 11. Nota saneadora e/ou publicação        | GLCC                                           | • Nota saneadora<br>• Edital de chamamento público                                   | ≤ 5 dias úteis                                                                         |
    | 12. Recebimento e seleção de propostas    | Comissão julgadora                             | • Pareceres de seleção<br>• Resultado do chamamento                                  | ≥ 5 dias úteis (depende do marco legal)                                                |
    | 13. Recursos e homologação                | Comissão de recursos                           | • Pareceres de recursos<br>• Homologação                                             | ≥ 5 dias úteis (depende do marco legal)                                                |
    | 14. Habilitação                           | GLCC                                           | Documentação habilitatória                                                           | ≥ 5 dias úteis (depende do marco legal)                                                |
    | 15. Manifestação Técnica e Jurídica Externa | APPI e Entidade parceira                     | • Nota técnica<br>• Parecer jurídico da parceira                                     | ≤ 10 dias úteis                                                                        |
    | 16. Assinatura                            | GLCC                                           | • Instrumento jurídico assinado<br>• Publicações                                     | ≤ 10 dias úteis                                                                        |
    | 17. Execução da parceria                  | Unidade demandante / Gestor / Comissão         | Relatórios e fontes de comprovação                                                   | N/A (varia pelo instrumento)                                                           |
    | 18. Prestação de contas                   | GLCC                                           | • Prestação de contas<br>• Parecer conclusivo                                        | N/A (varia pelo marco regulatório)                                                     |


=== "Fluxo detalhado"
    
    ```mermaid
    flowchart TD
        %% Legenda
        A_LEG@{ shape: lean-r, label: "Unidade demandante" }
        B_LEG@{ shape: rect, label: "APPI" }
        C_LEG@{ shape: rounded, label: "GLCC" }
        D_LEG@{ shape: trap-b, label: "Procuradoria Jurídica" }
        E1_LEG@{ shape: odd, label: "Comissão Julgadora" }
        E2_LEG@{ shape: stadium, label: "Comissão de Recursos" }
        I_LEG@{ shape: diamond, label: "Decisão" }
    classDef default stroke:#333,stroke-width:1px,fill:#f8f8f8,rx:6,ry:6,font-size:22px;
    ```
    ```mermaid
    %%{init: { 'flowchart': { 'htmlLabels': true }, 'maxTextSize': 90000 }}%%
    flowchart TD
    %% Etapas iniciais
    A@{ shape: lean-r, label: "Solicitar parceria (enviar proposta ou manifestação de interesse)" } --> B@{ shape: rect, label: "Realizar triagem preliminar (viabilidade, marco regulatório e instrumento jurídico)" }
    B --> C@{ shape: diamond, label: "Necessita chamamento público?" }
    C -->|Sim| SEL
    C -->|Não| DIS
    %% Chamamento Público
    subgraph SEL ["Com chamamento público"]
        direction TB
        S1@{ shape: rect, label: "Elaborar minuta do edital e do instrumento jurídico" }
        S1 --> S2@{ shape: diamond, label: "Minutas validadas internamente?" }
        S2 -->|Não| S1
        S2 -->|Sim| S1a@{ shape: rect, label: "Realizar consulta pública ou processo equivalente (se exigível pelo marco regulatório)" }
        S1a --> S1b@{ shape: rect, label: "Ajustar conforme consulta pública (se for o caso)" }
        S1b --> S1c@{ shape: lean-r, label: "Emitir nota técnica" }
        S1c --> S3@{ shape: rounded, label: "Instruir processo SEI" }
        S3 --> S4@{ shape: trap-b, label: "Análise jurídica" }
        S4 --> S5@{ shape: rounded, label: "Ajustar e elaborar nota saneadora" }
        S5 --> S6@{ shape: rect, label: "Publicar edital" }
        S6 --> S7@{ shape: odd, label: "Receber propostas" }
        S7 --> S8@{ shape: odd, label: "Selecionar propostas" }
        S8 --> S10@{ shape: odd, label: "Publicar resultado" }
        S10 --> S12@{ shape: stadium, label: "Receber e julgar recursos" }
        S12 --> S13@{ shape: odd, label: "Homologar resultado" }
    end
    %% Dispensa
    subgraph DIS ["Sem chamamento público"]
        direction TB
        D2@{ shape: rect, label: "Desenvolver minuta do instrumento jurídico" }
        D2 --> D3@{ shape: diamond, label: "Minutas validadas internamente?" }
        D3 -->|Não| D2
        D3 -->|Sim| D1c@{ shape: lean-r, label: "Emitir nota técnica" }
        D1c --> D4@{ shape: rounded, label: "Instruir processo SEI" }
        D4 --> D5@{ shape: trap-b, label: "Análise jurídica" }
        D5 --> D6@{ shape: rounded, label: "Ajustar e elaborar nota saneadora" }
    end
    %% Convergência pós-seleção/dispensa
        S13 --> G1
        D6 --> G1
        G1@{ shape: rounded, label: "Verificar documentos e habilitar entidade parceira" } --> I1@{ shape: diamond, label: "Necessária manifestação técnica e jurídica da entidade parceira?" }
        I1 -->|Sim| I2@{ shape: rect, label: "Solicitar nota técnica e parecer jurídico da entidade parceira" }
        I2 --> I3@{ shape: rect, label: "Ajustar instrumento jurídico conforme sugestões (se necessário)" }
        I1 -->|Não| J1
        I3 --> J1@{ shape: rect, label: "Revisar e consolidar instrumento jurídico" }
        J1 --> J2@{ shape: rounded, label: "Assinar instrumento jurídico" }
        J2 --> J3@{ shape: rect, label: "Providenciar publicações exigidas pelo marco regulatório (se for o caso)" }
        %% Execução e acompanhamento
        J3 --> K2@{ shape: lean-r, label: "Executar parceria" }
        %% Decisão sobre metas/resultados
        K2 --> L1@{ shape: diamond, label: "Metas e resultados alcançados?" }
        L1 -->|Sim| M1@{ shape: rounded, label: "Analisar prestação de contas (se exigível pelo marco regulatório)" }
        L1 -->|Não| L2@{ shape: diamond, label: "Há justificativas formais adequadas?" }
        L2 -->|Sim| M1
        L2 -->|Não| L3@{ shape: rect, label: "Adotar medidas cabíveis conforme marco regulatório" } --> M1
        %% Prestação de Contas e conclusão
        M1 --> N1@{ shape: diamond, label: "Há irregularidades na prestação de contas?" }
        N1 -->|Não| FIM(((Fim)))
        N1 -->|Sim| N2@{ shape: rounded, label: "Notificar entidade parceira para esclarecimentos" } --> N3@{ shape: rounded, label: "Emitir parecer sobre prestação de contas (aprovar, aprovar com ressalvas ou reprovar)" }
        N3 -->|Aprovada| FIM
        N3 -->|Ressalvas| N4@{ shape: rounded, label: "Aplicar providências cabíveis conforme marco regulatório" } --> FIM
        N3 -->|Reprovada| N4 --> FIM
    
    classDef default stroke:#333,stroke-width:1px,fill:#f8f8f8,rx:6,ry:6,font-size:15px;
    ```

## 🔬 Detalhamento do Processo

Agora que já identificamos cada etapa, é hora de entrar nos detalhes.

### 1. 🗂️ Protocolo e Registro Inicial

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `unidade demandante` (do `IEPHA-MG` ou da `entidade parceira`)  
    - **Atividades:**
      - Enviar a proposta de parceria e documentos preliminares à `APPI`
      - Solicitar por SEI, e-mail ou reunião
    - **Documentos:**
      - Ofício, Memorando ou Carta de Intenções (consulte um modelo [aqui](https://iepha303-my.sharepoint.com/:w:/g/personal/lucas_fainblat_iepha_mg_gov_br/EYdfxSvs8RBGiVch2U930DQBEUJdB1DgexiM9XD4DYPPdw?e=RDK8Ga))
      - Portfólio da `entidade parceira` e apresentação do projeto, se houver (consulte exemplos: [aqui](https://www.gov.br/iphan/pt-br/assuntos/andancas/CadernoAndanasdoPatrimniofinal22_041.pdf) ou [aqui](https://museudarepublica.museus.gov.br/wp-content/uploads/2019/02/revista-do-professor_PEJA_para-internet.pdf))
    - **Prazo:** N/A (sob demanda)

=== "✅ Checklist"

    | Checklist | Exemplos |
    | :--- | :--- |
    | **✅ Objeto da parceria:** o que se quer fazer por meio de parceria? | Modelagem 3D de um bem tombado / dossiê de tombamento / capacitações de servidores / digitalização de documentos |
    | **✅ Justificativa da parceria:** por que fazer por parceria, não diretamente? | A `entidade parceira` possui um projeto captado para executar o objeto / a `entidade parceira` possui tecnologia exclusiva que vai doar para o projeto / o bem tombado aguarda intervenções emergenciais |
    | **✅ Responsabilidades:** o que se espera do `IEPHA-MG` e o que se espera da `entidade parceira`? | `IEPHA-MG`: disponibilizar uma sala / compartilhar diretrizes técnicas / oferecer capacitações / acompanhar o parceiro em visitas técnicas / `Entidade parceira`: oferecer restauradores para trabalhar numa peça / realizar um seminário / oferecer acesso a uma plataforma digital |
    | **✅ Resultados e metas:** o que especificamente se espera alcançar com a parceria? Quando? | 3 modelos 3D de bens tombados impressos até dezembro / 1 dossiê de tombamento concluído até janeiro / 3 cursos de capacitação realizados e 30 servidores capacitados até junho |

=== "🚨 Atenção"
    > Ao requisitar uma parceria, a `unidade demandante` deve considerar se tem "_pernas_" para executar e monitorar o que está sendo proposto, pois será necessário um ponto focal para gerir o futuro instrumento jurídico, garantir que as metas e resultados estejam sendo cumpridos e organizar a comprovação disso num eventual processo de prestação de contas.

---

### 2. 🎯 Triagem Preliminar

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `APPI`  
    - **Atividades:**
      - Analisar **viabilidade** da parceria
      - Identificar o **marco regulatório** e o **tipo de instrumento jurídico** adequados
      - Identificar necessidade ou não de **chamamento público**
      - Requisitar complementação de informações, se necessário
      - Elaborar `minuta de instrumento jurídico`, caso haja viabilidade da parceria
      - Responder `unidade demandante` pelo mesmo meio da etapa anterior
    - **Atividades:** (se houver chamamento público)
      - Elaborar `minuta de edital de chamamento público` (e anexos), caso seja necessário
    - **Documentos:**
      - Correspondência de resposta (memorando, e-mail etc.)
      - Se `APPI` julgar que há viabilidade da parceria: `Minuta de instrumento jurídico` (enviada por _link na nuvem_)
      - Se `APPI` julgar que há viabilidade e é necessário chamamento público: `minuta de edital de chamamento público` (enviada por _link na nuvem_)
    - **Prazo:** até `5 dias úteis` (se não houver necessidade de chamamento público) / até `15 dias úteis` (se houver necessidade de chamamento público)

=== "✅ Checklist"

    | Checklist | Observações | Respostas |
    | :--- | :--- | :--- |
    | **✅ A parceria faz sentido pro `IEPHA-MG`?** | Está alinhada ao PPAG / cabe no estatuto / possui coerência com a estratégia institucional / é de interesse público | |
    | **✅ A parceria é viável na prática?** | Os resultados são atingíveis / o `IEPHA-MG` possui meios para cumprir com as suas obrigações | |
    | **✅ Qual o marco regulatório e instrumento jurídico ideal para a parceria?** | `APPI` deve decidir com base nas respostas abaixo | [MRFC](https://iepha-mg.github.io/manual.appi/paginas/marcos_regulatorios/MRFC/README.html) / [MROSC](https://iepha-mg.github.io/manual.appi/paginas/marcos_regulatorios/MROSC/README.html) / [Modelo OSCIP/OS](https://iepha-mg.github.io/manual.appi/paginas/marcos_regulatorios/descentralizacao/README.html) / [Fundações de Apoio](https://iepha-mg.github.io/manual.appi/paginas/marcos_regulatorios/fundacoes/README.html) / [Acordo de Cooperação Técnica](https://iepha-mg.github.io/manual.appi/paginas/marcos_regulatorios/ACT/README.html) |
    | | ✅ Envolve transferências de recursos, comodato ou ocupação de espaço? | Sim / Não |
    | | ✅ Envolve concessão de bolsas, prêmios ou fomento a projetos? | Sim / Não |
    | | ✅ Foi proposta por alguma `entidade parceira` ou pelo `IEPHA-MG`? | Proposta pela `entidade parceira` / Proposta pelo `IEPHA-MG` |
    | | ✅ O objeto da parceria é complexo ou simples? | Complexo / Simples - Justificar |
    | | ✅ É necessário um plano de trabalho detalhado? | Sim / Não - Justificar |
    | | ✅ Seria necessário nomear formalmente gestores, fiscais ou comissão de monitoramento, tendo em vista a complexidade do objeto? | Sim / Não - Justificar |
    | | ✅ Será necessário chamamento público? Se não, por quê? | Sim / Não - Não envolve transferências / competição é inviável / situação é hipótese de dispensa - outras razões |

=== "🚨 Atenção"
    > Documentos na _nuvem_ facilitam o trabalho conjunto, porque todas as partes podem revisar, comentar e acompanhar as mudanças num único arquivo. Além disso, o sistema guarda o histórico, permitindo voltar atrás se for preciso.

=== "❓ Saiba mais"
    > A `APPI` utiliza minutas padronizadas, baseadas em modelos disponibilizados por órgãos públicos do Governo Federal, para facilitar a tramitação jurídica dos processos de parceria. Por isso, envia o "_esqueleto_" dos documentos em letras pretas e o "_recheio_" em letras azuis. Assim, recomenda-se não alterar as partes em preto, ao passo que as partes em azul devem ser modificadas conforme cada caso concreto.

---

### 3. 🔎 Análise Técnica Interna

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `unidade demandante` e, se for o caso, demais Diretorias/Gerências relacionadas ao objeto da parceria no `IEPHA-MG`
    - **Atividades:**
      - Revisar `minuta de instrumento jurídico`
      - Sugerir alterações
      - Registrar comentários
      - Responder `APPI` pelo mesmo meio da etapa anterior
    - **Atividades:** (se houver chamamento público)
      - Revisar `minuta de edital de chamamento público` (e anexos), caso seja necessário
    - **Documentos:**
      - Correspondência de resposta (memorando, e-mail etc.)
      - `minuta de instrumento jurídico` comentada e revisada com sugestões (_link na nuvem_)
      - `minuta de edital de chamamento público` comentada e revisada com sugestões (_link na nuvem_), se for o caso
    - **Prazo:** até `5 dias úteis` (se não houver necessidade de chamamento público) / até `10 dias úteis` (se houver necessidade de chamamento público)

=== "✅ Checklist Instrumento Jurídico"

    | Checklist | Observações |
    | :--- | :--- |
    | **✅ Preâmbulo** | Introdução de qualquer `minuta de instrumento jurídico`, contendo dados das partes que vão assinar. Cláusula em azul |
    | **✅ Objeto da parceria** | Parte mais importante da `minuta de instrumento jurídico`. Deve ser descrita de forma clara e objetiva: nem vaga demais, nem detalhada em excesso. Assim, permite que diferentes atividades e metas sejam realizadas dentro da parceria. Cláusula em azul. |
    | **✅ Vigência** | Início e fim da parceria. Cada `minuta de instrumento jurídico` terá um limite, conforme `marco regulatório`. Cláusula em azul |
    | **✅ Atribuições das partes** | Define-se as responsabilidades do `IEPHA-MG` e da `entidade parceira`. Cláusula em azul |
    | **✅ Plano de Trabalho** | Definição de `resultados`, `produtos` e `metas`. Somente necessário em alguns casos (estará na minuta se positivo). Cláusula em azul |
    | **✅ Justificativa da parceria e público-alvo** | Geralmente parte do `plano de trabalho`, portanto somente necessário em alguns casos. Cláusula em azul |
    | **✅ Outras cláusulas** | Partes do documento como "do foro", "proteção de dados" etc. Geralmente são cláusulas padrão, sinalizadas em preto, portanto modificá-las não é recomendável |

=== "✅ Checklist Chamamento Público"

    | Checklist | Observações |
    | :--- | :--- |
    | **✅ Conformidade entre chamamento e instrumento jurídico** | A `minuta de instrumento jurídico` deve ser `anexo` da `minuta de edital de chamamento público`. Suas cláusulas, itens e remissões devem ter coerência mútua |
    | **✅ Fundamentos e objeto** | A base legal, a motivação e o objeto da parceria devem estar bem explicados para qualquer pessoa entender |
    | **✅ Programação orçamentária (se for o caso)** | Deve estar clara qual dotação orçamentária viabiliza a celebração da parceria, quanto será destinado a ela, como e quando serão feitos os repasses |
    | **✅ Regras de inscrição** | Quem pode participar, quem não pode participar, como participar e se inscrever, até quando serão recebidas propostas e que documentos devem ser apresentados? Geralmente, anexos específicos indicam a plataforma e o formulário de inscrição |
    | **✅ Regras de seleção** | Quais são as categorias das propostas, quantas serão contempladas, quem vai recebê-las e julgá-las, como elas serão julgadas e como serão publicados os resultados. Muitas vezes, anexos específicos são utilizados para os critérios de seleção |
    | **✅ Dúvidas, impugnações e recursos** | Canais e procedimentos para tirar dúvidas, apresentar recursos, defesas e impugnações |
    | **✅ Etapas e prazos** | Cronogramas com etapas e prazos para quem quiser se inscrever e acompanhar o processo |
    | **✅ Declarações** | Se necessário, anexar modelos de declarações, comprovações e outras exigências legais |
    | **✅ Anexos específicos** | São necessários anexos específicos? Exemplo: plantas de espaços que serão ocupados, fichas técnicas de equipamentos, referencial conceitual da política pública etc. |

---

### 4. ♻️ Alterações (se houver)

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `APPI`
    - **Atividades:**
      - Revisar `minuta de instrumento jurídico` conforme etapa anterior
      - Encaminhar `minuta de instrumento jurídico` à `entidade parceira` (se não houver chamamento público)
    - **Atividades:** (se houver chamamento público)
      - Revisar `minuta de edital de chamamento público` conforme etapa anterior
      - Proceder à etapa 7
    - **Documentos:**
      - Correspondência de encaminhamento (memorando, e-mail etc.)
      - `Minuta de instrumento jurídico` validada pela `unidade demandante` (_link na nuvem_)
      - `Minuta de edital de chamamento público` validada pela `unidade demandante` (_link na nuvem_), se houver chamamento público
    - **Prazo:** até `2 dias úteis` (se não houver chamamento público) / até `5 dias úteis` (se houver chamamento público)

---

### 5. 🔍 Análise Técnica Externa (ou consulta pública)

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `entidade parceira` (se não houver chamamento) ou `APPI` (se houver chamamento)
    - **Atividades:**
      - Revisar `minuta de instrumento jurídico`
      - Sugerir alterações
      - Registrar comentários
      - Responder `APPI` pelo mesmo meio da etapa anterior
    - **Atividades:** (se houver chamamento público)
      - Providenciar consulta pública, sessões técnicas ou procedimento equivalente, para revisar `minuta de edital de chamamento público` (e anexos)
      - Registrar sugestões, comentários e melhorias, se for o caso
    - **Documentos:**
      - Correspondência de resposta (memorando, e-mail etc.)
      - `Minuta de instrumento jurídico` comentada e revisada com sugestões (_link na nuvem_)
    - **Prazo:** até `5 dias úteis` (se não houver chamamento público) / até `10 dias úteis` (se houver chamamento público)

=== "🚨 Atenção"
    > A etapa 3 traz checklists para análise técnica de `minuta de instrumento jurídico` e `minuta de edital de chamamento público`, que podem ser utilizados também nesta etapa.

=== "❓ Saiba mais"
    > Como ainda não há decreto estadual regulamentando a [Lei 14.903/2024 (Marco do Fomento)](https://www.planalto.gov.br/ccivil_03/_ato2023-2026/2024/lei/l14903.htm), não foram estabelecidos prazos mínimos para realização de consulta pública, razão pela qual adotamos o mesmo parâmetro de 10 dias úteis utilizado para a análise técnica interna, considerando que a documentação envolvida numa chamada pública pode ser muito extensa. Entretanto, até o momento é possível realizar a consulta pública em menos tempo. 

---

### 6. ♻️ Alterações (se houver)

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `APPI`
    - **Atividades:**
      - Revisar `minuta de instrumento jurídico` conforme etapa anterior
      - Criar `processo SEI` com `minuta de instrumento jurídico` e documentos relevantes (se houver)
      - Encaminhar `processo SEI` à `unidade demandante`
    - **Atividades:** (se houver chamamento público)
      - Revisar `minuta de edital de chamamento público` conforme sugestões da etapa anterior
    - **Documentos:**
      - Correspondência de encaminhamento (memorando, e-mail etc.)
      - `Minuta de instrumento jurídico` validada pela `entidade parceira` (documento no SEI)
    - **Prazo:** até `2 dias úteis`

---

### 7. ✏️ Manifestação Técnica Interna

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `APPI`
    - **Atividades:**
      - Emitir `nota técnica`
      - Encaminhar `processo SEI` à `APPI`
    - **Documentos:**
      - Correspondência de encaminhamento (memorando no SEI)
      - `nota técnica` (documento no SEI; consulte um modelo [aqui](https://iepha303-my.sharepoint.com/:w:/g/personal/lucas_fainblat_iepha_mg_gov_br/EQjHT3MfaOxLvOt_eijbS0UBjqPOARFzOHEzE3M0ZfpTBQ?e=G6poy7))
    - **Prazo:** até `5 dias úteis`

=== "✅ Checklist"

    | Checklist de uma boa nota técnica | Observações |
    | :--- | :--- |
    | **✅ Objeto da parceria** | Definir o objeto e comentar sua pertinência |
    | **✅ Justificativa da parceria e interesse público** | Por que a parceria é importante para o público? Por que está sendo feita como parceria e não diretamente? |
    | **✅ Alinhamento institucional com as competências da `unidade demandante` e do `IEPHA-MG`** | Objeto tem alinhamento com alguma ação orçamentária ou programa do PPAG? Cabe na estratégia institucional? Cabe no estatuto? |
    | **✅ Viabilidade e exequibilidade técnica** | A `unidade demandante` deve atestar que a parceria é viável e que possui meios para ser executada com seus quadros e recursos |
    | **✅ Conclusão** | `unidade demandante` manifesta-se favorável, favorável com ressalvas ou desfavorável à parceria |

---

### 8. ♻️ Alterações (se houver)

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `APPI`
    - **Atividades:**
      - Ler `nota técnica`
      - Revisar `minuta de instrumento jurídico` conforme etapa anterior, se for o caso
      - Encaminhar `processo SEI` à `GLCC` (Gerência de Licitações, Contratos e Convênios da Diretoria de Planejamento, Gestão e Finanças)
    - **Atividades:** (se houver chamamento público)
      - Revisar `minuta de edital de chamamento público` conforme etapa anterior, se for o caso
    - **Documentos:**
      - Correspondência de encaminhamento (memorando no SEI)
    - **Prazo:** até `2 dias úteis`

---

### 9. 🗃️ Instrução do processo

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `GLCC`
    - **Atividades:**
      - Instruir o `processo SEI` com os documentos pertinentes
      - Encaminhar `processo SEI` à `procuradoria jurídica`
    - **Documentos:**
      - Estatutos, certidões negativas e demais documentos aplicáveis conforme o caso (documentos no SEI)
      - Correspondência de encaminhamento (memorando no SEI)
      - `minuta de instrumento jurídico`
      - `minuta de edital de chamamento público`, se for o caso
    - **Prazo:** até `5 dias úteis`

---

### 10. ⚖️ Análise Jurídica

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `procuradoria jurídica`
    - **Atividades:**
      - Verificar a conformidade legal do `processo SEI`
      - Orientar explicitamente sobre ajustes necessários
      - Emitir `parecer jurídico` conclusivo
      - Enviar o `processo SEI` à `GLCC`
    - **Documentos:**
      - Correspondência de encaminhamento (memorando no SEI)
      - `parecer jurídico` (documento no SEI)
    - **Prazo:** até `10 dias úteis`

=== "✅ Checklist"

    | Checklist de uma boa nota jurídica | Observações ([Manual de Boas Práticas Consultivas (4ª Edição), Advocacia-Geral da União (AGU)](https://www.gov.br/agu/pt-br/composicao/cgu/cgu/manuais/manual-de-boas-praticas-consultivas-4a-edicao.pdf/@@download/file)) |
    | :--- | :--- |
    | **✅ Redação clara e objetiva quanto aos encaminhamentos** | Deve ser fácil de entender para o solicitante ([Manual da AGU, p. 22](https://www.gov.br/agu/pt-br/composicao/cgu/cgu/manuais/manual-de-boas-praticas-consultivas-4a-edicao.pdf/@@download/file)). |
    | **✅ Conclusão simples e absolutamente inteligível** | A conclusão deve destacar de forma explícita e objetiva quais providências devem ser tomadas ([Manual da AGU, p. 22](https://www.gov.br/agu/pt-br/composicao/cgu/cgu/manuais/manual-de-boas-praticas-consultivas-4a-edicao.pdf/@@download/file)). |
    | **✅ Foco no essencial, evitando tratados jurídicos** | Só em caso de necessidade a conclusão pode remeter a tópicos específicos detalhados. O padrão é a clareza e a concisão ([Manual da AGU, p. 22](https://www.gov.br/agu/pt-br/composicao/cgu/cgu/manuais/manual-de-boas-praticas-consultivas-4a-edicao.pdf/@@download/file)). |
    | **✅ Interação com os assessorados antes da manifestação final** | É boa prática que a nota seja fruto de diálogo com as áreas envolvidas, podendo incluir consultas formais e informais para esclarecimento prévio ([Manual da AGU, p. 56](https://www.gov.br/agu/pt-br/composicao/cgu/cgu/manuais/manual-de-boas-praticas-consultivas-4a-edicao.pdf/@@download/file)). |
    | **✅ Limites da análise jurídica** | Não é boa prática emitir posicionamentos conclusivos sobre temas técnicos, administrativos ou de conveniência; se o fizer, deve indicar explicitamente o caráter não obrigatório do acatamento ([Manual da AGU, p. 32](https://www.gov.br/agu/pt-br/composicao/cgu/cgu/manuais/manual-de-boas-praticas-consultivas-4a-edicao.pdf/@@download/file)). |

=== "🚨 Atenção"
    > A não ser que a legislação do `marco regulatório` indique o contrário, a `minuta de instrumento jurídico` que estiver exatamente no padrão de outra já analisada e aprovada por `procuradoria jurídica` do Estado de Minas Gerais **não precisa passar por nova análise jurídica** - ou seja, esta etapa pode ser "_pulada_" em alguns casos. **Porém, se houver qualquer dúvida, recomenda-se sempre a consulta jurídica.**

---

### 11. 🧼 Nota saneadora (se necessário) e publicação (se houver chamamento público)

=== "ℹ️ Info"

    - **Fase**: Análise técnica
    - **Ator Responsável:** `GLCC`
    - **Atividades:**
      - Interpretar `parecer jurídico`
      - Revisar `minuta de instrumento jurídico` conforme `parecer jurídico`
      - Elaborar `nota saneadora`, listando todos os pontos solicitados pela `procuradoria jurídica` e os encaminhamentos dados
      - Proceder diretamente à etapa 14 (no caso de não haver chamamento público)
    - **Atividades:** (se houver chamamento público)
      - Revisar `minuta de edital de chamamento público` conforme `parecer jurídico`
      - Assinar e publicar `edital de chamamento público`
    - **Documentos:**
      - Correspondência de encaminhamento (memorando no SEI)
      - `nota saneadora` (documento no SEI; consulte um modelo [aqui](https://iepha303-my.sharepoint.com/:w:/g/personal/lucas_fainblat_iepha_mg_gov_br/EZO8QeWCKNZLpIBIvvBUFTkBuLOG3LKL0L-vUQP94i2D6w?e=UyOhXf))
      - `edital de chamamento público`, se for o caso
    - **Prazo:** até `5 dias úteis`

---

### 12. 📥 Recebimento e seleção de propostas (somente no caso de chamamento público)

=== "ℹ️ Info"

    - **Fase**: Chamamento público
    - **Ator Responsável:** `comissão julgadora` (ou equivalente)
    - **Atividades:**
      - Receber propostas dos candidatos
      - Selecionar propostas com base nos critérios do `edital de chamamento público`
      - Elaborar `parecer` para cada proposta analisada
      - Publicar `resultado do chamamento público`
    - **Documentos:**
      - `parecer` de cada proposta analisada
      - `resultado do chamamento público`
    - **Prazo:** mínimo de `5 dias úteis`, podendo variar conforme `marco regulatório`

---

### 13. 📣 Recursos e homologação do resultado (somente no caso de chamamento público)

=== "ℹ️ Info"

    - **Fase**: Chamamento público
    - **Ator Responsável:** `comissão de recursos` (ou equivalente)
    - **Atividades:**
      - Receber recursos dos candidatos
      - Julgar recursos com base no `edital de chamamento público`
      - Elaborar `parecer` para cada recurso analisado
      - Receber contrarrazões, se for o caso
      - Homologar `resultado do chamamento público`
    - **Documentos:**
      - `parecer` de cada recurso analisado
      - Homologação do `resultado do chamamento público`
    - **Prazo:** mínimo de `5 dias úteis`, podendo variar conforme `marco regulatório`

---

### 14. 📣 Habilitação

=== "ℹ️ Info"

    - **Fase**: Celebração do instrumento jurídico
    - **Ator Responsável:** `GLCC`
    - **Atividades:**
      - Analisar documentação da `entidade parceira`
      - Instruir o `processo SEI` com a documentação
      - Solicitar complementações ou atualizar certidões vencidas, se for o caso
      - Habilitar `entidade parceria` a celebrar `instrumento jurídico`
      - Encaminhar `processo SEI` à `APPI` (se houver necessidade de manifestação técnica e jurídica externa) ou proceder diretamente à etapa 16 (assinatura)
    - **Documentos:**
      - Estatutos, certidões negativas e demais documentos aplicáveis conforme o caso (documentos no SEI)
    - **Prazo:** até `5 dias úteis`, podendo variar conforme `marco regulatório`

=== "🚨 Atenção"
    > Quanto mais recente o `marco regulatório`, mais flexíveis são as exigências da Habilitação, que passam a ser mais adequadas à realidade do público-alvo, desburocratizando a fase de celebração do `instrumento jurídico`. As exigências de habilitação sempre constam no `instrumento jurídico` e no `edital de chamamento público` (se for o caso).

---

### 15. 📐 Manifestação Técnica e Jurídica Externa (se for o caso)

=== "ℹ️ Info"

    - **Fase**: Celebração do instrumento jurídico
    - **Ator Responsável:** `APPI` e `entidade parceira`
    - **Atividades:**
      - `APPI` contatar `entidade parceira` 
      - `entidade parceira` emitir `nota técnica`
      - `entidade parceira` emitir `parecer jurídico`
      - `entidade parceira` encaminhar `nota técnica` e `parecer jurídico` à `APPI`
      - `APPI` instruir `processo SEI` com `nota técnica` e `parecer jurídico` da `entidade parceira`
      - `APPI` encaminhar processo à `GLCC` para proceder à assinatura
    - **Documentos:**
      - Correspondências de encaminhamento (ofícios no SEI, e-mails ou mensagens)
      - `nota técnica` da `entidade parceira` (documento anexado no SEI)
      - `parecer jurídico` da `entidade parceira` (documento anexado no SEI)
    - **Prazo:** até `10 dias úteis`

=== "🚨 Atenção"
    > Boas práticas para a elaboração de `nota técnica` e `parecer jurídico` constam nas etapas 7 e 10 e podem ser encaminhadas à `entidade parceira`.

---

### 16. ✍️ Assinatura

=== "ℹ️ Info"

    - **Fase**: Celebração do instrumento jurídico
    - **Ator Responsável:** `GLCC`
    - **Atividades:**
      - Promover alterações restantes, se for o caso
      - Consolidar o `instrumento jurídico` em sua versão final
      - Instruir o `processo SEI` com os documentos pertinentes, atualizando o que for necessário
      - Encaminhar `instrumento jurídico` à assinatura do `dirigente máximo` do `IEPHA-MG`
      - Encaminhar `instrumento jurídico` à assinatura do `dirigente máximo` da `entidade parceria`
      - Publicar `instrumento jurídico` assinado (se for exigível pela legislação)
      - Comunicar `ASCOM` a publicar documentos no site do `IEPHA-MG` (se for exigível pela legislação)
    - **Documentos:**
      - Estatutos, certidões negativas e demais documentos aplicáveis conforme o caso (documentos no SEI)
      - `instrumento jurídico` assinado (documento no SEI)
      - `extrato de publicação`, se for o caso (documento e publicação no SEI)
      - Site do `IEPHA-MG` atualizado com publicações, se for o caso
    - **Prazo:** até `10 dias úteis`

---

### 17. 🚀 Execução da parceria

=== "ℹ️ Info"

    - **Fase**: Execução e acompanhamento
    - **Ator Responsável:** `unidade demandante` (ou comissão de monitoramento, supervisor, gestor do contrato, ou equivalente, dependendo do `marco regulatório`)
    - **Atividades:**
      - Verificar atribuições, resultados e metas previstos no `instrumento jurídico`
      - Realizar atividades necessárias para concretizar o objeto do `instrumento jurídico`
      - Realizar visitas e verificações para averiguar a realização das atividades conforme previsto no `instrumento jurídico`
      - Comunicar-se e articular o que for necessário junto à `entidade parceira`
      - Providenciar rodadas de monitoramento e avaliação, caso seja exigido pelo `marco regulatório`
      - Registrar comprovações da execução da parceria no `processo SEI`
      - Elaborar `relatório de monitoramento` ou equivalente, se exigido pelo `marco regulatório`
      - Elaborar `relatório de avaliação` ou equivalente, se exigido pelo `marco regulatório`
      - Elaborar `relatório de execução do objeto cultural` ou equivalente, se exigido pelo `marco regulatório`
      - Articular com a `ASCOM` a divulgação de resultados no âmbito do `IEPHA-MG`
      - Reportar-se ao seu superior hierárquico e ao `gabinete` do `IEPHA-MG` em caso de irregularidades ou suspeitas
      - Colaborar no que for necessário para o processo de `prestação de contas`
    - **Documentos:**
      - `fonte de comprovação` dos resultados alcançados (documentos no SEI)
      - `relatório de monitoramento` ou equivalente, se exigido pelo `marco regulatório`
      - `relatório de avaliação` ou equivalente, se exigido pelo `marco regulatório`
      - `relatório de visitação` ou equivalente, se exigido pelo `marco regulatório`
      - `relatório de execução do objeto cultural` ou equivalente, se exigido pelo `marco regulatório`
    - **Prazo:** N/A (varia conforme o `instrumento jurídico`)

=== "🚨 Atenção"
    > É desejável que a gestão do `instrumento jurídico` seja feita na `unidade demandante`, que possui domínio técnico e competências para executar a parceria.

---

### 18. 👮 Prestação de contas

=== "ℹ️ Info"

    - **Fase**: Prestação de contas
    - **Ator Responsável:** `GLCC`
    - **Atividades:**
      - Verificar comprovantes de resultados
      - Verificar comprovantes financeiros, se for o caso
      - Seguir os procedimentos de prestação de contas definidos em seção específica do `marco regulatório`
      - Consultar `unidade demandante`, `entidade parceira` ou demais áreas competentes em caso de necessidade de esclarecimentos
      - Emitir parecer conclusivo sobre `prestação de contas`
      - Instruir `processo SEI` com a `prestação de contas`
      - Publicar extrato de aprovação ou reprovação da `prestação de contas`, se exigido pelo `marco regulatório`
      - Recomendar ao `dirigente máximo` do `IEPHA-MG` sobre aplicação de sanções ou procedimentos de saneamento de irregularidades previstos no `marco regulatório`, se necessário
    - **Documentos:**
      - `prestação de contas` aprovada (com ou sem ressalvas) ou reprovada
      - parecer conclusivo (documento no SEI)
    - **Prazo:** N/A (varia conforme o `marco regulatório`)