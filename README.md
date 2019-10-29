# TestesSphinx

Testes de documentação com o Sphinx.

## Instalação do Sphinx com suporte ao Fortran

    conda create -n Sphinx-Fortran python=2

    source activate Sphinx-Fortran

    source activate Sphinx-Fortran

    conda install sphinx sphinx_rtd_theme

    pip install sphinx-fortran

## Programa exemplo para a documentação

    mkdir Example_Fortran

    cd Example_Fortran

    mkdir src

    wget https://acenet-arc.github.io/ACENET_Summer_School_General/code/profiling/md_gprof.f90

    mv  md_gprof.f90  src/md.f90

## Gerando uma documentação com o Sphinx-Fortran

    echo '**/_build/'  >> .gitignore

    mkdir docs

    cd docs

    sphinx-quickstart

. . .

    make html

    firefox _build/html/index.html

# Referência

* ![Instalando Sphinx](https://ostueker.github.io/Example_Fortran/UsingSphinxFortran.html#installing-sphinx)
