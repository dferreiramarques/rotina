# Rotina

Painel semanal para acompanhar hábitos, tensão arterial, peso e cintura, com um semáforo por semana.

## Como funciona

- **Começar registo**: define a data de início. A grelha limpa-se todas as segundas-feiras.
- **Semáforo**: verde a partir de 80% dos objetivos cumpridos, amarelo entre 50% e 79%, vermelho abaixo disso.
- **Tensão arterial**: leituras de manhã e à noite, com médias de 7 dias e gráfico de 14 dias.
- **Peso e cintura**: evolução desde o início e relação cintura/altura.
- **Análises de controlo**: contagem até à janela das semanas 8 a 12 e lista de preparação.

## Dados

Os dados ficam guardados no navegador (`localStorage`) de cada dispositivo e nunca são enviados para este repositório.
Para passar os dados de um dispositivo para outro, usa **Exportar cópia (JSON)** e **Importar cópia**.

## Publicar

1. Cria um repositório e coloca o `index.html` na raiz.
2. Em **Settings → Pages**, escolhe **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. O painel fica disponível em `https://<utilizador>.github.io/<repositório>/`.

Ficheiro único, sem dependências além das fontes Google Fonts.
