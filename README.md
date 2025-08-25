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

Após análises sobre qual a origem dos dados para esse projeto, decidimos utilizar dados reais provenientes de repositórios confiáveis. Acreditamos que as chances do projeto obter maior sucesso utilizando dados reais serão maiores, além do fato de podermos contribuir diretamente com orgãos e empresas a partir de análises em pacientes reais.

Fizemos diversas pesquisas de mercado até chegarmos na <strong>UCI</strong> (<i>University of California, Irvine</i>). Por se tratar de uma universidade pública nos Estados Unidos muito reconhecida por suas contribuições na área de Ciência da Computação e Aprendizado de Máquina, acreditamos que os dados disponibilizados atenderão plenamente nessa fase do projeto. Trata-se de um repositório considerado como uma das fontes mais bem curadas, confiáveis e acessíveis para projetos que utilizam datasets científicos.

Os dados foram obtidos através do serviço <strong>Opendatabay</strong>, podendo ser visualizados diretamente no repositório <strong>UCI Machine Learning Repository</strong> clicando [aqui](https://www.opendatabay.com/data/healthcare/f5d2b271-9092-470a-9c4d-6110959f4d99). O dataset utilizado é o <strong>Cleveland Heart Disease Dataset</strong>, na qual foi criado originalmente pelo <strong>Cleveland Clinic Foundation</strong> e faz parte de um seleto grupo de datasets, amplamente utilizado na literatura científica para o estudo e predição de doenças cardiovasculares. Esse dataset fornece variáveis clínicas fundamentais, como pressão arterial, colesterol, sintomas e frequência cardíaca, que são extremamente relevantes para aplicações de Inteligência Artificial em saúde.

Para fins informativos, a <strong>UCI</strong> disponibiliza uma [página](https://archive.ics.uci.edu/dataset/45/heart+disease) em seu site contendo diversas informações, como por exemplo o nome dos criadores ou responsáveis pela manutenção dos dados, informações referentes ao dataset, etc.

Para fins de documentação do projeto, foi criado um diretório para armazenamento de datasets utilizados no projeto. Inicialmente a estrutura está definida como:

```
document/
└── datasets/
    └── cardiology/
        └── UCI/
            └── HeartDiseasePredictionDataset.csv
```

> ### Dados Textuais (NLP)



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