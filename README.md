# Smartivus praktika įmonėje

## MySQL duomenų bazės aukšto patikimumo sprendimo diegimas bei testavimas naudojant Ansible diegimo įrankį

Šis projektas skirtas MySQL replikacijos infrastruktūros diegimui, naudojant `Ansible` automatizavimo įrankį. Tikslas – sukurti aukšto patikimumo (angl. high availability) sprendimą su `ProxySQL`, `MySQL` replikacija bei binlog skaitytuvu (angl. binlog reader).  

Projektas apima:
- Serverių inventoriaus valdymą
- `MySQL` replikacijos diegimą
- `ProxySQL` diegimą ir konfigūravimą
- Binlog skaitytuvo (angl. binlog reader) diegimą tarp `MySQL` ir `ProxySQL`
- Replikacijos valdytojo (angl. replication manager) diegimą
- Automatizuotus testavimo scenarijus
