# quest_germanArticles
Quest library for German articles and pronouns

Have a look at http://docs.textadventures.co.uk/quest/ for context.

This library offers articles and personal pronouns for Inanimate objects (also male, female and plural ones). It does not cover characters, simply because I haven't run into any problems there yet and I'm too lazy atm. Should I ever need it I will expand the library.

Once you have imported the library you can use attributes for getting German articles and pronouns on you inamimate objects. The names of the attributes follow this scheme:

article_<case>_<definite?>
pp_<case>

where <case> can be: nom, gen, dat, acc (for nominative, genitive, dative, accusative)

and <definite> can be: def, ind (for definite, indefinite)

Indefinite only works on singular objects.

You can append _UC to any of the attribute names to get the same with the first letter capitalised.

Examples:

singular female object: object.article_gen_ind = einer
plural male object: object.pp_dat_UC = Ihnen

Have fun!
