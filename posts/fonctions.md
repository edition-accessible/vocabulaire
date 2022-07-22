---
title: Les fonctionnalitès d'accessibilité du livre numérique
description: 
date: 2022-06-01
tags:
- Définitions
layout: layouts/post.njk
---
 
<article id="accessModeTextual">
<h2>Lecture non visuelle : alternatives textuelles et texte vrai</h2>
<p>Cas d'usage : lorsque vous activez la fonction lecture audio de votre liseuse, la voix lira une description lorsqu’elle rencontre une image. Vous pourrez ainsi profiter de l’intégralité du livre sans perdre d’information.</p>
<details><summary>En savoir plus sur la lecture non visuelle</summary>
<ul>
<li>Définition : le contenu du livre numérique est intégralement consultable en texte, les autres médias nécessaires à la compréhension sont décrits ou disposent d’une alternative textuelle.</li>
	<li>Exemple :
	<div class="ckeditor-html5-video" style="text-align: center;">
	<video controls="controls" controlslist="nodownload" src="statics/thorium-descr-imgs.m4v" width="480px" aria-describedby="transcriptionThoriumVocal"></video>
	</div><span id="transcriptionThoriumVocal">Transcription : la voix de synthése lit le titre puis la description de l'image. Un surlignage jaune permet d'identifier que c'est l'image qui est lue.</span></li>
	<li>Précisions : la plupart des publications numériques disponiblesincluent leur contenu en texte numérique et peuvent indiquer qu’elles sont adaptées aux lecteurs d’écran. Les exceptions sont les publications dont une partie du contenu essentiel à la compréhension n’est inclus que dans des images, comme des graphiques, des tableaux ou des équations présentés sous forme d’images, et les publications dont l’apparence fixe est créée par une image de chaque page au lieu d’un texte véritable.</li>
</ul>
</details><hr/>

</article>
<article>
<h2 id="accessModeAuditory">Des livres entièrement audio</h2>
<p>Cas d'usage : lorsque vous achetez un livre audio vous voulez être sûr que toute l’information est présente sous forme audio, y compris le sommaire, le temps de lecture et d’autres informations qui peuvent être communiquées sur une image de couverture jointe aux fichiers audios.</p>
<details><summary>En savoir plus sur l'accessibilité du livre audio</summary>
<ul>
<li>Exemple : <img alt="Capture d'écran d'un dossier contenant des fichiers MP3 et un fichier couverture.mp3" src="statics/image3.png"></li>
<li>Définition : indication que cette publication peut être lue intégralement en mode audio. Cette désignation s’applique même si le texte est également disponible avec l’audio.</li>
<li>Précisions : les livres audio présentés sans texte sont considérés comme des publications optimisées. Ils ne répondent pas à toutes les exigences en matière d’accessibilité et ne seront donc pas identifiés lors du filtrage des publications “accessibles”, mais ils donnent accès à la publication à des utilisateurs spécifiques qui ont besoin de l’audio. Le fait de permettre aux utilisateurs d’être autonomes pour chercher dans une collection toutes les publications avec le son intégral aidera ces utilisateurs et le fait d’inclure cette information dans les métadonnées affichées alertera également les utilisateurs pour lesquels le son est inaccessible.</li>
</ul>
</details><hr/>

</article>
<article>
<h2 id="displayTransformability"> Modifier l'aspect : des ajustements visuels sont possibles</h2>
<p>Cas d'usage : lorsque vous lisez, vous souhaitez pouvoir modifier la taille des caractères ainsi que les espacements pour rendre la lectureconfortable en fonction de votre matériel ou des conditions.</p>
<details><summary>En savoir plus sur les possibilités de mofification de la mise en page</summary>
<ul>
<li>Exemple : <img alt="Dans l'interface de Thorium, l'aspect du livre est modifié : le fonc passe en en sépia puis en noir ; la police est grossie puis modifiée, les espacements des lignes sont agrandis." src="statics/thorium_adjust_txt.gif"></li>
<li>Définition : Lors de sa lecture, la mise en forme du fichier est adaptée aux besoins de l’utilisateur (taille adaptée à l’écran, police, taille de la police, espacements, etc.) en fonction des possibilités du logiciel de lecture.</li>	<li>Précisions : cela concerne les livres numériques au format EPUB (quand la mise en page n’est pas fixe), Kindle, Books ou HTML.</li>
</ul>
</details><hr/>

