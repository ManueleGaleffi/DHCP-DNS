# DHCP-DNS

# Obbiettivo

- ogni rete deve avere il proprio DHCP Server, tutti i PC sono configurati dinamicamente.
- su una delle reti ( a vostra scelta) è presente un server DNS che offre il servizio a tutte e 4 le sottoreti.
- sulla stessa rete del DNS è presente anche un server HTTP che deve esporre le proprie pagine web con dominio "SIRulez.it"

# Soluzione

Creiamo 4 sottoreti con subnetmask 255.255.255.192.

Poi diamo un indirizzo IP a ognuna delle 4 porte del router.

Per ogni sottorete mettiamo un server DHCP e un pc configurato dinamicamente.

Infine una delle sottoreti mettiamo un server HTTP che conterra la pagina web e un server DNS che associa il dominio della pagina web con il suo indirzzo IP ed entrambi configurati staticamente.
