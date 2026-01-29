<template>
  <v-footer color="black" class="white--text pa-2 pb-0">
    <v-container>
      <v-row>
        <v-col cols="6" md="4">
          <h4 class="mb-4">
            <v-img
              width="200px"
              height="200px"
              src="@/assets/logo-img-w.png"
              alt="Logo"
              contain
            ></v-img>
          </h4>
        </v-col>

        <v-col cols="6" md="2">
          <v-list density="compact" bg-color="transparent">
            <v-list-item title="Produtos" />
            <v-list-item title="Lançamentos" />
            <v-list-item title="Ofertas" />
          </v-list>
        </v-col>

        <v-col cols="6" md="2">
          <v-list density="compact" bg-color="transparent">
            <v-list-item title="Contato" />
            <v-list-item title="Trocas" />
            <v-list-item title="Entrega" />
          </v-list>
        </v-col>

        <v-col cols="12" md="4">
          <h5 class="mb-3">Siga-nos</h5>
          <v-btn icon="mdi-instagram" variant="text" />
          <v-btn icon="mdi-facebook" variant="text" />
          <v-btn icon="mdi-twitter" variant="text" />
        </v-col>
      </v-row>

      <v-divider class="pt-6 pb-0" />

      <div class="text-center text-caption">
        © {{ new Date().getFullYear() }} Undefined Clothes — Todos os direitos
        reservados
      </div>
    </v-container>
  </v-footer>
</template>
