# Ordre de priorité

* Analyse
* Planification
* Installation des VM
  * SRV-LIN1-01
    * Installer selon spécifications
    * DNS
    * DHCP
    * LDAP
    * SSH avec authentification par clé
  * SRV-LIN1-02
    * Installer selon spécifications
    *
    * Owncloud
    * Etablir sync avec SRV-LIN1-01
    * Se connecter avec un des comptes de l'annuaire
  * NAS-LIN1-01
    * OpenMediaVault en RAID 1 logiciel
    * Vérifier si users disposent autorisations nécessaires
* Vérifier si DHCP fct (client SRV-LIN1-02 reçoit ip dans range ?)
* Vérifier si DNS fct (ping SRV-LIN1-01 depuis SRV-LIN1-02 et inversément ?)
* Vérifictation de la totalité
