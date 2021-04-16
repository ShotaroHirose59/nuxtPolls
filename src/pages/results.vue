<template>
  <v-list class="mx-auto" width="800">
    <v-title style="font-size: 24px; font-weight: bold"
      >あなたが好きなアプリを２つ選んでください。(結果)</v-title
    >
    <v-subheader>editch予選会</v-subheader>

    <v-row>
      <v-col class="mt-8" cols="10" sm="10" md="10">
        <v-progress-linear
          :value="appA"
          rounded
          color="pink accent-3"
          height="32"
        >
          <v-col>
            <strong class="title ml-4" style="color: #fff">アプリA</strong>
          </v-col>
        </v-progress-linear>
      </v-col>
      <v-col class="mt-8" cols="2" sm="2" md="2">
        <span class="title mt-8">{{ appA }}票</span>
      </v-col>

      <v-col class="mt-4" cols="10" sm="10" md="10">
        <v-progress-linear
          :value="appA"
          rounded
          color="pink accent-3"
          height="32"
        >
          <v-col>
            <strong class="title ml-4" style="color: #fff">アプリA</strong>
          </v-col>
        </v-progress-linear>
      </v-col>
      <v-col class="mt-4" cols="2" sm="2" md="2">
        <span class="title mt-8">{{ appA }}票</span>
      </v-col>

      <v-col class="mt-4" cols="10" sm="10" md="10">
        <v-progress-linear
          :value="appA"
          rounded
          color="pink accent-3"
          height="32"
        >
          <v-col>
            <strong class="title ml-4" style="color: #fff">アプリA</strong>
          </v-col>
        </v-progress-linear>
      </v-col>
      <v-col class="mt-4" cols="2" sm="2" md="2">
        <span class="title mt-8">{{ appA }}票</span>
      </v-col>

      <v-col class="mt-4" cols="10" sm="10" md="10">
        <v-progress-linear
          :value="appA"
          rounded
          color="pink accent-3"
          height="32"
        >
          <v-col>
            <strong class="title ml-4" style="color: #fff">アプリA</strong>
          </v-col>
        </v-progress-linear>
      </v-col>
      <v-col class="mt-4" cols="2" sm="2" md="2">
        <span class="title mt-8">{{ appA }}票</span>
      </v-col>

      <v-col class="mt-4" cols="10" sm="10" md="10">
        <v-progress-linear
          :value="appA"
          rounded
          color="pink accent-3"
          height="32"
        >
          <v-col>
            <strong class="title ml-4" style="color: #fff">アプリA</strong>
          </v-col>
        </v-progress-linear>
      </v-col>
      <v-col class="mt-4" cols="2" sm="2" md="2">
        <span class="title mt-8">{{ appA }}票</span>
      </v-col>
    </v-row>
  </v-list>
</template>

<script>
export default {
  data() {
    return {
      appA: 50,
    }
  },
}
</script>
