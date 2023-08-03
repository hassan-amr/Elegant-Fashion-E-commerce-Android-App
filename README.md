# Elegant-Fashion-E-commerce-Android-App

## ✅ Contact Me / My Profiles
### <p align="center">Hi there, I'm Hassan Amr 👋</p>
<p align="center">
  <a href="mailto:hassan.amr.soliman@gmail.com" target="_blank">
    <img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/gmail.png" width="50" height="38">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://linkedin.com/in/hassan-amr-684a851ba" target="_blank">
    <img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/linkedin.png" width="45" height="45">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/hassan-amr" target="_blank">
    <img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/github.png" width="50" height="50">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.hackerrank.com/HassanAmrSoliman" target="_blank">
    <img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/hacker_rank.png" width="45" height="50">
  </a>
</p>


## ✅ About the App
<b>➡️ Elegent Fashion is a Multi-Seller E-commerce Android App that I finished developing it in Feb. 2021, I built it to learn, better understand & gain experience in</b>
- E-Commerce Applications
- Android Build Variants
- Firebase Products
- Applications with high complexity architecture and huge number of classes
- Crahlytics and Reports


<b>➡️ And I was able to accomplish the above requirements using</b>
- Java Programming Language
- Android Product Flavors
- Firebase Cloud Firestore
- Firebase Cloud Storage Database
- Firebase Crashlytics

<b>➡️ Finally I merged all of the above in an Multi-Seller E-commerce App with 3 App Versions that allows the user to</b>

<b>📱 Elegant Fashion (Customer)</b>
- Register and Login
- Account Settings and Preferences
- Search and Filter Products
- Add Products to WishList
- Add Products to Cart
- Checkout Order
- Track Orders (Past and Current)
- Rate Products

<b>📱 Elegant Fashion (Seller)</b>
- Register and Login
- Account Settings and Preferences
- Add, Edit or Delete his/her Products
- Track Customer Orders
- Dashboard for Revenue, Products Count, Orders Count (Shipped / Cancelled / Denied)

<b>📱 Elegant Fashion (Admin)</b>
- Login
- Add products and Edit/ Delete any Product
- Accept / Deny new Sellers and Products
- Block/ Unblock Users and Sellers
- Dashboard for Revenue, Products Count, Orders Count (Shipped / Cancelled / Denied), Accepted / Denied Sellers and Products, Blocked Users and Sellers
- Search and Filter Products, Users and Sellers

## ✅ Project Files Structure
<table>
  <tr>
    <th><b>Common Java Files</b></th>
    <th><b>Customer Java Files</b></th>
    <th><b>Seller Java Files</b></th>
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/main_java_files.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_java_files.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_java_files.png"></td>
  </tr>

  <tr>
    <th><b>Admin Java Files</b></th>
    <th><b>Layout Files</b></th>
    <th><b>Layout Files (Cont.)</b></th>
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_java_files.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/layout_files.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/layout_files_cont.png"></td>
  </tr>
 
</table>

## ✅ Libraries Used & Product Flavors

- **Libraries Used**
```
    implementation 'androidx.appcompat:appcompat:1.1.0'
    implementation 'androidx.constraintlayout:constraintlayout:1.1.3'

    implementation 'com.android.support:appcompat-v7:28.0.0'
    implementation 'com.android.support:support-v4:28.0.0'
    implementation 'com.android.support:design:28.0.0'

    implementation 'com.android.support:cardview-v7:28.0.0'
    implementation 'com.android.support:recyclerview-v7:28.0.0'
    implementation 'android.arch.paging:runtime:2.1.1'

    implementation 'com.firebaseui:firebase-ui-firestore:6.2.1'
    implementation 'com.google.firebase:firebase-auth:19.2.0'
    implementation 'com.google.firebase:firebase-storage:19.1.1'
    implementation platform('com.google.firebase:firebase-bom:25.12.0')
    implementation 'com.google.firebase:firebase-crashlytics'

    implementation 'com.squareup.picasso:picasso:2.5.2'
    implementation 'de.hdodenhof:circleimageview:3.1.0'
    implementation 'com.github.denzcoskun:ImageSlideshow:0.0.7'
    implementation 'com.kofigyan.stateprogressbar:stateprogressbar:0.0.1'
    implementation 'com.crystal:crystalrangeseekbar:1.1.3'
    implementation 'com.borjabravo:readmoretextview:2.1.0'

    implementation 'com.android.support:multidex:1.0.3'
```
- **Product Flavors**
```
    flavorDimensions "default"
    productFlavors {

        customer {

        }

        seller {
            applicationIdSuffix ".seller"
        }

        admin {
            applicationIdSuffix ".admin"
        }

    }
```

## ✅ Elegant Fashion (Customer) App Screenshots
<table>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P1.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P2.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P3.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P4.png"></td>
    
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P5.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P6.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P7.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P8.png"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P9.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P10.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P11.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P12.png"></td>
  </tr>
  <tr>
  <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P13.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P14.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P15.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/customer_screenshots/P16.png"></td>
  </tr>
</table>

## ✅ Elegant Fashion (Seller) App Screenshots
<table>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P1.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P2.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P3.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P4.png"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P5.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P6.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P7.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P8.png"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P9.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P10.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P11.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/seller_screenshots/P12.png"></td>
  </tr>
</table>

## ✅ Elegant Fashion (Admin) App Screenshots
<table>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P1.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P2.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P3.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P4.png"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P5.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P6.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P7.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P8.png"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P9.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P10.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P11.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P12.png"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P13.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P14.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P15.png"></td>
    <td><img src="https://github.com/hassan-amr/Elegant-Fashion-E-commerce-Android-App/blob/main/images/admin_screenshots/P16.png"></td>
  </tr>
</table>
