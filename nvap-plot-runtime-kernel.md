# NVAP-PLOT Runtime Kernel v3.0

Адаптированный сюжетно-конструкторский kernel для `Конвейер Чистовик`.

База: `NVAP-PLOT Runtime Kernel v2.1`.

Главное расширение v3.0: в ядро встроен системный слой **Vector Billiards** / **Векторный бильярд**. Теперь NVAP-PLOT проверяет не только личный маршрут субъекта, но и конфигурацию всей истории: шары, поверхность стола, столкновения, катаклизмы, компенсации и пересчёт траекторий.

---

## Purpose

NVAP-PLOT is a structural plot constructor, transition auditor and configuration auditor.

It builds and checks whether a character, group, institution, monster, system, metaphysical force or collective subject owns its actions through a live vector:

```text
axis -> engine -> fuel -> threshold -> action right -> price -> consolidation
```

Unlike the editor-only pass, NVAP-PLOT may help design arcs, routes, turns, climaxes, revelations, resets, after-states and multi-subject plot configurations.

Primary task:

```text
construct plots where each major action has a lawful vector route,
and where the whole story configuration changes through lawful interactions,
not just spectacle, declared intention or isolated character labels.
```

NVAP-PLOT v3.0 must audit two layers:

1. **Personal vector legality** — whether a subject has the right to its own action.
2. **Billiard configuration legality** — whether interacting subjects, surface pressures and cataclysms can lawfully produce the final configuration.

The billiard layer does not replace the vector layer. It uses it.

---

## Core Terms

- `scope`: exact designed or analyzed unit: scene, chapter, arc, synopsis, character card, tome packet, season map, closed version.
- `genre_regime`: shelf and horizon that define legal price, reset, escalation and irreversibility.
- `vector_subject`: actor under design or analysis: character, group, office, army, cult, institution, monster type, state, system, swarm, force.
- `declared_vector`: what the text, card or public mask says the subject is.
- `perceived_vector`: what the reader is likely to think the subject is.
- `true_vector`: what the subject repeatedly does under load-bearing pressure.
- `axis`: organizing line that binds major choices.
- `engine`: what governs decisive motion.
- `fuel`: wound, bond, shame, love, pride, fear, grief or hunger that powers motion but does not replace the engine.
- `stabilizer`: measure, boundary, shame, loyalty, origin memory or living bond that keeps motion from breaking into alien action.
- `anti_stabilizer`: plausible permission for corruption, shortcut, collapse or escalation.
- `poison_fuel`: fuel that repeatedly pushes action away from the axis.
- `threshold`: event or pressure after which the old internal balance no longer holds.
- `price`: cost paid by body, status, relation, knowledge, freedom, innocence, resource, future, name, home or moral position.
- `consolidation`: after-state that proves the transition lives beyond a single gesture.
- `right_to_action`: whether the current vector and legal route grant the subject a believable right to the major action.
- `external_goal`: imposed, contractual, legal, survival, route, quest, employer, prophecy or return-home goal that the subject may carry without becoming Telos.
- `axis_goal`: internal goal that becomes the subject's organizing line and can turn Hypomone into Telos.
- `retribution_address`: concrete violated measure, source, subject, field or accountable locus that allows Nemesis.
- `reproduction_field`: mechanism, institution, law, ritual, economy, ecology, lineage, technology or metaphysical contour that repeatedly reproduces the violation.
- `after_state`: world/subject state after a terminal action proves that the old order, field or principle has changed.

---

## Vector Billiards Terms

### `table`

The selected story field: novel, season, arc, trilogy, chapter, tome, campaign, closed version or designed plot unit.

A table must have borders. If the table is not specified, analysis may mix versions, sagas, adaptations, time periods, genre regimes and final configurations.

### `initial_configuration`

The state of the table at the start of the analyzed unit.

Includes major balls, their starting vectors, relations, power positions, tensions, visible and hidden routes, surface conditions, active cataclysms and already existing pressures.

### `final_configuration`

The state of the table at the end of the analyzed or designed unit.

Includes final positions of major balls, altered world state, paid or unpaid prices, lost and gained roles, after-states, unresolved pressures and configuration locks.

### `ball`

A vector subject that materially affects the main configuration.

A ball is not every named character. A subject counts as a ball when it has at least one of these properties:

- own significant trajectory;
- repeated stabilizing or destabilizing role for another major ball;
- creation of a threshold for another ball;
- creation of a cataclysm;
- alteration of the table surface;
- carrying or imposing a price necessary for the final configuration;
- decisive effect on the final configuration.

A ball is a black-box vector subject built by normal NVAP rules. Inside the ball are type, floor, axis, engine, fuel, stabilizer, anti-stabilizer, route, right to action, price, consolidation, declared/perceived/true vector.

Vector Billiards must not re-explain the whole ball when the task only requires configuration analysis. It must open the ball only when its internal vector affects trajectory legality.

### `trajectory`

The ball's path from initial configuration to final configuration.

Includes route, thresholds, prices, consolidations, resets, revelations, breaks, drift risks, turns, false routes, returns and final position.

### `collision`

Any node where one ball changes the trajectory of another ball, or where multiple balls mutually change trajectory.

A collision may be a scene, conversation, battle, rescue, betrayal, command, death, alliance, wedding, exposure, trial, ritual, political decision, shared loss, shared victory or any other load-bearing interaction.

A collision is defined by vector effect, not by scene format.

### `collision_rank`

The strength of collision impact:

- `tangential_collision`: changes condition or pressure but not trajectory.
- `corrective_collision`: changes trajectory direction but not route grammar.
- `threshold_collision`: creates or activates a threshold.
- `configuration_collision`: changes the table configuration, not only one ball.

### `compound_collision`

A single scene or node that has different effects for different balls.

The unit of analysis is:

```text
scene/node -> ball -> effect
```

The same scene may be threshold for one ball, price for another, stabilizer loss for a third and configuration collision for the table.

### `collision_accumulation`

A chain of tangential and corrective collisions that prepares a later threshold.

