# Application basket



## Description

Bla bla

[Voir le site](basket.francoisrousselet.fr "basket.francoisrousselet.fr")

## Fonctionnalités

Bla bla

### Prévues

Voici les fonctionnalités prévues qui n'ont pas encore été traités :

- Web
- Mobile

### En cours de développement

Celles-ci sont en cours de développement :

- Web
- Mobile

### Fonctionnelles

Celles-ci sont fonctionnelles et vous pouvez les utilisez dès maintenant :

- Web
- Mobile



## Problèmes

### Problème 1

    function height(bloc){
    	var hauteur;
    	var pad;
    	if( typeof( window.innerWidth ) == 'number' ) {
    		pad = (window.innerHeight-125);
    		hauteur = window.innerHeight-pad;
    	}
    	else if( document.documentElement && document.documentElement.clientHeight ) {
    		pad = (document.documentElement.clientHeight);
    		hauteur = document.documentElement.clientHeight;
    	}
    	document.getElementById(bloc).style.height = hauteur+"px";
    	document.getElementById(bloc).style.paddingTop = pad+"px";
    }
    window.onload =	function(){ height("pan1") };
    window.onresize = function(){ height("pan1") };

Description du problème...
