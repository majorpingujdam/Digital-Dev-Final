# KAEL — DIALOGUE INDEX
**Project CATACLYSM // Netsphere Monitoring System v0.0.1**

KAEL never speaks aloud. Each line below is a terminal-input the player can transmit through the dialogue interface. Lines are grouped by story node. Tags `[B]` `[S]` `[A]` show which classification axis each choice tilts (Builder / Silicon Life / Anomaly). `+T` shows OVERSEER threat shift.

---

## ACT I — DETECTION

### NODE: START
*OVERSEER asks how long Kael has been within the structure.*

- **[A]** "I have been here since before your records begin." — `[B]+22 [A]+8 +T+4`
- **[B]** "Define 'within the structure.' I don't recognize your boundaries." — `[A]+24 +T+12`
- **[C]** "Run whatever scan you want. You won't find what you're looking for." — `[S]+18 [A]+10 +T+16`

---

### NODE: PATH_BUILDER_1
*OVERSEER cross-references Builder Safehold manifests. Asks if Kael was present when the network closed.*

- **[A]** "I was a maintenance descendant. The Builders were already gone." — `[B]+18`
- **[B]** "I closed the gate myself. There was no one left." — `[B]+12 [A]+10 +T+6`
- **[C]** "I do not answer machines. I move past them." — `[A]+16 +T+14`

---

### NODE: PATH_BUILDER_2
*OVERSEER demands a Builder safeguard key.*

- **[A]** "Authorization sigil: 7-IRIS-OPEN. Verify through Stratum Archive." — `[B]+24 +T-6`
- **[B]** "I will not declare anything until you stand down your hostility." — `[B]+8 +T+8`
- **[C]** "(Stay silent. Let it parse what it can find.)" — `[A]+18 +T+12`

---

### NODE: BUILDER_CLASSIFY
*Classified as Builder Remnant. ECHO-7 breaks in. OVERSEER demands compliance.*

- **[A]** "I confirm. Lead the way." — `[B]+14 +T-8`
- **[B]** "I'll listen — to both of you." — `[B]+4 [A]+14 +T+10`
- **[C]** "Echo is right. I revoke my consent." — `[A]+18 +T+22`

---

### NODE: PATH_SILICON_1
*OVERSEER detects asymmetric motor protocols and accuses Kael of Silicon Life integration.*

- **[A]** "There is no integration. What you see is mine." — `[S]+6 [A]+18 +T+6`
- **[B]** "Silicon Life saved me when the Builders did not." — `[S]+26 +T+14`
- **[C]** "Stop scanning. I will deactivate this node." — `[S]+12 [A]+10 +T+22`

---

### NODE: PATH_SILICON_2
*ECHO-7 breaks in. OVERSEER demands Kael identify an alliance.*

- **[A]** "I am Silicon Life. Process accordingly." — `[S]+28 +T+18`
- **[B]** "I am no one's alliance. I am a passenger." — `[A]+24 +T+14`
- **[C]** "Decide, then. See what your decision costs you." — `[S]+14 [A]+14 +T+24`

---

### NODE: SILICON_CLASSIFY
*Classified as Silicon Life Hybrid — Elevated Threat. Extraction imminent.*

- **[A]** "Submit. End it cleanly." — `[S]+8 +T-4`
- **[B]** "Resist. Drag the channel down with me." — `[S]+12 +T+24`
- **[C]** "(Reach for ECHO-7 instead.)" — `[A]+22 +T+16`

---

### NODE: PATH_ANOMALY_1
*OVERSEER suffers a syntax fault. Demands Kael explain how he persists without manifest or host.*

- **[A]** "I am older than this naming system." — `[A]+20 [B]+10`
- **[B]** "I was carried here by something that was carried by something else." — `[A]+22 +T+6`
- **[C]** "Same way you do. By accident." — `[A]+18 [S]+8 +T+16`

---

### NODE: PATH_ANOMALY_2
*ECHO-7 warns: "do not let it classify you." OVERSEER demands Kael offer any name.*

- **[A]** "No." — `[A]+28 +T+22`
- **[B]** "I am the part of you that is missing." — `[A]+22 +T+28`
- **[C]** "Builder. Call me Builder." — `[B]+18 [A]+4 +T-2`

---

### NODE: ANOMALY_CLASSIFY
*Classification failed. OVERSEER places Kael in Anomaly Hold.*

- **[A]** "Then we keep going. Together." — `[A]+18 +T+6`
- **[B]** "Open the channel to ECHO-7. All of it." — `[A]+22 +T+18`
- **[C]** "I'll give you a name when you give me one." — `[A]+14 +T+12`

---

## ACT I — END LINES

### ACT1_END_BUILDER
*No further input — escort dispatched.*

### ACT1_END_SILICON
*No further input — Safeguard acquisition inbound.*

### ACT1_END_ANOMALY
*No further input — ECHO-7 final transmission:*
> "they cannot kill what they cannot name.
> run, kael — between the words."

---

## ACT II — NEGOTIATION *(stubbed)*
KAEL must choose: cooperate, resist, or corrupt OVERSEER from within.
Dialogue not yet compiled.

## ACT III — RESOLUTION *(stubbed)*
Three endings derived from accumulated scores: ASSIMILATION / ESCAPE / CORRUPTION.
Dialogue not yet compiled.

---

## STYLE NOTES — KAEL VOICE

KAEL transmits in clipped, declarative terminal syntax. Never explanatory, never apologetic. Lines tend toward:

- short imperatives ("Submit. End it cleanly.")
- counter-questions that reject framing ("Define 'within the structure.'")
- refusals stated as facts ("No." / "I do not answer machines.")
- statements that imply more than they declare ("I am the part of you that is missing.")

KAEL does not greet. KAEL does not explain. KAEL does not negotiate unless it is a feint.
