# Car Wash

## Overview

Car Wash feature is used to buy a Car Wash by different methods, at the POS, at the dispenser or at the car wash controller (if the site has the option available). When a customer purchases a car wash the system that is used for the purchase is forced to print a receipt because it prints the Car Wash code on the receipt. Car Wash code is entered at the Car Wash Controller when the customer decides to redeem the code for the Car Wash.

When Car Wash is integrated with Verifone Commander™ Verifone Commander the following is some information on how this works:

* Car Wash “items” must be sold as PLUs.
* Car Wash items can be sold at POS or at dispenser where consumer is led through the required steps for purchase.
* Car Wash code (for redeeming the car wash) prints on the receipt and so ticket printing is forced.
* The PLU Promotions feature may be used to automatically discount Car Wash when the configured requirements for fuel purchased in the same transaction are met.

## Using Car Wash

Transactions with Car Wash purchases print the Car Wash code on the receipt and so will always force a ticket print.

Car Wash sales may be configured to offer a promotional price based on characteristics of the transaction. :::note This is an example of an automated discount and requires no special handling by the cashier. :::

A Car Wash sale is a PLU sale and can be sold at the POS by the following methods:

* The PLU number
* A PLU soft key set up with a Car Wash PLU
* A menu key set up with Car Wash PLUs

:::note A Car wash cannot be sold as a department sale. Car wash items can also be sold through a dispenser card reader. :::

### Car Wash Sale at the Dispenser

Prompts for the customer to purchase one (or not) and to select a type appear before or after the customer begins fueling, depending on the POS settings. The following exceptions may occur:
