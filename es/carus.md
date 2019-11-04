---
$title: Crear la portada
---
<table class="noborder">
<tr>
    <td colspan="2"><h5 id="fill">Plantilla: fill</h5></td>
</tr>
<tr>
    <td width="65%">La plantilla <strong>fill</strong> rellena la pantalla con el primer elemento secundario de la capa. El resto de elementos secundarios de esta capa no se muestran.

    <p>La plantilla "fill" se utiliza para fondos de pantalla que incluyen imágenes y vídeos.</p>
   <code class="nopad"><pre>&lt;amp-story-grid-layer template="fill">
  &lt;amp-img src="dog.png"
      width="720" height="1280"
      layout="responsive">
  &lt;/amp-img>
&lt;/amp-story-grid-layer></pre></code>
    </td>
    <td>
    {{ image('/static/img/docs/tutorials/amp_story/layer-fill.png', 216, 341) }}
    </td>
</tr>
</table>