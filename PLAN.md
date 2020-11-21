# GOAL: Get Google Universal Tracking Working With LinkedIn

## Create New Site
- Create new Oselot.com Site: https://github.com/tolicodes/oselot.com/tree/master
- Used `create-react-app`

## Create Landing Page
Text: Thank you for applying!

Put Header code in `index.html`
    ```
    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-PSWHTND');</script>
    <!-- End Google Tag Manager -->

Put Footer code in `index.html`
    ```
    <!-- Google Tag Manager (noscript) -->
    <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PSWHTND"
    height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
    <!-- End Google Tag Manager (noscript) -->
    ```