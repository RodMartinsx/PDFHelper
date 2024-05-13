[![author](https://img.shields.io/badge/Author-Rodrigo&nbsp;Martins-red.svg)](https://www.linkedin.com/in/rodrigo-martins-rodrigues/)
[![](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/)


# PDF Helper

Projeto de chatbot criado durante a imersão da [Alura](https://www.alura.com.br/) com a [Google](https://ai.google/) com o objetivo de ajudar a extrair informações de forma prática de arquivos .PDF utilizando o Gemini a AI da Google. 


## Step by Step 

- Tenha uma conta google.
- Crie uma [API KEY](https://aistudio.google.com/app/apikey)
- Utilize o colab ou outra IDE para abrir o código que está no formato notebook.
- Na variavel "GOOGLE_API_KEY" preencha sua KEY retirada do Google [AI Studio](https://aistudio.google.com/app/apikey).
- Preencha os inputs com as informações solicitadas.
    - 'Insira apenas o caminho do arquivo': caminho do arquivo sem a extensão.
    - 'Realize as perguntas sobre o arquivo': prompt de comando para AI. Para finalizar digite 'fim'.  

## Input

Após inserir o caminho do arquivo o modelo ja realizou a leitura e o guardou em uma variavel que será inserida como 'contexto' dentro do chatbot. 

O PDF inserido foi [Ciência de dados e big data: o que isso significa
para estudos populacionais e da saúde?](https://www.scielo.br/j/cadsc/a/JWLSWTVvPcKkkbB6p5VPVTL/?format=pdf&lang=pt).

Após iremos solicitar o modelo de forma simples e abrangente para realmente validar se ele recebeu a informação e conseguirá extrair de forma assertiva. 


- Prompt: Crie um fichamento técnico.

## Resultado: 

model: Fichamento Técnico

Título: Ciência de Dados e Big Data: O que isso significa para estudos populacionais e da saúde?

Autores: Raphael de Freitas Saldanha, Christovam Barcellos, Marcel de Moraes Pedroso

Publicação: Cadernos de Saúde Coletiva, 2021;29(esp.): 51-58

**Resumo:**

O artigo discute as implicações da ciência de dados e big data para estudos populacionais e de saúde. Argumenta-se que o volume de dados não é a característica mais promissora do big data, mas sim a complexidade e a possibilidade de integração com estudos convencionais por meio de equipes interdisciplinares.

**Introdução:**

- O termo "big data" está se tornando mais comum em publicações científicas e editais de pesquisa.
- A ciência de dados é um campo interdisciplinar que combina ciência da computação, matemática, estatística e conhecimento substantivo do problema em análise.
- 
**Big Data e Estudos Populacionais e de Saúde:**

- O volume de dados em estudos populacionais e de saúde é menor do que em outras áreas científicas.
- A complexidade dos dados e a possibilidade de integração com outras fontes são mais importantes do que o volume.
- Técnicas de data mining permitem detectar padrões e divergências que não são identificados por abordagens tradicionais.


**A Busca de Padrões e Divergências:**

- A ciência de dados permite uma abordagem "data-driven" em vez de "hypothesis-driven".
- Isso permite identificar perfis de risco específicos e contextos particulares de risco.
- A análise de dados georreferenciados permite contextualizar eventos de saúde-doença com o território.
  
**Big Data em Saúde, Acesso a Dados e Direito ao Sigilo:**

- A integração de dados de diferentes sistemas de informação pode fornecer uma visão mais abrangente da saúde da - população.
- No entanto, é necessário abordar preocupações com o uso indevido de dados individuais.
  
**Desafios e Perspectivas Futuras:**

- O uso de técnicas de big data pode superar modelos simplistas de classificação de riscos e identificação de desigualdades.
- É necessário preservar a autonomia e a capacidade de inovação da ciência em meio a ataques a pesquisas e tentativas de retrocesso na divulgação de dados.
- 
**Conclusão:**

- No âmbito da saúde e dos estudos populacionais, a ciência de dados e o big data oferecem novas ferramentas para análise, monitoramento, predição e estudo dos determinantes socioambientais e demográficos da saúde.
