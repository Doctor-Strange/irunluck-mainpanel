<template>
  <div>
    <p>sign up</p>
    <form>
      <input name="email" type="email" />
      <input name="password" type="password" />
      <input v-if="load" type="submit" value="ثبت" />
      <input v-else type="submit" value="..." />
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      load: true
    }
  }
}
</script>

<style></style>
