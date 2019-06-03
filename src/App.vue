<template>
  <div class="container">
    <div>
      <hr class="seperator">]
      <div class="page-header text-center">
        <h1>News Page Prototype</h1>
      </div>
    </div>
    <div class="centered-block">
      <hr class="seperator">
      <div>
        <div class="boardz centered-block">
          <!--The number of ul's equates to the number of columns  -->
          <ul> This will be the sidebar eventually</ul>
          <ul>
            <app-news-card></app-news-card>
            <app-news-card></app-news-card>
            <app-news-card></app-news-card>
            <app-news-card></app-news-card>
            <li>
              <h1>Constituam Adversarium</h1>*
              Cu simul oratio indoctum nam, cu offendit moderatius mel. Sea eu euismod consulatu, usu cu
              audiam perpetua, viris philosophia vis et. Cu sit tibique intellegam, error ludus scripta pri
              et. His congue aliquam iracundia ei. Has idque fastidii id, mucius erroribus vel ad. Ut posse
              albucius periculis his, duo an dicunt nostrud deleniti.
              Modo affert expetenda per ne. Et dolore platonem appellantur cum. Constituam adversarium in sit,
              mea ne porro vitae, eu pri modus dicam quaeque. At nibh brute sonet sea. Mei simul disputando
              eu, id vis esse explicari dissentiet, ei agam volutpat usu. Ex vis tollit mollis oportere, mei
              probatus qualisque te. Mei labore voluptaria ex, mei graeci feugiat definiebas eu.
            </li>

            <li>
              <h1>Fastidii Electram</h1>Vel adipisci suscipiantur te, nam ullum perfecto ut. Vitae contentiones id sed. Est vitae
              ponderum facilisis in. Quo illud eligendi similique et, odio detraxit pertinacia ea vix.
            </li>
          </ul>
          <ul>
            <li>
              <h1>Mea Ludico</h1>Cetero perpetua ius at, et feugait nostrum sit, mea ne quaeque fastidii electram. Delenit
              torquatos adipiscing vix ex. Viris tamquam postulant ei mel, ea singulis corrumpit democritum
              vim. No fierent salutatus vel, in persecuti vituperata eos, at nusquam perpetua hendrerit est.
              Ne pri odio option nusquam, sed natum admodum eleifend at. Sea putant malorum scripserit ut, ei
              duo prima eleifend, ea mea agam diceret inciderint.
            </li>

            <li>
              <h1>Impetus Accusata</h1>Vis omnium saperet ex. Wisi qualisque corrumpit eu vel, usu in vero inimicus mnesarchum. Eruditi
              vivendum usu at, elaboraret inciderint pri cu. Ius enim zril ad, zril timeam consulatu ex cum.
            </li>

            <li>
              <h1>Viderer Voluptua</h1>Vis omnium saperet ex. Wisi qualisque corrumpit eu vel, usu in vero inimicus mnesarchum. Eruditi
              vivendum usu at, elaboraret inciderint pri cu. Ius enim zril ad, zril timeam consulatu ex cum.
            </li>
          </ul>
          <ul>
            <li>
              <h1>Morbiso</h1>Morbi in sem quis dui placerat ornare. Pellentesque odio nisi, euismod in, pharetra a, ultricies
              in, diam. Sed arcu. Cras consequat.
            </li>

            <li>
              <h1>Sumo Summo</h1>Ex nostrud verterem mea, duo no delicata neglegentur. Audire integre rationibus ut pri, ex cibo
              oblique euismod sit, cibo iracundia vix at. Legimus torquatos definiebas an nec, mazim postulant
              at sit. Ne qui quando vocent accusata, nam tritani fierent no. Ea per vocent voluptatibus.
              Animal petentium patrioque id eos, et vis delenit reprimique. Vix clita essent expetenda et, duo
              in soleat graeci complectitur. Sit lorem vitae iudicabit in, malorum discere ne ius. Est eu
              adhuc blandit, ne copiosae placerat persequeris vim.
            </li>

            <li>
              <h1>Parabou Tras</h1>Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros
              eu erat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis
              luctus, metus.
            </li>

            <li>
              <h1>Vix Clita</h1>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum
              deleniti atque corrupti quos dolores et aut officiis debitis aut rerum necessitatibus saepe
              eveniet ut et voluptates repudiandae sint et molestiae non recusandae.
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NewsCard from "./components/NewsCard.vue";

export default {
  // data:function(){
  // },
  components: {
    appNewsCard: NewsCard
  }
};
</script>

<style>
</style>

