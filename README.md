<div align="center">

<img src="https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/media/image62.png" alt="Ventana Serra - Grupo Arcese" width="300" style="max-width: 300px; height: auto;" />

# Solução de Integração CargoWise 2.0 &bull; ERP Volpe
### Plataforma de Automação Cadastral, Faturamento (AR), Contas a Pagar (AP), Emissão de NFS-e e Gestão Contratual

[![Status: Homologado](https://img.shields.io/badge/Status-Homologado%20em%20Produção-2ea44f?style=for-the-badge&logo=checkmarx&logoColor=white)](#status-da-homologação-no-erp-volpe)
[![Versão 2.0.0](https://img.shields.io/badge/Versão-2.0.0-0052cc?style=for-the-badge)](#visão-geral-do-projeto)
[![Runtime: Node.js / TypeScript](https://img.shields.io/badge/Runtime-Node.js%20%7C%20TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](#arquitetura-e-segurança)
[![Banco: SQL Server](https://img.shields.io/badge/Database-SQL%20Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](#arquitetura-e-segurança)
[![Transacionalidade ACID](https://img.shields.io/badge/Segurança-Transacional%20ACID-blueviolet?style=for-the-badge)](#arquitetura-e-segurança)

<br />

### 📥 Central de Downloads Rápidos (Clique para Baixar)

[![⬇️ Baixar Manual Oficial em PDF](https://img.shields.io/badge/⬇️%20Baixar-Manual%20Oficial%20(PDF)-dc2626?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/Manual_de_Integracao_CargoWise.pdf)
&nbsp;
[![⬇️ Baixar Pacote de JSONs](https://img.shields.io/badge/⬇️%20Baixar-Pacote%20JSON%20(ZIP)-059669?style=for-the-badge&logo=json&logoColor=white)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/payloads_cargowise_json.zip)
&nbsp;
[![🌐 Abrir Apresentação Web](https://img.shields.io/badge/🌐%20Visualizar-Apresentação%20Web%20(HTML)-4f46e5?style=for-the-badge)](Apresentacao_Cliente_CargoWise.html)

<br />

**Portal Executivo de Documentação & Homologação para Clientes e Equipes Operacionais**

---

</div>

## 📌 Documentação Oficial & Downloads Individuais

Para download direto de qualquer arquivo de especificação ou exemplo prático de teste, utilize a tabela abaixo:

| Arquivo / Recurso | Tipo | Descrição | Tamanho | Ação de Download |
| :--- | :---: | :--- | :---: | :---: |
| 📕 **Manual de Integração CargoWise (PDF)** | `PDF` | Documento executivo oficial diagramado em alta resolução | ~1.3 MB | [![Baixar PDF](https://img.shields.io/badge/Download-PDF-dc2626?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/Manual_de_Integracao_CargoWise.pdf) |
| 📦 **Pacote Completo de Payloads JSON (ZIP)** | `ZIP` | **Todos os 7 payloads de teste** empacotados em um único arquivo | ~21 KB | [![Baixar ZIP](https://img.shields.io/badge/Download-ZIP-059669?style=flat-square&logo=zip&logoColor=white)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/payloads_cargowise_json.zip) |
| 📄 `01_account_parceiro_nacional_request.json` | `JSON` | Payload de cadastro/vínculo no CadÚnico (`POST /Account`) | 521 B | [![Baixar JSON](https://img.shields.io/badge/Download-JSON-orange?style=flat-square)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/json/01_account_parceiro_nacional_request.json) |
| 📄 `01_ap_fatura_padrao_request.json` | `JSON` | Payload fatura AP padrão com frete internacional (`POST /AP`) | 2.5 KB | [![Baixar JSON](https://img.shields.io/badge/Download-JSON-orange?style=flat-square)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/json/01_ap_fatura_padrao_request.json) |
| 📄 `02_ap_fatura_padrao_request.json` | `JSON` | Payload alternativo de AP com rateio contábil (`POST /AP`) | 2.5 KB | [![Baixar JSON](https://img.shields.io/badge/Download-JSON-orange?style=flat-square)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/json/02_ap_fatura_padrao_request.json) |
| 📄 `02_ar_faturamento_nfse_request.json` | `JSON` | Faturamento AR com NFS-e e retenções (`POST /AR`) | 4.9 KB | [![Baixar JSON](https://img.shields.io/badge/Download-JSON-orange?style=flat-square)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/json/02_ar_faturamento_nfse_request.json) |
| 📄 `03_ap_fatura_multiprocesso_real.json` | `JSON` | Caso real: 262 taxas em 58 processos (R$ 431k homologados) | 567 KB | [![Baixar JSON](https://img.shields.io/badge/Download-JSON-orange?style=flat-square)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/json/03_ap_fatura_multiprocesso_real.json) |
| 📄 `04_ar_faturamento_nfse_request.json` | `JSON` | Faturamento AR com Reforma Tributária IBS/CBS (`POST /AR`) | 4.9 KB | [![Baixar JSON](https://img.shields.io/badge/Download-JSON-orange?style=flat-square)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/json/04_ar_faturamento_nfse_request.json) |
| 📄 `05_contract_vinculo_request.json` | `JSON` | Vínculo de contrato comercial, IE e KAM (`POST /Contract`) | 224 B | [![Baixar JSON](https://img.shields.io/badge/Download-JSON-orange?style=flat-square)](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/json/05_contract_vinculo_request.json) |
| 🌐 **Apresentação Executiva Standalone** | `HTML` | Visualização limpa em tela cheia para clientes sem GitHub | ~15 KB | [![Abrir HTML](https://img.shields.io/badge/Visualizar-HTML-4f46e5?style=flat-square)](Apresentacao_Cliente_CargoWise.html) |

> [!TIP]
> **Dica para o Cliente:** Clicando em qualquer botão de download acima, o arquivo é aberto ou baixado diretamente para a sua máquina.

---

## 🎯 Visão Geral do Projeto

A **API CargoWise 2.0** é o ecossistema de integração desenvolvido para conectar de forma bidirecional e automatizada a operação global de agenciamento de cargas no **CargoWise** ao ecossistema corporativo e fiscal do **ERP Volpe** da **Ventana Serra (Grupo Arcese)**.

```mermaid
flowchart LR
    CW["🌐 CargoWise One<br/>(Operação Global)"] -->|"JSON / HTTPS<br/>(Bearer Token)"| API["⚙️ API Ventana CargoWise 2.0<br/>(Node.js / Plata Runtime)"]
    API -->|"Transações ACID<br/>(Rollback Total)"| VOLPE[("🏢 ERP Volpe<br/>(SQL Server)")]
    VOLPE --> CAD["👥 CadÚnico (Parceiros)"]
    VOLPE --> FIN["💰 Financeiro (AP & AR)"]
    VOLPE --> FIS["🧾 Fiscal (NFS-e & RPS)"]
    VOLPE --> OP["🚢 Operacional (Processos)"]

    classDef cw fill:#0b3c5d,stroke:#072a42,stroke-width:2px,color:#ffffff;
    classDef api fill:#0052cc,stroke:#0747a6,stroke-width:2px,color:#ffffff;
    classDef volpe fill:#00875a,stroke:#006644,stroke-width:2px,color:#ffffff;
    classDef dest fill:#f4f5f7,stroke:#c1c7d0,stroke-width:1px,color:#172b4d;
    class CW cw;
    class API api;
    class VOLPE volpe;
    class CAD,FIN,FIS,OP dest;
```

### 💼 Benefícios e Ganhos de Negócio

* ⚡ **Eliminação Total de Digitação Manual:** Sincronização automática de parceiros, conhecimentos de frete, despesas operacionais e notas de débito.
* 🛡️ **Conformidade Fiscal e Reforma Tributária:** Mapeamento integral dos tributos retidos federais e municipais (ISS, PIS, COFINS, IRRF, CSLL) e suporte preparado para a transição do **IBS/CBS**.
* 🔒 **Segurança Transacional ACID:** Todas as operações que afetam múltiplos módulos realizam validação integral. Se qualquer validação fiscal falhar, 100% da transação sofre *rollback*, impedindo a geração de títulos órfãos ou notas fiscais desvinculadas.
* 💱 **Gestão Eficiente de Câmbio e Moedas Estrangeiras:** Conversão precisa de montantes em moedas como USD e EUR pela taxa oficial enviada, aplicando rateios corretos por centro de custo e processo operacional (*Shipment*).
* 🔄 **Ciclo Completo com Suporte a Estornos:** Tratamento nativo de cancelamentos e notas de crédito (`creditNote: true`), liquidando e estornando contas no ERP Volpe de forma espelhada ao CargoWise.

---

## 🏗️ Arquitetura e Segurança

A solução foi projetada sob padrões corporativos de alta resiliência e desempenho:

<div align="center" style="margin: 20px 0;">
  <a href="https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/media/diagram_mermaid_1.svg" target="_blank">
    <img src="https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/media/diagram_mermaid_1.png" alt="Arquitetura Técnica do Sistema" style="width: 100%; max-width: 950px; border: 1px solid #d0d7de; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.06);" />
  </a>
  <p style="font-size: 0.85em; color: #57606a; margin-top: 6px;">
    <i>Figura 1: Arquitetura Técnica, Plata Runtime e Transacionalidade ACID no ERP Volpe</i>
  </p>
</div>

* **Engine:** Node.js com TypeScript sob o framework corporativo `pwi-plata-type`.
* **Banco de Dados:** Microsoft SQL Server com consultas parametrizadas (*Query Builder* imune a SQL Injection).
* **Autenticação:** Header HTTP `x-access-token` com token seguro Bearer individualizado por ambiente.
* **Fail-Fast & Validação Estrutural:** O payload é inspecionado contra tipagens rígidas antes da abertura de locks transacionais no banco de dados.

---

## 🚀 Módulos e Endpoints Disponíveis

A integração abrange todo o fluxo operacional, financeiro e comercial:

| Módulo | Endpoint | Método | Descrição Executiva | Tabelas Volpe Afetadas |
| :--- | :--- | :---: | :--- | :--- |
| **Parceiros** | `/v1/cargowise/Account` | `POST` | Cadastro unificado anti-duplicidade de clientes, fornecedores e agentes internacionais | `TB_CADUNICO`, `TB_CIDADES` |
| **Contas a Pagar** | `/v1/cargowise/AP` | `POST` | Inclusão de faturas de custos de armadores, agentes e prestadores com rateio contábil | `FI_MOVFIN`, `FI_MOVRAT`, `AG_PROCESSOTAXAS` |
| **Faturamento & NFS-e** | `/v1/cargowise/AR` | `POST` | Emissão de faturas a clientes, desdobramento de reembolsos e geração de NFS-e fiscal | `AG_FATURADO`, `FT_NSERVICOS`, `FT_NSITENS`, `FI_MOVFIN` |
| **Contratos** | `/v1/cargowise/Contract` | `POST` | Associação de número contratual, Inscrição Estadual e representante comercial (KAM) | `CW_CONTRATO`, `TB_CADUNICO` |
| **Monitoramento** | `/v1/version` | `GET` | Health Check em tempo real para monitorar status da API e conexão ao banco | Auditoria / Monitoramento |

---

## 📊 Status da Homologação no ERP Volpe

Todos os cenários operacionais foram homologados com dados reais e encontram-se certificados:

```
[✔] Cadastro de Parceiro Nacional com CNPJ e Regime Tributário      -> Validado (ID 36268)
[✔] Cadastro de Parceiro Internacional (NIF / Endereço Exterior)     -> Validado
[✔] Fatura AP Padrão com Rateio e Frete Internacional               -> Validado (ID 14008)
[✔] Fatura AP Multi-Processos (262 taxas, 58 processos, R$ 431k)    -> Validado (ID 1953450)
[✔] Estorno de Fatura AP com baixa e reversão financeira             -> Validado (FI_BAIXAS)
[✔] Faturamento AR com Emissão Automática de NFS-e / RPS             -> Validado (ID 80031)
[✔] Tratamento de Isenções e Reforma Tributária (IBS/CBS)           -> Validado
[✔] Vínculo Contratual Comercial com Representante KAM               -> Validado (ID 14022)
```

### 📸 Evidências Reais de Homologação

<div align="center" style="margin: 20px 0;">
  <img src="https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/media/volpe_ap_contas_a_pagar_real.jpg" alt="Fatura Multi-Processos Homologada no ERP Volpe" style="width: 100%; max-width: 900px; border: 1px solid #d0d7de; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.06);" />
  <p style="font-size: 0.85em; color: #57606a; margin-top: 6px;">
    <i>Figura 2: Homologação no ERP Volpe — Processamento de Fatura AP Complexa com 58 processos e 262 itens de taxa</i>
  </p>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/media/image58.png" alt="Cadastro de Parceiro Homologado em TB_CADUNICO" style="width: 100%; max-width: 900px; border: 1px solid #d0d7de; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.06);" />
  <p style="font-size: 0.85em; color: #57606a; margin-top: 6px;">
    <i>Figura 3: Homologação no ERP Volpe — Mapeamento Automático do Parceiro na tabela mestre TB_CADUNICO</i>
  </p>
</div>

---

## 🧪 Como Realizar Testes e Homologações

Para enviar requisições de teste à API, baixe o pacote [`payloads_cargowise_json.zip`](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/payloads_cargowise_json.zip) ou use os arquivos da pasta [`json/`](https://raw.githubusercontent.com/MatheusRafaelPWI/Ventana_node_ApiCargoWise2.0/main/json/):

### Cabeçalhos HTTP Obrigatórios
```http
POST /v1/cargowise/Account HTTP/1.1
Host: api.ventanaserrabrasil.com.br
Content-Type: application/json
x-access-token: Bearer SEU_TOKEN_AUTORIZADO
```

### Exemplo Rápido: Verificação de Disponibilidade
```bash
curl -X GET "https://api.ventanaserrabrasil.com.br/v1/version"
```

**Resposta:**
```json
{
  "status": 200,
  "version": "2.0.0",
  "service": "Ventana_node_ApiCargoWise2.0",
  "database": "ONLINE"
}
```

---

## 💼 Informações Corporativas & Suporte

* **Cliente:** Ventana Serra do Brasil / Grupo Arcese
* **Desenvolvimento & Integração:** PWI Tecnologia
* **Ambiente Atual:** Homologação / Produção
* **Repositório:** `Ventana_node_ApiCargoWise2.0`

> Para dúvidas técnicas, credenciais de homologação ou solicitações de customização, contate a equipe técnica responsável.

---

<div align="center">
  <sub>Ventana Serra &bull; Grupo Arcese &bull; PWI Tecnologia &copy; 2026 Todos os direitos reservados.</sub>
</div>
