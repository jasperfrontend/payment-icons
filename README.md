# payment-icons
Payment Provider Icons with almost kinda font-awesome-style markup. Demo: [https://jaspervandermeer.com/payment-icons/](https://jaspervandermeer.com/payment-icons/)

![Demo](https://i.imgur.com/ClSrvQS.png)

| TODO |
| --- |
| ~Make it responsive~ |
| ~Make icons stack or display inline(-block)~ |
| Optimize the SVG |
| Add multiple icon sizes with an extra css class |

## Description
This provides an easy way to include payment provider icons in your website or app. It's always a hassle to get a list of supported payment providers so we usually resort to Google Images to steal somebody else's work - And I know you did that, just like I did.

Since [stealing is wrong](https://www.youtube.com/watch?v=HmZm8vNHBSU), I decided to stop stealing icons from Google Images and instead steal utilize somebody's creative work from Behance which in turn consists of artwork stolen from companies providing payment services with expensive lawyers and all that. So please, read the disclaimer below. It's all for a good cause: Getting more people to use your payment services.

## Installation

### **Easy mode:** Composer:
Install through composer:
`composer require tweemeterstudio/payment-icons`

Check if this line exists in your composer.json file:

```
{
    "require": {
        "tweemeterstudio/payment-icons": "0.*"
    }
}
```
### **Also quite easy mode:** Manual download:
Download the [zip of this repo](https://github.com/tweemeterstudio/payment-icons/archive/master.zip), extract its folder to your project.
---
## Integration in your project
Include the following line in the `<head>` of your document:
```
<link href="/path/to/payment-icons/payment-icons.min.css">
```
You need to mind the `/path/to/` part when including the `payment-icons.min.css` file. The css file and `/assets` folder should reside in the **same directory!**

## Usage
To use the payment icons you can simply include
```
<ins class="pi-payment-icons">
    <i class="pi pi-paypal"></i>
    <i class="pi pi-mastercard"></i>
    <i class="pi pi-ideal"></i>
</ins>
```
to your page, where the classes of the `<i>` as children of the `<ins>` decide which payment provider icons are shown. The full list of available payment providers are mentioned below.
## List of available payment providers and its corresponding CSS class
| Payment Provider  | CSS Class |
|---|---|
| PayPal            | `paypal` |
| Apple Pay         | `apple-pay` |
| Google Pay        | `google-pay` |
| Alipay            | `alipay` |
| Mastercard        | `mastercard` |
| Visa              | `visa` |
| American Express  | `american-express` |
| Diner's Club      | `diners-club` |
| Maestro           | `maestro` |
| VPay              | `vpay` |
| Girocard          | `girocard` |
| Klarna            | `klarna` |
| Giropay           | `giropay` |
| iDeal             | `ideal` |
| Przelewy24        | `przelewy24` |
| Bitcoin           | `bitcoin` |
| Etherereum        | `ethereum` |
| Ripple            | `ripple` |

## Disclaimer
All logos, designs, brands and names are © to their respective owners.
Original icon design by [Spektrum 44](https://www.behance.net/gallery/93190297/Free-E-Commerce-Logos) on [Behance](https://www.behance.net/spektrum44).

Thank you 💙
