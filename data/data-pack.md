# Practice data pack: BU Pay & Credit, first consumer card

**Sample data, illustrative, not Riverty research. All people, numbers and events are fictional.**

Fictional evidence for the case brief "Riverty's First Consumer Card". It imagines a friends-and-family test launch in Germany with 1,200 invited people over four months. Use it where a lab needs notes, tickets, metrics or a backlog. Do not present these figures as Riverty facts.

## Interview and research notes (Module 2, Exercise 1)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

- **N-01, consumer, heavy BNPL user, 25-34:** "I use pay later for almost everything online. Not because I am short of money. I just want it to leave my account after I keep the item."
- **N-02, consumer, heavy BNPL user, 25-34:** "I already have two of these apps. A third card is one more thing to check before payday."
- **N-03, consumer, regular BNPL user, 35-44:** "In a shop I tap my bank card without thinking. I would have to remember this card exists."
- **N-04, consumer, heavy BNPL user, 18-24:** "If it worked at the supermarket I would use it every day. I would like to split the big weekly shop."
- **N-05, consumer, light BNPL user, 45-54:** "A credit card with interest is exactly what I try to avoid. If it says instalments I get nervous."
- **N-06, consumer, test launch participant:** "The card was declined at a bakery and the app did not say why. I went back to my debit card the same week."
- **N-07, consumer, test launch participant:** "I could not see in one place what I owe on the card and what I owe on my normal pay later orders."
- **N-08, enterprise merchant, ecommerce lead:** "If your card pays at every shop, why would my customers still pick you at my checkout? Show me what I get."
- **N-09, SME merchant, owner:** "We joined for the checkout option. If the card came with offers that send people to us, that is interesting. If it sends them to big marketplaces, it is not."
- **N-10, internal, risk:** "The test group is mostly colleagues. Their approval and repayment numbers will look better than real customers."
- **N-11, internal, operations:** "Every proposition change goes back through approval for pricing, credit policy and terms. That takes months. Plan scope with that in mind."
- **N-12, consumer, regular BNPL user, 25-34:** "Cashback would make me try it. Whether I keep using it is a different question."

## Tickets and bugs from the test launch (Module 2, Exercise 1)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

- **T-101, bug:** In-store payment declined with no reason shown in the app. 48 in-store declines in the test log.
- **T-102, bug:** Adding the card to the phone wallet fails or is abandoned after activation. 143 activated cards never reached the wallet.
- **T-103, ticket:** Card balance and regular pay later orders shown on two different screens. Participants ask which total is the real one.
- **T-104, ticket:** Statement date and pay later due dates differ. Two reminders arrive in the same week for different amounts.
- **T-105, bug:** Instalment option appears after the purchase only for some categories. Participants think it is random.
- **T-106, ticket:** Identity check asks for a document photo again after a failed upload. Some applicants give up at this step.
- **T-107, ticket:** Participants ask whether using the card affects their credit score. No help article exists yet.
- **T-108, bug:** Push notification for a purchase arrives minutes late in some shops, so participants think the payment failed and pay again with another card.

## Funnel: where people drop (Module 3)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

| step | people | pct_of_previous_step | pct_of_invited |
|---|---|---|---|
| invited | 1200 | 100.0 | 100.0 |
| applied | 716 | 59.7 | 59.7 |
| identity_check_completed | 628 | 87.7 | 52.3 |
| approved | 586 | 93.3 | 48.8 |
| card_activated | 431 | 73.5 | 35.9 |
| first_purchase_in_activation_month | 350 | 81.2 | 29.2 |
| three_plus_purchases_in_activation_month | 253 | 72.3 | 21.1 |

Added to phone wallet is not a funnel step because online purchases do not need it. See metric_baselines.csv. Full list: pilot_participants.csv.

## Change over time: monthly trend (Module 3)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

| pilot_month | active_cards | purchases | volume_eur | avg_spend_per_active_card_eur | in_store_share_of_purchases_pct | partner_merchant_share_of_volume_pct | instalments_share_of_purchases_pct | decline_rate_pct | in_store_decline_rate_pct |
|---|---|---|---|---|---|---|---|---|---|
| Month 1 | 76 | 290 | 15206.91 | 200.09 | 17.6 | 56.8 | 15.2 | 2.7 | 12.1 |
| Month 2 | 174 | 723 | 38284.38 | 220.03 | 15.4 | 63.0 | 16.5 | 2.2 | 7.5 |
| Month 3 | 278 | 1162 | 58837.34 | 211.65 | 17.7 | 58.8 | 18.1 | 2.6 | 6.4 |
| Month 4 | 262 | 1107 | 61085.73 | 233.15 | 17.0 | 63.1 | 17.4 | 3.5 | 8.7 |

## Change over time: activity by activation month (Module 3)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