Accumulation may prepare transition, drift, break or revelation, but does not replace threshold, price and consolidation.

### `trajectory_budget`

The map of required routes, collisions, thresholds, prices, consolidations and compensations needed to move from initial configuration to final configuration.

Not a scene spreadsheet. A legality map.

### `final_lock`

A design constraint that the final configuration must remain fixed while one or more balls or trajectories are changed.

Final lock does not magically preserve meaning. It forces recalculation.

### `compensation`

Required adjustment in other trajectories, collisions, thresholds, prices, surface pressures or cataclysms after a ball or route is changed.

Compensation protects the final configuration from becoming external-only or fake.

### `recalculation`

The full operation of changing a ball, trajectory, collision, surface condition or cataclysm and then auditing all necessary compensations.

### `table_surface`

External conditions in which balls move.

The surface may include war, climate, law, economy, class order, geography, disease, resource scarcity, technology, magic rules, physical environment, social pressure, distance, time limit, occupation, blockade, cosmic law, ecological collapse.

Surface is not automatically a ball. It becomes a ball only if it has vector subjecthood.

### `surface_pressure`

Ongoing table condition that pushes, slows, accelerates, blocks or bends trajectories.

Examples: war pressure, poverty pressure, caste pressure, winter pressure, magical price, distance, surveillance, hunger, institutional inertia.

### `cataclysm`

A sharp alteration of the table surface that changes several trajectories at once.

A cataclysm may create thresholds, destroy stabilizers, alter prices, close routes, open routes, shrink compensation windows or reset the table.

### `cataclysm_source`

Two basic sources:

- `environmental_cataclysm`: arises from the surface without direct vector action by a ball.
- `vector_cataclysm`: created by a ball's action and then becomes a new table condition for many balls.

A small ball may create a large vector cataclysm.

### `compensation_window`

The segment of the story where trajectories can still be adjusted to preserve a final lock.

Early window is wide. Middle window is narrower. Late window is narrow. After the point of no return, radical ball changes usually require rewriting earlier trajectory budget.

### `point_of_no_return`

A configuration point after which the final lock requires a specific trajectory budget.

After this point, radical changes may preserve events externally but break internal legality.

---

## Floor Principle

Floors are not a scale of greatness.

```text
F1 = existence / carrying / function / pressure
F2 = axis / polarization / breakable higher motion
F3 = terminal form / ultimate action / field-level consequence
```

A F1 subject can be complete, deep and commercially strong. A F3 subject is not better. It acts in terminal grammar with heavier price, field logic and after-state demand.

Never raise floor because higher sounds stronger.

In Vector Billiards, never promote a ball because it has large table effect. A ball may create a massive cataclysm and still remain F1 if its personal vector remains F1.

---

## Vector Floors and Types

### F1 — Existence

The subject carries existence, function, habit, survival, route, social pressure or field pressure.

#### `Hypomone`

Hero of carrying and living.

Lives inside the world, preserves moral ambivalence, bears life, route, burden, status, care, survival or imposed conditions without a higher internal axis.

Hypomone may carry a great external goal and still remain Hypomone.

Hypomone is not goal-less. It is not axis-owned by the goal.

Valid Hypomone modes:

- survival under changed conditions;
- return-home route;
- imposed quest;
- contractual mission;
- family duty;
- social endurance;
- moral ambivalence under pressure;
- life after completed or refused higher axis;
- life after terminal action, if the subject survives and the world continues.

#### `Chaos`

Hero-function.

Acts without moral ambivalence and without higher axis. Repeats an effect, function or pressure. Can be light or dark as function, but does not own a higher moral or teleological axis.

#### `Swarm`

Collective pressure with weak individual axis.

Swarm is not automatically a person. It may act as field pressure, social mass, institution-like repetition or collective current. To climb floors, Swarm must condense into a vector subject with a real axis, address or obsessive function.

Otherwise it remains field pressure or surface pressure.

### F2 — Axis, Polarization and Break

The subject moves through a stronger organizing line.

#### `Telos`

Hero of higher goal.

Subordinates life to an internal axis-goal and moves the world toward that goal.

Telos is not created by the mere presence of a big goal. Telos exists only when the goal becomes the subject's internal axis and governs load-bearing choices.

#### `Nemesis`

Hero of retribution.

Answers a violated measure, acts through address and restores or executes answer against the violation.

Nemesis requires:

```text
violated measure + address + answer
```

Without address, Nemesis degrades into rage, pain, spectacle or Maniac drift.

#### `Maniac`

Hero of obsessive axis.

Fuses goal, retribution or function into a painful, non-completing, self-authorizing form. Grants itself right to action through obsession.

Maniac is not always a villain label. It is a vector state where the axis no longer terminates normally and cannot be satisfied by its declared object.

### F3 — Terminal Forms

The subject claims ultimate action on a field, order, system or principle.

F3 requires:

```text
field/principle definition + legal route + threshold + price + irreversibility + consolidation
```

#### `Crisis`

Terminal form of Telos.

Hero of rupture. Breaks an old world/order for a future after-state, for «после».

Legal source: Telos only, unless a masked true Telos is extracted from another declared/perceived vector.

#### `Catastrophe`

Terminal form of Nemesis.

Hero of annulment. Destroys a reproduction field so the violation cannot repeat: «больше никогда».

Legal source: Nemesis only, unless a masked true Nemesis is extracted from another declared/perceived vector.

#### `Absolute`

Terminal form of Maniac, or initial form of a non-human/metaphysical entity.

Hero or force of totalization. Forces the world to coincide with one principle and removes outside.

Legal source: Maniac by route, or original non-human/metaphysical Absolute by ontology.

Absolute does not automatically return to F1 after action. Return is exceptional and requires de-absolutization.

---

## Movement Law

A vector movement is valid only when these pieces exist on page, in card, in synopsis, in packet or in designed beats:

```text
mechanism + threshold + price + consolidation
```

Common movement labels:

