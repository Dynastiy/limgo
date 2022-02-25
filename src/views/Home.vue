<template>
  <div>
    <div class="sign__up">
      <div class="sign-up-container">
        <h4>Sign Up</h4>
        <p class="mb-5">Welcome to Lingo Logistics</p>
        <form action="">
          <div class="mb-3">
            <label for="phone">Phone Number</label>
            <input
            class="input"
              type="tel"
              id="phone"
              name="phone"
              pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"
              placeholder="Enter Your Phone Number"
            />
          </div>
          <div class="mb-3">
            <label for="password">Create Password</label>
            <div class="input-field">
                <input
                type="password"
                id="password"
                name="password"
                placeholder="Pick a strong password"
              />
            </div>
          </div>
          <div class="mb-3">
            <label for="confirm-password">Confirm Password</label>
            <div>
                <input
                type="password"
                id="confirm-password"
                name="confirm-password"
                placeholder="Confirm your password"
              />
            </div>
          </div>
          <div class="mt-5">
            <button type="submit" id="submit" > Create Account </button>
          </div>
          <div class="mt-5 text-center">
            <p class="small">Already have an Account? <router-link to="/">Sign in</router-link> </p>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
