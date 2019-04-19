### BC Mega Menu
This module use create mega menu for site

You can manage Add/Edit/Delete/Enable/Disable mega menu

![](/assets/bcmenu1.jpg)

### Step add new mega menu
#### Step 1:  Configure information mega menu
* Name : name of mega menu
* Identifier : id of menu
* Class: if you need edit css for each menu, you can add name class for menu.
* Hook into : select position display this menu on frontend
Disable/enable this block on frontend
![](/assets/bcmenu2.jpg)

#### Step 2: Create new menu parent item
1. Drag/Drop "Menu item" to "Content area"
2. Click button edit information parent item
![](/assets/bcmenu3.jpg)

3. Input information parent item
    * Name : name of parent item
    * Link : you can input links url (EX : http://www.arenathemes.com/ ) or use link internal site (EX: link http://www.yoursite.com/contactus , you can input "contactus")
    * Font Awesome Icon: add icon font awesome for parent menu.
    * Class: if you need edit css for each menu item , you can add class for menu item.
![](/assets/bcmenu4.jpg)

4. Save menu.

#### Step 3: Create dropdown for menu parent item
1. Click button configure show dropdown of parent item
2. Drag/Drop "Column" to "Content dropdown"
3. Select size for column (1 - 12)
    * Content dropdown can add many columns : 1,2,3,4,5,6 columns
    * Max total size of columns is 12
    * Example some layout dropdown : 1 column(2, 3), 2 columns(2-2, 2-3), 4 columns(3-3-3-3, 3-2-2-3), 5 columns(2-2-2-2-2, 3-2-2-2-3)
4. Drag/Drop "Widget item" to "Content column"
5. Click widget and input information for widget
![](/assets/bcmenu5.jpg)

#### Step 4: Configure content widget item
**1. Widget Link:**
* Title : name link
* Link : you can input links url (EX : http://www.arenathemes.com/ ) or use link internal site (EX: link http://www.yoursite.com/contactus , you can input "contactus")
![](/assets/bcmenu6.jpg)

**2. Text:**
* Content : Input content of widget. If you want input content with format HTML , you can click in editor button "Source"
* Note : if you want use link internal site in content , you can use code "{base_url}". 
EX : ``<a href={base_url}order">Link</a>``
![](/assets/bcmenu7.jpg)

**3. Category:**
* Select parent category : It will display list subcategories of category that you select.
* Show sub category : enable/disable show child categories of subcategories (Display category level 3)
![](/assets/bcmenu8.jpg)

**4. Product:**
* Product: input list id products. Ex:2,5,12. You can find id product in **Catalog > products**
* Style : select style template of products
![](/assets/bcmenu9.jpg)



