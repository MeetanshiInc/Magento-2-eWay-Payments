# **Magento 2 eWay Payments Extension**

The **Magento 2 eWay Payments** extension allows merchants to seamlessly integrate eWay payment solutions into their Magento store, offering customers a secure and efficient payment experience. By accepting various payment methods including credit and debit cards, eWay ensures smooth, hassle-free transactions, making it a reliable choice for online merchants looking to enhance their payment system.

## **How It Works**

The **Magento 2 eWay Payments extension** integrates directly with the eWay payment gateway. Once installed and configured, customers can select eWay as their payment method during checkout. The extension facilitates secure credit card payments, supports multiple currencies and provides a seamless user experience, making the payment process quick and secure.

## **Key Features**

* Choose between Direct Connection or Responsive Shared Page methods for processing transactions.  
* Customize the payment method label to fit your store's branding.  
* Capture authorized payments seamlessly.

## **Secure Transactions**

The Magento 2 eWay Payments extension ensures secure transaction processing through eWay’s encrypted payment gateway, providing peace of mind for both merchants and customers. Payment details are transmitted securely, with 3D Secure authentication added for enhanced security.

## **Multiple Payment Options**

This extension offers flexibility by supporting a variety of payment methods through eWay, including credit and debit cards (Visa, MasterCard, American Express) and PayPal, allowing customers to select their preferred payment option during checkout.

## **Seamless Integration with Magento**

The extension seamlessly integrates with your Magento 2 store, allowing merchants to manage payment settings directly from the admin panel with easy-to-use configuration options, requiring no technical expertise for setup.

## **Real-Time Transaction Monitoring**

Merchants can monitor transactions in real-time through the Magento admin panel, gaining detailed insights into sales, payment status, errors and easily tracking payment disputes and refunds.

## **Fraud Prevention**

eWay’s built-in fraud detection tools perform real-time checks during payment processing, helping prevent fraudulent transactions, reduce chargebacks and protect your store from malicious activities through seamless integration with eWay’s fraud detection systems.

## **Extension Installation**

To install the **Magento 2 eWay Payments** extension, follow these steps:

### **Step 1:**

Extract the zip folder and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure Magento 2 eWay Payments Extension**

To configure the extension, log in to your Magento 2 admin panel, navigate to **Sales \> Payment Methods**, and adjust the settings to enable the extension.

### **Step 1: Configure Settings**

![configuration](https://github.com/user-attachments/assets/ebce9682-27a8-46d7-894a-7f57145d15ee)

* **Enabled**: Set to "YES" to activate the payment method.  
* **Connection Type**: Choose the connection type from the dropdown—either **Direct Connection** or **Responsive Shared Pages**.  
* **Title**: Enter the title for the payment method to display on the frontend.  
* **Sandbox Mode**: Enable sandbox mode by setting it to "YES" for testing purposes.  
* **Live API Key**: Input the live API key provided during eWay Gateway registration.  
* **Live API Password**: Enter the live API password received during eWay Gateway registration.  
* **Live Client-Side Encryption Key**: Add the live encryption key provided upon registering with eWay Gateway.  
* **Sandbox API Key**: Provide the sandbox API key issued during eWay Gateway registration.  
* **Sandbox API Password**: Enter the sandbox API password obtained during eWay Gateway registration.  
* **Sandbox Client-Side Encryption Key**: Add the sandbox encryption key provided upon eWay Gateway registration.  
* **Payment Action**: Select the desired payment action from the dropdown menu.  
* **Debug**: Enable debugging by setting it to "YES."  
* **Credit Card Types**: Specify the credit card types that will be accepted for payments.  
* **Payment from Applicable Countries**: Choose the countries where this payment method will be available.  
* **Sort Order**: Define the sort order for how the payment method appears in the list.

### **Step 2: Check eWay Payments on the Frontend**

After successfully configuring the extension, the eWay payment method will be available and visible on the frontend.

* **eWay Payment Method Using Direct Connection**

![eWay Payment Method Using Direct Connection](https://github.com/user-attachments/assets/12af6578-230a-44e1-bb51-9ee46f17be93)

The Direct Connection method requires customers to enter their credit card details to complete the payment. To finalize the transaction and successfully place the order, click the **"Place Order"** button.

* **eWay Payment Method Using Responsive Shared Page Connection**

![eWay Payment Method Using Responsive Shared Page Connection](https://github.com/user-attachments/assets/c936292f-397d-4633-9bf2-1fe3d1c88998)

With the Responsive Shared Page method, customers are redirected to a payment form hosted by eWay to complete the transaction. Fill out the form and click the **"Pay Now"** button to finalize the payment.

* **eWay Payment Method in the My Account Section**

![eWay Payment Method in the My Account Section](https://github.com/user-attachments/assets/1e91a5c2-3ecb-47da-bc7a-8b7a4ade6a72)

The customized payment method name, as configured in the backend, is displayed under the **"My Orders"** tab within the Account Dashboard. An example of this for the eWay payment method is shown below.

### **Step 3: Check eWay Payments in the Backend**

After an order is placed on the frontend using the eWay payment method, the transaction details can be viewed in the backend under the order details section.

* **eWay Payment Method Details in Order View**

![eWay Payment Method Details in Order View](https://github.com/user-attachments/assets/d26da14b-dcea-4412-963b-f7f2310520f8)

The Order View section in the backend provides payment details, including the payment method name (eWay), transaction ID, response code, and approval message.

## Download the [Magento 2 eWay Payments Extension](https://meetanshi.com/magento-2-eway-payments.html) Now\!
