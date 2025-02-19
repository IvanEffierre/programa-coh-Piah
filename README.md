## Tarefa de programação: Programa completo - Similaridades entre textos - Caso COH-PIAH
### Apresentação:
Este projeto é parte do trabalho de conclusão do curso da USP (Universidade de São Paulo), disponibilizado na plataforma https://www.coursera.org/

### Objetivo:
Basicamente, a tarefa é implementar corretamente as seguintes funções: 
1 - compara_assinatura(as_a, as_b) <br>
2 - calcula_assinatura(texto) <br>
3 - avalia_textos(textos, ass_cp) <br>

### Funções de suporte
Para facilitar o trabalho, foi fornecido um esqueleto do programa completo como base, de uso obrigatório. As funções definidas nele devem ser utilizadas no seu programa; algumas já estão implementadas, outras devem ser implementadas pelo aluno (conforme indicado pelo comentário "IMPLEMENTAR, disposto no código-fonte). Sinta-se livre para criar funções adicionais, caso necessário. <br>

### Comportamento do Jogo:
As funcionalidades descritas na seção "Objetivo" foram implementadas via código.<br>
Sendo assim,  o usuário tem que informar textos para que o programa faça uma avaliação e retorne qual dos textos disponibilizados foi infectado pelo "vírus" Coh-Piah, resultando em um possível plágio.

### Texto descritivo conforme publicado pelo Autor do Desafio
Os Traços Linguísticos que seu programa deve utilizar são calculados da seguinte forma:<br>
Tamanho médio de palavra é a soma dos tamanhos das palavras dividida pelo número total de palavras.

Relação Type-Token é o número de palavras diferentes dividido pelo número total de palavras. Por exemplo, na frase "O gato caçava o rato", temos 5 palavras no total (o, gato, caçava, o, rato) mas somente 4 diferentes (o, gato, caçava, rato). Nessa frase, a relação Type-Token vale 
4/5 = 0.8

Razão Hapax Legomana é o número de palavras que aparecem uma única vez dividido pelo total de palavras. Por exemplo, na frase "O gato caçava o rato", temos 5 palavras no total (o, gato, caçava, o, rato) mas somente 3 que aparecem só uma vez (gato, caçava, rato). Nessa frase, a relação Hapax Legomana vale 
3/5 = 0.6 <br><br>
Tamanho médio de sentença é a soma dos números de caracteres em todas as sentenças dividida pelo número de sentenças (os caracteres que separam uma sentença da outra não devem ser contabilizados como parte da sentença).<br><br>

Complexidade de sentença é o número total de frases divido pelo número de sentenças.<br><br>

Tamanho médio de frase é a soma do número de caracteres em cada frase dividida pelo número de frases no texto  (os caracteres que separam uma frase da outra não devem ser contabilizados como parte da frase).<br><br>

Após calcular esses valores para cada texto, você deve compará-los com a assinatura fornecida para os infectados por COH-PIAH. O grau de similaridade entre dois textos, 
a e b, é dado pela fórmula:<br>

​S
a
b
=
∑
i
=
1
6
∣
∣
f
i
,
a
−
f
i
,
b
∣
∣
6
S 
ab
​
 = 
6
∑ 
i=1
6
​
 ∣∣f 
i,a
​
 −f 
i,b
​
 ∣∣
​
<br>

### Créditos
1 - O esqueleto do código-fonte foi disponibilizado pela equipe do curso, mantendo a estrutura original. <br>
2 - Códigos escritos em linguagem Python por Valdivan Ramos. <br>

### Considerações Finais
As empresas e marcas citados aqui, possuem seus créditos. As marcas ou produtos citados possuem direitos reservados aos seus respectivos donos / mantededores. <br>
USP - (Universidade São Paulo) <br>
Coursera - (https://www.coursera.org/) <br>
Este código-fonte, bem como a resolução através da implementação das três funções ( seção "Objetivo"), podem ser apreciados para caráter educacional por parte dos amantes da linguagem Python e ou aqueles que desejem aprmorar, sendo base para quem tiver dificuldade em terminar o referido curso.<br>
Bom Desenvolvimento! (Good development!). <br>
