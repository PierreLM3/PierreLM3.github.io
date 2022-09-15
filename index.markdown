---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<html>
  <head>
    <meta charset="utf-8">
    <script type="text/javascript" src="https://widget.itea.fr/js/itea_widget.js"></script
  </head>
  <body>
      
{% for item in site.data.menu.toc %}
    <h3>{{ item.title }}</h3>
      <ul>
        {% for entry in item.subfolderitems %}
          <li><a href="{{ entry.url }}">{{ entry.page }}</a></li>
        {% endfor %}
      </ul>
{% endfor %}
  
    <table style="text-align:center;margin-left: auto;margin-right: auto;" border="1" width="500">
  <colgroup>
    <col width="1000">
    <col width="100">
  </colgroup>
<tbody>

<tr>
   <th>Dates</th>
   <th>Tarifs</th>
</tr>
<tr>
  <td>semaine hiver hors vacances scolaires Noël & février</td>
  <td>1700&nbsp;€</td>
<tr>
  <td>semaine hiver vacances scolaires Noël & février</td>
  <td>3400&nbsp;€</td>
<tr>
  <td>été & hors saison</td>
  <td>950&nbsp;€</td>
</tr>
</tr>
</tbody>
</table>

<br/>
<p>VACANCES de NÖEL 2022 et NOUVEL AN 2023 : du fait des nombreuses possibilités, pour connaître le tarif, utilisez l'outil de réservation en bas de page ou contactez nous. </p>

<p>En hiver, les locations se font principalement à la semaine du dimanche au dimanche. En été et hors saison du samedi au samedi. Pour les week-ends, nous consulter. </p>

<p>Le tarif ci-dessus est le tarif toutes charges comprises, pour 7 nuits - voir les disponibilités ci-dessous. Pour des week-ends ou des courts séjours, nous consulter. Un kit bébé (lit, chaise haute, baignoire, ...) est mis à disposition gracieusement. </p>
<p>Sauf arrangement spécifique, les arrivées se font à partir de 16 heures et les départs au plus tard à 10 heures.</p>
<p>Le tarif ne comprend pas les prestations complémentaires proposées ci-dessous, ni la taxe de séjour (2,48 euros par personne de plus de 18 ans et par jour).</p>
<p>Les prestations complémentaires qui peuvent vous être proposées sont les suivantes :</p>
<p>- le fourniture de draps : kit lit 1 place - 10 euros, kit lit 2 places 12 euros - dans ce cas, les chambres sont préparées suivant vos besoins ;</p>
<p>- le fourniture de linge de toilette : 5 euros par personne ;</p>
<p>- le ménage de fin de séjour pour 140 euros.</p>
<p>Le contrat de location sera un contrat Gîtes de France.</p>
<p>Un acompte de 25 % du montant de la location sera réclamé lors de l'établissement du contrat. Une caution ou dépôt de garantie d'un montant de 700 euros devra être remise lors de l'entrée dans les lieux.</p>
<p>Les chèques vacances ANCV sont les bienvenus.</p>
<p style="text-align: center;">
  
<script type='text/javascript'>
  var parametresWidget = {
    key : 'tftr8_fc',
    numGite : '73G148140',
    widget : 'resa',
  };
  widgetIteaGL(parametresWidget);
</script>

