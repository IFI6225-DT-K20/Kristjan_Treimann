<template>
    <v-row class="text-center">
      <v-col
        class="mb-5"
        cols="12"
      >
        <v-row justify="center">
          <a
            v-for="(link, i) in importantLinks"
            :key="i"
            :href="link.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ link.text }}
          </a>
        </v-row>
      </v-col>
    </v-row>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({

      importantLinks: [
        {
          text: 'IGAPÄEVAPANGANDUS',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'RAHA KASVATAMINE',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'LAEN JA LIISING',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'PENSION',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'VAJAD ABI?',
          href: 'https://medium.com/vuetify',
        },
      ]
    }),
  }
</script>
