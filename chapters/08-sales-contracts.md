# Chapter 8 — Sales Contracts
*The operating system underneath every deal for goods.*

---

Here is a problem that nearly broke American commerce in the twentieth century, and a statute that fixed it.

In the years before 1952, a business in New York buying equipment from a supplier in California was operating under a patchwork of inconsistent state laws. The rules for forming a contract, what counted as acceptance, what warranties attached to the goods, who bore the risk if the shipment was destroyed in transit — all of these varied by state. A seller in Texas and a buyer in Ohio might not even agree on which state's law governed their transaction, let alone what that law required. For a continental economy trying to function as a single market, this was an increasingly serious operational problem.

The fix was the *Uniform Commercial Code*. A project of the American Law Institute and the National Conference of Commissioners on Uniform State Laws, drafted primarily by Karl Llewellyn of Columbia Law School, completed in 1952 and adopted in substantially every U.S. state in the years that followed. The UCC contains nine substantive articles. The one that governs most commercial transactions between buyers and sellers is *Article 2 — Sales*.

Article 2 is the operating system of U.S. commercial transactions for goods. It applies whether the parties know it or not, whether they mention it in their contract or not, whether they've read it or not. The practitioner who understands it operates with precision; the practitioner who relies on common-law contract intuitions in a goods transaction is flying with an outdated map.

---

## What Article 2 covers — and what it doesn't

The threshold question in any commercial dispute is which legal framework applies. Get this wrong and everything that follows is built on the wrong foundation.

UCC § 2-105 defines *goods* as all things which are movable at the time of identification to the contract for sale, other than money, investment securities, and things in action. In plain terms: manufactured products, agricultural commodities, livestock, vehicles, raw materials, equipment — anything tangible that can be picked up and moved. If you're buying widgets, Article 2 governs. If you're buying legal advice, Article 2 does not. If you're buying real estate, Article 2 does not. If you're licensing software, the answer is genuinely contested, but the general direction is that pure software licensing is not a sale of goods. Article 2 is specifically calibrated to commercial reality between parties dealing in things you can put on a truck.

The more interesting question arises in the middle ground: contracts that involve both goods and services. A heating-system installation contract. A software implementation contract that includes both the software and the implementation labor. A catering contract that includes both food (goods) and service. These mixed contracts don't fit neatly on either side of the line.

The framework courts use is the *predominant purpose* test, articulated in *Bonebrake v. Cox* (1974) and widely followed since. The question is whether the transaction is predominantly for goods (with services incidental) or predominantly for services (with goods incidental). Courts look at the relative dollar values of the two components, the contract language, the nature of what the parties were actually bargaining for, and how the transaction was negotiated. There is no formula that produces a clean answer in every case — the test is genuinely fact-specific — but the direction is clear: when goods dominate the economic substance of the deal, Article 2 governs; when services dominate, common law governs.

<!-- → [INFOGRAPHIC: Spectrum diagram — left end labeled "Pure Goods (Article 2)" and right end "Pure Services (Common Law)," with the center zone labeled "Mixed Contracts — Predominant Purpose Test." Three example contracts plotted along the spectrum: bulk equipment purchase (far left), heating-system installation (center-left), staffing contract with incidental software license (center-right). Each annotated with the factors courts weigh. Reader should see the test as a spectrum judgment, not a binary switch.] -->

This matters because the rules differ substantially. Common law requires mirror-image acceptance; Article 2 does not. Common law implies no warranties about the quality of the goods; Article 2 implies several. The applicable framework is not a technicality.

One more distinction before we get into the substance: Article 2 treats *merchants* differently from non-merchants. A merchant, under the UCC, is a party who deals in goods of the kind being sold, or who holds herself out as having particular knowledge of the relevant trade. Several Article 2 provisions impose stricter requirements on merchants — most notably the *firm offer* rule under § 2-205, which makes a merchant's signed written offer irrevocable for the time stated (or for a reasonable time, up to three months), even without consideration from the other side. Common law would require consideration to make an offer binding; Article 2 says that for merchants, the signed written promise is enough.

The design choice is deliberate. Merchants operate in commercial markets with specialized knowledge and repeat dealing. Holding them to higher standards than casual consumers reflects the reality that they can protect themselves — through contract drafting, standard practices, and industry knowledge — in ways that ordinary consumers cannot.

---

## The battle of the forms

Here is a scene that plays out thousands of times every day in U.S. commerce: a buyer sends a purchase order. The seller sends back a sales acknowledgment. Both forms are printed in advance, drafted by lawyers, full of detailed boilerplate about delivery terms, payment terms, warranties, dispute resolution, and a dozen other things. The buyer's form says one set of things; the seller's form says different things. Neither party reads the other's form carefully. The goods ship. Everything seems fine — until something goes wrong.