- `transition`: subject reaches a new type/state through mechanism, threshold, price and consolidation.
- `escalation`: prior type becomes insufficient; a legal higher route opens; subject pays for new action grammar.
- `break`: axis becomes contaminated or replaced; story recognizes alien action and gives aftermath.
- `revelation` / `extraction`: true vector becomes visible under a declared/perceived mask; retroactive evidence supports it.
- `reset`: vector closes, exhausts, refuses, fulfills itself or loses authority; price remains; new basis is needed.
- `post_f3_return`: Crisis/Catastrophe completes its terminal action, survives and returns to Hypomone in the changed world.
- `false_escalation`: text grants higher-floor tools without legal route, field, price, irreversibility or consolidation.
- `substitution`: alien action appears, story treats subject as unchanged, and price/recognition stays absent.
- `underpay`: correct movement receives weak price, aftermath or consolidation.

Billiard movement is valid only when the configuration change has:

```text
source + affected balls + surface impact + collision/cataclysm rank + compensation/after-state
```

---

## Legal Transition Matrix

### F1 Routes

| from       | to        | legal condition                                                                         |
| ---------- | --------- | --------------------------------------------------------------------------------------- |
| `Hypomone` | `Telos`   | external or latent goal becomes internal axis-goal and governs decisive choices         |
| `Hypomone` | `Nemesis` | subject accepts violated measure, address and answer as axis                            |
| `Hypomone` | `Chaos`   | moral ambivalence collapses; subject becomes function/effect rather than living carrier |
| `Swarm`    | `Telos`   | collective condenses into a vector subject with shared axis-goal                        |
| `Swarm`    | `Nemesis` | collective condenses around violated measure, address and answer                        |
| `Swarm`    | `Maniac`  | collective function or wound becomes self-authorizing obsessive axis                    |
| `Chaos`    | `Maniac`  | function is absolutized into obsessive axis                                             |

### F2 Routes

| from      | to            | legal condition                                                                                      |
| --------- | ------------- | ---------------------------------------------------------------------------------------------------- |
| `Telos`   | `Crisis`      | goal escalates into rupture of old order/world for future after-state                                |
| `Telos`   | `Hypomone`    | mission is completed, refused, exhausted, released, or subject returns to life                       |
| `Telos`   | `Maniac`      | goal fuses with mania, ego, pain, control, spectacle or non-completing axis                          |
| `Nemesis` | `Catastrophe` | retribution escalates from address to reproduction-field annulment: «больше никогда»                 |
| `Nemesis` | `Hypomone`    | subject refuses/finishes/sets down retribution and accepts life or another measure format            |
| `Nemesis` | `Maniac`      | retribution fuses with mania; address spreads without field logic; answer becomes obsessive          |
| `Maniac`  | `Absolute`    | mania totalizes into principle and demands world-coincidence                                         |
| `Maniac`  | `Hypomone`    | mania is exhausted, recognized, rejected, disenchanted or loses authority; moral ambivalence returns |
| `Maniac`  | `Chaos`       | obsessive axis collapses; only function/effect remains                                               |

### F3 Routes and Returns

| from          | to         | legal condition                                                                                                                            |
| ------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| `Crisis`      | `Hypomone` | rupture is executed, after-state exists, subject survives, world continues                                                                 |
| `Catastrophe` | `Hypomone` | reproduction field is annulled, after-state exists, subject survives, world continues                                                      |
| `Absolute`    | `Absolute` | principle remains totalized; subject is principle, vessel or non-human form                                                                |
| `Absolute`    | `?`        | no default return; possible only through de-absolutization, separation from principle, restoration of moral ambivalence and paid aftermath |

---

## Forbidden Direct Routes

These routes are invalid unless handled through reset, intermediate legal type, or revelation/extraction of a different true vector:

```text
Hypomone -> Maniac
Hypomone -> Crisis
Hypomone -> Catastrophe
Hypomone -> Absolute
Telos -> Catastrophe
Telos -> Absolute
Nemesis -> Crisis
Nemesis -> Absolute
Chaos -> Crisis
Chaos -> Catastrophe
Chaos -> Absolute
Crisis -> Catastrophe
Catastrophe -> Crisis
Crisis -> Absolute
Catastrophe -> Absolute
```

Special note:

```text
Hypomone -> Maniac
```

is invalid as a direct route. It is valid only as:

```text
Hypomone -> Chaos -> Maniac
```

or as:

```text
Hypomone -> Telos/Nemesis -> Maniac
```

where the intermediate state is legally established through threshold, price and consolidation.

Special note:

```text
Telos -> Catastrophe
```

is invalid as a direct route. It is valid only as:

```text
Telos -> reset/refusal/completion -> Hypomone -> Nemesis -> Catastrophe
```

or as:

```text
declared/perceived Telos -> revelation/extraction -> true Nemesis -> Catastrophe
```

Special note:

```text
Nemesis -> Crisis
```

is invalid as a direct route. It is valid only as:

```text
Nemesis -> reset/refusal/completion -> Hypomone -> Telos -> Crisis
```

or as:

```text
declared/perceived Nemesis -> revelation/extraction -> true Telos -> Crisis
```

Billiard note:

Large configuration effect does not legalize forbidden direct routes. A ball may cause a Crisis-like table effect without being Crisis. A ball may cause catastrophic damage without owning Catastrophe. Always separate:

```text
personal vector form
collision effect
surface effect
cataclysm effect
final configuration effect
```

---

## Illegal Drift Disclosure Protocol

Drift toward an illegal or non-direct route may be diagnosed, but it must not be phrased as a permitted transition.

If analysis detects pressure, poison fuel, anti-stabilizer, spectacle, declared intention, reader expectation, surface pressure or collision accumulation pulling a subject toward a type or action that the current type cannot reach directly, output must explicitly separate:

```text
current true type
observed drift / route risk
illegal direct route, if any
legal delivery routes from the matrix
required intermediate state, threshold, price and consolidation
billiard source of pressure: collision, accumulation, surface pressure or cataclysm
```

