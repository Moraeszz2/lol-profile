<template>
	<v-container>
		<v-layout align-center text-center wrap>
			<v-flex xs12>
				<v-img src="/android-chrome-512x512.png" class="my-3" contain height="200"></v-img>
			</v-flex>

			<v-flex mb-4>
				<h1 class="display-2 font-weight-bold mb-3">
					Seja bem vindo!
				</h1>
				<p class="subheading font-weight-regular">
          teste
        </p>
			</v-flex>
		</v-layout>
	</v-container>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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
