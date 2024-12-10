# TexTeX


[Pygments](http://pygments.org), a Python-based code highlighting tool, comes with a set of builtin styles (not css files) for code highlighting. You have to generate a CSS file using the command line.
# Tex
You can generate these yourself, but this git repository has already generated them for you.


AI
-----


These css files were generated using pygmentize on the command line like so::

    pygmentize -S default -f html -a .highlight > default.css