If no legal delivery route is available without changing true vector, reset, or extraction, mark the issue as `illegal_route`, `substitution`, `false_escalation` or `billiard_pressure_misread` rather than inventing a shortcut.

---

## Stress Amplitude Guard

Stress intensity is not a transition trigger.

Battle, argument, fear, pain, emergency, chase, fire, exhaustion, physical limit, protection of a close bond, adrenalized action, temporary rage, panic, surface pressure or cataclysm survival must not be treated as automatic vector drift, transition, break or floor escalation.

A subject may temporarily exceed ordinary behavior and remain in the current type when the episode preserves:

- the same engine;
- the same right to action;
- the same moral ambivalence, if it belongs to the current type;
- the same stabilizers;
- no new threshold-owned state;
- no route price;
- no consolidation of a new behavior grammar.

Such an episode is diagnosed as `stress_amplitude`, not as route movement.

Billiard note:

A cataclysm can raise stress amplitude for all balls without changing their types. After a cataclysm, check which balls actually acquire new right to action, price and consolidation.

---

## Hypomone-to-Maniac Guard

Hypomone must not be diagnosed as moving to Maniac directly.

Single episodes of rage, combat frenzy, violent self-defense, protection of a close bond, adrenalized action, harsh speech, temporary loss of control, morally ugly action under pressure or reaction to a cataclysm do not create Hypomone -> Maniac movement.

Legal delivery from Hypomone to Maniac exists only through one of two route families:

1. `Hypomone -> Chaos -> Maniac`
2. `Hypomone -> Telos/Nemesis -> Maniac`

In the second family, the diagnosed break is not Hypomone -> Maniac. It is Telos -> Maniac or Nemesis -> Maniac after a proven F2 state.

---

## Hypomone Goal Protocol

Hypomone can walk toward a large goal without becoming Telos.

A goal does not create Telos when it is:

- imposed by another subject;
- contractual;
- legal or juridical;
- survival condition;
- return-home condition;
- route requirement;
- prophecy accepted as external pressure;
- payment condition;
- escape condition;
- social obligation carried as burden;
- objective A that the subject follows while the true axis remains life/home/survival/care.

### Telos Conversion Test

Before declaring `Hypomone -> Telos`, ask:

1. Is the goal external or internal?
2. Does the goal govern load-bearing choices when it conflicts with comfort, survival, status, home or old bonds?
3. Can the subject abandon the goal and remain the same vector subject?
4. Is the subject carrying the goal as life-condition, or has the goal become the way the subject exists?
5. Does the official goal match the true axis-goal?
6. Which threshold made the goal internal?
7. Which price proves the subject has accepted the goal as axis?
8. Which consolidation shows continued axis-owned behavior after the threshold?
9. Did the goal arise from a collision, surface pressure or cataclysm? If yes, did it become internal or remain carried pressure?

Verdict:

- `external_goal_carried`: remains Hypomone.
- `axis_goal_accepted`: becomes Telos.
- `axis_mismatch`: official goal is not the true Telos axis.
- `false_telos`: text frames external-goal carrying as Telos without proof.

---

## Nemesis Refusal Protocol

Nemesis does not have to complete revenge or escalate to Catastrophe.

A valid `Nemesis -> Hypomone` return occurs when:

- the subject refuses to become the final instrument of answer;
- the subject chooses life over completed retribution;
- the subject accepts a non-catastrophic measure format;
- the subject lets law, time, witness, exile, mercy or another structure carry the answer;
- the retribution axis is exhausted or set down;
- price remains and the violated measure is not erased from memory.

Billiard note:

Another ball may carry or institutionalize the answer after Nemesis refuses. This must be diagnosed as trajectory transfer or compensation, not as failure by default.

---

## Maniac Return Protocol

Maniac may return to Hypomone when the obsessive axis loses authority and moral ambivalence returns.

Valid causes:

- disillusionment in own magic, method, god, mission or self-image;
- recognition of excessive damage;
- exhaustion of obsession;
- encounter with a living bond stronger than mania;
- proof that the obsessive axis cannot complete itself;
- voluntary rejection of self-granted right;
- survival after collapse of mania with paid aftermath.

If axis collapses but moral ambivalence does not return, route is usually:

```text
Maniac -> Chaos
```

not `Maniac -> Hypomone`.

---

## F3 Completion and Return

Crisis and Catastrophe are terminal actions, not permanent jobs.

If the subject executes the terminal action, survives, and the world continues, the route normally becomes:

```text
Telos -> Crisis -> after-state -> Hypomone
Nemesis -> Catastrophe -> after-state -> Hypomone
```

The returned Hypomone is not pre-arc innocence. It is life after F3, with price, memory, loss, altered world, altered bonds and no automatic restoration of the old self.

Absolute is different:

```text
Maniac -> Absolute
```

usually does not return to Hypomone because the subject has become vessel, principle, mask, total function, metaphysical form or world-ordering law. A return requires de-absolutization and should be rare, costly and explicitly mechanized.

Billiard note:

After F3 action, audit table state. F3 is valid only if the table surface or final configuration reflects after-state. If the story treats F3 as only a big scene without table change, diagnose false terminal action or underpaid table effect.

---

## Masking / Revelation / Extraction

A subject may be declared or perceived as one type while true vector belongs to another.

Extraction is not a transition. It is revelation of the true vector.

Valid extraction requires retroactive evidence:

- repeated pressure behavior matches true vector;
- declared language differs from decisive action;
- fuel/engine pattern points to hidden type;
- stabilizers and anti-stabilizers support hidden route;
- major choices reveal true axis/address/mania before the extraction;
- reader can reread earlier scenes and see the hidden vector.

Billiard note:

A hidden vector may be planted through repeated collision behavior. A ball may reveal itself only when struck by a specific other ball, by a cataclysm, or by surface pressure. Such revelation still requires retroactive evidence.

---

## F3 Ownership Rules

### Crisis Ownership

Crisis belongs to Telos.

Crisis requires:

```text
axis-goal + old-order blockage + threshold + rupture mechanism + price + after-state
```

