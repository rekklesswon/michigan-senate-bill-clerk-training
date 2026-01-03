# Practice Scenarios for Bill Clerks

**Purpose:** Realistic scenarios to practice coding legislative actions in real-time

**How to Use:**
1. Read each scenario as if you're listening to live Senate proceedings
2. Answer the questions (what would you code?)
3. Check the expandable answer key
4. Practice until you can quickly identify actions and code them correctly

---

## Navigation
**Back to:** [Course Home](../README.md)

---

## Scenario 1: Committee Report

**You're a Bill Clerk. The Committee Chair announces:**

> "Mr. President, the Committee on Transportation and Infrastructure has had under consideration Senate Bill 342, a bill to amend the Michigan Vehicle Code regarding electric vehicle charging stations. The committee reports the bill with the recommendation 'do pass as amended.' The committee amendments change the implementation timeline from 2025 to 2026 and add reporting requirements for charging station operators. The committee also refers the bill to the Committee on Appropriations due to fiscal impact."

### Questions:

1. What committee reported the bill?
2. What was the committee's action/recommendation?
3. What changes did the committee make?
4. Where does the bill go next?
5. What should you code?

<details>
<summary><strong>Answer Key</strong></summary>

### Answers:

1. **Committee:** Transportation and Infrastructure
2. **Action:** Reported with recommendation "do pass as amended"
3. **Changes:** Committee made two amendments:
   - Changed implementation timeline from 2025 to 2026
   - Added reporting requirements for charging station operators
4. **Next step:** Bill goes to Appropriations Committee (NOT to General Orders) because of fiscal impact
5. **Code:**
   - SB 342
   - Committee: Transportation and Infrastructure
   - Action: Reported "do pass as amended"
   - Committee amendments: Timeline change, reporting requirements added
   - Referred to: Appropriations Committee

### Key Learning Points:
- Bill doesn't go to General Orders yet because of additional committee referral
- "Do pass as amended" means committee made changes
- Multiple referrals are common (policy committee → Appropriations)
- You should note the substance of amendments for context
</details>

---

## Scenario 2: Floor Amendment on General Orders

**You're coding floor proceedings:**

> **President:** "Senate Bill 445 is before the Senate on General Orders. The Senator from the 15th District is recognized."
>
> **Senator Williams:** "Thank you, Mr. President. Senate Bill 445 addresses rural broadband access by providing grants to internet service providers. I ask my colleagues for support."
>
> **President:** "The Senator from the 22nd District is recognized."
>
> **Senator Jackson:** "Mr. President, I offer Floor Amendment 1 to Senate Bill 445. This amendment increases the grant cap from $500,000 to $750,000 per provider to better address the infrastructure costs in rural areas."
>
> **President:** "The amendment has been offered. The question being on the adoption of Floor Amendment 1. All in favor say 'aye.' All opposed say 'no.' In the opinion of the Chair, the ayes have it. The amendment is adopted."
>
> **Senator Lee:** "Mr. President, I offer Floor Amendment 2 to Senate Bill 445. This amendment adds a reporting requirement for grant recipients to submit annual progress reports."
>
> **President:** "The amendment has been offered. Senator Davis?"
>
> **Senator Davis:** "I request a roll call vote, Mr. President."
>
> **President:** "A roll call has been requested. The question being on the adoption of Floor Amendment 2. The Secretary will call the roll... Roll call: Yeas 15, Nays 23, Excused 0, Not Voting 0. The amendment is defeated."
>
> **Senator Williams:** "Mr. President, I move that Senate Bill 445 be advanced to Third Reading."
>
> **President:** "The question being on advancing the bill to Third Reading. All in favor say 'aye.' All opposed say 'no.' In the opinion of the Chair, the ayes have it. The bill is advanced to Third Reading."

### Questions:

1. What stage is SB 445 in at the beginning?
2. How many amendments were offered?
3. What was the result of Floor Amendment 1?
4. What was the result of Floor Amendment 2?
5. What happened at the end?
6. What should you code for this entire sequence?

<details>
<summary><strong>Answer Key</strong></summary>

### Answers:

1. **Stage:** General Orders (Committee of the Whole)
2. **Amendments offered:** Two (FA 1 and FA 2)
3. **FA 1 result:** ADOPTED (voice vote) - increased grant cap from $500K to $750K
4. **FA 2 result:** DEFEATED (roll call: 15-23) - reporting requirement rejected
5. **Final action:** Bill advanced to Third Reading (voice vote)
6. **Complete coding:**

