# Webcrawler_NTMel
Projeto de webcrawler para a loja Naturimel Marília-SP

# Objetivo
Este projeto tem como objetivo criar uma aplicação que coleta dados de preços de produtos de sites de fornecedores e os organiza para visualização e análise, facilitando comparações e a geração de relatórios.

---

## Funcionalidades

- Escavar dados (scraping) de um ou mais sites de lojas de produtos naturais.
- Armazenar os dados em um banco de dados.
- Apresentar os dados de forma organizada em uma interface gráfica.
- Gerar relatórios em PDF com os dados coletados.
- Permitir a comparação com preços da própria loja.

---

## Fluxo do Projeto

1. **Coleta de dados** dos seguintes sites:
   - Apiários Bonádio
   - Apis Flora
   - Netnutri

2. **Organização por produtos**.

3. **Decisão sobre armazenamento**:
   - Se armazenar: os dados são tratados e enviados ao banco.
   - Caso contrário: os dados são tratados apenas na memória.

4. **Visualização**:
   - Interface gráfica com TKinter (ou outro framework).
   - Exibição dos preços e comparações com a loja.

5. **Relatórios**:
   - Geração opcional de PDF para exibição dos dados coletados.

---

## Funcionalidades Planejadas

- [x] Webcrawler para pelo menos 2 sites
- [ ] Armazenamento dos dados em banco de dados
- [ ] Compatibilidade com Microsoft Edge
- [ ] Visual funcional (com interface gráfica)
- [ ] Visual estético (design agradável)
- [ ] Comparação de preços com produtos da loja
- [ ] Geração de relatório em PDF
- [ ] Criação de instalador do app

---

## Tecnologias Utilizadas

- Python
- Bibliotecas:
  - `requests` / `httpx`
  - `BeautifulSoup` / `lxml`
  - `tkinter`
  - `sqlite3` / `MySQL`
  - `reportlab` ou `fpdf` (para PDF)
- Git para versionamento
- Trello para organização de tarefas (Scrum)

---

## Status Atual

- Ainda em desenvolvimento (Estágios iniciais)

---