Under common-law contract doctrine, this scenario produces no contract. The seller's acknowledgment, containing different terms, is a counter-offer; it rejects the buyer's offer rather than accepting it. The buyer, by accepting the goods, arguably accepts the seller's counter-offer on the seller's terms. The so-called *last shot rule* — the last form sent before performance governs — produces outcomes that have no logical relationship to what either party actually intended or negotiated.

UCC § 2-207 replaces this with something more realistic. The provision is the most-litigated in U.S. commercial law, and it's worth understanding precisely.

Under § 2-207(1), an expression of acceptance operates as an acceptance even if it states terms different from or additional to those in the offer — *unless* the acceptance is expressly conditioned on the offeror's assent to the different terms. The practical effect: the seller's acknowledgment forms a contract even when it differs from the buyer's purchase order, as long as the seller hasn't explicitly said "we'll only sell on our terms and no others."

Under § 2-207(2), when both parties are merchants, the additional terms in the acceptance automatically become part of the contract — *unless* they materially alter the offer, the offeror objects to them within a reasonable time, or the offer itself says no additions are allowed. So if the seller's acknowledgment adds a term that doesn't significantly change what the buyer agreed to, it slips into the contract without the buyer having to explicitly agree.

Under § 2-207(3), if the forms don't establish a contract but the parties perform anyway — the seller ships, the buyer accepts and pays — a contract is formed on the terms on which the writings agree, plus the UCC's default rules for everything on which they disagree.

Work through a specific case to see how this operates. A buyer sends a purchase order: delivery in 30 days, payment 60 days after delivery, standard seller warranty terms. The seller sends an acknowledgment: delivery in 45 days, payment 30 days after delivery, express warranty disclaimer, and a forum-selection clause requiring any litigation to be filed in the seller's home state. The seller ships; the buyer accepts and pays.

Under § 2-207(1): the acknowledgment forms a contract — it doesn't say "only on our terms." Under § 2-207(2): between merchants, the additional terms become part of the contract unless they materially alter the offer. The warranty disclaimer almost certainly materially alters — eliminating warranties changes the buyer's fundamental rights and is exactly the kind of surprise that the materiality test is designed to screen out. It's excluded. The forum-selection clause is a closer call; courts have split on whether forum selection is material. The delivery and payment timing disagreements don't come from § 2-207(2)'s additional-terms analysis — they're *different* terms, not additional ones, and the majority rule treats different terms using a *knockout* approach: the conflicting terms cancel each other out and the UCC's default rules fill the gaps.

<!-- → [TABLE: The worked § 2-207 example mapped term by term — columns: Term in Dispute, Buyer's Form, Seller's Form, Treatment Under § 2-207, Result. Rows: Delivery timing (different → knockout → UCC default), Payment timing (different → knockout → UCC default), Warranty disclaimer (additional, materially alters → excluded), Forum-selection clause (additional, materiality contested → fact-specific). Reader should see the three-subsection analysis playing out across actual contract terms, not just in the abstract.] -->

The practical lesson: § 2-207 ensures that contracts get formed in commercial form-exchange contexts even when the forms don't match. But the resulting contract is assembled from a combination of agreed terms, surviving additional terms, and UCC defaults — which may not be what either party expected or wanted. The discipline the provision creates is not "read the other side's form carefully" (though that helps); it's "understand the default rules that fill the gaps when your form and theirs don't agree."

---

## What the UCC promises about the goods themselves

Common law, by default, makes no promises about the quality of goods sold. If you sell me a widget that doesn't work, I have no recourse under common law unless we specifically contracted for it to work. The deal was a deal; what you delivered is what I got.

Article 2 changes this. It builds a set of warranties into every sale of goods, operating by default whether or not the parties wrote them down.

The first is the *express warranty* under § 2-313. Any affirmation of fact or promise the seller makes about the goods, if it becomes part of the basis of the bargain, creates an express warranty. This is fairly intuitive: if the seller tells me the engine produces 250 horsepower and it produces 180, the seller has breached a warranty. The limit is *puffery* — subjective opinions or promotional language that no reasonable buyer would take as a factual commitment. "This is the best engine on the market" is puffery. "This engine produces 250 horsepower" is a warranty.

The second is the *implied warranty of merchantability* under § 2-314. When the seller is a merchant in goods of the kind sold, those goods are warranted to be merchantable — fit for their ordinary purposes, adequately packaged and labeled, meeting the standards of the trade. If you buy flour from a commercial flour merchant and it's full of gravel, it's not merchantable. No written warranty is required; the warranty is implied by the act of commercial sale. The seller doesn't have to promise merchantability; the law assumes it.

