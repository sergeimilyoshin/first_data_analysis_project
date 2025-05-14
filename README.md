Hello, everyone!
Here is the project for newly established Brazilian marketplace.
There is problem - revenue is stagnating and I need to find reasons why it might happen.
What I've done:

    Completed cohort analysis and calculated retention rate.
    Determined if marketplace has achieved product/market fit.
    Identified the 5 key metrics to focus on to maximize company profit.
    Selected one of the 3 main hypotheses using the ICE framework.
    Defined the key metrics that your hypothesis should impact.
    Summarized conclusions from the work done.

Used datasets descriptions:

    olist_customers_dataset.csv — Table with unique user identifiers

        customer_id — Per-order user identifier
        customer_unique_id — Unique user identifier (similar to a passport number)
        customer_zip_code_prefix — User's postal code
        customer_city — User's delivery city
        customer_state — User's delivery state

    olist_orders_dataset.csv — Orders table

        order_id — Unique order identifier (receipt number)
        customer_id — Per-order user identifier
        order_status — Order status
        order_purchase_timestamp — Order creation timestamp
        order_approved_at — Payment confirmation timestamp
        order_delivered_carrier_date — Handover timestamp to logistics provider
        order_delivered_customer_date — Delivery timestamp
        order_estimated_delivery_date — Promised delivery date

    olist_order_items_dataset.csv — Items included in orders

        order_id — Unique order identifier (receipt number)
        order_item_id — Item identifier within an order
        product_id — Product identifier (similar to a barcode)
        seller_id — Seller identifier
        shipping_limit_date — Seller's maximum delivery date before handing over to logistics partner
        price — Price per unit
        freight_value — Item weight

Unique order statuses in olist_orders_dataset:

    created — Created
    approved — Approved
    invoiced — Invoiced
    processing — Processing (order assembly)
    shipped — Shipped from warehouse
    delivered — Delivered to customer
    unavailable — Canceled due to product unavailability
    canceled — Canceled
