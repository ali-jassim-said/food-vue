<template>
    <section class="section-cta" id="cta">
      <div class="container">
        <div class="cta">
          <div class="cta-text-box">
            <h2 class="heading-secondary">
              Get your first meal for free!
            </h2> 
            <p class="cta-text">Healthy, tasty and hassle-free meals are waiting for you. Start eating well today. You can cancel or pause anytime.
               And the first meal is on us!
            </p>
            <form action="#" class="cta-form">
              <div>
              <label for="name">Full Name</label>
              <input type="text" id="name" placeholder="your name" required>
            </div>
            <div>
              <label for="email">Email address</label>
              <input type="email" name="" id="email" required placeholder="me@example.com">
            </div>
            <div>
              <label for="">Where did you hear us?</label>
              <select name="" id="select-where" required>
                <option value="">Please choose one option</option>
                <option value="Friends">Friends and family</option>
                <option value="Youtube">Youtube video</option>
                <option value="Podcast">Podcast</option>
                <option value="Facebook">Facebook ad</option>
                <option value="Others">Others</option>
              </select>
            </div>
              <button class="btn btn-form">Sign up now</button>
            </form>
          </div>
          <div class="cta-img-box" role="img" aria-label="women enjoy food"></div>   <!--for blind people-->
        </div>
      </div>
    </section>
</template>

<script>
export default {
    name: 'cta'
}
</script>

