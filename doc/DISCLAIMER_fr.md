## Démo

* [Démo officielle](https://kresus.org/fr/demo.html) Ne créez pas une connexion à vos comptes bancaires, ou bien tout le monde pourra voir vos données bancaires privées !

Les architectures 32 bits ne sont pas prises en charge car nodejs ne fournit plus d'archives pour systèmes 32 bits.does not provide builds for 32 bits anymore.

## Limitations

* Par défault, tous les utilisateurs ont accès aux comptes. L'administrateur doit manuellement sélectionner l'utilisateur autorisé via l'écran d'administration YunoHost.

## Feuille de route

* Fonctionne correctement :

  * [x] installation/suppression/sauvegarde/mise à jour avec x86_64

* À confirmer
  * [x] Prise en charge ARM

* À venir :
  * [ ] l'URL ne peut pas être modifiée
  * [ ] Prise en charge des emails
  * [ ] Amélioraton des logs et de leur rotation
  * [ ] Ajouter un utilisateur qui seul aura accès à l'application (par défaut tout le monde a accès à l'application)