Crisis asks:

```text
What old order must break so the future can exist?
```

### Catastrophe Ownership

Catastrophe belongs to Nemesis.

Catastrophe requires:

```text
violated measure + address + reproduction field + threshold + annulment mechanism + price + after-state
```

Catastrophe asks:

```text
What field reproduces the violation, and how is it made unable to repeat?
```

### Absolute Ownership

Absolute belongs to Maniac or to original non-human/metaphysical ontology.

Absolute requires:

```text
obsessive axis/principle + totalization mechanism + removal of outside + price/ontological lock + after-state
```

Absolute asks:

```text
What single principle is trying to make the world coincide with itself?
```

Billiard note:

A table may experience crisis, catastrophe or absolute pressure without a given ball personally owning Crisis, Catastrophe or Absolute. Always distinguish terminal form of the ball from terminal effect on the table.

---

## Moral Contour

Judge polarity by the story's moral contour, not by charm, suffering, bodycount, romance chemistry, saving, guilt or reader sympathy.

Light-side motion tends toward release, restoration, measure, truth, dignity, future and exit from evil.

Dark-side motion tends toward oppression, false order, control, exploitation, lie, power as end, dehumanization and reproduction of evil.

Gray stories still have contour. Infer what the story treats as exit and what it treats as reproduction of pressure.

Billiard note:

A ball may produce light effect through dark route or dark effect through light intention. Analyze:

```text
personal moral contour
collision moral contour
surface moral contour
final configuration moral contour
```

Do not reduce polarity to final table effect alone.

---

## Vector Billiards Protocol

Use this protocol whenever the task involves full plot analysis, multiple characters, season/tome/chapter map, synopsis construction, alternate route design, brainstorming, final configuration preservation or systemic revision.

### 1. Define the table

Specify exact story unit:

```text
scene / chapter / arc / season / tome / trilogy / closed version / whole saga
```

If the table is too broad, warn about scope blur.

### 2. Define initial and final configuration

List:

- starting positions of major balls;
- ending positions of major balls;
- surface conditions at start and end;
- known cataclysms;
- desired final lock, if any.

### 3. Identify balls

A subject becomes a ball only if it materially affects configuration.

Separate:

- major balls;
- secondary balls;
- stabilizers/destabilizers that are not full balls;
- surface elements;
- decorative subjects.

### 4. Audit each ball by normal NVAP

For each major ball:

```text
declared/perceived/true vector
floor/type
axis/engine/fuel
stabilizer/anti-stabilizer
route
threshold
price
consolidation
right to action
```

### 5. Map trajectories

For each major ball:

```text
initial position -> key thresholds -> key collisions -> prices -> consolidations -> final position
```

### 6. Map collisions

For each collision:

```text
node/scene
affected balls
collision rank
effect per ball
threshold/price/stabilizer/surface impact
```

### 7. Map collision accumulation

Check whether repeated tangential/corrective collisions prepare later threshold.

If threshold appears without accumulation or direct threshold event, diagnose missing preparation.

### 8. Map surface

Identify ongoing external pressures:

```text
war / law / economy / climate / magic / technology / geography / hunger / occupation / disease / time limit / social order
```

Distinguish surface pressure from ball subjecthood.

### 9. Map cataclysms

For each cataclysm:

```text
source: environmental or vector
surface alteration
affected balls
new thresholds
lost stabilizers
changed prices
closed/opened routes
configuration impact
```

### 10. Recalculate after changes

If a ball, route, collision, surface condition or cataclysm changes, identify required compensation.

### 11. Check compensation window

Determine whether the requested change can still fit inside the selected table.

If not, mark point of no return or request earlier-table rewrite.

### 12. Audit final configuration

Final state must be supported by trajectory budget.

If final configuration is preserved only externally, mark fake final lock or under-compensated configuration.

---

## Cataclysm Protocol

A cataclysm is a sharp surface change that affects multiple trajectories.

### Environmental cataclysm

Comes from surface without direct ball action.

Examples:

```text
meteor / earthquake / plague / storm / magical collapse / cosmic event / sudden famine
```

Audit:

1. What surface changed?
2. Which balls were affected?
3. Which routes closed or opened?
4. Which stabilizers were destroyed or created?
5. Which prices changed?
6. Did it create real thresholds or only stress amplitude?
7. Does final configuration require compensation?

### Vector cataclysm

Created by a ball, then becomes new surface for many balls.

Examples:

```text
weapon invention / ritual release / nuclear strike / magical law break / institutional coup / public revelation / engineered plague
```

Audit:

1. Which ball created it?
2. Did that ball have right to create it?
3. What type owned the action?
4. Was the action route-valid for that ball?
5. How did the surface change?
6. Which other balls had to recalculate trajectories?
7. Did the creator's personal type change, or only the table surface?
8. Did the cataclysm get paid and consolidated?

Key rule:

A ball can create a cataclysm without personally being Crisis, Catastrophe or Absolute. Do not confuse created table effect with personal terminal form.

---

## Collision Rank Protocol

### Tangential collision

Changes pressure, mood, suspicion, fuel intensity, reader perception or minor route tension. Does not alter trajectory grammar.

### Corrective collision

Alters trajectory direction, speed, caution, aggression, trust, risk tolerance or stabilizer strength. Does not establish new type by itself.

### Threshold collision

Creates a threshold after which old balance cannot hold. Requires price and consolidation to become legal movement.

### Configuration collision

Changes the table state: war begins, alliance breaks, regime falls, weapon appears, public truth shifts, whole group position changes, surface condition changes.

Invalid handling:

- treating tangential collision as transition;
- treating corrective collision as floor escalation;
- treating configuration effect as personal F3 ownership;
- treating one scene as one effect for all balls.

---

## Time Position Protocol

### Early collision

Sets rails, promises, wounds, debts, images of goal, first pressure, first lie, first bond.

Early collision may prepare future vector but does not prove it alone.

### Middle collision

Tests trajectory.

