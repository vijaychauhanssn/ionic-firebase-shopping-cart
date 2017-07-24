# Shopping Cart 

##UPDATE (10-07-2016)
[FoodKart v0.3](https://github.com/vijaychauhanssn/ionic-firebase-shopping-cart.git) is released. Read the complete [tutorial series here](https://ssn.000webhostapp.com/tag/firebase/). 



FoodKart v0.2

FoodKart is an simple Food Purchase App, build in HTML5 - Cordova. Since it is a web app, you can easily port it to all the platforms.

Here is a complete set of Tutorials for Ionic Cordova:

[Ionic Cordova Shopping Cart ](https://ssn.000webhostapp.com/tag/shopping-cart/)

###  What's New:

    1. Added Image Slider to show the featured product (ie food items)
    2. Added lazy load feature for product listing (ie it loads products list only when you scroll down )
    3. Cart Bug fixed (Earlier the cart values would decrement to -ve )
    4. Added more products in the menu list

###  Bugs to be Fixed:

    1. The lazy load list is based on state change listener. So it load more products every time you change the page (ie if you go to cart page and then come back to menu page, it would add 3 products to the product list )

###  Feature to be Added:

    1. Easy login/registration with phone number verification
    2. Back-end to handle orders
    3. Dynamically get the featured listing
    4. Push notification service to show the order status.

###  Potential Use :

    1. In food courts you could host a local WiFi, with its default page as FoodKart. 
    Then when the user need to order a product, he could easily connect to the WiFi 
    and place the order.  


Installation

Please you could find more detailed installation and build instructions at the App official documentation.

#Install Latest Ionic Framework
$ npm install -g ionic@latest

#Browse the App
$ cd ionic-firebase-shopping-cart

#Install package.json dependencies
$ npm install

#Install Cordova/PhoneGap plugins (cordovaPlugins pakage.json branch dependencies)
$ ionic state restore (obsolete in CLI 3)

#Test your app on multiple screen sizes and platform types by starting a local development server
$ ionic serve
or
$ ionic serve --lab 

#Build iOS
$ ionic platform add ios
$ ionic build ios --prod

Or with Ionic CLI 3 https://ionicframework.com/docs/cli/

$ ionic cordova platform rm ios
$ ionic cordova platform add ios
$ ionic cordova prepare ios
$ ionic cordova build ios --prod

#Build Android
$ ionic platform add android
$ ionic build android --prod

Or with Ionic CLI 3 https://ionicframework.com/docs/cli/

$ ionic cordova platform rm android
$ ionic cordova platform add android
$ ionic cordova prepare android
$ ionic cordova build android --prod

#Deploying/Running on emulator
$ ionic run android --prod
Ionic View

You have always the option to try the Ionic Framework App by downloading the Ionic View (http://view.ionic.io/). Then, use the following App Id to fetch a preview of the app: 2b03d01e
APK

Download Android APK
Ionic 3 + Angular 4 + Typescript UAC: Useful Articles Collection

https://docs.google.com/document/d/1DGka2qg5bacJw_jgVvsXDo-2g7AW0ffjjxNUtGlcEqM
Releases

Ionic Framework App 1.11.0
- Filter Wordpress Posts by Author (Linked Author)
- Home Wordpress Page integration
- Updated Ionic Framework to 3.4.2 and Angular to 4.1.3
- Updated Module Dependencies  
Ionic Framework App 1.10.0
- Firebase 4 integration. New Firebase Module, Firebase Home, Firebase Login, Firebase Sign Up, Firebase Reset Password Components
- Firebase Authentication/Login with Email/Password and Facebook Sign-In Methods
- Firebase Logout
- Firebase New User (Email/Password) Registration
- Firebase Password Reset Email functionality
- Firebase Detailed Documentation
- Wordpress Tags integration
- In App Wordpress Tags integration in the Wordpress Menus
- Ionic Framework update to 3.2.0 and Angular to 4.1.0
- Ionic Native update to 3.6.1
- Ionic app-scripts update to 1.3.7
- Fixed double fire event in the Social Sharing action
- Several updates/fixes
Ionic Framework App 1.9.0
- Ionic 3 + Angular 4, Ionic Framework update to 3.0.1
- Ionic app-scripts update to 1.3.1 and Typescript update to 2.2.1
- Added Feed Category support
- Several updates
Ionic 2 App 1.8.0
- Split Pane component integration
- Nav-inception integration
- Added Wordpress Menus nested navigation support to the side content
- Set/Get Facebook Loggedin User to Ionic Storage
- Events publish-subscribe style event system integration
- Ionic 2 Framework update to 2.3.0
- Ionic Native 3.x update (installation only of the active plugins)
- Ionic 2 app-scripts update to 1.1.4 and ionic-storage to 2.0.0
- Several fixes/improvements
Ionic 2 App 1.7.0
- Youtube Channels integration with Youtube Channel and Channel Video Components
- Order Youtube Videos by date
- Ionic 2 Framework update to 2.1.0
- Ionic 2 app-scripts update to 1.1.3
Ionic 2 App 1.6.0
- Charts integration, New Charts Module and Charts Component (Bar, Line, Radar, Polar, Pie, Bubble, Doughnut, Mixed Charts)
- Ionic Native Email Composer integration, New Contact Form with Email Composer
- Ionic 2 Framework update to 2.0.1
- Ionic 2 app-scripts update to 1.1.0
- New Ionic 2 App Tutorial: How to add a Wordpress Menu <id> to the App Sidebar Menu
Ionic 2 App 1.5.0
- Wordpress Menus support (WP API Menus integration)
- Unlimited Menu levels support
- New Wordpress Menus, Wordpress Menu and Wordpress Menu Item Components in the Wordpress Module
- In App navigation from Wordpress Menus to Categories, Posts and Pages 
Ionic 2 App 1.4.0
- Ionic 2 Framework update to 2.0.0
Ionic 2 App 1.3.0
- New Facebook Connect Module
- Facebook Login/Logout
- Access to the Facebook Graph API
- Ionic 2 Framework update to 2.0.0-rc.5
- Ionic 2 app-scripts update to 1.0.0
Ionic 2 App 1.2.0
- Wordpress Login / JWT Authentication for WordPress REST API Version 2.
- New Wordpress Home Component (modern design).
- New Login Module/Component.
Ionic 2 App 1.1.0
- WordPress REST API Version 2 Pages integration
Ionic 2 App 1.0.0
- Initial release


 
####Update (31-07-2016):

Video Tutorial: 

[![Ionic Shopping Cart]()

