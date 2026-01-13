<template>
  <div class="container">
    <div class="content">
      <h1>Notre site fait peau neuve !</h1>
      <p class="subtitle">Il est actuellement en cours de refonte.</p>

      <div class="contact">
        <p>
          En attendant, nous restons bien sûr disponibles pour répondre à vos
          questions :
        </p>
        <a href="mailto:kreatim@adventuregroup.fr" class="email"
          >Kreatim@adventuregroup.fr</a
        >
        <a href="tel:0428296340" class="phone">04.28.29.63.40</a>
      </div>
    </div>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Montserrat", sans-serif;
}

.container {
  min-height: 100vh;
  background-color: #1e9ca8;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 2rem;
}

.content {
  text-align: center;
  color: white;
  max-width: 600px;
}

h1 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
}

.subtitle {
  font-size: 1.25rem;
  margin-bottom: 3rem;
  opacity: 0.9;
}

.contact {
  background-color: rgba(255, 255, 255, 0.1);
  padding: 2rem;
  border-radius: 12px;
}

.contact p {
  font-size: 1rem;
  margin-bottom: 1.5rem;
  line-height: 1.6;
}

.email,
.phone {
  display: block;
  color: white;
  text-decoration: none;
  font-size: 1.25rem;
  font-weight: 600;
  margin: 0.75rem 0;
  transition: opacity 0.2s;
}

.email:hover,
.phone:hover {
  opacity: 0.8;
}

@media (max-width: 640px) {
  h1 {
    font-size: 1.75rem;
  }

  .subtitle {
    font-size: 1rem;
  }

  .email,
  .phone {
    font-size: 1rem;
  }
}
</style>
