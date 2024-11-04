Externe licenties
=================

Het is mogelijk om een licentie te installeren met een externe licentie generator. Deze generator stuurt de licentiecode naar de Beer Selector. Deze pagina legt uit hoe dit werkt.

1.  Zorg ervoor dat de `external-licensing` service geactiveerd is.
2.  Sluit de licentiegenerator aan op de Beer Selector.
    -   Sluit de RX port van de licentiegenerator aan op GPIO 16 van de Beer Selector
    -   Sluit de TX port van de licentiegenerator aan op GPIO 17 van de Beer Selector
3.  Herstart de Beer Selector
4.  Sluit de stroom van de licentiegenerator aan.

Na een aantal seconde zal de melding in het scherm verschijnen dat de licentie is geactiveerd.