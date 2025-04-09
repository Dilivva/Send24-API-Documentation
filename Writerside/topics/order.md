# Order Creation Flow

1.  When a customer places an order with Send24 as the selected shipping method, the plugin will:
    -   Automatically calculate the shipping cost based on the customer's address and selected delivery option.
    -   Create an order in Send24 using the configured API key.
2.  The Send24 order details, including tracking information, will be added to the WooCommerce order notes.