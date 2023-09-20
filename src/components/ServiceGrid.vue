<template>
  <div>
    <div class="card">
     <CardService 
      image="https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/"
      card-title="Augmentez vos ventes"
      card-subtitle="Développez votre chiffre d'affaires en décrochant plus de rendez-vous avec le PowerDialer, la numérotation en un clic (Click to Dial), et l'analyse en temps réel."
      card-button="Améliorez votre productivité"
      name="Sara Kinsella"
      logo="https://a.storyblok.com/f/157376/160x160/dca5dd2b34/summit-solar.png/m/48x0"
      title="Responsable des opérations de vente chez Summit Solar"
      subtitle="Nous avons augmenté nos quotas de 10 % grâce aux données que nous avons rassemblées avec les tags et les statistiques d’appel d’Aircall."
     />  
    </div>
    <div class="card">
    <CardService
      image="https://a.storyblok.com/f/157376/944x608/622eb0ffcc/frame-337-copie.jpg/m/"
      card-title="Améliorez votre Service Client"
      card-subtitle="Démarquez-vous de vos concurrents avec une expérience client unique comme le Serveur Vocal Interactif personnalisé, routage d'appels par compétence et les tableaux de bord en temps réel"
      card-button="Déployez un Service Client exemplaire"
      name="Audrey Gostoli"
      logo="https://a.storyblok.com/f/157376/x/d3eed6c095/tiime.svg"
      title="Co-fondatrice, Tiime"
      subtitle="Le passage à la téléphonie d’entreprise cloud avec Aircall nous permet d’effectuer un suivi des KPIs pour identifier nos points forts et points faibles."/>
    </div>
  </div>
  
</template>

<script>
import CardService from "./CardService.vue"
export default {
  name: "ServiceGrid",

  components:{
    CardService,
  }
};
</script>

<style scoped lang="scss"> 
div{
  display: flex;
  flex-direction: row;
  & > .card{
    width: 50%;
    padding: 30px;
  }
}
</style>