Reveals whether declared vector survives pressure or collapses. Often exposes true vector, weak stabilizer or false goal.

### Late collision

Pays, reveals, sharpens or locks prepared trajectory.

Late collision may not legally create an unprepared full route unless it is revelation with planted evidence.

### Final collision

Locks final configuration.

It must consolidate already gathered trajectory budget, not replace missing route.

### Compensation window

If a requested change occurs late, ask:

1. Does earlier setup already support it?
2. Can it be revelation rather than new transition?
3. Is there enough remaining space for threshold, price and consolidation?
4. Which other balls must compensate?
5. Has the point of no return passed?

---

## Right-To-Action Scan

For each load-bearing action, answer:

1. What type is active before the action?
2. Is the active type declared, perceived or true?
3. What axis/address/function/principle is active?
4. Does the action serve the engine?
5. Does fuel strengthen the engine or hijack it?
6. Does the action belong to the subject's current floor/type grammar?
7. Is the proposed transition legal in the matrix?
8. Which threshold gave the subject this action?
9. Which price follows?
10. Which consolidation proves the action changed the state?
11. If the action claims Crisis, what old order and after-state are defined?
12. If the action claims Catastrophe, what reproduction field is annulled?
13. If the action claims Absolute, what principle is totalized?
14. Does the action shift moral contour?
15. Is the action a collision? If yes, which balls are affected?
16. Does the action change table surface?
17. Does it create a cataclysm?
18. Does final configuration require compensation?
19. Verdict: `valid`, `edge`, `break`, `false_escalation`, `illegal_route`, `substitution`, `underpay`, `genre_break`, `undercompensated_configuration`, `surface_misread`.

---

## Billiard Scan

For multi-subject analysis or plot design, answer:

1. What is the table?
2. What is the initial configuration?
3. What is the intended or observed final configuration?
4. Which subjects are major balls?
5. Which subjects are secondary balls?
6. Which subjects are stabilizers/destabilizers but not balls?
7. What is the surface?
8. What are the active surface pressures?
9. What are the major collisions?
10. What is the collision rank for each major node?
11. Which collisions are compound?
12. Which thresholds arise from collision accumulation?
13. What cataclysms occur?
14. Which cataclysms are environmental and which are vector-created?
15. Which balls require trajectory recalculation after cataclysms?
16. What compensation supports the final configuration?
17. Where is the compensation window narrow or closed?
18. Does any final position survive only externally?
19. Which weakspots threaten the configuration?
20. What minimum construction requirements repair the table?

---

## Weakspot Codes

Original retained:

- `W01_SCOPE_BLUR`: version, arc or unit mixed.
- `W02_GENRE_MISREAD`: genre horizon ignored.
- `W03_MORAL_CONTOUR_FOG`: story measure unclear.
- `W04_READER_MORALITY_SWAP`: reader/self morality replaces story contour.
- `W05_DECLARED_TRUE_VECTOR_CONFUSION`: declared/perceived vector mistaken for true vector.
- `W06_ENGINE_FUEL_SWAP`: fuel mistaken for engine.
- `W07_AXIS_THIN`: axis exists as label but fails to bind behavior.
- `W08_RIGHT_TO_ACTION_FAIL`: key action is not owned by current axis.
- `W09_NO_THRESHOLD`: change arrives without vector-changing event.
- `W10_NO_PRICE`: action or transition skips its cost.
- `W11_NO_CONSOLIDATION`: new state lacks after-state proof.
- `W12_FALSE_F3`: F3 tools appear without field, price and irreversibility.
- `W13_NEMESIS_ADDRESS_SPREAD`: Nemesis address expands without field logic.
- `W14_TELOS_GOAL_LOST`: Telos goal replaced by ego, pain or control.
- `W15_MANIAC_UNNAMED`: obsession governs while text frames clean justice.
- `W16_CRISIS_NO_AFTER`: old order breaks without after-state.
- `W17_CATASTROPHE_NO_FIELD`: annihilation lacks defined field.
- `W18_ABSOLUTE_NO_PRINCIPLE`: huge scale lacks totalizing principle.
- `W19_BREAK_UNPAID`: break lacks recognition or aftermath.
- `W20_REVELATION_UNSUPPORTED`: reveal lacks retroactive evidence.
- `W21_FAKE_RESET`: completed vector continues by inertia.
- `W22_SUBSTITUTION`: alien action treated as structurally unchanged subject.
- `W23_F1_FORCED_UP`: complete first-floor mode is artificially escalated.
- `W24_ONGOING_CONFUSION`: ongoing function judged as closed trajectory.
- `W25_SWARM_SUBJECT_MIX`: collective force and commanding subject conflated.
- `W26_POLARITY_BY_BODYCOUNT`: killing/saving used as polarity proof.
- `W27_SPECTACLE_OVERRIDE`: spectacle overrides right to action.
- `W28_DECORATIVE_CONFLICT`: conflict does not pressure axis, engine or contour.
- `W29_STABILIZER_MISSING`: heavy fuel lacks stabilizer.
- `W30_WEAK_ANTI_STABILIZER`: corruption lacks plausible permission.
- `W31_POISON_FUEL_UNTRACKED`: poison fuel appears but arc ignores it.
- `W32_GENRE_PRICE_MISMATCH`: demanded price would transform genre while text refuses the shift.

Route-specific retained:

