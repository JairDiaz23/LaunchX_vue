<script>
  import InfoPasteleria from "@/components/InfoPasteleria";
  import PastelCard from "@/components/PastelCard";
  export default {
    components: {InfoPasteleria, PastelCard}
  }
</script>

<template>
  <div class="about">
    <InfoPasteleria label="Dirección: " value="Teopanzolco"/>
    <InfoPasteleria label="Telefono: " value="7773393423"/>
    <InfoPasteleria label="Horario de atención: " value="9 am a 6 pm"/>
  </div>
  <div>
    <div class="row">
      <div class="col-md-4">
        <PastelCard
          description="Aqui va la descripcion"
          imgSrc="assets/tresillo.png"
        />
      </div>
    </div>
  </div>
</template>
