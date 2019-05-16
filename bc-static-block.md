#### BC Static Block
This module is show static blocks on frontend. You can add many blocks on frontend

1. You can manage Add/Edit/Delete/Enable/Disable static block

    ![](/assets/bcblock1.jpg)

2. Add/Edit static block


* Title : title each block show on frontend
* Identifier : id of block
* Hook into : select postion display this filter block on frontend
* Disable/enable this block on frontend
* Content : Input content of static block. If you want input content with format HTML , you can click in editor menu "Tools > source code"

    ![](/assets/bcblock2.jpg)

#### Example code
**1. Need help**
Hook: displayNav1
```
<p>Need help? <a href="#">Send us a ticket</a></p>
```
![](/example/bcblock1.jpg)

**2. Copyright Footer**
Hook: displayFooterAfter
```
<div class="copy-right col-sm-5">© 2019 AutoPart Market Store. All Right Reserved. PrestaShop Themes by arenathemes</div>
```
![](/example/bcblock2.jpg)

**3. Hotline header**
Hook: displayTop
```
<div class="phone">
<div class="phone-icon-wrapper"><i class="demo-icon icon-headphones">.</i></div>
<div class="phone-info-wrapper"><span>Hotline:</span> <span> (+800) 123 456 7890 </span></div>
</div>
```
![](/example/bcblock3.jpg)

**4. Info Top Contact**
Hook: displayTopContact
```
<div class="contact-info-icons row">
<div class="col-md-4 col-xs-12 col-sm-4">
<div class="contact-info"><i class="arena-icons icon-phone-icon"></i><span class="contact-info-title">+48 655 555 555</span><span class="contact-info-subtitle">Phone Us</span></div>
</div>
<div class="col-md-4 col-xs-12 col-sm-4">
<div class="contact-info middle"><i class="arena-icons icon-mailicon"></i><span class="contact-info-title">support@arenathemes.com</span><span class="contact-info-subtitle">Write us Email</span></div>
</div>
<div class="col-md-4 col-xs-12 col-sm-4">
<div class="contact-info last"><i class="arena-icons icon-faxicon"></i><span class="contact-info-title">+48 655 555 555</span><span class="contact-info-subtitle">FAX Us</span></div>
</div>
</div>
```
![](/example/bcblock4.jpg)

**5. Info Bottom Contact**
Hook: displayBottomContact
```
<address class="text-center light-bg"><span class="address-title">Arenathemes Co.</span> 3100 West Cary Street Richmond, Virginia 23221<br /> Phone: +48 548 499 999</address>
<p><iframe width="1170" height="450" style="border: 0;" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d501702.6042522421!2d106.41416795384438!3d10.768999950616228!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x317529292e8d3dd1%3A0xf15f5aad773c112b!2zSOG7kyBDaMOtIE1pbmgsIFZp4buHdCBOYW0!5e0!3m2!1svi!2s!4v1444821132224" frameborder="0" allowfullscreen="allowfullscreen"></iframe></p>
```
![](/example/bcblock5.jpg)

**6. Track my order**
Hook: displayTopRight
```
<p><a href="#" class="track-order-btn"><span><i class="demo-icon icon-paper-plane-empty">.</i>track my order</span></a></p>
```
![](/example/bcblock6.jpg)

**7. Banner TopHome**
Hook: displayTopHome
```
<div class="home-banner-items">
<div class="row">
<div class="col-xl-3 col-lg-3  col-12">
<div class="banner-item">
<div class="image"><a href="/collections"> <img class=" lazyloaded" alt="Banner" src="https://arenatheme.gitlab.io/demo-image/autopart/Banner_1.png" /> </a></div>
<div class="text ">
<div class="title">B&M 111212 Street</div>
<div class="subtitle">Strip Transmission</div>
<div class="offer"><span class="text">Starting from</span>
<div class="price"><span class="prices-banner">$59.95</span> <span class="label">New</span></div>
</div>
</div>
</div>
</div>
<div class="col-xl-6 col-lg-6 col-12 hide-mobile">
<div class="banner-item">
<div class="image"><a href="/collections"> <img class=" lazyloaded" alt="Banner" src="https://arenatheme.gitlab.io/demo-image/autopart/Banner_2.png" /> </a></div>
<div class="text ">
<div class="title">THE BEST PRICES</div>
<div class="subtitle">ACCESSSORIES</div>
<div class="offer"><span class="text">Head Units & Receivers</span></div>
<a class="btn btn-banner" href="#">Shop Now</a></div>
</div>
</div>
<div class="col-xl-3 col-lg-3  col-12">
<div class="banner-item">
<div class="image"><a href="/collections"> <img class=" lazyloaded" alt="Banner" src="https://arenatheme.gitlab.io/demo-image/autopart/Banner_3.png" /> </a></div>
<div class="text ">
<div class="title">Deluxe Cooling</div>
<div class="subtitle">System Pressure</div>
<div class="offer"><span class="text">Starting from</span>
<div class="price" span="">$59.95</div>
</div>
</div>
</div>
</div>
</div>
<div class="row">
<div class="col-xl-6 col-lg-6 col-12 hide-mobile">
<div class="banner-item">
<div class="image"><a href="/collections"> <img class=" lazyloaded" alt="Banner" src="https://arenatheme.gitlab.io/demo-image/autopart/Banner_4.png" /> </a></div>
<div class="text ">
<div class="title">THE BEST PARTS</div>
<div class="subtitle">FOR YOUR CAR.</div>
<div class="offer"><span class="text">Head Units & Receivers</span></div>
<a class="btn btn-banner" href="#">Shop Now</a></div>
</div>
</div>
<div class="col-xl-6 col-lg-6 col-12 hide-mobile">
<div class="banner-item">
<div class="image"><a href="/collections"> <img class=" lazyloaded" alt="Banner" src="https://arenatheme.gitlab.io/demo-image/autopart/banner_5.png" /> </a></div>
<div class="text ">
<div class="title">THE BEST PRICES</div>
<div class="subtitle">ACCESSSORIES</div>
<div class="offer"><span class="text">Head Units & Receivers</span></div>
<a class="btn btn-banner" href="#">Shop Now</a></div>
</div>
</div>
</div>
</div>
```
![](/example/bcblock7.jpg)

