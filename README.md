# 📋 Conduta Médica – AMA/UPA/PSA/Emergência

**App de apoio à decisão clínica para atendimento na rede municipal de São Paulo, com filtros por nível de complexidade e diferenciação de condutas baseadas em protocolos da SMS/SP.**

> ⚠️ Este é um app pessoal, desenvolvido para consulta rápida durante o plantão, com base em protocolos oficiais da Secretaria Municipal da Saúde de São Paulo.

---

## 🚀 Acesse o app

[https://dd2r8x5b9n-spec.github.io/conduta-medica/](https://dd2r8x5b9n-spec.github.io/conduta-medica/)

---

## 🏥 Níveis de Atendimento (Filtros)

O app permite filtrar as condutas por nível de atendimento, facilitando a decisão clínica conforme o local de atuação:

| Nível | Descrição |
|-------|-----------|
| **📋 Todos** | Exibe todas as condutas cadastradas. |
| **🏥 AMA** | Condutas resolutivas na Atenção Básica (estabilização e encaminhamento). |
| **🚑 UPA** | Condutas para Unidade de Pronto Atendimento (diagnóstico, estabilização e internação breve). |
| **🏨 PSA** | Condutas hospitalares (em desenvolvimento). |
| **🚨 Emergência** | Condutas para situações de risco iminente (IAM, AVC, Sepse, etc.). |

---

## 🩺 Diferenciações Clínicas Incluídas

| CID | Diagnóstico | Diferenciação |
|-----|-------------|---------------|
| **I21** | Infarto Agudo do Miocárdio (IAM) | 🔹 IAM com supra ST (trombólise/ICP)<br>🔹 IAM sem supra ST (estratificação de risco)<br>🔹 Bloqueio de ramo novo (tratar como supra) |
| **I64** | Acidente Vascular Cerebral (AVC) | 🔹 AVC isquêmico (janela de trombólise)<br>🔹 AVC hemorrágico (controle pressórico, neurocirurgia) |
| **E16** | Hipoglicemia | 🔹 Hipoglicemia leve/moderada (carboidrato rápido)<br>🔹 Hipoglicemia grave (glicose EV/Glucagon)<br>🔹 Suspeita de insulinoma (encaminhamento endocrinológico) |

---

## 📋 Condutas Incluídas (43 CIDs)

| CID | Diagnóstico | Nível |
|-----|-------------|-------|
| A54 | Gonorreia | AMA |
| A90 | Dengue | AMA |
| B01 | Varicela | AMA |
| B02 | Herpes Zoster | AMA |
| B04 | Mpox | UPA |
| B26 | Caxumba | AMA |
| B26.0 | Orquite por Caxumba | UPA |
| B86 | Escabiose | AMA |
| E16 | Hipoglicemia (com insulinoma) | AMA |
| G40 | Crise Epiléptica | Emergência |
| G43.0 | Enxaqueca sem aura | AMA |
| G03.9 | Meningite (suspeita) | Emergência |
| H00.0 | Hordéolo | AMA |
| H10.9 | Conjuntivite | AMA |
| H83.0 | Labirintite | AMA |
| I10 | Hipertensão Arterial | AMA |
| I16 | Crise Hipertensiva | Emergência |
| I21 | IAM (com diferenciação) | Emergência |
| I50 | Insuficiência Cardíaca | UPA |
| I64 | AVC (isquêmico/hemorrágico) | Emergência |
| I80.9 | TVP | UPA |
| I71.0 | Dissecção de Aorta | Emergência |
| I67.1 | Aneurisma Cerebral | Emergência |
| J11 | Síndrome Gripal / Dengue | AMA |
| J44 | Exacerbação de DPOC / Asma | AMA |
| K81.0 | Colecistite | UPA |
| N23 | Cólica renal | AMA |
| N39 | ITU | AMA |
| N94.6 | Dismenorreia | AMA |
| O14 | Pré-eclâmpsia | Emergência |
| O21 | Hiperêmese Gravídica | AMA |
| R04.0 | Epistaxe | AMA |
| R06.0 | Dispneia | AMA |
| R07.4 | Dor Torácica | AMA |
| R10.0 | Abdômen Agudo | AMA |
| R42 | Tontura | AMA |
| R51 | Cefaleia | AMA |
| R65.2 | Sepse | Emergência |
| T63 | Acidente por animal peçonhento | UPA |
| T78.2 | Choque anafilático | Emergência |
| U07.1 | COVID-19 | AMA |
| W54 | Mordedura de cão | AMA |
| W57 | Picada de inseto | AMA |

---

## 🛠️ Funcionalidades

- ✅ **Busca por CID ou diagnóstico** com filtro simultâneo pelo nível de atendimento.
- ✅ **Catálogo dinâmico** que se adapta ao filtro selecionado.
- ✅ **Edição, exclusão e cadastro** de condutas (dados salvos localmente).
- ✅ **Campo "Observações Importantes"** para lembretes rápidos, tabelas e diferenciações.
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
- Preencha os campos (CID, diagnóstico, exames, tratamento, conduta geral, nível, observações, fonte).
- Clique em **Salvar**.

### Editando o arquivo `index.html`
- Abra o arquivo `index.html` no Bloco de Notas.
- Localize a lista `condutas = [ ... ]` e adicione/edite os objetos.
- Salve e faça upload no GitHub.

---

## 🔄 Como atualizar o app

1. Edite os arquivos no computador.
2. Faça **upload** no GitHub (substituindo os arquivos antigos).
3. No iPhone, abra o app (com internet) e feche – ele vai carregar a versão nova.

---

## 📂 Estrutura do projeto
