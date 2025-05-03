# Pipeline ADF - Exportando Tabela para Blob Storage

## 🚀 O que esse pipeline faz?

Esse pipeline do **Azure Data Factory** foi criado pra pegar os dados da tabela dbo.employee (que está em um banco SQL Server) e salvar tudo num arquivo .txt lá no **Blob Storage**, na pasta/camada chamada **bronze**.

---
---
![prints_dio](https://github.com/user-attachments/assets/a026f9d4-0019-4bae-bbd0-8f761f5585bc)

---

## 🛠️ O que foi usado

- Azure Data Factory
- Azure SQL Server
- Azure Blob Storage

---

## 🔄 Como o fluxo funciona

1. **Fonte dos dados**: Tabela dbo.employee do banco SQL Server.
2. **Destino**: Um arquivo .txt no Blob Storage.
3. **Formato**: Arquivo de texto simples, separado por vírgulas (CSV disfarçado de .txt mesmo 😄).
4. **Nome do arquivo**: dbo.employee.txt


