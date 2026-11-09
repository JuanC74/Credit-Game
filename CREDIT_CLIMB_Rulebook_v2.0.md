# CREDIT CLIMB: OFFICIAL TOURNAMENT RULEBOOK
**Version 2.0 (Comprehensive Adjudicated Edition)**

---

## 1. OBJECTIVE & GOLDEN RULES

### 1.1 Objective
In **Credit Climb**, players navigate the volatile modern financial system by managing revolving debt, acquiring income-generating asset classes, maintaining high credit capacity, and building an optimal Credit Rating. 

The game concludes when the **Market Crash** card is drawn from the Market Event Deck. The player who has accumulated the highest **Final Portfolio Score** at the moment of the crash is declared the winner.

### 1.2 The Golden Rules
1. **Rulebook Hierarchy:** If the text on an Asset Card, History Card, or Market Event Card directly contradicts this Rulebook, the card text takes precedence.
2. **Hardware & Score Bounds:** A player’s Credit Score Dial is bounded between a minimum floor of **300** and a maximum ceiling of **850**. Any game effect, bonus, or penalty that would push a player’s score above 850 or below 300 is truncated at that boundary.
3. **Discrete Financial Units:** All currency transactions are denominated in increments of $100. Debt is represented in discrete units: **1 Red Cube = $100 of Principal Debt**. Debt cannot be taken, placed, or paid off in fractional units (less than 1 full Red Cube / $100).
4. **Finite Capacity:** A player may never place more Red Cubes on a card than that card's printed Capacity Boxes. Over-limit debt is strictly illegal.

---

## 2. COMPONENTS

* **1 Game Board** (featuring a perimeter track with GO, Asset Spaces, Expense Spaces, and Market Event Spaces)
* **2 Six-Sided Movement Dice (d6)**
* **5 Player Tokens** (representing financial archetypes)
* **15 Score Dials** (3 dials per player: Hundreds, Tens, Units; tracking 300 to 850)
* **2 Ledger Pads** (50 double-sided monthly audit sheets)
* **5 Starter Credit Cards** (Initial revolving credit line with 10 Capacity Boxes = $1,000 capacity)
* **20 History Cards** (Background identities providing unique starting parameters)
* **150 Asset Cards** divided across 4 tiers:
  * Green Tier (Entry-level retail credit & bonds)
  * Blue Tier (Mid-tier prime revolving accounts & equities)
  * Gold Tier (Premium corporate credit & real estate)
  * Brown Tier (Alternative assets & distressed debt lines)
* **50 Market Event Cards** (including 1 distinct **Market Crash** endgame card)
* **100 Red Cubes** (Debt & Utilization Markers; each cube represents $100)
* **30 Late Tokens** (Black delinquency markers; -20 score penalty per token)
* **Bank Currency Supply** (bills in denominations of $100, $500, $1,000, $5,000, and $10,000)

---

## 3. SETUP

1. **The Banker:** Select one player to act as the Banker. The Banker manages the Bank’s cash reserves, unowned Asset Cards, Red Cubes, and Late Tokens. If the Banker is also a player, they must keep their personal funds strictly separate from Bank funds.
2. **Starting Capital:** The Banker issues each player **$2,000 in Cash** comprised of:
   * 1x $1,000 bill
   * 1x $500 bill
   * 5x $100 bills
3. **The Credit Ledger & Dials:** Each player receives one Ledger Sheet and one 3-dial Score Tracker. Set all score dials to an initial **Credit Score of 670**.
4. **Starter Account:** Each player receives **1 Starter Credit Card** face-up in their personal play area. This card has a starting limit of **10 Capacity Boxes** ($1,000 capacity) and begins with **0 Red Cubes** (zero debt).
5. **Identity & Credit History:** 
   * Shuffle the deck of 20 History Cards.
   * Deal 1 History Card face-up to each player. 
   * Immediately resolve any starting conditions printed on the card (e.g., student debt placed as Red Cubes on the card, starting score adjustments, or supplemental cash).
6. **Deck Preparation:**
   * Shuffle the Asset Cards and place them face-down next to the board as the Asset Draw Deck.
   * Separate the **Market Crash** card from the Market Event Cards. Shuffle the remaining 49 Event Cards.
   * Count out the bottom **12 cards** (approximately 25% of the deck). Shuffle the **Market Crash** card together with these 12 cards, and place this 13-card stack at the bottom of the Market Event Deck. Place the Event Deck face-down on its designated board space.
7. **Token Placement & Turn Order:**
   * Place all player tokens on the **GO** space.
   * Each player rolls the two dice. The player with the highest total is the First Player. Ties are re-rolled among tied players. Play proceeds clockwise around the table.

---

## 4. THE TURN CYCLE

