# quick_glam_capstone

### About QuickGlam

QuickGlam is a mock e-commerce website that specializes in selling press on acrylic nails. It is meant to give a feel of a real working website with working links and input forms. The theme that I chose for the website was pink, I wanted to give it a rock princess feel. The website is consisted of HTML/CSS/Bootstrap usage to make it run. Some of the challenges I faced are image sizing and hoping to incorporate a bigger knowledge of bootstrap to make it easier. The pages the website include are:

* Home Page 
* Product Page
* New User Page
* Returning User Page
* Checkout page



    

 ![homepage](/images/homescreenshot.PNG)
   ![prodcutpage](/images/productpage.PNG)
    ![newuserpage](/images/newuserpage.PNG)
    ![returninguserpage](/images/returninguserpage.PNG)
    ![checkoutpage](/images/checkoutpage.PNG)

 #### A intresting piece of code
While making the website I had a lot of help when implementing code. While I had outside sources to help me, I made sure to understand it as well as make it my own. A piece of code that I was happy to make mine was in the "newuser.html". In this piece I used different input forms to make it my own as well as learned where to add "needs-validation" and where to add "required" to have it be responsive, if left empty. 
```javascript
// implemented validation to all input forms
<form class="row g-3 needs-validation" validate> 
        <div class="row g-3">
          <div class="col">
            <label for="inputfirstname4" class="form-label" style="font-family: 'DM Serif Display', serif;">First Name</label>
            <input type="text" class="form-control" placeholder="John" aria-label="First name" required>
            <div class="valid-feedback">
              Looks good!
            </div>
          </div>
          <div class="col">
            <label for="inpulastname4" class="form-label" style="font-family: 'DM Serif Display', serif;">Last Name</label>
            <input type="text" class="form-control" placeholder="Doe" aria-label="Last name" required>
          </div>
        </div>
        <div class="col-md-6">
          <label for="inputEmail4" class="form-label" style="font-family: 'DM Serif Display', serif;">Email</label>
          <input type="email" class="form-control" id="inputEmail4" placeholder="johndoe@email.com" aria-label="Email" required>
        </div>
        <div class="col-md-6">
          <label for="inputPassword4" class="form-label" style="font-family: 'DM Serif Display', serif;">Password</label>
          <input type="password" class="form-control" id="inputPassword4" required>
        </div>
        <div class="col-md-12">
          <label for="inputPassword4" class="form-label" style="font-family: 'DM Serif Display', serif;">Confirm password</label>
          <input type="password" class="form-control" id="inputPassword4" required>
        </div>
        <p style="font-family: 'DM Serif Display', serif;">How did you hear about us?</p>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
          <label class="form-check-label" for="flexRadioDefault1" style="font-family: 'DM Serif Display', serif;">
            Social Media
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" checked>
          <label class="form-check-label" for="flexRadioDefault2" style="font-family: 'DM Serif Display', serif;">
            Other
          </label>
        </div>
        <div class="col-12">
          <button type="submit" class="btn btn-primary">Sign in</button>
        </div>
      </form>
```

#### Websites that helped build this website
[BootStrap](https://getbootstrap.com/)

[w3school](https://www.w3schools.com/bootstrap5/index.php)

[MDB](https://mdbootstrap.com/)