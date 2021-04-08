<template>
  <section id="contact" class="contact-us">
    <div class="parallax">
      <div class="container">
        <div class="row">
          <div class="heading text-center col-sm-10 col-center">
            <h2 class="wow fadeInDown"> Contact Us</h2>
            <p class="wow fadeInDown">Rincott ideas would be thrilled to talk with you further about your branding, print production and media design needs.</p>
          </div>
        </div>
        <div class="contact-form" >
          <div class="row">
            <div class="col-sm-6 wow fadeIn">
              <form id="main-contact-form" name="contact-form" method="post" action="#">
                <div class="row">
                  <div class="col-sm-6">
                    <div class="form-group">
                      <input name="name" class="form-control" placeholder="Name"  type="text">
                    </div>
                  </div>
                  <div class="col-sm-6">
                    <div class="form-group">
                      <input name="email" class="form-control" placeholder="Email Address" type="email">
                    </div>
                  </div>
                </div>
                <div class="form-group">
                  <input name="subject" class="form-control" placeholder="Subject" required  type="text">
                </div>
                <div class="form-group">
                  <textarea name="message" id="message" class="form-control" rows="4" placeholder="Enter your message" required></textarea>
                </div>
                <div>
                  <button type="submit" class="submit-bt2">Send Now </button>
                </div>
              </form>
            </div>
            <div class="col-sm-6 wow fadeIn">
              <div class="contact-info">
               
                <ul class="address">
                  <li><i class="fa fa-map-marker"></i><span>Address : </span> Shomulu, Lagos, Nigeria</li>
                  <li><i class="fa fa-phone"></i><span>Phone :</span> +234 (0) 816 903 6341</li>
                  <li><i class="fa fa-envelope"></i><span>Email : </span><a href="mailto:rincott@yahoo.com"> &nbsp;rincott@yahoo.com</a></li>
                  <li><i class="fa fa-envelope"></i><span>Email : </span><a href="#">interior &amp; furniture</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Contact'
}
</script>


<style>

</style>
