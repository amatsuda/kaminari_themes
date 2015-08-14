# [Kaminari Themes](https://github.com/amatsuda/kaminari)

The generator can fetch several sample template themes from this repository,
in addition to the bundled "default" one, to help you create a nice-looking paginator.

    rails g kaminari:views default

You can also specify between erb, haml or slim (in some themes):

    rails g kaminari:views semantic_ui -e haml

To see the full list of available themes, take a look at the themes repository,
or just hit the generator without specifying a THEME argument.

    rails g kaminari:views
