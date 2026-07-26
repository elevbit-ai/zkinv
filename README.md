# Zkinv - Gerador de Previsibilidade de Ativos

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)

**Ferramenta de análise preditiva de ações e criptomoedas com inteligência artificial quântica.**

[Live Demo](https://usacomment.com) · [Report Bug](https://github.com/elevbit-ai/zkinv/issues)

</div>

---

## Funcionalidades

- **Análise Quântica de Ativos** — Previsões de alta e baixa para ações e criptomoedas
- **Gráficos Interativos** — Visualização com Chart.js (preço, MME 20, MME 50)
- **Múltiplas APIs de IA** — Gemini, Groq e OpenAI para análises preditivas
- **Indicadores Técnicos** — SMA 20/50 e RSI 14 períodos calculados automaticamente
- **Exportação em PDF** — Relatórios completos com gráficos e análises
- **Cotações em Tempo Real** — Painel com ativos brasileiros, americanos e criptomoedas
- **Sistema de Cache** — Dados armazenados localmente por 15 minutos
- **Doação via PIX** — QR Code integrado para apoio ao projeto

## Como Funcionar

### Configuração da API

1. Obtenha uma chave de API do [Google Gemini](https://aistudio.google.com/app/apikey)
2. Insira a chave no campo "Configuração da API"
3. Clique em "Salvar Chave" — ela será armazenada localmente no navegador

### Análise de Ativos

1. Selecione o mercado (Ações Brasil, Ações EUA ou Criptomoedas)
2. Digite o código do ativo (ex: PETR4, AAPL, BTC-USD)
3. Clique em "Analisar Ativo"
4. Aguarde a análise completa (gráfico + relatório preditivo)

### Relatório Preditivo

O sistema gera um relatório completo com:
- **Probabilidade de Alta** (Compra)
- **Probabilidade de Baixa** (Venda)
- **Horizonte Preditivo** (próximos 5-10 pregões)
- **Justificativa Técnica** (análise detalhada)
- **Recomendação Final** (COMPRA, VENDA ou MANTER)

## Mercados Suportados

| Mercado | Exemplos | Moeda |
|---------|----------|-------|
| Ações Brasil | PETR4, MGLU3, VALE3 | BRL |
| Ações EUA | AAPL, GOOGL, MSFT | USD |
| Criptomoedas | BTC, ETH, SOL | BRL |

## Indicadores Técnicos

- **SMA 20** — Média Móvel Simples de 20 períodos (tendência curto prazo)
- **SMA 50** — Média Móvel Simples de 50 períodos (tendência médio prazo)
- **RSI 14** — Índice de Força Relativa (sobrecompra/sobrevenda)

## Stack Tecnológica

- **Frontend:** HTML5, Tailwind CSS, JavaScript Vanilla
- **Gráficos:** Chart.js com adaptador date-fns
- **PDF:** jsPDF
- **APIs de IA:** Google Gemini, Groq (Llama 3), OpenAI (GPT-4o)
- **Dados:** Brapi (fallback: Alpha Vantage)

## Instalação

Sem instalação necessária. Abra `index.html` em qualquer navegador moderno.

```bash
git clone https://github.com/elevbit-ai/zkinv.git
cd zkinv
open index.html
```

## APIs Utilizadas

| API | Uso | Chave |
|-----|-----|-------|
| Google Gemini | Análise preditiva com IA | Necessária (gratuita) |
| Brapi | Cotações ações BR | Incluída (limitada) |
| Alpha Vantage | Fallback de dados | Demo (limitada) |
| Groq | Fallback de IA | Opcional |
| OpenAI | Fallback de IA | Opcional |

## Estrutura do Projeto

```
zkinv/
├── index.html      # Aplicação principal (HTML único)
├── README.md       # Documentação do projeto
├── LICENSE         # Licença MIT
└── .gitignore      # Arquivos ignorados
```

## Contribuindo

Contribuições são bem-vindas! Sinta-se à livre para enviar um Pull Request.

1. Faça o fork do projeto
2. Crie sua branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adicionar nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## Autor

**Joaquim Pedro de Morais Filho**

- Website: [USAcomment.com](https://usacomment.com)
- Email: j360074@hotmail.com
- GitHub: [@elevbit-ai](https://github.com/elevbit-ai)

## Aviso Legal

Este sistema é uma ferramenta de estudo e **não representa recomendação de investimento**. Todas as previsões são baseadas em análises técnicas e inteligência artificial, mas não garantem resultados futuros. Invista com responsabilidade.

## Doação

Se este projeto foi útil para você, considere fazer uma doação via PIX:

```
00020101021126370014br.gov.bcb.pix0115pagamento@bk.ru5204000053039865802BR5925Joaquim Pedro De Morais F6009Sao Paulo62070503***63043A02
```

---

<div align="center">

Feito com precisão por **Joaquim Pedro de Morais Filho**

</div>
