

intro : the other day i was using scss to make my portfolio
and realized how much better it makes writing css
i mean thats what pre processors do . typescript make javascript better,ll sass makes css better. but what about html. what preprossecor does it have.
one of tge most popular html preprossecor is pug
which is html is just html with tabs and i hate it so thats ehy i decided to make my own preprossecor for html. introducing html + css = htss (hyper text style sheet). this is such a bad idea like css is hated for it syntax but its esoteric language anyway so no one cares. and yeah its actually a language unlike html. this will be the syntax of htss. it a lot like css
now lets build it

bulding: so to . make the languge i first need to define a pipeline. the language the frontent parses the htss cose into an ast then the transformer takes kt and turns it into a pure html node tree and the last step is to parse the html node tree into pure html and then we are done.

now this is 8 how everything works in a more depth first we take