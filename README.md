# QA_public_administration_brazil

# Perguntas e Respostas sobre Administração Pública no Brasil

Este repositório contém um arquivo JSON que pode ser utilizado para fine-tuning de um modelo de Linguagem de Aprendizado Longo (LLM) em questões e respostas relacionadas à administração pública no Brasil. 

O objetivo desse arquivo é fornecer um conjunto de dados estruturados que possa ser utilizado para melhorar a capacidade de resposta do modelo em relação a esse tópico específico.

## Estrutura do Arquivo JSON

O arquivo JSON possui a seguinte estrutura:

```json
[
    {
        "question": "Quando a Convenção das Nações Unidas contra a Corrupção foi aprovada no Brasil?",
        "answer": "No Brasil, a Convenção da ONU contra a Corrupção foi ratificada pelo  Decreto Legislativo nº 348, de 18 de maio de 2005, e promulgada pelo  Decreto Presidencial nº 5.687, de 31 de janeiro de 2006.",
        "category": "Convenção da ONU Contra a Corrupção",
        "url": "https://www.gov.br/cgu/pt-br/acesso-a-informacao/perguntas-frequentes/articulacao-internacional/convencao-da-onu#aprovacao",
        "date": "15/05/2023"
    },
    {
        "question": "O que representa a Convenção das Nações Unidas contra a Corrupção?",
        "answer": "A Convenção da ONU é o mais abrangente tratado internacional sobre prevenção e combate à corrupção. Ela é o maior instrumento internacional juridicamente vinculante, dessa forma, obriga os Estados Partes que a ratificaram a cumprir os seus dispositivos, sob pena de serem pressionados pela comunidade internacional. Pelo seu caráter global, a Convenção demonstra a preocupação em torno do problema da corrupção. Além disso, a partir da ratificação da Convenção pelo Brasil, ela ingressa no ordenamento jurídico como lei ordinária, ou seja, a partir desse momento, torna-se lei interna brasileira, exceto para as cláusulas de direito penal, e seu cumprimento é obrigatório por todos.",
        "category": "Convenção da ONU Contra a Corrupção",
        "url": "https://www.gov.br/cgu/pt-br/acesso-a-informacao/perguntas-frequentes/articulacao-internacional/convencao-da-onu#aprovacao",
        "date": "15/05/2023"
    },
  ...
]
```
Cada item do arquivo JSON representa uma pergunta e sua respectiva resposta e algumas informações adicionais.

O campo "question" contém a pergunta em formato de texto, o campo "answer" contém a resposta correspondente, o campo “category” inclui uma descrição mais genérica osbre o assunto da pergunta, o campo “url” contém a fonte das informações e o campo “date” contém a data na qual o conteúdo foi acessado.

Todo o conteúdo das perguntas presentes neste arquivo é de domínio público, ou seja, são informações amplamente disponíveis e livres de direitos autorais.

Você pode adicionar novas perguntas e respostas seguindo a mesma estrutura. Certifique-se de manter o formato JSON válido, onde cada item está separado por vírgula e o arquivo é uma lista de objetos JSON.

## Contribuição

Se você tiver perguntas adicionais e respostas sobre administração pública no Brasil que gostaria de contribuir, fique à vontade para enviar um pull request neste repositório ou enviar um e-mail para rodrigo.m.silva@cgu.gov.br.
