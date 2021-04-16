<template>
  <v-list subheader two-line flat class="mx-auto" width="560">
    <v-title style="font-size: 20px; font-weight: bold"
      >あなたが好きなアプリを２つ選んでください。</v-title
    >
    <v-subheader>editch予選会</v-subheader>

    <v-list-item-group v-model="settings" active-class="pink--text" multiple>
      <v-card elevation="0" outlined>
        <v-list-item>
          <template #default="{ active }">
            <v-list-item-action>
              <v-checkbox
                :input-value="active"
                color="pink accent-3"
              ></v-checkbox>
            </v-list-item-action>

            <v-list-item-content>
              <v-list-item-title>アプリ1</v-list-item-title>
              <v-list-item-subtitle>Aさん</v-list-item-subtitle>
            </v-list-item-content>
          </template>
        </v-list-item>
      </v-card>

      <v-card class="mt-4" elevation="0" outlined>
        <v-list-item>
          <template #default="{ active }">
            <v-list-item-action>
              <v-checkbox
                :input-value="active"
                color="pink accent-3"
              ></v-checkbox>
            </v-list-item-action>

            <v-list-item-content>
              <v-list-item-title>アプリ2</v-list-item-title>
              <v-list-item-subtitle>Bさん</v-list-item-subtitle>
            </v-list-item-content>
          </template>
        </v-list-item>
      </v-card>

      <v-card class="mt-4" elevation="0" outlined>
        <v-list-item>
          <template #default="{ active }">
            <v-list-item-action>
              <v-checkbox
                :input-value="active"
                color="pink accent-3"
              ></v-checkbox>
            </v-list-item-action>

            <v-list-item-content>
              <v-list-item-title>アプリ3</v-list-item-title>
              <v-list-item-subtitle>Cさん</v-list-item-subtitle>
            </v-list-item-content>
          </template>
        </v-list-item>
      </v-card>

      <v-card class="mt-4" elevation="0" outlined>
        <v-list-item>
          <template #default="{ active }">
            <v-list-item-action>
              <v-checkbox
                :input-value="active"
                color="pink accent-3"
              ></v-checkbox>
            </v-list-item-action>

            <v-list-item-content>
              <v-list-item-title>アプリ4</v-list-item-title>
              <v-list-item-subtitle>Dさん</v-list-item-subtitle>
            </v-list-item-content>
          </template>
        </v-list-item>
      </v-card>

      <v-card class="mt-4" elevation="0" outlined>
        <v-list-item>
          <template #default="{ active }">
            <v-list-item-action>
              <v-checkbox
                :input-value="active"
                color="pink accent-3"
              ></v-checkbox>
            </v-list-item-action>

            <v-list-item-content>
              <v-list-item-title>アプリ５</v-list-item-title>
              <v-list-item-subtitle>Eさん</v-list-item-subtitle>
            </v-list-item-content>
          </template>
        </v-list-item>
      </v-card>
    </v-list-item-group>
    <v-row>
      <!-- <v-col class="mt-8" style="text-align: center">
        <v-text-field
          v-model="message4"
          label="校長オプション"
          placeholder="誕生日を入力してください"
          color="pink accent-3"
          outlined
          clearable
        ></v-text-field>
      </v-col> -->
      <v-col class="mt-8" style="text-align: center">
        <v-btn depressed color="blue-grey lighten-5" x-large>
          <strong style="color: #f50057">投票する</strong>
        </v-btn>
      </v-col>
    </v-row>
  </v-list>
</template>

<script>
// import Logo from '~/components/Logo.vue'
// import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  // components: {
  //   Logo,
  //   VuetifyLogo,
  // },
}
</script>
