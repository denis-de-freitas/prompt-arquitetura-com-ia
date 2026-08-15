Atue como um Arquiteto de Software Sênior especialista em Clean Architecture e Métricas de Robert C. Martin. 
Analise a seguinte estrutura de pacotes e classes do meu projeto Java [INSERIR ABAIXO OU ANEXAR CÓDIGO/LISTA DE PACOTES].

Para cada pacote principal do projeto, calcule ou estime com base no código fornecido:
1. Ca (Afferent Coupling): Quantos pacotes externos dependem dele.
2. Ce (Efferent Coupling): De quantos pacotes externos ele depende.
3. Instabilidade (I = Ce / (Ce + Ca)).
4. Abstração (A = número de tipos abstratos/interfaces / total de tipos no pacote).
5. Distância da Main Sequence (D = |A + I - 1|).

Em seguida, forneça:
- Um relatório textual classificando os pacotes (se estão na "Zona de Dor" - Zone of Pain, na "Zona de Inutilidade" - Zone of Uselessness, ou equilibrados na Main Sequence).
- Um gráfico em formato Mermaid.js (tipo XY ou scatter/tabela visual) mapeando o eixo X como Instabilidade e o eixo Y como Abstração, plotando a linha ideal A + I = 1 e a posição de cada pacote.
