# 📦 Almeida Stock Master v3.0 — Controle Ativo de Validades

O **Almeida Stock Master v3.0** é um software desktop profissional para gerenciamento de estoque, triagem de lotes e controle estrito de validades de produtos. Desenvolvido com uma interface moderna em *Dark Mode*, o sistema foi projetado para otimizar a rotina de operadores de pátio e logística, oferecendo feedback visual imediato sobre a criticidade dos itens armazenados.

---

## 📷 Demonstração do Sistema

### 📦 Movimentação de Lotes e Painel Principal
Interface dinâmica de lançamentos (Entradas/Saídas) com cálculo de faturamento em tempo real e monitoramento de criticidade por cores.
![Painel Principal](5c59e783-dce6-4281-a3ee-cf463dd16eaf.jpg)

### 📝 Cadastro Rápido de Produtos
Formulário limpo e intuitivo para inserção de novas mercadorias no banco de dados.
![Formulário de Cadastro](606f100a-f0aa-4b9d-8f94-3bae99de2473.jpg)

---

## 🚀 Funcionalidades Principais

- **📊 Controle Ativo de Validades:** O sistema calcula automaticamente os dias restantes para o vencimento de cada lote, categorizando-os em:
  - 🟢 **Estável (OK):** Produtos com prazo de validade seguro.
  - ⚠️ **Crítico:** Alerta visual para produtos que vencem em menos de 15 dias.
  - ❌ **Produto Vencido:** Bloqueio e sinalização de itens vencidos.
  - 🚨 **Estoque Baixo:** Alerta automático se o lote possuir 50 caixas ou menos.
- **🔄 Movimentação Dinâmica (Entrada/Saída):** Atualização instantânea da quantidade de caixas disponíveis por lote.
- **💰 Faturamento da Sessão:** Monitoramento em tempo real do valor bruto movimentado nas saídas do turno.
- **📡 Integração com a Gerência (JSON Backend):** Salvamento automático de dados em arquivos locais JSON, simulando relatórios de diretrizes enviados pelo supervisor e exportação de fechamento de estoque.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.14+** (Linguagem base do projeto)
- **CustomTkinter** (Interface gráfica moderna e customizada com suporte a Dark Mode nativo)
- **Tkinter** (Componentes complementares de interface e caixas de mensagem)
- **JSON** (Persistência e estruturação de dados local de forma leve)

---

## ⚙️ Como Executar o Projeto

1. Certifique-se de ter o **Python** instalado na sua máquina.
2. Clone este repositório ou baixe o arquivo do código fonte.
3. Abra o terminal na pasta do projeto e execute o comando abaixo (o sistema possui rotina de auto-instalação para a biblioteca `customtkinter` caso você não a tenha):

```bash
python "codigo do stock master v2.py"