The third is the *implied warranty of fitness for a particular purpose* under § 2-315. When the seller has reason to know the buyer's specific purpose for the goods, and the buyer is relying on the seller's skill and judgment to select or furnish the goods, those goods are warranted fit for that specific purpose. The distinction from merchantability matters: merchantability is about ordinary use; fitness for particular purpose is about the buyer's specific application. If I tell a supplier I'm building equipment that will operate in temperatures down to -40°C and they recommend a specific lubricant for that application, they have warranted that the lubricant will perform at -40°C — even if the same lubricant, used in ordinary ambient applications, would be perfectly merchantable.

<!-- → [TABLE: Three-warranty comparison — columns: Warranty, UCC Section, What It Covers, Who It Applies To, What Triggers It, How to Disclaim. Rows: Express Warranty (§ 2-313), Merchantability (§ 2-314), Fitness for Particular Purpose (§ 2-315). The merchantability vs. fitness distinction — ordinary use vs. buyer's specific application — should be the visual centerpiece of this table.] -->

The warranties are powerful, but they're defeasible. Article 2 permits effective disclaimer. Under § 2-316, the merchantability warranty can be disclaimed if the word *merchantability* is used conspicuously in the disclaimer — it has to be visible and explicit. The fitness warranty can be disclaimed by conspicuous written language. And there is a shortcut: the phrase *as is* or *with all faults*, if conspicuous, effectively disclaims both implied warranties without specifying them individually. The design logic is that a buyer who sees "as is" is on notice that they're getting what they get with no quality assurance from the seller.

Consumer contracts add a layer of complexity. Disclaimers in standard-form consumer contracts face unconscionability scrutiny — courts are less willing to enforce warranty disclaimers buried in fine print against consumers who had no realistic ability to negotiate them than they are to enforce the same disclaimers between commercial merchants with comparable bargaining positions.

---

## Who bears the risk when the shipment never arrives

Suppose the goods are shipped, the seller fulfilled its obligations, and the buyer was ready to receive — but somewhere in transit, the shipment is destroyed. A flood. A truck accident. Theft. Who bears the loss?

This is the *risk of loss* question, and UCC § 2-509 provides the default answer based on the specific structure of the delivery arrangement.

In a *shipment contract* — one in which the seller is required to ship the goods but not to deliver them to any particular destination — risk passes to the buyer when the seller delivers the goods to the carrier. Once the seller hands the package to the shipping company, it's the buyer's problem. If the goods are destroyed in transit, the buyer bears the loss and still owes the contract price. The seller has done what it was required to do.

In a *destination contract* — one in which the seller is required to deliver the goods to a specific place — risk doesn't pass until the seller tenders the goods at that destination. The seller bears the risk through the entire journey. If the shipment is destroyed in transit, it's the seller's problem; the seller must either deliver conforming goods or face a breach claim.

The practical identifier is the shipping terms. *FOB origin* (Free on Board at the seller's facility) means the seller's delivery obligation ends when the goods leave the seller's dock — shipment contract, risk passes early. *FOB destination* means the seller's obligation runs all the way to the buyer's facility — destination contract, risk passes late. These terms aren't arcane trade jargon; they're the mechanism by which the parties specify, in two words, which side of the risk-of-loss line they're on.

<!-- → [INFOGRAPHIC: Side-by-side journey diagram for shipment vs. destination contracts. A goods-in-transit illustration showing Seller's Facility → Carrier → Buyer's Facility. In the shipment-contract panel, the risk-transfer point is marked at Seller's Facility (when goods are handed to carrier). In the destination-contract panel, the risk-transfer point is marked at Buyer's Facility. Labeled with FOB Origin and FOB Destination respectively. Reader should be able to identify instantly which party bears transit risk under each arrangement.] -->

A separate rule applies when goods are held by a *bailee* — a third-party warehouse or storage facility. Risk passes to the buyer when the buyer receives a negotiable document of title, or when the bailee acknowledges the buyer's right to possession. The buyer, in other words, takes on the risk when she gets the legal mechanism to claim the goods, not when the goods are physically in her hands.

The risk-of-loss rules interact with the warranty rules in ways that matter. Suppose goods arrive damaged — was the damage in transit, or were the goods defective when shipped? If the goods were non-conforming when the seller tendered them, the risk doesn't pass under § 2-509 in the ordinary way; a separate provision (§ 2-510) keeps the risk on the seller until the buyer has accepted conforming goods or had a reasonable opportunity to inspect and reject. The seller can't transfer risk by shipping defective goods and claiming the buyer's problem begins the moment the carrier takes possession.

---

## What happens when the deal breaks down

When one party breaches, Article 2 provides specific remedies calibrated to put the non-breaching party in the position it would have occupied had the contract been performed.

For the buyer, the core breach scenario is the seller delivering goods that don't conform to the contract — wrong goods, late delivery, defective quality. The buyer's options, in the order they typically arise:

*Rejection.* The buyer can refuse to accept non-conforming goods, as long as rejection is timely and the buyer gives the seller a specific reason. Rejection returns the problem to the seller, who has a limited right to *cure* — to fix the non-conformity within the contract time or, in some circumstances, slightly beyond it.

*Cover.* If the seller fails to deliver or the buyer legitimately rejects, the buyer can purchase substitute goods elsewhere and recover the difference between the cover price and the contract price. Cover is the cleanest remedy: it puts the buyer in the position it would have occupied had the seller performed, without requiring the buyer to wait for a damages calculation after the fact.

*Damages without cover.* If the buyer doesn't cover, the measure of damages is the difference between the market price and the contract price at the time of breach — putting the buyer in the same economic position cover would have achieved, but calculated abstractly rather than from an actual substitute purchase.

*Specific performance.* For unique goods — where no market substitute exists — the buyer can obtain a court order requiring the seller to deliver. This is the narrow exception to the general principle that the UCC remedies in money.

For the seller, the core breach scenario is the buyer refusing to accept or pay for goods the seller has tendered. The seller can resell the goods and recover the difference between the resale price and the contract price. If the seller cannot reasonably resell — because the market has collapsed, because the goods are custom-made for the buyer — the seller can recover the full contract price. The seller can also recover incidental damages: the costs of stopping delivery, caring for and returning goods, and arranging resale.

<!-- → [TABLE: Remedies reference — two panels side by side. Buyer's Remedies (for seller's breach): Rejection, Cover, Market-price damages, Specific performance — each with trigger condition and measure of recovery. Seller's Remedies (for buyer's breach): Withhold delivery, Resell and recover differential, Full contract price (where resale unavailable), Incidental damages — each with trigger condition and measure. Both panels share a footer row: Consequential Damages — recoverable by either party when reasonably foreseeable at contracting.] -->

