# first_data_analysis_project
Hello, everyone!
This is a first project that I completed in DA courses without any mentors support.
Here is the task:

" You are a data analyst about to join a startup that is creating a new marketplace. The startup has recently entered the market and specializes in selling new products from Brazil that are just beginning to appear in stores.

Product manager is concerned about his product because the marketplace's revenue has been stagnant for several months. He has given you complete freedom to act. The main goals are to grow key metrics while ensuring no inconvenience to customers, as PM cares deeply about their experience.

After some thought, you’ve outlined the following tasks:

    Task 1: Assess monthly retention in order completion using cohort analysis.
    Task 2: Determine whether this marketplace has achieved product/market fit.
    Task 3: Identify the 5 key metrics the product team should focus on to maximize company profit.
    Task 4: Select one of the 3 main hypotheses using the ICE framework.
    Task 5: Define the key metrics that your hypothesis should impact.
    Task 6: Summarize conclusions from the work done.

Datasets:

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
    canceled — Canceled "