The game is played over a series of simulated financial months. On their turn, the active player must resolve the following **4 Phases in strict sequential order**:

```
[ Phase 1: The Statement ] ➔ [ Phase 2: Movement ] ➔ [ Phase 3: Transaction ] ➔ [ Phase 4: The Audit ]
```

---

### PHASE 1: THE STATEMENT (Upkeep & Debt Service)
The active player reviews all Red Cubes across their active cards and resolves debt service:

1. **Calculate Interest:** Count the total number of Red Cubes across all cards in your play area. Each cube represents $100 in debt. You must pay **$10 per cube in Interest** to the Bank.
   * *Quantization Rule:* Interest must be paid in full using Bank cash. If your total interest payment is not a multiple of $100, round **UP** to the nearest $100 increment (e.g., 3 cubes = $30 interest, rounded up to $100; 10 cubes = $100; 12 cubes = $120 interest, rounded up to $200).
2. **Late Penalty (Default):** If you do not have sufficient cash to pay your full interest obligation:
   * Pay all available cash toward interest.
   * Immediately take **1 Late Token**. Deduct **20 points** from your Credit Score Dial immediately.
   * The unpaid balance is capitalized: add **1 Red Cube** to your available credit card capacity. If you have no open capacity boxes to hold this cube, proceed immediately to the **Insolvency & Bankruptcy** procedure (Section 5.3).
3. **Pay Principal (Optional):** You may spend cash from your hand to pay down principal debt at a rate of **$100 Cash per 1 Red Cube removed**. Return removed cubes to the Bank supply. You may pay down any number of whole cubes up to your available cash.
4. **Curing Delinquencies (Optional):** If you possess any Late Tokens, you may pay a **$200 Delinquency Fee** per token to the Bank to discard that Late Token. *Note: Discarding a Late Token restores eligibility for the GO bonus, but does not retroactively restore lost dial points.*

---

### PHASE 2: MOVEMENT

1. **Roll & Move:** The active player rolls both dice and advances their token clockwise around the board that exact number of spaces.
2. **Passing or Landing on GO:** 
   * Each time a player’s token lands on or passes the **GO** space during movement, the player collects a **$200 Salary** from the Bank.
   * **Clean Record Bonus:** If the player currently has **zero Late Tokens** in their play area at the time of passing or landing on GO, they immediately increase their Credit Score Dial by **+20 points** (subject to the 850 ceiling). If the player holds one or more Late Tokens, this bonus is forfeited for this pass.

---

### PHASE 3: TRANSACTION
The active player must resolve the space upon which their token landed:

#### A. Asset Space (Revolving Lines & Investment Accounts)
* **If Unowned:** The active player may choose to apply for the Asset Card:
  1. *Credit Score Check:* The player's current dial score must meet or exceed the space's printed Minimum Credit Rating.
  2. *Hard Inquiry Penalty:* If applied for, the player immediately reduces their Credit Score Dial by **-5 points** (simulating a credit check), regardless of whether the purchase is completed.
  3. *Acquisition Fee:* Pay the printed Purchase Cost (or Account Setup Fee) in Cash to the Bank.
  4. *Claim Card:* Take the corresponding Asset Card from the bank. Place it face-up in your play area. Its printed **Capacity Boxes** immediately expand your **Total Credit Capacity**.
  5. *Decline:* If the player chooses not to apply or cannot afford the fee/score check, nothing happens. The space remains unowned.
* **If Owned by an Opponent:** The active player must pay a **$100 Transaction / Interbank Fee** to the owner. If owned by the active player, no fee is paid.

#### B. Expense Space (Unplanned Life Events & Bills)
The player must settle the exact expense amount indicated on the space (e.g., *"Emergency Medical Bill: $500"*):
* **Payment Method:** The player may pay using **Cash**, **Revolving Credit**, or any combination thereof:
  * *Cash:* Pay bills directly to the Bank.
  * *Credit:* Place 1 Red Cube onto an empty Capacity Box on any active card for each $100 charged.
* **Insufficient Funds / Over-Limit:** If the player cannot cover the full expense via Cash and available empty Capacity Boxes combined, they must pay all available cash and fill all remaining capacity boxes, then immediately declare **Insolvency** (Section 5.3).

#### C. Market Event Space
Draw the top card of the Market Event Deck and read it aloud.
* **Immediate Resolution:** Execute the card instructions immediately.
* **The Crash Trigger:** If the card drawn is the **Market Crash**, the game terminates immediately. Complete only the current space resolution; do not proceed to Phase 4. Proceed directly to **Section 6: Final Scoring**.
* **Discard:** If the card is not the Market Crash, place it face-up on the Event discard pile.

---

### PHASE 4: THE AUDIT (Credit Utilization Scoring)
At the conclusion of your turn, calculate your **Credit Utilization Ratio**:

