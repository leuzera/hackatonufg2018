<template>
  <v-layout align-center justify-space-around row fill-height>
      <v-card flat >
        <v-img src="/images/acessibilidade-icone.png" class="img--center" heigth="200px" width="200px"></v-img>
        <v-card-actions>
            <v-btn block to="?leitura" color="secondary" dark>Leitura Acessível</v-btn>
        </v-card-actions>
      </v-card>
      <v-card flat >
        <v-img src="/images/contract.png" class="img--center" heigth="200px" width="200px"></v-img>
        <v-card-actions>
            <v-btn block to="/documentos" color="secondary" dark>Modelos de Documentos Acessíveis</v-btn>
        </v-card-actions>
      </v-card>
      <v-card flat width="300px;">
          <v-img src="/images/livro.png" class="img--center" heigth="200px" width="200px"></v-img>
        <v-card-actions>
            <v-btn block to="/posts" color="secondary" dark>Guia de Acessibilidade Digital</v-btn>
        </v-card-actions>
      </v-card>
  </v-layout>
</template>

<script>
export default {}
</script>

<style>

.img--center {
  background-color: rgba(0, 0, 0, 0);
  margin-left:auto;
  margin-right:auto;
}

</style>