</article>
<article id="displayTransformabilityNo">
<h2>Conserver l'aspect</h2>
<p>Cas d'usage : vous souhaitez disposer d’une représentation exacte de la version papier pour l’imprimer ou parce que vous utilisez le livre numérique en complément d’une édition imprimée.</p>
<details><summary>En savoir plus sur la mise en page fixe</summary>
<ul>
<li>Exemple : <a href="https://ressources.sesamath.net/coll_docs/cah/valide/manuel_chapitre_2014_2SP1.pdf">Une page d'un manuel scolaire dont la mise en page structure fortement la lecture.</a><br/><img alt="" src="statics/image6.png" style="width: 319.71px; height: 502.60px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""></li>
<li>Définition : Lors de sa lecture, la mise en forme du fichier n’est pas modifiée quelle que soit la taille de l’écran. L’utilisateur ne peut pas modifier la police ou les espacements.</li>
<li>Précisions : les mises en page fixes sont par nature difficilement accessibles car elle sne peremttent pas d'ajuster le texte à sa vision ou à son écran. Il ets aussi particuliérement complexe d'assurer leur restitution correcte par une technologie d'assistance comme un lecteur d'écran qui assure la retsitution vocale ou braille. Par ailleurs la pagination de référence de l'original peut-être ajoutée dans un format EPUB ou HTML et rendue disponible via un menu spécifique.</li>
</ul>
</details><hr/>
<p><a href="#navigation">Revenir au menu</a></p>
</article>
<article id="disableByDrm">
 <h2>Pas de mesure de protection invalidante</h2>
 <p>Cas d'usage : l'orsque vous achetez un livre num&eacute;rique, certaines mesures de protection peuvent emp&ecirc;cher l&rsquo;extraction du texte et ainsi rendre le fichier illisible pour une synth&egrave;se vocale ou une technologie d&rsquo;assistance. La mesure de protection peut &eacute;galement &ecirc;tre incompatible avec votre mat&eacute;riel ou logiciel de lecture.
 </p>
 <details><summary>En savoir plus sur les difficultées liées aux verrous numériques</summary>
<ul>
<li>Exemple :<br/>
<img alt="" src="statics/image5.png" style="width: 381.00px; height: 137.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title="">
<img alt="" src="statics/image1.png" style="width: 584.00px; height: 240.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""></li>
<li>
<span>D&eacute;finition :</span>
<span>&nbsp;les verrous num&eacute;riques, aussi appel&eacute;s DRM (de l&rsquo;anglais Digital Rights Management) ou mesures de protections techniques, sont des mesures de protection pour &eacute;viter ou limiter certains usages non autoris&eacute;s comme l&rsquo;impression, la copie ou le partage des fichiers num&eacute;riques. Ces 
<a href="https://www.google.com/url?q=https://fr.wikipedia.org/wiki/Gestion_des_droits_num%25C3%25A9riques%23Les_livres_num%25C3%25A9riques&amp;sa=D&amp;source=editors&amp;ust=1654525991332926&amp;usg=AOvVaw3DjsY4lvyx0sSaR_xELZml">mesures de protection appliqu&eacute;s aux livres num&eacute;riques</a> &nbsp;peuvent rendre inop&eacute;rantes des fonctionnalit&eacute;s essentielles &agrave; l&rsquo;accessibilit&eacute;. </li>
<li>Pr&eacute;cisions : </li>
</ul></details><hr/>
<p><a href="#navigation">Revenir au menu</a></p>
 </article>
<article id="conformsTo">
<h2>Conformité aux standards</h2>
<p>Cas d'usage : un enseignant ou un prescripteur devant choisir des ouvrages à étudier en classe doit s’assurer que son choix conviendra à tous les élèves ou à toutes les personnes concernées. 
</p>
<details><summary>En savoir plus sur la conformité et les standards</summary>
<ul>
<li>Exemple : <a href="https://edition-accessible.github.io/signalement/protoype1/ace-smart-report-fr.html">un rapport de conformité d'accessibilité EPUB (nouvelle fenêtre)</a></li>
<li>Définition : les normes 
<a href="https://www.w3.org/Translations/WCAG20-fr/">Règles pour l'accessibilité des contenus Web (WCAG en anglais)</a>et <a href="https://www.edrlab.org/public/sne/TAE_HTML_V3/Techniques_d_Accessibilite_EPUB%201.0.htm">Accessibilité EPUB (<span lang="en">Epub Accessibility</span> en anglais) </a> offrent un consensus sur les pratiques à mettre en oeuvre pour assurer la meilleur accessibilité possible au plus grand nombre d'utilisateurs. Les créateurs de documents doivent les respecter ainsi que les fabricants de matériel de lecture ou de technologies d'assistance.</li>
<li>Précisions : ces normes sont techniques et peuvent-être difficiles à comprendre pour des utilisateurs. </li>
</ul>
</details><hr/>

</article>