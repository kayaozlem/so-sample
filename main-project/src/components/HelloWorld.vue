<template>
  <div class="hello">
    <dummy-button />
    <DummyImage />
  </div>
</template>

<script>
import DummyButton from 'ui-library/src/components/DummyButton';
import DummyImage from 'ui-library/src/components/DummyImage';

export default {
  name: 'HelloWorld',
  components: {DummyButton, DummyImage},
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
