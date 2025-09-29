# Veille : Web scraping (Projet 2 - OC)

## 🎯 Contexte
Projet OpenClassrooms : extraire des données d’un site e-commerce de livres, sauvegarder en CSV et télécharger les images.

## 📌 Ce que j’ai appris
- Manipuler BeautifulSoup pour naviguer dans le HTML.
- Gérer les erreurs et remplacer les champs manquants par "N/A".
- Organiser le code par phases et branches Git.

## ⚠️ Limites rencontrées
- Téléchargement d’images long sans parallélisation.
- Difficultés à gérer des erreurs HTTP sans retry.

## 🚀 Pistes d’amélioration
- Utiliser `concurrent.futures` pour paralléliser les téléchargements.
- Étendre à d’autres sites en adaptant les sélecteurs CSS.

## 🔗 Ressources
- [Documentation BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)  
- [Documentation Python csv](https://docs.python.org/3/library/csv.html)  
- [Vidéo Tuto (scraping) - Ninja Scripter](https://www.youtube.com/@ninjascripter5214/videos)
- [Q/A avec ChatGPT](chat.openai.com/chat)
- Discussions & exemples vus sur [Stack Overflow](https://stackoverflow.com/questions/tagged/web-scraping+python)  
