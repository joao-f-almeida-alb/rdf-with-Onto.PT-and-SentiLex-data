# RDF with Onto.PT and SentiLex-PT data

## About

In this repository, a RDF file is provided with the Portuguese connection between words, such as synonyms, hyperonyms and other attributes obtained from the [Onto.PT](http://ontopt.dei.uc.pt/) website, 
which also has information about the confidence level of each triple (which is a value that
represents the number of sources that supported that connection between the words, being the maximum value 10).

Some words in the document also contain information about their polarity (which is the same as sentimental value), from the SentiLex-PT dataset, the SentiLex-flex-PT version, which 
contains various inflected forms of each lemma.

## Onto.PT

The data used was from the triples ["Triplos relacionais 10 recursos"](http://ontopt.dei.uc.pt/index.php?sec=download\_outros), and obtains connections related with
synonyms, hyperonyms from different 10 sources such as [PAPEL](https://www.linguateca.pt/PAPEL/), [Dicionário Aberto](https://dicionario-aberto.net/), [Wikcionário.PT](https://pt.wiktionary.org/wiki/Wikcion%C3%A1rio:P%C3%A1gina_principal), [TeP](http://www.nilc.icmc.usp.br/tep2/), [OpenThesaurus.PT](https://paginas.fe.up.pt/~arocha/AED1/0607/trabalhos/thesaurus.txt), [OpenWordNet-PT](https://github.com/own-pt/openWordnet-PT), [PULO](http://wordnet.pt/), [Port4Nooj](https://www.linguateca.pt/Repositorio/Port4Nooj/), [Wordnet.Br](http://www.nilc.icmc.usp.br/wordnetbr/), [ConceptNet](http://conceptnet.io/).
Each line of the source document has a relationship between two lemmas.

## SentiLex-PT

[SentiLex-PT](https://github.com/sillasgonzaga/lexiconPT/blob/master/data-raw/SentiLex-lem-PT02.txt) is a sentiment lexicon designed for the extraction of sentiment and opinion about human entities in Portuguese texts. We use this dataset to complement
the information about words, with information about the polarity. For more information about this dataset you can click [here](https://www.inesc-id.pt/ficheiros/publicacoes/11406.pdf).


## Contacts

For any question related with this document, or if you need any source file to manipulate the connections, feel free to contact us:

jfalmeida@student.dei.uc.pt

jessicac@student.dei.uc.pt
