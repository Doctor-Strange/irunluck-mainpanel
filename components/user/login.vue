<template>
  <div>
    <p>login</p>
    <form>
      <input name="email" type="email" />
      <input name="password" type="password" />
      <input name="confirmPassword" type="password" />
      <input v-if="load" type="submit" value="ثبت" />
      <input v-else type="submit" value="..." />
    </form>
    <ConfirmCode />
  </div>
</template>

<script>
import ConfirmCode from './confirmCode'

export default {
  data() {
    return {
      load: true
    }
  }
}
</script>

<style></style>
