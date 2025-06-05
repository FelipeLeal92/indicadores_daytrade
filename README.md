
# 📈 Trade Analytics App

Um aplicativo interativo desenvolvido em Python com **Streamlit** para **análise estatística completa de trades**, ideal para day traders que desejam acompanhar sua performance de forma objetiva e melhorar continuamente com base em indicadores de performance reais.

---

## 🧠 Funcionalidades Principais

- 📊 **Cálculo automático de indicadores de performance**:
  - Taxa de Acerto (%)
  - Expectância
  - Retorno médio por trade
  - Fator de Lucro (Profit Factor)
  - Índice de Sharpe
  - Razão de Sortino
- 📅 Registro de trades com:
  - Data
  - Ativo (WDO, WIN, etc.)
  - Quantidade de contratos
  - Lucro Líquido (com taxas já descontadas)
- 📈 Visualização gráfica:
  - Histograma de retornos por trade
  - Evolução acumulada do patrimônio
- 📁 Salvamento e carregamento automático dos dados em CSV
- 🧮 Cálculo de **Alavancagem (%)** por trade
- 🔐 Dados organizados e estruturados para facilitar análise e backup

---

## 🚀 Como usar

### 1. Pré-requisitos

- Python 3.10+
- Bibliotecas:
  ```bash
  pip install streamlit pandas numpy matplotlib
  ```

### 2. Executar o App

```bash
streamlit run app1.py
```

---

## 🗃️ Estrutura do Projeto

```
📁 indicadores_trade/
├── app1.py              # Código principal do app (interface + lógica)
├── dados.csv            # Base de dados dos trades (criada automaticamente)
└── README.md            # Documentação do projeto
```

---

## 🧠 Indicadores Explicados

| Indicador         | Descrição                                                                 |
|------------------|---------------------------------------------------------------------------|
| Taxa de Acerto   | Porcentagem de trades com lucro                                           |
| Expectância      | Média estatística do resultado esperado por trade                         |
| Retorno Médio    | Lucro líquido médio por trade                                             |
| Fator de Lucro   | Soma dos lucros / Soma dos prejuízos                                      |
| Sharpe Ratio     | Retorno médio dividido pela volatilidade total dos resultados             |
| Sortino Ratio    | Retorno médio dividido pela volatilidade apenas dos resultados negativos  |

---

## 📷 Capturas de Tela

> ⚙️ (Adicione aqui prints do app rodando com gráficos e a tabela de trades para mostrar como ele funciona visualmente.)

---

## 📌 Observações

- O campo **Lucro Líquido** deve ser inserido **com taxas já descontadas**.
- A contagem dos trades na tabela começa em **1**, para facilitar leitura.
- O campo **ProfitLoss** foi removido em favor de **Alavancagem (%)** e outros indicadores mais relevantes.

---

## 🧪 Melhorias futuras

- Exportar relatórios em PDF
- Adicionar filtros por data, ativo ou resultado
- Implementar análise de drawdown
- Modo escuro

---

## 🤝 Contribuição

Contribuições são bem-vindas! Envie um fork ou abra uma issue com sugestões e correções.

---

## 🛡️ Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais detalhes.

---

## 🤘 Autor

Desenvolvido por **Felipe Leal** – Engenheiro Químico, futuro especialista em Python e heavy metal enthusiast.  
[GitHub](https://github.com/FelipeLeal92) | [LinkedIn](https://linkedin.com/in/seu-perfil)
