<div>
  <img src="https://res.cloudinary.com/di4veouyn/image/upload/v1685684827/mags.jpg">
  <div class="hero-tiles-container">
    <div class="hero-image">
      <h2>
        📆 
      </h2>
      <h3>
        Book a demo
      </h3>
    </div>
    <div class="hero-image">
      <h2>
        🤙
      </h2>
      <h3>
        Contact for more information
      </h3>
    </div>
  </div>
  
</div>

<style>
  img {
    width: 100%;
    object-fit: cover;
    
  }

  @media(max-width: 750px) {
    img {
      height: 300px;
    }
  }

  @media(min-width: 750px) {
    img {
      height: 600px;
    }
  }

  .hero-image {
    flex: 1;
    min-height: 160px;
    min-width: 200px;
    background-color: var(--white);
    position: relative;
    padding: 10px;
    bottom: 120px;
    border-radius: 18px;
    border: 1px solid var(--black);
    margin: 10px;
    transition: transform .5s,box-shadow .5s ease-in-out;
  }

  .hero-tiles-container {
    display: flex;
    flex-wrap: wrap;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
    justify-content: space-evenly;
    width: 100%;

  }

  h2 {
    text-align: center;
  }

  h3 {
    text-align: center;
  }

</style>