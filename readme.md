![Speed Css](public/assets/images/speed_css.png)

# Pourquoi utiliser speed css ?
Pour coder rapidement tout en personalisant son contenu.

Coder en évitant de toucher au css le plus possible.

----------------------------------------------------------------------
# !!!Nous ne travaillons qu'avec des classes!!!
Dans chaque projet, tout est paramétré pour avoir la structure suivante dans chaque page html:

body

    header //Qui va contenir les menus

    content // Qui va contenir tous les éléments de notre site

    footer // Qui va contenir les mentions, les réseaux sociaux etc..

Pour connecter "Speed Css" à son projet: 

On inclut dans le head config.css:
```
<link rel="stylesheet" href="public/assets/css/config.css">
```

Si vous voulez rajouter du css personnel, vous pourrez rajouter un main.css ou style.css

----------------------------------------------------------------------
# Comment espacer ou positionner des éléments?

space_1 : Permet d'espacer des éléments autour.

space_2 : Permet d'espacer des éléments dont deux collés aux extrémités.

col     : Permet de mettre des éléments en colone

center  : Permet de centrer un élément

align_start : Permet de faire un alignement au début de notre div

align_center: Permet d'aligner au centre de notre div

align_end: Permet d'aligner a la fin de notre div

float_r : Permet de déplacer un élément tout à droite

float_l : Permet de déplacer un élément tout à gauche (valeur par défaut)

f_wrap : Permet de placer à la ligne les éléments si pas assez d'espace

gap + valeur : Permet d'espacer tous les éléments à l'intérieur de la div en question (exemple: gap50)

display_none : Permet de faire disparaitre un élément 

----------------------------------------------------------------------
# Comment mettre de la couleur en arrière plan ?

back_red    : Permet de mettre l'arrière plan en rouge.

back_blue   : Permet de mettre l'arrière plan en bleu.

back_green  : Permet de mettre l'arrière plan en vert.

back_yellow : Permet de mettre l'arrière plan en jaune.

back_orange : Permet de mettre l'arrière plan en orange.

back_black  : Permet de mettre l'arrière plan en noir.

back_grey   : Permet de mettre l'arrière plan en gris.

back_purple : Permet de mettre l'arrière plan en violet.

back_pink   : Permet de mettre l'arrière plan en rose.

back_brown  : Permet de mettre l'arrière plan en marron.

back_white  : Permet de mettre l'arrière plan en blanc.

----------------------------------------------------------------------
# Comment mettre de la couleur dans son texte ?

txt_red    : Permet de mettre le texte en rouge.

txt_blue   : Permet de mettre le texte en bleu.

txt_green  : Permet de mettre le texte en vert.

txt_yellow : Permet de mettre le texte en jaune.

txt_orange : Permet de mettre le texte en orange.

txt_black  : Permet de mettre le texte en noir.

txt_grey   : Permet de mettre le texte en gris.

txt_purple : Permet de mettre le texte en violet.

txt_pink   : Permet de mettre le texte en rose.

txt_brown  : Permet de mettre le texte en marron.

txt_white  : Permet de mettre le texte en blanc.

----------------------------------------------------------------------
# Comment mettre de la couleur dans son texte ?

txt_center  : Permet de centrer un texte.

txt_size5   : Permet de modifier la taille d'un texte. (txt_size + valeur) 5,10,15,20,25,30

----------------------------------------------------------------------
## Comment changer la hauteur ou la largeur d'un élément?

w | h | vh  + valeur

exemple: w100 = width: 100%;

exemple: h100 = height: 100%;

Il n'existe que 100vh pour le moment en valeur

exemple: vh100 = height: 100vh;

----------------------------------------------------------------------
## Comment mettre de la marge sur mes éléments sur la partie extérieure ?

mrg + valeur + option

Liste des options:

_l = left

_r = right

_t = top

_b = bottom

Exemple: mrg100_l = margin-left: 100%;

Dans le cas où on veux mettre 0.50 on écrit = mrg050 + option

----------------------------------------------------------------------
## Comment mettre de la marge sur mes éléments sur la partie intérieure ?

pad + valeur + option

Liste des options:

_l = left

_r = right

_t = top

_b = bottom

Exemple: pad100_l = padding-left: 100%;

Si dans le cas ou on veux mettre 0.50 on écrit = pad050 + option

----------------------------------------------------------------------
# Comment arrondir les bords ou tout le bouton ?

btn_1 = border-radius: 10px; | Arrondit les bords du bouton

btn_2 = border-radius: 50%;  | Fait une boule 
