export
<template>
  <div>
    <h2>Dad Jokes</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      jokes: [],
    };
  },

  async created() {
    const config = {
      headers: {
        Accept: "Application/json",
        "User-Agent" : "",
      },
    };

    try {
      const res = await axios.get()
    } catch (err) {

    }
  },

  head() {
    return {
      title: "Dad Jokes",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best Place for Corny Dad Jokes",
        },
      ],
    };
  },
};
</script>

<style></style>
