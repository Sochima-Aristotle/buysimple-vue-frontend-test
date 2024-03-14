<template>
  <!-- <div class="wholePage">
    <div class="page1">
      <img src="./assets/project.png" alt="Logo" class="img" />
      <p class="green">Tailwind</p>
    </div>
    <div class="bg-slate-900">
      <div class="flex items-center justify-center">
        <h1>Welcome</h1>
        <p>Enter ...</p>
      </div>
    </div>
  </div> -->

  <div class="container">
    <div class="showcase">
      <div class="logo">
        <img src="./assets/logo.png" alt="logo" />
      </div>

      <div class="showcase-image">
        <img src="./assets/showcase.png" alt="logo" />
      </div>

      <div class="showcase-text">
        <h1>Team Achieve</h1>
        <p>Your perfect solution for funding your desires</p>
      </div>
    </div>

    <div class="form">
      <div class="mobile-logo">
        <img src="./assets/logo.png" alt="logo" />
      </div>

      <div class="form-title">
        <h1>Welcome Back</h1>
        <p>Enter your email address and password to access your account.</p>
      </div>

      <form>
        <div class="email">
          <label for="email">
            Email Address
            <span class="required">*</span>
          </label>

          <input
            type="email"
            id="email"
            name="email"
            class=""
            placeholder="Enter Email"
          />
        </div>

        <div class="password">
          <label for="password"
            >Password

            <span class="required">*</span>
          </label>
          <input
            type="password"
            id="password"
            name="password"
            class=""
            placeholder="Enter Password"
          />
        </div>

        <div class="form-features">
          <div class="remember">
            <input type="checkbox" name="remember" id="remember" />
            <p>Remember Me</p>
          </div>

          <a href="#">Forgot Password</a>
        </div>

        <button type="submit">Sign In</button>

        <div class="signup-cta">
          <p>Don't have an account?</p>
          <a href="#">Sign Up</a>
        </div>
      </form>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
