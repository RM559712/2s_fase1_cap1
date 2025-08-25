# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/images/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Cap 1 - Batimentos de Dados – Mapeando o Coração Moderno 

## 👨‍👩 Grupo

Grupo de número <b>[...]</b> formado pelos integrantes mencionados abaixo.

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/cirohenrique/">Ciro Henrique</a> ( <i>RM559040</i> )
- <a href="https://www.linkedin.com/in/marcofranzoi/">Marco Franzoi</a> ( <i>RM559468</i> )
- <a href="https://www.linkedin.com/in/rodrigo-mazuco-16749b37/">Rodrigo Mazuco</a> ( <i>RM559712</i> )

## 👩‍🏫 Professores:

### Tutor(a) 
- <a href="https://www.linkedin.com/in/leonardoorabona/">Leonardo Ruiz Orabona</a>

### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição

<b>Referência</b>: https://on.fiap.com.br/mod/assign/view.php?id=494570&c=13283

> ### Dados Numéricos (IoT)

Após uma análise criteriosa sobre a origem dos dados para este projeto, decidimos utilizar dados reais provenientes de repositórios confiáveis. Acreditamos que trabalhar com dados reais aumenta significativamente as chances de sucesso do projeto, além de possibilitar a contribuição direta para órgãos e instituições a partir de análises em pacientes reais.

Após pesquisas de mercado, selecionamos a <strong>UCI</strong> (<i>University of California, Irvine</i>), uma universidade pública dos Estados Unidos reconhecida internacionalmente por suas contribuições nas áreas de Ciência da Computação e Aprendizado de Máquina. Consideramos que os dados disponibilizados pelo repositório UCI Machine Learning Repository são amplamente curados, confiáveis e acessíveis, atendendo plenamente às necessidades desta fase do projeto.

