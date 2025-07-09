# Projeto de Banco de Dados - Restaurante (MySQL)

Este projeto foi desenvolvido como parte da formação em **Análise de Dados**, com foco em modelagem e manipulação de banco de dados utilizando **MySQL**.

## 💡 Descrição do Projeto

O sistema simula o funcionamento de um restaurante fictício. Nele, foram implementadas tabelas relacionais para gerenciar:

- Funcionários
- Clientes
- Produtos e suas informações
- Pedidos

Além da estrutura, foram aplicadas **consultas SQL** que exploram filtros, ordenações, joins, subconsultas, views e funções personalizadas.

## 📌 Objetivos de Aprendizado

Durante o projeto, as seguintes competências foram adquiridas:

✅ Diferenciar e aplicar tipos de bancos de dados conforme as necessidades específicas de cada aplicação  
✅ Compreender e instalar sistemas de gerenciamento de banco de dados (SGBDs) relacionais  
✅ Utilizar comandos SQL para manipulação e administração de dados  
✅ Garantir integridade e eficiência dos dados com DDL, DML, DQL, DCL e DTL  
✅ Criar e utilizar views e funções SQL para automatizar e otimizar consultas  
✅ Aplicar boas práticas com foco em segurança e conformidade com a LGPD  

## 🛠️ Tecnologias Utilizadas

- **MySQL**
- **Workbench** ou **DBeaver** (ou outro SGBD compatível)
- Linguagem SQL padrão ANSI

## 🗃️ Estrutura de Tabelas

- `funcionarios`
- `clientes`
- `produtos`
- `info_produtos`
- `pedidos`
- `backup_pedidos` (cópia de segurança)
- `resumo_pedido` (view de join entre tabelas)

## 🔍 Exemplos de Consultas Implementadas

- Seleção de clientes com nomes iniciados por letra específica
- Filtros por status de pedidos
- Joins entre múltiplas tabelas para relatórios
- Agregações com `GROUP BY`, `AVG`, `SUM`, `COUNT`
- Ranking de produtos mais caros
- Uso de `CASE` e `IFNULL`
- Criação de `VIEW` com total de pedidos
- Funções SQL personalizadas com `CREATE FUNCTION`

## ⚙️ Funções Criadas

```sql
-- Retorna os ingredientes de um produto
SELECT BuscaIngredientesProduto(10);

-- Compara o valor de um pedido com a média geral
SELECT mediaPedido(6);
```

## 📊 Exemplos de Insights

- Produtos mais vendidos e seus valores
- Clientes com maior volume de pedidos
- Fornecedores com mais produtos ativos
- Média de preços por categoria
- Pedidos com status pendente ou cancelado

## 📎 Como Executar

1. Copie o script completo do projeto (`.sql`)
2. Cole no seu ambiente MySQL (ex: MySQL Workbench)
3. Execute bloco a bloco para criação das tabelas, inserção de dados, views e funções
4. Teste as consultas propostas

## 👨‍💻 Autor

**Leonardo da Cunha Ramos**  
Projeto acadêmico desenvolvido durante curso de Análise de Dados com foco prático em banco de dados relacional.

---

📫 Para dúvidas, sugestões ou colaborações: [Seu LinkedIn ou GitHub aqui]





