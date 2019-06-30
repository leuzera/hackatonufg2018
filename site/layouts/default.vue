<template>
  <v-app>
    <v-toolbar dark extended height="156px" extension-height="64px">
      <img src="/logo.png" height="100%" width="auto"/>
      <template v-slot:extension>
        <v-toolbar-items>
          <v-btn flat to="/">Inicio</v-btn>
          <v-btn flat to="/leitura">Leitura Acessível</v-btn>
          <v-btn flat to="/documentos">Modelos de Documentos Acessíveis</v-btn>
          <v-btn flat to="/posts">Guia de Acessibilidade Digital</v-btn>
          <v-btn flat to="/sobre">Sobre</v-btn>
        </v-toolbar-items>
      </template>
    </v-toolbar>
    <v-content>
      <v-container fluid>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer class="pa-3">
      <v-spacer></v-spacer>
    </v-footer>
  </v-app>
</template>

<script>
export default {}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

</style>
