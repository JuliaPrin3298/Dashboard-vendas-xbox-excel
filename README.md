# 🎮 Dashboard de Vendas - Xbox Game Pass

## 🌟 Sobre este Projeto
Este projeto representa um marco importante na minha jornada de análise de dados: **é o primeiro dashboard profissional que desenvolvi.
**

Projeto prático voltado à criação de uma dashboard utilizando uma base de dados hipotética de assinaturas de serviços digitais.

---

## 📋 Funcionalidades
O dashboard consolida dados brutos e os transforma em visualizações estratégicas, permitindo acompanhar:
- **Receita Total:** Valor das assinaturas somado aos *Season Passes* (EA Play e Minecraft).
- **Mix de Produtos:** Distribuição entre planos Core, Standard e Ultimate.
- **Retenção:** Análise de clientes com renovação automática ativa vs. inativa.
- **Crescimento:** Evolução da base de assinantes ao longo de 2024.

---

## 🗂 Estrutura do Arquivo
Para garantir a organização e as boas práticas de modelagem de dados, o arquivo foi dividido em 4 abas estratégicas:

### 1. 🎨 A̳ssets (Ativos Visuais)
Define a identidade visual do projeto, garantindo consistência com a marca Xbox.
- **Conteúdo:** Paleta de cores hexadecimais (ex: `#9BC848` para o verde característico) e ícones.

### 2. 🗃️ B̳ases (Base de Dados)
Contém o registro transacional bruto de todos os assinantes (Jan/2024 - Dez/2024).
- **Estrutura:** Cada linha representa um cliente único.
- **Colunas Chave:** `Subscriber ID`, `Plan`, `Auto Renewal`, `Total Value`.

### 3. 🧮 C̳álculos (Motor de Análise)
Aba responsável pelo processamento dos dados ("Back-end").
- **Técnica:** Utilização de Tabelas Dinâmicas para agregar dados da aba *Bases*.
- **KPIs Gerados:** Contagens de vendas, somas de receita e agrupamentos por período.

### 4. 📊 D̳ashboard (Visualização)
A interface final apresentada ao usuário ("Front-end").
- **Destaque:** Saudação personalizada e cartões de métricas claros.
- **Atualização:** Data de corte e período de cálculo visíveis.

---

## 🚀 Tecnologias e Aprendizados
Neste meu primeiro projeto, apliquei conceitos fundamentais de análise de dados no Excel:
- **Tratamento de Dados:** Estruturação de bases de dados brutas.
- **Tabelas Dinâmicas (Pivot Tables):** Para sumarização ágil de informações.
- **Fórmulas de Negócio:** Cálculo de receita líquida considerando descontos.
- **Data Visualization:** Criação de um layout limpo e intuitivo para leitura de métricas.

---

## ⚙️ Como Utilizar
1.  **Inserção:** Adicione novos dados de vendas na aba `Bases`.
2.  **Processamento:** No menu do Excel, vá em **Dados > Atualizar Tudo**.
3.  **Análise:** Visualize os gráficos atualizados automaticamente na aba `Dashboard`.

---
*Desenvolvido por Julia Rocha - 2026*