| activation_month | cards_activated | pct_active_month_0 | pct_active_month_1 | pct_active_month_2 | pct_active_month_3 |
|---|---|---|---|---|---|
| Month 1 | 98 | 77.6 | 66.3 | 51.0 | 55.1 |
| Month 2 | 133 | 82.0 | 69.2 | 57.1 |  |
| Month 3 | 161 | 84.5 | 64.0 |  |  |
| Month 4 | 39 | 74.4 |  |  |  |

Share of cards activated in that month that made at least one purchase k months later. Blank means not yet observable.

## User split (Module 3)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

| dimension | segment | invited | approved | activated | activation_rate_of_approved_pct | purchases_per_active_month | avg_monthly_spend_eur | in_store_share_pct | partner_merchant_share_of_volume_pct | instalments_share_pct |
|---|---|---|---|---|---|---|---|---|---|---|
| bnpl_use | heavy | 350 | 167 | 138 | 82.6 | 5.82 | 320.88 | 12.1 | 68.1 | 25.4 |
| bnpl_use | light | 354 | 158 | 98 | 62.0 | 2.46 | 125.13 | 24.5 | 52.1 | 6.0 |
| bnpl_use | regular | 496 | 261 | 195 | 74.7 | 3.91 | 200.2 | 19.3 | 56.3 | 12.7 |
| relation | employee | 639 | 352 | 253 | 71.9 | 4.12 | 222.17 | 17.7 | 61.9 | 17.2 |
| relation | friend_or_family | 561 | 234 | 178 | 76.1 | 4.2 | 215.69 | 15.9 | 59.8 | 17.3 |
| age_band | 18-24 | 132 | 70 | 51 | 72.9 | 4.34 | 227.02 | 18.4 | 62.1 | 18.9 |
| age_band | 25-34 | 453 | 220 | 157 | 71.4 | 4.37 | 235.75 | 14.8 | 61.3 | 18.3 |
| age_band | 35-44 | 352 | 173 | 126 | 72.8 | 3.9 | 202.58 | 17.8 | 61.5 | 16.4 |
| age_band | 45-54 | 174 | 80 | 65 | 81.2 | 4.25 | 222.99 | 20.0 | 60.9 | 14.2 |
| age_band | 55+ | 89 | 43 | 32 | 74.4 | 3.67 | 190.75 | 16.0 | 56.8 | 18.6 |

Row-level purchases: card_transactions.csv.

## Test launch rates (Module 3 and Module 5)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

| metric | test_launch_observation | note |
|---|---|---|
| approval rate | 93.3% of completed identity checks | pilot invitees are mostly employees, so this may run high |
| activation rate | 73.5% of approved |  |
| spend per active card | about EUR 2,595 a year if the pilot monthly average held | a 12x extrapolation of four months |
| share of existing users who would take a card | not measurable in an invite-only test | state your own assumption |
| annual churn | not measurable in 4 months | state your own assumption |

Fictional test launch values. Where a rate is not measurable, state your own assumption.

## Backlog to score (Module 4)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

| feature_id | feature | value_1_to_5 | effort_1_to_5 |
|---|---|---|---|
| B1 | Decline reason and retry hint shown in the app |  |  |
| B2 | Add to phone wallet straight from the approval screen |  |  |
| B3 | One balance view for card and regular pay later orders |  |  |
| B4 | Choose pay now or pay later per purchase after paying |  |  |
| B5 | Offers from partner merchants inside the card app |  |  |
| B6 | Cashback on every purchase |  |  |
| B7 | Physical card |  |  |
| B8 | One due date for card and pay later orders |  |  |

Value and effort are blank on purpose. Add features from your own labs if you need them.

## Baseline rates (Module 5)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

| metric | baseline_pct | measured_over | base_count |
|---|---|---|---|
| approved to activated | 73.5 | approved people | 586 |
| activated to added to phone wallet | 66.8 | activated cards | 431 |
| activated to first purchase in activation month | 81.2 | activated cards | 431 |
| in-store share of purchases, Month 4 | 17.0 | purchases in Month 4 | 1107 |
| in-store decline rate, Month 4 | 8.7 | in-store attempts in Month 4 | 206 |
| partner merchant share of volume, Month 4 | 63.1 | card volume in Month 4 |  |
| instalments share of purchases, Month 4 | 17.4 | purchases in Month 4 | 1107 |

## Audience sizes (Module 6)

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._

| audience | size | source |
|---|---|---|
| German Riverty BNPL users in scope (ASSUMED practice figure) | 1000000 | assumed |
| share of the base: heavy users, 4+ orders a month (ASSUMED 30%) | 300000 | assumed |
| share of the base: use the Riverty app monthly (ASSUMED 35%) | 350000 | assumed |
| share of the base: opted in to marketing email (ASSUMED 40%) | 400000 | assumed |
| share of the base: allow app push messages (ASSUMED 25%) | 250000 | assumed |
| SME and mid-size partner merchants in Germany | not in brief | open: estimate it and state your assumption |

Every number here is an assumed practice figure or open. Each share is taken from the base in the first row, not from the row above.

_Sample data, illustrative, not Riverty research. All people, numbers and events are fictional._