$$\text{Credit Utilization} = \left( \frac{\text{Total Red Cubes Currently on All Your Cards}}{\text{Total Capacity Boxes Across All Your Active Cards}} \right) \times 100\%$$

Adjust your Credit Score Dial based on the resulting percentage tier:

| Credit Utilization Tier | Score Adjustment | Effect Description |
| :--- | :---: | :--- |
| **0% Utilization** *(0 Red Cubes)* | **+5 Points** | **Saver's Bonus:** Pristine balance sheet. *(Requires at least 1 Active Card)* |
| **1% – 30% Utilization** | **0 Points** | **Prime Tier:** Optimal, healthy credit management. |
| **31% – 50% Utilization** | **-10 Points** | **Elevated Risk:** Mild over-extension penalty. |
| **51% – 99% Utilization** | **-20 Points** | **High Risk:** Severe debt stress penalty. |
| **100% (Maxed Out)** | **-50 Points** | **Critical Delinquency:** Capital exhaustion penalty. |

*Note: If a player owns zero cards (Total Capacity = 0), their utilization is treated as 0% for scoring purposes.*

---

## 5. LEDGER, DEBT CAPACITY & INSOLVENCY

### 5.1 Total Capacity Management
* A player’s **Total Capacity** is the sum total of all Capacity Boxes printed on their Starter Card, History Card, and all acquired Asset Cards.
* Each single Box accommodates exactly **1 Red Cube ($100 debt)**.
* Cubes placed on a specific card remain on that card until paid off in Phase 1 or cleared via a specific card effect.

### 5.2 Simultaneous Triggers & Priority
If an event or board condition causes simultaneous triggers for multiple players, resolution proceeds in **Clockwise Priority**, beginning with the active player.

### 5.3 Insolvency & Bankruptcy Procedure
If at any point a player is obligated to pay Cash or take on a Red Cube and is completely unable to do so (cash is $0 and all capacity boxes are occupied):
1. **Emergency Asset Liquidation:** The player must surrender Asset Cards to the Bank. The Bank pays the player **50% of the card’s printed purchase price** in cash. Red Cubes on liquidated cards are transferred to any empty boxes on remaining cards; if no boxes exist, they remain as unbacked debt obligations.
2. **Formal Bankruptcy:** If all Asset Cards are liquidated and the player still cannot satisfy the mandatory payment:
   * The player discards all remaining Asset Cards.
   * All Red Cubes are returned to the Bank.
   * The player receives **3 Late Tokens** (-60 points applied immediately to their dial).
   * The player’s Credit Score Dial is reset to the statutory minimum of **400** (or lowered by 60, whichever results in a lower score).
   * The player retains only their Starter Credit Card and continues play.

---

## 6. END OF GAME: THE MARKET CRASH & SCORING

### 6.1 Triggering the Crash
The game ends **the exact moment the Market Crash card is revealed** from the Market Event Deck. 
* Any effects on the Market Crash card itself are resolved.
* No further turns, movement, salary collections, or Phase 4 Audits take place.

### 6.2 Final Portfolio Score Calculation
Each player uses the calculation grid on the bottom of their Ledger Sheet to compute their **Final Portfolio Score**:

$$\begin{aligned}
\textbf{Final Portfolio Score} = \;& \text{Current FICO Dial Score (300–850)} \\
& + \; [\text{Number of Asset Cards Owned} \times 10] \\
& + \; \left\lfloor \frac{\text{Total Cash in Hand}}{100} \right\rfloor \times 1 \\
& - \; [\text{Total Red Cubes Remaining} \times 50] \\
& - \; [\text{Total Late Tokens Possessed} \times 20]
\end{aligned}$$

#### Scoring Breakdown Table
1. **FICO Base Score:** Enter your ending Credit Score Dial value (e.g., 720 pts).
2. **Asset Portfolio Bonus:** +**10 Points** for each Asset Card in your play area.
3. **Cash Liquidity Bonus:** +**1 Point** for every full **$100** of cash in hand (round down).
4. **Debt Default Penalty:** -**50 Points** for every un-cleared **Red Cube** ($100 debt) remaining across all your cards.
5. **Outstanding Delinquency Penalty:** -**20 Points** for each **Late Token** remaining in your possession.

---

### 6.3 Victory & Tie-Breakers
The player with the highest Final Portfolio Score is the winner. In the event of a tie, apply the following tie-breaker hierarchy in order:

1. **Highest Credit Score:** The tied player with the highest final FICO Dial Score wins.
2. **Lowest Debt:** The player with the fewest Red Cubes wins.
3. **Most Liquid Cash:** The player with the greatest cash reserves wins.
4. **Shared Victory:** If players remain tied across all criteria, victory is shared.

---
*(End of Official Rules — Version 2.0)*
