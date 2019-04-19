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
**1. Banner left**
Hook: displayLeftColumn
```
<div class="bc-banner-left d-none d-md-block"><a href="3-clothes"><img src="https://arenatheme.gitlab.io/demo-image/electro/left-sidebar-banner.png" alt="" height="800" width="480" /></a></div>
```
![](/example/bcblock1.jpg)

**2. Copyright Footer**
Hook: displayFooterAfter
```
<div class="copy-right col-sm-5">© 2019 Electro Market Store. All Right Reserved. PrestaShop Themes by arenathemes</div>
<div class="col-sm-7 bc-bewaer-ft"><a href="#"><img alt="" src="https://arenatheme.gitlab.io/demo-image/electro/logo_pament_1.png" /></a></div>
```
![](/example/bcblock2.jpg)

**3. Banner Home**
Hook: displayTopHome
```
<div class="bc-banner-top">
<div class="row">
<div class="bc-banner bc-banner-1 col-sm-8">
<div class="bc-banner--wrapper"><a href="./3-clothes"><img src="https://arenatheme.gitlab.io/demo-image/electro/banner_home_2.png" alt="" width="1366" height="407" /></a>
<div class="text-content">
<p class="simple-text">Simple Promotion</p>
<p class="color-text">Get Up To 25% Off</p>
<span class="check-icon"></span></div>
</div>
</div>
<div class="bc-banner bc-banner-2 col-sm-4">
<div class="bc-banner--wrapper"><a href="./blog"><img src="https://arenatheme.gitlab.io/demo-image/electro/banner_home_1.png" alt="" width="800" height="600" /></a>
<div class="text-content">
<p class="simple-text">Simple Promotion</p>
<span class="check-icon"></span></div>
</div>
</div>
</div>
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






