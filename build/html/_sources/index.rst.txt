Sistemas Operativos
================================

.. only:: html

 Referencia: Operating System concepts - 10th edition. 
 --------------------------------------------------------------------------------------

.. html sin procesar para centrar el título
.. raw:: html

    <style type="text/css">
    div.documentwrapper h1 {
    text-align: center;
    font-size: 280% ;
    font-weight: bold;
    margin-bottom: 4px;
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

Los sistemas operativos son un componente esencial de cualquier sistema informático. Se ejecutan continuamente desde que el sistema se inicia, gestionan los recursos del hardware y ofrecen un entorno para la ejecución de los programas. Por ejemplo, aunque un sistema solo tenga una CPU y una cantidad limitada de memoria —como era común hasta hace unos años— los sistemas operativos modernos son capaces de crear la ilusión de que es capaz de ejecutar múltiples tareas en paralelo y los programadores, por lo general, no tienen que preocuparse por la cantidad de memoria realmente disponible.

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