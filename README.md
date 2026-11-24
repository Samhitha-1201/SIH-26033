# Smart India Hackathon Workshop
# Date:24.11.2026
## Reference Number:26017264
## Name: Samhitha N

## Problem Title

SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization

Ministry of Consumer Affairs, Food & Public Distribution

## Theme

Agriculture, FoodTech & Rural Development

## Problem Description

Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution

FARMBRIDGE: A Collective Agricultural Trading and Transparent Supply Chain Platform

1. Detailed Explanation of the Proposed Solution

FARMBRIDGE is a digital agricultural trading platform designed to empower small and marginal farmers by enabling collective selling, transparent price discovery and shared logistics.

Unlike conventional digital marketplaces that allow farmers to sell their produce individually, FARMBRIDGE introduces a Collective Harvest Pooling mechanism. It groups nearby farmers cultivating the same crop with compatible harvest dates and quality grades into virtual bulk lots.

The platform connects these pooled lots with bulk buyers such as supermarkets, restaurants, hostels, retailers and food-processing industries.

Its major modules include:

- Collective Harvest Pooling: Combines small quantities of produce from multiple farmers into larger marketable lots.
- Farmer-Controlled Price Auction: Allows farmers to establish minimum acceptable prices while buyers submit competitive bids.
- Shared Logistics: Coordinates common transportation and optimizes pickup and delivery routes.
- Transparent Price Tracker: Displays farmer earnings, transportation expenses, platform charges and final buyer prices separately.
- Rescue Harvest Alert: Identifies produce approaching its spoilage window and alerts potential buyers and processing units.

2. How It Addresses the Problem

FARMBRIDGE reduces dependence on multiple price-setting intermediaries by providing a direct connection between farmers and buyers.

Collective selling improves the bargaining position of small farmers who cannot independently supply large buyers. Competitive bidding encourages fairer price discovery, while shared transportation reduces individual logistics expenses.

Transparent transaction records help farmers understand their actual earnings and enable consumers and buyers to understand the cost of procurement.

3. Innovation and Uniqueness

The major innovation of FARMBRIDGE is its Collective Harvest Pooling mechanism combined with farmer-controlled price discovery.

Unlike ordinary farmer-to-consumer applications, it focuses on converting fragmented agricultural production into collectively marketable bulk supply.

Its distinguishing innovations are:

1. Virtual pooling of compatible harvests from multiple nearby farmers.
2. Farmer-defined minimum prices and competitive buyer bidding.
3. Shared transportation with transparent cost allocation.
4. Individual earnings records even when farmers participate in collective sales.
5. Spoilage-window-based rescue alerts for unsold agricultural produce.

The platform aims to transform farmers from isolated sellers into organized market participants without requiring them to surrender control over their produce or pricing decisions.


## Technical Approach

1. Technologies to be used
- Frontend: React.js (web) with a mobile-responsive, multilingual interface
- Backend: Node.js with Express REST APIs
- Database: PostgreSQL (users, lots, bids, transactions)
- Maps and routing: Google Maps / OpenStreetMap APIs for pickup and delivery routes
- Notifications: SMS and WhatsApp alerts (Twilio or similar) for bids and rescue alerts
- Data sources: Agmarknet / eNAM mandi price data as the reference price
- Hosting: Cloud (AWS / Render) with GitHub for version control

2. Methodology and process for implementation
1. Farmers register and list produce (crop, quantity, harvest date, quality grade, location).
2. The pooling engine groups nearby farmers with the same crop, compatible harvest dates and quality grade into a virtual bulk lot.
3. Farmers set a minimum acceptable price, and bulk buyers submit competitive bids.
4. The highest valid bid above the minimum price wins, and the lot is confirmed.
5. The logistics module plans a common pickup route and splits transport cost fairly among farmers.
6. The Transparent Price Tracker records farmer earnings, transport cost, platform charge and final buyer price separately.
7. The Rescue Harvest Alert monitors each lot's spoilage window and notifies buyers and processing units when produce is close to spoiling

## Feasibility and Viability

1. Analysis of the feasibility of the idea
- Technical: Built on mature, open-source technologies, so a working prototype is achievable.
- Economic: Revenue comes from a small commission per transaction, and farmers save on logistics through shared transport.
- Operational: Farmer Producer Organizations (FPOs), self-help groups and local agri-officers can help onboard farmers.

2. Potential challenges and risks
- Low digital literacy and limited internet access in rural areas
- Trust issues around online payments and bidding
- Matching harvest dates and quality grades across farmers
- Buyer adoption and payment defaults
- Last-mile transport availability

3. Strategies for overcoming these challenges
- Simple regional-language interface with voice and icon-based navigation, plus SMS and WhatsApp support
- Onboarding through FPOs, cooperatives and Krishi Vigyan Kendras
- Escrow-based payments, with payment released after delivery confirmation
- Standard quality grading checklists with photo uploads
- Tie-ups with local transporters and a pilot launch in one district before scaling

## Impact and Benefits

1.Potential impact on the target audience
- Small and marginal farmers gain bargaining power and sell at fairer prices.
- Fewer middlemen mean a larger share of the final price reaches the farmer.
- Bulk buyers get reliable, traceable supply from one platform.
- Consumers gain transparency about where the price they pay goes.

2. Benefits of the solution
- Social: Empowers small farmers and strengthens farmer collectives.
- Economic: Higher farmer income, lower per-farmer logistics cost, and fair price discovery.
- Environmental: Rescue alerts cut food waste, and route optimisation reduces fuel use and emissions.

## Research and References

1. Details / Links of the reference and research work
- eNAM (National Agriculture Market): https://enam.gov.in
- Agmarknet (mandi price data): https://agmarknet.gov.in
- Ministry of Agriculture & Farmers Welfare, FPO promotion scheme: https://agriwelfare.gov.in
- FAO, The State of Food and Agriculture (food loss and waste): https://www.fao.org
- ICAR-CIPHET, study on post-harvest losses of major crops and commodities in India


