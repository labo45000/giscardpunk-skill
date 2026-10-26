---
name: "giscardpunk"
description: "Reproduire fidèlement le style GiscardPunk, un rétrofuturisme français des années 1970-80 à base d'archives imprimées, de photos d'époque, de typographies grotesques et de palette chaude délavée. Utiliser pour créer une maquette, un visuel, un post, un décor ou un prompt de génération d'image dans ce style, ou quand l'utilisateur mentionne GiscardPunk, le compte @giscardpunk ou un style 'années 70-80 rétrofuturiste à la française'."
---

# GiscardPunk Design

Ce skill sert à produire des visuels qui ressemblent à ceux du compte Instagram @giscardpunk. Le style n'est pas un design moderne « rétro » : c'est la culture graphique et photographique française des années 1970-80, vue comme une archive d'une France uchronique où l'ère Giscard aurait pris une autre direction technologique.

Les mesures chiffrées sont dans `references/palette-and-stats.md`. Consulte le compte Instagram @giscardpunk pour voir le style avant de produire quoi que ce soit : une description écrite ne remplace pas l'œil.

## 1. Règle de fidélité

- Le but est que le résultat paraisse extrait d'une archive imprimée ou d'une photo d'époque, pas d'un site contemporain qui imite le style.
- Quand une règle de ce skill et une bonne pratique web moderne se contredisent, suis le skill. Exemples : pas de glassmorphism, pas de dégradés doux, pas de coins arrondis type app.
- Si la demande est vague (« un truc dans le style »), choisis une famille visuelle (section 3) et dis-le à l'utilisateur. Ne demande que si le format de sortie est inconnu.
- Ne prétends jamais qu'une image est une vraie archive. Si tu génères un visuel, présente-le comme une création dans le style, sauf si l'utilisateur fournit lui-même une source.

## 2. Diagnostic du corpus (801 visuels)

- Le compte publie surtout des documents d'époque : publicités, couvertures de magazines et de catalogues, affiches, photos de presse, brochures, cartes postales. Quelques visuels sont retravaillés (grilles 3D, illustrations, mises en scène).
- Sujets récurrents : architecture brutaliste et béton, trains et métros (TGV, RER, métros à pneus), Concorde, automobiles des années 70-80 (Renault, Citroën, Peugeot, Simca), ordinateurs personnels et Minitel, bureaux et intérieurs, science-fiction et espace (navette, stations orbitales), infrastructures (ponts, centrales, réseaux).
- Dominante : tons moyens, légèrement délavés, 40 % de pixels chauds (orange, brun, beige), 35 % de neutres, 19 % de tons froids (bleu, cyan).

## 3. Les cinq familles visuelles

Choisis une famille par visuel. Un même post peut mélanger deux familles, mais garde une dominante claire.

### A. Photo couleur d'archive (la plus fréquente)
- Photo de presse ou de catalogue des années 70-80, teintes chaudes et délavées.
- Noirs légèrement relevés, blancs crème, dominante orange-brun ou jaune-vert selon la source.
- Grain visible, léger flou de mise au point, parfois trame d'impression visible.
- Sujets : voiture en plan 3/4, train à grande vitesse en mouvement, intérieur de bureau, ville avec immeubles en barre.

### B. Publicité imprimée
- Titre immense en haut, en grotesque bold, parfois en capitales blanches sur fond noir (exemple : pub Concorde/Rolex).
- Image produit ou scène au centre, en noir et blanc ou en couleur, avec une légende.
- Texte d'accompagnement en petit corps, aligné à gauche, en bas à gauche.
- Logo ou signature en bas à droite.
- Ajouter un élément graphique simple : bande de couleur, cadre fin, signe de marque.