The thread running through all of these remedies is *consequential damages*: losses beyond the immediate transaction that result from the breach. Consequential damages are recoverable by either party when the breaching party, at the time of contracting, reasonably should have foreseen them as a probable result of breach. The seller who knows the buyer needs the goods by a specific date to meet a downstream production commitment — because the buyer said so, or because the nature of the transaction made it obvious — is on the hook for the downstream losses if late delivery causes them. The seller who had no reason to know bears no such exposure.

---

## The framework in operation

Caraway, a small manufacturer, orders a batch of specialized industrial sensors from a supplier called Northbeam. Delivery: 30 days, FOB Northbeam's facility. The sensors arrive on time. On incoming quality inspection, they fail. Caraway notifies Northbeam and rejects the shipment.

Work through the framework.

*Article 2 governs.* This is a sale of goods — movable, tangible items — between two businesses. No mixed-contract question arises.

*Warranties.* The contract contained no effective disclaimer — Caraway should verify the terms, but absent conspicuous disclaimer of merchantability, Northbeam has warranted that the sensors are fit for their ordinary purposes. Sensors that fail quality inspection are not merchantable. The warranty is breached.

*Risk of loss.* FOB origin means risk passed to Caraway when Northbeam delivered the sensors to the carrier. Caraway bore the transit risk. But the breach of warranty is independent of the risk-of-loss allocation. The sensors didn't fail because of something that happened in transit; they were defective when tendered. The risk-of-loss rule doesn't insulate Northbeam from a warranty claim.

*Remedies.* Caraway has rejected the goods — timely, with specific reason. Caraway can recover the contract price, incidental damages (inspection and return costs), and cover by purchasing conforming sensors elsewhere at whatever the current market price is, recovering the differential from Northbeam. If the sensor failure delays Caraway's downstream production and Northbeam had reason to know at contracting that delivery timing was production-critical, consequential damages are available.

<!-- → [INFOGRAPHIC: Caraway/Northbeam fact pattern mapped through all four framework sections — four labeled bands stacked vertically: (1) Scope [Article 2 governs — sale of goods between merchants, no mixed-contract issue], (2) Warranties [no effective disclaimer → merchantability implied → defective sensors breach it], (3) Risk of Loss [FOB origin → risk passed at carrier handoff → but § 2-510 keeps risk on Northbeam for pre-existing defects], (4) Remedies [rejection → contract price recovery → cover → consequential damages if production delay foreseeable]. Each band shows the legal rule and its application to these specific facts. Reader should see the four analytical steps as a structured sequence, not four independent questions.] -->

The operational takeaway is not just the legal analysis — it's the sequence of decisions the framework forces: notify rejection promptly, document the specific non-conformity, evaluate cover options immediately, preserve evidence. The framework is not an academic structure; it's a sequence of decisions that either preserves or forfeits rights.

That is what a legal operating system does. It runs in the background of every commercial transaction, shaping what is owed, what is warranted, who bears the risk, and what remedies are available when something goes wrong. The practitioner who understands it doesn't have to improvise when the transaction breaks down. The practitioner who doesn't is operating without knowing the rules of the game they're already playing.
