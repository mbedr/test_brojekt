Hallo Welt
==========

Das ist ein Beispiel wie man einen Text mit reStructuredText schreibt:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
1) Mit einem **Editor** üben
2) wie denn *sonst* :D


Unterabschnitt A:
-----------------
"Lustig" wenn man ''**Sachen** verlinken'' kann zb auf rtd_

.. _rtd: http://www.readthedocs.com


Unterabschnitt B:
-----------------
Hier steht nicht viel [#]_. Schauen Sie weiter unten nach!


Unterabschnitt C:
-----------------
Ein Satz mit einem `anonymen Link auf die Python Website`__.

__ http://www.python.org/

\* so geht eine Multiplikation: ''\*'' mit backslash + *

.. [#] Fußnote verpasst! ;)

Listen:
~~~~~~~
* Absatz groß mit "*"
   - Absatz mittel mit "-"
      + Absatz klein mit "+"
   - Absatz mittel mit "-"

Vorformatierung:
~~~~~~~~~~~~~~~~

Ein Beispiel::

  Wenn ich hier einen Text schreibe hört dieser auf, nachdem ich den Abschnitt mit "Enter" beendet 
  und eine neue Zeile angefangen habe. Geht mit "::"

Beispiel Ende.

::

 So geht das auch

Wichtig, dass man immer eine Zeile zwischdrin frei lässt!