**SB 445 - General Orders:**
- Sponsor: Senator Williams (15th District)
- Subject: Rural broadband grants to ISPs

**Amendments:**
- FA 1 (Sen. Jackson): Increase grant cap $500K → $750K
  - Vote: Voice vote
  - Result: ADOPTED
- FA 2 (Sen. Lee): Add annual reporting requirement
  - Vote: Roll call - Yeas 15, Nays 23, Excused 0, Not Voting 0
  - Result: DEFEATED

**Motion to Advance:**
- Made by: Sen. Williams
- Vote: Voice vote
- Result: CARRIED - Bill advanced to Third Reading

### Key Learning Points:
- General Orders is where amendments happen
- Voice votes don't record individual votes (just "ayes have it")
- Any Senator can request roll call vote
- Roll call shows exact vote count
- Bill must be moved to Third Reading (not automatic)
- Five-day rule starts when bill placed on Third Reading
</details>

---

## Scenario 3: Advancing to Third Reading

**Senate floor proceedings continue:**

> **President:** "The Chair lays before the Senate Senate Bill 567 on General Orders."
>
> **Senator Martinez:** "Mr. President, Senate Bill 567 reforms the Michigan Business Tax to provide credits for small businesses hiring veterans. The bill was thoroughly reviewed in the Finance Committee and I urge my colleagues to support it."
>
> **President:** "Is there any discussion? Seeing none, the question is on advancing Senate Bill 567 to Third Reading. All in favor say 'aye.' All opposed say 'no.' In the opinion of the Chair, the ayes have it. Senate Bill 567 is advanced to Third Reading."

### Questions:

1. What happened in this scenario?
2. Were any amendments offered?
3. What is the next step for SB 567?
4. When can the Senate vote on final passage?
5. What should you code?

<details>
<summary><strong>Answer Key</strong></summary>

### Answers:

