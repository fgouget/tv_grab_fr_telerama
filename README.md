# tv_grab_fr_telerama
XMLTV Grabber using telerama data

## Nouvelle API telerama
<b>Depuis la version 1.22</b>, une nouvelle api de telerama est utilisée. 

les numéro des chaînes n'étant pas les mêmes, il est nécessaire de refaire un
<pre>
tv_grab_fr_telerama --configure
</pre>
Si vous utilisez mythtv, il conviendra de modifier également ces ids dans la base de données (ou depuis myhtweb) pour mettre ceux au nouveau format (CXXX.api.telerama.fr). Les Ids sont visibles dans votre fichier de configuration généré plus haut.

Ce fichier de configuration doit également être placé dans votre répertoire xmltv à la place du précédent.
