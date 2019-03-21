<template>
    <div>
        <p>
            Users ID: {{ userId }}
        </p>
    </div>
</template>

<script>
export default {
  data() {
    return {
      userId: this.$route.params.id
    };
  }
};
</script>