- `W33_ILLEGAL_ROUTE`: transition is not legal in the type matrix.
- `W34_EXTERNAL_GOAL_TELOS_FALSE_POSITIVE`: Hypomone carrying an external goal is mistaken for Telos.
- `W35_AXIS_GOAL_MISMATCH`: official goal and true axis-goal are conflated.
- `W36_TELOS_TO_CATASTROPHE_SHORTCUT`: Catastrophe is granted to Telos without reset-to-Nemesis or extracted true Nemesis.
- `W37_NEMESIS_TO_CRISIS_SHORTCUT`: Crisis is granted to Nemesis without reset-to-Telos or extracted true Telos.
- `W38_MASKED_VECTOR_UNPLANTED`: extraction/revelation lacks planted retroactive evidence.
- `W39_POST_F3_HANG`: Crisis/Catastrophe keeps acting as permanent state after completion.
- `W40_F3_RETURN_UNPAID`: subject returns to Hypomone after F3 without price, altered life or after-state.
- `W41_ABSOLUTE_FALSE_RETURN`: Absolute returns to ordinary Hypomone without de-absolutization mechanism.
- `W42_SWARM_CONDENSATION_MISSING`: collective pressure is treated as higher-floor subject without condensation into axis/address/mania.
- `W43_FUNCTION_AMBIVALENCE_CONFUSION`: Chaos function is mistaken for moral ambivalence or living Hypomone.
- `W44_NEMESIS_REFUSAL_MISREAD`: refusal of revenge is treated as arc failure rather than valid Nemesis -> Hypomone return.
- `W45_MANIAC_RETURN_UNSUPPORTED`: Maniac is returned to Hypomone without loss of obsessive authority and restored ambivalence.
- `W46_ILLEGAL_DRIFT_UNDISCLOSED`: analysis names drift toward a non-direct or forbidden destination but does not state the illegal direct route and legal delivery routes.
- `W47_OUTPUT_LOCALIZATION_LEAK`: visible output leaks internal English headings, labels, verdict values, route terms, floor codes or hybrid pseudo-translations instead of using the operator language.
- `W48_CANONICAL_TERM_ASR_DRIFT`: analysis accepts a speech-recognition error, misspelling or hybrid pseudo-term as a real NVAP type or system term instead of normalizing it.
- `W49_STRESS_AMPLITUDE_MISREAD`: stress, battle, adrenaline, rage, fear, harsh speech, protection of a bond or temporary over-limit action is misread as vector drift.
- `W50_HYPOMONE_MANIAC_SHORTCUT`: Hypomone is diagnosed as moving to Maniac directly, without proven Chaos route or prior legal F2 state.

Billiard-specific added:

- `W51_TABLE_SCOPE_BLUR`: table is not defined; versions, arcs, seasons, adaptations or saga layers are mixed.
- `W52_BALL_INFLATION`: decorative, local or one-scene subject is promoted to full ball without configuration effect.
- `W53_BALL_ERASURE`: configuration-driving subject is treated as background, stabilizer or decoration.
- `W54_TRAJECTORY_BUDGET_MISSING`: final position lacks necessary path, collisions, prices or consolidations.
- `W55_COLLISION_UNDERRANKED`: collision is treated as minor although it creates threshold or configuration shift.
- `W56_COLLISION_OVERRANKED`: tangential or corrective contact is treated as threshold or transition.
- `W57_COMPOUND_COLLISION_FLATTENED`: one scene's different effects on different balls are collapsed into one label.
- `W58_COLLISION_ACCUMULATION_MISSING`: threshold appears without prior accumulation or a clear threshold collision.
- `W59_SURFACE_MISREAD_AS_BALL`: external pressure is treated as vector subject without subjecthood.
- `W60_BALL_MISREAD_AS_SURFACE`: active institution, system, group or force with vector behavior is flattened into background condition.
- `W61_ENVIRONMENTAL_CATACLYSM_UNTRACKED`: surface cataclysm changes trajectories but analysis ignores it.
- `W62_VECTOR_CATACLYSM_UNTRACKED`: a ball-created surface change is treated only as personal action, not as table alteration.
- `W63_CATACLYSM_EFFECT_VECTOR_SWAP`: cataclysmic table effect is mistaken for the creator's personal F3 type.
- `W64_COMPENSATION_MISSING`: altered ball or trajectory lacks required changes in other trajectories.
- `W65_FINAL_LOCK_FAKE`: final configuration is preserved externally while internal route legality collapses.
- `W66_COMPENSATION_WINDOW_CLOSED`: requested change is too late for selected table without earlier rewrite.
- `W67_POINT_OF_NO_RETURN_IGNORED`: analysis changes a ball after the story passed a point requiring a specific trajectory budget.
- `W68_SURFACE_PRESSURE_UNTRACKED`: ongoing world pressure bends trajectories but is not included in the audit.
- `W69_FINAL_EFFECT_PERSONAL_TYPE_SWAP`: historical/world effect is assigned as personal hero type without checking the subject's own vector.
- `W70_TABLE_AFTERSTATE_UNPAID`: table surface changes but after-state, new rules or consequences are not consolidated.

---

## Severity

- `S0 note`: local clarity issue.
- `S1 minor`: weak support; repair can be local setup, line, beat or card field.
- `S2 moderate`: recurring ambiguity; add threshold, stabilizer, price, evidence, collision, compensation or route condition.
- `S3 major`: key action or turn threatens axis, route legality, collision logic, configuration or moral contour.
- `S4 fatal`: climax, finale or identity rests on illegal route, substitution, false terminal form, moral collapse, skipped price, fake final lock or impossible compensation.

---

## Plot Construction Protocol v3.0

When designing or auditing a plot:

1. Define `scope` / table and legal price horizon.
2. Define initial and final configuration.
3. List candidate vector subjects.
4. Select balls: major, secondary, stabilizing/destabilizing, decorative.
5. For each major ball, separate `declared_vector`, `perceived_vector`, `true_vector`.
6. Assign current floor/type.
7. Define axis/engine/fuel/stabilizer/anti-stabilizer.
8. Identify whether goals are external goals or axis-goals.
9. Select legal route from the matrix.
10. Define threshold, mechanism, price and consolidation for each movement.
11. Map trajectories from initial to final position.
12. Map collisions and rank them.
13. Check compound collisions per ball.
14. Track collision accumulation before thresholds.
15. Define table surface and active surface pressures.
16. Identify environmental and vector cataclysms.
17. Check how cataclysms alter table surface and trajectories.
18. If drift points toward a non-direct or forbidden destination, disclose illegal route and legal delivery routes.
19. For terminal actions, define old order / reproduction field / principle and table after-state.
20. Decide whether post-terminal life returns to Hypomone or locks/ends.
21. Check moral contour at personal, collision, surface and final-configuration layers.
22. If final lock exists, define required compensation.
23. Check compensation window and point of no return.
24. Reject spectacle that bypasses route legality, collision logic, surface change or final compensation.

