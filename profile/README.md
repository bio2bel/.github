# Bio2BEL

[Hetionet](https://het.io) was published by
[Himmelstein *et al.*](https://doi.org/10.7554/eLife.26726) in 2017
and was the first public/open biomedical knowledge graph.

[Bio2BEL](https://doi.org/10.1101/631812) was developed in parallel
and was inspired by Hetionet as a more generic mechanism for converting
biological knowledge into a common schema, using the
[Biological Expression Language](https://biological-expression-language.github.io/).

Unfortunately, the associated manuscript spent two years in review, and was ultimately
tabled by the original authors. However, in the following pandemic years the construction of
biomedical knowledge graphs (albeit, with less principled approaches) became quite popular.

The `bio2bel` Python package contains shared utilities for converting generic resources
to BEL, and a different repository was created for each resource that can be converted to BEL.

For more context on BEL, see:

1. [An Incomplete History of Selventa and the Biological Expression Language (BEL) ](https://cthoyt.com/2020/04/28/history-of-bel.html)
2. [A Listing of Publicly Available Content in the Biological Expression Language (BEL)](https://cthoyt.com/2020/04/30/public-bel-content.html)
3. [A Reading List of Academic Articles using the Biological Expression Language (BEL)](https://cthoyt.com/2020/05/22/bel-papers.html)

As of update of this page in early Spring 2025, there are not any major public-facing BEL efforts, but the entire PyBEL and Bio2BEL
codebases are ripe for revitalization if there's any interest! Please reach out to [@cthoyt](https://github.com/cthoyt) if you are
interested in supporting its maitenance.
