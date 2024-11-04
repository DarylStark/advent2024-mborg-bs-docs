Software update
===============

De software van het apparaat kan worden geüpdatet via een draadloze verbinding. De software update kan worden uitgevoerd door de volgende stappen te volgen:

1.  Open de seriele console van het apparaat volgende de stappen in `Console connectie <../02-console/01-console-connection.html>`_.
2.  Zorg ervoor dat de *enable modus* actief is.
3.  Voer het volgende commando in om de beschikbare software te zien (let op; dit is een voorbeeld)

    .. code-block:: bash

        advent2024# ota get-versions

        Available versions online:

        1.0.0 - 2024-11-30 - Initial version <-- your current version
        1.0.1 - 2024-12-05 - Memory fixes - LATEST

4.  Om de software te updaten, voer het volgende commando in:

    .. code-block:: bash

        advent2024# ota update 1.0.1

5.  Het apparaat zal de software downloaden en updaten. Hierna moet het apparaat opnieuw worden opgestart.