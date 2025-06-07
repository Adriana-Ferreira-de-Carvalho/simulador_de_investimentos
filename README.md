### simulador_de_investimentos

# 📈 Simulador de Investimentos

Ferramenta completa para simulação de investimentos em Fundos Imobiliários com projeções realistas.

## ✨ Funcionalidades

- **Simulação personalizada** por perfil (Conservador, Moderado, Agressivo)
- **Cálculo automático** de patrimônio acumulado (função FV)
- **Projeção de dividendos** mensais
- **Comparativo de cenários** (5, 10, 15, 20 anos)
- **Alocação inteligente** por tipo de FII

## 🛠️ Como Usar

1. **Configuração Inicial**
   - Insira seu salário na célula D2
   - Selecione seu perfil no dropdown
   - O sistema calcula automaticamente a sugestão de investimento (30%)

2. **Personalize sua simulação**
   - Ajuste o aporte mensal em D7
   - Defina o período em anos em D9
   - Insira a taxa esperada em D8 (ex: 0,85% para 10% ao ano)

3. **Analise os resultados**
   - Patrimônio total projetado em D12
   - Dividendos mensais em D13
   - Comparativo entre cenários na tabela inferior

## 📊 Métodos de Cálculo

```excel
Patrimônio = FV(taxa_mensal, períodos, -aporte)
Dividendos = Patrimônio × 0,6% (rendimento médio)
