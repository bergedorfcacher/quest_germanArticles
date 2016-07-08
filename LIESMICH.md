# quest_germanArticles
Quest library für deutsche Artikel und Personalpronomen

Siehe auch: http://docs.textadventures.co.uk/quest/


Diese library beinhaltet Artikel und Personalpronomen für Inanimate objects (auch in den Versionen male, female und plural). Characters sind nicht abgedeckt, schlicht weil ich da noch keine Probleme hatte. Sollte ich es mal brauchen, werde ich die library entsprechend erweitern.

Wenn du die library importiert hast, kansst du attributes von inanimate objects verwenden, um deutsche Artikel und Personalpronomen zu erhalten. Die Attributnamen folgen diesem Schema:

article_[case]_[definite?]

pp_[case]

Dabei kann [case] folgendes sein: nom, gen, dat, acc (für Nominativ, Genitiv, Dativ, Akkusativ)

und [definite?] kann sein: def, ind (für bestimmt, unbestimmt)

Unbestimmt funktioniert nur mit singular Objekten.

Du kannst an jeden Attributnamen _UC anhängen und erhältst dann dasselbe mit großgeschriebenem Anfangsbuchstaben.

Beispiele:

singular female object: object.article_gen_ind = einer
plural male object: object.pp_dat_UC = Ihnen

Viel Spaß!

This libray steht unter der MIT-Lizenz: https://opensource.org/licenses/MIT
