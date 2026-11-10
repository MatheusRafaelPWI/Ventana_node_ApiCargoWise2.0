# Catálogo de Payloads JSON — CargoWise 2.0

Esta pasta armazena todos os payloads de requisição dos endpoints da API CargoWise 2.0 desacoplados da documentação impressa (Word e PDF) e dos manuais para garantir máxima legibilidade e organização:

1. **`01_account_parceiro_nacional_request.json`**: Payload de criação/vinculação de parceiro nacional no CadÚnico (`POST /v1/cargowise/Account`).
2. **`02_ap_fatura_padrao_request.json`**: Payload de inclusão de fatura AP padrão com frete internacional e rateio contábil (`POST /v1/cargowise/AP`).
3. **`03_ap_fatura_multiprocesso_real.json`**: Payload real homologado no ERP Volpe contendo 262 itens de encargos em 58 processos operacionais (Invoice `00062840MAT4` / ID `1953450` / R$ 431.339,31).
4. **`04_ar_faturamento_nfse_request.json`**: Payload completo de faturamento AR com emissão de NFS-e, retenções federais/municipais e Reforma Tributária IBS/CBS (`POST /v1/cargowise/AR`).
5. **`05_contract_vinculo_request.json`**: Payload de vínculo de contrato comercial, Inscrição Estadual e representante KAM (`POST /v1/cargowise/Contract`).

> **Nota Operacional:** As respostas da API (`HTTP 200`, `HTTP 400`, `HTTP 401`) e dados de integridade de versão são mantidos diretamente no corpo dos manuais para consulta e validação imediata.
