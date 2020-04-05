# Modelo Vetorial

* Reconstruir o índice considerando o conjunto de dados que indicamos. Esses são os dados coletados por Bernardi e os estaremos usando para facilitar a correção da atividade. Se você já estiver usando esses dados não precisa reconstruir o índice;
* Refinar o índice invertido de forma a também incluir o IDF (inverse document frequency) de cada termo do dicionário; (10 pts)
* Implementar as seguintes versões do modelo vetorial:(10 pts)
* Representação binária;
* TF (lembre-se que esse modelo já está implementado);
* TF-IDF;
* BM25* (não usaremos Okapi já que os documentos não tem grande variação de tamanho).
* Execute os algoritmos separadamente em 3 consultas de sua escolha e retorne os top-5 documentos mais similares à cada consulta; (10 pts)
* Compare os resultados encontrados e responda. (20 pts)
* Quais modelos você acha que trouxe os melhores resultados? Por que? Inspecione os documentos retornados para melhor embasar sua resposta.
* Calcule e reporte o overlap par-a-par entre os resultados de cada modelo (usando o índice de Jaccard (Links to an external site.))
