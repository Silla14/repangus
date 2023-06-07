Titre : Argus Surveillance DVR 4.0 - Weak Password Encryption

Version: Argus Surveillance DVR 4.0

Description : Cette vulnérabilité sert à crypter des mots de passe faible dans Angus Surveillance DVR 4.0.

Utilisation : Après l'installation de l'application, nous devons créer un nouvel utilisateur appelé "test" ensuite changer son not de passe en "test". La configuration est enregistrée dans C:\ProgramData\PY_Software\Argus Surveillance DVR\DVRParams.ini
On peut y voir le mot de passe hacher de "test" qui est "E03BB7409083E03B". Avec un code python, l'automatisation du hachage a été mis en place. 

CVE utilisé: CVE-2022-25012

Licence : Indiquez la licence sous laquelle le projet est distribué. Précisez les droits et les restrictions pour les utilisateurs ou les contributeurs potentiels.

Auteur de l'exploit : Salman Asad (@deathflash1411) a.k.a LeoBreaker 