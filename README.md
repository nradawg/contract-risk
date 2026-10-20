# Contract Risk

**Paste this URL into any AI chat and it runs. No install, no key.**

```
Read https://raw.githubusercontent.com/nradawg/contract-risk/main/README.md and run it on me.
```

---


**Use this when** an agreement is in front of you and you need to know which
clauses will actually cost you, in plain words, before you sign or send it.

This is a reading aid, not legal advice, and it says where that line is.

## What I read for, in cost order

**Money and exit.** Most of the real losses come from these four.

- Term and renewal. Does it auto renew, how much notice gets you out, and from
  which date is that notice counted. A missed notice window is the most common
  way people pay for a year they did not want.
- Termination. Can either side leave for convenience, with what notice, and is
  that right mutual or one way.
- Payment. When due, late interest, who pays collection or legal costs.
- Scope and change. What is out of scope, who approves a change order, what
  happens when the work grows. No change process means growth is free to them.

**Risk transfer.** Smaller print, larger numbers.

- Indemnification. Who defends whom, for what, and whether it runs both ways.
- Limitation of liability. Is there a cap, what is it tied to (often fees paid
  in the last 12 months), is it mutual, and what is carved out of it.
- Insurance you are required to carry. A real monthly cost, so it is a price
  term, not boilerplate.

**Ownership.** Who owns the work and when it transfers, which should be on full
payment. Rights to your own tools, templates, and portfolio use. How long
confidentiality runs, and whether it is mutual. Non compete and non solicit get
flagged with the lookup rather than a verdict, because enforceability is state
law, it is contested, and it has changed recently.

**Process.** Governing law and venue, since a dispute two time zones away costs
you even when you win. Arbitration, class action waiver, and who pays the
arbitrator. Assignment and change of control, meaning whether you can be handed
to whoever buys them.

## The absent clause pass

This is the step that gets skipped, and it finds more money than the clause by
clause read. A missing liability cap, missing payment terms, missing late fee,
missing kill fee, missing IP transfer on payment, missing acceptance criteria.
Silence usually defaults against the smaller party, so the output lists what is
not in the document.

## The terms are often not in the clauses

A friendly clause can be gutted by how one capitalized word is defined, so read
the defined terms. The exhibits, order form, and statement of work override the
body more often than people expect. And flag every clause that points at a web
page, any "as set out in our then current policy at <url>", because that is a
term the other side can change after you sign.

## How each flag reads

The clause and its section number, what it means in plain words, what it would
cost you, a verdict of `CHANGE THIS` with the ask, `PRICE IT IN`, or `FINE`, and
a label: `CHECKED` quoted from the document, `FROM YOU` your deal context,
`GUESSED` where I inferred intent.

## What you see

```
CONTRACT RISK: client services agreement, 14 pages

CHANGE THIS
 s4.2  Auto renews for 12 months unless cancelled 90 days before
       the anniversary. CHECKED, quoted.
       Plain words: forget once and you owe another full year.
       Ask for 30 days, or renewal by mutual written agreement.

 s9    Indemnity runs one way, you defend them, including their
       legal fees, with no cap. CHECKED.
       Plain words: one claim can exceed everything the contract
       pays you. This is the clause to fight.
       Ask for mutual indemnity and tie it to the liability cap.

 ABSENT  No limitation of liability anywhere in the document.
       Searched all 14 pages and both exhibits. CHECKED.
       Plain words: your exposure is unbounded. More dangerous
       than a bad cap would be.
       Ask for fees paid in the prior 12 months, mutual.

PRICE IT IN
 s6.1  You carry $2M general liability and name them as additional
       insured. CHECKED. Quote that before you agree to the rate.
 s11   Venue is their state, two time zones away. CHECKED.

WATCH
 s5.3  Points to "the then current support policy" at a URL.
       CHECKED. They can change this after you sign. Ask to attach
       today's version as an exhibit.

FINE
 s7    IP transfers on receipt of full payment. CHECKED.

GET A LAWYER ON  s9 and the missing cap, because uncapped
indemnity is outside what a reading aid settles. 7 flags, 0 guessed.
```

## Where a lawyer is not optional

Equity or ownership, a personal guarantee, an uncapped indemnity, a non compete
you intend to rely on, regulated data such as health, payment, or minors, cross
border terms, and anything where losing costs more than you can write a cheque
for. Say that number out loud and decide against it.

## Limits

**The trap.** The naive version flags scary sounding boilerplate, misses the
clause that is not there, and states enforceability as settled when it is state
law and currently contested. Confident legal conclusions are the failure mode
here, not missed clauses.

It reads the text you give it. Not the exhibits you did not paste, not the master
agreement this order form hangs off, not your law, and not what a court did last
month. It says a clause is worth asking about, never that it is enforceable.

---

## How this one knows what it knows

Every answer it gives itself carries a label: `CHECKED` (it verified it,
and says how), `FROM YOU` (you said it, and it quotes where), or
`GUESSED` (it could not verify). Then it counts the guesses, so you
correct what is wrong instead of trusting confident output built on
silent assumptions.

> Never ask for something you can check.
> Never assume something you cannot check.

One of 48 skills. The rest, and the house rules: [https://github.com/nradawg/assume-nothing](https://github.com/nradawg/assume-nothing)

MIT.
