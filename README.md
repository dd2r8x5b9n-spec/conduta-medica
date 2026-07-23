# 🏥 Conduta Médica – AMA/SP

App de apoio à decisão clínica para o primeiro atendimento nas AMAs da Prefeitura de São Paulo.

---

## 📱 Apps disponíveis

| App | Descrição | Acesso |
|-----|-----------|--------|
| **Conduta Médica** | Protocolos e condutas para atendimento ambulatorial | [Abrir](https://dd2r8x5b9n-spec.github.io/conduta-medica/) |
| **REMUME – Medicamentos SP** | Consulta rápida de medicamentos disponíveis na rede municipal (UBS + AMA) | [Abrir](https://dd2r8x5b9n-spec.github.io/conduta-medica/remume.html) |

---

## 💊 REMUME – Relação Municipal de Medicamentos

- Lista atualizada com base na REMUME da SMS-SP (junho/2026).
- Inclui medicamentos orais, injetáveis, inaláveis, oftálmicos e tópicos.
- Filtros por grupo terapêutico, local (UBS/AMA), via de administração e popularidade.
- Busca inteligente por nome (prioriza o início do termo).
- Modo escuro e favoritos (salvos localmente).

---

## 🛠️ Tecnologias

- React (via CDN)
- Babel (para JSX no navegador)
- GitHub Pages (hospedagem)

---

## 📂 Estrutura do repositório

conduta-medica/
├── index.html          # App Conduta Médica
├── remume.html         # App REMUME (medicamentos)
├── service-worker.js   # (opcional, para PWA)
└── README.md

---

## 🔄 Atualização

Os dados da REMUME são atualizados manualmente sempre que a prefeitura divulga nova versão (geralmente 2 vezes ao ano). Para atualizar, edite o arquivo `remume.html` e substitua a lista de medicamentos.

---

## 📄 Licença

Uso interno e educacional – dados provenientes da Secretaria Municipal da Saúde de São Paulo.