# Deliverect (deliverect)
Deliverect is a global restaurant integration platform that connects delivery marketplaces, online ordering channels, POS systems, and store operations into a single hub serving over 80,000 locations across more than 50 markets. For developers and integration partners, Deliverect exposes a suite of REST APIs documented in its Developer Hub, including the POS, Commerce, Channel, Dispatch, Store, Pay, CRM, Loyalty, KDS, and Gift Cards APIs. The APIs let partners receive and manage orders and catalogues, build online ordering and kiosk channels, manage last-mile dispatch, process payments, manage customers and loyalty, and control stock, hours, and availability. Authentication uses OAuth 2.0 machine-to-machine access tokens with client_id and client_secret credentials issued after an API agreement, scoped by integration type.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/deliverect/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Delivery, Online Ordering, Point of Sale, Order Management, Integration

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### Deliverect POS API
Connect point-of-sale systems to Deliverect to receive and manage orders and catalogues, sync products, manage inventory, and push order status updates across delivery and ordering channels. Uses OAuth 2.0 machine-to-machine access tokens with the genericPOS scope. A generated OpenAPI specification is available.

**Human URL:** [https://developers.deliverect.com/reference/pos_endpoints](https://developers.deliverect.com/reference/pos_endpoints)

#### Tags:

 - Point of Sale, Orders, Menu, Inventory

#### Properties

- [OpenAPI](openapi/deliverect-pos-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/pos_endpoints)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)
- [GettingStarted](https://developers.deliverect.com/reference/get-started)

#### Naftiko Capabilities

- [pos-api-floors](capabilities/pos-api-floors.yaml)
- [pos-api-inventory](capabilities/pos-api-inventory.yaml)
- [pos-api-orders](capabilities/pos-api-orders.yaml)
- [pos-api-products](capabilities/pos-api-products.yaml)
- [pos-api-registration](capabilities/pos-api-registration.yaml)
- [pos-api-tables](capabilities/pos-api-tables.yaml)

### Deliverect Commerce API
Power digital ordering, click-and-collect, and kiosk experiences with store details, menu data, basket creation, validation, discounts, and a checkout flow that injects orders to the POS. Authenticates with OAuth 2.0 machine-to-machine access tokens using the genericCommerce scope.

**Human URL:** [https://developers.deliverect.com/reference/commerce-channel-api](https://developers.deliverect.com/reference/commerce-channel-api)

#### Tags:

 - Online Ordering, Commerce, Baskets, Checkout, Kiosk

#### Properties

- [OpenAPI](openapi/deliverect-commerce-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/commerce-channel-api)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [commerce-api-baskets](capabilities/commerce-api-baskets.yaml)
- [commerce-api-checkout](capabilities/commerce-api-checkout.yaml)
- [commerce-api-coupons](capabilities/commerce-api-coupons.yaml)
- [commerce-api-menus](capabilities/commerce-api-menus.yaml)
- [commerce-api-stores](capabilities/commerce-api-stores.yaml)
- [commerce-api-upsell](capabilities/commerce-api-upsell.yaml)

### Deliverect Channel API
Integrate ordering channels and marketplaces with Deliverect to create and cancel orders, sync menus, snooze products, update store and courier status, and exchange payment events. Authenticates with OAuth 2.0 machine-to-machine access tokens scoped via genericChannel.

**Human URL:** [https://developers.deliverect.com/reference/channel_endpoints](https://developers.deliverect.com/reference/channel_endpoints)

#### Tags:

 - Channels, Orders, Menu, Fulfillment

#### Properties

- [OpenAPI](openapi/deliverect-channel-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/channel_endpoints)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [channel-api-accounts](capabilities/channel-api-accounts.yaml)
- [channel-api-channel-links](capabilities/channel-api-channel-links.yaml)
- [channel-api-couriers](capabilities/channel-api-couriers.yaml)
- [channel-api-menus](capabilities/channel-api-menus.yaml)
- [channel-api-opening-hours](capabilities/channel-api-opening-hours.yaml)
- [channel-api-orders](capabilities/channel-api-orders.yaml)
- [channel-api-payments](capabilities/channel-api-payments.yaml)
- [channel-api-products](capabilities/channel-api-products.yaml)
- [channel-api-registration](capabilities/channel-api-registration.yaml)
- [channel-api-store-status](capabilities/channel-api-store-status.yaml)

### Deliverect Dispatch API
Manage last-mile delivery by validating delivery availability, creating, updating, and cancelling delivery jobs, and exchanging courier and fulfillment events. Authenticates with OAuth 2.0 machine-to-machine access tokens scoped via genericFulfillment.

**Human URL:** [https://developers.deliverect.com/reference/dispatch_endpoints](https://developers.deliverect.com/reference/dispatch_endpoints)

#### Tags:

 - Dispatch, Delivery, Fulfillment, Couriers

#### Properties

- [OpenAPI](openapi/deliverect-dispatch-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/dispatch_endpoints)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [dispatch-api-fulfillment](capabilities/dispatch-api-fulfillment.yaml)
- [dispatch-api-jobs](capabilities/dispatch-api-jobs.yaml)

### Deliverect Store API
Query and update store and product availability, snooze products by PLU or tag, set busy mode, and configure opening and holiday hours across locations and channels. Authenticates with OAuth 2.0 machine-to-machine access tokens scoped via store or genericPOS.

**Human URL:** [https://developers.deliverect.com/reference/store_endpoints](https://developers.deliverect.com/reference/store_endpoints)

#### Tags:

 - Store Management, Availability, Opening Hours, Inventory

#### Properties

- [OpenAPI](openapi/deliverect-store-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/store_endpoints)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [store-api-allergens](capabilities/store-api-allergens.yaml)
- [store-api-locations](capabilities/store-api-locations.yaml)
- [store-api-opening-hours](capabilities/store-api-opening-hours.yaml)
- [store-api-products](capabilities/store-api-products.yaml)
- [store-api-store-status](capabilities/store-api-store-status.yaml)
- [store-api-tables](capabilities/store-api-tables.yaml)

### Deliverect Pay API
Process payment requests, list available payment gateways, retrieve payments, issue refunds, and manage payment profiles for ordering transactions. Authenticates with OAuth 2.0 machine-to-machine access tokens scoped via payments.

**Human URL:** [https://developers.deliverect.com/reference/pay_endpoints](https://developers.deliverect.com/reference/pay_endpoints)

#### Tags:

 - Payments, Gateways, Refunds

#### Properties

- [OpenAPI](openapi/deliverect-pay-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/pay_endpoints)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [pay-api-gateways](capabilities/pay-api-gateways.yaml)
- [pay-api-payments](capabilities/pay-api-payments.yaml)
- [pay-api-profiles](capabilities/pay-api-profiles.yaml)

### Deliverect CRM API
Manage customer profiles, identify customers by email, update delivery addresses, vehicles, and favorites, and retrieve order history and favorite orders for personalized ordering. Authenticates with OAuth 2.0 machine-to-machine access tokens.

**Human URL:** [https://developers.deliverect.com/reference/crm_endpoints](https://developers.deliverect.com/reference/crm_endpoints)

#### Tags:

 - CRM, Customers, Orders

#### Properties

- [OpenAPI](openapi/deliverect-crm-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/crm_endpoints)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [crm-api-customers](capabilities/crm-api-customers.yaml)
- [crm-api-orders](capabilities/crm-api-orders.yaml)

### Deliverect Loyalty API
Integrate loyalty programs by creating and retrieving loyalty customers, reading program configuration, retrieving and validating programs, and validating compensation cards. Authenticates with OAuth 2.0 machine-to-machine access tokens.

**Human URL:** [https://developers.deliverect.com/reference/loyalty-channel](https://developers.deliverect.com/reference/loyalty-channel)

#### Tags:

 - Loyalty, Customers, Programs

#### Properties

- [OpenAPI](openapi/deliverect-loyalty-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/loyalty-channel)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [loyalty-api-authentication](capabilities/loyalty-api-authentication.yaml)
- [loyalty-api-compensation-cards](capabilities/loyalty-api-compensation-cards.yaml)
- [loyalty-api-configuration](capabilities/loyalty-api-configuration.yaml)
- [loyalty-api-customers](capabilities/loyalty-api-customers.yaml)
- [loyalty-api-programs](capabilities/loyalty-api-programs.yaml)

### Deliverect KDS API
Integrate Kitchen Display Systems to register devices, receive order notifications, push order status updates, and sync product updates. Authenticates with OAuth 2.0 machine-to-machine access tokens scoped via genericKDS.

**Human URL:** [https://developers.deliverect.com/reference/kds_endpoints](https://developers.deliverect.com/reference/kds_endpoints)

#### Tags:

 - Kitchen Display System, Orders, Products

#### Properties

- [OpenAPI](openapi/deliverect-kds-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/kds_endpoints)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [kds-api-orders](capabilities/kds-api-orders.yaml)
- [kds-api-products](capabilities/kds-api-products.yaml)
- [kds-api-registration](capabilities/kds-api-registration.yaml)

### Deliverect Gift Cards API
Redeem gift cards, check balances, apply and reverse gift cards, and register gift card provider profiles for ordering channels. Authenticates with OAuth 2.0 machine-to-machine access tokens.

**Human URL:** [https://developers.deliverect.com/reference/giftcards](https://developers.deliverect.com/reference/giftcards)

#### Tags:

 - Gift Cards, Payments, Profiles

#### Properties

- [OpenAPI](openapi/deliverect-gift-cards-api-openapi-original.yml)
- [Documentation](https://developers.deliverect.com/reference/giftcards)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)

#### Naftiko Capabilities

- [gift-cards-api-gift-cards](capabilities/gift-cards-api-gift-cards.yaml)
- [gift-cards-api-profiles](capabilities/gift-cards-api-profiles.yaml)

## Common Properties

- [Website](https://www.deliverect.com)
- [Documentation](https://developers.deliverect.com/)
- [APIReference](https://developers.deliverect.com/reference)
- [Authentication](https://developers.deliverect.com/reference/machine-2-machine-access-token-1)
- [GettingStarted](https://developers.deliverect.com/reference/get-started)
- [Webhooks](https://developers.deliverect.com/reference/partner-webhooks-3)
- [Support](https://developers.deliverect.com/discuss)
- [GitHubOrganization](https://github.com/Deliverect)
- [MCP Server](https://developers.deliverect.com/reference/mcp)
- [n8n Connector](https://github.com/Deliverect/n8n-nodes-deliverect)
- [n8n Nodes (npm)](https://www.npmjs.com/package/n8n-nodes-deliverect)
- [LinkedIn](https://www.linkedin.com/company/deliverecthq)
- [X](https://twitter.com/deliverect_com)
- [LLMsTxt](https://developers.deliverect.com/llms.txt)
- [Spectral](rules/deliverect-spectral-rules.yml)
- [Vocabulary](vocabulary/deliverect-vocabulary.yaml)
- [Plans](plans/deliverect-plans-pricing.yml)
- [RateLimits](rate-limits/deliverect-rate-limits.yml)
- [FinOps](finops/deliverect-finops.yml)
- [JSONLD](json-ld/deliverect-channel-api-context.jsonld)
- [JSONLD](json-ld/deliverect-commerce-api-context.jsonld)
- [JSONLD](json-ld/deliverect-crm-api-context.jsonld)
- [JSONLD](json-ld/deliverect-dispatch-api-context.jsonld)
- [JSONLD](json-ld/deliverect-gift-cards-api-context.jsonld)
- [JSONLD](json-ld/deliverect-kds-api-context.jsonld)
- [JSONLD](json-ld/deliverect-loyalty-api-context.jsonld)
- [JSONLD](json-ld/deliverect-pay-api-context.jsonld)
- [JSONLD](json-ld/deliverect-pos-api-context.jsonld)
- [JSONLD](json-ld/deliverect-store-api-context.jsonld)

## Artifacts

Machine-readable API specifications and derived artifacts organized by format.

### OpenAPI

- [deliverect-channel-api-openapi-original.yml](openapi/deliverect-channel-api-openapi-original.yml)
- [deliverect-commerce-api-openapi-original.yml](openapi/deliverect-commerce-api-openapi-original.yml)
- [deliverect-crm-api-openapi-original.yml](openapi/deliverect-crm-api-openapi-original.yml)
- [deliverect-dispatch-api-openapi-original.yml](openapi/deliverect-dispatch-api-openapi-original.yml)
- [deliverect-gift-cards-api-openapi-original.yml](openapi/deliverect-gift-cards-api-openapi-original.yml)
- [deliverect-kds-api-openapi-original.yml](openapi/deliverect-kds-api-openapi-original.yml)
- [deliverect-loyalty-api-openapi-original.yml](openapi/deliverect-loyalty-api-openapi-original.yml)
- [deliverect-pay-api-openapi-original.yml](openapi/deliverect-pay-api-openapi-original.yml)
- [deliverect-pos-api-openapi-original.yml](openapi/deliverect-pos-api-openapi-original.yml)
- [deliverect-store-api-openapi-original.yml](openapi/deliverect-store-api-openapi-original.yml)

### JSON Schema

- [channel-api-channel-prep-time-schema.json](json-schema/channel-api-channel-prep-time-schema.json)
- [channel-api-channel-snooze-schema.json](json-schema/channel-api-channel-snooze-schema.json)
- [channel-api-post-channelname-courierupdate-channellinkid-schema.json](json-schema/channel-api-post-channelname-courierupdate-channellinkid-schema.json)
- [channel-api-post-channelname-menustatus-id-schema.json](json-schema/channel-api-post-channelname-menustatus-id-schema.json)
- [channel-api-post-channelname-order-channellinkid-schema.json](json-schema/channel-api-post-channelname-order-channellinkid-schema.json)
- [channel-api-post-channelname-updaterating-schema.json](json-schema/channel-api-post-channelname-updaterating-schema.json)
- [channel-api-post-channelname-updatestorestatus-channellinkid-schema.json](json-schema/channel-api-post-channelname-updatestorestatus-channellinkid-schema.json)
- [commerce-api-commerce-channel-api-baskets-create-basket-schema.json](json-schema/commerce-api-commerce-channel-api-baskets-create-basket-schema.json)
- [commerce-api-commerce-channel-api-baskets-update-basket-customer-schema.json](json-schema/commerce-api-commerce-channel-api-baskets-update-basket-customer-schema.json)
- [commerce-api-commerce-channel-api-baskets-update-basket-discounts-schema.json](json-schema/commerce-api-commerce-channel-api-baskets-update-basket-discounts-schema.json)
- [commerce-api-get-upsell-items-schema.json](json-schema/commerce-api-get-upsell-items-schema.json)
- [commerce-api-patch-commerce-accountid-baskets-basketid-store-schema.json](json-schema/commerce-api-patch-commerce-accountid-baskets-basketid-store-schema.json)
- [commerce-api-post-commerce-account-id-checkouts-1-schema.json](json-schema/commerce-api-post-commerce-account-id-checkouts-1-schema.json)
- [commerce-api-post-commerce-accountid-baskets-recreate-schema.json](json-schema/commerce-api-post-commerce-accountid-baskets-recreate-schema.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-deliveryaddresses-schema.json](json-schema/crm-api-patch-crm-accountid-customers-crmprofileid-deliveryaddresses-schema.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-favorites-schema.json](json-schema/crm-api-patch-crm-accountid-customers-crmprofileid-favorites-schema.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-schema.json](json-schema/crm-api-patch-crm-accountid-customers-crmprofileid-schema.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-vehicles-schema.json](json-schema/crm-api-patch-crm-accountid-customers-crmprofileid-vehicles-schema.json)
- [crm-api-post-crm-accountid-customers-lookup-schema.json](json-schema/crm-api-post-crm-accountid-customers-lookup-schema.json)
- [crm-api-post-crm-accountid-customers-schema.json](json-schema/crm-api-post-crm-accountid-customers-schema.json)
- [dispatch-api-dispatch-cancel-job-schema.json](json-schema/dispatch-api-dispatch-cancel-job-schema.json)
- [dispatch-api-dispatch-create-job-schema.json](json-schema/dispatch-api-dispatch-create-job-schema.json)
- [dispatch-api-dispatch-updatejob-schema.json](json-schema/dispatch-api-dispatch-updatejob-schema.json)
- [dispatch-api-post-fulfillment-validate-schema.json](json-schema/dispatch-api-post-fulfillment-validate-schema.json)
- [gift-cards-api-giftcards-registerprofile-schema.json](json-schema/gift-cards-api-giftcards-registerprofile-schema.json)
- [gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-applygiftcard-schema.json](json-schema/gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-applygiftcard-schema.json)
- [gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-getgiftcardbalance-schema.json](json-schema/gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-getgiftcardbalance-schema.json)
- [kds-api-kds-order-notification-schema.json](json-schema/kds-api-kds-order-notification-schema.json)
- [kds-api-post-post-kds-orderstatus-orderid-schema.json](json-schema/kds-api-post-post-kds-orderstatus-orderid-schema.json)
- [loyalty-api-loyalty-channel-create-loyalty-customer-schema.json](json-schema/loyalty-api-loyalty-channel-create-loyalty-customer-schema.json)
- [loyalty-api-loyalty-channel-get-programs-schema.json](json-schema/loyalty-api-loyalty-channel-get-programs-schema.json)
- [loyalty-api-loyalty-token-schema.json](json-schema/loyalty-api-loyalty-token-schema.json)
- [pay-api-pay-endpoints-refund-payment-schema.json](json-schema/pay-api-pay-endpoints-refund-payment-schema.json)
- [pay-api-pay-endpoints-request-payment-schema.json](json-schema/pay-api-pay-endpoints-request-payment-schema.json)
- [pay-api-payplatform-payments-profile-register-schema.json](json-schema/pay-api-payplatform-payments-profile-register-schema.json)
- [pay-api-payplatform-payments-refund-schema.json](json-schema/pay-api-payplatform-payments-refund-schema.json)
- [pay-api-payplatform-payments-request-schema.json](json-schema/pay-api-payplatform-payments-request-schema.json)
- [pay-api-payplatform-payments-unregister-profile-schema.json](json-schema/pay-api-payplatform-payments-unregister-profile-schema.json)
- [pos-api-insert-update-products-and-categories-schema.json](json-schema/pos-api-insert-update-products-and-categories-schema.json)
- [pos-api-inventory-update-schema.json](json-schema/pos-api-inventory-update-schema.json)
- [pos-api-pos-api-product-sync-callback-schema.json](json-schema/pos-api-pos-api-product-sync-callback-schema.json)
- [pos-api-pos-register-schema.json](json-schema/pos-api-pos-register-schema.json)
- [pos-api-post-orderstatus-orderid-schema.json](json-schema/pos-api-post-orderstatus-orderid-schema.json)
- [pos-api-post-updatepreparationtime-schema.json](json-schema/pos-api-post-updatepreparationtime-schema.json)
- [store-api-post-mark-products-out-of-stock-by-tag-schema.json](json-schema/store-api-post-mark-products-out-of-stock-by-tag-schema.json)
- [store-api-post-post-locations-openinghours-schema.json](json-schema/store-api-post-post-locations-openinghours-schema.json)
- [store-api-post-update-store-status-schema.json](json-schema/store-api-post-update-store-status-schema.json)

### JSON Structure

- [channel-api-channel-prep-time-structure.json](json-structure/channel-api-channel-prep-time-structure.json)
- [channel-api-channel-snooze-structure.json](json-structure/channel-api-channel-snooze-structure.json)
- [channel-api-post-channelname-courierupdate-channellinkid-structure.json](json-structure/channel-api-post-channelname-courierupdate-channellinkid-structure.json)
- [channel-api-post-channelname-menustatus-id-structure.json](json-structure/channel-api-post-channelname-menustatus-id-structure.json)
- [channel-api-post-channelname-order-channellinkid-structure.json](json-structure/channel-api-post-channelname-order-channellinkid-structure.json)
- [channel-api-post-channelname-updaterating-structure.json](json-structure/channel-api-post-channelname-updaterating-structure.json)
- [channel-api-post-channelname-updatestorestatus-channellinkid-structure.json](json-structure/channel-api-post-channelname-updatestorestatus-channellinkid-structure.json)
- [commerce-api-commerce-channel-api-baskets-create-basket-structure.json](json-structure/commerce-api-commerce-channel-api-baskets-create-basket-structure.json)
- [commerce-api-commerce-channel-api-baskets-update-basket-customer-structure.json](json-structure/commerce-api-commerce-channel-api-baskets-update-basket-customer-structure.json)
- [commerce-api-commerce-channel-api-baskets-update-basket-discounts-structure.json](json-structure/commerce-api-commerce-channel-api-baskets-update-basket-discounts-structure.json)
- [commerce-api-get-upsell-items-structure.json](json-structure/commerce-api-get-upsell-items-structure.json)
- [commerce-api-patch-commerce-accountid-baskets-basketid-store-structure.json](json-structure/commerce-api-patch-commerce-accountid-baskets-basketid-store-structure.json)
- [commerce-api-post-commerce-account-id-checkouts-1-structure.json](json-structure/commerce-api-post-commerce-account-id-checkouts-1-structure.json)
- [commerce-api-post-commerce-accountid-baskets-recreate-structure.json](json-structure/commerce-api-post-commerce-accountid-baskets-recreate-structure.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-deliveryaddresses-structure.json](json-structure/crm-api-patch-crm-accountid-customers-crmprofileid-deliveryaddresses-structure.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-favorites-structure.json](json-structure/crm-api-patch-crm-accountid-customers-crmprofileid-favorites-structure.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-structure.json](json-structure/crm-api-patch-crm-accountid-customers-crmprofileid-structure.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-vehicles-structure.json](json-structure/crm-api-patch-crm-accountid-customers-crmprofileid-vehicles-structure.json)
- [crm-api-post-crm-accountid-customers-lookup-structure.json](json-structure/crm-api-post-crm-accountid-customers-lookup-structure.json)
- [crm-api-post-crm-accountid-customers-structure.json](json-structure/crm-api-post-crm-accountid-customers-structure.json)
- [dispatch-api-dispatch-cancel-job-structure.json](json-structure/dispatch-api-dispatch-cancel-job-structure.json)
- [dispatch-api-dispatch-create-job-structure.json](json-structure/dispatch-api-dispatch-create-job-structure.json)
- [dispatch-api-dispatch-updatejob-structure.json](json-structure/dispatch-api-dispatch-updatejob-structure.json)
- [dispatch-api-post-fulfillment-validate-structure.json](json-structure/dispatch-api-post-fulfillment-validate-structure.json)
- [gift-cards-api-giftcards-registerprofile-structure.json](json-structure/gift-cards-api-giftcards-registerprofile-structure.json)
- [gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-applygiftcard-structure.json](json-structure/gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-applygiftcard-structure.json)
- [gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-getgiftcardbalance-structure.json](json-structure/gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-getgiftcardbalance-structure.json)
- [kds-api-kds-order-notification-structure.json](json-structure/kds-api-kds-order-notification-structure.json)
- [kds-api-post-post-kds-orderstatus-orderid-structure.json](json-structure/kds-api-post-post-kds-orderstatus-orderid-structure.json)
- [loyalty-api-loyalty-channel-create-loyalty-customer-structure.json](json-structure/loyalty-api-loyalty-channel-create-loyalty-customer-structure.json)
- [loyalty-api-loyalty-channel-get-programs-structure.json](json-structure/loyalty-api-loyalty-channel-get-programs-structure.json)
- [loyalty-api-loyalty-token-structure.json](json-structure/loyalty-api-loyalty-token-structure.json)
- [pay-api-pay-endpoints-refund-payment-structure.json](json-structure/pay-api-pay-endpoints-refund-payment-structure.json)
- [pay-api-pay-endpoints-request-payment-structure.json](json-structure/pay-api-pay-endpoints-request-payment-structure.json)
- [pay-api-payplatform-payments-profile-register-structure.json](json-structure/pay-api-payplatform-payments-profile-register-structure.json)
- [pay-api-payplatform-payments-refund-structure.json](json-structure/pay-api-payplatform-payments-refund-structure.json)
- [pay-api-payplatform-payments-request-structure.json](json-structure/pay-api-payplatform-payments-request-structure.json)
- [pay-api-payplatform-payments-unregister-profile-structure.json](json-structure/pay-api-payplatform-payments-unregister-profile-structure.json)
- [pos-api-insert-update-products-and-categories-structure.json](json-structure/pos-api-insert-update-products-and-categories-structure.json)
- [pos-api-inventory-update-structure.json](json-structure/pos-api-inventory-update-structure.json)
- [pos-api-pos-api-product-sync-callback-structure.json](json-structure/pos-api-pos-api-product-sync-callback-structure.json)
- [pos-api-pos-register-structure.json](json-structure/pos-api-pos-register-structure.json)
- [pos-api-post-orderstatus-orderid-structure.json](json-structure/pos-api-post-orderstatus-orderid-structure.json)
- [pos-api-post-updatepreparationtime-structure.json](json-structure/pos-api-post-updatepreparationtime-structure.json)
- [store-api-post-mark-products-out-of-stock-by-tag-structure.json](json-structure/store-api-post-mark-products-out-of-stock-by-tag-structure.json)
- [store-api-post-post-locations-openinghours-structure.json](json-structure/store-api-post-post-locations-openinghours-structure.json)
- [store-api-post-update-store-status-structure.json](json-structure/store-api-post-update-store-status-structure.json)

### JSON-LD

- [deliverect-channel-api-context.jsonld](json-ld/deliverect-channel-api-context.jsonld)
- [deliverect-commerce-api-context.jsonld](json-ld/deliverect-commerce-api-context.jsonld)
- [deliverect-crm-api-context.jsonld](json-ld/deliverect-crm-api-context.jsonld)
- [deliverect-dispatch-api-context.jsonld](json-ld/deliverect-dispatch-api-context.jsonld)
- [deliverect-gift-cards-api-context.jsonld](json-ld/deliverect-gift-cards-api-context.jsonld)
- [deliverect-kds-api-context.jsonld](json-ld/deliverect-kds-api-context.jsonld)
- [deliverect-loyalty-api-context.jsonld](json-ld/deliverect-loyalty-api-context.jsonld)
- [deliverect-pay-api-context.jsonld](json-ld/deliverect-pay-api-context.jsonld)
- [deliverect-pos-api-context.jsonld](json-ld/deliverect-pos-api-context.jsonld)
- [deliverect-store-api-context.jsonld](json-ld/deliverect-store-api-context.jsonld)

### Examples

- [channel-api-channel-prep-time-example.json](examples/channel-api-channel-prep-time-example.json)
- [channel-api-channel-snooze-example.json](examples/channel-api-channel-snooze-example.json)
- [channel-api-post-channelname-courierupdate-channellinkid-example.json](examples/channel-api-post-channelname-courierupdate-channellinkid-example.json)
- [channel-api-post-channelname-menustatus-id-example.json](examples/channel-api-post-channelname-menustatus-id-example.json)
- [channel-api-post-channelname-order-channellinkid-example.json](examples/channel-api-post-channelname-order-channellinkid-example.json)
- [channel-api-post-channelname-updaterating-example.json](examples/channel-api-post-channelname-updaterating-example.json)
- [channel-api-post-channelname-updatestorestatus-channellinkid-example.json](examples/channel-api-post-channelname-updatestorestatus-channellinkid-example.json)
- [commerce-api-commerce-channel-api-baskets-create-basket-example.json](examples/commerce-api-commerce-channel-api-baskets-create-basket-example.json)
- [commerce-api-commerce-channel-api-baskets-update-basket-customer-example.json](examples/commerce-api-commerce-channel-api-baskets-update-basket-customer-example.json)
- [commerce-api-commerce-channel-api-baskets-update-basket-discounts-example.json](examples/commerce-api-commerce-channel-api-baskets-update-basket-discounts-example.json)
- [commerce-api-get-upsell-items-example.json](examples/commerce-api-get-upsell-items-example.json)
- [commerce-api-patch-commerce-accountid-baskets-basketid-store-example.json](examples/commerce-api-patch-commerce-accountid-baskets-basketid-store-example.json)
- [commerce-api-post-commerce-account-id-checkouts-1-example.json](examples/commerce-api-post-commerce-account-id-checkouts-1-example.json)
- [commerce-api-post-commerce-accountid-baskets-recreate-example.json](examples/commerce-api-post-commerce-accountid-baskets-recreate-example.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-deliveryaddresses-example.json](examples/crm-api-patch-crm-accountid-customers-crmprofileid-deliveryaddresses-example.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-example.json](examples/crm-api-patch-crm-accountid-customers-crmprofileid-example.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-favorites-example.json](examples/crm-api-patch-crm-accountid-customers-crmprofileid-favorites-example.json)
- [crm-api-patch-crm-accountid-customers-crmprofileid-vehicles-example.json](examples/crm-api-patch-crm-accountid-customers-crmprofileid-vehicles-example.json)
- [crm-api-post-crm-accountid-customers-example.json](examples/crm-api-post-crm-accountid-customers-example.json)
- [crm-api-post-crm-accountid-customers-lookup-example.json](examples/crm-api-post-crm-accountid-customers-lookup-example.json)
- [dispatch-api-dispatch-cancel-job-example.json](examples/dispatch-api-dispatch-cancel-job-example.json)
- [dispatch-api-dispatch-create-job-example.json](examples/dispatch-api-dispatch-create-job-example.json)
- [dispatch-api-dispatch-updatejob-example.json](examples/dispatch-api-dispatch-updatejob-example.json)
- [dispatch-api-post-fulfillment-validate-example.json](examples/dispatch-api-post-fulfillment-validate-example.json)
- [gift-cards-api-giftcards-registerprofile-example.json](examples/gift-cards-api-giftcards-registerprofile-example.json)
- [gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-applygiftcard-example.json](examples/gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-applygiftcard-example.json)
- [gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-getgiftcardbalance-example.json](examples/gift-cards-api-post-giftcards-channel-channellinkid-profilelink-giftcardproviderprofilelinkid-getgiftcardbalance-example.json)
- [kds-api-kds-order-notification-example.json](examples/kds-api-kds-order-notification-example.json)
- [kds-api-post-post-kds-orderstatus-orderid-example.json](examples/kds-api-post-post-kds-orderstatus-orderid-example.json)
- [loyalty-api-loyalty-channel-create-loyalty-customer-example.json](examples/loyalty-api-loyalty-channel-create-loyalty-customer-example.json)
- [loyalty-api-loyalty-channel-get-programs-example.json](examples/loyalty-api-loyalty-channel-get-programs-example.json)
- [loyalty-api-loyalty-token-example.json](examples/loyalty-api-loyalty-token-example.json)
- [pay-api-pay-endpoints-refund-payment-example.json](examples/pay-api-pay-endpoints-refund-payment-example.json)
- [pay-api-pay-endpoints-request-payment-example.json](examples/pay-api-pay-endpoints-request-payment-example.json)
- [pay-api-payplatform-payments-profile-register-example.json](examples/pay-api-payplatform-payments-profile-register-example.json)
- [pay-api-payplatform-payments-refund-example.json](examples/pay-api-payplatform-payments-refund-example.json)
- [pay-api-payplatform-payments-request-example.json](examples/pay-api-payplatform-payments-request-example.json)
- [pay-api-payplatform-payments-unregister-profile-example.json](examples/pay-api-payplatform-payments-unregister-profile-example.json)
- [pos-api-insert-update-products-and-categories-example.json](examples/pos-api-insert-update-products-and-categories-example.json)
- [pos-api-inventory-update-example.json](examples/pos-api-inventory-update-example.json)
- [pos-api-pos-api-product-sync-callback-example.json](examples/pos-api-pos-api-product-sync-callback-example.json)
- [pos-api-pos-register-example.json](examples/pos-api-pos-register-example.json)
- [pos-api-post-orderstatus-orderid-example.json](examples/pos-api-post-orderstatus-orderid-example.json)
- [pos-api-post-updatepreparationtime-example.json](examples/pos-api-post-updatepreparationtime-example.json)
- [store-api-post-mark-products-out-of-stock-by-tag-example.json](examples/store-api-post-mark-products-out-of-stock-by-tag-example.json)
- [store-api-post-post-locations-openinghours-example.json](examples/store-api-post-post-locations-openinghours-example.json)
- [store-api-post-update-store-status-example.json](examples/store-api-post-update-store-status-example.json)

## Capabilities

Self-contained Naftiko capabilities (one per API business surface), each exposing both a REST and an MCP adapter over an inline consumes block.

| Capability | API | MCP Tools |
|------------|-----|-----------|
| [Deliverect Channel API — Accounts](capabilities/channel-api-accounts.yaml) | Deliverect Channel API | 1 |
| [Deliverect Channel API — Channel Links](capabilities/channel-api-channel-links.yaml) | Deliverect Channel API | 2 |
| [Deliverect Channel API — Couriers](capabilities/channel-api-couriers.yaml) | Deliverect Channel API | 2 |
| [Deliverect Channel API — Menus](capabilities/channel-api-menus.yaml) | Deliverect Channel API | 2 |
| [Deliverect Channel API — Opening Hours](capabilities/channel-api-opening-hours.yaml) | Deliverect Channel API | 1 |
| [Deliverect Channel API — Orders](capabilities/channel-api-orders.yaml) | Deliverect Channel API | 5 |
| [Deliverect Channel API — Payments](capabilities/channel-api-payments.yaml) | Deliverect Channel API | 1 |
| [Deliverect Channel API — Products](capabilities/channel-api-products.yaml) | Deliverect Channel API | 1 |
| [Deliverect Channel API — Registration](capabilities/channel-api-registration.yaml) | Deliverect Channel API | 1 |
| [Deliverect Channel API — Store Status](capabilities/channel-api-store-status.yaml) | Deliverect Channel API | 2 |
| [Deliverect Commerce API — Baskets](capabilities/commerce-api-baskets.yaml) | Deliverect Commerce API | 9 |
| [Deliverect Commerce API — Checkout](capabilities/commerce-api-checkout.yaml) | Deliverect Commerce API | 2 |
| [Deliverect Commerce API — Coupons](capabilities/commerce-api-coupons.yaml) | Deliverect Commerce API | 1 |
| [Deliverect Commerce API — Menus](capabilities/commerce-api-menus.yaml) | Deliverect Commerce API | 2 |
| [Deliverect Commerce API — Stores](capabilities/commerce-api-stores.yaml) | Deliverect Commerce API | 2 |
| [Deliverect Commerce API — Upsell](capabilities/commerce-api-upsell.yaml) | Deliverect Commerce API | 1 |
| [Deliverect CRM API — Customers](capabilities/crm-api-customers.yaml) | Deliverect CRM API | 7 |
| [Deliverect CRM API — Orders](capabilities/crm-api-orders.yaml) | Deliverect CRM API | 3 |
| [Deliverect Dispatch API — Fulfillment](capabilities/dispatch-api-fulfillment.yaml) | Deliverect Dispatch API | 3 |
| [Deliverect Dispatch API — Jobs](capabilities/dispatch-api-jobs.yaml) | Deliverect Dispatch API | 4 |
| [Deliverect Gift Cards API — Gift Cards](capabilities/gift-cards-api-gift-cards.yaml) | Deliverect Gift Cards API | 4 |
| [Deliverect Gift Cards API — Profiles](capabilities/gift-cards-api-profiles.yaml) | Deliverect Gift Cards API | 2 |
| [Deliverect KDS API — Orders](capabilities/kds-api-orders.yaml) | Deliverect KDS API | 3 |
| [Deliverect KDS API — Products](capabilities/kds-api-products.yaml) | Deliverect KDS API | 1 |
| [Deliverect KDS API — Registration](capabilities/kds-api-registration.yaml) | Deliverect KDS API | 1 |
| [Deliverect Loyalty API — Authentication](capabilities/loyalty-api-authentication.yaml) | Deliverect Loyalty API | 1 |
| [Deliverect Loyalty API — Compensation Cards](capabilities/loyalty-api-compensation-cards.yaml) | Deliverect Loyalty API | 1 |
| [Deliverect Loyalty API — Configuration](capabilities/loyalty-api-configuration.yaml) | Deliverect Loyalty API | 1 |
| [Deliverect Loyalty API — Customers](capabilities/loyalty-api-customers.yaml) | Deliverect Loyalty API | 2 |
| [Deliverect Loyalty API — Programs](capabilities/loyalty-api-programs.yaml) | Deliverect Loyalty API | 2 |
| [Deliverect Pay API — Gateways](capabilities/pay-api-gateways.yaml) | Deliverect Pay API | 1 |
| [Deliverect Pay API — Payments](capabilities/pay-api-payments.yaml) | Deliverect Pay API | 5 |
| [Deliverect Pay API — Profiles](capabilities/pay-api-profiles.yaml) | Deliverect Pay API | 2 |
| [Deliverect POS API — Floors](capabilities/pos-api-floors.yaml) | Deliverect POS API | 1 |
| [Deliverect POS API — Inventory](capabilities/pos-api-inventory.yaml) | Deliverect POS API | 1 |
| [Deliverect POS API — Orders](capabilities/pos-api-orders.yaml) | Deliverect POS API | 4 |
| [Deliverect POS API — Products](capabilities/pos-api-products.yaml) | Deliverect POS API | 4 |
| [Deliverect POS API — Registration](capabilities/pos-api-registration.yaml) | Deliverect POS API | 1 |
| [Deliverect POS API — Tables](capabilities/pos-api-tables.yaml) | Deliverect POS API | 1 |
| [Deliverect Store API — Allergens](capabilities/store-api-allergens.yaml) | Deliverect Store API | 1 |
| [Deliverect Store API — Locations](capabilities/store-api-locations.yaml) | Deliverect Store API | 1 |
| [Deliverect Store API — Opening Hours](capabilities/store-api-opening-hours.yaml) | Deliverect Store API | 6 |
| [Deliverect Store API — Products](capabilities/store-api-products.yaml) | Deliverect Store API | 4 |
| [Deliverect Store API — Store Status](capabilities/store-api-store-status.yaml) | Deliverect Store API | 1 |
| [Deliverect Store API — Tables](capabilities/store-api-tables.yaml) | Deliverect Store API | 1 |

## Vocabulary

- [Deliverect Vocabulary](vocabulary/deliverect-vocabulary.yaml) — Unified taxonomy mapping 77 resources, 14 actions, 45 workflows, and 9 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Deliverect Spectral Rules](rules/deliverect-spectral-rules.yml) — 32 rules enforcing Deliverect API conventions (OAuth 2.0 security, camelCase parameters, Title Case tags, Deliverect summary prefix)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
