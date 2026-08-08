# 📋 Conduta Médica – AMA/UPA/PSA/Emergência (Pública) + Privado (Particulares)

**App de apoio à decisão clínica para atendimento na rede municipal de São Paulo (versão pública) e para hospitais particulares/convênios (versão privada), com filtros por nível de complexidade e diferenciação de condutas baseadas em protocolos oficiais da SMS/SP e das sociedades brasileiras (SBEM, SBC, SBN, etc.).**

> ⚠️ Este é um app pessoal, desenvolvido para consulta rápida durante o plantão, com base em protocolos oficiais da Secretaria Municipal da Saúde de São Paulo e diretrizes das sociedades médicas brasileiras.

---

## 🚀 Acesse os apps

| App | Descrição | Acesso |
|-----|-----------|--------|
| **Conduta Médica – Pública** | Protocolos e condutas para atendimento na rede municipal (AMA, UPA, PSA e Emergência pública) | [Abrir](https://dd2r8x5b9n-spec.github.io/conduta-medica/) |
| **Conduta Médica – Privado** | Protocolos e condutas para atendimento em **hospitais particulares / convênios** (apenas PSA e Emergência, com exames de alta complexidade) | [Abrir](https://dd2r8x5b9n-spec.github.io/conduta-medica/privado.html) |
| **REMUME – Medicamentos SP** | Consulta rápida de medicamentos disponíveis na rede municipal de São Paulo | [Abrir](https://dd2r8x5b9n-spec.github.io/conduta-medica/remume.html) |

---

## 🏥 Versão Privada – Hospitais Particulares / Convênios

A versão **`privado.html`** foi desenvolvida especificamente para **atendimento em hospitais particulares e planos de saúde**, com as seguintes características:

- **Filtros:** apenas **PSA** e **Emergência** (não inclui AMA/UPA).
- **Exames e tratamentos** compatíveis com a infraestrutura de hospitais particulares:
  - Ressonância magnética (RM)
  - Angiotomografia (angioTC)
  - Ecocardiograma transesofágico
  - Angioplastia primária
  - Trombectomia mecânica
  - CPRE (colangiopancreatografia retrógrada endoscópica)
  - Drogas de alto custo (ticagrelor, prasugrel, apixaban, rivaroxaban, etc.)
- **Diretrizes** baseadas nas sociedades brasileiras (SBC, SBEM, SBN, SBU, SBCP, etc.).
- **Aviso claro** no cabeçalho: *"Esta versão NÃO inclui AMA/UPA e considera exames de alta complexidade"*.

A versão pública (`index.html`) continua disponível para a rede municipal (AMA, UPA, PSA e Emergência pública).

---

## 🚨 Escala de Manchester (Classificação de Risco)

A Escala de Manchester é utilizada para priorizar o atendimento de acordo com a gravidade do caso:

| Cor | Classificação | Tempo máximo para atendimento | Descrição |
|-----|---------------|-------------------------------|-----------|
| 🔴 **Vermelho** | Emergência | **Imediato (tempo 0)** | Risco iminente de morte. Atendimento imediato. |
| 🟠 **Laranja** | Muito Urgente | **Até 10 minutos** | Risco de perda de função de órgão ou membro. |
| 🟡 **Amarelo** | Urgente | **Até 60 minutos** | Casos de gravidade moderada. |
| 🟢 **Verde** | Pouco Urgente | **Até 120 minutos** | Casos menos graves, sem risco imediato. |
| 🔵 **Azul** | Não Urgente | **Até 240 minutos** | Casos mais leves, que podem aguardar ou ser encaminhados. |

---

## 🏥 Níveis de Atendimento (Filtros)

O app permite filtrar as condutas por nível de atendimento, facilitando a decisão clínica conforme o local de atuação:

| Nível | Descrição |
|-------|-----------|
| **📋 Todos** | Exibe todas as condutas cadastradas. |
| **🏥 AMA** | Condutas resolutivas na Atenção Básica (estabilização e encaminhamento). |
| **🚑 UPA** | Condutas para Unidade de Pronto Atendimento (diagnóstico, estabilização e internação breve). |
| **🏨 PSA** | Condutas para Pronto-Socorro (estabilização e encaminhamento para especialidades). |
| **🚨 Emergência** | Condutas para situações de risco iminente (IAM, AVC, Sepse, etc.). |

> **Nota:** Na versão **privado.html**, apenas os filtros **PSA** e **Emergência** estão disponíveis, pois o atendimento em hospitais particulares não contempla AMA/UPA.

---

## 🩺 Diferenciações Clínicas Incluídas

| CID | Diagnóstico | Diferenciação |
|-----|-------------|---------------|
| **I21.0** | IAM com Supra ST (IAMCSST) | 🔹 Trombólise ou ICP primária – janela de 12h. |
| **I21.4** | IAM sem Supra ST (IAMSST) | 🔹 Estratificação de risco (TIMI/GRACE) – AAS + Betabloqueador + Estatina + Heparina. |
| **I63.9** | AVC Isquêmico (AVCI) | 🔹 Janela de trombólise (até 4,5h) – TC de crânio obrigatória. |
| **I61.9** | AVC Hemorrágico (AVCH) | 🔹 Controle pressórico rigoroso – TC de crânio confirmatória. |
| **E16** | Hipoglicemia | 🔹 Leve/moderada vs. grave – suspeita de insulinoma. |

---

## 📋 Condutas Incluídas (versão pública – `index.html`)

### 🏥 AMA (Atenção Básica)
- A54 – Gonorreia
- A90 – Dengue
- B01 – Varicela
- B02 – Herpes Zoster
- B26 – Caxumba
- B86 – Escabiose
- E16 – Hipoglicemia
- G43.0 – Enxaqueca
- H00.0 – Hordéolo
- H10.9 – Conjuntivite
- H83.0 – Labirintite
- I10 – Hipertensão Arterial
- J11 – Síndrome Gripal
- N23 – Cólica renal
- N39 – ITU
- O21 – Hiperêmese Gravídica
- R04.0 – Epistaxe
- R06.0 – Dispneia
- R07.4 – Dor Torácica
- R10.0 – Abdômen Agudo
- R42 – Tontura
- R51 – Cefaleia
- U07.1 – COVID-19
- W54 – Mordedura de cão
- W57 – Picada de inseto

### 🚑 UPA (Unidade de Pronto Atendimento)
- B04 – Mpox
- B26.0 – Orquite por Caxumba
- I16 – Crise Hipertensiva
- I21.4 – IAM sem Supra ST
- I50 – Insuficiência Cardíaca
- I80.9 – TVP
- J44 – Exacerbação de DPOC
- K81.0 – Colecistite Aguda
- N20.0 – Litíase Urinária Obstrutiva
- N10 – Pielonefrite Aguda
- O14 – Pré-eclâmpsia
- R33 – Retenção Urinária Aguda
- R65.2 – Sepse (estabilização)
- T63 – Acidente por animal peçonhento
- T78.2 – Choque anafilático

### 🏨 PSA (Pronto-Socorro)
- E86 – Gastroenterite com Desidratação
- K35 – Apendicite Aguda

### 🚨 Emergência
- E05.9 – Crise Tireotóxica
- E10.1 – Cetoacidose Diabética
- E11.0 – Estado Hiperosmolar Hiperglicêmico
- G41 – Estado de Mal Epiléptico
- I21.0 – IAM com Supra ST
- I48 – Arritmias Cardíacas
- I60 – Hemorragia Subaracnoide
- I61.9 – AVC Hemorrágico
- I63.9 – AVC Isquêmico
- K56 – Obstrução Intestinal
- K80.3 – Litíase Biliar Obstrutiva
- K85 – Pancreatite Aguda
- N44 – Torção Testicular
- S06 – TCE
- S27/S36 – Trauma Torácico/Abdominal

---

## 📋 Condutas Incluídas (versão privada – `privado.html`)

A versão privada contém **todos os 59 CIDs** listados acima, mas com **exames e tratamentos ajustados** para a realidade de hospitais particulares (RM, angioTC, trombectomia, angioplastia, ecocardiograma transesofágico, etc.). Além disso, **inclui os CIDs que estavam ausentes na versão pública** (ex: A54, B01, B02, B04, B26, B26.0, B86, E86, G43.0, H00.0, H10.9, H83.0, J11, N10, N39, O21, W54, W57) e separa **S27** (Trauma Torácico) e **S36** (Trauma Abdominal) em entradas distintas.

---

## 🛠️ Funcionalidades (ambas as versões)

- ✅ **Busca por CID ou diagnóstico** com filtro simultâneo pelo nível de atendimento.
- ✅ **Catálogo dinâmico** que se adapta ao filtro selecionado.
- ✅ **Edição, exclusão e cadastro** de condutas (dados salvos localmente).
- ✅ **Campo "Observações Importantes"** para lembretes rápidos, diferenciações e prescrições de internação.
- ✅ **Funcionamento offline** (Service Worker).
- ✅ **Botão secreto** (5 toques no título) para exportar dados em JSON (apenas para o administrador).
- ✅ **Ícone na Tela de Início** (PWA) para acesso rápido no iPhone.

---

## 📲 Como instalar no iPhone

1. Acesse o link do app no **Safari** (navegador obrigatório para instalação).
2. Toque no ícone **"Compartilhar"** (quadrado com seta para cima).
3. Role para baixo e toque em **"Adicionar à Tela de Início"**.
4. Confirme o nome e toque em **"Adicionar"**.

Pronto! O app vai aparecer como um ícone na sua tela inicial, funcionando em tela cheia e offline.

---

## ✏️ Como adicionar ou editar condutas

### Pelo próprio app (recomendado)
- Role a tela até a seção **"Cadastrar nova conduta"**.
- Preencha os campos: CID, diagnóstico, exames, tratamento, conduta geral, nível (`AMA`, `UPA`, `PSA`, `Emergencia`), observações, fonte.
- Clique em **Salvar**.

### Editando o arquivo `index.html` ou `privado.html` (avançado)
1. Abra o arquivo correspondente no Bloco de Notas ou editor de código.
2. Localize a lista `protocolsData = [ ... ]` (dentro do `<script>`).
3. Cada conduta é um objeto com os campos:
   - `cid` – Código CID-10.
   - `diag` – Nome do diagnóstico.
   - `setting` – Nível de atendimento (`"AMA"`, `"UPA"`, `"PSA"`, `"Emergência"`).
   - `exames` – Array de exames a solicitar.
   - `tratamento` – Array de tratamentos.
   - `conduta` – Conduta geral (texto).
   - `ref` – Fonte do protocolo (ex: "SBC / SBEM").
4. Adicione, edite ou remova objetos conforme necessário.
5. Salve o arquivo e faça o upload para o GitHub.

---

## 🔄 Como atualizar o app

1. Edite os arquivos no computador.
2. Faça **upload** no GitHub (substituindo os arquivos antigos).
3. No iPhone, abra o app (com internet) e feche – ele vai carregar a versão nova.

---

## 📂 Estrutura do projeto

conduta-medica/
├── index.html # Versão pública (AMA/UPA/PSA/Emergência)
├── privado.html # Versão privada (PSA/Emergência – hospitais particulares)
├── service-worker.js # Habilita o modo offline
├── remume.html # App REMUME (medicamentos)
├── README.md # Este arquivo (documentação)
└── (futuramente) icon/ # Ícones para o PWA

---

## ⚠️ Aviso importante

**Este app é uma ferramenta de apoio à decisão clínica.**  
A conduta final e a responsabilidade pelo paciente são **sempre do médico responsável**.  
O app não substitui o julgamento clínico nem a avaliação presencial do paciente.

---

## 🙏 Agradecimentos

- Secretaria Municipal da Saúde de São Paulo (SMS/SP) – protocolos clínicos.
- Sociedades Brasileiras (SBEM, SBC, SBN, SBU, SBCP, etc.) – diretrizes.
- GitHub Pages – hospedagem gratuita.
- Comunidade de desenvolvedores que compartilhou conhecimento.

---

## 📝 Licença

Este projeto é de uso pessoal e educacional. Sinta-se livre para adaptá-lo às suas necessidades, respeitando os protocolos oficiais e as leis de privacidade.

---

Desenvolvido com 💙 por [K. Marjoub] – para uso próprio no atendimento na rede municipal de saúde e em hospitais particulares.