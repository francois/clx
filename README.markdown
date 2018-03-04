# clx

Un outil pour s'entraîner régulièrement. Après chaque Pomodoro, exécuter `clx` et exécutez l'exercise en question. Le script va
toujours exécuter tous les exercises de niveau 1 avant de passer au niveau 2, et ainsi de suite.

## Utilisation

Obtenir de l'aide:

    $ clx help
    $ clx --help
    $ clx -h

Écraser une base de donnée existante:

    $ clx new

Ajouter des exercises:

    $ clx add "Push ups" 2x8 2x8 2x10 2x10 2x12 2x12 3x10 3x12 3x15 3x20
    $ clx add "The chair" 1x60 1x75 1x90 1x105 1x120 2x90 2x105 2x120 2x120 2x120

Laisser le système choisir le prochain exercise à faire:

    $ clx

## LICENSE

This project and it's contents are distributed under a public domain license: you are free to do as you wish with the code and the contents.
