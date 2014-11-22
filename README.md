# [Kaminari Themes](https://github.com/amatsuda/kaminari)

The generator has the ability to fetch several sample template themes from this repository
in addition to the bundled "default" one, which will help you creating a nice looking paginator.

    rails g kaminari:views default

You can also specify between erb, haml or slim (in some themes):

    rails g kaminari:views semantic_ui -e haml

To see the full list of avaliable themes, take a look at the themes repository,
or just hit the generator without specifying THEME argument.

    rails g kaminari:views
