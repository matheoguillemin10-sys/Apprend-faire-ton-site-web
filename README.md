# Apprend-faire-ton-site-web
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Les bases du Web - Guide simple</title>
  <style>
    body {
      font-family: "Verdana", sans-serif;
      background-color: #faf9f6;
      color: #333;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      background-color: #0078d7;
      color: white;
      text-align: center;
      padding: 1.5rem;
    }
    h1 {
      margin: 0;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      background: white;
      padding: 2rem;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #0078d7;
      border-bottom: 2px solid #0078d7;
      padding-bottom: 5px;
    }
    .mot-cle {
      background-color: #e6f0ff;
      border-left: 6px solid #0078d7;
      padding: 1rem;
      margin-bottom: 1.2rem;
      border-radius: 8px;
    }
    .mot-cle strong {
      display: block;
      font-size: 1.2em;
      margin-bottom: 0.4rem;
      color: #005bb5;
    }
    footer {
      text-align: center;
      font-size: 0.9em;
      padding: 1rem;
      color: #666;
    }
    @media (max-width: 600px) {
      main {
        padding: 1rem;
      }
    }
  </style>
</head>

<body>
  <header>
    <h1>🌐 Comprendre les bases du Web</h1>
    <p>Un guide simple pour apprendre les mots clés essentiels avant de créer un site</p>
  </header>

  <main>
    <h2>Les principaux termes à connaître</h2>
    <div class="mot-cle">
      <strong>HTML (HyperText Markup Language)</strong>
      Langage qui structure le contenu d’une page web (titres, paragraphes, images, liens…).
    </div>
    <div class="mot-cle">
      <strong>CSS (Cascading Style Sheets)</strong>
      Langage qui sert à styliser le contenu HTML (couleurs, polices, marges, disposition…).
    </div>
    <div class="mot-cle">
      <strong>JavaScript</strong>
      Langage de programmation qui rend les pages interactives (animations, boutons, formulaires dynamiques…).
    </div>
    <div class="mot-cle">
      <strong>Balises HTML</strong>
      Éléments de base comme &lt;div&gt;, &lt;p&gt;, &lt;img&gt;, &lt;a&gt;, &lt;ul&gt;, etc. Elles organisent le contenu.
    </div>
    <div class="mot-cle">
      <strong>Attributs HTML</strong>
      Informations supplémentaires dans une balise, comme <code>src</code>, <code>alt</code>, <code>href</code>, etc.
    </div>
    <div class="mot-cle">
      <strong>Classes</strong>
      Identifiants utilisés en CSS pour styliser plusieurs éléments HTML similaires. Préfixés par un point (<code>.</code>).
    </div>
    <div class="mot-cle">
      <strong>ID</strong>
      Identifiant unique pour un élément HTML, utilisé en CSS ou JavaScript. Préfixé par un dièse (<code>#</code>).
    </div>
    <div class="mot-cle">
      <strong>Responsive Design</strong>
      Technique permettant à un site de s’adapter à tous les types d’écrans (mobile, tablette, ordinateur).
    </div>
    <div class="mot-cle">
      <strong>Flexbox</strong>
      Méthode CSS pour organiser les éléments en ligne ou en colonne de manière flexible.
    </div>
    <div class="mot-cle">
      <strong>Grid</strong>
      Méthode CSS pour organiser les éléments en grille (lignes et colonnes).
    </div>
    <div class="mot-cle">
      <strong>index.html</strong>
      Fichier principal d’un site web, généralement la page d’accueil.
    </div>
    <div class="mot-cle">
      <strong>style.css</strong>
      Fichier contenant les règles de style CSS pour le site.
    </div>
    <div class="mot-cle">
      <strong>assets/</strong>
      Dossier utilisé pour stocker les ressources comme les images, icônes, polices, etc.
    </div>
    <div class="mot-cle">
      <strong>Navigateur</strong>
      Programme (Chrome, Firefox, Safari…) qui interprète le HTML/CSS/JS et affiche la page web.
    </div>
    <div class="mot-cle">
      <strong>Serveur</strong>
      Ordinateur distant qui héberge les fichiers du site web et les rend accessibles via Internet.
    </div>
    <div class="mot-cle">
      <strong>Hébergement</strong>
      Service permettant de mettre un site en ligne (ex : GitHub Pages, Netlify, OVH…).
    </div>
    <div class="mot-cle">
      <strong>Nom de domaine</strong>
      Adresse personnalisée d’un site web (ex : www.moncvquentin.fr).
    </div>
    <div class="mot-cle">
      <strong>Éditeur de code</strong>
      Logiciel pour écrire du code (ex : Visual Studio Code, Sublime Text).
    </div>
    <div class="mot-cle">
      <strong>Inspecteur (devtools)</strong>
      Outil intégré dans les navigateurs pour examiner et modifier le code d’une page en direct.
    </div>
    <div class="mot-cle">
      <strong>Validateur HTML/CSS</strong>
      Outil en ligne pour vérifier que le code HTML ou CSS est correct (ex : validator.w3.org).
    </div>
     <h2>1️⃣ Comprendre comment fonctionne le Web</h2>
    <div class="etape">
      <strong>Le Web, c’est quoi ?</strong>
      C’est un grand réseau d’ordinateurs connectés entre eux.  
      Quand quelqu’un visite ton site :
      <ul>
        <li>Son <strong>navigateur</strong> (ex : Chrome, Edge, Safari) envoie une demande à un autre ordinateur appelé <strong>serveur</strong>.</li>
        <li>Le serveur renvoie ta page de recette.</li>
        <li>Le navigateur l’affiche joliment à l’écran !</li>
      </ul>
    </div>
    <h2>2️⃣ Créer ta première page de recette</h2>
    <div class="etape">
      <strong>Étape 1 : Ouvrir un éditeur de code</strong>
      Utilise un logiciel comme <strong>Visual Studio Code</strong> ou le simple <strong>Bloc-notes</strong> de ton ordinateur.
    </div>
    <div class="etape">
      <strong>Étape 2 : Écrire ta recette en HTML</strong>
      Copie ce code dans ton éditeur :
      <pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang="fr"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;title&gt;Recette de confiture de fraises&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;h1&gt;Recette de confiture de fraises 🍓&lt;/h1&gt;
  &lt;ul&gt;
    &lt;li&gt;1 kg de fraises&lt;/li&gt;
    &lt;li&gt;800 g de sucre&lt;/li&gt;
    &lt;li&gt;1 jus de citron&lt;/li&gt;
  &lt;/ul&gt;
  &lt;ol&gt;
    &lt;li&gt;Laver les fraises&lt;/li&gt;
    &lt;li&gt;Faire cuire avec le sucre&lt;/li&gt;
    &lt;li&gt;Mettre en pot&lt;/li&gt;
  &lt;/ol&gt;
&lt;/body&gt;
&lt;/html&gt;</code></pre>
    </div>
    <div class="etape">
      <strong>Étape 3 : Enregistrer le fichier</strong>
      Enregistre ton document sous le nom <code>index.html</code>.  
      Ensuite, double-clique dessus : ta recette s’ouvrira dans ton navigateur ! 🎉
    </div>
    <h2>3️⃣ Mettre ton site en ligne</h2>
    <div class="etape">
      <strong>Étape 1 : Créer un compte GitHub</strong>
      Va sur <a href="https://github.com" target="_blank">github.com</a> et crée ton compte gratuitement.
    </div>
    <div class="etape">
      <strong>Étape 2 : Créer un nouveau dossier (“repository”)</strong>
      Clique sur <em>New repository</em> et nomme-le par exemple <code>mes-recettes</code>.
    </div>
    <div class="etape">
      <strong>Étape 3 : Ajouter ta page</strong>
      Clique sur <em>Add file → Upload files</em>, puis glisse ton fichier <code>index.html</code> dedans.  
      Clique sur <em>Commit changes</em>.
    </div>
    <div class="etape">
      <strong>Étape 4 : Activer GitHub Pages</strong>
      - Clique sur <em>Settings → Pages</em>  
      - Dans <em>Source</em>, choisis : <code>main</code> et <code>/(root)</code>  
      - Clique sur <strong>Save</strong>  
      Ton site sera bientôt disponible à une adresse comme :  
      <code>https://tonnom.github.io/mes-recettes/</code>
    </div>
    <div class="etape">
      <strong>Étape 5 : Partager ton lien</strong>
      Copie l’adresse du site et envoie-la à tes amis par e-mail, SMS ou WhatsApp 💌
    </div>
    <h2>4️⃣ Ajouter d’autres recettes</h2>
    <div class="etape">
      <strong>Créer une page par recette</strong>
      - <code>tarte-pommes.html</code>  
      - <code>gateau-chocolat.html</code>  
      - <code>soupe-legumes.html</code>  
      Puis, crée un <strong>menu</strong> sur ta page d’accueil avec des liens vers chacune.
    </div>
    <div class="etape">
      <strong>Exemple de lien</strong><br>
      &lt;a href="tarte-pommes.html"&gt;Voir la tarte aux pommes&lt;/a&gt;
    </div>
    <h2>5️⃣ Améliorer ton site</h2>
    <div class="etape">
      <strong>Quelques idées :</strong>
      <ul>
        <li>Ajouter un fichier <code>style.css</code> pour les couleurs et les polices.</li>
        <li>Utiliser des <strong>images</strong> de tes plats (dans un dossier <code>assets/</code>).</li>
        <li>Essayer un <strong>responsive design</strong> pour que ton site s’adapte aux téléphones.</li>
      </ul>
    </div>
    <div class="etape">
      <strong>Besoin d’aide ?</strong>
      Tu peux vérifier ton code avec le validateur HTML officiel :
      👉 <a href="https://validator.w3.org/" target="_blank">validator.w3.org</a>
    </div>
  </main>
  <footer>
    <p>© 2025 - Guide du Web par Roger | Créé pour apprendre les bases du développement web</p>
  </footer>
</body>
</html>
