---
layout: post
title: Aventures en Perl
---

2020 arrive à grands pas et ayant un peu de temps libre devant moi, j'ai décidé d'apprendre [Perl](https://www.perl.org/) par la pratique. C'est un langage avec plus de 30 ans d'existance et sa devise est : "There is more than one way to do it." (Il y a plus d'une façon de le faire.) A priori il est facile à apprendre, mais avec beaucoup de profondeur, donc difficile à maitriser. 

J'utilise actuellement un Lenovo ThinkPad X260 sous Windows 10 avec le sous-système pour Linux activé et Ubuntu 18.04.3 LTS installé. Pour plus d'informations à ce propos, vous pouvez lire [la documentaiton sur le sous-système pour Linux](https://docs.microsoft.com/fr-fr/windows/wsl/about). Mon ouvrage de réference est la quatrième édition de [Modern Perl](https://pragprog.com/book/swperl/modern-perl-fourth-edition) écrit par [chromatic](http://modernperlbooks.com/) et disponible en eBook gratuit.

Bien que la dernière version stable de Perl soit `v5.30.1`, ma version d'Ubuntu contient `v5.26.1` et j'ai décidé de rester sur celle-ci pour le moment. J'ai commencé par installer [App::cpanminus](https://metacpan.org/pod/App::cpanminus) avec la commande `sudo apt-get install cpanminus` afin de pouvoir mieux gérer les modules à partir de [CPAN](https://www.cpan.org/), ainsi que [build-essential](https://packages.ubuntu.com/bionic/build-essential) avec `sudo apt-get install build-essential` pour pouvoir utiliser les modules qui se servent de [XS](https://perldoc.perl.org/perlxs.html).

Je suis désormais prêt pour cette aventure ! 🤠
