---
layout: default
title: Contact Us
description: The contact info for Quality Property Inspections.
---
<div>
   <!--::breadcrumb part start::-->
   <section class="breadcrumb blog_bg">
      <div class="container">
         <div class="row">
            <div class="col-lg-12">
               <div class="breadcrumb_iner">
                  <div class="breadcrumb_iner_item">
                     <h2>contact</h2>
                  </div>
               </div>
            </div>
         </div>
      </div>
   </section>
   <!--::breadcrumb part start::-->

  <!-- ================ contact section start ================= -->
  <section class="contact-section area-padding">
    <div class="container">
      <div class="d-none d-sm-block mb-5 pb-4">
        <div id="map" style="height: 480px;"></div>
        <script>
          function initMap() {
            var rowlandHeights = {lat: 33.970959, lng: -117.896210};
            var map = new google.maps.Map(document.getElementById('map'), {
              center: {lat: 33.970959, lng: -117.896210},
              zoom: 11,
              scrollwheel:  false
            });
            var marker = new google.maps.Marker({
               position: rowlandHeights,
               map: map
            });
          }
          
        </script>
        <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyABh2lDPSAqKYfXn3JqIBQSFTMH4_WZGDI&callback=initMap"></script>
        
      </div>


      <div class="row">
        <div class="col-12">
          <h2 class="contact-title">Get in Touch</h2>
        </div>
        <!--
        <div class="col-lg-8">
          <form class="form-contact contact_form" action="contact_process.php" method="post" id="contactForm" novalidate="novalidate">
            <div class="row">
              <div class="col-12">
                <div class="form-group">
                    <textarea class="form-control w-100 placeholder hide-on-focus" name="message" id="message" cols="30" rows="9" placeholder="Enter Message"></textarea>
                </div>
              </div>
              <div class="col-sm-6">
                <div class="form-group">
                  <input class="form-control placeholder hide-on-focus" name="name" id="name" type="text" placeholder="Enter your name">
                </div>
              </div>
              <div class="col-sm-6">
                <div class="form-group">
                  <input class="form-control placeholder hide-on-focus" name="email" id="email" type="email" placeholder="Enter email address">
                </div>
              </div>
              <div class="col-12">
                <div class="form-group">
                  <input class="form-control placeholder hide-on-focus" name="subject" id="subject" type="text" placeholder="Enter Subject">
                </div>
              </div>
            </div>
            <div class="form-group mt-3">
              <button type="submit" class="button button-contactForm">Send Message</button>
            </div>
          </form>
        </div>
         -->
        <div class="col-lg-4">
          <div class="media contact-info">
            <span class="contact-info__icon"><i class="ti-home"></i></span>
            <div class="media-body">
              <h3><a href="">Rowland Heights</a></h3>
              <p>California</p>
            </div>
          </div>
          <div class="media contact-info">
            <span class="contact-info__icon"><i class="ti-tablet"></i></span>
            <div class="media-body">
              <h3><a href="tel:6264174216">(626) 417-4216</a></h3>
              <p>Available 24/7</p>
            </div>
          </div>
          <div class="media contact-info">
            <span class="contact-info__icon"><i class="ti-email"></i></span>
            <div class="media-body">
              <h3><a href="mailto:tien830@gmail.com">tien830@gmail.com</a></h3>
              <p>Email us at anytime!</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- ================ contact section end ================= -->

</div>