# webrest_translatingapp
Application for translation of Romanian<>Ukrainian<>English<>French words.
To be able to parse the XML document, please change the path to the ParsingXML.java class file.
To be able to translate a word, please enter the following address http://localhost:8080/RESTful/AddService/a/b/c
                                                                                                            .a->word for translation
                                                                                                            .b->source-language
                                                                                                            .c->target language
Cuvinte disponibile pentru traducere:
          -masina      -avtomobil     -car		  -voiture
      		-casa	       -budynok	      -house	  -loger
      		-masa	       -stil	        -table	  -tableu
      		-scaun	     -sydinnya	    -seat	    -siege
      		-telefon     -telefon	      -phone	  -telephone
      		-calculator  -komp'yuter    -computer	-ordinateur

If the source or target language is entered incorrectly or does not exist in the database, a corresponding message will be displayed.
If the entered word does not exist in the database, a corresponding message will be displayed.
