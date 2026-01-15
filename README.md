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
  ## 1.Competition Pressure  
      * Zomato offering heavy discounts, free delivery, or membership benefits
      * Rise of quick-commerce (Zepto/BBNow) offering ready-to-eat meals.  
  ### Metrics to analyze   
      * Market Share YoY  
      * Price Competitiveness Index  
      * Discount Elasticity  
      * Customer migration (Swiggy → Zomato) % 
  
  ## 2.Weather & Traffic Impact 
      * Heavy rains, civic issues in Bangalore affecting deliveries.
      * Peak-hour traffic surges causing longer delivery times → lower orders.
  ### Metrics  
      * Order decline by weather clusters  
      * Delivery time spike correlation  
  ## 3.Local Regulations  
      * Delivery timing restrictions  
      * Traffic regulation zones (e.g., ORR closures)
  ### Metrics  
      * Orders by time of day  
      * Region-wise drop (%) 
## B.Product & App Experience Issues 
## 1.App Update Issues
     * New UI update increasing drop-offs.  
     * Login failures, stuck screens, payment issues.  
### Metrics
     * App Crash Rate  
     * Home → Restaurant Page Conversion  
     * Cart → Payment Success Funnel  
## 2.Search & Discovery Failures  
     * Restaurants not appearing correctly.  
     * Low relevance of suggestions.
### Metrics
     * Search Success Rate  
     * CTR on restaurant cards  
     * Add-to-cart after search  
## 3.Payment Failures  
     * UPI, card, and wallet failure rates increasing.  
     * Many users abandoning due to failed payments.  
### Metrics
     * Payment Failure Rate  
     * Retry Rate  
     * Payment Gateway-wise disruption report 

## C. Delivery & Operational Issues  
## 1. Increased Delivery Time 
     * Shortage of delivery partners.  
     * Traffic spikes → ETA increases → users drop.  
### Metrics
     * Avg delivery time by cluster  
     * ETA vs Order Placement Correlation  
     * Bounce after ETA view  
## 2. High Surge Fee / High Delivery Charges  
     * Peak-time surge making orders expensive.
     * Delivery fee increasing due to fewer delivery partners.  
### Metrics
     * Orders drop after surge view  
     * Basket size vs delivery fee correlation
## 3. Restaurant Availability Issues  
     * Many restaurants offline during rains or rush hours.  
     * Partner churn in specific areas. 
### Metrics
     * Restaurant offline rate  
     * Cancellation due to restaurant unavailability  
## D. Customer Behavior Shifts  
## E. Customer Experience Issues  

# Actionable Solutions (Product + Ops + CX)  

## A. Product & UX Solutions  
## B. Pricing & Promotions Strategy  
## C. Operations & Restaurant Partner Strategy  
## D. Customer Experience Improvements  


      
