{lang=en}
### Model-View-Controller

Architecture pattern, often used to implement user interfaces. It divides a
system into three interconnected parts (model, view and controller) to separate
the following responsibilities:

  * Model manages data and logic of the system. The "truth" that will be shown or
  displayed by one or many views. Model does not know (depend on) its views.
  * View can be any number of (arbitrary) output representation of (model) information.
  Multiple views of the same model are possible.
  * Controller accepts (user) input and converts those to commands for the model or view.


{lang=de}
### Model-View-Controller

Architekturmuster, das häufig zur Implementierung von
Benutzeroberflächen verwendet wird. Unterteilt ein System in drei
miteinander verbundene Teile (Modell / model, Präsentation / view und
Steuerung / controller), um die folgenden Verantwortlichkeiten zu
trennen:

-   Das Modell verwaltet Daten und Logik des Systems. Die „Wahrheit",
    die von einer oder vielen Präsentationen gezeigt oder angezeigt
    wird. Das Modell kennt seine Präsentationen nicht (und ist nicht von
    ihnen abhängig).

-   Die Präsentation kann eine Reihe von (beliebigen)
    Outputdarstellungen der (Modell-) Informationen sein. Mehrere
    Präsentationen desselben Modells sind möglich.

-   Die Steuerung akzeptiert (Benutzer-) Eingaben und wandelt diese in
    Befehle für das Modell oder die Präsentation um.

