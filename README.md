# MealMe (mealme)
MealMe provides the largest food ordering API, enabling developers to get menus, inventory, and send orders to the point of sale at over 1 million restaurants and grocery stores for pickup or delivery. Includes a Food Search API, Menu API, and Grocery Ordering API.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mealme/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Delivery, Food, Grocery, Ordering, Restaurants

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-06-02

## APIs

### MealMe Food Ordering API
The MealMe API enables getting menus and inventory and sending orders to the POS of over 1 million restaurants and grocery stores. Every menu item includes real-time availability, prices, and customizations.

**Human URL:** [https://www.mealme.ai/](https://www.mealme.ai/)

**Base URL:** https://api.mealme.ai

#### Tags:

 - Food, Grocery, Ordering, Restaurants

#### Properties

- [Documentation](https://docs.mealme.ai/docs/api-features)
- [Getting Started](https://docs.mealme.ai/docs/create-order)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/mealme/refs/heads/main/openapi/mealme-openapi.yml)
- [Reference](https://docs.mealme.ai/reference)
- [Overview](https://docs.mealme.ai/docs/endpoints-overview)
- [Tutorials](https://docs.mealme.ai/docs/store-search-order-flow)

#### Naftiko Capabilities

- [Search](capabilities/mealme-search.yaml)
- [Stores](capabilities/mealme-stores.yaml)
- [Carts](capabilities/mealme-carts.yaml)
- [Orders](capabilities/mealme-orders.yaml)
- [Payments](capabilities/mealme-payments.yaml)
- [Connect Accounts](capabilities/mealme-connect-accounts.yaml)
- [Support Chat](capabilities/mealme-support-chat.yaml)
- [Tracking](capabilities/mealme-tracking.yaml)
- [Geocoding](capabilities/mealme-geocoding.yaml)

## Common Properties

- [GitHub Organization](https://github.com/MealMe-Ai)
- [LinkedIn](https://www.linkedin.com/company/mealme)
- [Portal](https://www.mealme.ai/)
- [Documentation](https://docs.mealme.ai/)
- [LLMs.txt](https://api.mealme.ai/llms.txt)
- [Spectral Rules](rules/mealme-spectral-rules.yml)
- [Vocabulary](vocabulary/mealme-vocabulary.yaml)
- [JSON-LD Context](json-ld/mealme-api-context.jsonld)
- [Plans & Pricing](plans/mealme-plans-pricing.yml)
- [Rate Limits](rate-limits/mealme-rate-limits.yml)
- [FinOps](finops/mealme-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [MealMe Food Ordering API](openapi/mealme-openapi.yml) — 34 paths, 36 operations across 9 tags

### JSON Schema

- [Cart](json-schema/mealme-api-cart-schema.json)
- [Cart Item](json-schema/mealme-api-cart-item-schema.json)
- [Cart Request](json-schema/mealme-api-cart-request-schema.json)
- [Order](json-schema/mealme-api-order-schema.json)
- [Order Request](json-schema/mealme-api-order-request-schema.json)
- [Payment Method](json-schema/mealme-api-payment-method-schema.json)
- [Payment Method Create Request](json-schema/mealme-api-payment-method-create-request-schema.json)
- [Product](json-schema/mealme-api-product-schema.json)
- [Store](json-schema/mealme-api-store-schema.json)

### JSON Structure

- [Cart](json-structure/mealme-api-cart-structure.json)
- [Cart Item](json-structure/mealme-api-cart-item-structure.json)
- [Cart Request](json-structure/mealme-api-cart-request-structure.json)
- [Order](json-structure/mealme-api-order-structure.json)
- [Order Request](json-structure/mealme-api-order-request-structure.json)
- [Payment Method](json-structure/mealme-api-payment-method-structure.json)
- [Payment Method Create Request](json-structure/mealme-api-payment-method-create-request-structure.json)
- [Product](json-structure/mealme-api-product-structure.json)
- [Store](json-structure/mealme-api-store-structure.json)

### JSON-LD

- [MealMe API Context](json-ld/mealme-api-context.jsonld)

### Examples

- [Cart](examples/mealme-api-cart-example.json)
- [Cart Item](examples/mealme-api-cart-item-example.json)
- [Cart Request](examples/mealme-api-cart-request-example.json)
- [Order](examples/mealme-api-order-example.json)
- [Order Request](examples/mealme-api-order-request-example.json)
- [Payment Method](examples/mealme-api-payment-method-example.json)
- [Payment Method Create Request](examples/mealme-api-payment-method-create-request-example.json)
- [Product](examples/mealme-api-product-example.json)
- [Store](examples/mealme-api-store-example.json)

## Naftiko Capabilities

Self-contained Naftiko capabilities, one per MealMe business surface. Each file inlines its HTTP consumes block plus a REST exposer and an MCP exposer.

| Capability | APIs Combined | Tools | Persona |
|------------|---------------|-------|---------|
| [Search](capabilities/mealme-search.yaml) | MealMe Food Ordering API | 4 | Developer / Diner |
| [Stores](capabilities/mealme-stores.yaml) | MealMe Food Ordering API | 4 | Developer / Merchant |
| [Carts](capabilities/mealme-carts.yaml) | MealMe Food Ordering API | 5 | Developer / Diner |
| [Orders](capabilities/mealme-orders.yaml) | MealMe Food Ordering API | 3 | Developer / Diner |
| [Payments](capabilities/mealme-payments.yaml) | MealMe Food Ordering API | 4 | Developer |
| [Connect Accounts](capabilities/mealme-connect-accounts.yaml) | MealMe Food Ordering API | 8 | Developer / Merchant |
| [Support Chat](capabilities/mealme-support-chat.yaml) | MealMe Food Ordering API | 5 | Support Agent / Diner |
| [Tracking](capabilities/mealme-tracking.yaml) | MealMe Food Ordering API | 1 | Developer |
| [Geocoding](capabilities/mealme-geocoding.yaml) | MealMe Food Ordering API | 2 | Developer |

## Vocabulary

- [MealMe Vocabulary](vocabulary/mealme-vocabulary.yaml) — Unified taxonomy mapping 12 resources, 9 actions, 9 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [MealMe Spectral Rules](rules/mealme-spectral-rules.yml) — 32 rules across 13 categories enforcing MealMe API conventions

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/mealme-plans-pricing.yml) — API Commons Plans 0.1 (Free, Professional, Enterprise)
- [Rate Limits](rate-limits/mealme-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/mealme-finops.yml) — FinOps Framework / FOCUS 1.3 alignment

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
