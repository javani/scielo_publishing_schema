.. _elemento-pub-id:

<pub-id>
^^^^^^^^

Aparece em:

  :ref:`elemento-element-citation`


Atributos obrigatórios:

  1. ``@pub-id-type``

Ocorre:

  Zero ou mais vezes

Identifica o tipo de identificador (id) de um :term:`documento` em uma referência. Deve possuir o atributo ``@pub-id-type`` cujos possíveis valores são:

+--------+----------------------------------------+
| Valor  | Descrição                              |
+========+========================================+
| pmid   | :term:`PubMed` ID                      |
+--------+----------------------------------------+
| pcmid  | :term:`PubMed` Central ID              |
+--------+----------------------------------------+
| doi    | Número DOI registrado no CrossRef      |
+--------+----------------------------------------+
| pii    | Identificador do editor                |
+--------+----------------------------------------+
| other  | qualquer outro identificador           |
+--------+----------------------------------------+

Exemplo:

.. code-block:: xml

    ...
    <element-citation>
        <pub-id pub-id-type="pmid">15867408</pub-id>
    </element-citation>
    ...

.. {"reviewed_on": "20160628", "by": "gandhalf_thewhite@hotmail.com"}
