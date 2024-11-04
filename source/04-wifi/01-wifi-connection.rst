Wifi verbinding
===============

Het apparaat kan een Wifi verbinding maken met een draadloos netwerk. Dit kan gebruikt worden voor software updates en voor het weergeven van de huidige tijd op het apparaat. Een Wifi verbinding kan worden gemaakt door de volgende stappen te volgen:

1.  Open de seriele console van het apparaat volgende de stappen in `Console connectie <../02-console/01-console-connection.html>`_.
2.  Zorg ervoor dat de *configuratie modus* actief is.
3.  Voer het volgende commando in:

    .. code-block:: bash

        advent2024(config)#wifi <username> <password>

4.  Het apparaat zal nu proberen een verbinding te maken met het draadloze netwerk. Als de verbinding succesvol is, zal het apparaat de huidige tijd weergeven. Tevens zijn de IP gegevens te zien in ``show wifi``