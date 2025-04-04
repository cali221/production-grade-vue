<!-- Challenge: Rewrite the following HTML using a render function -->
<script>
import { h } from 'vue'
export default {
  props: {
    level: {
      type: Number,
      default: 1
    }
  },
  render() {
    return h(`h${this.level}`, 'Hello it works!')
  }
}
</script>

<style></style>
