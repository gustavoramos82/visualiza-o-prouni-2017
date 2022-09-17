# Análise Sobre os Aprovados do Prouni em 2017

Neste projeto será feito uma análise de dados, a partir de um dataset obtido no kaggle (que pode ser acessado [aqui](https://www.kaggle.com/datasets/raphaelmarconato/pro-uni-scholarship-2017)) que é sobre os aprrovados no Prouni no ano de 2017, o intuito é fazer uma análise macro, fazer uma analise separada por idade e depois fazer uma análise micro (será escolhido o Estado do Pará, pois é o Estado onde resido), e fazer as comparações.

### Sobre o dataset

O dataset é sobre os Aprovados no Prouni no ano de 2017 e se tem as seguintes colunas:


    ANO CONCESSAO BOLSA: Ano em que a bolsa foi concedida;
    NOME IES BOLSA: Nome da Universidade onde o aluno vai estudar com bolsa;
    TIPO_BOLSA: Se é bolsa parcial ou integral;
    MODALIDADE_ENSINO_BOLSA: Se é presencial ou a distância;
    NOME_CURSO_BOLSA: Nome do curso;
    NOME_TURNO_CURSO_BOLSA: Periodo em que o aluno irá estudar;
    SEXO_BENEFICIARIO_BOLSA: Gênero do Estudante;
    RACA_BENEFICIARIO_BOLSA: Raça que o beneficiário se declarou;
    DT_NASCIMENTO_BENEFICIARIO: Data emque o beneficiário nasceu;
    BENEFICIARIO_DEFICIENTE_FISICO: Se o beneficiario tem alguma deficiência fisica;
    REGIAO_BENEFICIARIO_BOLSA: Região que o beneficiario mora;
    SIGLA_UF_BENEFICIARIO_BOLSA: Sigla do estado;
    MUNICIPIO_BENEFICIARIO_BOLSA: Municipio.

Foi adicionado uma coluna idade fazendo a diferença de 2017 pelo o ano de nascimento dos aprovados para facilitar a análise.

## Análise Macro

Nesta parte,será feita a análise macro do dataset, ou seja, informaçõa geral dos aprovados no Brasil.

Podemos ver que de 66% do aprovados foram em bolsa integral, 78% são do tipo de ensino presencial e 54% é do sexo femino, como pode ser visto nos gráficos a abaixo:

![image](https://user-images.githubusercontent.com/39843884/190859876-3e2dc5fd-9d3b-4c29-a837-7adb02ff53fa.png) ![image](https://user-images.githubusercontent.com/39843884/190859915-0eec7c4e-8d5c-42a9-83df-37c987c654f3.png) ![image](https://user-images.githubusercontent.com/39843884/190859948-77bd8b02-93bd-4f1b-bb27-63c3631d1f4e.png)

Importante ressaltar de que cerca de 99% não tem deficiência fisica, o que é umdaod q diz que a maioria dos aprovados não tem somente deficiência fisica e que poderia ser abordado quanto aos outros tipos de deficiência, tais como autismo, sindrome de downn, etc. no qual podria mais conhecimento e se ter que conhecer mais sobre.

![image](https://user-images.githubusercontent.com/39843884/190860496-041919f2-0ace-4097-9220-2fc33ebd99da.png)

Quanto a idade, a maior parte tem em torno de 20 anos, e vai diminuindo  conforme a idade vai aumentando, mostando que a maior parte do que é aprovado é composto por jovens.

![image](https://user-images.githubusercontent.com/39843884/190860611-e8912ef5-ad9a-4945-91b3-7dcd7934518a.png)

A maioria escolheu o periodo noturno para estudar, e os menos procurados são o vespertino (tarde) e o integral.

![image](https://user-images.githubusercontent.com/39843884/190860853-884b4850-d21b-44a3-ba59-74124d73888f.png)

A maioria se declarou de raça parda ou branca

![image](https://user-images.githubusercontent.com/39843884/190860950-5331a9f7-f41c-453e-9589-1df47ef017e1.png)

E uma parte bem discrepante é da região sudeste de onde a mairoia dos aprovados moram, e o menor são as regiões Norte e o Centro-Oeste.

![image](https://user-images.githubusercontent.com/39843884/190861151-2cd1ee99-1dab-4be0-9925-acb55508b72a.png)

Interessante notar que, dos cerca de 100 mil que moram na região sudeste, cerca de 60% é do Estado de São Paulo, com pode ser visto no gráfico abaixo vendo por Estado.

![image](https://user-images.githubusercontent.com/39843884/190861316-b1e21281-c700-46c4-97a0-602a540b1e3f.png)

Os três cursos mais procurados são Direito, Administração e Pedagogia.

![image](https://user-images.githubusercontent.com/39843884/190861395-62b9fd6b-6f8c-46b4-861f-c0100ecc7fd9.png)

E as três faculdades/ Universidades que os aprovados se candidataram são Universidade Paulista, Unopar e e Centro Universitário Internacional

![image](https://user-images.githubusercontent.com/39843884/190861452-36dcfb47-3719-4155-80a7-2f34ab759689.png)

## Próximos Passos

Agora os Próximos passos será fazer uma análise separada por idade para comparar os interesses de cada faixa etária, fazer uma análise micro, no caso foi escolhido o Estado do Pará.
