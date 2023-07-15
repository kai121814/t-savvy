
<template>
    <div class="bg text-white">
    <footer class="contact-section">
      <div class="column">
        <h3>About Us</h3>
        <p>Welcome to Tech Savvy</p>
        <p>In front of Ozamiz City Hall, 2nd floor of Mercury Drug/SSS, Ozamiz, Philippines</p>
        <p>Email Address</p>
        <p>techsavvy@gmail.com</p>
    </div>
      <div class="column">
        <h3>Contact Us</h3>
        <form>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" style="height: 20px;" required>
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" style="height: 20px;" required>
          <label for="message">Message:</label>
          <textarea id="message" name="message" style="height: 50px;" required></textarea>
          <button type="submit">Send Message</button>
        </form>
      </div>
      <div class="column">
        <h3>Follow Us</h3>
        <div class="social-icons">
          <a href="#">FaceBook</a>
          <a href="#">Instagram</a>
        </div>
      </div>
    </footer>
</div>
  </template>
  
  <style>
    .bg{
        background-color: #73A9AD;
    }

  .contact-section {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
  }
  
  .column {
    flex: 1;
    padding: 20px;
  }
  
  .column h3 {
    margin-bottom: 10px;
  }
  
  form {
    display: grid;
    grid-template-columns: 1fr;
    grid-gap: 10px;
  }
  
  form label {
    display: block;
  }
  
  form input,
  form textarea,
  form button {
    width: 100%;
  }
  
  .social-icons {
    display: flex;
    gap: 10px;
  }
  
  .social-icons a {
    color: #333;
  }
  
  .social-icons i {
    font-size: 20px;
  }
  </style>