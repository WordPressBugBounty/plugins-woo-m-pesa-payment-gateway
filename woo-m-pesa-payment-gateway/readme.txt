=== M-Pesa(Kenya) Checkout for Woocommerce ===Contributors: demkitechPlugin Name: M-Pesa(Kenya) Checkout for WooCommerceTags: mobile, money, m-pesa, mpesa, woocommerceAuthor: Demkitech SolutionsRequires at least: 2.2Tested up to: 6.9Stable tag: 1.0License: GNU General Public License v2.0License URI: http://www.gnu.org/licenses/gpl-2.0.htmlDonate link: #== Description ==The plugin enables the customer to have an option of paying for goods using M-PESA mobile money service from a Wordpress site that has WooCommerce plugin installed. The plugin adds an option on the checkout section for paying through M-PESA(A mobile payment platform). In order to use the plugin, one must get a Paybill or Till number, which is a unique number that will act as an account where the payments from the customer will be channeled. After this, one must create an account on the Safaricom’s Daraja Portal and link this Paybill or Till number to the account created on the portal. The portal will enable you to get the following:-	Passkey-	Consumer Key-	Consumer Secret-	Enpoints for Sandbox/Production for authentication and payment request.These details should be filled after activating the plugin and will be stored in your website.The above setup is to ensure that it is the site owner who has full control over the payment details of the Paybill or Till number.When the customer clicks on the Pay button on the payment page, the plugin will initiate a payment authentication request to the customer. The customer will then accept or decline the payment from the personal mobile phone and the callback will be sent from the portal with details of the customer’s action. This is what is then used to determine if to change the status of the order or not.This free version plugin does process callbacks and also Till number payments are not enabled, to get these  features you need to purchase the Pro version here: [GET PRO VERSION](https://woompesa.demkitech.com/)== Our Customers ==

These are some of our customers using the Pro Version of the plugin:<div style="display:flex; gap:20px; flex-wrap:wrap; align-items:center;">

  <div style="text-align:center;">
    <a href="https://mkurugenzi.ke/" target="_blank" rel="noopener">
      <img src="https://demowoompesa.demkitech.com/wp-content/uploads/2026/03/mk3.png" alt="MkurugenziKe" width="120" height="55" />MkurugenziKe
    </a>
  </div>

  <div style="text-align:center;">
    <a href="https://kikao64.ke/" target="_blank" rel="noopener">
      <img src="https://demowoompesa.demkitech.com/wp-content/uploads/2026/03/kikao.png" alt="Kikao" width="120" height="55" />
    Kikao</a>
  </div>
  
   <div style="text-align:center;">
    <a href="https://westside-stationers.com" target="_blank" rel="noopener">
      <img src="https://demowoompesa.demkitech.com/wp-content/uploads/2026/03/westside.webp" alt="Westside" width="120" height="55" />
    Westside Stationers</a>
  </div>
  
   <div style="text-align:center;">
    <a href="https://yattabeekeepers.co.ke" target="_blank" rel="noopener">
      <img src="https://demowoompesa.demkitech.com/wp-content/uploads/2026/03/yatta.png" alt="Yatta" width="120" height="55" />
    Yatta Beekeepers</a>
  </div>
  
   <div style="text-align:center;">
    <a href="https://grounded.co.ke" target="_blank" rel="noopener">
      <img src="https://demowoompesa.demkitech.com/wp-content/uploads/2026/03/grounded.png" alt="Grounded" width="120" height="55" />
    Grounded</a>
    <br />
  </div>

</div>#### Plugin features: ####* Compatible with Wordpress themes.* Easy to use.* Lightweight.* Supports all modern browsers.#### How to use: ####1.	Make sure you have installed and activated WooCommerce plugin before installing and activating this plugin.2.	Upload Woocommerce M-PESA Payment Gateway plugin files to the wordpress plugins directory (/wp-content/plugins/), or install the plugin from the Wordpress admin plugin screen.3.	Activate the plugin.4.	On the Wordpress admin, navigate to WooCommerce > Settings > M-PESA > Manage and fill in the fields provided in order for the plugin to work.== Disclaimer ==This plugin does not have any relation with WooCommerce or M-PESA. The plugin’s purpose is just to help in linking the WooCommerce plugin with the M-PESA payment method. THE PLUGIN SHOULD AT NO POINT BE HELD RESPONSIBLE IF THE DARAJA ENDPOINT IS UNREACHABLE OR UNABLE TO SERVE REQUESTS.In the plugin description there is links to other websites which are not under the control of WooCommerce M-PESA Payment Gateway Plugin. We have no control over the nature,content and availability of those sites. The inclusion of any links does not necessarily imply a recommendation or endorse the views expressed within them.#### Demo ####The demo site for the plugin is [here.](https://demowoompesa.demkitech.com/)Below is the demo for the plugin:https://youtu.be/JeH-VJu8x7Y== Installation ==1. Unzip files.2. Upload the folder into your plugins directory.3. Activate the plugin.4. Update the settings.== Upgrade Notice ==This is the first version.== Screenshots ==1. Payment Gateways List2. Settings page 13. Settings page 24. Request accepted5. Transaction in progress6. Customer action response== Changelog === 1.0 === Frequently Asked Questions ==How does the customer authenticate the payment?The customer receives a Sim Application Toolkit push to authenticate the payment and this is secure since it is the customer doing this.