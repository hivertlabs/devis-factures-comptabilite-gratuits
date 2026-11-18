# L'Établi pour les débutants

**Devis, factures et comptabilité expliqués pas à pas, avec le pourquoi de chaque étape**

Ce guide s'adresse à vous si vous venez de créer votre entreprise, si vous n'avez jamais fait de facture, ou si le mot « TVA » vous donne des sueurs froides. Il ne suppose aucune connaissance. Chaque étape est expliquée : ce qu'il faut faire, et surtout pourquoi.

L'objectif est simple : que vous puissiez tenir vos devis, vos factures et votre comptabilité seul, sans payer un rendez-vous chez un comptable pour comprendre les bases.

> **À savoir avant de commencer.** Ce guide décrit les règles françaises en vigueur en 2026. Il vous aide à comprendre et à bien faire, il ne remplace pas un expert-comptable pour les situations particulières (société avec salariés, montage complexe, contrôle fiscal). L'Établi est fourni gratuitement, tel quel, sans garantie.

---

## Sommaire

1. Installer et ouvrir L'Établi
2. Votre configuration, case par case

3. Votre premier devis

4. Du devis à la facture : acompte, solde, avoir

5. La numérotation : pourquoi elle est si surveillée

6. La comptabilité au quotidien

7. La TVA expliquée simplement

8. Micro-entreprise ou régime réel : ce qui change pour vous

9. Ce que fait le comptable, et le fichier FEC

10. Les fichiers à garder, et pendant combien de temps

11. Les erreurs les plus fréquentes

12. Lexique

---

## 1. Installer et ouvrir L'Établi

### Deux façons de l'utiliser

**En ligne**, avec le lien du site. Vous n'installez rien. La page s'ouvre dans votre navigateur, mais **rien n'est envoyé sur internet** : vos clients, vos prix et vos factures restent sur votre ordinateur. Le site ne fait que vous donner le programme.

