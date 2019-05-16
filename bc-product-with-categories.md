#### BC Product With Categories
This module is show product of categories on frontend. You can use many product blocks on frontend

1.You can manage Add/Edit/Delete/Enable/Disable filter product blocks

![](/assets/bcprocat1.jpg)

2.Add/Edit Filter Product

* List Content Category: add/edit/delete list categories will get products
* Title Product : title each product block show
* Hook: select position display this block on frontend
* Template: template display product block
* Custom Template: Input if you choose "Template" is "Custom". File template create in folder /modules/bcproductwithcategories/views/templates/hook/namecustom.tpl
* Number product: Limit number products get in product list
* Number product display : Number product display in slider. ("Use slider" is active)
* Image size: type product image show on frontend
* Use Slider: Disable/enable use slider products
* Active: Disable/enable this product block on frontend
* Content: description block
* Order: sort block on frontend

![](/assets/bcprocat2.jpg)

3.Add/Edit content category
* Disable/enable this category product block on frontend
* Category: select category will get products
* Choose big product: select big product will show on frontend (use in special template)
* Big image size: size image product of big product
* Class: if you need edit css for each block , you can add class for block item
* Content: description for each tab product

![](/assets/bcprocat3.jpg)

#### Example configure
###### List Content Category
* List Content Category: select display 3 categories
* Demo content:
```
<div class="tab-item-content">
<p class="title">THE BEST AUTO PARTS</p>
<p class="subtitle">IN PREMIUMS</p>
<p class="description">Quisque quam diam, posuere eu metus non</p>
<a href="#" class="btn-primary"> Shop More</a></div>
<div class="tab-item-background" style="background-image: url('https://arenatheme.gitlab.io/demo-image/autopart/background-tab.png');"></div>
```

###### CONFIGURE PRODUCT WITH CATEGORIES
* Title Product: All Cars Must Have
* Hook: displayHome
* Template: standard
* Custom Template: 
* Number product: 12
* Number product display: 2
* Image size: home_default
* Use Slider: Yes
* Active: Yes
* Content: 
* Order: 0

![](/example/bcprocat.jpg)











