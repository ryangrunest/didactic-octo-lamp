<template>
  <v-row justify="center" align="center">
		<v-col :cols="12" :sm="8">
			<v-card
				elevation="8"
				outlined
				shaped
			>
				<v-card-title>Hi Noodle :)</v-card-title>
				
			</v-card>
		</v-col>
  </v-row>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
