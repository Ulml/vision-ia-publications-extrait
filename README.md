# Publications et Ressources IA — Vision IA

**Vidéo :** Les géants de l’IA viennent de perdre leur avance (jamais vu ça)  
**Chaîne :** Vision IA  
**Date :** 28 octobre 2026  
**Lien :** https://www.youtube.com/watch?v=gvh9JpAC7GI

## Résumé

Cette vidéo présente une semaine où des modèles spécialisés, légers et souvent open-source surpassent ou rivalisent avec les géants généralistes de l’IA. Elle met en avant des modèles exécutables localement, à coût réduit, dans des domaines spécifiques : biologie/ADN, édition d’images, voix, conception mécanique, vision par ordinateur et génération 3D.

## Modèles et publications mentionnés

### 1. Carbon-X (Hugging Face Bio)
Modèle de langage de 14,8 milliards de paramètres pour l’analyse et la génération d’ADN. Entraîné conjointement sur séquences ADN et texte naturel. Performance proche de GPT-6.1 Sol sur des benchmarks ADN (66,7 % vs 67,5 %), à un coût ~1000x inférieur. Exécutable localement sur une seule GPU 80 Go. Licence Apache 2.0.

- **Modèle :** https://huggingface.co/HuggingFaceBio/Carbon-X

### 2. Fibo 2.0 (Bria AI)
Modèle d’édition et de génération d’images open-weights de ~8 milliards de paramètres (flow-matching). Unifie génération text-to-image et édition par instructions. #1 en édition d’images parmi les modèles open-weights (Artificial Analysis, oct. 2026). Checkpoints Dev et Edit Turbo. Licence non-commerciale (CC BY-NC) pour les poids ; API commerciale disponible.

- **Dev :** https://huggingface.co/briaai/Fibo-2.0-dev
- **Edit Turbo :** https://huggingface.co/briaai/Fibo-2.0-edit-turbo
- **Docs :** https://huggingface.co/docs/diffusers/api/pipelines/bria_fibo2

### 3. Dessa (Block)
Modèle vocal speech-to-speech full-duplex, entraîné uniquement sur des conversations audio humaines (sans texte, sans modèle pré-entraîné). Capable d’interruptions, de rires, de détection de sarcasme. S’exécute localement sur MacBook Pro M4 Max. Preview de recherche (accès anticipé pour chercheurs en sécurité). Pas de poids publics pour le moment.

- **Page officielle :** https://block.xyz/dessa

### 4. SKY-001 (Skyfall AI)
Modèle de monde d’ingénierie (Engineering World Model) pour la conception mécanique et BIM. Décompose automatiquement des objets 3D complexes en hiérarchie de sous-ensembles et planifie les étapes de construction CAD. Beaucoup plus rapide et moins cher que les LLMs frontières sur des benchmarks CAD/BIM (self-reported). Preview de recherche avec liste d’attente.

- **Page produit :** https://skyfall.ai/sky-001
- **Blog :** https://skyfall.ai/blog/introducing-sky-001

### 5. GPT-Rosalind + ~2000 agents (OpenAI / PerturbAI / Scripps)
Système distribué de ~1946 agents IA (GPT-Rosalind) qui a analysé un atlas cérébral CRISPR de ~8 millions de cellules de souris en 32 minutes. A récupéré des conclusions de l’étude originale, généré des hypothèses (ex. lien cholestérol / neurodégénérescence) et cité des centaines de références. Preprint bioRxiv du 16 octobre 2026.

- **Preprint bioRxiv :** https://www.biorxiv.org/content/10.64898/2026.10.15.759436v1
- **DOI :** https://doi.org/10.64898/2026.10.15.759436
- **Annonce OpenAI :** https://openai.com/index/scaling-ai-research-for-complex-biological-data/

### 6. WeVisOne-VL (Tencent WeChat Vision)
Modèle de vision par ordinateur (VLM) de 2B et 4B paramètres. Unifie détection d’objets, localisation, comptage, OCR, segmentation et matting alpha via un token `<OBJ>` et un décodeur pixel léger (9,6 M). Leader sur 30+ benchmarks. Licence Apache 2.0. Publié le 22 octobre 2026.

- **4B :** https://huggingface.co/tencent/WeVisOne-VL-4B
- **2B :** https://huggingface.co/tencent/WeVisOne-VL-2B
- **Paper arXiv :** https://arxiv.org/abs/2610.31329
- **GitHub :** https://github.com/Tencent/WeVisOne-VL
- **Project page :** https://tencent.github.io/WeVisOne-VL/

### 7. Hi3D v1.0 (Hi3D / Math Magic, basé sur Sparc3D)
Modèle open-source de raffinement de géométrie 3D haute résolution. Prend un maillage grossier + image de référence et produit une géométrie détaillée jusqu’à une grille d’extraction sparse de 1536³. Entraîné sur ~2 millions d’assets 3D. Validé en production. Code et poids disponibles.

- **GitHub :** https://github.com/hi3d-official/Hi3Dv1.0
- **Hugging Face :** https://huggingface.co/hi3d-official/Hi3Dv1.0
- **Site :** https://www.hi3d.ai/hi3d-1-0-open-source

## Conclusion

La vidéo conclut que l’ère des modèles géants généralistes s’achève au profit d’une constellation de modèles spécialisés, légers, souvent open-source et exécutables localement. Ces modèles sont présentés comme accessibles et monétisables.

---
*Document généré le 28 octobre 2026 à partir de l’analyse de la vidéo et des sources publiques associées.*
