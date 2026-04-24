#  Arbeidslogg: Active Directory & Powershell 

I dag har jeg jobbet med å sette opp Active Directory på en Windows Server. Jeg startet med å installere Active Directory Domain Services (AD DS) og gjorde serveren til en Domain Controller slik at jeg kunne opprette et domene og administrere brukere sentralt. Etter dette laget jeg en OU-struktur der jeg opprettet hovedgruppene Elever, Undervisere og Ledelse, og delte Elever videre inn i klassene 1 til 7. Dette gjorde jeg for å få en ryddig og strukturert organisering av brukerne.

Videre opprettet jeg Group Policy Objects (GPO) for de ulike klassene og hovedgruppene, og koblet disse til riktig OU. I GPO-ene satte jeg innstillinger som fast bakgrunnsbilde, skjermsparer etter 5 minutter og krav om passord ved opplåsing. Dette ble gjort for å sikre likt oppsett og bedre kontroll over brukerne i domenet.

Jeg prøvde også å teste oppsettet ved å lage en testbruker og logge inn i VM, men jeg fikk ikke dette til å fungere helt som planlagt, så jeg fikk ikke tatt skjermbilder av sluttresultatet.

Gjennom denne oppgaven har jeg lært hvordan Active Directory brukes til å organisere brukere og hvordan Group Policy kan brukes til å styre innstillinger sentralt i et nettverk. Selv om testingen ikke fungerte helt, fikk jeg likevel satt opp hele strukturen og forstått hvordan systemet henger sammen.


Jeg ble ikke helt ferdig i timen fordi vi sluttet ca. 13:15 og det ble IS på taket så jeg gikk hjem og fortsatte arbeidet senere. Jeg jobbet videre hjemme til rundt klokken 17:00, hvor jeg fullførte testing, lagde brukerveiledninger, tok skjermbilder og skrev ferdig dokumentasjonen. Jeg laget også en bruker, men jeg fikk fortsatt ikke testet innlogging fordi jeg ikke fikk logget inn på VM-ene jeg hadde tilgjengelig. Jeg prøvde også å lage en ny VM for å teste Group Policy-oppsettet, men fikk det fortsatt ikke til, så jeg valgte å gå videre med dokumentasjonen siden strukturen og oppsettet allerede var ferdig.

Jeg føler at jeg har lært mye gjennom denne oppgaven, spesielt hvordan Active Directory fungerer sammen med Group Policy. Jeg brukte også tid i storefri på feilsøking for å prøve å få alt til å fungere og for å sikre at jeg kunne levere en ferdig rapport.
