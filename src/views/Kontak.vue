<template>
  <div class="kontak">
    <div class="all-title-box">
            <div class="container text-center">
                <h3>Kontak ESQ Business School Menara 165, Lt 18 & 19 </h3>
            </div>
        </div>

        <div id="contact" class="section wb">
            <div class="container">
                <div class="section-title text-center">
                    <h3>Kritik / Saran</h3>
                    <p class="lead">Apapun saran / kritik yang anda berikan akan sangat bergharga untuk berkembangnya web ini <br> Terima Kasih !</p>
                </div><!-- end title -->

                <div class="row">
                    <div class="col-xl-6 col-md-12 col-sm-12">
                        <div class="contact_form">
                            <div id="message"></div>
                            <form id="contactform" class="" action="config/save_saran.php" name="contactform" method="post">
                                <div class="row row-fluid">
                                    <div class="col-lg-12 col-md-12 col-sm-12">
                                        <input type="text" name="name" id="name" class="form-control" placeholder="Full Name">
                                    </div>
                                    <div class="col-lg-6 col-md-6 col-sm-6">
                                        <input type="email" name="email" id="email" class="form-control" placeholder="Your Email">
                                    </div>
                                    <div class="col-lg-6 col-md-6 col-sm-6">
                                        <input type="text" name="phone" id="phone" class="form-control" placeholder="Your Phone">
                                    </div>
                                    <div class="col-lg-12 col-md-12 col-sm-12">
                                        <textarea class="form-control" name="isi" id="isi" rows="6" placeholder="Give us more details.."></textarea>
                                    </div>
                                    <div class="text-center pd">
                                        <button type="submit" value="SEND" id="submit" class="btn btn-light btn-radius btn-brd grd1 btn-block">Send Massage</button>
                                    </div><br>
                                </div>
                            </form>
                        </div>
                    </div><!-- end col -->
                    <div class="col-xl-6 col-md-12 col-sm-12">
                        <div class="map-box">
                            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3965.794715324946!2d106.8073964143412!3d-6.290690463321816!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f1fa599ef523%3A0xce4d3f317f5ed3f4!2sMenara+165%2C+Jl.+TB+Simatupang%2C+RT.3%2FRW.3%2C+Cilandak+Tim.%2C+Ps.+Minggu%2C+Kota+Jakarta+Selatan%2C+Daerah+Khusus+Ibukota+Jakarta+12560!5e0!3m2!1sid!2sid!4v1556449770243!5m2!1sid!2sid" width="600" height="500" frameborder="0" style="border:0" allowfullscreen></iframe>
                        </div>
                    </div>
                </div><!-- end row -->
            </div><!-- end container -->
        </div><!-- end section -->
  </div>
</template>
