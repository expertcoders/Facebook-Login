Facebook-Login
==============

Facebook Login Installation

Change your APP ID
````javascript

<script>
window.fbAsyncInit = function () {
  FB.init({
    appId: 'APP ID',
    status: true,
    cookie: true,
    xfbml: true
  });
};


````