**8. Banner Mid Car Services**
Hook: displayMidHome
```
<div class="banner-services">
<div class="left-content">
<div class="text">
<div class="hotlines"><span class="title"> HOTLINE 24/7: </span> <span class="content">(+1) 000 123 456</span></div>
<div class="block-content">
<p class="title"><span>Anytime</span> & Anywhere You Are</p>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
<a href="#">Learn More</a></div>
</div>
</div>
<div class="right-content parallax" style="background-image: url('https://arenatheme.gitlab.io/demo-image/autopart/background-services.png');">
<div class="content">
<div class="title">AutoPart.</div>
<div class="subtitle">Car Services</div>
</div>
</div>
</div>
```
![](/example/bcblock8.jpg)

**9. Banner Shipping services**
Hook: displayBottomHome
```
<div class="policy-wrapper">
<div class="policy-list">
<div class="policy-item col-12 col-sm-6 col-md-6 col-lg-3">
<div class="icon "><i class="icon-chrom-flying-airplane">.</i></div>
<div class="text">
<h6>FREE DELIVERY</h6>
<span>Worldwide from $75</span></div>
</div>
<div class="policy-item col-12 col-sm-6 col-md-6 col-lg-3">
<div class="icon"><i class="icon-flash">.</i></div>
<div class="text">
<h6>EASY RETURNS</h6>
<span>365 days for free returns</span></div>
</div>
<div class="policy-item col-12 col-sm-6 col-md-6 col-lg-3">
<div class="icon"><i class="icon-chat-empty">.</i></div>
<div class="text">
<h6>COMFORT PAYMENTS</h6>
<span>Credit Cards Available</span></div>
</div>
<div class="policy-item col-12 col-sm-6 col-md-6 col-lg-3">
<div class="icon"><i class="icon-gift">.</i></div>
<div class="text">
<h6>FREE GIFTS</h6>
<span>Get gifts and discounts</span></div>
</div>
</div>
</div>
```
![](/example/bcblock9.jpg)

**10. About Autopart**
Hook: displayFooterHome
```
<div class="about-store">
<h4 class="block-title">About Theloke AutoPart</h4>
<div class="about-description">
<p>A fictional burger shop. Selling locally sourced lamb and beef burgers. Wanted to create something strong and bold to try and reflect the burgers that they would sell. We just wrapped up the design of a live streaming app we've been working on for the past few months. These are the first two screens the user sees after signup up.</p>
</div>
<h4 class="block-title">Payment Method</h4>
<a href="#"><img alt="" src="https://arenatheme.gitlab.io/demo-image/autopart/Payment_logo.png" /></a></div>
```
![](/example/bcblock10.jpg)

**11. Contact Info footer**
Hook: displayFooterBefore
```
<div class="contact-box-wrapper col-12 col-lg-6">
<h4 class="title-block">Contact Info</h4>
<div class="contact-box row" div="">
<div class="support-box col-4"><i class="demo-icons icon-headphones"></i>
<div class="text"><span class="title">Hotlines:</span> <span class="content">(+1) 000 123 456</span> <span class="content">(+1) 000 123 456</span></div>
</div>
<div class="support-box col-4"><i class="demo-icons icon-clock"></i>
<div class="text"><span class="title">Opening Hours:</span> <span class="content">07:00 - 22:00,</span> <span class="content">UTC -11</span></div>
</div>
<div class="support-box col-4"><i class="demo-icons icon-chrom-web-page-home"></i>
<div class="text"><span class="title">Showroom:</span> <span class="content">328 W.North Ave.</span> <span class="content">Troy, NY 12180</span> <a href="#" class="get-direction"><i class="demo-icons icon-paper-plane-empty"></i>Get Direction</a></div>
</div>
</div>
</div>
```
![](/example/bcblock11.jpg)
