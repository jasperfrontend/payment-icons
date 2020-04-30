# payment-icons
Payment Provider Icons with font-awesome-style markup. Demo: [https://jaspervandermeer.com/payment-icons/](https://jaspervandermeer.com/payment-icons/)
| TODO |
| --- |
| ~Make it responsive~ |
| Make icons stack or display inline(-block) |
| Optimize the SVG |
| Add multiple icon sizes with an extra css class |

## Description
This provides an easy way to include payment provider icons in your website or app. It's always a hassle to get a list of supported payment providers so we usually resort to Google Images to steal somebody else's work - And I know you did that, just like I did.

Since stealing isn't good I decided to stop stealing icons from Google Images and instead steal somebody's creative work from Behance which in turn consists of artwork stolen from companies providing payment services with expensive lawyers and all that. So please, read the disclaimer below. It's all for a good cause: Getting more people to use your payment services.
## Installation
I think the usage will be something like
1. **Easy mode:** Install through Composer: `composer require tweemeterstudio/payment-icons`
```
{
    "require": {
        "tweemeterstudio/payment-icons": "1.0.*"
    }
}
```
2. **Also quite easy mode:** Download the [zip of this repo](https://github.com/tweemeterstudio/payment-icons/archive/0.1.zip), extract its folder to your project and include the following line in the `<head>` of your document:
```
<link href="/path/to/payment-icons/payment-icons.min.css">
```
You need to of course mind the path/to/ part when including the payment-icons.min.css file. The css file and `/assets` folder should reside in the same directory!
## Usage
To use the payment icons you can simply include
```
<ins class="pi-payment-icons">
    <i class="pi pi-paypal"></i>
    <i class="pi pi-mastercard"></i>
    <i class="pi pi-ideal"></i>
</ins>
```
to your page, where the classes of the `<i>` within the `<ins>` decide which payment provider icons are shown. The full list of available payment providers are mentioned below.
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
