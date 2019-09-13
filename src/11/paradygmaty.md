# Paradygmaty

Im więcej wiem, tym bardziej przekonuję się że wiem niewiele i tym mniej ufam prawdom zawartym w księgach. 
Jak zaczynałem programować to jechano po programowaniu strukturalnym, mówiono że OOP to jedyna słuszna droga, 
potem że DOP, bo wydajność, a teraz jak od kilku lat sprzęt się nie rozwija, to znów wraca się do mikrooptymalizacji i neguje sens rozdmuchanej obiektowości. Wszystkie książki które uzasadniały jedyne słuszne podejście na tamten czas, można dziś spuścić w kiblu.


DOP vs OOP vs FOP


[Programming paradigms ( OOP, FOP, DOP and many others ) : learnpython](https://www.reddit.com/r/learnpython/comments/6tpnyw/programming_paradigms_oop_fop_dop_and_many_others/)

> FOP (functional oriented programming ): It is mostly done when you have constant data type , so in the end you will pass that data to lots of functions with data type being similar or same. In python , FOP oriented functions are next: map,filter and every other function that can grab 1 data file or pair and use it with iteration, often great examples are lambda functions, small quick functions that get and return parameter. [FOP](https://en.wikipedia.org/wiki/Functional_programming)
> 
>      sometuple = (125,325,225)    
>      sometuple = map( str, sometuple)    
>      print( sometuple )    
>       ('125','325','225')    
>     
> 
> DOP ( data oriented programming ): Data oriented programming is mostly done when you have some database you need to manipulate. It is mostly done when working with SQL or any other tabular system. Most of functions here are in short term : get, set, change, implement, return. [DDP or DOP](https://en.wikipedia.org/wiki/Data-driven_programming)
> 
>      some_database = database.load()
>      item_id = 12345 # some integer ID 
>      item = some_database.get(item_id)
>      some_database.set( item_id, change_item(item) )
>      {'data_item_id': new_value}
>     
> 
> There are a lot of other programming paradigms where you can gather information [here](https://en.wikipedia.org/wiki/Programming_paradigm)
> 
> I personally use specific type of paradigm depending on issue and structure of app/program. For base work ( building systems, utils and etc ) i use FOP or DDP(DOP) depending if i need database or i am doing some constant type data. Later i often use Agents, Inductive programming ,Semantic , Structured programming and i often recycle functions ( defining functions so they are not type derivative, so i can use same function with int and with string and give desired expected result ), i am just lazy so this type is very usefull for me.
