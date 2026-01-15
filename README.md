# Swiggy_case_study
([<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/7167212f-dcdf-42f3-b8b9-7990cf9d505d" />])

A full RCA + Solutions + Metrics Breakdown 

#   Problem Statement  
 Swiggy has observed a 30% drop in food orders specifically in Bangalore, one of its largest and most profitable markets.  

This is a critical business red flag indicating:  
      * Lower revenue 
      * Loss of market share  
      * Shift in customer behavior  
      * Potential operational or product issues  

We need to identify why this is happening and propose data-driven solutions.  

# Step-by-Step RCA (Root Cause Analysis)  

## A.Market-Level & External Factors  
  ##  1.Competition Pressure  
      * Zomato offering heavy discounts, free delivery, or membership benefits
      * Rise of quick-commerce (Zepto/BBNow) offering ready-to-eat meals.  
  ### Metrics to analyze   
      * Market Share YoY  
      * Price Competitiveness Index  
      * Discount Elasticity  
      * Customer migration (Swiggy → Zomato) % 
  
  ##  2.Weather & Traffic Impact 
      * Heavy rains, civic issues in Bangalore affecting deliveries.
      * Peak-hour traffic surges causing longer delivery times → lower orders.
  ### Metrics  
      * Order decline by weather clusters  
      * Delivery time spike correlation  
  ##  3.Local Regulations  
      * Delivery timing restrictions  
      * Traffic regulation zones (e.g., ORR closures)
  ### Metrics  
      * Orders by time of day  
      * Region-wise drop (%) 
## B.Product & App Experience Issues 
##  1.App Update Issues
     * New UI update increasing drop-offs.  
     * Login failures, stuck screens, payment issues.  
### Metrics
     * App Crash Rate  
     * Home → Restaurant Page Conversion  
     * Cart → Payment Success Funnel  
##  2.Search & Discovery Failures  
     * Restaurants not appearing correctly.  
     * Low relevance of suggestions.
### Metrics
     * Search Success Rate  
     * CTR on restaurant cards  
     * Add-to-cart after search  
##  3.Payment Failures  
     * UPI, card, and wallet failure rates increasing.  
     * Many users abandoning due to failed payments.  
### Metrics
     * Payment Failure Rate  
     * Retry Rate  
     * Payment Gateway-wise disruption report 

## C. Delivery & Operational Issues  
##  1. Increased Delivery Time 
     * Shortage of delivery partners.  
     * Traffic spikes → ETA increases → users drop.  
### Metrics
     * Avg delivery time by cluster  
     * ETA vs Order Placement Correlation  
     * Bounce after ETA view  
##  2. High Surge Fee / High Delivery Charges  
     * Peak-time surge making orders expensive.
     * Delivery fee increasing due to fewer delivery partners.  
### Metrics
     * Orders drop after surge view  
     * Basket size vs delivery fee correlation
##  3. Restaurant Availability Issues  
     * Many restaurants offline during rains or rush hours.  
     * Partner churn in specific areas. 
### Metrics
     * Restaurant offline rate  
     * Cancellation due to restaurant unavailability  
## D. Customer Behavior Shifts  
##  1. Shift Toward Home Cooking  
     * Inflation causing users to cook at home more often.  
     * Reduction in frequency of food ordering.  
### Metrics  
     * Order frequency per user  
     * Avg monthly orders per customer segment  
##  2. Office Crowd Decrease  
     * Hybrid/remote working reducing lunch orders in tech parks.
### Metrics
     * Order drop in office hotspots  
     * Lunch-time decline %
## E. Customer Experience Issues  
##  1. Wrong/Missing Orders  
     * Increase in refund and complaint tickets. 
##  2. Poor Packaging  
     * Food leakage or damage causing dissatisfaction.  
### Metrics  
     * Complaints per 1,000 orders  
     * Refund Rate  
     * CSAT & NPS trends  
## Final Combined Root Causes (Probable)  
     * Competitor discounts from Zomato 
     * Heavy rains causing delays & cancellations  
     * Surge fees making ordering expensive
     * App performance issues from last update
     * Payment failures during peak time
     * Restaurant offline/unavailability spike  
  These combined can easily explain a 30% drop. 
     
 
# Actionable Solutions (Product + Ops + CX)  

## A. Product & UX Solutions  
## 1. Improve ETA Accuracy + Reduce Delivery Time 
   * Dynamic routing optimization
   * Boost incentives for delivery partners during peak hours
Expected Impact: Orders ↑ 10%
## 2.Fix App Issues  
   * Roll back problematic UI flows
   * Improve login/payment stability
   * Enhance session caching
Expected Impact: Funnel conversion ↑ 12%
## 3. Search & Personalization Upgrade  
    * Use vector search for better relevance
    * Personalized restaurant ranking by user preference
    * Real-time availability check  
Expected Impact: Search → Order conversion ↑ 8%  
    
## B. Pricing & Promotions Strategy  
## 1. Temporary Discount Campaign  
    * "Bangalore Food Week": free delivery + surge waiver in specific areas  
    * Counter competitor's discount temporarily  
 Expected Impact: Orders ↑ 15–20%  
## 2.Boost Swiggy One Incentives  
    * Lower renewal fee  
    * Add free desserts/combos for members 
 Expected Impact: Retention ↑ 10% 
## C. Operations & Restaurant Partner Strategy  
## 1.Improve Delivery Partner Supply  
    * Referral incentives  
    * Earnings guarantee during peak rain hours  
 Impact: ETA ↓ significantly  
## 2. Re-activate Offline Restaurants  
    * Contact partners in affected areas  
    * Assign relationship managers for top 200 restaurants  
Impact: Availability ↑ 7–10%

## D. Customer Experience Improvements
## 1. Fix Complaints Fast  
    * Fast refund pipeline  
    * Priority resolution for repeated complaints  
 Impact: NPS ↑ 15%  
## 2. Packaging Audit  
    * Better packaging for biryani, beverages, and liquids 
    * Introduce “leak-proof guarantee” 
 Impact: Complaint rate ↓ 20%   

 # Key Metrics to Track for Recovery  
  * Daily Orders (City-level)
  * Delivery Time / ETA
  * Surge Fee Impact Metric
  * Restaurant Availability %
  * Payment Failure Rate
  * Search Success Rate
  * Conversion Funnel Metrics (Home → Order)
  * NPS & CSAT
  * Repeat Order Rate
  * Active Users in Bangalore
# Final Summary  
A 30% drop in Swiggy orders in Bangalore is usually due to a combination of competition pressure, bad weather, surge fees, delivery delays, app issues, and payment failures.  
The recovery strategy involves:  
* Product Fixes(ETA, search, app stability)
* Operational Enhancements(delivery partner supply, restaurant availability)   


      
