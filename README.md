# formation_shinepress
Ce repertoire est le lieu de stokage des prises de notes ainsi que des cours suivis a la formation SHINEPRESS

# commade de creation des repertoires et sous repertoire en une commande
```bash
mkdir [parametre] nom_du_repertoire
```

```gitbash
mkdir -p ecom/{env,templates,static/{css,img,js},src/{models,urls,views}} # pour 
```
####    creer un dossier parent 'ecom' avec des sous repertoir env, templates ;; 
#####   static et ses sous repertoires img, css etjs;; src et ses sous repertoires
#####    models, urls puis views



### utilisation du css pour faire une animation pour remplacer la balise <marquee> html qui est obsolette
```css
    p {
        animation: marquee 10s linear infinite alternate;
    }
    @keyframes marquee {
        0% { transform: translateX(-100%); }
        100% { transform: translateX(100%); }
    }
```

```html
    <p>this text is animate</p>
```


