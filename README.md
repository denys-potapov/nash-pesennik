Наш песенник
=============

Основан на [Patacrep!](http://www.patacrep.com/en/index.php), оттуда можно брать заграничные песни.

Этот ридми кончено надо расширить и обновить.

Сборка
----

Качаем исходники:

    git clone git@github.com:PatapSmile/nash-pesennik.git

Для сборки необходимы следующие пакеты:

    sudo apt-get install texlive-base texlive-latex-extra texlive-lang-cyrillic texlive-fonts-recommended
    sudo apt-get install python
    sudo apt-get install lilypond 

Чтобы собрать пакеты надо в папке с исходниками выполнить команду:

	make all

Редактирование песен

Каждая песня - файл в подпапке с именем исполнителя в папке songs. Например: songs/nikolskiy/muzikant.sg. Формат - интуитивно понятный.

После создания песни ее надо добавить в файл книги books/chorded.sb, books/lyric.sb