# Wikimedia

Diretório central do **Aquila-Wiki** dedicado a projetos, ferramentas, dados e documentação relacionados ao ecossistema Wikimedia.

Este diretório organiza os trabalhos conforme o projeto Wikimedia ao qual estão relacionados, mantendo separadas as diferentes áreas de atuação e facilitando a reutilização dos recursos desenvolvidos.

## Estrutura

```text
Wikimedia/
├── Wikipedia/
├── Wikidata/
├── Commons/
├── Wikisource/
└── README.md
```

## Subdiretórios

### Wikipedia

Reúne projetos relacionados à **Wikipédia**, incluindo:

* pesquisas para criação e expansão de artigos;
* análises de conteúdo;
* estudos biográficos e históricos;
* modelos e estruturas reutilizáveis;
* documentação de processos editoriais;
* scripts e ferramentas auxiliares para edição.

O conteúdo relacionado diretamente à produção e manutenção de artigos da Wikipédia deve ser organizado preferencialmente neste diretório.

### Wikidata

Destinado a projetos relacionados ao **Wikidata** e à organização de dados estruturados.

Pode incluir:

* consultas SPARQL;
* modelos de dados;
* estudos de itens e propriedades;
* ferramentas de coleta e tratamento de dados;
* scripts de automação;
* projetos de integração entre Wikidata e outros conjuntos de dados.

### Commons

Destinado aos trabalhos relacionados ao **Wikimedia Commons**.

Pode conter:

* organização de arquivos multimídia;
* documentação de categorias;
* metadados;
* informações sobre licenciamento;
* ferramentas para organização e manutenção de arquivos;
* projetos de integração entre imagens, documentos e dados estruturados.

### Wikisource

Área destinada a projetos relacionados ao **Wikisource**, especialmente trabalhos envolvendo fontes documentais e textos digitalizados.

Pode incluir:

* transcrição de documentos históricos;
* preparação de textos para publicação;
* pesquisas bibliográficas;
* organização de fontes;
* ferramentas de apoio à digitalização e revisão;
* documentação de processos editoriais.

## Organização dos projetos

Cada subdiretório pode conter seus próprios projetos e documentação. Quando um projeto envolver mais de uma plataforma Wikimedia, deve-se considerar a possibilidade de organizá-lo no nível mais adequado da estrutura ou criar referências entre os diretórios envolvidos.

Exemplo:

```text
Wikimedia/
├── Wikipedia/
│   ├── README.md
│   └── projetos/
├── Wikidata/
│   ├── README.md
│   └── projetos/
├── Commons/
│   ├── README.md
│   └── projetos/
└── Wikisource/
    ├── README.md
    └── projetos/
```

## Princípios

Os projetos mantidos neste diretório devem priorizar:

* **Verificabilidade** — informações devem possuir fontes ou documentação adequada.
* **Rastreabilidade** — alterações e processos importantes devem poder ser identificados.
* **Reutilização** — ferramentas, scripts e estruturas devem ser desenvolvidos de maneira reutilizável sempre que possível.
* **Transparência** — decisões técnicas e editoriais relevantes devem ser documentadas.
* **Compatibilidade** — recursos devem respeitar as características e políticas dos projetos Wikimedia envolvidos.
* **Preservação** — informações históricas e documentais devem ser organizadas de forma a favorecer sua preservação e consulta futura.

## Relação com o Aquila-Wiki

O diretório `Wikimedia/` representa uma das áreas centrais do Aquila-Wiki, mas não deve ser entendido como um repositório independente.

Projetos que produzam **dados, fontes, scripts ou pesquisas reutilizáveis em diferentes projetos Wikimedia** podem permanecer nas áreas correspondentes do repositório principal:

```text
Aquila-Wiki/
├── Wikimedia/
├── Pesquisas/
├── Fontes/
└── Scripts/
```

Essa separação permite distinguir **onde o recurso é utilizado** de **qual é a natureza do recurso**.

## Licenciamento

Os códigos e demais materiais originais deste repositório estão sujeitos à licença definida no projeto.

Conteúdos provenientes dos projetos Wikimedia, documentos de terceiros, imagens, textos e outros materiais externos permanecem sujeitos às respectivas licenças, direitos autorais e condições de uso.

Antes de redistribuir ou modificar materiais externos, verifique sua licença e procedência.

## Contribuições

Contribuições para esta área devem seguir as orientações estabelecidas no arquivo [`CONTRIBUTING.md`](../CONTRIBUTING.md).

Problemas de segurança devem ser comunicados de acordo com a política definida em [`SECURITY.md`](../SECURITY.md).
