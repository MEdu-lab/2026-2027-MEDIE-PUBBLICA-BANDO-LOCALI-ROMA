{% if progetto.tipo_scuola != "pubblica" %}

## ASPETTI ORGANIZZATIVI

Il laboratorio si svolge ogni {{ programmazione.giorno_settimana }} dal {{ programmazione_calcolata.primo_incontro }} al {{ programmazione_calcolata.ultimo_incontro }}, per un totale di **{{ programmazione_calcolata.totale_incontri }} incontri** (media di {{ programmazione_calcolata.media_per_mese }} incontri al mese).

{% else %}

## ASPETTI ORGANIZZATIVI

Il progetto copre l'intero anno scolastico {{ progetto.anno_scolastico }}, indicativamente da ottobre a maggio, con cadenza {{ corso.frequenza }} in orario pomeridiano extrascolastico. Ogni partecipante è coinvolto in una lezione individuale di strumento di circa 45 minuti e nell'incontro collettivo di musica d'insieme (mini orchestra e coro) di circa un'ora e mezza. La fascia d'età di riferimento è {{ corso.fascia_eta }} (scuola secondaria di primo grado); l'accesso non richiede alcuna competenza musicale pregressa.

Giorni, orari, calendario dettagliato ed eventuali quote di partecipazione verranno concordati con la scuola e con il Municipio in base alle disponibilità degli spazi e alle condizioni previste dall'avviso pubblico. I maestri garantiscono la custodia dei ragazzi per tutta la durata delle attività e la riconsegna degli ambienti in ordine al termine di ogni incontro.
{% endif %}
