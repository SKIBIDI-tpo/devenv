# Skibidi Projekt

## Uvod

Preden lahko postaviš projekt, moraš na svoj računalnik namestiti naslednje programe:

1. **VirtualBox**: [Prenesi VirtualBox](https://www.virtualbox.org/)
2. **Vagrant**: [Prenesi Vagrant](https://www.vagrantup.com/)

⚠️ **Pomembno**: Natančno sledi navodilom, da bo projekt pravilno deloval!

---

## Struktura projekta

Mapa s projektom mora biti organizirana na naslednji način, da aplikacija deluje pravilno:

```
SKIBIDI
├─── Homestead (trenutni folder v katerem smo)   
├─── api (laravel)
└─── app (vue)
```

Pred začetkom se prepričaj, da struktura tvojega projekta ustreza zgoraj navedenemu.

## Navodila za zagon

1. **Postavitev Homesteada**  
   Pojdi v mapo `Homestead` in zaženi virtualni stroj z ukazom:
   ```bash
   vagrant up

2. **Dostop do aplikacije**  
   Ko je Homestead uspešno postavljen, lahko preveriš delovanje aplikacije na naslovu:
   http://192.168.56.56

3. **Podatki za povezavo z MySQL**
   Za dostop do baze podatkov uporabi naslednje podatke:
- **Host**: `127.0.0.1`
- **Uporabnik**: `homestead`
- **Geslo**: `secret`



