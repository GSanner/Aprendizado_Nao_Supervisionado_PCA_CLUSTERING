# Aprendizado_Nao_Supervisionado_PCA_CLUSTERING

Projeto feito no curso Let's Data - Jornada Cientista da Dados

## Motivação 
Questionários com dezenas ou até centenas de respostas são difíceis de analisar para agrupar os segmentos semelhantes. PCA chega para nos salvar: reduzir a dimensionalidade das respostas a tais questionários melhor muito a compreensão e aplicação da análise de aglomerados (clusterização).

Esse tipo de problema claramente é aplicável em diversos segmentos da economia!

## Objeto de Estudo 
Estamos lançando um novo conceito de carro, uma espécie de microvan (maior que SUV, mas menor que minivan), e queremos conhecer o melhor público para iniciar nossas campanhas de marketing.

O principal método para detectar tais tendências é a pesquisa primária do consumidor, geralmente começando com grupos focais direcionados e prosseguindo para pesquisas de média e, eventualmente, de grande escala. Essas pesquisas servem a pelo menos dois propósitos:

- verificar os “desejos e necessidades” de um determinado grupo/nicho de consumidores
- junto com os dados demográficos, tentar avaliar o perfil de quem gostou do conceito de microvan da Let's Ride
  
As perguntas de negócio que queremos responder são:

- Qual é o segmento alvo para este carro?
- Quais são os desejos e necessidades deste segmento?
  
Então, a Let's Ride realizou pesquisa de vários grupos focais entre potenciais compradores desses carros. Ainda, a equipe de marketing examinou uma longa lista de potenciais atributos que poderiam ser importantes para compradores de microvans, bem como declarações de estilo de vida, validadas por suas extensas pesquisas anteriores na indústria automobilística. Com base em notas detalhadas feitas durante a fase de grupo focal, estabeleceu-se em um conjunto de 30 atributos que pareciam capturar a natureza da discussão, bem como variáveis demográficas importantes. O objetivo é usar esses atributos para capturar as dimensões-chave que caracterizam potenciais compradores e identificar os segmentos que a Let's Ride poderia criar para suas campanhas. Por fim, foi apresentado um projeto do carro (microvan) para que os potenciais consumidores dessem uma nota de 1 a 9 se gostaram ou não.

O problema é que, se fizermos uma análise de aglomerados com 30 features, o resultado não será muito inteligível e ficaria difícil depreender os perfis dos clientes. Podemos reduzir a dimensionalidade das features para agrupar as que possuem variância similar (PCA) e então avaliar qual foi o resultado dessa redução em termos de interesses dos clientes. Para avaliar a homegeneidade dos grupos, somente com clusterização, mas já com PCA conseguimos ter a junção de features com variância semelhante, o que, para respostas de questionários, serve como um agrupamento de perfis de respostas.

Assim como nos outros projetos, bancos, telefônicas, varejo, qualquer empresa que presta algum tipo de serviços e possui informações sobre seus clientes pode se beneficiar de análise de questionários de clientes e redução em componentes principais conforme iremos construir nesse projeto.

ps: esse estudo de caso real (Grosse Pointe Associates and The “Microvan”) está disponível no excelente livro "Modern Marketing Research: Concepts, Methods, and Cases" ISBN 1133188966


## Instalação das dependências

Para instalar as dependências do projeto, certifique-se de ter o Python instalado. Em seguida, execute o seguinte comando no terminal ou prompt de comando: pip install -r requirements.txt

Este comando irá instalar todas as bibliotecas e suas versões especificadas no arquivo `requirements.txt`, garantindo que o ambiente esteja configurado corretamente.

## Executando o projeto

Para executar o projeto, siga os passos abaixo:

1. Clone este repositório para o seu ambiente local.
2. Navegue para o diretório do projeto no terminal ou prompt de comando.
3. Certifique-se de que as dependências estejam instaladas (consulte a seção "Instalação das dependências" acima).
4. Execute o seguinte comando: python main.py
5. Isso iniciará o aplicativo e você poderá interagir com ele através da interface do usuário.
