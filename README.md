# Illuminati-Consulting-Case-Exam
# Dealer Attention Engine

**Case:** Which dealers need management attention?
**Submitted by:** Shobali

## Which dealers need attention, why, and what to do about it

Dealers are judged on sales against target. That number reports trouble late
and often blames the wrong dealer. This engine turns data the manufacturer
already owns into a ranked list of dealers to act on, each with one named
cause, one action and one owner.

## Submission

| What | Where |
|---|---|
| 1.5 minute video | https://youtu.be/6PoAAg2dsD0 |
| Business solution and logic | Dealer_Attention_Engine_Data_to_Decision.pdf |
| Working prototype | Dealer_Attention_Engine_Prototype.ipynb |

## The prototype

A Python notebook that runs the full chain: data, metrics, signals, diagnosis,
decision. It is already executed, so all outputs are visible without running
anything. It needs no external files and no internet, only pandas and numpy.

Tested on 48 dealers over 24 months with problems planted in the data, so the
notebook measures whether the engine finds what is actually there.

## Data

Finance and inventory fields are a labelled representative extract: the schema
and source systems are real, the values are not a client's. Market data follows
published FADA and VAHAN grain. Every number in the engine is tagged Published,
Derived, Contractual or Calibrated, with its owner named.
