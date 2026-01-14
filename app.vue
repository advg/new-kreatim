<template>
  <div class="container">
    <div class="content">
      <h1>Notre site fait peau neuve !</h1>
      <p class="subtitle">Il est actuellement en cours de refonte.</p>

      <div class="contact">
        <p>Pour continuer à jouer avec nous :</p>
        <div class="contact-links">
          <a href="mailto:kreatim@adventuregroup.fr" class="contact-link">
            <Icon name="lucide:mail" class="icon" />
            <span>kreatim@adventuregroup.fr</span>
          </a>
          <a href="tel:0428296340" class="contact-link">
            <Icon name="lucide:phone" class="icon" />
            <span>04.28.29.63.40</span>
          </a>
        </div>
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
  background-color: #0a1543;
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
  color: #ffbb18;
}

.subtitle {
  font-size: 1.25rem;
  margin-bottom: 3rem;
  opacity: 0.9;
}

.contact {
  background-color: rgba(255, 255, 255, 0.08);
  padding: 2.5rem;
  border-radius: 16px;
  backdrop-filter: blur(10px);
}

.contact p {
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
  line-height: 1.6;
}

.contact-links {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.contact-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 0.75rem;
  color: white;
  text-decoration: none;
  font-size: 1.1rem;
  font-weight: 500;
  padding: 0.875rem 1.5rem;
  border-radius: 8px;
  background-color: rgba(255, 255, 255, 0.08);
  border: 1px solid rgba(255, 255, 255, 0.15);
  transition: all 0.2s ease;
}

.contact-link:hover {
  background-color: rgba(255, 255, 255, 0.12);
  border-color: rgba(255, 255, 255, 0.25);
  transform: translateY(-2px);
}

.icon {
  width: 20px;
  height: 20px;
  color: #ffbb18;
}

@media (max-width: 640px) {
  h1 {
    font-size: 1.75rem;
  }

  .subtitle {
    font-size: 1rem;
  }

  .contact {
    padding: 1.5rem;
  }

  .contact-link {
    font-size: 0.95rem;
    padding: 0.75rem 1rem;
  }
}
</style>
