# 🧩 LexiCustoms

**LexiCustoms** é um repositório aberto dedicado à criação, organização e compartilhamento de **dicionários e léxicos personalizados** derivados ou inspirados na base de dados do [Unitex/GramLab](https://unitexgramlab.org/pt).

O objetivo é fornecer **datasets lexicais adaptáveis** para aplicações em *Processamento de Linguagem Natural (PLN)*, linguística computacional e análise textual.

---

## 📚 Objetivo

O projeto visa:

* Reunir **dicionários personalizados** baseados no formato Unitex;
* Facilitar o **reuso e a extensão** de léxicos linguísticos para diferentes domínios e variações do português (ou outras línguas);
* Servir como **fonte aberta de dados lexicais**, promovendo interoperabilidade entre pesquisadores, linguistas e desenvolvedores.

---

## 🧱 Estrutura do Repositório

```
LexiCustoms/
│
├── data/
│   ├── pt_BR/
│   │   ├── adjetivos.txt
│   │   ├── substantivos.txt
│   │   ├── verbos.txt
│   │   └── ...
│   ├── en/
│   │   └── ...
│   └── meta/
│       └── sources.json      # informações sobre origem e versão dos dados
│
├── scripts/
│   ├── converter_unitex.py   # scripts de conversão e normalização
│   ├── merge_dicts.py
│   └── validate_entries.py
│
├── docs/
│   └── formato_dicionario.md # explicação do formato dos arquivos
│
├── LICENSE
└── README.md
```

---

## ⚙️ Como usar

1. Clone o repositório:

   ```bash
   git clone https://github.com/<seu-usuario>/LexiCustoms.git
   cd LexiCustoms
   ```

2. Explore os datasets em `data/` ou use os scripts de conversão para gerar novos dicionários compatíveis com Unitex.

3. Para contribuir, veja as [diretrizes de contribuição](#🤝-contribuindo).

---

## 🧪 Formato dos Arquivos

Os dicionários seguem o formato `.dic` ou `.txt` usado pelo Unitex/GramLab, contendo uma entrada por linha com a estrutura:

```
palavra,lema.categoria+atributos
```

Exemplo:

```
bonito,bonito.A+Hum+Masc+Sg
correndo,correr.V+Ger
```

---

## 🤝 Contribuindo

Sinta-se à vontade para:

* Adicionar novos dicionários por domínio ou idioma;
* Corrigir entradas ou atributos;
* Criar *pull requests* com scripts de conversão ou limpeza de dados.

Antes de contribuir, confira o guia em `docs/CONTRIBUTING.md` (em construção).

---

## 🪪 Licença

Os arquivos e scripts deste repositório são disponibilizados sob a licença **APACHE 2.0**, exceto quando explicitamente indicado.

---

## 🌐 Links úteis

* [Unitex/GramLab (oficial)](https://unitexgramlab.org/pt)
* [Documentação do formato `.dic`](https://unitexgramlab.org/documentation)
* [Repositório GitHub do Unitex/GramLab](https://github.com/UnitexGramLab)

---
Se quiser, posso complementar isso com um **`sources.json` de exemplo**, listando como documentar a origem de cada conjunto de dados.
Quer que eu gere esse arquivo modelo também?
