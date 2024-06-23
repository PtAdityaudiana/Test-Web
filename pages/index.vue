<template>
  <div class="container black-background">
    <div class="content">
      <h1 class="text-3xl font-bold underline">MIG-25: Foxbat</h1>
      <div class="image-container">
        <img src="@/assets/image.jpg" alt="MIG-25 Foxbat" class="image"/>
      </div>
      <p class="image-description">Pesawat MiG-25 Foxbat adalah pesawat tempur supersonik Soviet yang dikembangkan pada tahun 1960-an. Pesawat ini terkenal karena kecepatan dan ketinggiannya yang sangat tinggi, serta kemampuannya untuk melakukan misi pengintaian jarak jauh. MiG-25 dilengkapi dengan mesin kuat dan dapat mencapai kecepatan lebih dari Mach 3. Meskipun dirancang untuk kecepatan dan ketangguhan, Foxbat tidak begitu manuverabel dalam pertempuran udara langsung. Pesawat ini memiliki peran utama dalam angkatan udara Soviet dan digunakan oleh negara-negara lain di seluruh dunia.</p>
      <p class="image-description">by coem</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style scoped>
html, body {
  margin: 0;
  height: 100%;
}

.container {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  height: 100vh;
  background-color: black;
  flex-direction: column; /* Stack elements vertically */
}

.content {
  text-align: center;
  color: white;
  width: 100%;
}

h1 {
  color: white;
  font-size: 40px;
  font-family: 'Roboto', sans-serif;
  margin-bottom: 40px; /* Optional: Add margin at the bottom of h1 */
}

.image-container {
  margin-bottom: 10px; /* Optional: Adjust margin as needed */
}

.image {
  width: 400px;          /* Set the width of the image */
  height: 300px;         /* Set the height of the image */
  max-width: 100%;       /* Optional: Make sure the image is responsive */
  max-height: 500px;     /* Optional: Set a max height for the image */
}

.image-description {
  color: white;
  font-size: 16px;
  text-align: center;
  margin-top: 10px; /* Optional: Adjust margin as needed */
  margin-left: 250px;
  margin-right: 250px;
}
</style>