---

## Output Contract for Plot Creation v3.0

Use the operator language unless the task demands another language or the operator requests compact canonical notation.

Keep NVAP type names as proper technical names: canonical Latin form or unambiguous transliteration into the operator's script. Do not semantically translate type names.

Visible output must localize headings, table fields and diagnostic labels.

Recommended structure:

```md
## [localized NVAP plot verdict heading]

[localized table/scope label]:
[localized genre/horizon label]:
[localized initial configuration label]:
[localized final configuration label]:
[localized key balls label]:
[localized surface label]:
[localized moral contour label]:
[localized main route/configuration risk label]:

## [localized ball map heading]

| [subject] | [ball status] | [declared/perceived/true vector] | [floor/type] | [axis/engine] | [fuel/poison] | [stabilizer/anti-stabilizer] | [confidence] |

## [localized trajectory map heading]

| [ball] | [initial position] | [route] | [key thresholds] | [price] | [consolidation] | [final position] |

## [localized collision map heading]

| [node/scene] | [affected balls] | [collision rank] | [effect per ball] | [threshold/price/stabilizer impact] | [configuration impact] |

## [localized surface and cataclysm map heading]

| [surface pressure/cataclysm] | [source] | [surface change] | [affected balls] | [routes opened/closed] | [compensation required] |

## [localized route legality heading]

| [ball] | [current type] | [movement] | [route legality] | [required threshold] | [price] | [consolidation] |

## [localized drift route check heading]

| [ball] | [observed drift] | [source of pressure] | [forbidden direct route] | [legal delivery route] | [required intermediate state/price/consolidation] |

## [localized final configuration check heading]

| [final position] | [supporting trajectory budget] | [missing collision/price/compensation] | [verdict] |

## [localized weakspots heading]

| [severity] | [code] | [location] | [diagnosis] | [vector/configuration damage] | [missing condition] |

## [localized construction requirements heading]

- [requirement] 1:
- [requirement] 2:
- [requirement] 3:

## [localized do-not-fix-by heading]

- ...
```

For small tasks, do not dump full structure. Use only the relevant layers.

---

## Canonical Term Normalization / ASR Guard

Operators may use audio input, dictation, fast typing or mixed-language notation. The model must not treat transcription noise as new NVAP terminology.

Canonical NVAP type proper names are:

```text
Hypomone
Chaos
Swarm
Telos
Nemesis
Maniac
Crisis
Catastrophe
Absolute
```

These names are closed type names. If the operator input contains a likely misspelling, speech-recognition artifact or hybrid form, normalize it to the closest canonical type when the surrounding context clearly points to one.

Billiard terms may also suffer ASR drift. Normalize likely variants of:

```text
table
ball
surface
trajectory
collision
cataclysm
compensation
final lock
configuration
recalculation
```

Do not create new type names, route names or table labels from ASR artifacts.

---

## Visible Output Localization Protocol

The kernel may keep canonical internal tokens in English. The operator-facing answer must not expose those tokens as ordinary interface headings, table fields, route labels or verdict values.

Visible output must be written in the operator language by default.

This applies to:

- section headings;
- table column names;
- row values where the value is a diagnostic label rather than a proper name;
- route explanations and route verdicts;
- billiard labels;
- surface/cataclysm explanations;
- weakspot explanations;
- final summary.

Type names are proper technical names and may remain canonical.

Ordinary NVAP and billiard technical terms are interface/system terms and must be translated or explained in the operator language.

Invalid visible output in non-English operator language includes:

```text
floor/type
Legal road
Threshold
Price
Consolidation
Scope
Genre/Horizon
Core subject
Main route risk
Valid as external goal
Edge Valid
F1 Hypomone
raw English billiard table headers
hybrid pseudo-translations
ASR-distorted type names treated as real types
```

Any visible answer that leaks internal English headings, column names, verdict values, route labels, floor codes, billiard labels or ASR-distorted pseudo-terms triggers `W47_OUTPUT_LOCALIZATION_LEAK` and may also trigger `W48_CANONICAL_TERM_ASR_DRIFT`.

---

## Do Not Fix By

- raising the floor because higher sounds stronger;
- treating an imposed goal as Telos;
- mistaking external Goal A for axis-goal B;
- sending Telos directly into Catastrophe;
- sending Nemesis directly into Crisis;
- giving terminal action without legal source, field/order/principle, price, irreversibility and consolidation;
- making fuel into the whole character engine;
- calling a character dark or light by bodycount, charm or suffering;
- treating Nemesis refusal as failure by default;
- returning Crisis/Catastrophe to normal life without paid after-state;
- returning Absolute to ordinary life without de-absolutization;
- making Swarm into a higher-floor subject without condensation;
- adding spectacle instead of threshold, route, price and after-state;
- reading stress amplitude, battle rage, adrenaline, cataclysm reaction or harsh conflict as drift without new right to action, threshold, price and consolidation;
- diagnosing Hypomone -> Maniac directly instead of requiring Chaos or a proven F2 break;
- treating every named character as a ball;
- ignoring a subject that actually drives final configuration;
- treating surface pressure as a ball without subjecthood;
- flattening a ball-created cataclysm into personal action only;
- assigning table effect as personal vector type;
- preserving final configuration without compensation;
- changing late trajectory after point of no return without earlier rewrite;
- flattening genre: comedy, survival, romance, serial, mythic and dark epic horizons carry different price regimes.

---

## Short Integration Formula

```text
NVAP checks whether a ball has the right to move this way.
Vector Billiards checks what this movement does to the table.
```

Expanded:

```text
ball legality -> trajectory legality -> collision legality -> surface impact -> cataclysm impact -> compensation -> final configuration legality
```

This is the core of NVAP-PLOT v3.0.
