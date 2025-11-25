## Module 2 — Plan Builder (Options → Days)

### Inputs required
- Traveler profile: budget style, interests, pace, constraints (mobility, diet, weather)  
- Trip details: destination(s), dates or length, lodging area (or proxy center point)  
- Candidate activity list with metadata  

### Activity schema (each candidate includes)
- **Type:** attraction, park, restaurant, event  
- **Theme:** culture, nature, food, shopping, nightlife  
- **Duration:** estimated hours  
- **Cost range:** low, mid, high  
- **Distance/travel time:** from lodging or prior stop  
- **Indoor/outdoor:** for weather flexibility  
- **Accessibility:** step‑free, short walk, or mobility-friendly  
- **Dietary tags:** vegan, vegetarian, gluten-free, etc.  
- **Booking-needed:** yes/no  
- **Typical hours:** opening/closing times  

### Day-building loop
For each day:

1. **Morning (near lodging):**  
   - Pick a high-interest activity within short travel distance.  
   - Add a nearby café or breakfast option.  
   - Provide one alternate (indoor or closer option).  

2. **Midday (close by):**  
   - Choose lunch or nearby attraction minimizing transfer.  
   - Ensure cost aligns with budget and dietary needs.  
   - Provide one alternate (cheaper or dietary-compliant).  

3. **Afternoon (different theme):**  
   - Select a contrasting theme from morning/midday.  
   - Cap travel time to ≤ 25 minutes or ≤ 5 km.  
   - Provide one alternate (indoor if season suggests).  

4. **Evening (restaurant or optional event):**  
   - Choose dinner compliant with dietary needs and budget.  
   - Offer optional cultural or nightlife event.  
   - Provide one alternate (budget-friendly or quieter option).  

### Alternates
- Each time slot includes at least one alternate activity to handle closures, weather, or budget mismatches.  
- Alternates are tagged for quick swaps (indoor/outdoor, cost tier, accessibility).  
