# Guide HeyGen — Créer ton avatar IA pour le pitch
**Durée estimée : 30 à 45 minutes**

---

## Pourquoi HeyGen ?

HeyGen est l'outil le plus simple et le plus propre pour créer un avatar vidéo réaliste depuis son propre visage et sa voix. Le résultat est professionnel, le lip-sync est excellent, et on peut générer la vidéo en quelques minutes une fois l'avatar créé.

---

## ÉTAPE 1 — Créer ton compte HeyGen

1. Va sur **heygen.com**
2. Clique sur "Get Started Free"
3. Connecte-toi avec ton email pro (david.kohler@groupe-simago.com)

> ⚠️ Le plan gratuit permet de créer une vidéo test. Pour la vidéo finale (2 min 30), il faudra probablement un abonnement Creator (~$29/mois) — ou créer ton avatar une fois et générer la vidéo immédiatement.

---

## ÉTAPE 2 — Enregistrer ta vidéo de consentement (5 min)

Pour cloner ton avatar, HeyGen demande une courte vidéo de toi. Voici les conditions idéales :

**Ce dont tu as besoin :**
- Un endroit calme, fond uni (mur blanc/gris ou fond sobre)
- Bonne lumière frontale (fenêtre ou lampe devant toi)
- Ta webcam ou ton téléphone en mode portrait ou paysage

**Ce que tu enregistres :**
- 2 à 5 minutes de toi qui parles naturellement face caméra
- Lis n'importe quoi à voix haute — article, texte quelconque
- Parle à ton rythme normal, avec tes expressions naturelles
- Regarde la caméra (pas l'écran)

**À éviter :**
- Fond chargé ou en mouvement
- Lumière derrière toi (contre-jour)
- Bouger la tête de façon excessive
- Bruits de fond

---

## ÉTAPE 3 — Créer ton avatar dans HeyGen

1. Dans le menu, clique sur **"Avatars"** → **"Create Avatar"**
2. Sélectionne **"Instant Avatar"** (le plus rapide)
3. Upload ta vidéo
4. HeyGen génère ton avatar en 5-10 minutes
5. Valide en regardant l'aperçu

---

## ÉTAPE 4 — Créer la vidéo avec le script

1. Clique sur **"Create Video"**
2. Sélectionne ton avatar
3. Dans la zone de texte, **colle le script** (fichier `pitch-shark-tank-script.md`)
4. Choisis la voix : **ta voix clonée** (générée automatiquement depuis ta vidéo)
5. Configure le fond :
   - Recommandé : fond uni **#006C5F** (vert Simago foncé)
   - Ou fond neutre sombre
6. Lance la génération

---

## ÉTAPE 5 — Récupérer et intégrer la vidéo

Une fois la vidéo générée :
1. **Télécharge le fichier MP4** (pour l'avoir en local)
2. **Publie sur YouTube** (non répertorié) ou **Loom** pour avoir un lien partageable
3. Dans le fichier `pitch-landing-page.html`, trouve le commentaire :
   ```
   <!-- 🎬 INSTRUCTION : Remplace cet id par ton lien HeyGen/YouTube/Loom -->
   ```
4. Remplace par le code d'intégration de ta vidéo :

**YouTube :**
```html
<iframe src="https://www.youtube.com/embed/TON_ID_VIDEO" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>
```

**Loom :**
```html
<iframe src="https://www.loom.com/embed/TON_ID_LOOM" 
        frameborder="0" 
        allowfullscreen>
</iframe>
```

---

## ÉTAPE 6 — Héberger la landing page

La landing page est un fichier HTML autonome. Pour la partager avec le jury :

**Option A — La plus simple : partage direct du fichier**
- Envoie le fichier `pitch-landing-page.html` en pièce jointe
- Le jury l'ouvre dans son navigateur, tout s'affiche en local

**Option B — Hébergement en ligne (recommandé)**
- Va sur **netlify.com/drop** (gratuit, sans inscription)
- Glisse-dépose le fichier `pitch-landing-page.html`
- Tu obtiens un lien public en 30 secondes
- Exemple : `https://simago-ia-league.netlify.app`

---

## Mail d'envoi au jury — Template

```
Objet : Simago IA League — Candidature Shark Tank IA League

Bonjour [Prénom],

Vous trouverez ci-dessous ma candidature pour le Shark Tank IA League.

Plutôt qu'une présentation classique, j'ai préféré vous montrer le projet tel qu'il est : 
piloté par l'IA, de bout en bout.

→ [Accéder à la présentation](LIEN_LANDING_PAGE)

La vidéo dure 2 minutes 30. Les détails du projet sont disponibles sur la page.

À votre disposition pour toute question,
David Kohler
Groupe Simago
david.kohler@groupe-simago.com
```

---

## Alternatives à HeyGen si besoin

| Outil | Forces | Lien |
|-------|--------|------|
| **Synthesia** | Très pro, plein d'avatars | synthesia.io |
| **D-ID** | Gratuit pour tester | d-id.com |
| **Runway** | Plus créatif, moins avatar | runwayml.com |
| **Loom** | Si tu préfères enregistrer toi-même | loom.com |

---

*Guide v1.0 — Mai 2026*
