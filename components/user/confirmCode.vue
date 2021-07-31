<template>
  <div>
    <p>کد تایید</p>
    <form>
      <input name="code" placeholder="کد تایید را وارد کنید" type="text" />
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
