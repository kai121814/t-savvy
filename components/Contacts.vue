<template>
  <div class="bg-black text-white">
    <footer class="contact-section flex justify-between items-start">
      <div class="column">
        <h1 class="text-center">About Us</h1>
        <div class="intro">
        <p class="mt-5 text-2xl font-bold">Welcome to Tech Savvy</p>
        <p class="mt-5 font-bold">Address</p>
        <p >In front of Ozamiz City Hall, 2nd floor of Mercury Drug/SSS, Ozamiz, Philippines</p>
        <p class="mt-5 font-bold">Email Address</p>
        <p>techsavvy@gmail.com</p>
      </div>
      </div>
      <div class="column">
        <h1 class="text-center">Contact Us</h1>
        <form>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" class="h-8" required>
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" class="h-8" required>
          <label for="message">Message:</label>
          <textarea id="message" name="message" class="h-20" required></textarea>
          <button type="submit" class="bg-teal-700 text-white px-4 py-2">Send Message</button>
        </form>
      </div>
      <div class="column">
        <h1 class="text-center">Follow Us</h1>
        <div class="social-icons text-black">
          <p class="btn bg-teal-700">Facebook</p>
          <p class="btn bg-teal-700 text-black">Instagram</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>
.intro{
  font-size: larger;
}
.bg {
  background-color: #73A9AD;
}

.contact-section {
  @apply flex justify-between items-start;
}

.column {
  @apply flex-1 p-4;
}

.column h1 {
  @apply mb-2 text-3xl font-bold;
}

form {
  @apply grid grid-cols-1 gap-4;
}

form label {
  @apply block;
}

form input,
form textarea,
form button {
  @apply w-full;

}

.social-icons {
  @apply space-y-4 grid grid-rows-1 justify-center mt-8;
}

.btn {
  @apply inline-block px-4 py-4 px-32 text-center rounded text-white;
}

.btn:hover {
  @apply opacity-75;
}

</style>
