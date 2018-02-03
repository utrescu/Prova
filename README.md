# prova

## Instal·lació dels requeriments

Per poder-lo usar cal tenir Node i instal·lar Nativescript (si no el teniu)

    npm install -g nativescript
 
Es pot comprovar que ho teniu tot a punt amb:

    tns doctor
L'error més habitual és no tenir definit el directori on teniu el SDK d'Android. 
En Linux (Bash) es defineix a .profile (amb el directori correcte):

    export ANDROID_HOME=/home/usuari/Android/SDK

## Executar el programa

Es clona el projecte: 
 
    git clone https://github.com/utrescu/prova.git
    cd prova
 
 Per executar-lo en Android
 
     tns run android

En IOS es semblant (però cal estar en un Mac i tenir XCode)

    tns run ios