Os dados utilizados foram obtidos por meio do serviço OpenDataBay e podem ser visualizados diretamente no repositório <strong>[UCI Machine Learning Repository](https://www.opendatabay.com/data/healthcare/f5d2b271-9092-470a-9c4d-6110959f4d99)</strong>. O dataset selecionado é o Cleveland Heart Disease Dataset, originalmente criado pela Cleveland Clinic Foundation. Trata-se de um conjunto amplamente utilizado na literatura científica para estudos e predição de doenças cardiovasculares. Ele fornece variáveis clínicas fundamentais, como pressão arterial, colesterol, sintomas e frequência cardíaca, que são extremamente relevantes para aplicações de Inteligência Artificial em saúde. O arquivo está disponível para [visualização](https://github.com/RM559712/2s_fase1_cap1/tree/main/document/datasets/cardiology/UCI/HeartDiseasePredictionDataset.csv) diretamente neste projeto.

Para fins informativos, a <strong>UCI</strong> disponibiliza uma [página oficial](https://archive.ics.uci.edu/dataset/45/heart+disease) com informações detalhadas sobre o dataset, incluindo os responsáveis pela criação e manutenção, descrições das variáveis e documentação adicional. 

Para organização e documentação do projeto, foi criado um diretório específico para armazenamento dos datasets utilizados em seus formatos originais, cuja estrutura inicial está definida como:

```
document/
└── datasets/
    └── cardiology/
        └── UCI/
            └── HeartDiseasePredictionDataset.csv
```

A estrutura acima prevê a expansão tanto para outros datasets relacionados à exames cardiológicos como também para outros tipos de exames.

### Variáveis relevantes para análise dos exames cardiológicos

Analisando os parâmetros disponibilizados no dataset mencionado acima, concluímos que as variáveis mais relevantes para a análise são:

- Parâmetros `cp` e `exang` pois refletem o estado imediato do paciente;
- Parâmetros `trestbps` e `chol` pois ajudam a prever os riscos e guiar em possíveis intervenções;
- Parâmetro `thalach` pois demonstra como o coração responde mediante à esforço;
- Parâmetro `age` pois os riscos de doenças cardíacas aumentam com a idade, já que pessoas mais velhas têm maior probabilidade de eventos cardiovasculares;
- Parâmetro `sex` pois homens e mulheres podem apresentar padrões diferentes de doença cardíaca. Homens têm maior incidência em idade mais jovem e mulheres têm sintomas podem ser atípicos, com risco aumentando após a menopausa;

> ### Dados Textuais (NLP)

Existem diversos conteúdos que exploram doenças cardiovasculares tanto no Brasil como em outros países. Optamos em escolher conteúdos focados no cenário nacional pois, inicialmente, nossa intenção é ajudar a população brasileira. Sendo assim, selecionamos alguns conteúdos provenientes da <strong>[Biblioteca Virtual em Saúde](https://bvsms.saude.gov.br/)</strong>, também conhecida como <strong>BVS</strong>.

De acordo com o site da Biblioteca Virtual em Saúde do Ministério da Saúde, "<i>a Biblioteca Virtual em Saúde do Ministério da Saúde – BVS MS, disponível na internet desde 2001, é responsável pela veiculação das publicações bibliográficas produzidas pelo Ministério da Saúde, bem como informações gerais na área de ciências da saúde. Como as publicações do MS não são comercializadas, a BVS MS torna-se o principal canal de acesso para essa produção.</i>" (<i>[link](https://bvsms.saude.gov.br/o-que-e-a-bvs-ms/)</i>).

Abaixo estão pontuados os conteúdos que serão utilizados nas análises para exploração:

- <strong>Hipertensão Arterial Sistêmica</strong>: pode ser visualizado clicando [aqui](https://github.com/RM559712/2s_fase1_cap1/tree/main/document/nlp/cardiology/bvsms/HipertensaoArterialSistemica.pdf);
- <strong>Protocolos Clínicos e Diretrizes Terapêuticas - Vol. 3</strong>: pode ser visualizado clicando [aqui](https://github.com/RM559712/2s_fase1_cap1/tree/main/document/nlp/cardiology/bvsms/ProtocolosClinicosDiretrizesTerapeuticas-Vol.3.pdf);

Destacamos que um dos principais motivos pela escolha desses conteúdos é a riqueza de informações detalhadas sobre diagnóstico, tratamento, prevenção e acompanhamento de pacientes com doenças cardiovasculares. Além disso, abaixo estão pontuados como os dados desses conteúdos poderão contribuir na análise NLP.

- <strong>Análise de Sentimentos</strong>: Ambos os textos contêm recomendações e orientações médicas que transmitem diferentes níveis de urgência ou cautela;
- <strong>Extração de Sintomas e Sinais Clínicos</strong>: Os textos descrevem sintomas, sinais e condições clínicas, como hipertensão, dispneia e edema;
- <strong>Classificação de Tópicos</strong>: Os conteúdos estão organizados em seções claras, como diagnóstico, tratamento, fatores de risco e estratégias de cuidado;

Com todas essas informações alinhadas em análises preditivas, concluímos que o projeto poderá atuar de forma automatizada em diferentes frentes, como por exemplo:

- Apoio em decisões médicas, fornecendo recomendações baseadas em evidências e auxiliando médicos e equipes de saúde na escolha de tratamentos mais adequados;
- Diagnósticos automatizados, auxiliando na identificação de pacientes em risco e permitindo intervenções precoces;
- Eficácia em tratamentos, garantindo que práticas clínicas estejam alinhadas com recomendações oficiais de acordo com os conteúdos selecionados;

> ### Dados Visuais (VC)



## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

1. <b>assets</b>: Diretório para armazenamento de arquivos complementares da estrutura do sistema.
    - Diretório "images": Diretório para armazenamento de imagens.

2. <b>config</b>: Diretório para armazenamento de arquivos em formato <i>json</i> contendo configurações.

3. <b>document</b>: Diretório para armazenamento de documentos relacionados ao sistema.

4. <b>scripts</b>: Diretório para armazenamento de scripts.

5. <b>src</b>: Diretório para armazenamento de código fonte do sistema.

6. <b>tests</b>: Diretório para armazenamento de resultados de testes.
	- Diretório "images": Diretório para armazenamento de imagens relacionadas aos testes efetuados.

7. <b>README.md</b>: Documentação do projeto em formato markdown.

<i><strong>Importante</strong>: A estrutura de pastas foi mantida neste formato para atender ao padrão de entrega dos projetos.</i>

## 🔧 Como executar o código

Como se trata de uma versão em formato <strong>Jupyter Notebook</strong>, para execução das funcionalidades, os seguintes passos devem ser seguidos:

1. Utilizando o prompt de comando, acesse o diretório `.../s2_fase1_cap1/src` de acordo com o local de armazenamento em seu computador;
2. Execute a linha de comando `jupyter notebook` para inicializar o <strong>Jupyter Notebook</strong> a partir do diretório acessado;
3. Após a inicialização, uma nova aba será aberta em seu browser. Clique no arquivo `cnn.ipynb` para que seja carregado em outra aba do browser;
4. Selecione as células que deseja executar e clique no ícone "Run this cell and advance (Shift+Enter)" para executar os processos;

## 🗃 Histórico de lançamentos

* 1.0.0 - 03/09/2025

## 📋 Licença

Desenvolvido pelo Grupo [...] para o projeto da fase 1 (<i>Cap 1 - Batimentos de Dados – Mapeando o Coração Moderno</i>) da <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a>. Está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>