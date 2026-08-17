# Dashboard Histórico Tarifário

Dashboard pronto para GitHub Pages, criado a partir do arquivo `Historico_Tarifario_Caracol_Concorrencia(2).xlsx`.

## O que tem
- Gráfico de linhas comparando todas as atrações.
- Filtro por ingresso **Adulto** ou **Meia**.
- Alternância entre **Preço (R$)**, **Variação mensal (R$)** e **Variação mensal (%)**.
- Filtro de período.
- Seleção individual das atrações.
- Tabela de variação do último mês selecionado.
- Meses e valores sem informação preenchidos com **0**.
- Na variação percentual, quando o mês anterior é 0, o dashboard mostra `—` para evitar divisão por zero.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie `index.html`, `data.json`, `dados_completos.csv` e este `README.md` para a raiz.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`.
6. Salve. O GitHub exibirá a URL pública do dashboard.

> O `index.html` já contém os dados embutidos, então funciona diretamente no GitHub Pages. O `data.json` e o CSV ficam disponíveis para manutenção e conferência.
