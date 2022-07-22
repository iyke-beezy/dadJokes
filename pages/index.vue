export <template>
  <div>
    <Default />
    <h2>
      Welcome to the best dad jokes on the planet.
    </h2>
  </div>
</template>

<script>
import Default from './../layouts/default'
export default {
    layout: "<Default />",
    head() {
        return {
            title: "Welcome to Dad Jokes",
            meta: [
                {
                    hid: "description",
                    name: "description",
                    content: "Best Place for Corny Dad Jokes",
                },
            ],
        };
    },
    components: { Default }
}
</script>
