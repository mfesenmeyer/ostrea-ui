<template>
	<div>
		<h2>Login</h2>
		<form>
			<div class="form-group">
				<label for="username">Username</label>
				<input />
			</div>
			<div class="form-group">
				<label htmlFor="password">Password</label>
				<input />
				<div>Password is required</div>
			</div>
			<div class="form-group">
				<button class="btn btn-primary">Login</button>
				<router-link to="/register" class="btn btn-link"> Register </router-link>
			</div>
		</form>
	</div>
</template>

<script>
// imports

export default {
  name: 'LoginPage',
  methods: {
    // Log the user in
    login () {
      console.log('Testing method')

    }
  }
}
</script>
<style lang="scss" scoped>
</style>
