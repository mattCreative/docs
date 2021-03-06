- API
    - [Introduction]()
    - [Authentication](authentication)
        - [Client Credentials](#client-credentials)
        - [Refresh Token](#refresh-token)
        - [Authorization Code](#authorization-code)
- Inventory
    - [Products](product)
        - [Get products by criteria](#get-products)
        - [Get product by ID](#get-product-id)
        - [Search products by criteria](#get-products-search)
        - [Create product](#post-product)
        - [Update product](#put-product-id)
        - [Delete product](#delete-product-id)
        - [Get product fields](#get-product-fields)
        - [Get product fields by ID](#get-product-id-fields)
        - [Get product modifiers by ID](#get-product-id-modifiers)
        - [Get product variations by ID](#get-product-id-variations)
    - [Product Modifers](modifier)
        - [Get product modifier by ID](#get-product-id-modifier-id)
        - [Create product modifier](#post-product-id-modifier)
        - [Update product modifier](#put-product-id-modifier-id)
        - [Delete product modifier](#delete-product-id-modifier-id)
        - [Get product modifier fields](#get-product-id-modifier-fields)
        - [Get product modifier fields by ID](#get-product-id-modifier-id-fields)
    - [Product Variations](variation)
        - [Get product variation by ID](#get-product-id-modifier-id-variation-id)
        - [Create product variation](#post-product-id-modifier-id-variation)
        - [Update product variation](#put-product-id-modifier-id-variation-id)
        - [Delete product variation](#delete-product-id-modifier-id-variation-id)
        - [Get product variation fields](#get-product-id-modifier-id-variation-id-fields)
        - [Get product variation fields by ID](#get-product-id-modifier-id-variation-id-fields)
    - [Categories](category)
        - [Get category tree](#get-category-tree)
        - [Get categories by criteria](#get-categories-by-criteria)
        - [Get category by ID](#get-category-by-id)
        - [Create category](#create-category)
        - [Update category](#update-category)
        - [Delete category](#delete-category)
        - [Get category fields](#get-category-fields)
        - [Get category fields by ID](#get-category-fields-by-id)
    - [Brands](brand)
        - [Get brands by criteria](#get-brands)
        - [Get brand by ID](#get-brand-id)
        - [Create brand](#post-brand)
        - [Update brand](#put-brand-id)
        - [Delete brand](#delete-brand-id)
        - [Get brand fields](#get-brand-fields)
        - [Get brand fields by ID](#get-brand-id-fields)
    - [Collections](collection)
        - [Get collections by criteria](#get-collections)
        - [Get colleciton by ID](#get-collection-id)
        - [Create colleciton](#post-collection)
        - [Update colleciton](#put-collection-id)
        - [Delete colleciton](#delete-collection-id)
        - [Get collection fields](#get-collection-fields)
        - [Get collection fields by ID](#get-collection-id-fields)
- Checkout flow
    - [Carts](cart)
        - [Get cart contents](#get-cart-identifier)
        - [Add item to cart](#post-cart-identifier-item)
        - [Add variation to cart](#post-cart-identifier-variation)
        - [Update item in a cart](#put-cart-identifier-item-id)
        - [Get item from cart by identifier](#get-cart-identifier-item-id)
        - [Check if item is in a cart](#get-cart-identifier-has-id)
        - [Delete cart and contents](#delete-cart-identifier)
        - [Delete item from cart](#delete-cart-identifier-item-id)
    - [Checkout](checkout)
        - [Get the available checkout options](#get-cart-identifier-checkout)
        - [Pass a cart to checkout](#post-cart-identifier-checkout)
        - [Process payment for an order](#post-checkout-payment)
    - [Orders](order)
        - [Get multiple orders by criteria](#get-orders)
        - [Get single order by criteria](#get-order)
        - [Get order by ID](#get-order-id)
        - [Create order](#post-order)
        - [Update order](#put-order-id)
        - [Delete order](#delete-order-id)
        - [Get order fields](#get-order-fields)
        - [Get order fields by ID](#get-order-id-fields)
    - [Order Items](order-item)
        - [Get order items by criteria](#get-order-items)
        - [Create order item](#post-order-item)
        - [Update order item](#put-order-item-id)
        - [Delete order item](#delete-order-item-id)
- Customers
    - [Customers](customer)
        - [Get customers by criteria](#get-customers)
        - [Get customer by ID](#get-customer-id)
        - [Create customer](#post-customer)
        - [Update customer](#put-customer-id)
        - [Delete customer](#delete-customer-id)
        - [Get customer fields](#get-customer-fields)
        - [Get customer fields by ID](#get-customer-id-fields)
    - [Customer Groups](customer-group)
        - [Get customer group by ID](#get-customer-group-id)
        - [Create customer group](#post-customer-group)
        - [Update customer group](#put-customer-group-id)
        - [Delete customer group](#delete-customer-group-id)
        - [Get customer group fields](#get-customer-group-fields)
        - [Get customer group fields by ID](#get-customer-group-id-fields)
    - [Addresses](address)
        - [Get addresses by criteria](#get-addresses)
        - [Get address by ID](#get-address-id)
        - [Create address](#post-address)
        - [Update address](#put-address-id)
        - [Delete address](#delete-address-id)
        - [Get address fields](#get-address-fields)
        - [Get address fields by ID](#get-address-id-fields)
- Store Setup
    - [Gateways](gateway)
        - [Get gateways](#get-gateways)
        - [Get gateway by slug](#get-gateway-slug)
        - [Get enabled gateways](#get-enabled-gateways)
        - [Get disabled gateways](#get-disabled-gateways)
        - [Update gateway](#put-gateway-slug)
        - [Enable gateway](#enable-gateway-slug)
        - [Disable gateway](#disable-gateway-slug)
        - [Get gateway fields by slug](#get-gateway-slug-fields)
    - [Taxes](tax)
        - [Get tax bands](#get-taxes)
        - [Get tax band by ID](#get-tax-id)
        - [Create tax band](#post-tax)
        - [Update tax band](#put-tax-id)
        - [Delete tax band](#delete-tax-id)
        - [Get tax band fields](#get-tax-fields)
        - [Get tax band fields by ID](#get-tax-id-fields)
    - [Shipping Methods](shipping)
        - [Get shipping by criteria](#get-shipping)
        - [Get shipping by ID](#get-shipping-id)
        - [Create shipping](#post-shipping)
        - [Update shipping](#put-shipping-id)
        - [Delete shipping](#delete-shipping-id)
- International
    - [Currencies](currency)
        - [Set currency](#set-currency)
        - [Get currencies by criteria](#get-currencies)
        - [Get currency by ID](#get-currency-id)
        - [Create currency](#post-currency)
        - [Update currency](#put-currency-id)
        - [Delete currency](#delete-currency-id)
    - [Languages](language)
        - [Get languages by criteria](#get-languages)
        - [Get language by ID](#get-language-slug)
        - [Create language](#post-language)
        - [Update language](#put-language-slug)
        - [Delete language](#delete-language-slug)
        - [Set language](#set-language)
        - [Get language fields](#get-language-fields)
        - [Get language fields by slug](#get-language-slug-fields)
- Custom Data
    - [Flows](flow)
        - [Get flows](#get-flows)
        - [Get flow by slug](#get-flow-slug)
        - [Create flow](#post-flow)
        - [Update flow](#put-flow-slug)
        - [Delete flow](#delete-flow-slug)
	- [Flow Entries](entry)
        - [Get flow entries](#get-flow-slug-entries)
        - [Get flow entry by ID](#get-flow-slug-entry-id)
        - [Create flow entry](#post-flow-slug-entry)
        - [Update flow entry](#put-flow-slug-entry-id)
        - [Delete flow entry](#delete-flow-slug-entry-id)
    - [Flow Fields](field)
        - [Get flow fields](#get-flow-slug-fields)
        - [Get flow field by ID](#get-flow-slug-field-slug)
        - [Create flow field](#post-flow-slug-field)
        - [Update flow field](#put-flow-slug-field-slug)
        - [Delete flow field](#delete-flow-slug-field-slug)
    - [Flow Field Types](field-type)
        - [Get flow fieldtypes](#get-flows-type-slug)
        - [Get flow fieldtype by slug](#get-flows-types)
- Misc
    - [Files](files)
        - [Get file by ID](#get-file-id)
        - [Upload file](#post-file)
        - [Delete file](#delete-file-id)
    - [Email Templates](email-templates)
        - [Get email templates](#get-emails)
        - [Get email template by slug](#get-email-slug)
        - [Create email template](#post-email)
        - [Update email template](#put-email-slug)
        - [Delete email template](#delete-email-slug)
        - [Get email template fields](#get-email-fields)
        - [Get email template by slug](#get-email-slug-fields)
    - [Webhooks](webhooks)
        - [Get webhooks by criteria](#get-webhooks)
        - [Get webhook by ID](#get-webhook-id)
        - [Create webhook](#post-webhook)
        - [Update webhook](#put-webhook-id)
        - [Delete webhook](#delete-webhook-id)
        - [Get webhook fields](#get-webhook-fields)
        - [Get webhook fields by id](#get-webhook-id-fields)