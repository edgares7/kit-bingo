<template>
  <div class="home flex items-center justify-center h-screen w-screen">
    <div class="grid grid-cols-5 gap-3">
      <div class="text text-center text-lg font-black">B</div>
      <div class="text text-center text-lg font-black">I</div>
      <div class="text text-center text-lg font-black">N</div>
      <div class="text text-center text-lg font-black">G</div>
      <div class="text text-center text-lg font-black">O</div>
      <div class="card card-1 flex flex-col items-center justify-center">
        <img src="@/assets/images/club/europe/england/Arsenal_FC.svg" alt="" />
        <p>Arsenal</p>
      </div>
      <div class="card card-2 flex flex-col items-center justify-center">
        <img src="@/assets/images/club/europe/england/Chelsea_FC.svg" alt="" />
        <p>Chelsea</p>
      </div>
      <div class="card card-3 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/england/Liverpool_FC.svg"
          alt=""
        />
        <p>Liverpool</p>
      </div>
      <div class="card card-4 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/england/Manchester_City_FC_badge.svg"
          alt=""
        />
        <p>Manchester City</p>
      </div>
      <div class="card card-5 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/england/Manchester_United_FC_crest.svg"
          alt=""
        />
        <p>Manchester United</p>
      </div>
      <div class="card card-6 flex flex-col items-center justify-center">
        <img src="@/assets/images/club/europe/france/AS_Monaco_FC.svg" alt="" />
        <p>Monaco</p>
      </div>
      <div class="card card-7 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/france/Olympique_Marseille_logo.svg"
          alt=""
        />
        <p>Marseille</p>
      </div>
      <div class="card card-8 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/france/Paris_Saint-Germain_F.C..svg"
          alt=""
        />
        <p>PSG</p>
      </div>
      <div class="card card-9 flex flex-col items-center justify-center">
        <img src="@/assets/images/club/europe/france/SSC_Neapel.svg" alt="" />
        <p>Napoli</p>
      </div>
      <div class="card card-10 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/germany/Borussia_Dortmund_logo.svg"
          alt=""
        />
        <p>Borussia Dortmund</p>
      </div>
      <div class="card card-11 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/germany/FC_Bayern_München_logo_(2017).svg"
          alt=""
        />
        <p>Bayern Munich</p>
      </div>
      <div class="card card-12 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/germany/FC_Schalke_04_Logo.svg"
          alt=""
        />
        <p>Schalke 04</p>
      </div>
      <div
        class="
          free
          card card-13
          flex flex-col
          items-center
          justify-center
          bg-red-100
        "
      >
        <img
          src="@/assets/images/club/europe/italy/AS_Roma_logo_(2017).svg"
          alt=""
        />
        <p>Roma</p>
      </div>
      <div class="card card-14 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/italy/FC_Internazionale_Milano_2021.svg"
          alt=""
        />
        <p>Inter Milan</p>
      </div>
      <div class="card card-15 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/italy/Juventus_FC_2017_icon_(black).svg"
          alt=""
        />
        <p>Juventus</p>
      </div>
      <div class="card card-16 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/italy/Logo_of_AC_Milan.svg"
          alt=""
        />
        <p>AC Milan</p>
      </div>
      <div class="card card-17 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/netherlands/Ajax_Amsterdam.svg"
          alt=""
        />
        <P>AJAX</P>
      </div>
      <div class="card card-18 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/netherlands/Feyenoord_logo.svg"
          alt=""
        />
        <p>Feyenoord</p>
      </div>
      <div class="card card-19 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/netherlands/PSV_Eindhoven.svg"
          alt=""
        />
        <p>PSV</p>
      </div>
      <div class="card card-20 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/spain/Atletico_Madrid_2017_logo.svg"
          alt=""
        />
        <p>Atletico Madrid</p>
      </div>
      <div class="card card-21 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/spain/FC_Barcelona_(crest).svg"
          alt=""
        />
        <p>Barcelona</p>
      </div>
      <div class="card card-22 flex flex-col items-center justify-center">
        <img
          src="@/assets/images/club/europe/spain/Real_Madrid_CF.svg"
          alt=""
        />å
        <p>Real Madrid</p>
      </div>
      <div class="card card-23 flex flex-col items-center justify-center">
        <img src="@/assets/images/club/europe/spain/Valenciacf.svg" alt="" />
        <p>Valencia</p>
      </div>
      <div class="card card-24 flex flex-col items-center justify-center">
        <img src="@/assets/images/club/europe/scotland/Celtic_FC.svg" alt="" />
        <p>Celtic</p>
      </div>
      <div class="card card-25 flex flex-col items-center justify-center">
        <img src="@/assets/images/club/europe/scotland/Rangers_FC.svg" alt="" />
        <p>Rangers</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>
<style lang="scss" scoped>
.card {
  border: 1px solid black;
  @apply h-40;
  @apply w-40;
  img {
    max-height: 80%;
    height: auto;
  }
}
</style>
