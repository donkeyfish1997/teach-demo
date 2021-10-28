<script>
export default {
  data() {
    const a = { b: { c: "hi" } };
    return { a };
  },
};
</script>
<template>
  <div>
    <!-- 這麼寫可以 -->
    {{ a.b.c }}
    <!-- 這麼寫就會出錯 -->
    {{ a?.b.c }}
  

  </div>
</template>

