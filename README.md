# TimeTravel Agency - Webapp Interactive 🕰️

Projet réalisé dans le cadre du module **IA Créatives (M1/M2)**. Cette application web interactive permet d'explorer des destinations temporelles à travers une expérience immersive et personnalisée.

## 🚀 Lien vers la Webapp Déployée
https://fr304.github.io/timetravel-agency/

---

## 🛠️ Stack Technique
* **Développement :** HTML5, CSS3, JavaScript natif.
* **Design :** Thème "Premium Dark Mode" avec accents dorés, typographies élégantes (Playfair Display, Space Mono) et animations au scroll.
* **Déploiement :** GitHub Pages.

## 🤖 Fonctionnalités IA
* **Agent Conversationnel (Chronos) :** Chatbot utilisant l'IA **Mistral Small** (via OpenRouter) pour conseiller les voyageurs.
* **Système de Fiabilité (Fallback) :** Pour pallier les instabilités des APIs gratuites, un système de réponses de secours ("Smart Fallback") a été intégré. Il garantit une réponse cohérente et historique même en cas de latence serveur.
* **Personnalisation :** Quiz interactif de 4 questions recommandant la destination idéale selon le profil de l'utilisateur.
* **Cohérence IA :** Réponses programmées pour respecter le contexte historique (Paris 1889, Crétacé, Florence 1504).

## 📊 Gestion & Optimisation
* **Consommation de Tokens :** Surveillance active via le dashboard OpenRouter. Optimisation des appels API pour limiter l'usage (environ 8K tokens consommés durant la phase de test et déploiement).
* **Performance :** Approche "Mobile-first" pour garantir une navigation fluide sur tous les supports.

## 🎨 Assets & Créativité
* **Visuels :** Intégration des images et assets générés lors de la Session 1 via Midjourney et Runway.
* **UX/UI :** Curseur personnalisé interactif, transitions fluides et effets de parallaxe.

## 📝 Transparence & Crédits
Conformément aux principes d'Open Source et de transparence :
* **Code :** Structure initiale générée via **Bolt.new** (Claude 3.5 Sonnet) et affinée manuellement pour l'intégration de la logique de secours du chatbot.
* **Modèle IA :** Mistral AI via l'agrégateur OpenRouter.
* **Prompts :** Définition précise de la personnalité de Chronos : "Expert historique, ton luxueux, chaleureux et professionnel".
* **Assets :** Images créées par notre groupe durant la Session 1.

---
*Projet Pédagogique - M1/M2 Digital & IA*
