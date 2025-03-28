#  Banco de Dados I

Repositório da disciplina **Banco de Dados I**, contendo materiais de estudo, diagramas e resoluções de exercícios.

##  Transcrições e Resumos com Inteligência Artificial

Uma característica única deste repositório é o uso de **Inteligência Artificial (IA)** para gerar transcrições de aulas e resumos de conteúdos. Isso traz diversas vantagens:

* **Revisão Eficiente:** Resumos concisos permitem revisar rapidamente os pontos-chave de cada aula ou tópico.
* **Busca Facilitada:** Transcrições e resumos em texto possibilitam buscar por palavras-chave, otimizando o estudo.
* **Flexibilidade:** Estude no seu ritmo, acessando o conteúdo em texto a qualquer hora e lugar.

## Transcrição de Aulas com Whisper

As transcrições das aulas são geradas utilizando o Whisper, uma ferramenta de reconhecimento de fala de código aberto desenvolvida pela OpenAI.

### Como as Transcrições são Feitas

O processo de transcrição envolve os seguintes passos:

1.  **Instalação do Whisper:** O Whisper é instalado utilizando o gerenciador de pacotes pip:

    ```bash
    !pip install git+https://github.com/openai/whisper.git
    ```

2.  **Instalação do FFmpeg:** O FFmpeg é uma ferramenta de linha de comando utilizada pelo Whisper para processar arquivos de áudio. Ele pode ser instalado utilizando o gerenciador de pacotes apt:

    ```bash
    !sudo apt update && sudo apt install ffmpeg
    ```

3.  **Transcrição do Áudio:** O Whisper é executado na linha de comando, fornecendo o arquivo de áudio como entrada e o modelo a ser utilizado. O modelo "medium" oferece um bom equilíbrio entre velocidade e precisão:

    ```bash
    !whisper "aulaexemplo.mp3" --model medium
    ```

O Whisper gera um arquivo de texto contendo a transcrição da aula.

##  Estrutura do Repositório

 **aulas/** → Material organizado por aulas (exemplo: `aula01`, `aula02`, etc.), incluindo transcrições e resumos gerados por IA.
 **praticas/estudos_de_caso/** → Estudos de caso independentes, incluindo PDFs e diagramas.
 **README.md** → Documentação do repositório.

##  Conteúdo

✔️ Modelagem Entidade-Relacionamento (MER)
✔️ Normalização e formas normais
✔️ Transformação de MER para modelo relacional
✔️ Consultas SQL básicas e avançadas
✔️ Implementação de bancos de dados

##  Ferramentas Utilizadas

* **BRModelo** → Para modelagem de dados
* **MySQL/PostgreSQL** → Para implementação dos bancos de dados
* **Markdown** → Para documentação
* **Ferramentas de IA** → Para transcrição e resumo de aulas.

##  Como Usar

1.  Clone este repositório:
     ```bash
     git clone https://github.com/seu-usuario/banco_de_dados_I.git
     ```
2.  Explore os materiais dentro das pastas `aulas` e `praticas/estudos_de_caso`, aproveitando as transcrições e resumos gerados por IA.
3.  Utilize os diagramas e estudos de caso para praticar modelagem e consultas SQL.

---