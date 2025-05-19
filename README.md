# Progetto Cisco Packet Tracer: Rete Clinica

## Descrizione

Questo progetto realizzato con Cisco Packet Tracer rappresenta la simulazione di una rete per una clinica. Include vari dispositivi di rete configurati per garantire comunicazione, sicurezza e scalabilità. La topologia è pensata per riflettere una struttura clinica reale con reparti, uffici amministrativi e connessioni esterne.

## Obiettivi del progetto

* Simulare una rete realistica per una struttura sanitaria
* Garantire separazione tra reparti (es. amministrazione, laboratorio, ambulatori)
* Abilitare comunicazione sicura tra dispositivi
* Fornire accesso a Internet e a un server centrale

## Componenti principali

* **Router** per la gestione del traffico tra VLAN e verso Internet
* **Switch Layer 2** per la connessione interna dei dispositivi
* **PC e Laptop** in rappresentanza dei vari reparti
* **Server** centrale (per cartelle cliniche o gestione utenti)
* **Access Point Wireless** per la connettività mobile

## Configurazioni Implementate

* Segmentazione della rete in **VLAN**
* Assegnazione di **indirizzi IP statici e dinamici (DHCP)**
* **Routing** tra le VLAN tramite Router-On-A-Stick
* Configurazione di **Access Control List (ACL)** per limitare l'accesso
* Impostazione del **Server DNS e DHCP**
* Simulazione del traffico e test di connettività con ping e browser

## Requisiti

* Cisco Packet Tracer (versione compatibile con il file .pkt allegato)

## Istruzioni per l'uso

1. Aprire il file `reteClinica.pkt` con Cisco Packet Tracer
2. Esaminare la topologia e la configurazione dei dispositivi
3. Eseguire test di connettività con `ping` tra dispositivi
4. Analizzare il comportamento delle VLAN e delle ACL

## Note

Per modificare la rete o fare test ulteriori, si consiglia di creare una copia del file originale.