**Hors ligne**, avec le fichier `LEtabli.html`. Sur le site, cliquez sur « Télécharger L'Établi », sous les boutons de l'accueil. Vous obtenez un seul fichier, qui contient tout, y compris la lecture automatique des tickets. Rangez-le dans un dossier à vous (par exemple `Documents\Entreprise\`) et ouvrez-le d'un double-clic.

**Pourquoi proposer les deux ?** Le fichier marche même sans connexion, sur un chantier ou si le site disparaît un jour. Le lien en ligne vous donne toujours la dernière version.

### Le conseil le plus important de ce chapitre

**Utilisez toujours la même façon de l'ouvrir**, et ne déplacez pas le fichier une fois rangé.

Pourquoi : le navigateur garde en mémoire quelques informations pour vous faire gagner du temps, notamment le compteur de vos factures. Cette mémoire est liée à l'endroit d'où la page est ouverte. Si vous ouvrez un jour le lien et le lendemain le fichier, ou si vous déplacez le fichier, le navigateur croit avoir affaire à un autre logiciel et repart de zéro. Rien n'est perdu pour autant (vos fichiers `.json` contiennent tout, voir chapitre 10), mais vous éviterez des surprises.

### Quel navigateur ?

L'Établi fonctionne avec les navigateurs les plus répandus : **Edge** (celui qui est déjà installé sur Windows), **Chrome** et **Firefox**. Gardez celui que vous utilisez déjà.

Pour faire vos PDF, cliquez sur le bouton « Imprimer » du logiciel et choisissez une imprimante PDF : « Enregistrer au format PDF » ou « Microsoft Print to PDF ». Le logiciel copie le nom du fichier au moment du clic (par exemple `F-2026-003_Martin`). Si la case « Nom » de la fenêtre d'enregistrement est vide, cliquez dedans, faites **Ctrl+V**, puis Entrée.

---

## 2. Votre configuration, case par case

La configuration, c'est votre fiche d'identité d'entreprise : elle s'imprime sur chaque devis et chaque facture. Vous la remplissez une seule fois.

Cliquez sur « ✨ Créer ma configuration » et suivez les étapes. À la fin, cliquez sur « ✅ Terminer : télécharger ma configuration et faire mon premier devis ». Un fichier `config_devis_... .json` est téléchargé.

**Ce fichier, c'est votre logiciel personnel. Gardez-le précieusement.** Les fois suivantes, cliquez sur « 📂 Charger ma configuration (.json) » et tout est prêt.

### Pourquoi toutes ces mentions ?

Une facture n'est pas un simple papier qui réclame de l'argent. C'est une **pièce légale** : votre client s'en sert pour sa propre comptabilité, l'administration s'en sert pour contrôler la TVA, et un juge s'en sert en cas de litige. C'est pour cela que la loi impose des mentions précises. Une mention manquante peut coûter une amende (15 € par mention manquante et par facture, plafonnée au quart du montant de la facture), et surtout, elle peut empêcher votre client professionnel de récupérer sa TVA, ce qui ne vous fera pas de publicité.

Le logiciel vous demande donc :

| Case | Pourquoi |
|---|---|
| **Pays** | Les taux, les mentions et les numéros demandés changent selon le pays. Choisissez-le en premier. La comptabilité ne fonctionne que pour la France. |
| **Nom, adresse** | Votre client doit pouvoir vous identifier et vous écrire. |
| **Forme juridique** (EI, EURL, SASU...) | Elle indique qui répond des dettes. Elle est obligatoire sur les documents d'une société. |
| **SIREN ou SIRET** | C'est votre numéro d'immatriculation, le numéro qui prouve que votre entreprise existe. Le SIREN a 9 chiffres, le SIRET en a 14 (le SIREN plus 5 chiffres pour votre établissement). Vous le trouvez sur votre avis de situation INSEE ou sur annuaire-entreprises.data.gouv.fr. |
| **Numéro de TVA intracommunautaire** | Uniquement si vous facturez la TVA : il doit alors figurer sur vos factures. Les impôts vous l'attribuent, vous le trouvez dans votre espace professionnel sur impots.gouv.fr. |
| **Capital social, RCS ou RM** | Pour les sociétés : le capital et le lieu d'immatriculation font partie des mentions obligatoires. |
| **Assurance** | Pour les métiers du bâtiment, l'assurance décennale est obligatoire. Vos devis et factures doivent indiquer l'assureur, le contrat et la zone couverte. C'est aussi un argument : un client prudent vérifie. |
| **Taux de TVA** | Voir chapitre 7. Si vous êtes en franchise de TVA, le logiciel imprime la mention « TVA non applicable, art. 293 B du CGI », obligatoire dans ce cas. |
| **Tarifs** | Vos prix habituels, pour ne pas les retaper à chaque devis. |
| **Conditions de paiement** | Délai de paiement, pénalités de retard, et pour les clients professionnels l'indemnité forfaitaire de 40 € pour frais de recouvrement. Ces mentions sont obligatoires : sans elles, vous aurez plus de mal à réclamer des pénalités à un mauvais payeur. |
| **Dépannage chez les particuliers** | Si vous faites du dépannage, de la réparation ou de l'entretien (plomberie, électricité, chauffage...), cochez la case : vos devis indiqueront que le client peut garder les pièces remplacées, comme la loi l'exige. |
| **Signature** | Une image de votre signature et de votre tampon. Sans image, la case reste vide pour signer et tamponner à la main. |

### Les conditions générales de vente (CGV)

Facultatives, mais utiles. Ce sont vos règles du jeu : ce qui se passe si le client annule, si les travaux prennent du retard, si le chantier n'est pas accessible. Si vous n'en avez pas, cliquez sur « 📝 Mettre le squelette dans la zone » : c'est un texte à trous. Complétez ou supprimez chaque passage entre crochets. Tant qu'il en reste un, l'impression est bloquée, pour qu'aucun client ne reçoive des CGV à trous.

**Pourquoi elles comptent :** des CGV ne s'appliquent à votre client que s'il les a reçues et acceptées. C'est pour cela qu'elles s'impriment avec le devis, et que le cadre de signature précise qu'il les a lues.

### Changer quelque chose plus tard

Cliquez sur « ⚙️ Modifier ma configuration », faites votre changement, puis « 💾 Télécharger ma configuration ». **Remplacez l'ancien fichier par le nouveau**, sinon vous rechargerez l'ancienne version la prochaine fois.

---

## 3. Votre premier devis

### Pourquoi faire un devis ?

Le devis protège les deux côtés. Pour le client : il sait ce qu'il va payer. Pour vous : une fois signé, c'est un contrat. Si le client conteste plus tard, le devis signé fait foi.

Dans certains cas, il est même **obligatoire** : pour les travaux de dépannage, de réparation ou d'entretien chez un particulier (plomberie, chauffage, électricité, serrurerie, maçonnerie...), le devis est dû **quel que soit le montant**, même pour une intervention à 80 €. L'ancien seuil de 150 € a été supprimé en 2017. Il est aussi obligatoire dès que le client le demande. En pratique, faites-en un à chaque fois.

### Les étapes

1. **Remplissez le client, l'objet et la date prévue des travaux.** L'objet, c'est une phrase qui dit de quoi il s'agit (« Remplacement du chauffe-eau, 12 rue des Lilas »). La date des travaux sert ensuite pour la facture et pour la TVA.
2. **Ajoutez vos lignes** avec le cadre bleu « AJOUTER UNE LIGNE » : une prestation, une majoration, le déplacement, ou un titre pour découper le devis en parties. Une fois la ligne ajoutée, tout se modifie dessus : désignation, quantité, unité, prix, TVA.

3. **Lisez le cadre jaune « À vérifier avant d'envoyer ».** Il signale ce qui manque. Il est là pour vous éviter d'envoyer un devis incomplet.

4. **Cliquez sur « 💾 Enregistrer (.json) ».** Pourquoi : c'est ce fichier qui vous permettra de transformer le devis en facture plus tard, sans tout retaper.

5. **Cliquez sur « 🖨️ IMPRIMER LE DEVIS »** et choisissez votre imprimante PDF. Le nom du fichier (numéro du devis et nom du client) est déjà copié : Ctrl+V dans la case « Nom ». Envoyez ce PDF au client.

Les petits « i » ronds affichent une explication quand vous passez la souris dessus.

### Séparer la main-d'œuvre et les fournitures

Si vous fournissez du matériel (un chauffe-eau, du carrelage), mettez-le sur des lignes à part de la main-d'œuvre. Pourquoi :

- c'est plus clair pour le client ;

- en micro-entreprise, les ventes de matériel et les prestations n'ont pas le même taux de cotisations ni le même plafond (chapitre 8). Le logiciel s'appuie sur vos lignes pour faire le tri.

---

## 4. Du devis à la facture : acompte, solde, avoir

Le cadre vert « ET ENSUITE ? », en bas de l'écran, vous guide à chaque étape.

### Cas simple : pas d'acompte

Les travaux sont finis. Ouvrez le devis (« 📂 Ouvrir un devis ou une facture »), cliquez sur « Transformer ce devis en facture », complétez la date de la prestation, puis cliquez sur « ✅ ÉMETTRE ET IMPRIMER LA FACTURE ».

### Cas avec acompte

Un acompte, c'est une partie du prix payée d'avance, souvent à la signature. Il vous permet d'acheter le matériel sans avancer l'argent, et il engage le client.

1. **Le client a signé :** ouvrez le devis, cliquez sur « Faire la facture d'acompte », puis émettez-la. Gardez son fichier (par exemple `F-2026-001.json`).
2. **Les travaux sont finis :** ouvrez ce fichier `F-2026-001.json` et cliquez sur « Faire la facture de solde ». L'acompte est déduit tout seul, avec son numéro, sa date et son montant.

**Pourquoi une vraie facture pour l'acompte ?** Parce que l'argent encaissé doit être justifié par une facture, et que la TVA sur un acompte est due dès que vous l'encaissez (chapitre 7). Un simple « reçu » ne suffit pas.

### « Émettre », qu'est-ce que ça veut dire ?

Tant qu'une facture n'est pas émise, c'est un brouillon : vous pouvez tout changer. Quand vous cliquez sur « Émettre », elle reçoit son numéro définitif, elle est **verrouillée**, et son fichier `.json` est téléchargé pour vos archives.

**Pourquoi la verrouiller ?** Parce que la loi interdit de modifier une facture déjà envoyée. Si l'on pouvait changer une facture après coup, on pourrait cacher des ventes ou trafiquer la TVA. Le verrouillage vous protège : en cas de contrôle, vos factures prouvent d'elles-mêmes qu'elles n'ont pas été retouchées.

### Une erreur sur une facture émise : l'avoir

Une facture émise ne se modifie pas et ne se supprime pas. Pour corriger, on fait un **avoir** : une facture « en négatif » qui annule tout ou partie de la première. Ouvrez la facture et cliquez sur « Créer un avoir ». Il reprend toutes les lignes en négatif ; pour un avoir partiel, supprimez ou modifiez les lignes avant de l'émettre. Ensuite, si besoin, faites une nouvelle facture juste.

Exemple : vous avez facturé 10 heures au lieu de 8. Vous faites un avoir de 2 heures. Le client paie la facture moins l'avoir.

### Le délai de paiement

Indiquez toujours une date limite de paiement. Entre professionnels, la loi limite le délai à 60 jours après la date de facture (ou 45 jours fin de mois si c'est prévu au contrat) ; sans accord particulier, c'est 30 jours après la prestation. Pour un particulier, vous êtes libre, mais une date claire évite les « je pensais avoir le temps ».

### La facture électronique, en France

Depuis le 1er septembre 2026, toute entreprise doit pouvoir *recevoir* des factures électroniques. Une facture électronique n'est pas un PDF envoyé par mail : c'est un fichier structuré, transmis par une plateforme agréée par l'administration.

L'obligation d'en *émettre* arrive pour les petites entreprises et les micro-entrepreneurs le 1er septembre 2027, et seulement pour les factures à des clients professionnels établis en France. Pour vos clients particuliers, la facture PDF reste possible, mais à la même date vos ventes aux particuliers devront être déclarées à l'administration (e-reporting), elles aussi via une plateforme agréée.

L'Établi fait des factures PDF et ne transmet rien à une plateforme. D'ici là, rien ne change pour vous. Le moment venu, certaines plateformes agréées acceptent vos factures PDF et les transforment en factures électroniques, parfois gratuitement (Indy, par exemple).

---

## 5. La numérotation : pourquoi elle est si surveillée

La loi impose que vos factures soient numérotées **dans une suite continue, sans trou ni doublon**.

**Pourquoi :** un trou dans la numérotation, c'est le premier signe qu'une facture a été « oubliée » pour ne pas déclarer la vente. Un contrôleur des impôts commence souvent par là. Une numérotation propre, c'est la preuve simple que vous déclarez tout.

Ce que fait L'Établi :

- les devis et les factures ont chacun leur compteur (vous pouvez en être au devis n° 10 et à la facture n° 3, c'est normal : tous les devis ne sont pas acceptés) ;

- factures, factures d'acompte et avoirs se suivent dans la même série : F-2026-001, F-2026-002, et ainsi de suite. La série repart à 001 chaque année, ce qui est autorisé parce que l'année fait partie du numéro ;

- le numéro suivant est proposé tout seul, et le logiciel vous prévient si un numéro est déjà pris ou s'il en saute un ;

- l'onglet « ✅ Contrôles » de la comptabilité liste les numéros manquants.

**Si le compteur a été perdu** (nouvel ordinateur, historique effacé) : ouvrez votre dernière facture `.json`, le compteur se remet à jour. Ou indiquez le dernier numéro émis dans « Modifier ma configuration », à l'étape Signature. Pour ne pas en arriver là : quand le bandeau jaune le propose, téléchargez de nouveau votre configuration, elle contient le compteur.

**Et une facture en mode démo ?** Le mode démo (SPÉCIMEN) sert aux essais. Il ne prend pas de numéro, justement pour ne pas créer de trou.

---

## 6. La comptabilité au quotidien

### À quoi sert la comptabilité, concrètement ?

À trois choses :

1. **Savoir combien vous déclarez** : chiffre d'affaires pour l'URSSAF, TVA pour les impôts.

2. **Prouver ce que vous déclarez** : en cas de contrôle, chaque chiffre doit renvoyer à une pièce (une facture, un ticket).

3. **Savoir où vous en êtes** : qui vous doit de l'argent, combien vous dépensez.

La comptabilité de L'Établi est réservée à la France, et elle s'ouvre quand votre configuration est chargée. Deux grands boutons apparaissent en haut : « 📝 Devis et factures » et « 📒 Comptabilité ».

### Créer votre dossier de l'année

1. Cliquez sur « 📒 Comptabilité », indiquez l'année, puis « ✨ Créer un nouveau dossier ». Il y a **un dossier par année**, parce que la comptabilité et les déclarations se font par année.
2. Cliquez sur « 📥 Importer des factures (.json) » et sélectionnez d'un coup tous les fichiers de vos factures de l'année (Ctrl+A dans la fenêtre). Ensuite, chaque facture que vous émettez s'ajoute toute seule au dossier ouvert.

3. Cliquez sur « 💾 Enregistrer le dossier » : un fichier `compta_2026_... .json` est téléchargé. Rangez-le avec votre configuration. Le bouton « 💾 Tout enregistrer », en haut de l'écran, télécharge d'un coup votre configuration et votre dossier, avec des noms assortis. La première fois, le navigateur peut demander s'il a le droit de télécharger plusieurs fichiers : cliquez sur « Autoriser ».
4. **La fois suivante**, sur l'accueil, cliquez sur « 📂 Charger ma configuration » et sélectionnez les deux fichiers ensemble : la configuration et le dossier comptable (clic sur l'un, puis Ctrl + clic sur l'autre). Tout s'ouvre d'un coup. Vous pouvez aussi charger la configuration seule, puis « 📂 Ouvrir un dossier » dans la comptabilité.

**Un dossier, une entreprise.** Le dossier comptable reste attaché à l'entreprise de la configuration qui l'a créé (son SIREN). Si vous gérez deux entreprises et que vous ouvrez le dossier de l'une avec la configuration de l'autre, le logiciel refuse ou bloque, sans rien modifier. Pourquoi : des factures ou des dépenses rangées dans la mauvaise entreprise, c'est une comptabilité fausse, et parfois un fichier FEC au mauvais nom.

**Le bouton « Enregistrer le dossier » devient rouge** tant que des modifications ne sont pas enregistrées dans votre fichier. Pourquoi tant d'insistance : la mémoire du navigateur peut être vidée à tout moment (un nettoyage, une mise à jour, un autre ordinateur). Votre fichier, lui, reste. Prenez l'habitude : vous finissez une saisie, vous enregistrez.

### Un client a payé : l'encaissement

Onglet « 🧾 Ventes et encaissements », bouton « + encaissement » sous la facture. Indiquez le montant, le mode de paiement et **la date où l'argent est arrivé sur votre compte**.

**Pourquoi la date d'encaissement est si importante :** une facture n'est pas de l'argent. Pour un artisan ou un prestataire, la TVA est due quand le client paie, pas quand vous facturez. Et en micro-entreprise, l'URSSAF vous demande de déclarer ce que vous avez **encaissé**, pas ce que vous avez facturé. C'est donc cette date qui décide du mois de votre déclaration. Le champ est surligné en jaune pour cette raison, et le calendrier refuse une date antérieure à la facture ou dans le futur.

Un client qui paie en deux fois : deux encaissements. Un chèque : la date à retenir est celle où il est crédité sur votre compte, regardez votre relevé.

### Un client ne paie pas : les relances

Une facture impayée, c'est du travail fait gratuitement tant que l'argent n'est pas arrivé. Le plus souvent, c'est un oubli : un simple rappel suffit. Mais plus on attend, plus c'est difficile à récupérer.

Le logiciel surveille la **date d'échéance** de chaque facture (la date limite de paiement imprimée dessus). Dès qu'elle est dépassée et que la facture n'est pas entièrement encaissée :

- un encadré « 🔔 factures à relancer » apparaît sur le tableau de bord, et une pastille sur l'onglet « Ventes et encaissements » ;
- sous la facture, le bouton « relancer » vous dit **quoi faire à cette étape**.

Les étapes, dans l'ordre :

1. **Un rappel simple**, par téléphone ou par mail : numéro de facture, montant, échéance, et « quand le paiement est-il prévu ? ».
2. **Une relance écrite plus ferme**, avec un nouveau délai (par exemple 8 jours).
3. **La mise en demeure**, par lettre recommandée avec accusé de réception : elle réclame la somme et fixe un dernier délai avant une action en justice. Gardez la preuve d'envoi.
4. **Les recours** : sous 5 000 €, la procédure simplifiée de recouvrement des petites créances, menée par un commissaire de justice ; sinon, ou si le client conteste, l'injonction de payer devant le tribunal. La fiche officielle est sur entreprendre.service-public.fr.

Pour un client **professionnel**, vos factures prévoient des pénalités de retard (3 fois le taux de l'intérêt légal) et une indemnité forfaitaire de 40 € pour frais de recouvrement : le logiciel calcule le montant dû à ce jour. Pour un client **particulier**, il n'y a pas de pénalités sur vos factures ; après une mise en demeure, des intérêts au taux légal peuvent être réclamés.

**Le logiciel ne relance personne à votre place.** C'est vous qui appelez ou qui écrivez. Ensuite, cliquez sur « Noter la relance » : la date, le moyen (téléphone, mail, recommandé...) et une note (« promet de payer vendredi »). La relance suivante est proposée 15 jours plus tard. Pourquoi noter : si l'affaire va devant un juge, l'historique de vos relances prouve que vous avez laissé sa chance au client.

Ne laissez pas traîner : le délai pour agir en justice est de **2 ans contre un particulier** et de **5 ans contre un professionnel**. Les réglages (combien de jours après l'échéance être prévenu, écart entre deux relances) sont dans l'onglet « ⚙️ Paramètres ». Une facture de l'an dernier encore impayée : importez-la dans le dossier de cette année pour continuer à la suivre.

### Une dépense : le justificatif

Onglet « 🛒 Dépenses », bouton « Photo ou PDF du justificatif ». Prenez en photo le ticket ou choisissez la facture PDF du fournisseur. Pour une bonne lecture, tenez le téléphone bien au-dessus du ticket, posé à plat, sans reflet de lampe : une photo prise en biais ou éblouie se lit mal, et le logiciel préfère alors ne rien remplir plutôt que de se tromper. Le logiciel lit le document et remplit les cases tout seul, en jaune : la date, le fournisseur, le numéro de facture, les montants et la TVA.

**Vérifiez toujours les cases jaunes.** La lecture automatique peut se tromper, surtout sur un ticket froissé ou mal éclairé. C'est vous qui validez, et c'est vous qui répondez des chiffres.

Puis :

1. **Choisissez la catégorie.** Le logiciel en propose une d'après le fournisseur et le contenu, mais vous devez la confirmer. Pourquoi c'est obligatoire : la catégorie décide si la TVA est récupérable, et dans quel compte la dépense va chez le comptable.

2. **Enregistrez.** La dépense reçoit un numéro de pièce (A-2026-001, A-2026-002...).

3. **Écrivez ce numéro au dos du ticket** ou sur la facture papier, et rangez-le. Pourquoi : en cas de contrôle, on vous demandera « montrez-moi la pièce A-2026-047 ». Vous la retrouvez en dix secondes.

**La photo ne remplace pas l'original.** Pour qu'une copie numérique ait la même valeur légale que le papier, la loi exige un procédé certifié (signature électronique, horodatage, image sans aucune retouche) qu'un logiciel gratuit hors ligne ne peut pas offrir. La photo sert au classement et à la saisie. **Gardez le ticket ou la facture papier pendant 10 ans.** Astuce : les tickets de caisse thermiques s'effacent avec le temps, faites-en une photocopie et agrafez-la à l'original.

### Les catégories qui posent question

| Situation | Catégorie | Pourquoi |
|---|---|---|
| Matériaux, fournitures, petits outils | « Fournitures, matériaux de chantier et petit outillage » | Un outil de moins de 500 € HT l'unité passe directement en dépense. |
| Un outil ou une machine de plus de 500 € HT l'unité | « Gros outil ou machine (à amortir) » | Au-delà de 500 € HT, l'outil dure plusieurs années : il est « amorti », c'est-à-dire que son coût est étalé sur sa durée d'usage. Le seuil se juge **outil par outil**, jamais sur le total de la facture. Le matériel que vous posez chez le client n'est jamais amorti, quel que soit le prix. |
| Carburant d'un utilitaire | « Carburant véhicule utilitaire » | TVA récupérable à 100 %. |
| Carburant d'une voiture ou d'un pick-up double cabine | « Carburant véhicule de tourisme » | TVA récupérable à 80 % seulement. Le pick-up double cabine est traité comme une voiture. |
| Entretien d'une voiture de tourisme | « Entretien, réparation véhicule de tourisme » | TVA non récupérable. |
| Restaurant | « Repas au restaurant » | TVA récupérable si le repas est professionnel. Sous 150 € HT, un ticket suffit **à condition d'y écrire le nom et l'adresse de votre entreprise**. Au-delà, demandez une vraie facture. |
| Hôtel, train, avion, taxi | « Hôtel » ou « Train, avion, taxi » | La dépense est déductible de votre bénéfice, mais la TVA sur le transport de personnes n'est pas récupérable. Le logiciel ne la compte pas, par prudence pour l'hôtel aussi. |
| Cadeaux clients | « Cadeaux clients » | TVA récupérable jusqu'à 73 € TTC par cadeau et par client sur l'année. |
| Facture d'un sous-traitant du bâtiment **sans TVA** (mention « autoliquidation ») | « Sous-traitance », puis cochez « Facture sans TVA d'un sous-traitant du bâtiment » | C'est vous qui déclarez cette TVA, et vous la déduisez en même temps (chapitre 7). Indiquez le taux des travaux chez votre client : le logiciel calcule le reste. |
| Facture d'un sous-traitant **avec** TVA | « Sous-traitance » | Normal pour une prestation (contrôle, étude, transport...). Mais si ce sont des travaux du bâtiment sur un de vos chantiers, il aurait dû facturer sans TVA : l'onglet « Contrôles » vous le signale. |

### Une facture qui mélange plusieurs choses

Par exemple chez un grossiste : des fournitures, et une perceuse à 600 € HT. Cliquez sur « Répartir sur plusieurs catégories » et indiquez le montant de chaque partie. Pourquoi : la perceuse doit être amortie, les fournitures non. Une seule catégorie pour tout donnerait un résultat faux.

### Une erreur après validation

Rien ne s'efface. Le bouton « corriger » (dépenses) ou « annuler » (encaissements) garde la trace de l'ancienne version. Pourquoi : comme pour les factures, une comptabilité où l'on peut effacer sans trace n'a aucune valeur de preuve. Corriger en laissant une trace, c'est montrer que vous êtes de bonne foi.

### Les autres onglets

- **📊 Tableau de bord** : vos ventes mois par mois. Bleu foncé = payé, bleu clair = pas encore payé. Une barre orange signale un mois où vos dépenses dépassent ce que vous avez facturé. En haut, l'encadré des factures à relancer, quand il y en a.
- **💶 TVA** (si vous facturez la TVA) : la TVA à déclarer, mois par mois ou trimestre par trimestre.

- **📒 Micro-entreprise** (si vous êtes micro) : le chiffre d'affaires à déclarer à l'URSSAF, le livre des recettes et le registre des achats.

- **✅ Contrôles** : numéros de facture manquants, dates incohérentes, seuils dépassés. Une pastille rouge indique le nombre d'alertes. Faites-y un tour avant chaque déclaration.

- **📤 Exports** : PDF, tableurs (CSV) et fichier FEC pour votre comptable.

- **⚙️ Paramètres** : un résumé de votre configuration, en clair, les réglages des relances et les taux utilisés pour l'année.

---

## 7. La TVA expliquée simplement

### Le principe

La TVA est un impôt payé par le client final, que vous **collectez** pour l'État. Vous n'êtes qu'un intermédiaire : l'argent de la TVA ne vous appartient pas.

- Sur vos ventes, vous ajoutez de la TVA : c'est la **TVA collectée**.
- Sur vos achats professionnels, vous en payez : c'est la **TVA déductible**.

- Vous reversez à l'État la différence : TVA collectée moins TVA déductible.

Exemple : vous facturez 1 000 € HT + 200 € de TVA. Pour ce chantier, vous avez acheté 300 € HT de matériel + 60 € de TVA. Vous reversez 200 − 60 = 140 €.

**Le piège classique du débutant :** considérer les 1 200 € comme son argent. Les 200 € de TVA ne sont pas à vous. Mettez-les de côté dès l'encaissement, par exemple sur un compte épargne de l'entreprise, pour ne pas être pris de court le jour de la déclaration.

### La franchise : quand vous ne facturez pas de TVA

En dessous de certains seuils de chiffre d'affaires annuel, vous pouvez être en **franchise en base de TVA**. C'est souvent le cas des micro-entrepreneurs qui démarrent. En 2026, les seuils sont de 85 000 € pour les ventes de marchandises et de 37 500 € pour les prestations de services.

En franchise :

- vous ne facturez pas de TVA, et la mention « TVA non applicable, art. 293 B du CGI » est obligatoire sur vos factures (le logiciel l'imprime) ;

- vous ne récupérez pas la TVA sur vos achats ;

- l'onglet TVA n'apparaît pas, puisqu'il n'y a rien à déclarer.

Au 1er janvier 2027, les règles de TVA changent de code (elles passent du Code général des impôts au Code des impositions sur les biens et services). Le fond ne change pas, et la mention « art. 293 B du CGI » reste admise sur les factures jusqu'au 30 juin 2028. Le logiciel sera mis à jour d'ici là.

**Attention au dépassement :** si vous dépassez les seuils majorés (93 500 € pour les ventes, 41 250 € pour les services), vous devez facturer la TVA dès le jour du dépassement. L'onglet « Contrôles » vous prévient.

**Pourquoi rester en franchise ou non ?** En franchise, vos prix sont plus bas pour un particulier, qui ne récupère pas la TVA. Mais vous ne récupérez rien sur vos achats. Si vous achetez beaucoup de matériel ou si vos clients sont surtout des professionnels (qui, eux, récupèrent la TVA), facturer la TVA peut être plus intéressant. C'est un vrai choix à faire selon votre activité.

### Quand la TVA est-elle due ?

C'est la question qui fait trébucher tout le monde.

- **Prestations de services et travaux** (le cas de la plupart des artisans) : la TVA est due **quand le client paie**, acomptes compris. Pas à la date de facture. C'est la raison pour laquelle la date d'encaissement compte autant (chapitre 6).
- **Ventes de marchandises** : la TVA est due à la livraison. Un acompte encaissé sur une vente rend toutefois la TVA due dès son encaissement.

- Il existe une option pour payer la TVA des services dès la facturation (« option pour les débits »). Elle se choisit dans la configuration, si vous l'avez demandée aux impôts.

Le logiciel fait ce calcul tout seul, y compris quand un client paie une facture à plusieurs taux en plusieurs fois.

### La TVA sur vos achats

Vous pouvez la déduire si :

- la dépense sert votre activité ;

- vous avez une facture (ou un ticket valable) qui indique le taux et le montant de TVA ;

- elle n'entre pas dans une exclusion (voir le tableau du chapitre 6).

Pour un service acheté, la TVA se déduit le mois où vous le payez. Pour un bien, le mois de l'achat.

### Les taux dans le bâtiment

- **20 %** : le taux normal, et les constructions neuves.
- **10 %** : travaux d'amélioration, de transformation, d'aménagement ou d'entretien dans un logement de plus de 2 ans.

- **5,5 %** : travaux de rénovation énergétique dans un logement de plus de 2 ans.

Les taux réduits demandent que le client confirme l'âge et l'usage du logement. Si vous n'êtes pas sûr du taux, appliquez 20 % ou renseignez-vous : un taux réduit appliqué à tort, c'est vous qui payez la différence en cas de contrôle.

### La sous-traitance dans le bâtiment : l'autoliquidation

Quand une entreprise du bâtiment confie une partie de ses travaux à un sous-traitant, la TVA ne suit pas le chemin habituel. Le sous-traitant facture **sans TVA**, avec la mention « autoliquidation », et c'est l'entreprise principale qui déclare la TVA à sa place.

- **Vous êtes le sous-traitant** : cochez « Autoliquidation » sur la facture (client professionnel). Le logiciel imprime la mention obligatoire et ne compte pas de TVA : c'est votre client qui la déclare.
- **Vous êtes l'entreprise principale** : la facture de votre sous-traitant arrive sans TVA. Saisissez-la en « Sous-traitance » et cochez la case prévue. Vous devez **déclarer** cette TVA (au taux des travaux chez votre client : 20, 10 ou 5,5 %) et vous la **déduisez** sur la même déclaration, le mois où vous payez le sous-traitant. Elle ne vous coûte rien, mais elle doit figurer sur votre déclaration : l'onglet TVA la montre dans une colonne à part.

**Pourquoi ce système ?** Pour éviter qu'un sous-traitant encaisse la TVA puis disparaisse sans la reverser. Si un sous-traitant du bâtiment vous facture quand même la TVA, cette TVA facturée à tort n'est pas déductible : demandez-lui une facture rectifiée.

### Déclarer

Le logiciel vous donne les montants. La déclaration elle-même se fait sur votre espace professionnel, sur impots.gouv.fr, avec le formulaire CA3. Recopiez les chiffres de l'onglet TVA, qui les donne mois par mois et trimestre par trimestre.

**Attention, changement au 1er janvier 2027 :** le régime simplifié (une déclaration CA12 par an et deux acomptes en juillet et décembre) est supprimé. Les entreprises qui l'utilisaient passent à une déclaration CA3 mensuelle ou trimestrielle. Si vous étiez au régime simplifié en 2026, votre dernière CA12 porte sur 2026, puis vous déclarez en CA3 dès janvier ou dès le premier trimestre 2027.

---

## 8. Micro-entreprise ou régime réel : ce qui change pour vous

### La micro-entreprise

C'est le régime le plus simple. Vous déclarez votre **chiffre d'affaires encaissé** à l'URSSAF, chaque mois ou chaque trimestre, et vous payez un pourcentage dessus. Vous ne déduisez pas vos dépenses : un abattement forfaitaire est appliqué à votre place pour l'impôt sur le revenu.

Taux de cotisations 2026 :

| Activité | Cotisations | Versement libératoire de l'impôt (option) | Abattement pour l'impôt |
|---|---|---|---|
| Vente de marchandises | 12,3 % | 1 % | 71 % |
| Prestations artisanales ou commerciales | 21,2 % | 1,7 % | 50 % |
| Professions libérales | 25,6 % | 2,2 % | 34 % |

Plafonds de chiffre d'affaires : 203 100 € au total, dont 83 600 € de prestations au maximum. Dépasser deux années de suite fait sortir du régime.

**Pourquoi séparer ventes et prestations ?** Un artisan qui fournit le matériel a une activité « mixte » : le matériel revendu est une vente (12,3 %), la pose est une prestation (21,2 %). Déclarer tout en prestations, c'est payer trop. Déclarer tout en ventes, c'est payer trop peu et risquer un redressement. Le logiciel fait le tri à partir de vos lignes de facture. L'onglet « Micro-entreprise » vous donne les deux montants, mois par mois.

**Le livre des recettes et le registre des achats.** En micro, la loi vous demande de tenir la liste de vos encaissements (date, client, montant, mode de paiement, numéro de facture) et, si vous vendez des marchandises, la liste de vos achats. Le logiciel les tient pour vous à partir de vos saisies, et les exporte en PDF.

**Un piège :** en micro, vos dépenses ne baissent pas vos cotisations. Si vous dépensez beaucoup en matériel, le régime réel peut devenir plus intéressant. C'est une bonne question à poser à un comptable une fois par an, quand vous avez vos chiffres.

### Le régime réel

Vous payez des impôts et des cotisations sur votre **bénéfice** : ce que vous gagnez moins ce que vous dépensez. C'est plus juste si vous avez beaucoup de frais, mais la comptabilité est plus lourde (bilan, compte de résultat). Les sociétés (SASU, EURL, SARL...) y sont généralement soumises.

Dans ce cas, L'Établi tient le suivi de vos ventes, encaissements, dépenses et TVA, et prépare le fichier FEC pour votre comptable. Le bilan annuel reste son travail.

---

## 9. Ce que fait le comptable, et le fichier FEC

### Avez-vous besoin d'un comptable ?

- **En micro-entreprise :** en général non. Si vous tenez vos encaissements, vos dépenses et vos déclarations avec rigueur, vous pouvez vous en passer. Ce guide et le logiciel sont faits pour ça.
- **Au régime réel ou en société :** c'est fortement conseillé. Le bilan, la liasse fiscale et certaines déclarations demandent un vrai savoir-faire.

L'intérêt de bien tenir votre comptabilité dans L'Établi, même avec un comptable : il passera moins de temps sur votre dossier, donc il vous coûtera moins cher.

### Le FEC, c'est quoi ?

Le **fichier des écritures comptables** est un fichier au format imposé par l'administration. En cas de contrôle fiscal, une entreprise qui tient une comptabilité sur ordinateur doit pouvoir le fournir. C'est aussi un moyen simple de transmettre vos opérations à un comptable : son logiciel l'importe directement.

Onglet « 📤 Exports », carte « FEC pour le comptable ». Le fichier est nommé selon la règle officielle : votre SIREN, « FEC », puis la date de clôture (par exemple `123456789FEC20261231.txt`). Vérifiez que votre SIREN est bien renseigné dans la configuration.

**Pourquoi des numéros de comptes (6068, 626...) apparaissent dans le FEC ?** Les comptables classent les opérations selon un plan comptable national. Chaque catégorie de dépense correspond à un compte. Vous n'avez pas à les connaître : le logiciel s'en charge.

Deux détails qui font gagner du temps à votre comptable : la TVA de vos prestations reste « en attente » jusqu'au paiement du client (compte 44574), puis passe en TVA due (compte 44571), et chaque facture est « lettrée » avec son paiement, c'est-à-dire marquée d'une même lettre quand elle est soldée.

### Que donner au comptable ?

- le fichier FEC ;
- les exports PDF ou CSV, s'il les demande ;

- vos relevés bancaires de l'année ;

- les originaux des justificatifs, s'il veut les voir.

---

## 10. Les fichiers à garder, et pendant combien de temps

### Ce que vous devez garder

Rangez tout dans un même dossier, par année :

| Fichier | À quoi il sert |
|---|---|
| `config_devis_... .json` | Votre configuration. Sans lui, il faut tout ressaisir. |
| `D-2026-001.json`... | Chaque devis, pour le rouvrir ou le facturer. |
| `F-2026-001.json`... | Chaque facture émise. Il prouve le contenu exact de la facture. |
| Les PDF envoyés aux clients | Ce que le client a réellement reçu. |
| `compta_2026_... .json` | Votre dossier comptable de l'année, avec les photos des justificatifs et l'historique de vos relances. |
| Les tickets et factures papier | Les originaux de vos dépenses. |

**Durée de conservation : 10 ans** à compter de la clôture de l'année. Le délai fiscal est de 6 ans, mais le Code de commerce impose 10 ans pour les pièces comptables : retenez 10 ans pour tout.

### Les sauvegardes

Vos fichiers ne sont que sur votre ordinateur : c'est ce qui garantit leur confidentialité, mais c'est aussi un risque. Un disque dur qui lâche, un vol, et dix ans d'archives disparaissent.

La règle simple : **trois copies, sur deux supports différents, dont une hors de chez vous.** Par exemple : l'ordinateur, une clé USB ou un disque externe, et une copie chez un proche ou dans un coffre. Faites la copie au moins une fois par mois, et chaque fois que vous fermez une année.

---

## 11. Les erreurs les plus fréquentes

1. **Oublier d'enregistrer le dossier comptable.** Le bouton rouge est là pour ça. Saisie finie, fichier enregistré.
2. **Garder l'ancienne configuration** après une modification. Remplacez toujours l'ancien fichier par le nouveau.

3. **Mettre la date de facture à la place de la date d'encaissement.** La TVA et l'URSSAF tombent alors le mauvais mois.

4. **Dépenser la TVA encaissée.** Elle n'est pas à vous. Mettez-la de côté.

5. **Supprimer une facture ratée** au lieu de faire un avoir. Cela crée un trou dans la numérotation.

6. **Jeter les tickets après les avoir photographiés.** La photo n'a pas la valeur de l'original.

7. **Ne pas écrire le nom de l'entreprise sur un ticket de restaurant.** Sans cela, la TVA n'est pas récupérable.

8. **Mettre un gros outil en fournitures.** Au-delà de 500 € HT l'unité, il s'amortit.

9. **Mélanger les comptes personnels et professionnels.** Utilisez un compte bancaire dédié : c'est obligatoire en micro-entreprise dès que le chiffre d'affaires dépasse 10 000 € deux années de suite (et dès le départ pour une activité commerciale), et c'est de toute façon bien plus simple pour retrouver vos encaissements. Un simple compte courant séparé suffit, pas besoin d'un compte « pro » payant.

10. **Accepter les cases jaunes sans les lire.** La lecture automatique est une aide, pas une garantie.

11. **Ouvrir le logiciel tantôt en ligne, tantôt par le fichier.** Choisissez une façon et tenez-vous-y.

12. **Appliquer un taux de TVA réduit sans vérifier** l'âge et l'usage du logement.

13. **Laisser traîner un impayé** par gêne. Relancez dès l'échéance passée : plus on attend, moins on récupère.

14. **Déduire la TVA d'un sous-traitant du bâtiment** qui l'a facturée alors qu'il devait être en autoliquidation. Demandez-lui une facture rectifiée.

---

## 12. Lexique

**Acompte** : partie du prix payée avant la fin des travaux. Il fait l'objet d'une facture d'acompte.

**Autoliquidation** : mécanisme où c'est le client professionnel, et non le vendeur, qui déclare la TVA. Il s'applique notamment à la sous-traitance dans le bâtiment.

**Amortissement** : étalement du coût d'un bien durable (outil de plus de 500 € HT, véhicule) sur sa durée d'usage, au lieu de le compter en une fois.

**Avoir** : facture en négatif qui annule tout ou partie d'une facture émise.

**CGV** : conditions générales de vente, vos règles du jeu avec le client.

**Chiffre d'affaires (CA)** : total de vos ventes, hors taxes. En micro, on déclare le CA encaissé.

**Encaissement** : arrivée de l'argent sur votre compte.

**Émettre** : rendre une facture définitive. Elle reçoit son numéro et ne se modifie plus.

**FEC** : fichier des écritures comptables, au format imposé par l'administration.

**Franchise en base de TVA** : régime qui dispense de facturer la TVA sous certains seuils.

**HT, TTC** : hors taxes, toutes taxes comprises. TTC = HT + TVA.

**Justificatif, pièce** : document qui prouve une opération (facture, ticket).

**Livre des recettes** : liste chronologique de vos encaissements, obligatoire en micro-entreprise.

**Mise en demeure** : lettre (en recommandé avec accusé de réception) qui réclame officiellement une somme due et fixe un dernier délai avant une action en justice.

**Micro-entreprise** : régime simplifié où l'on paie un pourcentage du chiffre d'affaires encaissé.

**Régime réel** : régime où l'on est imposé sur le bénéfice réel (recettes moins dépenses).

**SIREN, SIRET** : numéros d'immatriculation de votre entreprise (9 et 14 chiffres).

**TVA collectée, déductible** : la TVA que vous facturez, et celle que vous payez sur vos achats.

**URSSAF** : organisme qui collecte vos cotisations sociales.

**Versement libératoire** : option de la micro-entreprise qui permet de payer l'impôt sur le revenu en même temps que les cotisations, par un petit pourcentage du chiffre d'affaires.

---

*L'Établi est un logiciel gratuit, créé par HivertLabs. Une question, une erreur dans ce guide, une idée ? Écrivez à hivertlabs@hotmail.com.*
