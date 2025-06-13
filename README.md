# Analyse du rapport généré par les tests Selenium : 

Les tests sont lancés mais rencontre l'erreur :
OSError: [Errno 8] Exec format error: '.../THIRD_PARTY_NOTICES.chromedriver'

J'ai essayé : 
l'Installation et utilisation de webdriver-manager pour gérer automatiquement le chromedriver.

Les tests échouent tous au moment du setup du driver (webdriver.Chrome(...)) à cause d’un fichier THIRD_PARTY_NOTICES.chromedriver incorrectement identifié comme exécutable par webdriver-manager.
Le rapport HTML (report.html) est bien généré malgré tout.


