# Cash/Credit Pricing

## Overview

Cash/Credit Pricing is used to allow a site to sell fuel at different fuel price levels based on whether the sale is paid by Cash or Credit (e.g. sites will often set the credit fuel price higher than the cash fuel price to offset the credit transactions fees for the site).

If the site is using different fuel prices for cash and credit, they must disable (or uncheck) the Ignore MOP Conflict setting in Fuel Configuration > Site Params.

The price level for each card type can be configured in the Payment Controller > EPS Configuration > FEPCard - Cash Credit Pricing by Card Type configuration screen.

If no configuration is done for the price level by card type, debit and prepaid cards default to cash fuel price level and all other card types default to credit fuel price level.

## Using Cash/Credit Pricing

### Prepay Transactions

Amount Prepay: If the transaction is tendered by cash, the customer dispenses fuel at the cash fuel price level at the pump. If the transaction is paid by credit, the customer dispenses fuel at the fuel price level configured for the card type (e.g. debit cards can either be configured at cash or credit price level).

Volume Prepay: For volume prepays, the cashier must select a fuel grade and a fuel price level when they ring up the fuel prepay. If the transaction is tendered by cash, the MOP entered must match the fuel price level selected by the cashier. If the transaction is paid by credit, the price level configured for the card type must match the fuel price level selected by the cashier. If there is a price level conflict, then an error message appears indicating "MOP Conflict".

### Postpay Transactions

When the Ignore MOP Conflict parameter is enabled (or checked), sales can be tendered using any MOP regardless of the original fuel price level of the sale.

When this parameter is not enabled (or not checked) and if the transaction is tendered by cash, the MOP entered must match the fuel price level. If the transaction is paid by credit, the price level configured for the card type must match the fuel price level. If there is a price level conflict then an error message appears indicating "MOP Conflict".

### DCR Transactions

Transactions initiated at the dispenser card reader are authorized at the fuel price level that has been configured for the card type that is used.

### Configuring Cash/Credit Pricing

If the site is using different fuel prices for cash and credit, disable (or uncheck) the Ignore MOP Conflict setting in Forecourt > Fuel > Site Parameters.

Configure cash and credit price amount for each fuel product service levels in Forecourt > Fuel Prices form.
