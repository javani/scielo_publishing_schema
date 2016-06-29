.. _elemento-app:

<app>
-----

Aparece em:

  :ref:`elemento-back`

Atributos obrigatórios:

  1. ``@id`` (Ver :ref:`sugestao-atribuicao-id`)

Ocorre:

  Zero ou mais vezes

Utilizado para indicar um apêndice ao documento. Exige o elemento :ref:`elemento-label` como título do apêndice. O elemento :ref:`app-group` deve sempre ser usado como agrupador do elemento ``<app>`` mesmo que houver somente uma ocorrência deste último.

Exemplos:

  ``app01... app10, app11``;

  * :ref:`Exemplo de apêndice com texto`
  * :ref:`Exemplo de apêndice com imagem (fotografia, figura, tabela, quadro, equação e etc)`
  * :ref:`Exemplo de apêndice com link externo (endereço do tipo URI)`
  * :ref:`Exemplo de apêndice com tabela`
  * :ref:`Exemplo de apêndice misto (figura mais tabela)`
  * :ref:`Exemplo de apêndice misto (texto mais figura)`
  * :ref:`Exemplo de apêndice com vídeo`


.. _Exemplo de apêndice com texto:

.. code-block:: xml

    ...
    <app-group>
          <app id="app01">
              <label>Apêndice</label>
              <p>Vivamus fermentum elit et pellentesque iaculis. Curabitur egestas rhoncus purus quis iaculis. Sed laoreet id leo eu tristique. Etiam hendrerit nibh in tincidunt mattis. Sed et volutpat nulla, eget semper tellus. Nullam imperdiet fringilla diam, nec mollis elit sagittis a. Nam euismod sagittis posuere.</p>
          </app>
    </app-group>
    ...


.. _Exemplo de apêndice com imagem (fotografia, figura, tabela, quadro, equação e etc):

.. code-block:: xml

    ...
    <app-group>
        <app id="app01">
              <label>Appendix 1</label>
              <title>Questionnaire for SciELO</title>
              <graphic xlink:href="1234-5678-rctb-45-05-0110-app01.tif"/>
        </app>
    </app-group>
    ...

.. _Exemplo de apêndice com link externo (endereço do tipo URI):

.. code-block:: xml

    ...
    <app-group>
        <app id="app01">
            <label>Appendix 1</label>
            <p>Para mais informações <ext-link ext-link-type="uri" xlink:href="http://www.scielo.org">clique aqui</ext-link> para verificar o pdf.</p>
        </app>
    </app-group>
    ...

.. _Exemplo de apêndice com tabela:

.. code-block:: xml

    ...
    <app-group>
      <app id="app01">
      <label>Appendix</label>
            <table-wrap>
              <label>Table 1</label>
              <caption>
                  <title>Título da tabela</title>
              </caption>
              <table frame="hsides" rules="all">
                  <colgroup width="XX%">
                      <col/>
                      <col/>
                      <col/>
                  </colgroup>
                  <thead>
                      <tr>
                           <th style="background-color:#e5e5e5">xxxxx</th>
                           <th style="background-color:#e5e5e5">xxxxx</th>
                           <th style="background-color:#e5e5e5">xxxxxx</th>
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                           <td align="center">xxxxx</td>
                           <td align="center">xxxx</td>
                           <td align="center">xxxx</td>
                      </tr>
                  </tbody>
              </table>
            </table-wrap>
      </app>
    </app-group>
    ...

.. _Exemplo de apêndice misto (figura mais tabela)

.. code-block:: xml

    ...
    <app-group>
        <app id="app01">
            <label>Appendix 1</label>
            <title>Questionnaire for SciELO</title>
            <graphic xlink:href="1234-5678-rctb-45-05-0110-app01.tif"/>
        </app>
        <app id="app02">
            <label>Appendix 2</label>
            <table-wrap>
                <label>Supplementary Table S1</label>
                <caption>
                    <title>Título da tabela</title>
                </caption>
                <table frame="hsides" rules="all">
                    <colgroup width="XX%">
                        <col/>
                        <col/>
                        <col/>
                    </colgroup>
                    <thead>
                        <tr>
                            <th style="background-color:#e5e5e5">xxxxx</th>
                            <th style="background-color:#e5e5e5">xxxxx</th>
                            <th style="background-color:#e5e5e5">xxxxxx</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td align="center">xxxxx</td>
                            <td align="center">xxxx</td>
                            <td align="center">xxxx</td>
                        </tr>
                    </tbody>
                </table>
            </table-wrap>
        </app>
    </app-group>
    ...

.. _Exemplo de apêndice misto (texto mais figura):

.. code-block:: xml

    ...
    <app-group>
        <app id="app01">
            <label>Appendix 1</label>
            <title>Questionnaire for student inclusion</title>
            <graphic xlink:href="1234-5678-rctb-45-05-0110-app01.tif"/>
        </app>
        <app id="app02">
            <label>Appendix 2</label>
            <p>Pellentesque sollicitudin, purus nec ultricies tristique, purus nisi imperdiet enim, nec mollis augue odio sit amet augue. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut cursus ipsum non nisi faucibus suscipit. Cras ut venenatis tellus.</p>
        </app>
    </app-group>
    ...

.. _Exemplo de apêndice com vídeo:

.. code-block:: xml

    ...
    <app-group>
          <app id="app01">
              <label>suplemento eletrônico</label>
              <supplementary-material id="suppl01">
              <media xlink:href="1234-5678-rctb-45-05-0110-m01.avi" mimetype="video" mime-subtype="avi"/>
              </supplementary-material>
          </app>
    </app-group>
    ...


.. {"reviewed_on": "20160623", "by": "gandhalf_thewhite@hotmail.com"}
