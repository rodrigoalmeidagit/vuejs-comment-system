<template>
  <div>
    <main>
      <div class="text-top">
        Videos novos toda <strong>quinta</strong> às <strong>20h</strong>
      </div>
      <a href="https://youtube.com/wdevoficial" target="_blank">
        <img
          alt="Inscreva-se"
          id="subscribe"
          src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg
"
        />
      </a>
      <div class="text-bottom">
        youtube.com/wdevoficial
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
main {
  background-color: var(--color-background-home);
  justify-content: center;
  align-items: center;
}

.text-top {
  color: var(--color-text-light);
  font-size: 22px;
  margin-bottom: 20px;
}

#subscribe {
  width: 340px;
}

.text-bottom {
  color: var(--color-text-light);
  font-size: 18px;
  margin-top: 20px;
}

@media (min-width: 700px) {
  #subscribe {
    width: 400px;
  }
}
</style>
