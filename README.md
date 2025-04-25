# :rocket: DIO_DATABRICKS  
## Bootcamp DIO – Microsoft AI for Tech – Azure Databricks  

---

##  Desafio de Projeto: Criando e Administrando recursos no Azure Data Factory

### :brain: Aprendizagem de recursos e projetos no Microsoft Azure!

Após realizar a inscrição da assinatura no portal Azure, irei criar uma unidade **Data Factory**, um serviço ETL baseado em nuvem que oferece melhor integração entre os dados.

---

## Etapas do Projeto


Na interface inicial, visualizamos a tela de criação do projeto.  
-> Para o preenchimento da coluna **"Assinatura"**, deve-se selecionar a assinatura correspondente do indivíduo. No meu caso: `Azure Subscription 1`.

---

![image](https://github.com/user-attachments/assets/1195cff4-0e37-41f6-9a0a-4306522634a8)

---

### Grupo de Recursos

Criei o Grupo de Recursos com o nome `DIO_DATABRICKS`, com o objetivo de facilitar a identificação e manter a estrutura do projeto mais organizada e padronizada.

---
![image](https://github.com/user-attachments/assets/dc786893-5915-44ff-aedb-bab7e9939624)
---

### :clipboard: Detalhes da Instância

- **Nome:** Nome da instância criada → `DF-DIO-Daniell`
- **Região:** `EAST US`  
  _A escolha da região impacta diretamente a disponibilidade e os serviços locais._
- **Versão:** `V2` do Azure Data Factory

---
![image](https://github.com/user-attachments/assets/29451232-9c06-479e-a00e-9550daf543a0)
---

### :dna: Integração com Git

Nesta etapa, é possível conectar um repositório GitHub ou Azure DevOps.  
> Optei por não configurar neste momento.

---
![image](https://github.com/user-attachments/assets/9cb321c5-33c4-459d-ae12-299e15e44b2b)
---

### :globe_with_meridians: Configurações de Rede

Optei por configurar como **Público**.  
-> Em redes privadas, a comunicação permanece na rede da Microsoft, aumentando segurança e reduzindo latência.

---
![image](https://github.com/user-attachments/assets/73b160b0-1cb3-4b4c-9130-a54c94014fdf)
---

### :closed_lock_with_key: Criptografia

O Azure Data Factory oferece criptografia em trânsito e em repouso, com integração ao **Azure Key Vault**.  
> Neste projeto, a criptografia foi deixada desabilitada.

---
![image](https://github.com/user-attachments/assets/44bbcc4e-5602-4868-8caa-e5b4c0c7e39a)
---

### :label: Marcas (Tags)

As tags permitem classificar recursos e consolidar faturamento.  
-> Recurso importante para organização em ambientes corporativos.

---
![image](https://github.com/user-attachments/assets/d8b4b30f-9aa3-4ee6-99e8-21a99e29abf1)
---

### Finalização

Após validar todas as configurações e personalizações, o projeto foi criado com sucesso clicando na opção **"Criar"**.

---
![image](https://github.com/user-attachments/assets/96f62ce0-52db-4a4d-9c85-f04e4e6cf629)
---

## :satellite: Extração de Dados via HTTP com Pipelines no Azure Databricks

### Objetivo

Criar um pipeline de dados no **Azure Databricks** que:

- Realiza requisições HTTP a uma API
- Trata e transforma os dados 
- Converte os dados em um schema estruturado 
- Armazena os dados transformados no **Azure Blob Storage** 

---

### :movie_camera: Vídeo Demonstrativo

https://github.com/user-attachments/assets/1da8cd03-8505-4fa7-b97a-1f73bc03ded3



---

## :bar_chart: Métricas de Monitoramento – Azure Blob Storage

### Métrica analisada: `Transactions`

- **Período de Baixa Atividade:**  
  Período inicial sem transações indica inatividade.

- **Pico de Atividade:**  
  Transações aumentam repentinamente, alcançando até **44 transações**. Pode indicar eventos de carga.

- **Flutuações:**  
  Atividade variável após o pico, indicando padrões distintos de uso.

> :pushpin: Esses dados ajudam a otimizar custos e desempenho do Azure Blob.

---
