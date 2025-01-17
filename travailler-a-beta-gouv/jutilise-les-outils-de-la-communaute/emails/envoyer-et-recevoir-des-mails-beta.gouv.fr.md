# Envoyer et recevoir des mails @beta.gouv.fr

### 0. Prérequis

Munis-toi de :

* ton adresse `prenom.nom@beta.gouv.fr`
* le mot de passe

### 1. Choisir son client de messagerie

Choisis sur quel logiciel de messagerie tu veux recevoir et envoyer tes emails. Par exemple :

* [Mail](https://support.apple.com/fr-fr/mail) (OS X / iOS) : le client mail par défaut d'Apple
* [Thunderbird](https://www.thunderbird.net/fr/) (OS X / Windows / Linux) : le client libre de Mozilla qu'on ne présente plus
* [Mailspring](https://getmailspring.com) (OS X / Windows / Linux) : un client gratuit et open-source, avec une interface moderne
* [Microsoft Courier](https://www.microsoft.com/fr-fr/p/courrier-et-calendrier/9wzdncrfhvqm?activetab=pivot:overviewtab) : le client mail par défaut de Windows
* [Microsoft Outlook](https://www.microsoft.com/fr-fr/microsoft-365/outlook/email-and-calendar-software-microsoft-outlook) : client mail souvent déjà installé sur les ordinateurs professionnels
* [Gmail](https://play.google.com/store/apps/details?id=com.google.android.gm\&hl=fr) : l'application mail par défaut sur Android (Attention vos données sont exporté aux états unis, vous ne pourrez pas faire de manipulation de données personnelles avec cette méthode)
* [AquaMail](https://www.aqua-mail.com) (Android) : une application mail fluide qui respecte la vie privée
* [ou beaucoup d'autres](https://duckduckgo.com/?q=meilleurs+clients+mails)

### **2. Configurer la réception et l'envoi d'emails**

Il existe des tutoriels détaillés pour certains clients mails :

* Apple Mail : [OSX](https://docs.ovh.com/fr/emails/guide-configuration-mail-de-mac-el-capitan/) et [iOS](https://docs.ovh.com/fr/emails/mail-mutualise-guide-configuration-iphone-ios-91/)
* [Gmail](https://docs.ovh.com/fr/emails/mail-mutualise-guide-configuration-dun-e-mail-mutualise-ovh-sur-linterface-de-gmail/)
* [Thunderbird](https://docs.ovh.com/fr/emails/configuration-email-configuration-pour-thunderbird/)
* [Courier](https://docs.ovh.com/fr/emails/configuration-courrier-sur-windows-10/)
* [Outlook](https://docs.ovh.com/fr/emails/configuration-outlook-2016/)

Pour les autres logiciels, la configuration se fait de manière suivante :

* **Ajouter un nouveau compte**
* Sélectionner l'option **IMAP / SMTP**
* Paramétrer le compte **IMAP** (courrier entrant) :

| Paramètre              | Valeur                       |
| ---------------------- | ---------------------------- |
| Serveur                | ssl0.ovh.net                 |
| Port                   | 993                          |
| Méthode de chiffrement | SSL                          |
| Nom d'utilisateur      | ton adresse beta.gouv.fr     |
| Mot de passe           | le mot de passe de ton email |

* Paramétrer le compte **SMTP** (courrier sortant) :

| Paramètre              | Valeur                       |
| ---------------------- | ---------------------------- |
| Serveur                | ssl0.ovh.net                 |
| Port                   | 587                          |
| Méthode de chiffrement | TLS                          |
| Nom d'utilisateur      | ton adresse beta.gouv.fr     |
| Mot de passe           | le mot de passe de ton email |

Tous les dossiers mails (brouillons, envoyés, reçu, archivés, etc.) sont maintenant automatiquement synchronisés entre les différents clients.

{% hint style="info" %}
Tu peux consulter tes mails directement sur [RoundCube](https://mail.ovh.net/roundcube/). L'interface n'est pas géniale, mais ça peut être une bonne solution pour dépanner, ou quand tu n'a pas accès à ton client web habituel.
{% endhint %}



