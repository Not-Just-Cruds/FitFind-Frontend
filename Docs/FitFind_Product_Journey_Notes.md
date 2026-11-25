# FitFind Product Journey Notes

> Source PDF: [FitFind_Product_Journey_Notes_Revised.pdf](../output/FitFind_Product_Journey_Notes_Revised.pdf)

> Revised product journey

## Linked contents

  - [Customer and shop-owner experiences](#customer-and-shop-owner-experiences)
- [How to read these notes](#how-to-read-these-notes)
- [Product concept: three layers working together](#product-concept-three-layers-working-together)
  - [One catalog, shown in two places](#one-catalog-shown-in-two-places)
- [Product boundaries](#product-boundaries)
- [1. Customer/User Experience](#1-customeruser-experience)
  - [1.1 Arrive and choose whether to personalize](#11-arrive-and-choose-whether-to-personalize)
  - [1.2 Set or change preferences](#12-set-or-change-preferences)
  - [1.3 Explore the personalized home feed](#13-explore-the-personalized-home-feed)
  - [1.4 Browse categories and search the whole marketplace](#14-browse-categories-and-search-the-whole-marketplace)
  - [1.5 Search with a picture](#15-search-with-a-picture)
  - [1.6 Open a shop’s Store Profile](#16-open-a-shops-store-profile)
  - [1.7 Open product details and compare](#17-open-product-details-and-compare)
  - [1.8 Check a specific branch and variant](#18-check-a-specific-branch-and-variant)
  - [1.9 Try on virtually or build an outfit](#19-try-on-virtually-or-build-an-outfit)
  - [1.10 Save items, revisit them and follow updates](#110-save-items-revisit-them-and-follow-updates)
  - [1.11 Ask a product question](#111-ask-a-product-question)
  - [1.12 Choose how to get the product](#112-choose-how-to-get-the-product)
  - [Path A: reserve, visit, try on and buy in person](#path-a-reserve-visit-try-on-and-buy-in-person)
  - [Path A continued: shop response and in-person purchase](#path-a-continued-shop-response-and-in-person-purchase)
  - [Path B: order for delivery](#path-b-order-for-delivery)
  - [1.13 Follow the reservation or order](#113-follow-the-reservation-or-order)
  - [1.14 Return a purchased product and contact support](#114-return-a-purchased-product-and-contact-support)
  - [1.15 Visit the shop and, if purchased, review](#115-visit-the-shop-and-if-purchased-review)
  - [1.16 Customer journey: recovery paths](#116-customer-journey-recovery-paths)
- [2. Shop Owner/Merchant Experience](#2-shop-ownermerchant-experience)
  - [2.1 Discover FitFind and start with a free account](#21-discover-fitfind-and-start-with-a-free-account)
  - [2.2 Enter the live Merchant Workspace](#22-enter-the-live-merchant-workspace)
  - [2.3 Explore free capabilities with real shop information](#23-explore-free-capabilities-with-real-shop-information)
  - [2.4 Review paid capabilities and account limits](#24-review-paid-capabilities-and-account-limits)
  - [2.5 Choose to upgrade and request payment](#25-choose-to-upgrade-and-request-payment)
  - [2.6 Successful payment and unlocking paid features](#26-successful-payment-and-unlocking-paid-features)
  - [2.7 Set up the business and Store Profile](#27-set-up-the-business-and-store-profile)
  - [2.8 Add and manage physical branches](#28-add-and-manage-physical-branches)
  - [2.9 Invite staff and set permissions](#29-invite-staff-and-set-permissions)
  - [2.10 Add products and variants](#210-add-products-and-variants)
  - [2.11 Identify unmet demand](#211-identify-unmet-demand)
  - [2.12 Forecast demand](#212-forecast-demand)
  - [2.13 Add products in bulk](#213-add-products-in-bulk)
  - [2.14 Set branch stock and prices](#214-set-branch-stock-and-prices)
  - [2.15 Create collections, promotions and announcements](#215-create-collections-promotions-and-announcements)
  - [2.16 Receive and decide reservation requests](#216-receive-and-decide-reservation-requests)
  - [2.17 Prepare, complete or close a reservation](#217-prepare-complete-or-close-a-reservation)
  - [2.18 Receive and manage delivery orders](#218-receive-and-manage-delivery-orders)
  - [2.19 Answer customer questions](#219-answer-customer-questions)
  - [2.20 Handle customer support and returns](#220-handle-customer-support-and-returns)
  - [2.21 Review performance and keep the shop current](#221-review-performance-and-keep-the-shop-current)
  - [2.22 Receive operational notifications](#222-receive-operational-notifications)
  - [Merchant journey: common operating outcomes](#merchant-journey-common-operating-outcomes)
- [3. POS/ERP integration testing approaches](#3-poserp-integration-testing-approaches)
  - [3.1 Actual provider sandbox](#31-actual-provider-sandbox)
  - [3.2 Lightweight mock POS/ERP service — recommended](#32-lightweight-mock-poserp-service-recommended)
- [4. How customer and merchant journeys connect](#4-how-customer-and-merchant-journeys-connect)
- [5. Confirmed direction, proposals, assumptions and open decisions](#5-confirmed-direction-proposals-assumptions-and-open-decisions)
  - [Agreed Direction](#agreed-direction)
  - [Proposed Features](#proposed-features)
  - [Working Assumptions](#working-assumptions)
  - [Open Decisions](#open-decisions)
- [6. Small glossary](#6-small-glossary)
- [7. Review and next stage](#7-review-and-next-stage)

### Customer and shop-owner experiences

A plain-language account of how shoppers discover products, choose in-store or delivery fulfillment, and how local retailers bring their shops into FitFind and serve customers.

> **Review stage**  
> Product journey revision for team review. The notes preserve the original customer and merchant story while incorporating current product directions and keeping unsettled launch and operating choices visible.

## How to read these notes

The document follows customers and shop owners from their first interaction with FitFind through ongoing use. Each journey stage explains what the person sees, what they do, how FitFind responds, and what can happen next. Short notes explain the meaning of important rules and decisions.

| Label | Meaning |
| --- | --- |
| Agreed Direction | A product rule or direction explicitly established in the project. |
| Proposed Feature | A capability in the intended product vision whose detailed rules or launch priority may still need review. |
| Working Assumption | A practical interpretation used to explain a journey; it needs confirmation if it affects a product promise. |
| Open Decision | A choice the project has not settled. The notes keep it open instead of silently choosing an answer. |

## Product concept: three layers working together

FitFind serves shoppers looking for fashion products from local physical shops. Three connected parts support one shopping system: a shared marketplace, a branded storefront for each business, and a private work area for owners and their staff.

#### **Layer:** Global Marketplace
- **Who uses it:** Customers
- **What it is for:** Shop across products from all participating retailers together. Customers can discover without knowing the seller, search, compare, open details, check variants and branches, then reserve or order delivery here.
- **How people move between layers:** Open product details and continue shopping from the marketplace. The seller name links to its Store Profile when the customer wants to explore that shop.

#### **Layer:** Store Profile / Storefront
- **Who uses it:** Customers
- **What it is for:** One branded customer-facing home for each business, with its identity, catalog, branches, collections, offers and announcements.
- **How people move between layers:** Enter directly or follow a shop link. Browse, compare, reserve or order delivery within the Store Profile; returning to the Global Marketplace is optional.

#### **Layer:** Merchant Dashboard
- **Who uses it:** Owner and authorized staff
- **What it is for:** Private area for business and Store Profile management, branches, catalog, stock, reservations, delivery orders, staff, conversations, promotions and performance.
- **How people move between layers:** Approved product and availability updates flow to the same listing in the marketplace and Store Profile.

### One catalog, shown in two places

A shop creates and maintains each product listing once. That same listing appears in the Global Marketplace and the shop’s Store Profile; these are not separate catalogs. Product information, variants and branch availability should remain consistent in both places. A customer may complete shopping from either entry point and never has to visit a Store Profile before reserving or ordering.

## Product boundaries

| In the product vision | Not decided for the first launch |
| --- | --- |
| Local participating physical shops; Men, Women and Kids; clothing, shoes and accessories. | Which customer and merchant capabilities are essential for the first usable release. |
| One Store Profile per business; multiple physical branches; one catalog per shop. | Whether delivery is part of the first launch or a later release. |
| Branch-level stock, availability and potentially different prices. | Exact sign-in requirements, payment timing and operational policies. |
| Two complete shopping entry points and two complementary fulfillment paths: in-store reservation/purchase and delivery/shipping. | The providers, coverage areas, delivery statuses and return/refund terms. |
| Reservation requires an actual shop decision; Pending is not confirmation. A reservation is not proof of purchase. | No assumed stock hold based only on a displayed quantity. |
| AI-generated product information requires retailer review and approval before publication. | Paid capabilities such as AI remain locked in the free live account until successful payment. |

## 1. Customer/User Experience

A customer can begin with broad discovery across local shops or enter a particular Store Profile directly. Either way, FitFind supports a complete shopping journey: preference-led exploration, product comparison, branch and variant checks, then an in-store reservation or a delivery order. Following a shop link is optional; it never gates checkout or a reservation.

### 1.1 Arrive and choose whether to personalize

The first screen makes it easy to start shopping without a lengthy setup. Personalization is an invitation, not a condition for browsing the full marketplace.

- **What the person sees:** A welcoming local fashion marketplace, with search, categories and an option to personalize.
- **What they do:** Browse now or begin a short preference setup.
- **What FitFind does:** Explains that products from participating local shops appear together and that the customer can shop from marketplace results or a specific shop profile.
- **What happens next:** The customer can explore immediately or set preferences first; account requirements remain an open decision.

### 1.2 Set or change preferences

A short setup offers useful starting signals while making clear that interests shape recommendations rather than restrict access.

- **What the person sees:** Choices for Men, Women or Kids; style; colors; budget; favorite shops or brands.
- **What they do:** Choose one or more interests, skip any step, or return later to adjust them.
- **What FitFind does:** Uses available choices to order recommendations and feed content; the full marketplace remains available.
- **What happens next:** The customer reaches a more relevant feed and can change preferences as their needs change.

### 1.3 Explore the personalized home feed

The home feed brings together product discovery and shop inspiration, not just links to storefronts. AI/ML-supported product recommendations can suggest items based on customer interests, browsing activity and stated preferences.

- **What the person sees:** Products, new arrivals, collections and inspiration from different participating shops.
- **What they do:** Open an item, collection or shop identity, or continue scrolling.
- **What FitFind does:** Uses available interests, browsing activity and preferences to recommend and order relevant listings. Each listing keeps its seller identity visible.
- **What happens next:** The customer can open details and continue shopping directly, or choose to visit the seller’s Store Profile.

### 1.4 Browse categories and search the whole marketplace

Search and categories cover all participating shops in one shared result set. The customer does not need to know the seller in advance.

- **What the person sees:** Category paths for Men, Women and Kids, clothing, shoes and accessories; search and filters such as size, color, price and style.
- **What they do:** Search a term, browse a category, apply filters and compare results from different shops.
- **What FitFind does:** Returns matching listings from across stores, with shop identity visible on cards or details.
- **What happens next:** The customer opens a product and can reserve or order directly from this marketplace journey.

### 1.5 Search with a picture

Visual search is an alternate way to begin when the customer has an image but not the right words.

- **What the person sees:** An option to add a photo or use the camera where available.
- **What they do:** Provide an image to find products that look similar.
- **What FitFind does:** Finds visually similar marketplace products and connects each result to its seller and branch information. Similarity is a discovery aid, not a promise of an exact match.
- **What happens next:** The customer opens or compares results; image handling and retention rules remain open.

### 1.6 Open a shop’s Store Profile

A Store Profile is a second complete shopping entry point for a customer who wants to shop a particular retailer. It is optional when arriving from a marketplace product.

- **What the person sees:** The shop identity, its catalog, branches, collections, offers and announcements.
- **What they do:** Browse the shop’s products, follow it, inspect branches, or open an item.
- **What FitFind does:** Shows the same listings used in marketplace results, within the context of that business.
- **What happens next:** The customer can select a product and continue to reservation or delivery here, without returning to the Global Marketplace.

### 1.7 Open product details and compare

Product details bring the decision-making information together and keep the seller visible.

- **What the person sees:** Images, description, options, seller identity, prices, availability, alternatives and comparison controls.
- **What they do:** Review the listing, compare exact matches or similar products, and select an item.
- **What FitFind does:** Shows the selected listing and identifies the shop. Comparison distinguishes an exact match from a visually or practically similar alternative.
- **What happens next:** The customer checks a size/color and branch. Product comparison rules remain open.

### 1.8 Check a specific branch and variant

Availability and price are tied to a particular combination of product, variant and branch. A shown quantity is an indication, not a guaranteed hold.

- **What the person sees:** Sizes, colors, relevant options, branch locations, reported availability and applicable prices.
- **What they do:** Choose the desired variant and branch; check hours or contact information where available.
- **What FitFind does:** Shows branch-specific information and warns when availability is unavailable or uncertain. Branch prices may differ.
- **What happens next:** The customer chooses a fulfillment path or checks another branch/variant. A hold exists only after the shop confirms a request.

### 1.9 Try on virtually or build an outfit

Inspiration tools help customers imagine how items work together, including items from different shops.

- **What the person sees:** A virtual try-on option and an Outfit Builder.
- **What they do:** Preview an item; combine clothing, shoes or accessories from several shops; save the outfit.
- **What FitFind does:** Creates an AI-assisted preview and keeps each outfit item linked to its own seller, listing, branch availability and price. It does not create one combined multi-shop purchase.
- **What happens next:** The customer can open each item separately to check availability and choose its own fulfillment. Accuracy and image handling remain open.

### 1.10 Save items, revisit them and follow updates

Saved choices help customers return without repeating discovery.

- **What the person sees:** Wishlist, recently viewed items, followed shops and product or variant alerts.
- **What they do:** Save items, revisit views, follow/unfollow a shop, or watch a product/variant.
- **What FitFind does:** Keeps choices accessible and can notify about restocks, price changes, new collections or shop announcements according to settings.
- **What happens next:** The customer returns to a listing whose current branch availability and price should be checked again.

### 1.11 Ask a product question

The customer can ask a shop-specific question when a listing does not answer something important.

- **What the person sees:** A way to ask about fit, fabric, size, availability or another product detail.
- **What they do:** Send a question from the product or shop context.
- **What FitFind does:** Routes the question to staff or a controlled AI-assisted/hybrid response. AI must use current shop information and must not invent stock or product claims.
- **What happens next:** The answer helps the customer choose a variant, branch or alternative; uncertain questions can go to staff.

### 1.12 Choose how to get the product

After discovery from either the Global Marketplace or a Store Profile, the customer chooses one of two complementary paths. Both use the same catalog listing and product details. The reservation fee applies to both paths; a delivery fee applies only to delivery. The product purchase amount remains the price of the item.

### Path A: reserve, visit, try on and buy in person

The customer wants the shop to review a request and prepare or hold the chosen item before a visit.

- **What the person sees:** Selected product, size/color, quantity, branch, reservation choice, fee information and request summary.
- **What they do:** Choose the variant and quantity, select a physical branch, choose reservation, review the reservation fee and send the request.
- **What FitFind does:** Sends the request to the shop for a decision. Pending remains pending; the fee is distinct from the product price and no delivery fee applies.
- **What happens next:** The customer waits for the shop’s response. If accepted, they visit the selected branch and try the item before deciding whether to buy.

### Path A continued: shop response and in-person purchase

A request becomes actionable only when the shop reviews it.

- **What the person sees:** Pending, Confirmed, Rejected or later Ready status, plus any response or stated hold details.
- **What they do:** Wait while Pending; after confirmation visit the branch, try the item and decide whether to purchase.
- **What FitFind does:** Records the shop’s decision and communicates it. The actual product purchase is completed at the physical shop if the customer chooses to buy.
- **What happens next:** The product amount is paid at the shop. Reservation fee rules and collection timing remain open; no delivery fee applies.

### Path B: order for delivery

A customer may complete a delivery journey from either shopping entry point. Delivery is part of the product vision alongside in-store reservation.

- **What the person sees:** Product, variant, quantity, relevant branch if applicable, delivery choice and fee summary.
- **What they do:** Choose the variant and quantity, select delivery and review the applicable reservation fee, delivery fee and product amount.
- **What FitFind does:** Sends the order to the shop. The merchant checks availability and prepares the product; FitFind supports updates without assuming an unapproved status system.
- **What happens next:** The order proceeds through delivery and the customer receives the product. Provider, coverage, payment timing and statuses remain open decisions.

| Fee | Purpose and path |
| --- | --- |
| Reservation fee | Applies to both in-store reservation and delivery order. Intended to encourage serious intent and protect the retailer when staff check stock, prepare an item or set it aside. It is not the product price. Refundability and collection mechanics are open. |
| Delivery fee | Applies only to delivery and covers that service. It does not apply to in-store reservation. Amount and collection timing are open. |
| Product purchase amount | The actual price of the selected item. For in-store purchase, paid when the customer buys at the shop. For delivery, the payment flow is not yet decided. |

From a retailer’s perspective, a request can consume staff time and prevent a sale elsewhere if a product is checked, prepared or held for someone who does not follow through. Delivery orders can create similar work if cancelled or refused. The reservation fee is intended to encourage serious requests and reduce unnecessary preparation. This explains the intent; it does not set a fee amount, penalty or refund rule, and it does not claim the fee is always non-refundable.

### 1.13 Follow the reservation or order

Customers need a clear view of what the shop has decided and what remains uncertain.

- **What the person sees:** A status and request history. Reservation statuses may include Pending, Confirmed, Rejected, Ready, Expired, Cancelled and Completed.
- **What they do:** Check updates, respond to a clarification request, visit when Ready, or choose another option after rejection/expiry.
- **What FitFind does:** Shows the reservation decision and any available details. Pending means no decision yet and is not a confirmed hold; Confirmed means the shop accepted; Ready means the item was prepared.
- **What happens next:** A completed reservation still does not prove a purchase. Delivery status names and transitions remain an open decision.

#### **Reservation status:** Pending
- **Meaning to the customer:** The shop has not decided yet; do not assume the item is being held.
- **Possible next action:** Wait, ask if appropriate, or explore alternatives.

#### **Reservation status:** Confirmed
- **Meaning to the customer:** The shop accepted the request.
- **Possible next action:** Review branch, variant and any stated hold details.

#### **Reservation status:** Rejected
- **Meaning to the customer:** The shop cannot fulfill it.
- **Possible next action:** Try another branch, variant or alternative.

#### **Reservation status:** Ready
- **Meaning to the customer:** The shop says the item is prepared.
- **Possible next action:** Visit before any stated hold deadline.

#### **Reservation status:** Expired
- **Meaning to the customer:** The request or hold period ended.
- **Possible next action:** Check current availability or request again.

#### **Reservation status:** Cancelled
- **Meaning to the customer:** The customer or shop cancelled.
- **Possible next action:** Review any reason and choose another path.

#### **Reservation status:** Completed
- **Meaning to the customer:** The reservation was closed or handoff marked complete.
- **Possible next action:** Purchase verification is still required before verified review eligibility.

### 1.14 Return a purchased product and contact support

Proposed support journey: after a purchase, a customer who wants to return an item contacts FitFind Support and explains the reason. Support reviews the case and determines the appropriate resolution under the policy that will be established. Where approved, the customer may receive a refund of the full fees, including the reservation fee. This is a proposed process, not a finalized policy or automatic promise. Return periods, eligibility, responsibility and refundable fees remain open. Product amount, reservation fee and delivery fee are separate amounts.

### 1.15 Visit the shop and, if purchased, review

The in-store journey ends with a real visit and a purchase decision; a reservation is not itself a sale.

- **What the person sees:** The confirmed request, selected branch and product; after purchase, an option to review when eligible.
- **What they do:** Visit, try the product and buy if it is right. For delivery, receive the product and complete the actual purchase.
- **What FitFind does:** Keeps reservation outcomes distinct from verified purchases and makes review eligibility depend on confirmed actual purchase for either path.
- **What happens next:** A verified-purchase review becomes available only after a reliable purchase confirmation. The verification method remains open.

### 1.16 Customer journey: recovery paths

When a search or order cannot proceed as expected, FitFind should explain what happened in plain language and offer realistic next steps without implying stock or delivery certainty.

#### **Situation:** No exact search result
- **What FitFind should make clear:** No exact match is currently listed; similar results are not exact matches.
- **Customer’s next options:** Change search terms, use visual search or browse categories.

#### **Situation:** Selected size/color unavailable
- **What FitFind should make clear:** The selected variant cannot currently be requested at that branch.
- **Customer’s next options:** Choose another variant or branch, ask the shop or compare alternatives.

#### **Situation:** Out of stock / stock changed
- **What FitFind should make clear:** Availability may have changed since browsing; displayed stock is not a hold.
- **Customer’s next options:** Check another branch, watch for restock or ask the shop.

#### **Situation:** Pending too long
- **What FitFind should make clear:** The shop has not decided; Pending does not mean confirmed.
- **Customer’s next options:** Wait, contact the shop if available, or review alternatives; response timing is open.

#### **Situation:** Rejected reservation
- **What FitFind should make clear:** The shop declined the request, optionally with a reason.
- **Customer’s next options:** Try another branch/variant or shop.

#### **Situation:** Expired or cancelled
- **What FitFind should make clear:** The request is no longer active.
- **Customer’s next options:** Review the reason, check current stock and create a new request if appropriate.

#### **Situation:** Delivery cannot be fulfilled
- **What FitFind should make clear:** The shop cannot currently complete the order; no unsupported promise about timing is made.
- **Customer’s next options:** Review available alternatives or contact support under the eventual process.

#### **Situation:** Delivery cancelled or refused
- **What FitFind should make clear:** The order did not complete; fee and refund treatment are not assumed.
- **Customer’s next options:** Review the case and contact FitFind Support.

#### **Situation:** Customer requests a return
- **What FitFind should make clear:** Return eligibility and fees depend on the policy still to be defined.
- **Customer’s next options:** Contact FitFind Support and provide purchase details.

## 2. Shop Owner/Merchant Experience

The retailer can start using FitFind through a free live account, working with the real business information and capabilities available in that tier. As the retailer explores the workspace, paid capabilities are clearly identified. The retailer may continue with the free features or pay to unlock the paid capabilities once their scope and plans are set.

### 2.1 Discover FitFind and start with a free account

A retailer can begin directly with a free account and start using the available capabilities. The free tier provides practical access to FitFind and lets the retailer assess its value during normal work.

- **What the person sees:** A merchant sign-up and workspace entry point with a clear explanation of free access.
- **What they do:** Create an account and begin the available business setup.
- **What FitFind does:** Creates a live merchant workspace with the features available at no charge. Account information and verification requirements remain to be decided.
- **What happens next:** The retailer can begin working in FitFind using real business information.

### 2.2 Enter the live Merchant Workspace

The retailer enters the same live workspace used for ongoing business operations, with free capabilities ready to use.

- **What the person sees:** A merchant workspace with its available navigation, setup tasks and account status.
- **What they do:** Open the workspace and choose a task to begin.
- **What FitFind does:** Shows the features available to the free account and any setup needed to use them.
- **What happens next:** The retailer can explore useful functions as part of normal use in the live workspace.

### 2.3 Explore free capabilities with real shop information

The retailer can try available free features while setting up or managing the actual shop. Free use is part of the live product experience.

- **What the person sees:** The retailer’s own business workspace, products, branches and available free functions.
- **What they do:** Use free capabilities with the business information they enter and maintain.
- **What FitFind does:** Applies changes to the live workspace according to the account’s access and normal publication rules.
- **What happens next:** The retailer can continue using free capabilities or consider an upgrade when a paid feature is useful.

### 2.4 Review paid capabilities and account limits

Paid capabilities should be visible and understandable even before the retailer upgrades. The exact paid feature set is not decided yet.

- **What the person sees:** Clear labels for features that require payment and an explanation of what access is available now.
- **What they do:** Review the available paid capabilities and decide whether any meet the shop’s needs.
- **What FitFind does:** Keeps paid functions unavailable until successful payment, without implying which specific features will be paid.
- **What happens next:** The retailer may continue with free access or choose to upgrade.

### 2.5 Choose to upgrade and request payment

An upgrade is optional. The retailer can request to proceed with payment when ready.

- **What the person sees:** An upgrade path with plan and payment information once these are defined.
- **What they do:** Choose to upgrade and continue to the payment step.
- **What FitFind does:** Presents the applicable subscription and payment flow; no plans or prices are assumed here.
- **What happens next:** Successful payment unlocks the paid capabilities included in the selected plan.

### 2.6 Successful payment and unlocking paid features

After payment succeeds, the retailer sees which additional capabilities are now available.

- **What the person sees:** Payment confirmation and updated access to paid capabilities.
- **What they do:** Continue working in the existing live workspace.
- **What FitFind does:** Unlocks the paid capabilities associated with the selected plan; free access remains part of the account.
- **What happens next:** The retailer continues normal use with the expanded access. Paid feature definitions, plans and account changes remain open decisions.

### 2.7 Set up the business and Store Profile

The retailer establishes one branded public presence for the business.

- **What the person sees:** Fields for business name, description, logo, cover, contact details, identity and storefront presentation.
- **What they do:** Enter business details and configure the Store Profile.
- **What FitFind does:** Creates one profile for the business and makes approved content available to customers. Verification and publishing approval requirements remain open.
- **What happens next:** The owner adds physical branches under the same business profile.

### 2.8 Add and manage physical branches

A business can represent several real locations while keeping one Store Profile.

- **What the person sees:** Branch location, address, hours, contact details, status and branch stock context.
- **What they do:** Add or update each branch.
- **What FitFind does:** Keeps branch records separate so customers can check a specific location.
- **What happens next:** The owner assigns employees and maintains availability per branch.

### 2.9 Invite staff and set permissions

The owner can involve staff while limiting access to what each role needs.

- **What the person sees:** Staff list, invitations and permission controls.
- **What they do:** Invite employees and assign appropriate access.
- **What FitFind does:** Applies authorized permissions and records relevant activity. Exact roles and permission boundaries remain open.
- **What happens next:** Authorized staff can help maintain listings, requests and customer conversations.

### 2.10 Add products and variants

The shop maintains one catalog; each product is entered once and shown in two customer-facing locations.

- **What the person sees:** Fields for title, category, audience, images, description, sizes, colors and other options.
- **What they do:** Create a product and its variants, then submit accurate information for publication.
- **What FitFind does:** Uses one listing for both Global Marketplace and Store Profile. Branch stock and price are managed separately from base product information.
- **What happens next:** The approved product can be discovered across FitFind and inside the shop’s Store Profile.

### 2.11 Identify unmet demand

FitFind can help a retailer see products, sizes or categories that customers search for but cannot find in the shop’s available inventory. This proposed retailer-facing AI capability has high business value; usefulness depends on available search and inventory information.

- **What the person sees:** A view of products, sizes or categories customers are searching for but cannot find in available inventory.
- **What they do:** Review the unmet-demand signals and consider whether the shop’s assortment or availability should change.
- **What FitFind does:** Highlights repeated customer searches that do not lead to an available product match. It does not create inventory or make purchasing decisions for the retailer.
- **What happens next:** The retailer can use the signal when reviewing assortment and stock decisions. Data thresholds, reporting and launch priority remain open.

### 2.12 Forecast demand

Demand forecasting can use historical customer activity and inventory or sales information, where available, to help the retailer anticipate future demand. This is a proposed machine-learning capability; data availability and forecast detail are not yet defined.

- **What the person sees:** A forecast or summary of expected demand, based on historical activity and available inventory or sales information.
- **What they do:** Review the forecast as one input when planning stock and product availability.
- **What FitFind does:** Uses available history to estimate future demand and explains when the information is incomplete. The forecast supports judgment rather than guaranteeing a result.
- **What happens next:** The retailer can consider the forecast alongside shop knowledge. Data sources, time periods, accuracy expectations and access remain open decisions.

### 2.13 Add products in bulk

A spreadsheet can make a large catalog easier to enter while preserving a review step.

- **What the person sees:** Excel/CSV upload area and an import preview.
- **What they do:** Upload product information and images, inspect matched rows, errors and proposed additions or updates, correct issues and approve.
- **What FitFind does:** Checks required information, highlights row-level problems and previews the effect before changes are applied.
- **What happens next:** After approval, valid products are added or updated in the one shop catalog.

### 2.14 Set branch stock and prices

Each branch’s stock and prices are maintained independently.

- **What the person sees:** Branch and variant controls for quantities, availability and applicable prices.
- **What they do:** Record current stock, sizes/colors and branch price where applicable.
- **What FitFind does:** Keeps each branch’s reported availability and price separate. A displayed quantity is not a guaranteed hold; no automated source or refresh cadence is assumed.
- **What happens next:** Customers see current reported information across marketplace and Store Profile listings.

### 2.15 Create collections, promotions and announcements

The retailer can give customers useful paths through the catalog and timely shop updates.

- **What the person sees:** Tools for collections, offers, promotions and announcements.
- **What they do:** Group products, publish a promotion or share an update.
- **What FitFind does:** Displays approved content on the Store Profile and relevant discovery areas. Promotion rules and content controls remain open.
- **What happens next:** Customers can discover the shop’s assortment and follow updates.

### 2.16 Receive and decide reservation requests

Every request requires a real shop decision; stock display alone never confirms it.

- **What the person sees:** A queue showing item, variant, branch, quantity and customer.
- **What they do:** Check actual stock; confirm, reject with a reason where possible, or ask for clarification.
- **What FitFind does:** Routes the request to the relevant branch/team, records the decision and informs the customer. Pending stays Pending until a deliberate decision.
- **What happens next:** If accepted, the retailer prepares the item or proceeds under the agreed process; otherwise customer options remain visible.

### 2.17 Prepare, complete or close a reservation

Staff can show progress after an accepted request and close it when the outcome is known.

- **What the person sees:** Status controls and history for each reservation.
- **What they do:** Mark Ready when prepared; later close as Completed, Cancelled or expired under the eventual policy.
- **What FitFind does:** Keeps status history and communicates the updated state. Completed does not automatically mean a verified purchase.
- **What happens next:** Purchase confirmation remains a separate step for verified reviews and analytics.

### 2.18 Receive and manage delivery orders

Delivery is a separate merchant fulfillment path in the product vision, alongside in-store reservations.

- **What the person sees:** A delivery order with product, variant, quantity, customer and relevant branch information.
- **What they do:** Review the order, check actual availability, prepare the product, handle delivery and keep the customer informed.
- **What FitFind does:** Supports order handling and customer updates without presuming a provider, detailed workflow or final status system.
- **What happens next:** Order completion and actual purchase need reliable confirmation; delivery operations and statuses remain open decisions.

### 2.19 Answer customer questions

Customers may ask about fit, fabric, sizing, product details or availability before choosing.

- **What the person sees:** A conversation queue connected to product and shop context.
- **What they do:** Respond manually, use an approved AI-assisted draft, or combine both.
- **What FitFind does:** Routes questions to authorized staff or a controlled hybrid process. AI uses current shop information and escalates when unsure; it does not invent stock.
- **What happens next:** The customer receives a product-specific answer and can continue shopping.

### 2.20 Handle customer support and returns

When a return is requested, the merchant may need to provide purchase or order details while FitFind Support reviews the case.

- **What the person sees:** A support request and relevant purchase/order context.
- **What they do:** Provide accurate information and cooperate with the support review as the final process requires.
- **What FitFind does:** FitFind Support reviews the proposed case and determines a resolution under a policy still to be defined. No merchant responsibility or refund rule is presumed.
- **What happens next:** Any approved return or fee refund follows the eventual policy.

### 2.21 Review performance and keep the shop current

The dashboard helps the retailer distinguish customer interest from confirmed sales.

- **What the person sees:** Activity by product, branch and time period.
- **What they do:** Review views, saves, follows, questions, reservations, response times and confirmed outcomes or sales where available.
- **What FitFind does:** Separates interest and reservation activity from sales; a view or reservation is not reported as a sale unless a purchase is confirmed.
- **What happens next:** The owner can improve listings, stock, responses or collections. Metrics and privacy details remain open.

### 2.22 Receive operational notifications

Notifications bring work that needs attention to the owner or relevant team.

- **What the person sees:** Alerts for new reservations, delivery orders, questions, low or changed stock, imports, staff actions and other defined events.
- **What they do:** Review and respond to tasks.
- **What FitFind does:** Notifies the appropriate owner/team based on permissions and settings. Notification channels and timing remain open.
- **What happens next:** The retailer keeps customer requests and shop information moving.

### Merchant journey: common operating outcomes

#### **Situation:** New product or content
- **Merchant action or meaning:** Publish approved catalog information once.
- **Customer-facing effect:** The same listing is available in marketplace discovery and the Store Profile.

#### **Situation:** Branch stock or price changes
- **Merchant action or meaning:** Update the relevant branch and variant.
- **Customer-facing effect:** Customers see branch-specific reported information; stock is not a hold.

#### **Situation:** Reservation request arrives
- **Merchant action or meaning:** Check actual stock and make a deliberate decision.
- **Customer-facing effect:** Pending remains unconfirmed until the shop acts.

#### **Situation:** Reservation is accepted
- **Merchant action or meaning:** Prepare the item and update its status.
- **Customer-facing effect:** Customer sees confirmation and readiness updates.

#### **Situation:** Delivery order arrives
- **Merchant action or meaning:** Check availability, prepare and handle through the agreed delivery process.
- **Customer-facing effect:** Customer receives order updates; final status and provider details remain open.

#### **Situation:** Customer asks a question
- **Merchant action or meaning:** Answer from current shop information or escalate uncertainty.
- **Customer-facing effect:** Customer receives a reliable product-specific answer.

#### **Situation:** Customer requests a return
- **Merchant action or meaning:** Provide relevant details as FitFind Support reviews the proposed case.
- **Customer-facing effect:** Resolution follows the policy that remains to be decided.

#### **Situation:** Staff changes shop information
- **Merchant action or meaning:** Use assigned access; review activity where available.
- **Customer-facing effect:** Current approved information is reflected to customers.

## 3. POS/ERP integration testing approaches

These are possible ways to test inventory links with external point-of-sale or enterprise resource planning services. They describe testing and validation only; they do not confirm a production integration or a provider FitFind will support.

### 3.1 Actual provider sandbox

Some providers offer a developer or sandbox environment where a sample store, products and inventory updates can be used for testing. Shopify Development Store and Square Sandbox are examples only, not confirmed FitFind providers. This approach tests against a real external service and reveals realistic synchronization behavior. Their product models may not fully represent fashion variants and multiple physical branches.

### 3.2 Lightweight mock POS/ERP service — recommended

The recommended testing approach is a lightweight external inventory service that behaves like a retailer’s system. It can represent products, sizes and colors, branches, stock quantities and prices without becoming a complete point-of-sale application. For example, the hoodie quantity changes from ten to three in the mock service; FitFind then updates the reported availability. Mockoon or JSON Server may be used as optional examples. This remains a testing recommendation, not a production integration decision.

## 4. How customer and merchant journeys connect

A customer-facing action depends on a retailer maintaining accurate information and responding to requests. The two entry points use the same catalog and fulfillment system; each action can start from marketplace discovery or the shop’s own Store Profile.

#### **Customer experience:** Discover products in the Global Marketplace.
- **Merchant action behind it:** Create and maintain one product listing.
- **Shared result:** The same product appears in global discovery and the Store Profile.

#### **Customer experience:** Shop directly from a Store Profile.
- **Merchant action behind it:** Maintain the business identity and catalog.
- **Shared result:** Customers can complete shopping within that specific shop.

#### **Customer experience:** See products from multiple shops together.
- **Merchant action behind it:** Each shop maintains its own catalog.
- **Shared result:** Unified discovery without duplicated catalogs.

#### **Customer experience:** Check branch availability and price.
- **Merchant action behind it:** Maintain stock and prices by branch and variant.
- **Shared result:** Decisions relate to the correct location and option.

#### **Customer experience:** Request a reservation.
- **Merchant action behind it:** Review and confirm or reject deliberately.
- **Shared result:** Pending remains unconfirmed until the shop decides.

#### **Customer experience:** Choose delivery.
- **Merchant action behind it:** Receive and prepare the order.
- **Shared result:** Customer and retailer follow the delivery journey.

#### **Customer experience:** Follow a shop or product.
- **Merchant action behind it:** Publish updates and maintain product information.
- **Shared result:** Customers receive relevant changes.

#### **Customer experience:** Ask a product question.
- **Merchant action behind it:** Staff or controlled AI/hybrid process responds.
- **Shared result:** Customer receives shop-specific information.

#### **Customer experience:** Submit a verified-purchase review.
- **Merchant action behind it:** Confirm an actual in-store or delivery purchase.
- **Shared result:** A reservation alone never qualifies as proof of purchase.

#### **Customer experience:** Request a return.
- **Merchant action behind it:** FitFind Support reviews a case with relevant retailer details.
- **Shared result:** Any resolution follows a policy still to be defined.

## 5. Confirmed direction, proposals, assumptions and open decisions

### Agreed Direction

**Agreed directions**

- FitFind combines a shared Global Marketplace, individual Store Profiles and a private Merchant Dashboard.
- Customers can shop directly from the Global Marketplace or directly from a Store Profile; visiting the Store Profile before shopping is optional.
- Each business has one Store Profile and may have multiple physical branches.
- Each shop maintains one catalog. The same listing appears in marketplace and Store Profile; it is not duplicated.
- Branch stock and availability may differ; branch prices may differ.
- Reservation requests require a shop decision. Pending is not confirmed and displayed stock is not a guaranteed hold.
- FitFind’s product vision supports in-store reservation/purchase and delivery/shipping.
- A reservation fee applies to both fulfillment paths; delivery fee applies only to delivery. Amounts, collection and refunds are undecided.
- A reservation is not proof of purchase. Verified reviews require actual purchase confirmation, whether in-store or delivery.
- Retailers can start with a free live account using real business information. Paid capabilities unlock after successful payment; which capabilities are free or paid remains undecided.
- AI recommendations, unmet-demand signals and forecasts are intended to support customer and retailer decisions; their scope and data rules remain to be decided.
- A lightweight mock external inventory service is the recommended POS/ERP testing approach; actual provider sandboxes remain an alternative.

### Proposed Features

The intended product vision includes preference onboarding, personalized discovery and product recommendations based on interests, browsing activity and preferences; visual search; AI virtual try-on; cross-shop outfit building; retailer-facing unmet-demand detection and demand forecasting; collections and inspiration; follows and product alerts; wishlist and recent views; product questions; bulk upload; employee permissions; activity history; merchant analytics; operational notifications; delivery fulfillment; support and returns. Their presence here does not settle implementation details or launch priority.

### Working Assumptions

**Working assumptions needing confirmation**

- Retailers can use available free features in a live account, then unlock paid capabilities after successful payment. The plans, feature split and upgrade details remain undecided.
- Retailers check actual stock before confirming a reservation or accepting a delivery order.
- Customer support may review return cases and may approve a refund of full fees, including a reservation fee; this is a proposed process, not a promise.
- Product listings can be displayed consistently across both customer entry points using one shop catalog.

### Open Decisions

| Topic | Decision still needed |
| --- | --- |
| Launch scope | Which customer and merchant capabilities are essential for the first usable release? Is delivery in the first launch or a later release? |
| Customer access and preferences | Can customers browse without an account? Which actions require sign-in? What are the final preference options and budget bands? |
| Storefront and dashboard | Which templates and customization controls are available? Is the Merchant Dashboard web, mobile or both? |
| Inventory | How is stock entered and refreshed? How is stale availability shown? Are reservations deducted while Pending or only after confirmation? |
| Branch prices | Is there a shared default price with optional branch overrides, or does each branch set its own price? |
| Reservation policy | How long may a request remain Pending? How long does a confirmed/ready item remain held? Can a reservation contain multiple items? Who can cancel or expire it? |
| Reservation fees | What is the amount and is it fixed or variable? When/how is it collected? What happens when rejected, cancelled or expired? How are fee refunds handled? |
| Delivery and shipping | Which areas are supported? Who provides delivery? How is its fee calculated and collected? How are failed deliveries and refused orders handled? What statuses should customers and merchants see? |
| Payments | When does the customer pay for the product? How does payment work in each fulfillment path? How are reservation and delivery fees collected and handled? |
| Returns and refunds | What is the return policy? Which cases qualify for refunds? Which fees may be refunded? How does FitFind Support resolve cases? |
| Retailer free access and subscription | What information is required to start a free account? Which capabilities are free and which are paid? What plans and paid capabilities will be offered? Does an existing free account upgrade in place? What verification or publication approval is required and when? |
| Purchase verification | What reliably confirms an in-store purchase and actual delivery purchase completion? |
| Notifications | Which events trigger alerts, which channels are used, and how are preferences managed? |
| AI features and customer data | How will recommendation signals use customer interests and browsing activity? What privacy, data-use, explanation and accuracy controls apply to recommendations, unmet-demand detection, forecasts, visual search and virtual try-on? |
| Product comparison | How are exact matches distinguished from similar products, and which attributes can customers compare? |
| Analytics and privacy | Which metrics are shown, at what level, and under what privacy controls? |
| Promotions and content | Which offer types, approval rules and content controls are available? |
| Bulk upload | Which file formats and fields are accepted, and how are image matching and error correction handled? |
| Staff roles | Which roles and permissions can owners assign? |
| Future phases | Which capabilities follow the first usable release? |

## 6. Small glossary

| Term | Plain-language meaning |
| --- | --- |
| Global Marketplace | Shared shopping area where products from all participating shops can be discovered, compared and purchased/reserved directly. |
| Store Profile / Storefront | One shop’s branded customer-facing page inside FitFind. Shopping can be completed there; it is an optional entry point. |
| Merchant Dashboard | Private work area an owner and authorized staff use to manage a shop. |
| Branch | A physical location belonging to a shop, with its own address, operating information and stock. |
| Variant | A version of a product, such as a particular size and color. |
| Inventory / Stock | Items and quantities a branch currently reports as available. A displayed quantity is not a guaranteed hold. |
| Personalized Feed | Marketplace suggestions shaped by customer preferences and followed shops. |
| Follow a Shop | Ask FitFind to keep the shop easy to revisit and show relevant updates. |
| Watch a Product | Ask to hear about changes to a chosen product or variant. |
| Visual Search | Use a picture to discover products that look similar. |
| Virtual Try-On | An AI-created preview of how an item may look; an aid, not a guarantee of fit. |
| Outfit Builder | A way to combine products into an outfit. Items from different shops remain separate listings and purchases. |
| Reservation | A customer request for a shop to review and prepare/hold an item. It is not confirmed until the shop accepts and is not proof of purchase. |
| Reservation Fee | Fee associated with both reservation and delivery paths, intended to encourage serious requests and protect retailer effort. Amount and rules remain open. |
| Delivery Fee | Fee that applies to the delivery path only. Amount and collection remain open. |
| Delivery Order | A request to purchase an item for delivery, subject to shop availability and an undecided delivery process. |
| Free Merchant Account | A live merchant workspace that provides features available at no charge; paid capabilities can be unlocked after payment. |
| Mock Data | Sample business, product or order information used for testing; live free-tier use works with the retailer’s real business information. |
| POS/ERP | A retailer’s external system for managing sales, products or stock. In this document it is discussed as an integration-testing context. |
| Verified-Purchase Review | A review available only after actual purchase is confirmed. A reservation alone does not qualify. |
| Activity Log | A history of relevant actions taken in the merchant workspace. |
| Bulk Upload | Adding or updating many product listings together from a spreadsheet, with a preview and approval step. |

## 7. Review and next stage

Please review the product concept, the two end-to-end journeys, fulfillment and fee distinctions, and the open decisions. Once the notes are reviewed and approved, the next stage can translate agreed behavior into diagrams. Launch scope, payment handling, reservation fee rules, delivery operations, returns, merchant verification and purchase verification remain to be decided.
