# Worldwide Keyboard AI — Confidentialité / Privacy

*Déclaration de confidentialité / Privacy policy — 6 novembre 2026*

[Français](#français) · [English](#english)

---

## Français

> **En résumé :** ce clavier ne collecte rien. Ce que vous tapez reste sur
> votre téléphone. Il n'y a ni compte, ni publicité, ni mouchard, ni
> statistique d'usage, et aucune frappe n'est envoyée nulle part — y compris
> par l'intelligence artificielle, qui calcule sur l'appareil.

### Qui publie cette application

Worldwide Keyboard AI est une application développée à titre individuel. Les
questions relatives à cette déclaration peuvent être posées publiquement dans
les [tickets de ce dépôt](https://github.com/Correctors-lang/worldwide-keyboard-ai/issues).

### Ce qui ne sort jamais du téléphone

- **Vos frappes.** La correction orthographique, la grammaire, la prédiction
  du mot suivant et la saisie par glissement sont calculées sur l'appareil,
  par une bibliothèque embarquée dans l'application. Aucun caractère saisi
  n'est transmis à un serveur.
- **Les textes confiés à l'IA.** Le modèle de langue s'exécute *sur le
  téléphone*. Écrire, corriger ou reformuler un texte avec l'IA n'envoie ce
  texte à personne.
- **Votre dictionnaire personnel**, les mots que vous ajoutez, vos réglages,
  vos emojis récents et le presse-papiers du clavier. Tout cela reste dans
  l'espace privé de l'application et disparaît à la désinstallation.

### Les seules connexions que l'application établit

Elles sont toutes déclenchées par une action de votre part, et aucune ne
transporte ce que vous écrivez.

- **Les paquets de langue.** Dictionnaires et règles sont téléchargés depuis
  `github.com/Correctors-lang/clavier-langues` quand vous ajoutez une langue
  ou qu'une mise à jour est disponible. La requête ne contient que le nom du
  fichier demandé ; comme toute requête web, elle expose votre adresse IP à
  GitHub.
- **Le modèle d'intelligence artificielle** (facultatif) est téléchargé une
  seule fois depuis `huggingface.co` si vous activez la fonction. Ensuite, il
  fonctionne hors ligne.
- **La recherche de GIF** (facultatif) n'a lieu que si vous ouvrez ce
  panneau : les mots que vous y tapez sont envoyés au fournisseur choisi dans
  les réglages, dont la politique de confidentialité s'applique alors à cette
  requête. Fermez le panneau et plus rien n'est envoyé.
- **La dictée vocale** (facultative, permission micro) est assurée par le
  moteur de reconnaissance installé sur votre téléphone, pas par ce clavier.
  Si ce moteur n'est pas un moteur hors ligne, c'est son éditeur — souvent
  Google — qui reçoit l'audio, selon ses propres règles. Le clavier
  n'enregistre rien.

### Les permissions et ce qu'elles servent

| Permission | À quoi elle sert |
|---|---|
| **Contacts** (facultative) | Les noms de vos contacts sont lus pour être ajoutés au dictionnaire local, afin qu'ils ne soient plus soulignés comme des fautes. Ces noms restent sur le téléphone et ne sont jamais transmis. Refuser n'empêche rien d'autre. |
| **Microphone** (facultative) | La dictée seulement, et seulement pendant que vous dictez. Le micro n'est pas requis pour installer le clavier. |
| **Internet** | Les quatre cas listés ci-dessus, et rien d'autre. |
| **Vibration** | Le retour tactile des touches. |
| **Modification des réglages système** (facultative) | Uniquement le verrou de rotation d'écran pendant la frappe, si vous activez ce réglage. Le clavier remet ensuite le réglage comme il l'a trouvé. |
| **Service de premier plan** | Le modèle d'IA tourne dans un processus séparé pour ne pas être interrompu en pleine génération. Ce processus ne communique avec rien d'extérieur au téléphone. |

### Journaux et diagnostics

La version publiée n'écrit aucun journal de diagnostic sur le disque et
n'envoie aucun rapport d'incident automatique. Un journal détaillé existe dans
les versions de développement, qui ne quittent pas la machine du développeur.

### Mode privé

Un réglage « mode privé permanent » supprime tout historique local : emojis
récents, cache des GIF, et bloque les captures d'écran du clavier.

### Enfants

L'application ne collecte aucune donnée personnelle, quel que soit l'âge de la
personne qui l'utilise.

### Vos droits

Aucune donnée n'étant collectée ni transmise, il n'y a rien à consulter,
rectifier ou supprimer chez nous : tout est sur votre téléphone, et la
désinstallation efface l'ensemble. Vous pouvez aussi vider les données de
l'application depuis les réglages Android.

### Modifications

Toute évolution de cette déclaration sera publiée ici, avec sa date.
L'historique complet est consultable dans l'historique Git de ce dépôt.

---

## English

> **In short:** this keyboard collects nothing. What you type stays on your
> phone. There is no account, no advertising, no tracker and no usage
> analytics, and no keystroke is ever sent anywhere — including by the
> artificial intelligence, which runs on the device.

### Who publishes this application

Worldwide Keyboard AI is developed by an individual. Questions about this
policy can be asked publicly in this repository's
[issue tracker](https://github.com/Correctors-lang/worldwide-keyboard-ai/issues).

### What never leaves the phone

- **Your keystrokes.** Spell checking, grammar, next-word prediction and glide
  typing are computed on the device, by a library bundled in the application.
  No typed character is sent to any server.
- **The text you give to the AI.** The language model runs *on the phone*.
  Writing, correcting or rephrasing a text with the AI sends that text to no
  one.
- **Your personal dictionary**, the words you add, your settings, your recent
  emoji and the keyboard clipboard. All of it stays in the application's
  private storage and is gone when you uninstall.

### The only connections the application makes

Each one is triggered by something you do, and none of them carries what you
write.

- **Language packs.** Dictionaries and rules are downloaded from
  `github.com/Correctors-lang/clavier-langues` when you add a language or an
  update is available. The request contains only the name of the file being
  fetched; like any web request, it exposes your IP address to GitHub.
- **The AI model** (optional) is downloaded once from `huggingface.co` if you
  enable the feature. After that it works offline.
- **GIF search** (optional) only happens while that panel is open: the words
  you type there are sent to the provider selected in the settings, whose own
  privacy policy then applies to that request. Close the panel and nothing
  more is sent.
- **Voice dictation** (optional, microphone permission) is performed by the
  speech recogniser installed on your phone, not by this keyboard. If that
  recogniser is not an offline one, its vendor — often Google — receives the
  audio under its own terms. The keyboard records nothing.

### Permissions and what they are for

| Permission | What it is for |
|---|---|
| **Contacts** (optional) | Your contacts' names are read so they can be added to the local dictionary and stop being underlined as mistakes. Those names stay on the phone and are never transmitted. Declining blocks nothing else. |
| **Microphone** (optional) | Dictation only, and only while you are dictating. A microphone is not required to install the keyboard. |
| **Internet** | The four cases listed above, and nothing else. |
| **Vibration** | Key press feedback. |
| **Modify system settings** (optional) | Only the screen rotation lock while typing, if you turn that setting on. The keyboard then restores the setting exactly as it found it. |
| **Foreground service** | The AI model runs in a separate process so it is not killed mid-generation. That process talks to nothing outside the phone. |

### Logs and diagnostics

The published build writes no diagnostic log to disk and sends no automatic
crash report. A detailed log exists in development builds, which never leave
the developer's machine.

### Private mode

A “permanent private mode” setting removes every local history: recent emoji,
GIF cache, and blocks screenshots of the keyboard.

### Children

The application collects no personal data, whatever the age of the person
using it.

### Your rights

Since no data is collected or transmitted, there is nothing on our side to
access, correct or delete: everything is on your phone, and uninstalling
erases all of it. You can also clear the application's data from the Android
settings.

### Changes

Any change to this policy will be published here, with its date. The full
history is readable in this repository's Git history.
