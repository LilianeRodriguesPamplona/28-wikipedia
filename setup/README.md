#### Estrutura HTML

- seção.wiki
  - div.container
    - imagem
    - h3(texto)
    - formulário.formulário
      - input.form-input type='texto'
      - button.submit-btn (pesquisar) type='enviar'
  - div.resultados
    - div.artigos
      - a
        - h4
        - p (lorem20)

#### DOCUMENTOS DE API

- [documentos docs](https://www.mediawiki.org/wiki/API:Main_page)

- pronto para usar URLs

#### Configuração inicial

- selecione formulário, entrada, resultados
- ouvir eventos de envio
- se valor vazio, exibe erro
- criar fetchPages()
- passe um valor de entrada válido para fetchPages()

#### Buscar páginas

- exibir carregamento durante a busca
- construir url dinâmico
- exibir se houver erro
- erro de exibição sem itens
- criar renderResults()
- passe resultados válidos para renderResults()

#### Renderizar resultados

- iterar sobre a lista
- retire o título, snippet, pageid
- configurar um cartão
- defina os resultados com div.articles e liste dentro
