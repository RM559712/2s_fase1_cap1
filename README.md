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

Os dados utilizados foram obtidos por meio do serviço OpenDataBay e podem ser visualizados diretamente no repositório <strong>[UCI Machine Learning Repository](https://www.opendatabay.com/data/healthcare/f5d2b271-9092-470a-9c4d-6110959f4d99)</strong>. O dataset selecionado é o Cleveland Heart Disease Dataset, originalmente criado pela Cleveland Clinic Foundation. Trata-se de um conjunto amplamente utilizado na literatura científica para estudos e predição de doenças cardiovasculares. Ele fornece variáveis clínicas fundamentais, como pressão arterial, colesterol, sintomas e frequência cardíaca, que são extremamente relevantes para aplicações de Inteligência Artificial em saúde.

Para fins informativos, a <strong>UCI</strong> disponibiliza uma [página oficial](https://archive.ics.uci.edu/dataset/45/heart+disease) com informações detalhadas sobre o dataset, incluindo os responsáveis pela criação e manutenção, descrições das variáveis e documentação adicional. 

Para organização e documentação do projeto, foi criado um diretório específico para armazenamento dos datasets utilizados, cuja estrutura inicial está definida como:

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