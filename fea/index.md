.fea - Adobe Feature files and derived formats
==============================================

Covering:

- The official Adobe ``.fea `` `specification
  <https://adobe-type-tools.github.io/afdko/OpenTypeFeatureFileSpecification.html>`_.
- The ``.feax`` `extension set <https://github.com/silnrsi/feax/>`_ by
  SIL. 
- The ``FeaPy`` preprocessor `construction
  <https://github.com/typesupply/feaPyFoFum>`_ by TypeSupply.
- The ``.fee``/``.fez`` `extension set
  <https://fez.readthedocs.io/en/latest/syntax.html>`_ by Simon
  Cozens.
- The GlyphsApp `extension set
  <https://handbook.glyphsapp.com/layout/feature-code/>`_.
- The FontLab `extension set
  <https://help.fontlab.com/fontlab-vi/OpenType-Features/>`_.
  
The main data table records the origin of each keyword, so that future
highlighter developers can more easily choose what to support (or can
enable end users to toggle support via some preference mechanism).

If I am missing any others, please do open an issue or make a
pull request. I did not, for example, find any information about any
syntax variants or extensions supported by Robofont.

FAQ
---

1. Yes, I would like to call it Fea++ or FeaPlusPlus, but that would
   make it harder to search for.
