# 📋 Conduta Médica – AMA/SP

**App de apoio à decisão clínica para o primeiro atendimento nas AMAs da Prefeitura de São Paulo.**

> ⚠️ Este é um app pessoal, baseado em protocolos oficiais da SMS/SP, desenvolvido para consulta rápida durante o plantão.

---

## 🚀 Acesse o app

[https://dd2r8x5b9n-spec.github.io/conduta-medica/](https://dd2r8x5b9n-spec.github.io/conduta-medica/)

---

## 📱 Funcionalidades

- ✅ Busca por **CID** ou **diagnóstico**
- ✅ Exibição resumida de **exames, tratamento e conduta geral**
- ✅ Indicação clara se o caso **resolve na AMA** ou **precisa ser encaminhado** para UPA/PSA
- ✅ Cadastro, edição e exclusão de condutas (dados salvos localmente)
- ✅ Funciona **offline** (após o primeiro acesso com internet)
- ✅ Ícone na Tela de Início do iPhone (PWA)

---

## 🏥 Condutas incluídas

Atualmente, o app contém protocolos para as seguintes condições (CID):

| CID | Diagnóstico |
|-----|-------------|
| I10 | Hipertensão Arterial Sistêmica |
| I50 | Insuficiência Cardíaca |
| I21 | Infarto Agudo do Miocárdio (IAM) |
| I64 | Acidente Vascular Cerebral (AVC) |
| I16 | Crise Hipertensiva |
| G40 | Crise Epiléptica |
| J44 | Exacerbação de DPOC / Asma |
| J11 | Síndrome Gripal / Dengue |
| N39 | Infecção do Trato Urinário (ITU) |
| E16 | Hipoglicemia |
| T14 | Trauma Leve |
| A54 | Gonorreia |
| B02 | Herpes Zoster |
| H10.9 | Conjuntivite |
| G43.0 | Enxaqueca sem aura |
| N23 | Cólica renal |
| K81.0 | Colecistite aguda |
| T78.4 | Alergia não especificada |

> 📌 *As condutas são baseadas nos protocolos da Secretaria Municipal de Saúde de São Paulo – SMS/SP.*

---

## 🛠️ Tecnologias

- HTML5, CSS3, JavaScript puro (sem frameworks)
- **localStorage** para persistência dos dados
- **Service Worker** para funcionamento offline
- **GitHub Pages** para hospedagem

---

## 📲 Como instalar no iPhone

1. Acesse o link do app no **Safari** (não use Chrome)
2. Toque no ícone **"Compartilhar"** (quadrado com seta para cima)
3. Role para baixo e toque em **"Adicionar à Tela de Início"**
4. Confirme o nome e toque em **"Adicionar"**

Pronto! O app vai aparecer como um ícone na sua tela inicial, funcionando em tela cheia e offline.

---

## ✏️ Como adicionar ou editar condutas

### Pelo próprio app (recomendado)
- Role a tela até a seção **"Cadastrar nova conduta"**
- Preencha os campos (CID, diagnóstico, exames, tratamento, conduta geral, fonte)
- Clique em **Salvar**

### Editando o arquivo `index.html`
- Abra o arquivo `index.html` no Bloco de Notas
- Localize a lista `condutas = [ ... ]` e adicione/edite os objetos
- Salve e faça upload no GitHub

---

## 🔄 Como atualizar o app

1. Edite os arquivos no computador
2. Faça **upload** no GitHub (substituindo os arquivos antigos)
3. No iPhone, abra o app (com internet) e feche – ele vai carregar a versão nova

---

## 📂 Estrutura do projeto

conduta-medica/
    index.html    # Página principal do app
    service-worker.js    # Habilita o modo offline
    README.md    # Este arquivo
    (futuramente) icon/    # Ícones para o PWA


---

## ⚠️ Aviso importante

**Este app é uma ferramenta de apoio à decisão clínica.**  
A conduta final e a responsabilidade pelo paciente são **sempre do médico responsável**.  
O app não substitui o julgamento clínico nem a avaliação presencial do paciente.

---

## 🙏 Agradecimentos

- Secretaria Municipal da Saúde de São Paulo (SMS/SP) – protocolos clínicos
- GitHub Pages – hospedagem gratuita
- Comunidade de desenvolvedores que compartilhou conhecimento

---

## 📝 Licença

Este projeto é de uso pessoal e educacional. Sinta-se livre para adaptá-lo às suas necessidades, respeitando os protocolos oficiais e as leis de privacidade.

---

Desenvolvido com 💙 por [K. Marjoub] – para uso próprio no atendimento na AMA.
