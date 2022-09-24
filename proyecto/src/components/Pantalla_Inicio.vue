<template>
    <v-row justify="center">
      <v-dialog
        v-model="dialog"
        persistent
        max-width="45%"
      >
        <v-card>
          <v-toolbar>
            <div class="text-h4 pa-4"></div>
          </v-toolbar>
          <v-card-text>
            <div>
            <p style="text-align:center">Bienvenido</p>
            </div>
            <div>
                <v-btn color="green darken-1" text @click="dialog = false">Entrar
            </v-btn>
            </div>
          </v-card-text>
          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn
              color="green darken-1"
              text
              @click="dialog = false"
            >
              Close
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-dialog>
    </v-row>
  </template>
<script>
    export default {
        name:"Pantalla_Inicio",
      data () {
        return {
          dialog: true,
        }
      },
    }
  </script>