1. **What happened:** SB 567 was on General Orders, no amendments were offered, and it was advanced to Third Reading
2. **Amendments:** None offered (clean advance)
3. **Next step:** Bill placed on Third Reading calendar; five-day rule begins
4. **Final passage vote:** Cannot happen until at least 5 calendar days pass after bill placed on Third Reading
5. **Code:**
   - SB 567 on General Orders
   - Sponsor: Sen. Martinez
   - Subject: Michigan Business Tax credits for hiring veterans
   - No amendments offered
   - Motion to advance to Third Reading: CARRIED (voice vote)
   - Bill advanced to Third Reading
   - Date placed on Third Reading: [today's date]
   - Eligible for final vote: [today + 5 calendar days]

### Key Learning Points:
- Not all bills are amended on General Orders
- Some bills move quickly if non-controversial
- Five-day rule is critical - mark the date!
- Count 5 CALENDAR days (not session days)
- Example: Placed Monday → Eligible Saturday
</details>

---

## Scenario 4: Third Reading and Final Passage

**Five days have passed. Third Reading vote occurs:**

> **President:** "The Chair lays before the Senate Senate Bill 567 on Third Reading. The bill has been on Third Reading for five calendar days and is now eligible for final passage. The question being on passage of the bill. The Secretary will call the roll."
>
> **Secretary:** [Calls roll of all 38 Senators]
>
> **President:** "Roll call: Yeas 32, Nays 6, Excused 0, Not Voting 0. The bill has passed. Senator Martinez?"
>
> **Senator Martinez:** "Mr. President, I move immediate effect."
>
> **President:** "The question being on immediate effect. The Secretary will call the roll."
>
> **Secretary:** [Calls roll again]
>
> **President:** "Roll call on immediate effect: Yeas 28, Nays 10, Excused 0, Not Voting 0. Immediate effect is granted. The bill is ordered to the House."

### Questions:

1. How many votes did the bill receive for passage?
2. Did the bill pass?
3. How many votes are needed for passage?
4. How many votes did immediate effect receive?
5. Was immediate effect granted?
6. How many votes are needed for immediate effect?
7. What happens next?
8. What should you code?

<details>
<summary><strong>Answer Key</strong></summary>

### Answers:

1. **Passage votes:** 32 Yeas, 6 Nays
2. **Did it pass:** YES (needs 20, got 32)
3. **Votes needed for passage:** 20 (majority of 38)
4. **Immediate effect votes:** 28 Yeas, 10 Nays
5. **IE granted:** YES (needs 26, got 28)
6. **Votes needed for IE:** 26 (2/3 of 38)
7. **Next step:** Bill sent to House for House process
8. **Code:**
   - SB 567 - Third Reading
   - Five-day rule satisfied (5 calendar days passed)
   - Final passage vote: Roll call
     - Yeas 32, Nays 6, Excused 0, Not Voting 0
     - Result: **PASSED**
   - Immediate effect vote: Roll call
     - Yeas 28, Nays 10, Excused 0, Not Voting 0
     - Result: **IMMEDIATE EFFECT GRANTED**
   - Status: Sent to House

### Key Learning Points:
- Third Reading is always roll call (individual votes recorded)
- 20 votes needed for passage
- 26 votes needed for immediate effect
- Immediate effect is separate vote after passage
- Bill can pass but IE can fail (bill still becomes law, just takes effect later)
- In this case, both passed
- Bill now goes to House for House process
</details>

---

## Scenario 5: Immediate Effect Denied

**Different scenario - Third Reading vote:**

> **President:** "Third Reading of Senate Bill 789. The question being on passage of the bill. The Secretary will call the roll."
>
> [Roll call occurs]
>
> **President:** "Roll call: Yeas 30, Nays 8, Excused 0, Not Voting 0. The bill has passed. Senator Lee?"
>
> **Senator Lee:** "Mr. President, I move immediate effect."
>
> **President:** "The question being on immediate effect. The Secretary will call the roll."
>
> [Roll call occurs]
>
> **President:** "Roll call on immediate effect: Yeas 24, Nays 14, Excused 0, Not Voting 0. Immediate effect is denied. The bill is ordered to the House."

### Questions:

1. Did SB 789 pass the Senate?
2. Was immediate effect granted?
3. What does this mean for when the law takes effect?
4. Does the bill still go to the House?
5. What should you code?

<details>
<summary><strong>Answer Key</strong></summary>

### Answers:

1. **Did it pass:** YES - got 30 votes (needs only 20)
2. **IE granted:** NO - got only 24 votes (needs 26)
3. **When law takes effect:** If Governor signs, law will take effect **90 days after the Legislature adjourns for the year** (sine die). Does NOT take effect immediately.
4. **Goes to House:** YES - bill still proceeds normally. IE denial doesn't kill the bill.
5. **Code:**
   - SB 789 - Third Reading
   - Final passage: PASSED
     - Yeas 30, Nays 8, Excused 0, Not Voting 0
   - Immediate effect: **DENIED**
     - Yeas 24, Nays 14, Excused 0, Not Voting 0
     - (Needed 26, got only 24)
   - Status: Sent to House
   - Note: Law will take effect 90 days after sine die (not immediately)

### Key Learning Points:
- Bill can pass but immediate effect can fail
- This happens fairly often (easier to get 20 than 26)
- Bill is NOT killed by IE denial
- Bill still goes to House and can become law
- Only difference: effective date (immediate vs. 90 days later)
- Some Senators vote FOR passage but AGAINST immediate effect (want law but not right away)
</details>

---

## Scenario 6: House Amendments and Concurrence

**House message and Senate response:**

> **President:** "The Chair lays before the Senate a message from the House of Representatives. The Secretary will read the message."
>
> **Secretary:** "Message from the House: Mr. President, the House has passed Senate Bill 567 with amendments. The House amendments are as follows: Amendment 1 changes the small business definition to include businesses with 50 or fewer employees instead of 100. Amendment 2 adds a sunset provision requiring the program to be reauthorized after three years."
>
> **President:** "The bill is before the Senate for concurrence in the House amendments. The Senator from the 15th District is recognized."
>
> **Senator Martinez:** "Thank you, Mr. President. I have reviewed the House amendments. While I would have preferred to keep the 100-employee threshold, the 50-employee limit is acceptable and ensures the program targets truly small businesses. The three-year sunset is reasonable. I move the Senate concur in the House amendments to Senate Bill 567."
>
> **President:** "The question being on concurrence in the House amendments to Senate Bill 567. The Secretary will call the roll."
>
> [Roll call occurs]
>
> **President:** "Roll call: Yeas 24, Nays 14, Excused 0, Not Voting 0. The Senate concurs in the House amendments. The bill is ordered enrolled and sent to the Governor."

### Questions:

1. What did the House do to SB 567?
2. What were the House amendments?
3. What motion did Senator Martinez make?
4. What was the vote result?
5. What happens next?
6. What should you code?

<details>
<summary><strong>Answer Key</strong></summary>

### Answers:

1. **House action:** House passed SB 567 with amendments (changed the bill)
2. **House amendments:**
   - Amendment 1: Changed small business definition from 100 employees → 50 employees
   - Amendment 2: Added 3-year sunset (program must be reauthorized)
3. **Motion:** Senator Martinez moved to **concur** in House amendments
4. **Vote result:** 24-14, Senate CONCURRED (needs 20, got 24)
5. **Next step:** Bill enrolled and sent to Governor (both chambers have now passed identical version)
6. **Code:**
   - Message from House: House passed SB 567 with amendments
   - House amendments:
     1. Small business definition: 100 employees → 50 employees
     2. Added 3-year sunset provision
   - Senate action: Motion to concur
   - Vote: Roll call - Yeas 24, Nays 14, Excused 0, Not Voting 0
   - Result: **SENATE CONCURRED**
   - Status: Bill enrolled and sent to Governor

### Key Learning Points:
- Concurrence requires 20 votes (simple majority)
- When Senate concurs, both chambers have passed identical version
- Bill goes straight to Governor (no conference committee needed)
- Sponsor may not like House amendments but accept them to move bill forward
- Once concurred, Senate is done with bill (now up to Governor)
</details>

---

## Scenario 7: Non-Concurrence and Conference Committee

**Different scenario with House amendments:**

> **President:** "The Chair lays before the Senate a message from the House. The House has passed Senate Bill 890 with amendments. The House amendments reduce funding from $100 million to $60 million and change the distribution formula significantly. The Senator from the 8th District?"
>
> **Senator Johnson:** "Mr. President, I appreciate the House's work on this bill, but the $60 million funding level is insufficient to achieve the bill's goals. The original $100 million was based on careful analysis. Additionally, the House's distribution formula would disadvantage rural areas. I move the Senate non-concur in the House amendments to Senate Bill 890 and request a Conference Committee be appointed."
>
> **President:** "The question being on non-concurrence in the House amendments. All in favor say 'aye.' All opposed say 'no.' In the opinion of the Chair, the ayes have it. The Senate non-concurs. The motion for a Conference Committee is in order."
>
> **Senator Johnson:** "I so move, Mr. President."
>
> **President:** "The motion is made. Without objection, a Conference Committee is requested. The Chair appoints Senators Johnson, Lee, and Davis as conferees. A message will be sent to the House."

### Questions:

1. What did Senator Johnson move?
2. Why did he move to non-concur?
3. What vote was taken on non-concurrence?
4. What happened after non-concurrence?
5. Who are the Senate conferees?
6. What happens next?
7. What should you code?

<details>
<summary><strong>Answer Key</strong></summary>

### Answers:

1. **Motion:** Senator Johnson moved to **non-concur** in House amendments
2. **Reason:** Funding too low ($60M vs. $100M) and distribution formula disadvantages rural areas
3. **Vote:** Voice vote, Senate non-concurred
4. **After non-concur:** Conference Committee requested and appointed
5. **Senate conferees:** Senators Johnson, Lee, and Davis (3 Senators)
6. **Next steps:**
   - House will appoint 3 Representatives as conferees
   - 6-member Conference Committee will negotiate compromise
   - Committee will produce Conference Report
   - Both chambers must vote on Conference Report
7. **Code:**
   - Message from House: House passed SB 890 with amendments
   - House amendments:
     - Reduced funding: $100M → $60M
     - Changed distribution formula
   - Senate action: Motion to non-concur
   - Vote: Voice vote
   - Result: **SENATE NON-CONCURRED**
   - Conference Committee requested
   - Senate conferees appointed: Johnson, Lee, Davis
   - Status: Awaiting House appointment of conferees

### Key Learning Points:
- Non-concurrence is appropriate when House amendments are unacceptable
- Usually leads to Conference Committee (negotiation)
- Senate appoints 3 conferees (usually sponsor + committee chair + minority member)
- House will appoint 3 conferees (total 6)
- Conference Committee will negotiate compromise
- Both chambers must approve Conference Report for bill to proceed
- Non-concurrence doesn't kill bill - it's negotiation tactic
</details>

---

## Scenario 8: Adopting Conference Report

**Conference Committee has completed work:**

> **President:** "The Chair lays before the Senate the Conference Report on Senate Bill 890. The Senator from the 8th District?"
>
> **Senator Johnson:** "Thank you, Mr. President. The Conference Committee met several times and produced a compromise. The Conference Report sets funding at $80 million, splitting the difference between the Senate's $100 million and the House's $60 million. The distribution formula uses a hybrid approach that addresses both urban and rural needs. I believe this is a fair compromise that allows the bill to move forward. I move the Senate adopt the Conference Report on Senate Bill 890."
>
> **President:** "The Senator from the 22nd District?"
>
> **Senator Lee:** "As a conferee, I support the Conference Report. It's not perfect, but it achieves the bill's core objectives."
>
> **President:** "The question being on adoption of the Conference Report on Senate Bill 890. The Secretary will call the roll."
>
> [Roll call occurs]
>
> **President:** "Roll call: Yeas 26, Nays 12, Excused 0, Not Voting 0. The Senate adopts the Conference Report. A message will be sent to the House."

**[Next day]**

> **President:** "The Chair has received a message from the House. The House has adopted the Conference Report on Senate Bill 890. The bill is ordered enrolled and sent to the Governor."

### Questions:

1. What did the Conference Committee do?
2. What was the compromise?
3. What was the Senate vote on the Conference Report?
4. What did the House do?
5. What happens next?
6. Can either chamber amend the Conference Report?
7. What should you code?

<details>
<summary><strong>Answer Key</strong></summary>

### Answers:

1. **Conference Committee:** Negotiated compromise between Senate version ($100M) and House version ($60M)
2. **Compromise:**
   - Funding: $80 million (split the difference)
   - Distribution: Hybrid formula (addresses urban and rural needs)
3. **Senate vote:** 26-12, Senate ADOPTED Conference Report
4. **House action:** House adopted Conference Report
5. **Next step:** Bill enrolled and sent to Governor (both chambers passed identical Conference Report version)
6. **Amendments to CR:** NO - Conference Reports cannot be amended. Must be adopted or rejected as written.
7. **Code:**

**Conference Report on SB 890:**
- Conference Committee compromise:
  - Funding: $80 million
  - Distribution formula: Hybrid approach
- Senate vote: Motion to adopt Conference Report
  - Roll call: Yeas 26, Nays 12, Excused 0, Not Voting 0
  - Result: **SENATE ADOPTED CONFERENCE REPORT**
- Message from House: House adopted Conference Report
- Status: Bill enrolled and sent to Governor
- Note: Both chambers have now passed identical version (Conference Report)

### Key Learning Points:
- Conference Reports are compromises negotiated by 6-member committee
- Cannot be amended - up or down vote only
- Requires majority in each chamber (20 in Senate, 56 in House)
- Both chambers must adopt for bill to proceed
- Once both adopt, bill goes to Governor
- Conference Committee process can take days, weeks, or months
- Compromise often splits differences or finds creative solutions
</details>

---

## Quick Coding Challenge

**Code the following rapid-fire sequence (like a busy floor session):**

> "Senate Bill 111 on General Orders. Senator Smith offers Floor Amendment 1. Voice vote. Amendment adopted. Senator Jones moves to advance to Third Reading. Motion carried."
>
> "Third Reading of Senate Bill 23. Roll call: Yeas 21, Nays 17. Bill passed. Immediate effect? Yeas 27, Nays 11. Immediate effect granted."
>
> "Message from House: House passed Senate Bill 456 with amendments. Senator Lee moves non-concurrence. Voice vote. Senate non-concurs. Conference Committee requested. Chair appoints Senators Lee, Martinez, Johnson as conferees."

<details>
<summary><strong>Answer Key - What You Should Have Coded</strong></summary>

**SB 111:**
- General Orders
- FA 1 (Sen. Smith): Adopted (voice vote)
- Moved to Third Reading: Carried

**SB 23:**
- Third Reading
- Passage: PASSED (21-17)
- Immediate effect: GRANTED (27-11)

**SB 456:**
- House passed with amendments
- Senate: NON-CONCURRED (voice vote)
- Conference Committee requested
- Senate conferees: Lee, Martinez, Johnson

### Speed Check:
If you coded all of this accurately in under 2 minutes, you're ready for real-time floor work!
</details>

---

## Key Takeaways from Practice Scenarios

✅ Committee reports: Note committee, action, amendments, next referral  
✅ General Orders: Track all amendments (number, sponsor, vote, result)  
✅ Third Reading: Record exact vote counts for passage and immediate effect  
✅ 20 for passage, 26 for immediate effect  
✅ House messages: Note what House did (passed as is / with amendments / defeated)  
✅ Concurrence: Senate accepts or rejects House amendments  
✅ Conference Committee: 3+3 negotiators, report cannot be amended  
✅ Speed and accuracy matter - floor moves fast!  

---

## Navigation
**Back to:** [Course Home](../README.md)

---

*Last Updated: January 2026 for 2025-2026 Legislative Session*
