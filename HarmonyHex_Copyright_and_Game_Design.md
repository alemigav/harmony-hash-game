# Harmony Hex

© 2025 Alexandre Gavronski. All rights reserved.

**Harmony Hex** is an original game concept, ruleset, symbolic system, and audiovisual gameplay design. Unauthorized reproduction, distribution, public performance, display, or creation of derivative works is prohibited without the express permission of the author.

Public availability of this document does **not** constitute a license.

---

## Copyright Deposit Description (Legal-Style)

### 1. Title of the Work

**Harmony Hex**

---

### 2. Nature of the Work

Harmony Hex is an original interactive audiovisual game system comprising rules, mechanics, symbolic representations, and player interactions expressed through software and graphical elements. The work constitutes a pictorial, graphic, literary, and audiovisual compilation protected as an original selection, coordination, and arrangement of gameplay mechanics and symbolic logic.

---

### 3. General Description of the Work

Harmony Hex is a grid-based puzzle game in which players manipulate symbolic elements through directional input to construct ordered symbolic sequences. Gameplay centers on the progressive construction of composite symbols from atomic components, culminating in a unique solved configuration that satisfies predefined spatial, logical, and symbolic constraints.

The originality of the work arises from the precise interaction of board topology, merge logic, ordering rules, fixation mechanics, uniqueness constraints, and symbolic representation, forming a system not reducible to any individual mechanic alone.

---

### 4. Game Board and Spatial Structure

The game board consists of a fixed **eight-by-eight (8×8) grid**, comprising sixty-four (64) discrete cells arranged in rows and columns. Each cell may contain at most one game element at any given time. Movement and interaction of elements are constrained by the boundaries of the grid.

Rows and columns are indexed from one (1) through eight (8) for purposes of spatial definition and rule application.

---

### 5. Special Cell Arrangement

A subset of cells within the grid is designated as **special cells**. These cells are defined as all cells located in:

* Column three (3)
* Column six (6)
* Row three (3)
* Row six (6)

The union of these rows and columns yields **twenty-eight (28) unique special cells**, forming a visual pattern analogous to a hash (#) symbol. Special cells possess interaction capabilities not available to non-special cells.

---

### 6. Fundamental Symbolic Elements

#### 6.1 Atomic Elements

The most basic game elements are symbolic **lines**, of which there are exactly two (2) types:

* **Yang line**: solid line
* **Yin line**: broken line

These atomic elements form the foundational units from which all higher-order symbols are constructed.

---

#### 6.2 Composite Elements

Composite elements consist of vertically stacked, ordered sequences of lines contained within a single cell:

* **Digrams**: two (2) ordered lines
* **Trigrams**: three (3) ordered lines
* **Hexagrams**: six (6) ordered lines

The system defines exactly four (4) digrams, eight (8) trigrams, and sixty-four (64) hexagrams.

---

### 7. Element Spawning Rules

At the commencement of a game session, a single atomic line element is randomly placed within an empty cell on the board.

After each directional movement input by the player, exactly one (1) additional atomic line element is spawned. Spawning occurs only in unoccupied cells and with equal probability between yin and yang line types.

---

### 8. Player Input and Movement Mechanics

Player interaction occurs primarily through four-directional swipe inputs: upward, downward, leftward, and rightward.

Upon receipt of a swipe input, all movable elements on the board shift simultaneously in the indicated direction, traveling until blocked by either the edge of the board or another element.

---

### 9. Merge Rules and Restrictions

#### 9.1 Permitted Merges

Merges occur when adjacent elements collide as a result of directional movement and satisfy defined criteria. Permitted merges are strictly limited to:

* Line combined with line, producing a digram
* Line combined with digram, producing a trigram
* Trigram combined with trigram, producing a hexagram

---

#### 9.2 Prohibited Merges

The following combinations are expressly prohibited:

* Digram combined with digram
* Digram combined with trigram
* Line combined with trigram
* Any merge involving a hexagram

Hexagrams are terminal elements and cannot merge further.

---

### 10. Sequence Ordering Determination

When composite elements are formed, internal ordering of lines is determined by spatial proximity relative to the direction of player input.

The element closest to the boundary toward which movement occurs contributes its lines to the lower portion of the resulting sequence, while the element farther from that boundary contributes its lines to the upper portion.

Additional rules apply:

* When a line merges with a digram to form a trigram, the line is placed above the digram.
* When two trigrams merge to form a hexagram, the trigram farther from the movement boundary forms the upper three lines.

These rules ensure deterministic and reproducible symbolic construction.

---

### 11. Fixation Mechanism

Hexagrams may be fixed into position only when located within special cells.

Fixation is triggered by a discrete tap or click input directed precisely at the target cell. Once fixed, a hexagram becomes immobile and visually distinguished.

A fixed hexagram may be released and returned to a movable state by a subsequent tap or click.

---

### 12. Uniqueness Constraint

No two fixed hexagrams within special cells may share the same symbolic configuration. Any attempt to fix a hexagram duplicating an already fixed hexagram is invalid and produces no effect.

---

### 13. Visual Expression

All symbolic elements are rendered visually within individual cells. Lines are stacked vertically to display internal ordering. Digrams, trigrams, and hexagrams display two (2), three (3), and six (6) lines respectively.

Special cells and fixed hexagrams are visually differentiated through highlighting and animated effects.

---

### 14. Scoring System

The game includes a scoring mechanism awarding points for the creation of composite elements. Higher-order constructions yield greater point values. Specific numerical values are implementation-defined and not essential to the scope of this work.

---

### 15. Winning Condition

A game session is successfully completed when all twenty-eight (28) special cells are occupied by fixed hexagrams and each such hexagram is symbolically unique.

Fulfillment of this condition results in the creation of a **Harmony Hex Token**, representing a completed and valid final configuration.

---

### 16. Losing Conditions

A game session terminates unsuccessfully if the board becomes fully occupied and no legal moves or merges remain, or if the board state no longer permits satisfaction of the winning condition.

---

### 17. Levels and Variants

The work presently includes a single level. Additional levels may be defined through alternative initial configurations or increased starting complexity without altering the core mechanics described herein.

---

### 18. Non-Fungible Token Output

Upon successful completion of a Harmony Hex Token, the system generates a digital certificate representing the solved state. This certificate includes:

* The exact positions and identities of the twenty-eight (28) fixed hexagrams
* A timestamp of completion
* A unique cryptographic hash derived from the final board configuration

This output constitutes a unique, non-fungible digital artifact intrinsically linked to the gameplay outcome.

---

### 19. Statement of Originality

The selection, coordination, and arrangement of mechanics, symbolic systems, spatial constraints, interaction rules, and visual expression described herein constitute an original work of authorship fixed in tangible form.

---

### 20. Scope of Claim

The copyright claim extends to the original rules, structure, symbolic representations, audiovisual expression, and the particular combination and arrangement thereof, as fixed in documentation, software, and visual output, excluding only elements dictated by technical necessity or external standards.

---

## Author’s Intent

The author expressly reserves all commercial, licensing, adaptation, and derivative rights. No rights are granted by implication, estoppel, or public availability.

---

**End of Document**
