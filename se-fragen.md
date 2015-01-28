SE Fragen
=========

#### Durch die Verwendung des Entwurfsmusters *Strategie* erhöht sich die Anzahl der Objekte.

**Richtig.**

> Für jeden Algorithmus wird eine neue Klasse erstellt und darin neue Objekte erzeugt.

#### Verwaltungsmethoden wie `get()` und `set()` sind im *Klassendiagram* eines *Entwurfsmodells* zu modellieren.

**Richtig.**

> ebenso wie `insert()` und `update()`

#### Die *Kann-Kriterien* aus dem Pflichtenheft werden im Entwurfsmodell *nicht länger berücksichtigt*.

**Falsch.**

> Sie werden berücksichtigt, es sollte aber baldmöglichst entschieden werden ob (Zie: **wann**) sie realisiert werden

*Zie hatte das "ob" durchgestrichnen und "wann" druntergeschrieben*

#### Die *Kann-Kriterien* aus dem Pflichtenheft werden im Entwurfsmodell *nicht länger berücksichtigt*, da sie im fertigen Softwareprodukt mit hoher Wahrscheinlichkeit nicht realisiert sein werden. (WS2011)

**Falsch.**

> Die Kann Kriterien werden genau wie die Muss-Kriterien im Entwurfsmodell berücksichtigt.

#### Objektorientierte Vererbung lässt sich nicht auf relationale Datenmodelle abbilden.

**Falsch.**

> Es gibt 3 Arten: `JOINED`, `TABLE-PER-CLASS` und `SINGLE-TABLE`

#### Ein Web-Server funktioniert nach dem *HTTP-Request-Response-Paradigma*. Das klassische *Model-View-Controller-Konzept* lässt sich hier nicht anwenden.

**Falsch.**

> es lässt sich ab HTML5 anwenden, ist nur richtig, wenn der Webserver ohne HTML5 arbeitet

*Gruselige Begründung*

#### Eine Klasse kann entweder *ganz* oder *gar nicht* persistent sein.

**Falsch.**

> Attribute können transient sein.

#### In einer Klasse ist es auch möglich, *nur einzelne Attribute* zu persistieren (WS2011)

**Richtig.**

> Attribute die nicht persistent sein sollen mit `@Transient` versehen.

#### In der Programmiersprache *Java* gibt es keine *Mehrfachvererbung*.

**Richtig.**

> eine Klasse kann nur von einer anderen Klasse erben

#### Im Klassendiagramm des Entwurfs sollten möglichst viele *Assoziationen unidirektional* sein

**Richtig.**

> Bidirektionalität ist sehr aufwändig

*Zie: gerade so...*

*Gruselige Begründung*

#### *Beans* haben stets *die Lebensdauer "request"*. (WS2011)

**Falsch.**

> Sie können auch Sessionscoped, Sitescoped und an die Lebensdauer der Webanwendung gebunden sein.

#### Das Entwurfsmuster *Singleton* ist ein *objektbasiertes Erzeugungsmuster*. (WS2011)

**Richtig.**

> Es kann dadurch nur eine Instanz eines Objektes geben. `Object.getInstanz();`

#### Ein *fachlich relevantes, eindeutiges* Attribut wie `kundenNr` oder `artikelId` ist als *Schlüsselattribut* der Datenbanktabelle einer Entitätsklasse *nicht geeignet*. (WS2011)

**Richtig.**

> Das sich die Fachlichkeit ändern kann und die OID nicht mit der Fachlogik verbunden werden soll.

#### Ein *Phase Listener* ermöglicht es, die Berechtigung des Benutzers beim Zugriff auf eine Webseite vom *Web Framework* "JavaServer Faces" überprüfen zu lassen. (WS2011)

**Richtig.**

> der Phasenlistener kann in die einzelnen Phasen der JSF eingebunden werden (after Phase, before Phase) um zu prüfen ob ein Benutzer angemeldet ist oder nicht.

*Ich geh hart davon aus dass das nicht drankommt!*

#### *Assoziative Klassen* müssen im Entwurfsprozess *transformiert* werden. (WS2011)

![](img/ws2011_45.jpg)

#### Das *Model-View-Controller-Konzept (MVC)* bezieht sich auf *alle drei Schichten* der im Entwurfsmodell eingesetzten Drei-Schichten-Architektur. (WS2011)

![](img/ws2011_46.jpg)

#### Im ORM vermeidet man es soweit wie möglich, künstliche (numerische) Primärschlüsssel zu vergeben.

#### Persistente und nicht persistente Entitäten unterscheiden sich durch die Art ihrer Annotationen.

#### Die Lebensdauer eines Managed Bean ergibt sich automatisch aus der Lebensdauer der zugehörigen JSP-Seite.

#### Durch eine Dateiprüfsumme kann Manipulation im Abnahmetest verhindert werden.

#### Unter einer Persistence Unit versteht man die Verwaltung des Datenbankzugangs.

#### Der Übergang vom Analysemodell zum Entwurfsmodell kann zielsprachenunabhängig erfolgen.

#### Dependency Injection ist ein Muster zur losen Kopplung von Komponenten.

#### In JSF kann die Navigationsstruktur zwischen Webseiten spezifiziert werden.
