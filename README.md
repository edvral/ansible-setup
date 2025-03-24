# Smartivus Praktika

## MySQL duomenų bazės aukšto patikimumo sprendimo diegimas bei testavimas naudojant Ansible diegimo įrankį

Šis projektas skirtas MySQL replikacijos infrastruktūros diegimui, naudojant `Ansible` automatizavimo įrankį. Tikslas – sukurti aukšto patikimumo (high availability) sprendimą su `ProxySQL`, `MySQL` replikacija bei binlog skaitytuvu.  

Projektas apima:
- Serverių inventoriaus valdymą
- `MySQL` replikacijos diegimą
- `ProxySQL` diegimą ir konfigūravimą
- Binlog skaitytuvo diegimą tarp `MySQL` ir `ProxySQL`
- Replikacijos valdytojo (replication manager) diegimą
- Automatizuotus testavimo scenarijus
