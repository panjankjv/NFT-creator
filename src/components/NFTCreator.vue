<template>
  <v-container
    fluid
    style="max-width:500px;"
    class="mb-12"
  >
    <v-img
      src="/logos/nft_creator/nft_creator_white.svg"
      height="55"
      contain
      class="mb-3"
    />
    <p class="text-center">
      An easy and quick way to create NFTs on Solana blockchain.<br>
      See
      <router-link
        to="/about"
        class="text-decoration-none"
      >
        how it works
      </router-link>
    </p>
    <v-divider
      class="my-6"
    />

    <app-wallet-btn />

    <v-divider
      class="my-6"
    />

    <n-f-t-creator-form />
  </v-container>
</template>

<script>
import AppWalletBtn from './AppWalletBtn.vue';
import NFTCreatorForm from './NFTCreatorForm.vue';

export default {
  components: { AppWalletBtn, NFTCreatorForm },
};
</script>

<style>

</style>
