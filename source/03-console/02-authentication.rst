Authenticatie
=============

.. note::

    De authenticatie is een belangrijk onderdeel van de console. Het is
    belangrijk dat de authenticatie goed is ingesteld om ongeautoriseerde
    toegang te voorkomen.

Na het maken van een console verbinding moet worden ingelogged om gebruik te kunnen maken van de console. De authenticatie is gebaseerd op een gebruikersnaam en wachtwoord. De gebruikersnaam en wachtwoord worden opgeslagen in de database. De authenticatie is een belangrijk onderdeel van de console. Het is belangrijk dat de authenticatie goed is ingesteld om ongeautoriseerde toegang te voorkomen.

De standaard credentials van het apparaat zijn:

- Gebruikersnaam: ``admin``
- Wachtwoord: ``admin``

Wachtwoord wijzigen
-------------------

Het wachtwoord kan worden gewijzigd door de volgende stappen te volgen:

1.  Open een console verbinding en log in met de huidige credentials
2.  Ga naar privilege mode met het commando ``enable``
3.  Vul het ``enable`` wachtwoord in
4.  Ga naar de configuratie mode met het commando ``configure terminal``
5.  Wijzig de credentials met het commando ``auth credentials <nieuwe-username> <nieuw-wachtwoord>``
6.  Wijzig het wachtwoord voor ``enable`` met het commando ``auth enable <nieuw-wachtwoord>``
7.  Verlaat de configuratie mode met het commando ``exit``
8.  Sla de configuratie op met het commando ``write memory``

Wachtwoord vergeten
-------------------

Mocht het wachtwoord vergeten zijn kan dit worden gereset naar de standaard credentials door de volgende stappen te volgen:

1.  Open de console verbinding en herstart het apparaat
2.  Ga naar ``ROMMON``. Meer informatie over ``ROMMON`` is te vinden in de sectie `ROMMON mode <./04-rommon-mode.html>`_
3.  Verwijder de huidige configuratie met het commando ``write erase``
4.  Herstart het apparaat

Hierna zullen de standaard credentials weer worden ingesteld.