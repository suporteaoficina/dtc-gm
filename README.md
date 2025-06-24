# 📄 Base de Códigos de Falha DTC GM (descricao_dtc_gm.csv)

Este repositório contém o arquivo `descricao_dtc_gm.csv`, uma tabela de códigos de falha (DTCs) utilizados em veículos da General Motors (GM), com descrições traduzidas para o português.

## ✅ Finalidade

Este CSV é utilizado por um script que converte os códigos de falha extraidos com XbusTrtool para exibir descrições compreensíveis dos códigos.  

## 🧩 Estrutura do CSV

| DTC     | Descrição                         |
|---------|-----------------------------------|
| P0100   | Fluxo de massa de ar - problema   |
| B1000   | Módulo defeituoso                 |
| U0100   | Perda de comunicação com ECM/PCM  |
| ...     | ...                               |

- **Coluna `DTC`**: Código padrão no formato OBD-II (ex: `P0101`, `B1325`, `U1000`, etc).
- **Coluna `Descrição`**: Texto explicativo técnico em português.
