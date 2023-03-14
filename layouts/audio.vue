<script setup lang="ts">
defineProps<{ video: string }>();
</script>

<template>
  <div class="slidev-layout video">
    <div class="my-auto mx-auto w-full">
      <div class="w-full h-[440px]">
        <slot />
        <br />
        <audio controls src="/assets/And When He Falleth.mp3">
          <a href="/media/cc0-audio/t-rex-roar.mp3"> Download audio </a>
        </audio>
        <br />
        <div v-click class="text-[14px] leading-[1.5rem]">
          [Male Voice] That cross you wear around your neck; is it only a
          decoration, or are you a true Christian believer?
          <br />
          [Female Voice] Yes, I believe - truly
          <br />
          [Male Voice] Then I want you to remove it at once! - and never to wear
          it within this castle again! Do you know how a falcon is trained my
          dear? Her eyes are sown shut. Blinded temporarily she suffers the
          whims of her God patiently, until her will is submerged and she learns
          to serve - as your God taught and blinded you with crosses.
          <br />
          [Female Voice] You had me take off my cross because it offended....
          <br />
          [Male Voice] It offended no-one. No - it simply appears to me to be
          discourteous to... to wear the symbol of a deity long dead.
          <br />
          [Male Voice] My ancestors tried to find it. And to open the door that
          seperates us from our Creator.
          <br />
          [Female Voice] But you need no doors to find God. If you believe....
          <br />
          [Male Voice] Believe?! If you believe you are gullible. Can you look
          around this world and believe in the goodness of a god who rules it?
          Famine, Pestilence, War, Disease and Death! They rule this world.
          <br />
          [Female Voice] There is also love and life and hope.
          <br />
          [Male Voice] Very little hope I assure you. No. If a god of love and
          life ever did exist... he is long since dead. Someone... something
          rules in his place.
        </div>
      </div>
    </div>
  </div>
</template>
