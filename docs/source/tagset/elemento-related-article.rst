.. _elemento-related-article:

<related-article>
-----------------

Aparece em:

  :ref:`elemento-article-meta`
  :ref:`elemento-front-stub`


Atributos obrigatórios:

  1. ``@related-article-type``
  2. ``@id``

Ocorre:

  Zero ou mais vezes


Utilizado para indicar um artigo relacionado, publicado ou não, separadamente. Este elemento deve ser inserido para artigos como: :ref:`errata` ou resposta de :ref:`artigo-comentado`.

Os valores possíveis para o atributo ``@related-article-type`` são:

+------------------------+-------------------------------------------+
| Valor                  | Descrição                                 |
+========================+===========================================+
| corrected-article      | Utilizado em errata para indicar o artigo |
|                        | objeto da correção.                       |
+------------------------+-------------------------------------------+
| commentary-article     | Utilizado em comentário ou editorial para |
|                        | citar o artigo que está sendo comentado.  |
+------------------------+-------------------------------------------+


Para *Errata* o elemento :ref:`elemento-related-article` deve, obrigatoriamente, apresentar os seguintes atributos: ``@related-article-type``; ``@id``; ``@xlink:href`` e ``@ext-link-type``.

Os valores possíveis para ``@ext-link-type`` são:

* doi
* scielo-pid
* scielo-aid

Exemplo:


Referências
===========

* ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. NBR14724: informação e documentação: trabalhos acadêmicos: apresentação. Rio de Janeiro: NBR, 2011.

* ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. NBR 6023: informação e documentação: referências: elaboração. Rio de Janeiro: NBR, 2002.

* JATS. Journal Article Tag Suite ANSI/NISO Z39.96-2012. Baltimore, USA: National Information Standards Organization, 2012. Disponível em:<http://jats.niso.org/>.

* JATS. Journal Article Tag Suite. Rockville Pike, USA: National Center for Biotechnology Information, 2013. Disponível em: <http://jats.nlm.nih.gov/>.

* JATS. Journal Publishing Tag Library NISO JATS Version 1.0. Rockville, USA: National Center for Biotechnology Information (NCBI), National Library of Medicine (NLM). 2012. Disponível em: <http://jats.nlm.nih.gov/publishing/tag-library/1.0/>.

* PubMed Central (NCBI). Sample PubMed Central Citations. Rockville Pike, USA: US National Library of Medicine National Institutes of Health. 2008. Disponível em: <http://www.ncbi.nlm.nih.gov/pmc/pmcdoc/tagging-guidelines/citations/v3/toc.html>.


.. {"reviewed_on": "20160628", "by": "gandhalf_thewhite@hotmail.com"}
