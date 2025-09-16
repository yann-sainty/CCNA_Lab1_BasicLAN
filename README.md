\# Lab 1 - Réseau Local Basique



\## Objectif

Apprendre à configurer un réseau local simple avec :

\- 2 PC

\- 1 Switch

\- 1 Routeur



\## Topologie

* Topologie en étoile

!\[topologie](images/topology.png)



\## Adressage IP

| Appareil | IP            | Masque          | Gateway       |

|----------|---------------|-----------------|---------------|

| PC1      | 192.168.1.2   | 255.255.255.0   | 192.168.1.254 |

| PC2      | 192.168.1.3   | 255.255.255.0   | 192.168.1.254 |

| Routeur  | 192.168.1.254 | 255.255.255.0   |               |



\## Configuration

\- Routeur : IP sur interface FastEthernet connectée au switch + `no shutdown`

\- PC : IP fixe + Gateway = IP du routeur

\- Switch : Pas de configuration nécessaire pour ce lab



\## Test

\- Ping de PC1 → Routeur : ✅ réussi

\- Ping de PC1 → PC2 : ✅ réussi



\## Résultat

Le réseau local fonctionne correctement, les PC communiquent via le switch et le routeur.



