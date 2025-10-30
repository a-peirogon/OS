Sistemas Operativos 
================================

.. html sin procesar para centrar el título
.. raw:: html

    <style type="text/css">
    div.documentwrapper h1 {
    text-align: center;
    font-size: 280% ;
    font-weight: bold;
    margin: 0 4px auto;
    }
    div.documentwrapper h2 {
    background-color: white;
    border: none;
    font-size: 130%;
    text-align: center;
    margin-bottom: 40px;
    margin-top: 4px;
    }
    a.headerlink:after {
    content: "";
    }

    div.sidebar {
    margin-right: -20px;
    margin-top: -10px;
    border-radius: 6px;
    font-family: sans-serif;
    min-width: 200pt;
    }
    div.sidebar ul {
    list-style: none;
    text-indent: -3ex;
    color: #555;
    }
    @media only screen and (max-width: 1080px) and (-webkit-min-device-pixel-ratio: 2), (max-width: 70ex) {
    div.sidebar ul {
    text-indent: 0ex;
    }
    }
    div.sidebar li {
    margin-top: .5ex;
    }
    div.preface {
    margin-top: 20px;
    }
    .vcenter {
    vertical-align: sub;
    }
    </style>


.. only:: html

    .. sidebar:: Referencias

       * `Operating Systems: Three Easy Pieces <https://pages.cs.wisc.edu/~remzi/OSTEP/>`_

    .. topic:: Apuntes de clase

        Material exploratorio sobre el núcleo de cualquier sistema infórmatico: los sistemas operativos. Me propongo en el presente estudiar los fundamentos cubiertos por diferentes referencias bibliográficas, a fin de adquirir los rudimentos apropiados del campo en cuestión.

Versión: |release|

|

.. rst-class:: tune

.. toctree::
   :numbered: 4

   intro/index.rst
   .. advanced/index.rst
   .. packages/index.rst

.. FIXME: Necesito el enlace de abajo para asegurar que el banner se copie al directorio destino.

.. only:: html
..
    >>> # Para doctest en entornos sin interfaz gráfica (debe ocurrir temprano)
    >>> import matplotlib
    >>> matplotlib.use('Agg')