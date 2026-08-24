---
hide:
  - navigation
  - toc
---

<style>

.md-main__inner {
    margin-top: 0;
}

.home-header {
  display: grid;
  grid-template-columns: minmax(320px, 1fr) auto minmax(320px, 1fr);
  align-items: center;
  gap: 2rem;

  width: 100%;
  padding: 18px 5vw;
  background: white;
}

.home-nav {
  display: flex;
  align-items: center;
  gap: 2.2rem;
  white-space: nowrap;
}

.home-nav.left {
  justify-content: flex-end;
}

.home-nav.right {
  justify-content: flex-start;
}

.home-logo img {
  display: block;
  width: 300px;
  max-width: 34vw;
  height: auto;
}

.home-nav a {
  white-space: nowrap;
  text-decoration: none;
  font-weight: 600;
}
.client-login {
  border: 2px solid currentColor;
  padding: 0.7rem 1.4rem;
  border-radius: 4px;
}


.hero {
  min-height: 650px;

  background:
    linear-gradient(
      rgba(10, 25, 40, 0.45),
      rgba(10, 25, 40, 0.45)
    ),
    url("../img/hero-bridge.jpg") center / cover no-repeat;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  padding: 3rem;
  text-align: center;
  color: white;
}

.hero h1 {
  color: white;
  font-size: 3.5rem;
}

.hero-button {
  display: inline-block;
  padding: 0.8rem 1.4rem;
  background: #0756d8;
  color: white !important;
  text-decoration: none;
  border-radius: 4px;
  font-weight: 700;
}


</style>

<div class="home-header">
  <div class="home-nav left">
    <a class="client-login" href="../client-login/">Client Login</a>
    <a href="../services/">Services</a>
    <a href="../team/">Team</a>
  </div>

  <div class="home-logo">
    <img src="../img/bond-bridge-logo.svg" alt="Bond Bridge">
  </div>

  <div class="home-nav right">
    <a href="../case-studies/">Case Studies</a>
    <a href="../contact-us/">Contact Us</a>
  </div>
</div>


<div class="hero" markdown>

# Fixed Income Data & <br /> Analytics. Built for Scale.

End-to-end expertise in data architecture, analytics infrastructure, and API <br />
integration for public and private fixed income markets.

**Quick conversation. No pitch. Just expertise in fixed income data and analytics.**

</div>