### C. Couverture de magazine ou illustration (aérographe, gouache)
- Illustration peinte ou aérographiée, aplats nets, contours marqués.
- Titre en lettres détourées (contour noir, remplissage jaune ou blanc, ombre portée) : style couverture L'Ordinateur Individuel.
- Bandeau rouge ou jaune en biais pour un accroche courte (« Le BBC au banc d'essai »).
- Sujets : ordinateurs, futurs de la conquête spatiale, paysages mis en scène, personnages en costume.

### D. Photo noir et blanc d'architecture ou de presse
- Béton brut en grand plan, lignes horizontales, volumes en décrochés, ciel gris clair.
- Contraste fort, noirs profonds, gris moyens riches.
- Ajout possible d'un signe graphique rouge sur le bâtiment (exemple : logo rouge sur mur béton).
- Cadrage en biais ou en contre-plongée, perspective marquée.

### E. Visuel 3D numérique rétro
- Grille de fil de fer bleu (lignes fines) sur fond bleu nuit, déformée autour d'un objet.
- Objet (voiture, bâtiment) découpé et posé sur la grille, éclairage plat, ombre minimale.
- Palette très limitée : bleu nuit, bleu fil, un objet rouge ou jaune.

## 4. Palette

Couleurs de base (mesurées, détail dans `references/palette-and-stats.md`) :
- Blanc papier : #F8F8F8, ou ivoire chaud #F0F0D0
- Noir d'encre : #080808
- Gris béton : #787878 à #A8A8A8
- Brun foncé : #503010, brun moyen : #705030
- Pêche pâle : #F0D0B0, beige sable : #D0B090
- Sienne : #905030, ocre : #907030, moutarde : #D0B070
- Bordeaux : #501010
- Bleu poudre : #90B0D0, bleu ciel : #70B0D0

Accents vifs (estimés sur les planches, pas mesurés) :
- Rouge : proche de #D8301E
- Jaune : proche de #F5C400
- Orange : proche de #F07820
- Turquoise : proche de #2A9A98
- Bleu nuit (3D) : proche de #0A0F2A

Règles de combinaison :
- Un fond neutre (papier ou béton), un accent vif dominant (rouge, jaune ou orange) et un accent secondaire (turquoise ou bleu).
- Pour les photos, garde la dominante chaude. Les bleus ne doivent pas écraser le visuel, sauf pour les ciels et les visuels 3D.
- Pas de couleur fluo ou néon pure, pas de dégradé arc-en-ciel.

## 5. Typographie

Le corpus contient plusieurs familles typographiques d'époque. Choisis-en une par visuel :
- Grotesque bold (évoque Univers ou Helvetica Bold) : titres en capitales ou casse mixte, interlignage serré. Pour les accroches de pub et les titres de magazine.
- Display géométrique des années 70 (évoque Microgramma ou Eurostile) : lettres larges et arrondies, pour les logos, les noms de produits et les titres d'affiche.
- Lettres détourées (contour net, remplissage contrasté, ombre portée) : pour les couvertures de magazine.
- Script ou italique display (exemple : titre « Massacre Vidéotex ») : pour les titres d'affiche ou de dossier, avec un contraste fort.

Règles :
- Le texte d'accompagnement est petit, justifié à gauche, en noir sur fond clair ou en blanc sur fond sombre.
- Les titres sont très gros, souvent coupés par l'image.
- Pas de polices modernes à chasse variable (Inter, SF, Roboto) et pas de police arrondie type app.

## 6. Composition et cadrage

- Cadrage central, monumental, souvent symétrique pour l'architecture et les objets.
- Plan large ou plan rapproché sur un objet, rarement de sujets coupés au hasard.
- Beaucoup de ciel ou de fond uni : au moins un tiers de l'image quand c'est possible.
- Perspective légèrement en contre-plongée pour les bâtiments, en plan 3/4 pour les voitures.
- Présence humaine discrète : silhouettes, passants, personnes en costume ou en tenue des années 70.
- Mise en page de magazine : bandeau de titre en haut, zone image au milieu, texte court en bas.

## 7. Traitement de l'image

- Grain fin à moyen sur les photos couleur, trame d'impression visible sur les imprimés.
- Teintes délavées : noirs à #080808 à #181818, blancs à #F0F0D0 au lieu de #FFFFFF.
- Léger décalage de couleur entre les plans (faux repérage) sur les imprimés.
- Pas d'effets de filtre instagram moderne (vignette forte, saturation poussée, HDR).

## 8. Vocabulaire pour les prompts

Français et anglais, à réutiliser tels quels :
- « archive photo 1978, faded color print, warm orange-brown cast, film grain »
- « French vintage print advertisement, 1970s, bold grotesque headline, black and white »
- « brutalist concrete architecture, 1970s, low angle, overcast sky »
- « airbrush sci-fi illustration, 1980s magazine cover, outlined yellow title »
- « blue wireframe grid background, retro 3D, night navy, single red car »
- « Renault 5 / Citroën BX / TGV Atlantique 1980s, period-accurate »
- « no modern UI, no gradients, no neon, no glassmorphism »

## 9. Ce qu'il faut éviter

- Esthétique web moderne : boutons arrondis, cartes à ombre douce, dégradés violets ou bleus.
- Couleurs trop propres : blancs purs #FFFFFF, noirs purs avec contraste extrême, saturation forte.
- Typographies modernes et sans empattement neutres (Inter, Montserrat).
- Éléments récents : téléphones, interfaces, logos contemporains, vêtements actuels.
- Effet « vaporwave » ou « synthwave » rose-violet. Le corpus n'a presque pas de violet.
- Mise en scène de faux documents avec faux textes lisibles d'un vrai journal ou d'une vraie marque sans l'indiquer.

## 10. Procédure

1. Clarifie le format de sortie : visuel unique, carrousel, maquette, prompt d'image, layout.
2. Choisis la famille visuelle (section 3) et la dominante palette (section 4).
3. Ouvre quelques publications du compte @giscardpunk qui correspondent à la famille choisie et compare-les à ton brief.
4. Écris le brief (sujet, cadrage, palette, typo, grain, éléments à éviter) avant de générer ou de dessiner.
5. Produis le visuel. Pour une maquette, garde des calques natifs si l'outil le permet.
6. Vérifie avec la checklist ci-dessous et corrige avant de livrer.

## 11. Checklist de fidélité

- [ ] Une famille visuelle claire (A à E), dite à l'utilisateur.
- [ ] Teintes chaudes dominantes, blancs crème, noirs relevés.
- [ ] Au plus deux accents vifs et un fond neutre.
- [ ] Typographie d'époque, pas de police moderne.
- [ ] Grain ou trame visible, pas de rendu lisse.
- [ ] Aucun élément contemporain (interface, logo actuel, vêtement récent).
- [ ] Cadrage monumental ou mise en page de magazine.
- [ ] Comparé à au moins deux publications du compte @giscardpunk de la même famille.

## 12. Ressources et limites

- `references/palette-and-stats.md` : mesures complètes de palette et de tonalité.
- Pour voir le style, consulte le compte Instagram @giscardpunk (https://www.instagram.com/giscardpunk/). Les visuels appartiennent à leurs auteurs. Ils servent à étudier le style. Ne réutilise pas les scans originaux dans un livrable sans droits, et précise leur origine si tu les montres.
- Le compte présente un univers imaginaire (uchronie). Ne présente pas ses visuels comme des faits historiques.
