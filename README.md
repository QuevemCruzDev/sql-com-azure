# sql-com-azure
# Projeto: Criação de Banco de Dados SQL no Azure

## 📌 Descrição
Este projeto tem como objetivo demonstrar o processo de criação de um **Banco de Dados SQL** no **Microsoft Azure**, incluindo a configuração básica, rede, segurança e revisão final solicitado como desafio de projeto na Dio.

---

## 🎯 Objetivo
Provisionar um banco de dados SQL no Azure

---

## 🛠 Ferramentas Utilizadas
- **Microsoft Azure**
- **Banco de Dados SQL do Azure**

---

## ✅ Etapas do Projeto

### 1️⃣ Configuração Básica
Na primeira etapa, foram definidos:
- **Assinatura**: Azure subscription 1
- **Grupo de recursos**: `estudos`
- **Nome do banco de dados**: `estudos`
- **Servidor**: `configuandosqlnewz (West US 2)`
- **Ambiente de trabalho**: Desenvolvimento
- **Camada de serviço**: Uso Geral – Sem servidor
- **Armazenamento de backup**: Redundância geográfica

![Tela de Configuração Básica](/imagens/img-1.PNG)

---

### 2️⃣ Configuração de Rede
- **Método de conectividade**: Sem acesso
- **Permitir que serviços e recursos do Azure acessem este servidor**: Não
- **Adicionar o endereço IP do cliente atual**: Não
- **Política de conexão**: Padrão
- **Versão mínima do TLS**: TLS 1.2

![Tela de Configuração de Rede](/imagens/img-2.PNG)

---

### 3️⃣ Revisão e Criação
- **Custo estimado**: 4,78 USD/mês + custo de computação
- **Localização**: West US 2
- **Redundância do backup**: Armazenamento de backup com redundância geográfica
- **Política de conexão**: Default
- **Segurança**: Transparent Data Encryption (ativado por padrão)

![Tela de Revisão](/imagens/img-3.PNG)

---

## 🔐 Configurações de Segurança
- **Criptografia (TDE)**: Ativada automaticamente
- **Conexões criptografadas (TLS)**: TLS 1.2 obrigatório
- **Firewall**: Acesso negado para IP externo por padrão

---

## 📂 Estrutura do Projeto

/projeto-criacao-bd-sql-azure

├── img-1.PNG # Configuração Básica

├── img-2.PNG # Configuração de Rede

├── img-3.PNG # Revisão e Criação

└── README.md # Documentação do projeto


## Conclusão
De forma fácil e intuitiva, podemos gerar um servidor de banco de dados e personalizá-lo de modo adequado às nossas necessidades rapidamente com as ferramentas de nuvem da Azure. Devemos sempre ressaltar a necessidade de observar os custos relacionados e se atendem às expectativas.