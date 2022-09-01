<template>
  <div>
    <div class="login-page">
      <div class="form">
        <form>
          <h1>Login to your account</h1>
          <input type="text" placeholder="Email" />
          <input type="text" placeholder="Password" />
          <div class="forgot-password">
            <NuxtLink to="/"> Forgot password? </NuxtLink>
          
            </div>

          <button>Sign In</button>
          <div>
            <div class="divider"></div>
            <div class="or">Log in with</div>
            <div class="divider"></div>
          </div>
          <div class="multiple-sign-in">
            <div class="google-sign-in">
              <img src="@/assets/icons/google.svg" alt="" />
              <span>Sign up with Google </span>
            </div>
            <div class="apple-sign-in">
              <img src="@/assets/icons/apple.svg" alt="" />
              <span>Sign up with Apple </span>
            </div>
          </div>

          <div class="new-to-ecojobz">
            New to Ecolabz? <NuxtLink to="/"> Get started </NuxtLink>
          </div>
        </form>
      </div>
      <div class="image">
        <img src="@/assets/images/image-form.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style>
</style>