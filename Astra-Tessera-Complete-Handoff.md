# Astra Tessera — Complete Codex Handoff

11 October 2026 · Edition 15

Read the current handoff first, then the chronology/checklist. Technical inventory and historical originals follow. This is an extensive reconstruction and source-document archive, not a literal chat export.

## Contents

1. HANDOFF.md
2. ANNOTATION_HISTORY.md
3. ACCEPTANCE_CHECKLIST.md
4. TECHNICAL_INVENTORY.md
5. HISTORICAL_PROJECT_DOCUMENTS.md


---

<!-- BEGIN HANDOFF.md -->

# ASTRA TESSERA — COMPLETE CONTINUATION HANDOFF

Prepared 11 October 2026 for Ravn and the next coding agent. Previous working agent: Rook. Snapshot: Edition 15, source commit `a54106f3bb8b37d50b1f618d1d70d06e35a5b922`.

This document is deliberately long. Read it before treating any existing feature as final or proposing a restart. It preserves the product, design preferences, interaction contracts, feature scope, failure history and transfer procedure. The accompanying annotation history and historical documents supply additional depth. This is NOT a verbatim export of the entire conversation; no claim is made that every past message or missing image was recovered. It is a source-grounded handoff based on the available conversation and project files. Do not invent remembered details.

## 1. What we are building

Astra Tessera is a digital-first, multi-universe collectible-card platform and proof of concept. The core pleasure is discovering a world, opening beautifully presented randomized packs, collecting illustrated cards, arranging a binder/collector room and showing the collection to others. The cards do not need game rules, combat stats, decks or competitive play. The user explicitly allowed fake TCG universes and non-playable cards.

The long-term concept includes officially licensed franchise collaborations and paid artists with distinct styles. Digital pack purchases would be inexpensive, with exact ownership quantities. Optional physical cards would be printed only from owned entitlements, with manufacturing/shipping costs rather than rarity-based markups. Combining prints, merchandise and binders could make shipping more efficient. This is a business concept, not a connected commercial service.

Current scope is entirely simulated: credits, recycling fragments, ownership, orders, products, social activity and creator identities are prototype data. The user clarified that unless someone picks up the idea, real selling may never happen: people can simply collect fake cards. Do not treat monetization, accounts, official IP licensing or a backend as prerequisites to polishing this proof of concept.

The user wants the prototype to communicate the real idea convincingly. “Simulated” is not permission for bland rectangular placeholder surfaces. Merchandise, packs, binders, table rewards, previews and peripheral pages matter as much as hero artwork. A finished-feeling experience matters even when checkout remains fake.

## 2. Identity and deployment — preserve these

- Product name: **Astra Tessera**. Earlier project name: Card Atlas / Rook Card Atlas. Old technical IDs and URL remain valid and should not be renamed casually.
- Existing private URL: https://rook-card-atlas.silly-llama-9439.chatgpt.site/
- Exact Site project ID: `appgprj_6ac94ebb79288191a53ff0e0d752dacf`.
- Last confirmed deployment: `appgdep_6acb5762628881918e6dc32712b7b33b`, succeeded.
- Last saved Site version: `appgprj_6ac94ebb79288191a53ff0e0d752dacf~appgver_4a8becbd2ae48191859e804962f3cb43`.
- Last source commit: `a54106f3bb8b37d50b1f618d1d70d06e35a5b922`.
- Audience confirmed owner-private at last publication. Do not widen it or create another Site as a migration shortcut.
- Hosting manifest: `.openai/hosting.json`, static directory `dist`.
- Original cloud checkout: `/workspace/sites/rook-card-atlas`. This is historical, not a Windows path to use on the new machine.

A ZIP transfers files, not Site authority, cloud chat state or connector credentials. Check authenticated Sites access before promising live updates. If unavailable, work locally and explain the gap. Never put a token in Git, a prompt, a ZIP or a handoff. The included Git bundle has source objects/history, not the old checkout's config, credentials or hooks.

## 3. How Ravn wants collaboration to work

Ravn supplies many annotations quickly, often with typos. Interpret the intended concrete behaviour, not the spelling. They have repeatedly lost annotations due to attachment-count limits. Acknowledge text even when screenshots fail; do not require them to rewrite everything. Distinguish “I received the note” from “I saved an artifact” and from “I implemented it.”

The user wants independent, substantial work, not constant permission checks, micro-changes or offers to continue. When authorized to make a big update, do the work through validation and delivery. When told “not yet,” “still testing,” “still writing,” or “wait,” accumulate feedback and do not start modifying the site. A clarification during active work is usually steering, not cancellation.

Be realistic, concise and candid. Do not be a yes-man or promise a perfect site, zero regressions, exact memory of unavailable old animations, guaranteed hours of work, a visible usage percentage, or access to another chat that has not been retrieved. The user has given usage thresholds before; do not claim you can measure account quota if you cannot.

The user has explicitly complained about one step forward/two steps back. Repair neighbouring behaviour, not only the selected screenshot. Prefer shared interaction logic over divergent implementations. Do not trade away working clicks to implement dragging or lose fluid motion to enforce boundaries. Reproduce before fixing if browser tooling exists. Show what was tested and what was not.

They like bold creative initiative, but proposed unfamiliar visual directions belong in **Design Lab**. They explicitly authorized multiple experimental versions, mixed options and comparisons so the normal site does not have to be repeatedly rolled back. Limit elaborate table studies to two worlds for now to save effort/usage.

They want an honest distinction between placeholders and the eventual finished look. Do not make them repeat “this needs real art” for every item. Keep a persistent final-art checklist. Equally, do not tell them everything is merely intentionally unfinished when there are real bugs. Missing art, provisional art, poor design and broken behaviour are different categories.

Avoid importing unrelated sensitive personal context. Relevant taste: broad gaming interests, especially immersive game worlds, sci-fi, fantasy, steampunk, collecting/cosmetics and showing off. Titanfall, Helldivers, BG3, Minecraft and Apex were examples of distinct universe mechanics, not proof of licensing or commands to clone those assets. The dedicated art-reference folders promised by two other chats are not in this transfer. Ask for them when needed; never pretend to have read them.

## 4. The visual standard

The desired result should look thoughtfully art-directed, not like a cheap generic AI-generated site. Strong compositions, recognizable shapes, intentional materials, world-specific objects and readable hierarchy matter more than indiscriminate particles or microdetail. Avoid homogeneous generated blur/noise and repeated stock-like compositions. Multiple art styles may coexist across universes/creators. The user explicitly invited learning from references and making original art; eventual artist/reference packs will guide that.

One coherent platform identity should contain different spaces: Discovery is a storefront/editorial entry; binder is a collecting room; opening is an in-universe ritual/table; print/merch is a product/proof studio; profile/lounge is showing off. Simply changing the layout inside the same background is insufficient. Yet the navigation and interaction conventions should remain understandable.

Background paintings must be composed for their actual positions. Reusing one universe hero image everywhere is provisional. Wide foreground tables plus a landscape beyond are now the preferred Lab approach. Long pages may need a second related artwork where the content changes subject; don't let the bottom suddenly become empty. Slow, subtle parallax/background movement was positively received, but must not obscure content or fight scrolling.

A “table” is a 2D immersive interface, not a 3D game level and not necessarily a literal rectangle photographed from above. The user clarified: same basic functional structure, drastically different look/feel by universe. Materials, frame shapes, surrounding architecture, fittings and props should feel part of the IP. The frame should resemble an in-world object, not a generic translucent rounded panel. The page below the global currency/back bar should belong to that universe. Borders and details should grow substantially richer for milestone and collectible/prestige tables.

They liked the cleaner open-scene experiment without the semitransparent panel. This was a preference for exploration, not a final commitment to removing every panel. The right-hand “Your pulls” UI can remain, optionally integrated with a physical box receiving filed cards. Any object added onto a desk must match the image's perspective, lighting, scale and material language; random emoji over a background do not satisfy the final standard.

Dynamic backgrounds should feel alive: drifting dust/fireflies, distant movement, or an occasional ship in a suitable space world. They liked drifting motion and the idea of a living window into the universe. Uniform stars represented as plain dots were criticized. Effects need world relevance and quality, not merely more toggles.

## 5. Current worlds and stable identifiers

| Visible world | Stable collection ID | Direction |
|---|---|---|
| Chaos Crew | `recrues` | Comic squad/gaming/voice-chat disasters; neon/technical hardware |
| Discount Dungeon | `donjon` | Comic fantasy dungeon; wood, metal, runes, vaults, chest/key |
| Orbital Oddjobs | `orbital` | Space workers/cargo/robots; ship panels, delivery code/pod |
| Clockwork Couriers | `couriers` | Steampunk postal dispatch, brass machinery/gears |
| Moonlit Menagerie | `moonlit` | Midnight hotel of strange creatures; silver, velvet, moon garden |

Five active original sets, twenty cards each, with legacy/archived content also present. Never derive IDs by translating visible names. The old `clockwork` archive is not the active `couriers` world. Preserve legacy ownership and custom edits. Cards should have English names, subtitles and humour based on visible artwork. The user mentioned a Wankil-like absurd tone initially; do not imitate exact copyrighted jokes or make the writing French. Good examples from the project include silly visual contradictions, underqualified staff and ordinary objects treated as heroic.

Rarity presentation must show through edges/borders and effects. Each world should have its own frame construction as well as rarity colour. Cut corners can be intentional, but their final rendering must be clean, never twitch or accidentally clip the artwork/sleeve. Cards should resemble physical TCG proportions, around 5:7, not overly tall posters. The user approved recent card back paintings and improving front art, but did not approve all art as finished.

## 6. Feature inventory and current status

“Implemented” below means code exists. It does not mean final visual approval. Inspect the source and browser for exact current behaviour.

### Discovery and universes
- Featured carousel with editorial cards, timed rotation, pause/resume and directional navigation. Arrows belong at the left/right edges without heavy boxes; pause should look like two separated bars, not Roman numerals.
- Announce new worlds immediately in the feature area/What's new. Clockwork and Moonlit arrival should be visible rather than silently added.
- Potential featured content includes arrivals, news, recommended packs, social content and merchandise; current news is editorial simulated content, not an external live feed.
- Collecting stats should relate to chosen/favourite/started franchises, not all cards on the entire platform. Clicking missing totals should expose per-universe breakdowns.
- Universe-led navigation replaces a primary Artists destination. Artists still matter on cards/detail pages and have portfolios.
- Universe pages give identity/art/pack calls to action enough space before the card catalog. The catalog may start about a small scroll below the hero rather than overwhelming the initial view.
- Catalogs use pagination rather than extremely long card grids. Apply comparable patterns across all worlds, not just one annotated world.
- Global back, search, scroll-to-top and What's new exist. Preserve meaningful back context.

### Binder and collection
- User chooses franchise folders. Show owned cards; optionally show missing cards for that franchise.
- Exact copy quantities are part of ownership. Hiding/removing a folder must not delete cards.
- Archived/paused worlds remain navigable when owned; legacy saves must survive additions.
- Paged album: at most three rows per page, with page size responsive to columns. Side page arrows follow scrolling. Redundant bottom arrows were removed by request. Page-turn animation is present/provisional.
- Binder shelf supports arrangements, hidden/displayed binders and row/column choices. Binders should be compact enough to display several without huge scrolling.
- Physical binder forms and artwork: leather books, futuristic holo binders, scroll-like fantasy forms, cases/guestbooks. Unique cosmetics should change silhouette/material/art, not just a flat colour.
- Free colour selection, advanced trim channels and previews exist. True selective recolouring of illustration regions is NOT solved. User prioritizes beautiful binders over mediocre recolourable ones. Don't apply a global pink tint to the whole painting and call that six-part recolouring.
- Binder customization panel has filtered owned/unlockable/world choices, stable overall dimensions and a separate preview. Selector scrolls within its area; options should fit without excessive outer scroll. No accidental native image drag.
- Latest decision: drag a binder onto another to **swap those two places**, including across rows. Other rows remain unchanged. Preserve the progressive movement/leaning that was approved. This supersedes insertion of intervening binders.

### Card details, credits and protection
- Inspect enlarged card, art, role/flavour text, rarity/number, owned quantity, artist/studio credit, printable state and story/journal.
- Credits on both card and detail view open a creator page. Back returns to the exact source context—same card modal, collection/filter/page/scroll—rather than sending the user to a generic page.
- Card story sits below/near the left card to use space and shrink the dialog. Journal/acquisition history was praised. Legacy acquisition dates must be honest, not invented.
- Actions include print queue, wishlist, protect/unprotect, showcase and recycle. Recycle/wishlist/cover affordances must be adequately visible, not tiny.
- Protection sleeve follows the card's transform and shape. Show protection in collection grids too. Putting on AND removing the sleeve should animate visibly, with reduced-motion handling.
- Cosmetic sleeve experiments add light/material effects across the card and at least border effects, not a detached static rectangle. Gilded, leaf/garden and holographic studies exist. These were approved as a good direction.
- Small showcase preview/dropdown in the detail flow allows checking or changing showcase without losing the current card context.

### Recycling, completion and currency
- Single and bulk recycling with filters, preview, protection and safeguards.
- User permits recycling the last/unique copy with two warnings. High rarities need conspicuous protection without making every common duplicate annoying.
- Never recycle protected/printed/reserved entitlements incorrectly. Invalid operations must not partially charge/delete.
- Automatic duplicate cosmetic conversion for rooms/binders/future trinkets was explicitly requested. Current fragment values are provisional.
- Crafting/duplicate protection/guarantee rules help completion. Pack odds and rules should be inspectable.
- Full-set completion rewards/profile icons, milestones and an extra cosmetic chance were liked. Numerical economy is not finalized.
- Insufficient credits must produce clear feedback at purchase, not a silent dead button. Demo refill is permitted.

### Packs and boxes
- Pack store reached through a universe stays in that universe. No redundant franchise dropdown; go back to change worlds.
- Visual single/bundle/box quantities. Loose bundles show multiple physical packs; a box is a dimensional object with lid/interior and packs, not a stretched single pack.
- Pack art is distinct original artwork. Objects feel physical through volume, lighting and restrained perspective.
- Drag/rotate inspection works on the store display itself, in inspection dialog and during opening where applicable. Reset angle on release; a separate Reset angle button was considered unnecessary.
- Interaction area fills its intended display region without an awkward unused bottom-left gap. Avoid janky angle jumps.
- Ready to open preserves the inspected quantity/world and shows its price.
- Purchased batches retain identity/world/queue; a new selected purchase should not accidentally open another world's old queue first.
- Multi-pack openings run successively; a toggle is allowed. A box has its own world-specific opening before its packs. Repeat-purchase repeats the original quantity, not always one pack.
- Open all at once summarizes the current batch. Closing that modal returns to the opening table, not too far back in navigation.

### Opening rituals
- Short real interactions with the object: foil drag tears the actual seam, key inserts/turns into a chest, directional command deploys a pod, dispatch mechanism for couriers, moonlit mechanism for its world. Do not copy the example literally to all worlds.
- The user liked Clockwork's ingenious dispatch-machine direction and later box animation. Preserve successful inventiveness.
- Manual and autoplay use the same meaningful animation path. Skip/autoplay has a button and shortcut. First two visits normal speed; third offers accelerated playback with opt-out and a later setting. Exact speed is provisional.
- Original bugs: duplicate keys, missing/clunky key turn, broken foil hit targets, two controls doing indistinguishable jobs, box showing wrong universe. Retest these when related handlers change.
- Effects scale with rarity and world; legendary should be an actual reveal moment, not only a different border. Next deliberately plays faster than the ceremonial reveal.
- Reduced motion and sound preferences remain. No audio files/paid runtime required for the synthesized current cues.

### Profile, showcase and community
- My showcase/collector room should be easy to reach. Navigation highlight follows current destination; it must not stick forever.
- Lounge begins with the user's own showcase, comments below, then discovering others, best pulls and leaderboards. Social data is fictional/local.
- Showcase slots should open an inline chooser: owned universes → owned cards → select, without dumping the user into binder navigation.
- Showcase supports drag ordering and keyboard/button alternatives. Neighbours respond gradually more as the held card approaches and return if it retreats. User described a magnetic/forcefield feeling: hesitant, fluid, noticeable, not an instantaneous jump. Recent stronger movement was desired.
- Unlike latest binder swap, showcase still uses insertion unless user changes that decision. Keep this distinction clear.
- Stationary click on showcase card must open detail. Dragging must not open detail, and credit clicks must still go to artist.
- Profile atmospheres, game favourites, Steam link and previews exist. Favourite games are fixed-size small boxes side-by-side, not cards that resize with quantity. Show game art; link to associated collection if it exists. Don't imply a Steam API/account connection from a manually entered URL.
- Visiting another collector should open their room/profile, not the current user's showcase. Completed-world honours/icons were praised.
- Watch together/spectator is local BroadcastChannel-based, not a live network multiplayer/social backend.

### Print and merchandise
- Printing only from owned available entitlements. Exact digital ownership is preserved under the current entitlement model while print history/consumption is tracked.
- Nine-pocket, multipage print planning and drag positioning exist. Combined print/merch parcel uses one simulated shipping estimate.
- Equal format/finish unit price regardless of card rarity. Premium physical products could cost differently, but business values await balancing.
- Merchandise should be rendered as believable products—binder, mat, sleeve, pin—not empty placeholders. Print & merch direction was positively received.
- No actual address collection, payments, shipments, commercial stock, tracking provider or real seller relationship is connected.

### Workshop, maintenance and safeguards
- Configurable rules/content and export/import exist. Prefer stable IDs and additive migrations.
- Malformed saves should not be overwritten; import validates and confirms replacement. Preserve old/custom catalog content.
- Help/onboarding/search/news/settings are implemented conveniences. Remove excessive repeated instructional prose as the final interface becomes self-evident, but keep accessible labels and non-obvious controls understandable.
- A dedicated mobile composition pass is deferred by user preference. Do not claim resizing desktop to a phone is final mobile design.

## 7. Exact normal opening interaction contract

This is the most regression-sensitive feature. Read the source history rather than guessing from the word “tilt.”

1. Draw outcomes are committed before animations. Animation skip/reload must not lose paid cards or grant extra copies.
2. Present a single offset pile of five cards (plus a cosmetic sixth if applicable). Small uneven offsets show physical depth; lower cards expose their backs, never unrevealed fronts.
3. Only the top card is interactive. First top card starts hidden. Dragging a hidden card moves it but **does not reveal or file it**. A deliberate stationary click or Reveal/Space flips it.
4. After that, a stationary click or Next sends the visible top card to the right and reveals the next. Do not require a second face-down flip for every card. Higher rarities sort toward the end while preserving actual outcomes and equal-rarity order. Multiple legendaries occupy the last positions.
5. During dragging, the card translates fluidly and leans/bends in the drag direction. This is not the pack-preview orbit effect. Current normal visible-card drag uses Y tilt up to 19 degrees, X up to 12, in-plane Z up to 8. These are implementation parameters, not eternal art direction. User likes the recovered original movement; keep it unless real testing calls for adjustment.
6. Remain within the agreed table bounds, with a slightly higher upper travel limit after Edition 15. Bounds must be calculated from stable geometry so transformed corners don't cause feedback jitter. Don't replace fluid movement with rigid translation to achieve bounds.
7. As the card approaches the right filing region, show a clear guide early enough to anticipate the drop. **Entering the zone is not filing. Releasing there files.** Releasing elsewhere springs home; pointer cancellation does not file or reveal.
8. Right-hand cards stack top-to-bottom in tidy stable slots. New arrival animates once. Do not rebuild/reanimate prior cards or flicker the box.
9. Clicking Next uses faster animation. Prevent rapid input from double-filing or double-charging. Unlock controls reliably when an animation is finished/cancelled.
10. Reveal, Next and Another pack share the exact same vertical action anchor. Face-down backs, face-up fronts, rarity effects and completion must not move it. Completion panel is card-sized and centred. Secondary completion choices sit below the primary button and disappear when a new pack begins.
11. Entry scroll puts the full table into the viewport while letting the global currency/back bar sit just above view; user can scroll a little up or use sidebar/bottom actions. This supersedes earlier “never scroll” demands. Do not make the whole screen cramped simply to retain the global bar.
12. Retest regular mouse click, tiny pointer jitter, intentional drag, reverse direction, corners, off-zone release, in-zone release, keyboard, reduced motion, last card, cosmetic last card and batch completion.

## 8. Design Lab contract and current Edition 15 behaviour

The Lab exists because final table design is undecided. It is a safe comparison area, not a production redesign applied without approval. Only Dungeon and Moonlit receive elaborate current scenes. Existing v13 paintings include a foreground desk and beautiful environment. At rest, the stack lies on that desk; manual/button pickup raises it to eye-level/centre. It stays raised on release. Pickup is not first reveal.

Once picked up, the user requested the same original normal opening behaviour: top-only drag, explicit first reveal, subsequent faces shown, bounded fluid movement, Next flight into right pull slots. Edition 15 moves toward that by using the normal card/back/pull-slot markup and common filing-zone geometry, but a separate Lab state/animation controller still exists. Do not falsely describe it as literally the identical complete controller. This remaining divergence is a useful refactor candidate once verified. Tests use DOM stubs and cannot certify 1:1 feel.

Current architecture choices: Open scene, Original table, Carved vault/Celestial window, Keeper's alcove/Moon garden pavilion. Rejected old Display cabinet/Collector's desk/Classic frame controls were removed; their old CSS remains historically in the cascade. Architecture is code-made SVG/CSS over the two existing paintings, not new commissioned art. User has not approved Edition 15 aesthetics yet.

Twelve detail layers: frame, foreground objects, glass panel, ambient light, motes, table inlay, side drapes, hanging lights, low mist, starfield, inscribed trim, display ledge. Latest user repeatedly reported being able to use only one at a time even though previous state tests passed. Edition 15 replaces buttons with native checkboxes and updates the scene incrementally without rerendering the controls. Multi-selection across architecture changes and saving is tested; actual browser composition still requires checking. Open scene must permit detail layers.

Physical receiver box below the right pull list is a Lab experiment. The animation currently targets a pull slot; a fully convincing “enters physical box then appears in list” sequence is not verified/final. Don't hide this gap if user asks.

Balanced is the selected motion preference; calm/lively remain comparison controls. Material studies are approved direction: sleeve inside card hierarchy, moving with the card, light/material effect not only static border. Saved combinations use a separate localStorage key and do not change normal room/inventory settings. No sample should award real demo inventory or consume credits.

## 9. Current checkpoint: completed versus awaiting review

Edition 15 code changes:
- Pairwise binder swaps and corresponding two-item preview.
- Absolute stage action anchoring rather than grid-only positioning.
- Another 16 pixels upper card travel.
- Singular “1 new card.”
- Explicit stationary showcase pointer-release opening of details.
- Native Lab checkboxes, in-place scene updates, combinations retained through architecture switches.
- Revised Lab stack/slots, pickup, face-up continuation, release geometry and filing animation.
- Replaced architecture options and perspective/material adjustments; physical receiver.

All 76 automated checks passed at snapshot. Latest full suite runtime was about 20 seconds. They include domain tests and one broad DOM-stub flow. The source was published successfully. **No real browser QA was possible in the old managed environment.** The user's annotations repeatedly revealed things those tests missed. Do not treat “76 passed” as evidence the Reveal button is now correctly placed in pixels, the details truly overlay correctly, or the motion is aesthetically right.

The next agent's first value should be reproducing the actual UI and checking these repairs. Do not jump directly to a massive new redesign and conceal these unresolved visual checks. Preserve the user-approved portions and compare the new browser result with the supplied descriptions.

## 10. Technical architecture and risk map

Buildless browser ES modules, HTML/CSS and localStorage. No package dependencies are required to run. `dist` is both source delivery directory and static output. `package.json` contains the Node test command. Serve over HTTP, not file://.

Key modules:
- `core.js`: state/accounting/validation and transactional operations.
- `catalog.js`, `edition-two.js`, `orbital.js`, `worlds-seven.js`: original and added content; stable collection/card IDs.
- `migration.js`, `experience-validation.js`: migration/validation; preserve custom text, ownership and archived content.
- `experience.js`: collecting/profile/queue/print/cosmetic logic.
- `collector-hub.js`: goals, journal, memories, milestone/table/room/print-planner state.
- `collector-custom.js`: colours/customization/extras.
- `community.js`: fictional community/game directory/guestbook logic.
- `presentation.js`, `presentation-dom.js`: sorted presentation and stable DOM updates.
- `opening.js`, `effects.js`: rituals/preferences/sound/reduced motion.
- `app.js`: main renderer, dialogs, event handlers and pointer lifecycle. Dense and increasingly large; use exact function scopes, not broad blind substitutions.
- `collector-views.js`, `views.js`, `workshop-view.js`: other page rendering.
- `edition-ten.js`: pagination, ordering geometry, binder/product/world object helpers.
- `edition-eleven.js`: fluid bounds, filing-zone geometry, original yielding and world frame.
- `edition-fourteen.js`: detail options and vacancy-chain preview for showcase insertion.
- `edition-fifteen.js`: pairwise binder swaps and scene architecture.
- `spectator.html/js`: same-origin local spectator channel.

CSS is accumulated: styles.css then edition-six through edition-fifteen. Later overrides and !important declarations are numerous. The same selector appears in several generations. Browser computed styles are essential when fixing layout. Do not assume a late rule wins without specificity/media checks. Refactor into shared scoped components incrementally only with before/after browser checks; do not wholesale rewrite during a bug fix.

Important current functions to inspect: `revealView`, `stageHTML`, `openingControls`, `renderStackLocal`, `advance`, `animateReveal`, `fileDraggedCard`, `pointerPaint`, `releasePhysical`, `springHome`, `prepareReorder`, `previewReorder`, `finishReorder`, `focusOpeningTable`, `designLab`, `labTableMarkup`, `labAdvance`, `previewDocument`, `showDetail`, `snapshot`, `back`.

Interaction risks:
- pointerdown.preventDefault can prevent native synthetic clicks; tests that dispatch only a click cannot reveal that.
- Bounds corrections must not count as user drag travel. Raw pointer distance is tracked separately; a stationary tap still reveals even if layout bounds would translate the card.
- Nested data-gesture elements must resolve to the intended top-level card, not only the back image.
- pointer capture and transformed geometry can feed back if remeasured incorrectly.
- suppressClick timing can swallow unrelated actions or allow duplicate dispatch. Preserve deliberate tap handling and test real events.
- Animations can finish after navigation/reset; guard old completion callbacks. Edition15 adds a Lab revision guard for world/reset; audit other state-changing Lab actions for stale callbacks if encountered.
- DOM rebuilding can replay arrivals, reset focus or interfere with a held pointer. Keep previously filed normal rail nodes stable.
- Fixed dimensions from multiple CSS generations can cause first face/back differences.
- Rarity/sleeve transforms must follow the same card hierarchy without clipping or detached overlays.

## 11. Persistence and migration

Main localStorage key is `card-atlas-v1`; it includes catalog/state export. Other keys include opening preferences (`card-atlas-opening`), effect preferences (see effects.js), and isolated Lab mix/favourite keys. The generated inventory lists exact strings found in the snapshot. Export/import is the supported portable collection backup; not every isolated browser setting is necessarily in the main export. Do not claim the ZIP includes the user's current collection.

Hosted Site origin and localhost origin have separate localStorage. Ports matter too. Opening localhost will initially show fresh demo state. Export on the hosted site, then import locally after validation; retain the backup. Never replace the live browser save just to take a screenshot. Use a separate browser profile/session or a copied save for QA.

Preserve exact quantities, printable entitlements, queued orders, protected cards, pending packs, current reveal, balances, rules, preferences, favourite folders, skins, tables, profile/showcase, journal/memories and archived cards. Content migrations should append/upsert carefully and retain user customization. Outcomes are committed before presentation, not on each animation frame.

## 12. Art assets, history and absent material

All tracked assets used by the source are included. `dist/assets` has edition directories. Existing docs/ART_ASSETS_* explain generation/provenance. Current v13 Lab paintings and v11 backs are present. Art remains original demo/concept work; fictional studio credits are not verified real artist commissions. Some older code-generated SVG art may still be used as fallback. Do not claim all final art is done.

The user has two other chats preparing large art-direction folders and later may provide hundreds of reference images. Those folders are not silently accessible and are not included here. A future art pass should use supplied approved references, not assume rejected experiments as canon. Art direction can change by world while card readability/shape/metadata remain consistent.

All available Git commits are included in source-history.bundle. Of particular interest, commit prefix `09d685a` was used as reference for earlier fluid drag feel. Inspect it in a separate worktree/clone and compare the relevant functions. Do not reset the whole app to recover one interaction. Edition13 `947f800...` fixed raw-motion tap classification; Edition14 `acad180...` introduced vacancy chains and control refactor; Edition15 is current. Earlier edition claims are history, not proof of present quality.

The conversation's screenshot filenames were reused across many batches, and many earlier uploads were absent at the time. This ZIP does not pretend to reconstruct an exact numbered screenshot archive. The latest screenshots were inspectable in the old session, but screenshots are not required for the source transfer. Textual annotation requirements are retained extensively. The original chat remains the authoritative conversational reference where available.

## 13. Recommended first session for the new agent

1. Read this handoff and the annotation chronology. Summarize only unresolved ambiguities, not everything the user already explained.
2. Run the existing tests from the extracted folder. Start the local HTTP site using allowed tooling. Verify the actual browser is available before promising visual validation.
3. Use a safe demo/test save. Verify card click/drag, fixed controls, pairwise binder swaps, stationary showcase detail, checkbox combinations and Lab sequence at 1304×884 and 1944×1244, the sizes used in feedback.
4. Check computed styles and pointer event delivery for any remaining bugs. Capture before/after evidence if supported. Preserve the normal site while adjusting Lab.
5. Check same Site deployment access separately. A working local folder is not authenticated publication access.
6. Present a concise readiness note: what transferred, what works, what you could visually verify and any remaining issue. Then continue user-authorized work.

## 14. What not to do

Do not make this into a gameplay TCG. Do not rename IDs to English. Do not delete archived sets. Do not overwrite browser saves. Do not silently switch binder swapping back to insertion. Do not reveal hidden cards just because dragged. Do not auto-file merely on entering a region. Do not add a flip click for every next card. Do not confuse pack rotation with card handling. Do not allow click suppression to disable card inspection. Do not claim all details mix just because a string test passed. Do not promote Lab experiments to production without a chosen direction. Do not leave product merchandise as empty placeholders while polishing only the hero. Do not equate prettier background with an in-world interface. Do not claim real partners/Steam/social/payments. Do not carry irrelevant personal sensitive data into project notes. Do not pretend a context handoff is literally the same running chat.

## 15. Completion standard

The aspiration is a beautiful, coherent, complete-feeling proof of concept. “Perfect” is the user's ambition, not a verifiable boolean. Deliver concrete improvements and accurately state limits. A good continuation makes the user repeat less, not more; safeguards earlier approvals; and uses actual browser evidence to prevent the regression cycle that caused frustration.


<!-- END HANDOFF.md -->


---

<!-- BEGIN ANNOTATION_HISTORY.md -->

# Extensive annotation and decision history

This is a chronological, faithful reconstruction of the visible project feedback, normalized for readability. It is NOT a literal full-chat transcript. Repetitions are retained where they establish importance. Quoted short phrases are exact or close user wording; all other entries are paraphrases. Later decisions override earlier ones. Historical “fix” requests may have code now but still need browser verification. Read HANDOFF.md for current contracts.

## A. Project origin and working relationship
- User called this coding worker Rook, distinct from Nyx/Vex planning chats. Wanted the developer idea discussed with Nyx retrieved rather than asking them to produce a handoff.
- Asked whether the agent could work roughly two hours while the phone/PC was off. Do not transform that into a capability guarantee; autonomous duration and execution environment vary.
- Early prototype request: stop when usage reaches 50% or prototype is done. Later said 49% usage remained and asked for a substantial overnight-quality pass. There is no dependable quota meter in this handoff.
- Asked to use personal/project context for UI taste. The important result is thoughtful gaming/collecting design, not inclusion of unrelated biography.
- Asked for two fake twenty-card universes, card-opening effects and funny text inspired broadly by absurd gaming humour. Cards need not be playable.
- Corrected all flavour text to English and jokes tied to what the illustration actually depicts.
- Named the site Astra Tessera.

## B. Original binder and sequential reveal definition
1. Binder has one folder per chosen franchise.
2. Shows cards owned; optionally includes unowned cards for that franchise.
3. Pack opening should be shiny, impressive and interactive, or completed by a button; effects may differ by universe.
4. After pack animation, five cards are a slightly offset physical stack, first top card hidden.
5. Click flips top card while four remain behind; edges help indicate rarity.
6. Next click sends visible card to right and shows second; repeat.
7. Right-hand results are arranged cleanly top-to-bottom.
8. Best rarities at the end; multiple legendaries occupy last/second-last, without implying every pack guarantees one.

## C. Early eight-comment repair/design batch
1. More emphasis on revealed cards; right-hand box flickered when main deck clicked.
2. Manual opening should be universe-specific: directional code → supply/drop pod for sci-fi; breaking a block for a suitable block game. These were examples, not one ritual for every universe.
3. Autoplay/skip button and keybind; first two full speed; third offers faster with opt-out; later settings can change preference.
4. Faint art behind card text was requested.
5. Card borders should express both rarity and IP, e.g. sci-fi technical versus fantasy ornate.
6. “Move right & reveal next” too verbose; use “Next.”
7. New arrivals animated twice and prior cards replayed; fix DOM/animation duplication.
8. Binder/discovery/opening/other tabs should feel like different spaces within a single vision; changing only content on a static shell felt weird.
9. Asked whether Astra light would help; this was a product/model question, not an instruction to silently change model.
10. Asked another universe and more detailed card artwork.

## D. Lost-annotation incident and collection of replacements
User lost a batch described as 23 annotations because max attachment count was twenty. Asked whether text visible in the chat briefly could be recovered. Do not claim nonexistent recovered material. User then told agent not to start, sending batches. Distinguish receiving notes from implementing.

### First replacement batch (five)
1. Add social features in navigation/experience.
2. Print studio should be a more interesting page.
3. Discovery featured rectangle like a Steam carousel: new arrivals, social content, recommended packs, merchandise from IP sellers; merchandise could help combined shipping.
4. Social content lower down too.
5. Discovery statistics based on user's favoured/started universes, with per-IP missing breakdown on click.

### Second replacement batch (seven)
1. More interesting bespoke background artwork across pages.
2. Free layout customization; unlockable cosmetic designs. A rare bonus sixth card could award a franchise binder.
3. More manageable, interesting binder design.
4. Allow unique/last-card recycling but two warnings; high rarities especially protected against accidents without constant annoying warnings.
5. Missing flavour text on a detailed card must be restored.
6. Artist credit on card and detail, linking to all creator work.
7. Filtered mass-recycle button.

### Third replacement batch (eight)
1. Primary browsing should be IP-based, not artist-based.
2. Buy/open multiple packs successively; boxes contain X packs and have their own IP-specific animation.
3. Final opening ceremony needs more effects and universe character.
4. Card backs should have a dedicated IP-specific artwork.
5. Open another pack directly from reveal screen.
6. Reveal effects get richer by rarity; legendary and above deserve real animation.
7. Better IP borders and much stronger card art.
8. Opening scene background fits universe. Mouse dragging can send cards right on release; otherwise spring to centre, like a physical TCG.

### Fourth replacement batch (five)
1. Global back button.
2. Chest should use a key, not mindlessly apply “break something” example to all objects. Be creative per IP.
3. Explicit insufficient-credit feedback.
4. Actual mouse-on-pack tear, rotate/inspect the pack; future cards have light/shine changing with tilt.
5. Next plays animation faster.

## E. First broad refinement after naming
User authorized all notes plus independently identified improvements, imagining a finished beloved site. Asked if switching model was safe; don't infer features from model name.

### Ten new comments — then explicit wait
1. Appearance options need live previews, use empty side area.
2. Featured carousel rotates automatically; arrows on outer sides, no boxes.
3. Hero can contain news of the day/other content.
4. Card art and borders still unfinished.
5. Universe page needs more identity/space and stronger pack CTA; catalog a little lower.
6. Packs need original art and physical movement.
7. Entering pack store from a universe should not ask to choose universe again.
8. Make quantity selection visual.
9. Loose bundles show more packs; box is actual opening box with packs inside.
10. Selected multi-pack batch automatically continues into next pack.

### Twelve opening/binder comments — still wait
1. Tear animation still needs substantial work.
2. Special card bends sideways with drag to reveal shine; dragging initial hidden card must not reveal it.
3. Next/next-pack belongs below centre stage; top corner is Open all.
4. Manipulate pack during opening too.
5. Autoplay and Tear seal were indistinguishable; clarify/consolidate workflow.
6. Appearance animations should be adapted to genuine illustration, richer effects.
7. When holding card aside, next card exposes back art only.
8. Cursor-following shine approved; keep it.
9. Binders need unique colours/shapes.
10. Examples: futuristic holo binder versus fantasy scroll.
11. Shine lagged above cursor when dragged downward; coordinate math needed correction.
12. Artist visit → Back restores exact previous card/context.

### Sixteen detail/customization/pack comments
1. Recycle action larger.
2. Protect action good; sleeve animation suggested.
3. Showcase preview/link/modal below card actions; close it to return to same detail.
4. Unique binder shape/art; free colour control for six separate parts like game character customization.
5. Cover action more visible.
6. Page backgrounds still too similar/empty.
7. Empty showcase slot opens universe then card picker in a popup, not a navigation detour.
8. Profile customization/social/game/Steam showcase possibilities.
9. Opening table navigation above universes.
10. Pack inspection rotation smoother.
11. Same manipulation during opening.
12. Box wrong universe and bugged; richer universe-based animation.
13. Previous key still visible beneath new key; turning clunky.
14. Legendary shine laggy.
15. Card angling clunky.
16. Key turn lacked animation.

### Two further notes
1. Rotation should already work in pack store, not only inspection popup.
2. Directional input icons should use one consistent arrow design.

## F. Placeholder/final-art discussions
1. Backgrounds must eventually be specially composed for their page, not reuse three universe images.
2. Pause bars need spacing so they don't look like Roman numerals.
3. Asked whether a broad polish instruction automatically includes replacing/finishing placeholders; answer must be yes to the intended scope, but do not falsely claim every current flaw was deliberate.
4. User explicitly did not authorize work during these questions.
5. More appearance colours/options.
6. Preview can switch pages to demonstrate density and other settings, not just show an abstract sample.
7. Binder colour changes should affect chosen illustrated/material regions, not globally tint the future artwork pink.
8. Drag binders into chosen locations; detailed physical IP binder requirement should not need repeating.

### Eight pack/binder notes — still writing
1. Recycle desk and wishlist buttons larger.
2. Whole pack display square interactive but shorter height; returns smoothly on release.
3. Box still unfinished; loose pack bundles good.
4. More physical volume/depth to packs.
5. Ready to open from inspection keeps selected quantity and shows price.
6. Seal drag stopped working.
7. Actual tear visibly opens actual pack.
8. Cards too tall; proper TCG proportions.

### Two corner notes and authorization
1. Corners looked broken and cursor at corners caused twitch.
2. Cut corners might be intended IP frame shape; acceptable test but final must be cleaner.
3. Add two worlds, fix notes, self-audit, then substantial polish pass.
4. Sleeve always fits card.
5. Showcase manual order; strengthen showing-off experience.
6. Easier profile/showcase access.
7. Profile atmosphere options need previews.
8. Opening table adapts per universe.

## G. Two new universes and first post-expansion review
New worlds Clockwork Couriers and Moonlit Menagerie added. User wanted carousel announcement at launch, not silent addition, while explicitly pausing changes during testing.

### Fourteen comments
1. Appearance preview should show actual rendered page/current collection, not vague representation.
2. Lounge starts with own showcase, comments, then other people/leaderboards/best pulls.
3. Favourite game gets an image and links associated collection if available; this can encourage discovering packs.
4. Drag cards by hand to reorder, not only arrows.
5. Scroll-to-top on long pages.
6. Card art improving; shine fix approved.
7. Pack movement area fills display region; avoid bottom-left emptiness.
8. Box should have apparent 3D volume (not a 3D game).
9. Pack/card object needs volume too.
10. New page entered slightly scrolled, hiding Back; fix navigation positioning.
11. Gear mechanism animation broken; don't defer a bug forever as “polish.”
12. Many art styles exist; reference concept-art styles to avoid uniform AI look.
13. Moonlit opening needs more creativity.
14. Unique IP mats/world opening space, like opening cards inside that world.

### Nine follow-ups
1. My showcase stays highlighted incorrectly.
2. Favourite games small fixed-size side-by-side tiles, like compact Discord cards.
3. Tile size must not depend on count.
4. Card drag filing bounds broke after background changes; card passed through right tray.
5. Entire area below global currency/back bar changes to IP style, including shapes/materials—not only a background.
6. Open-all modal closes back to same opening table.
7. Reset angle button unnecessary if release resets it.
8. Clockwork dispatch ingenuity praised.
9. Earn/unlock new opening tables through cosmetic cards, with richer designs.
10. Asked for feature ideas beyond polish; don't confuse an agent proposal with an approved commercial requirement.

## H. Requested massive update and “final” quality standards
User wanted all notes plus an independent first-time-visitor audit and substantial polish, not many tiny updates. Allowed asking to research finished sites for ideas. Requested written uncertainties so they could compare what the agent considers “finished.” Ambition: beautiful detailed art, complex thoughtful features. Do not literalize “no one could think of anything to add” as a completion guarantee.

### Fifteen notes during shop visit
1. Background parallax: follows scrolling more slowly/smoothly, bespoke composition per location.
2. Merchandise must receive art/polish too even as simulated proof of concept; no plain placeholder slabs.
3. Small binder strip needs artwork.
4. During drag, neighbours make space naturally with animation, not teleport after drop.
5. Phone UI needs a later dedicated redesign/resizing phase.
6. Print & merch direction approved.
7. Collector-room binders smaller to fit more.
8. User chooses displayed binders; rows support manageable overview.
9. Final UI can remove repeated small explanatory prose.
10. Big polish means everything: backgrounds, effects, binders, detailed tables—not isolated upgrades.
11. Binder after three rows should turn page, not endlessly scroll; home/print may remain long when appropriate.
12. Card story left to reduce wasted space/modal size.
13. Showcase preview as dropdown.
14. Protection animation more visible.
15. What's new praised.

### Thirteen opening/collection notes
1. Universe catalogs also paginate; generalize features where needed without requiring each world named.
2. Opening room attractive but still just a pretty box. Add in-world materials/assets/trinkets and environmental integration.
3. Drop guide appears on approach; no auto-filing until release.
4. Card cannot leave table bounds into header/far left.
5. Initially wanted entire table on screen without scrolling.
6–7. Fill unused left/right space.
8. Nearly physical/in-universe 2D atmosphere; user asked whether this intent was understood.
9. Room selector should avoid needless small scroll to finish viewing.
10. Reward table choices need vastly more visual detail.
11. Repeat purchase matches original five-pack/box amount. Box animation praised.
12. Duplicate cosmetics auto-recycle.
13. Completed-set extra cosmetic chance liked.

## I. Next repair cycle, clarified priorities
1. Asked again about PC-off coding; avoid claiming local tools work when PC is off.
2. Authorized large overnight pass with 49% usage remaining.

### Thirteen motion/layout/customization notes
1. Cards take slightly less space. Restore fluid original drag, retain boundaries; new motion too rigid.
2. Right drop guide should appear sooner.
3. Existing stage space/direction partly approved.
4. Border details should look like in-world object, not necessarily literal tabletop.
5. Fill available width.
6. Completion actions three stacked rows again.
7. Reward table details/border/objects grow dramatically per tier.
8. Relax earlier all-on-screen rule slightly if too cramped; header can be a little higher.
9. Page change button beside catalog.
10. Binder-choice boxes smaller.
11. Customizer fits viewport.
12. Scroll binder selector in bounded region, options below; filter franchise/owned/unlockable.
13. Preview image should not native-drag.
14. Two other chats preparing reference folders; later hundreds of references. Not provided here.

### Three follow-ups and explicit answers
1. Side page button in binder too.
2. Advanced recolouring should map selected palette colours/parts, not wash whole art.
3. Completed collection gives cool profile icons.
4. Card drag originally perfect before bounds broke; wants that recovered.
5. Clarified not actual 3D; still a website.
6. Each table genuinely distinct world, same functional ground structure.
7. Neighbour tilt gently/hesitantly pushes away proportional to approach, returns on retreat, like a forcefield. Existing movement nearly right at one point, then too weak later.
8. If selective binder recolouring too difficult, scrap that part; good-looking binder wins.
9. Physical design/pricing later; provisional economy can be balanced after overall concept settles.
10. Fake currency/collecting can be final prototype scope; no real selling requirement.

## J. Scroll policy and next interaction reviews
### Twelve notes
1–2. Latest scroll decision: on opening-table entry, scroll global currency/back bar just above view so full table fits. User can scroll up a little to use it, or use sidebar/bottom choices.
3. Showcase neighbour response needs more visible motion.
4. Completed-world honours praised.
5. Long print page needs another background artwork lower down where subject changes.
6. Visit showcase opens that person's room/profile.
7–8. Binder customizer outer size stays fixed when changing IP/filter, no shrinking/jumping.
9. Reduce top whitespace so colours fit.
10. Side page arrows that follow scroll praised; remove duplicate bottom paging arrows.
11. Protected cards visibly sleeved in binder; future collectible effects such as gold/fairy leaves.
12. Binder page-turn animation idea.

### Three card-motion notes
1. New card-back art praised.
2. Border still needs creative direction.
3. Hover tilt good, but drag only static translation; restore original drag animation later, not while annotating.
4. User distinguished drawn-card drag tilt from pack preview; must not substitute.
5. First Reveal/Next button sometimes higher, then slides down after first draw; stable anchor required.

### Two notes plus Lab authorization
1. Room previews need work; normal/milestone visually distinct; milestone/collectible should be spectacular.
2. “6/6 revealed · best pulls at end” helper text not needed in final release.
3. User will supply art reference folders later.
4. Add test branch/Lab to compare many bold table/design alternatives without breaking normal site.
5. Neighbour motion: earlier too much, later too little; find middle ground.
6. Other experiments allowed in Lab too.

## K. Edition13/14 lead-in
### Five bugs/approvals
1. Completion content should remain centred in table.
2. Drag works, click-to-reveal broken; user explicitly said concentrate, avoid regressions.
3. Collection journal/card story praised.
4. Animate unprotect too.
5. Showcase still needs more neighbour movement.

### Six Lab notes
1. Sleeve attached to moving card, not detached overlay.
2. Sleeve should add effects, at least border effects.
3. Tiny canned motion test insufficient; expand to hands-on area.
4. Toggle/mix architectural details.
5. Cleaner open-scene without semitransparent window liked, but still undecided about in-world frame.
6. Each scene painting has foreground table + beautiful landscape; initial stack lies on table, then rises to centre/eye-level and continues ordinary opening.
7. Go bold/high detail as if final, but only two tables to save effort.

### Seven normal-table notes
1. Completion box same size as cards.
2. Completion controls slimmer.
3. Reveal controls slimmer too.
4–5. Raise upper movement boundary to progress line; existing upward travel only millimetres.
6. After first draw controls shift; no need active-stage box, just stable Next.
7. Another pack occupies same place as Reveal/Next; end secondary buttons below.

### Plain text when annotations failed
1. Architecture options barely distinguishable.
2. Detail toggles seem one-at-a-time; wants 2–3× options and mixability.
3. Manually picked-up stack stays raised.
4. Explicit first reveal; after that next sample fronts stay visible.
5. Attached sleeve material study good.
6. Motion preference: balanced.
7. Binder neighbours move toward vacated space, not into occupied items. Later further refined to pairwise swap.
8. Showcase more movement.
9. Text saved although screenshots absent; asks whether enough to fix with preceding notes.
10. “really make sure to fix not add problems.”

Edition14 implemented vacancy-chain reordering, anchored shared control markup, card-sized completion, higher bounds, sample reveal fixes, twelve layers and stronger architecture differences. Tests passed; later feedback showed layout/toggle issues remained. Do not equate the release summary with acceptance.

## L. Latest twelve annotations — Edition15 basis
1. Binder movement animation now good. Across rows, do NOT move whole chain/row: targeted book moves into source place, held book takes target place. Pairwise swap, keep motion.
2–3. Reveal starts too high/touching the stack; Next and Another pack already at preferred lower position. All should use latter anchor.
4. Upper drag limit almost perfect, allow slightly more.
5. Table-choice previews must match actual screens; defer until final screens selected.
6. Grammar: “1 new cards” wrong.
7. Lab after pickup should behave one-to-one like normal table, including top-only grabbing, Next/rightward filing. Add only pickup, retain normal flow.
8. Open scene seems to block details. Reject Display cabinet, Collector's desk and Classic frame. Keep open scene, original normal table and try new genuinely polished IP-tied architectures. New background art may be added if needed and selectable.
9. Details still seem one-at-a-time. Drifting movement nice, stars plain dots. Think living view into universe. Keep pull panel, perhaps a physical box receives the cards in same region. Open scene or genuinely good frame still undecided.
10. Inscribed trim liked as an idea for suitable universe. Objects must fit world and perspective/position on desk.
11. Higher quality details will make experiments judgeable.
12. Showcase cards still must click open detail.
13. User reminded agent during implementation: fixes/updates must not break something else, like prior card handling; otherwise praised work.

Edition15 code was published and 76 automated tests passed. All twelve notes are documented in EDITION_15_REVIEW.md. No subsequent user visual acceptance of Edition15 is in this transfer. Important qualification: Lab still has a separate sample controller despite shared DOM pieces; no actual browser test certified 1:1 feel.

## M. Transfer conversation — latest instructions
1. User asked if Codex mode would make work easier. Agent explained browser testing is the key missing capability, not mode name alone.
2. User clarified cloud phone-created chat/project cannot simply appear as local E.M.A/Vex projects do. Needs a new local project/chat.
3. Agreed path: transfer a source folder/ZIP and extensive handoff. Existing cloud chat is not automatically the new Codex chat.
4. Preserve code, artwork, tests, history, feature knowledge, preferences, annotations, unfinished work and publication identity. Browser inventory separately exported from live site.
5. User explicitly requested a VERY extensive note, even much of conversation if helpful, leaving nothing to chance.
6. This package answers that request with structured current decisions, extensive chronology, original historical docs, function/action/asset map, regression checklist and Git bundle. It does not pretend to contain an unavailable literal chat export.


<!-- END ANNOTATION_HISTORY.md -->


---

<!-- BEGIN ACCEPTANCE_CHECKLIST.md -->

# Acceptance and regression checklist

Use real browser interaction when available. Automated tests supplement, not replace, these checks. Test at 1304×884 and 1944×1244 initially. Mobile is a separate later design phase; don't introduce obvious overflow meanwhile. Preserve user data by testing a copied/exported save or fresh isolated browser profile.

## Transfer readiness
- [ ] All dist JS/CSS/assets resolve locally over HTTP; console has no startup errors.
- [ ] Existing source tests pass; note environment/runtime.
- [ ] Old deployed private site remains unchanged by local testing.
- [ ] Main export/import can move a copied save between hosted origin and localhost without quantity loss.
- [ ] Publication access is verified separately, or clearly marked unavailable.

## Opening controls and interaction matrix
Repeat with a normal five-card pack and a cosmetic sixth-card pack.
- [ ] Reveal Y position equals Next Y position equals Another pack Y position within 1px, before/after animations settle.
- [ ] No overlap between back stack and control; completion panel width/height matches card.
- [ ] Stationary pointerdown/up reveals one card exactly; no extra filing from synthetic click.
- [ ] Small involuntary jitter still counts as click.
- [ ] Deliberate hidden-card drag does not reveal or file.
- [ ] Lower cards show backs only; cannot interact with underneath cards.
- [ ] Visible-card click files once and next front appears automatically.
- [ ] Drag direction gives fluid sideways/in-plane lean, not rigid translation or pack orbit.
- [ ] Cursor shine follows actual foil surface without lag/vertical offset.
- [ ] Corners do not jitter or clip sleeves.
- [ ] Upper bound gives expected travel; left/right/lower boundaries remain correct.
- [ ] Drop guide appears before release; hovering over it does not file.
- [ ] Release in zone files once; release elsewhere springs home; pointercancel does not file.
- [ ] Right column does not flicker or replay earlier arrival animations.
- [ ] Next is faster; double-click and rapid Space do not duplicate/skip/charge twice.
- [ ] Legendary and cosmetic presentations don't change inventory or layout anchors.
- [ ] Last-card file centres completion; singular/plural correct; secondary actions below.
- [ ] Reduced motion completes same state transitions without getting stuck.
- [ ] Scroll on entry shows table; Back accessible by slight upward scroll/sidebar/bottom actions.

## Packs and queue
- [ ] Pack/store/inspection/opening manipulation consistent; reset on release without jump.
- [ ] Foil drag tears actual seam; key inserts/turns once; no duplicate key.
- [ ] Direction arrows consistent; autoplay/skip works through each ritual.
- [ ] Wrong directional input resets appropriately; correct input completes.
- [ ] Box shows correct world, quantity, lid/interior/packs.
- [ ] New purchase prioritizes its own world/batch without discarding old waiting packs.
- [ ] Batch automatic next optional; repeat purchase preserves quantity.
- [ ] Open all summary closes to same table.
- [ ] Insufficient credits clearly explained and does not mutate state.
- [ ] Reload/skip during animation preserves committed pulls exactly.

## Binder and showcase gestures
- [ ] Same-row and cross-row binder drops swap only two items.
- [ ] All unrelated binder positions unchanged.
- [ ] Target progressively approaches vacated slot; retreat reverses it; no sudden premature save.
- [ ] Off-target release/cancel restores; valid release saves and survives reload.
- [ ] Showcase insertion retains smooth neighbour preview and only saves on release.
- [ ] Stationary showcase click opens selected detail; drag does not open modal.
- [ ] Artist credit and showcase arrow/control buttons do not start unwanted drag.
- [ ] Keyboard/button reorder alternatives remain.

## Design Lab
- [ ] Open scene permits any combination of detail checkboxes.
- [ ] Enable three details; disable middle; other two remain visibly enabled.
- [ ] Toggle details without losing focus/pickup/reveal progress.
- [ ] Change architecture/world; inspect expected retention/reset rules.
- [ ] Save/restore combination retains every enabled/disabled option and material/motion preference.
- [ ] Resting stack lies on pictured foreground desk.
- [ ] Manual pickup remains lifted on release; does not reveal face.
- [ ] After pickup, click/drag/Next/drop behaves like normal opening.
- [ ] Hidden sample drag doesn't reveal; only top card grabbable.
- [ ] Right filing flight goes to intended area; physical receiver doesn't block text/drop region.
- [ ] Reset/switch world during animation cannot mutate the new scene through stale callback.
- [ ] All five samples progress exactly once; samples never alter actual inventory/credits.
- [ ] Sleeve follows full card, retains border and material effect; balanced default.
- [ ] Architecture visibly distinct; frames and objects match perspective and don't cover cards.
- [ ] Atmosphere belongs to world; reduced motion stops ambient motion.

## Navigation and detail context
- [ ] Back from artist restores exact card modal, source collection, page, filters and scroll.
- [ ] Showcase picker stays modal: universe → card → selected slot.
- [ ] Showcase dropdown closes back to detail.
- [ ] Other collector links open other collector room/profile.
- [ ] Correct nav highlight; Opening table and My showcase easy to find.
- [ ] Catalog/binder side arrows follow scroll; no redundant bottom arrows.
- [ ] Customizer outer dimensions stable across filters; selector inner-scroll only; colours fit.
- [ ] No native image dragging in previews.

## Data/accounting
- [ ] Add worlds/content without losing legacy archives/custom edits.
- [ ] Owned counts, locks, printed/reserved copies and pending queue survive export/import/reload.
- [ ] Recycling common spares, last-copy double confirm, protected refusal, high-rarity safeguards.
- [ ] Bulk recycle preview equals result; cancellation no mutations.
- [ ] Duplicate cosmetic automatically converts once and records correct result.
- [ ] Print only available entitlement; equal rarity-independent unit price; combined parcel consistent.
- [ ] Bad import leaves existing save untouched; corrupt storage not silently overwritten.
- [ ] Milestones/journal do not invent legacy dates or double-award rewards.

## Visual approval — record separately
- [ ] Current scene choice approved by Ravn, or clearly still Lab experiment.
- [ ] Actual previews reflect chosen final rooms (deferred until choice).
- [ ] Dedicated page art fits its space; long print page doesn't end in accidental blankness.
- [ ] Cards, binders, packs, merch, reward previews and small shelf assets all receive attention.
- [ ] Readable English flavour tied to image; no missing copy or excessive tutorial clutter.
- [ ] No claim of final art before reference folders and user review.


<!-- END ACCEPTANCE_CHECKLIST.md -->


---

<!-- BEGIN TECHNICAL_INVENTORY.md -->

# Technical inventory — generated from Edition 15

This inventory describes files present in the transfer, not a certification that each path is visually finished.

## Source checkpoint

```text
a54106f 2026-10-11T11:30:44+02:00 Update Site source
acad180 2026-10-10T16:22:02-07:00 Update Site source
947f800 2026-10-10T15:43:58-07:00 Update Site source
7af9dc9 2026-10-10T15:09:14-07:00 Update Site source
fb7fa74 2026-10-10T14:30:05-07:00 Update Site source
cdc1e26 2026-10-10T13:40:00-07:00 Update Site source
d747dc0 2026-10-10T12:51:00-07:00 Update Site source
8922343 2026-10-10T12:20:31-07:00 Update Site source
99ccb63 2026-10-10T11:44:38-07:00 Update Site source
09d685a 2026-10-10T11:06:57-07:00 Update Site source
459a611 2026-10-10T10:00:24-07:00 Update Site source
33ffde6 2026-10-10T08:44:44-07:00 Update Site source
fa6707d 2026-10-10T05:29:41-07:00 Update Site source
88ab65b 2026-10-10T04:56:16-07:00 Update Site source
65fa775 2026-10-09T22:40:34+02:00 Update Site source
```

## Runtime

Buildless HTML/ES modules. No package dependencies. Serve dist over HTTP. Tests require Node.js. Source snapshot was tested with v24.19.0.

## Module exports and internal function map

### app.js

Functions: `art`, `hero`, `card`, `folderIds`, `folderHTML`, `packHTML`, `toast`, `save`, `commit`, `snapshot`, `navigate`, `back`, `download`, `openModal`, `modalHead`, `render`, `updateScrollControl`, `packsView`, `BONUS_TEXT`, `revealItems`, `backCard`, `cosmeticCard`, `revealView`, `openingControls`, `stageHTML`, `railSlot`, `renderStackLocal`, `advance`, `trueIfRemaining`, `animateReveal`, `skipReveal`, `insufficient`, `purchase`, `startNext`, `beginRitual`, `renderRitual`, `ritualInput`, `updateRitualProgress`, `autoplay`, `cinematic`, `completeRitual`, `showDetail`, `recycleDesk`, `reviewRecycle`, `lastRecycleWarning`, `chooseFolders`, `missing`, `openingSettings`, `secureRandom`, `mutateCatalog`, `nextId`, `onClick`, `person`, `applyRecycle`, `currentBoxSize`, `nextPackButton`, `repeatCount`, `queueAutoNext`, `bundleHTML`, `boxHTML`, `spaceArt`, `scheduleCarousel`, `showcaseMini`, `showcasePicker`, `profileStyle`, `customize`, `previewDocument`, `fitPreview`, `foilAt`, `pointerPaint`, `releasePhysical`, `springHome`, `packArt`, `arrowIcon`, `showcasePopup`, `binderArt`, `showcaseGallery`, `gameTiles`, `completionBadges`, `loungeView`, `fileDraggedCard`, `cardMemoryHTML`, `tablePicker`, `roomSettings`, `printPicker`, `searchResults`, `designReview`, `help`, `handleEdition9`, `watchParty`, `launchSpectator`, `broadcastOpening`, `exportCollectorImage`, `prepareReorder`, `previewReorder`, `clearReorder`, `finishReorder`, `pagedCards`, `shelfSettings`, `packInformation`, `handleEdition10`, `scheduleParallax`, `focusOpeningTable`, `designLab`, `handleEdition12`, `visitorProfile`, `labExtras`, `labSleevedCard`, `labAdvance`, `labTableMarkup`, `handleEdition13`.


### art.js

Functions: `cardHighlight`, `drawing`, `artwork`.
Exported values/classes: `escape`.


### card-art-v6.js

Exported values/classes: `CARD_ART`, `PACK_ART`, `SPACE_ART`.


### catalog.js

Exported values/classes: `RARITIES`, `DEFAULT_RULES`, `ARTISTS`, `COLLECTIONS`, `CARDS`, `DEFAULT_CATALOG`.


### collector-custom.js

Functions: `extras`, `validateCustom`, `customizeState`, `defaultColors`, `colorStyle`.
Exported values/classes: `COLOR_PARTS`, `BASE_COLORS`.


### collector-hub.js

Functions: `hub`, `ensureHub`, `tableInfo`, `milestoneRows`, `trackChanges`, `bootstrapHub`, `toggleGoal`, `claimMilestone`, `chooseTable`, `setRoom`, `setShelf`, `setNote`, `completion`, `setPrintSlot`, `movePrintSlot`, `printPlanCounts`, `clearPrintPlan`, `finishOnboarding`, `validateHub`.
Exported values/classes: `WORLD_IDS`, `WORLD_DESIGN`.


### collector-views.js

Functions: `collectorView`, `printPlanner`, `onboarding`.


### community.js

Functions: `resolveGame`, `addGuestbookEntry`, `deleteGuestbookEntry`, `collectionMilestones`.
Exported values/classes: `GAME_DIRECTORY`, `normalizeGame`.


### core.js

Functions: `validateCatalog`, `newState`, `validateState`, `log`, `transaction`, `random`, `pick`, `rarityRoll`, `packAvailability`, `openPack`, `refill`, `craft`, `recyclable`, `recycle`, `recycleAll`, `printable`, `setCart`, `quote`, `placeOrder`, `importSave`, `exportSave`, `updateCatalog`, `binderFolders`, `setBinderFolder`.


### drag-geometry.js

Functions: `overPulls`.


### edition-eleven.js

Functions: `yieldingOffset`, `filingZone`, `softBound`, `fluidBounds`, `worldFrame`.


### edition-fifteen.js

Functions: `swapOrder`, `swapOffsets`, `scenePortal`.


### edition-fourteen.js

Functions: `vacancyOffsets`.
Exported values/classes: `LAB_DETAILS`.


### edition-ten.js

Functions: `pageColumns`, `pageSlice`, `boundedDrag`, `insertOrder`, `nearestSlot`, `shiftSlots`, `binderProduct`, `worldObjects`, `merchArtwork`.
Exported values/classes: `COSMETIC_DUPLICATE_FRAGMENTS`.


### edition-three.js

Exported values/classes: `RARITIES`, `DEFAULT_RULES`, `ARTISTS`, `COLLECTIONS`, `CARDS`, `DEFAULT_CATALOG`.


### edition-two.js

Exported values/classes: `RARITIES`, `DEFAULT_RULES`, `ARTISTS`, `COLLECTIONS`, `CARDS`, `DEFAULT_CATALOG`.


### effects.js

Functions: `loadEffects`, `saveEffects`, `effectiveMotion`, `effectTier`, `particleHTML`, `primeAudio`, `playCue`.


### experience-validation.js

Functions: `validateExperience`, `list`, `pack`.


### experience.js

Functions: `defaults`, `prepare`, `transaction`, `toggleList`, `selectedSets`, `collectionStats`, `purchasePacks`, `takePack`, `markOpened`, `setReveal`, `finishPack`, `changeLayout`, `setSkin`, `moveFolder`, `updateProfile`, `toggleShowcase`, `postCard`, `recyclePreview`, `recycleSelection`, `setMerch`, `parcelQuote`, `placeParcel`, `prioritizeBatch`, `finishBatch`, `moveShowcase`.
Exported values/classes: `BONUS_CHANCE`, `SKINS`, `MERCH`, `PEOPLE`.


### legacy-art.js

Functions: `artwork`.
Exported values/classes: `escape`.


### legacy.js

Exported values/classes: `RARITIES`, `DEFAULT_RULES`, `ARTISTS`, `COLLECTIONS`, `CARDS`, `DEFAULT_CATALOG`.


### migration.js

Functions: `upgradeContent`.


### opening.js

Functions: `loadOpeningPrefs`, `saveOpeningPrefs`, `openingTheme`, `openingStep`, `openingTarget`, `openingDuration`, `openingVisual`.
Exported values/classes: `COMMAND`, `ARROWS`.


### orbital.js

Exported values/classes: `ORBITAL_ARTIST`, `ORBITAL_SET`, `ORBITAL_CARDS`.


### premium-art.js

Exported values/classes: `HERO_ART`, `PREMIUM_ART`.


### presentation-dom.js

Functions: `updateRevealDOM`.


### presentation.js

Functions: `sortPullsForReveal`, `createReveal`, `advanceReveal`, `revealComplete`.


### scene-art.js

Functions: `scene`, `props`, `orbitalDrawing`.


### spectator.js



### views.js

Functions: `viewHTML`.


### workshop-view.js

Functions: `legacyView`, `numberField`, `workshop`, `plan`.


### worlds-seven.js

Exported values/classes: `NEW_SETS`, `NEW_ARTISTS`, `NEW_CARDS`, `NEW_CARD_ART`.


## UI action identifiers

Search these in app.js to locate dispatch behaviour. Not all are visible in every state.

`advance-fast`, `archive`, `art-inspect`, `artist`, `artist-binder`, `auto-next`, `autoplay`, `back`, `binder`, `binder-cover`, `card`, `card-page`, `carousel-pause`, `cart-delta`, `choose-folders`, `choose-speed`, `claim-milestone`, `clear-filters`, `clear-print-plan`, `close-modal`, `collection-binder`, `confirm-clear-plan`, `confirm-import`, `confirm-parcel`, `confirm-print-plan`, `confirm-recycle`, `confirm-reset`, `craft-card`, `credits`, `customize`, `damaged`, `delete-comment`, `design-review`, `dismiss-welcome`, `edit-catalog`, `edit-profile`, `export`, `export-catalog`, `export-print-proof`, `export-showcase`, `favourite`, `final-recycle`, `folder-move`, `folder-options`, `follow`, `game-pick`, `global-search`, `goal-craft`, `goal-wish`, `goal-world`, `help`, `import`, `inspect-pack`, `lab-advance`, `lab-favourite`, `lab-load-mix`, `lab-motion`, `lab-replay`, `lab-reset`, `lab-save-mix`, `lab-sleeve`, `lab-toggle`, `lab-variant`, `lab-world`, `launch-spectator`, `layout`, `leave-table`, `like`, `lock`, `lounge-tab`, `merch-add`, `merch-delta`, `merch-detail`, `merch-filter`, `missing`, `missing-folder`, `nav`, `new-post`, `news`, `next-pack`, `open-all-batch`, `open-folder`, `opening-input`, `opening-settings`, `opening-speed`, `pack-count`, `pack-information`, `packs`, `parcel-scroll`, `person`, `pick-card`, `pick-print-card`, `pick-universe`, `pin-goal`, `place-parcel`, `preview-device`, `preview-page`, `print-move`, `print-page`, `print-picker`, `profile`, `profile-style`, `purchase`, `queue-card`, `recycle-all`, `recycle-card`, `recycle-desk`, `refill`, `refill-modal`, `remove-folder`, `remove-print-slot`, `repeat-purchase`, `reset`, `reset-inspect`, `resume`, `review-print-plan`, `room-arrangement`, `room-prop`, `room-settings`, `room-shelf`, `room-world`, `scroll-top`, `select-print-slot`, `set-skin`, `set-table`, `shelf-columns`, `shelf-toggle`, `show-goal`, `showcase`, `showcase-move`, `showcase-picker`, `showcase-popup`, `skip-opening`, `skip-reveal`, `slide`, `slide-next`, `slide-prev`, `slow-opening`, `table-picker`, `toggle-collection`, `toggle-folder`, `toggle-motion`, `toggle-sound`, `turn-key`, `universe`, `unseal-box`, `watch-party`, `wish`, `wishlist`

## Storage keys


- app.js: `astra-design-lab-favourite`, `astra-design-lab-mix`, `card-atlas-v1`

- opening.js: `card-atlas-opening`


## Test files and scenarios

### app-smoke.test.mjs

- Astra Tessera page rendering, box queue, artist credit, recycle warnings and combined parcel (DOM stubs, not browser QA)

### content-effects.test.mjs

- five collectible collections with 20 unique cards each
- all 100 cards have original humour text, roles and vector illustrations
- migration preserves credits, quantities, printed entitlements, cart, orders and custom content
- migration works for exported first-edition saves and does not reset user rules
- effects default to silent, respect reduced motion, and survive malformed preferences

### core.test.mjs

- default content and new save validate
- pack spends once, adds exactly packSize copies, leaves input unchanged
- insufficient funds, invalid RNG and paused collections leave state untouched
- duplicate protection selects a missing card within rolled rarity without altering rarity
- tenth missed pack gets rare in final slot and resets collection counter
- natural rare resets pity; no extra forced draw when pack already qualifies
- pity disabled does not guarantee rare
- print quantities never exceed ownership; quotes ignore rarity; digital copies persist
- print entitlements stay exhausted after another order
- recycling preserves one copy and printed or reserved quantities
- crafting handles affordability, disabled option, archived cards and owned cards
- save roundtrip includes custom catalog and print history
- malformed saves and out-of-range quantities rejected before use
- invalid rules and references rejected
- archiving preserves ownership, removes card from pack pool and prevents incompatible deletion
- collection is unavailable when a weighted rarity has no active card
- bulk simulation respects accounting and collection boundaries across 300 packs

### edition-eight.test.mjs

- favourite games use known art but only real catalogue matches link to collections
- comments round-trip older saves without touching ownership, print entitlements or queue
- collection milestones count distinct owned cards, never duplicate quantities

### edition-eleven.test.mjs

- neighbours yield continuously on approach and settle when moving away
- filing guide accepts card edge before pointer reaches tray, excluding leftward or off-table drags
- card movement remains continuous near boundaries without leaving its permitted area

### edition-fifteen.test.mjs

- binder swap exchanges only the selected pair, including different rows
- only target binder moves into the original vacancy
- scene architecture remains two-dimensional, world-specific and optional

### edition-fourteen.test.mjs

- reordering shifts the intervening chain into the vacancy in either direction
- preview grows smoothly and retreats without displacing unrelated slots
- vacancy chain works across rows
- detail controls have twelve unique independently saved identifiers

### edition-nine.test.mjs

- legacy collection memories are honestly undated and quantities are untouched
- new pulls have durable memories, while milestone claims never consume cards
- locked tables reject selection, and reward ownership survives recycling later
- bonus table collectibles use an extra slot without changing card quantities
- print planning obeys unprinted quantities, swaps slots and prunes consumed copies
- goals, notes and room preferences round-trip without corrupting ownership
- completion costs only missing cards and preserves distinct versus duplicate counts
- tray hit testing follows actual viewport positions after scroll and layout changes

### edition-seven.test.mjs

- new courier IDs cannot overwrite archived clockwork ownership or print entitlements
- both new worlds preserve quantities, isolated packs and bonus cover entitlements
- showcase ordering preserves exact members and rejects boundary moves without inventory changes
- new ritual identity and all expanded accents are accepted

### edition-ten.test.mjs

- cosmetic rewards advance within a batch, then recycle once without consuming cards
- milestone-owned room duplicates recycle, while a missing binder still unlocks first
- legacy queued cosmetics remain valid and never grant retrospective fragments
- room shelf choices persist but never remove collections, cards or printing rights
- page turns contain at most three rows with no lost or repeated cards at supported widths
- drag bounds exclude headings and outside edges but allow the right-hand tray
- reorder previews move intervening neighbours to the vacant slots without mutating order

### experience.test.mjs

- box purchase is atomic, charges once, persists every paid pack and its reveal position
- bonus cosmetic is extra to five cards and unlock survives export/import
- bulk recycle keeps last copies, locks, printed copies and print reservations
- last-copy recycling needs a second confirmation and clears a depleted showcase
- combined parcel charges one shipping estimate and consumes only queued print entitlements
- selected universe totals, personalisation and local social survive validation
- a new purchase keeps its universe first without losing older waiting packs
- six-part free colours and profile links survive save validation; unsafe URLs rejected
- legacy waiting packs get contiguous batch metadata without changing inventory

### folders-stack.test.mjs

- chosen franchise folders are saved, removable without deleting cards, and validated
- old saves infer owned franchise folders; pack opening and crafting add folders
- display sorting preserves exact pulls, draw order among equal rarities and inventory metadata
- first click flips; each following click parks one and reveals next; final click parks last
- single-card and ten-card packs finish with one flip plus one move per card
- English content migration translates shipped text, preserves custom edits and keeps same IDs

### opening.test.mjs

- orbital commands reset on wrong input and complete only in order
- opening preferences persist speed and separate franchise counts, reject malformed values
- edition 3 upgrades append third universe without changing customised existing content or quantities
- third universe has independent valid packs and adds its own binder folder

### presentation-dom.test.mjs

- filing replaces only the new slot, preserving previous card and rail nodes
- flip and timer updates do not replace any filed slot or replay arrivals


## CSS load order

Later selectors can override earlier ones; media/specificity/important must be inspected.


1. `styles.css`
2. `edition-six.css`
3. `edition-seven.css`
4. `edition-eight.css`
5. `edition-nine.css`
6. `edition-ten.css`
7. `edition-eleven.css`
8. `edition-twelve.css`
9. `edition-thirteen.css`
10. `edition-fourteen.css`
11. `edition-fifteen.css`


## Asset inventory

57 asset files. Full SHA-256 list in TRANSFER_MANIFEST.json.


### assets/v10

- `classic-binder.webp` — 124478 bytes
- `couriers-binder.webp` — 172990 bytes
- `couriers-desk-props.webp` — 68672 bytes
- `donjon-binder.webp` — 196236 bytes
- `donjon-desk-props.webp` — 48744 bytes
- `gallery.webp` — 199808 bytes
- `moonlit-binder.webp` — 146120 bytes
- `moonlit-desk-props.webp` — 88838 bytes
- `orbital-binder.webp` — 117354 bytes
- `orbital-desk-props.webp` — 88948 bytes
- `recrues-binder.webp` — 136938 bytes
- `recrues-desk-props.webp` — 100312 bytes
- `slate-binder.webp` — 68324 bytes
- `velvet-binder.webp` — 84700 bytes

### assets/v11

- `couriers-back.webp` — 161762 bytes
- `donjon-back.webp` — 171012 bytes
- `moonlit-back.webp` — 105272 bytes
- `orbital-back.webp` — 90720 bytes
- `recrues-back.webp` — 119548 bytes

### assets/v13

- `donjon-scene.webp` — 295912 bytes
- `moonlit-scene.webp` — 324668 bytes

### assets/v5

- `chaos-hero.webp` — 246198 bytes
- `cosmic-rubber-duck.webp` — 199490 bytes
- `dark-duck.webp` — 250240 bytes
- `dungeon-hero.webp` — 352324 bytes
- `last-brain-cell.webp` — 194192 bytes
- `orbital-hero.webp` — 280034 bytes

### assets/v6

- `binder.webp` — 423258 bytes
- `community.webp` — 292006 bytes
- `packs.webp` — 636344 bytes
- `printing.webp` — 381924 bytes
- `sheet0.webp` — 508694 bytes
- `sheet1.webp` — 476808 bytes
- `sheet2.webp` — 501332 bytes
- `sheet3.webp` — 565802 bytes
- `sheet4.webp` — 617280 bytes
- `sheet5.webp` — 612966 bytes

### assets/v7

- `binders.webp` — 623220 bytes
- `couriers-1.webp` — 632996 bytes
- `couriers-2.webp` — 637796 bytes
- `couriers-hero.webp` — 390500 bytes
- `discovery.webp` — 389468 bytes
- `moonlit-1.webp` — 600858 bytes
- `moonlit-2.webp` — 565210 bytes
- `moonlit-hero.webp` — 316244 bytes
- `packs.webp` — 618302 bytes

### assets/v8

- `arrivals.webp` — 353822 bytes
- `couriers-table.webp` — 358744 bytes
- `donjon-table.webp` — 245328 bytes
- `moonlit-table.webp` — 331470 bytes
- `orbital-table.webp` — 171538 bytes
- `recrues-table.webp` — 136714 bytes

### assets/v9

- `couriers-prestige.webp` — 478304 bytes
- `donjon-prestige.webp` — 250862 bytes
- `moonlit-prestige.webp` — 382522 bytes
- `orbital-prestige.webp` — 147210 bytes
- `recrues-prestige.webp` — 172352 bytes


## Publication and local runtime boundaries

.openai/hosting.json retains the existing private Site identity. It is not a credential. The new machine needs its own authenticated Sites access before publishing. source-history.bundle holds available source history; it does not hold remote authority or local browser saves.


<!-- END TECHNICAL_INVENTORY.md -->


---

<!-- BEGIN HISTORICAL_PROJECT_DOCUMENTS.md -->

# Historical project documents

These are preserved source documents, in filename order. They contain historical statuses, proposals and superseded instructions. HANDOFF.md and the latest user feedback take precedence. Automated-test counts here belong to older checkpoints.


---

# Original file: docs/ART_ASSETS_V10.md

# Edition 10 original artwork

Generated with the built-in image_gen tool on 2026-10-10. All fourteen assets visually inspected before integration. Binder assets have real alpha transparency; conversion preserves generated transparency. Original generations remain in scratch. No manual image retouching. Binder images optimized to 800px width, quality88 WebP with alpha; foreground prop layers optimized to at most1200×675. Dungeon alpha verified by compositing onto a dark plum surface; apparent colored fringe in raw viewer is absent in normal alpha composition.

## recrues

Path: `dist/assets/v10/recrues-binder.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-46d87996-6537-4447-ae41-c3d2c3098373.png`

Prompt:

Use case: product-mockup. A standalone physical collectible card binder product asset for a premium game-world collecting website. One closed binder standing upright, three-quarter view with front cover and left spine visible, entire object centered with generous transparent margin. Genuine transparent background, no floor or backdrop, no text or letters or watermark. Crisp intentional stylized game concept art with clean readable big shapes, restrained details, believable thickness, manufactured hinges and clasp, beautiful soft studio lighting, sharp silhouette. Not a flat rectangle, not excessive tiny ornament or noisy AI detail. Chaos Crew: angular futuristic hard-shell holo binder, violet black armor panels, acid-lime narrow edge accents, translucent holographic inset with abstract geometric circuit emblem, asymmetric clipped corners, thick dark spine, sturdy sleek latch. Playful premium esports equipment.

## donjon

Path: `dist/assets/v10/donjon-binder.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-e9d00747-75ea-4948-900c-8c1bbe656ba8.png`

Prompt:

Use case: product-mockup. A standalone physical collectible card binder product asset for a premium game-world collecting website. One closed binder standing upright, three-quarter view with front cover and left spine visible, entire object centered with generous transparent margin. Genuine transparent background, no floor or backdrop, no text or letters or watermark. Crisp intentional stylized game concept art with clean readable big shapes, restrained details, believable thickness, manufactured hinges and clasp, beautiful soft studio lighting, sharp silhouette. Not a flat rectangle, not excessive tiny ornament or noisy AI detail. Discount Dungeon: carved dark burgundy leather spellbook binder with brass fittings, sculpted friendly duck-head crest in center, aged cream paper edges, thick rounded raised spine ribs, broad elegant scroll-shaped brass corner guards and leather clasp. Warm collectible fantasy prop, witty but beautiful, no extra objects.

## orbital

Path: `dist/assets/v10/orbital-binder.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-51042a44-fa2a-4087-9776-a9cda252ee87.png`

Prompt:

Use case: product-mockup. A standalone physical collectible card binder product asset for a premium game-world collecting website. One closed binder standing upright, three-quarter view with front cover and left spine visible, entire object centered with generous transparent margin. Genuine transparent background, no floor or backdrop, no text or letters or watermark. Crisp intentional stylized game concept art with clean readable big shapes, restrained details, believable thickness, manufactured hinges and clasp, beautiful soft studio lighting, sharp silhouette. Not a flat rectangle, not excessive tiny ornament or noisy AI detail. Orbital Oddjobs: blue-teal industrial spacecraft cargo field binder, rounded rugged steel shell, inset pale-teal enamel panel with a simple orbital diagram emblem, visible precision hinges, orange small safety latch, thick graphite rubber spine and protective corners. Practical retro space explorer equipment.

## couriers

Path: `dist/assets/v10/couriers-binder.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-f3887a34-5dcf-4ab2-ad4a-17377b9aa65c.png`

Prompt:

Use case: product-mockup. A standalone physical collectible card binder product asset for a premium game-world collecting website. One closed binder standing upright, three-quarter view with front cover and left spine visible, entire object centered with generous transparent margin. Genuine transparent background, no floor or backdrop, no text or letters or watermark. Crisp intentional stylized game concept art with clean readable big shapes, restrained details, believable thickness, manufactured hinges and clasp, beautiful soft studio lighting, sharp silhouette. Not a flat rectangle, not excessive tiny ornament or noisy AI detail. Clockwork Couriers: tall teal leather mechanical dispatch ledger with brass spine, large clean articulated clockwork circular clasp on front, cream porcelain inset medallion, wing-shaped brass corner geometry, visible book thickness and elegant hinge. Strong art deco and steampunk industrial product design, a few purposeful gears not visual clutter.

## moonlit

Path: `dist/assets/v10/moonlit-binder.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-d106ac19-9c34-47f8-9013-0548fff7739e.png`

Prompt:

Use case: product-mockup. A standalone physical collectible card binder product asset for a premium game-world collecting website. One closed binder standing upright, three-quarter view with front cover and left spine visible, entire object centered with generous transparent margin. Genuine transparent background, no floor or backdrop, no text or letters or watermark. Crisp intentional stylized game concept art with clean readable big shapes, restrained details, believable thickness, manufactured hinges and clasp, beautiful soft studio lighting, sharp silhouette. Not a flat rectangle, not excessive tiny ornament or noisy AI detail. Moonlit Menagerie: indigo velvet arched-top collectible book cabinet binder, silver crescent moon crest, restrained painted moonflower vines, scalloped silver cover rim, elegantly curved thick spine, small pearl clasp. Distinct cathedral-window silhouette and whimsical boutique midnight hotel object. Refined silver/indigo/soft lavender.

## gallery

Path: `dist/assets/v10/gallery.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-b010e35b-1620-4afd-aef7-c33a7bb10f31.png`

Prompt:

Use case: stylized-concept. Original widescreen 16:9 environment artwork for a premium collectible card website's personal gallery. An intimate beautifully designed nocturnal collector's atelier, eye-level slightly elevated wide view, calm dark plum walls and walnut display shelving, restrained brass trim, warm indirect shelf lighting, subtle violet window glow. Central broad EMPTY dark work surface occupies lower 45 percent, empty shallow display niches at sides and rear upper third; space ready for separately composited binder/card UI. Architectural depth and physically believable surfaces, tailored game environment concept painting with crisp designed large shapes and restful detail hierarchy, not photoreal grain. Asymmetric tasteful lamp and one sculpted abstract brass ornament tucked at far edges, no books, no cards, no posters, no text, no logos, no people, no clutter. Central 60 percent calm low contrast usable negative space, beautiful expansive material craftsmanship, no extreme highlights.

## Review notes

All binders have readable three-quarter depth, a visible spine and a closure. Chaos is angular hard-shell; Dungeon has warm leather and duck crest; Orbital uses rugged cargo hardware; Couriers uses dispatch clockwork; Moonlit has an arched floral silhouette. Gallery deliberately leaves its large central surface clear for real UI. These are product concepts, not photographs of manufactured goods. Raster artwork should not be globally hue-rotated for customization; recolour separately rendered trim/panels instead.
## donjon-desk-props

Path: `dist/assets/v10/donjon-desk-props.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-d9496a08-cceb-4e64-aaca-978a1969d51f.png`

Prompt:

Use case: stylized-concept. Transparent foreground prop arrangement for a collectible card game's fantasy dungeon opening desk. Wide 16:9 transparent canvas. ALL objects contained in leftmost 22 percent of canvas and bottom-left corner. CENTRAL 70 percent and entire rightmost 25 percent MUST BE EMPTY ALPHA TRANSPARENCY, no connecting horizontal lines, no background, no backdrop. A short burning candle in a chunky brass holder, one elegant purple potion bottle, rolled cream parchment and duck-shaped red wax seal, clustered as physical tabletop props at the far left. Slight overhead three-quarter view looking down onto props. Warm brass burgundy wood accents, clean polished game concept product rendering, crisp intentional shapes, restrained detail, believable material depth, soft contact shadows restricted to immediately underneath props. No text, letters, cards, books or people. Keep all props entirely in view with margin. True transparent background.


## recrues-desk-props

Path: `dist/assets/v10/recrues-desk-props.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-38997a3e-fa92-4248-891e-f2e2c7f99989.png`

Prompt:

Use case: stylized-concept. Transparent foreground prop arrangement for a collectible card game's opening desk. Wide 16:9 transparent canvas. ALL objects contained in leftmost 22 percent of canvas and bottom-left corner. CENTRAL 70 percent and entire rightmost 25 percent MUST BE EMPTY ALPHA TRANSPARENCY, no connecting horizontal lines, no background, no backdrop. Slight overhead three-quarter view looking down onto props. Clean polished game concept product rendering, crisp intentional shapes, restrained detail, believable material depth, soft contact shadows restricted to immediately underneath props. No text, letters, cards, books or people. Keep all props entirely in view with margin. True transparent background. Chaos Crew futuristic gaming squad desk: compact violet hologram projector displaying a small abstract lime diamond, a black/violet game controller, tiny angular mascot charm and curled lime cable.


## orbital-desk-props

Path: `dist/assets/v10/orbital-desk-props.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-e7d38257-0eb6-4aca-8e53-e19fca734ff9.png`

Prompt:

Use case: stylized-concept. Transparent foreground prop arrangement for a collectible card game's opening desk. Wide 16:9 transparent canvas. ALL objects contained in leftmost 22 percent of canvas and bottom-left corner. CENTRAL 70 percent and entire rightmost 25 percent MUST BE EMPTY ALPHA TRANSPARENCY, no connecting horizontal lines, no background, no backdrop. Slight overhead three-quarter view looking down onto props. Clean polished game concept product rendering, crisp intentional shapes, restrained detail, believable material depth, soft contact shadows restricted to immediately underneath props. No text, letters, cards, books or people. Keep all props entirely in view with margin. True transparent background. Orbital Oddjobs spacecraft workbench: compact rugged teal radar instrument with circular green screen, small graphite oxygen canister with orange valve, two blank metal mission tags on a short loop.


## couriers-desk-props

Path: `dist/assets/v10/couriers-desk-props.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-15135cfa-42d1-47a9-8a0f-21d89b5f0d68.png`

Prompt:

Use case: stylized-concept. Transparent foreground prop arrangement for a collectible card game's opening desk. Wide 16:9 transparent canvas. ALL objects contained in leftmost 22 percent of canvas and bottom-left corner. CENTRAL 70 percent and entire rightmost 25 percent MUST BE EMPTY ALPHA TRANSPARENCY, no connecting horizontal lines, no background, no backdrop. Slight overhead three-quarter view looking down onto props. Clean polished game concept product rendering, crisp intentional shapes, restrained detail, believable material depth, soft contact shadows restricted to immediately underneath props. No text, letters, cards, books or people. Keep all props entirely in view with margin. True transparent background. Clockwork Couriers steampunk dispatch station: small brass pressure gauge on a dark teal block, polished brass service bell, short copper tubing and a little wing-shaped mechanical token.


## moonlit-desk-props

Path: `dist/assets/v10/moonlit-desk-props.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-57dae584-bdc8-4e28-8818-85999e0bcb4c.png`

Prompt:

Use case: stylized-concept. Transparent foreground prop arrangement for a collectible card game's opening desk. Wide 16:9 transparent canvas. ALL objects contained in leftmost 22 percent of canvas and bottom-left corner. CENTRAL 70 percent and entire rightmost 25 percent MUST BE EMPTY ALPHA TRANSPARENCY, no connecting horizontal lines, no background, no backdrop. Slight overhead three-quarter view looking down onto props. Clean polished game concept product rendering, crisp intentional shapes, restrained detail, believable material depth, soft contact shadows restricted to immediately underneath props. No text, letters, cards, books or people. Keep all props entirely in view with margin. True transparent background. Moonlit Menagerie midnight hotel desk: delicate silver crescent desk lamp on indigo base, small deep-violet vase with three pale moonflowers, and an elegant silver star-shaped key. Soft lavender glow.


## classic-binder

Path: `dist/assets/v10/classic-binder.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-68babfcc-b08a-4e21-8735-101f105d5de4.png`

Prompt:

Use case: product-mockup. A standalone physical collectible card binder product asset for a premium game-world collecting website. One closed binder standing upright, three-quarter view with front cover and left spine visible, entire object centered with generous transparent margin. Genuine transparent background, no floor or backdrop, no text or letters or watermark. Crisp intentional stylized game concept art with clean readable big shapes, restrained details, believable thickness, manufactured hinges and clasp, beautiful soft studio lighting, sharp silhouette. Not a flat rectangle, not excessive tiny ornament or noisy AI detail. Classic archive binder: simple warm tan leather with elegant brass corner protectors and one modest leather strap clasp, unadorned front panel, cream edges, rounded thick spine. Understated and warm, less elaborate than fantasy trophy books.


## velvet-binder

Path: `dist/assets/v10/velvet-binder.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-8cb7e9c7-0b22-4db5-b360-7ccdc7a840a9.png`

Prompt:

Use case: product-mockup. A standalone physical collectible card binder product asset for a premium game-world collecting website. One closed binder standing upright, three-quarter view with front cover and left spine visible, entire object centered with generous transparent margin. Genuine transparent background, no floor or backdrop, no text or letters or watermark. Crisp intentional stylized game concept art with clean readable big shapes, restrained details, believable thickness, manufactured hinges and clasp, beautiful soft studio lighting, sharp silhouette. Not a flat rectangle, not excessive tiny ornament or noisy AI detail. Midnight velvet binder: rectangular midnight violet fabric cover, slender silver edge trim and a small circular silver celestial medallion centered on front, plain smooth spine and neat silver clasp. Understated modern luxury, clean simple rectangular silhouette, no arch or flowers.


## slate-binder

Path: `dist/assets/v10/slate-binder.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-7af2471e-a2a5-4912-bcb9-d59f5b353731.png`

Prompt:

Use case: product-mockup. A standalone physical collectible card binder product asset for a premium game-world collecting website. One closed binder standing upright, three-quarter view with front cover and left spine visible, entire object centered with generous transparent margin. Genuine transparent background, no floor or backdrop, no text or letters or watermark. Crisp intentional stylized game concept art with clean readable big shapes, restrained details, believable thickness, manufactured hinges and clasp, beautiful soft studio lighting, sharp silhouette. Not a flat rectangle, not excessive tiny ornament or noisy AI detail. Carbon slate binder: graphite carbon modern geometric hard-case, subtle charcoal angular panel seams, a small brushed steel rectangular clasp, sturdy dark spine. Understated minimalist collector equipment, no neon glow or logos.


Foreground review: generated prop clusters occupy the left35–40% of each transparent canvas (not the requested22%). Integrate as a bounded scaled left-edge layer, keeping active card/tray space clear. All eight binder variants are visually inspected; basic three use quieter shapes/materials than earned world designs.


---

# Original file: docs/ART_ASSETS_V11.md

# Edition 11 card-back artwork

Five original universe card backs generated using built-in image_gen, visually inspected on 2026-10-11. No references used. Opaque full-bleed portrait designs with central emblems and no text. Converted to width600 WebP, quality86; no manual visual edits.

## recrues

Path: `dist/assets/v11/recrues-back.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-9dc3c599-f7aa-4f48-a354-def98bae07db.png`

Prompt:

Use case: stylized-concept. Premium collectible trading card BACK illustration, portrait aspect ratio exactly 5:7, full bleed opaque artwork. Perfectly front-on flat card graphic, not a physical tilted card or mockup, no surroundings. Purpose-built symmetrical strong frame and single readable central emblem, beautiful intentional stylized game concept artwork, restrained material detail, clear hierarchy and broad restful surfaces, rich depth in embossing without noisy micro-ornament. No text, letters, numbers or watermark. Violet and acid-lime squad technology: brushed black angular armor frame with violet glass inset, central luminous faceted squad diamond, geometric circuitry restricted to border, premium futuristic tactical aesthetic.

## donjon

Path: `dist/assets/v11/donjon-back.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-fdfb0a78-d692-4be0-ba60-cf12c5610407.png`

Prompt:

Use case: stylized-concept. Premium collectible trading card BACK illustration, portrait aspect ratio exactly 5:7, full bleed opaque artwork. Perfectly front-on flat card graphic, not a physical tilted card or mockup, no surroundings. Purpose-built symmetrical strong frame and single readable central emblem, beautiful intentional stylized game concept artwork, restrained material detail, clear hierarchy and broad restful surfaces, rich depth in embossing without noisy micro-ornament. No text, letters, numbers or watermark. Burgundy leather and warm antique gold fantasy: central friendly duck heraldic seal in a gold medallion, carved curling brass scrollwork frame, restrained rune-like abstract geometry without characters, dark warm leather field.

## orbital

Path: `dist/assets/v11/orbital-back.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-40b03431-b3fc-4a99-8f10-b5d8551f9e0a.png`

Prompt:

Use case: stylized-concept. Premium collectible trading card BACK illustration, portrait aspect ratio exactly 5:7, full bleed opaque artwork. Perfectly front-on flat card graphic, not a physical tilted card or mockup, no surroundings. Purpose-built symmetrical strong frame and single readable central emblem, beautiful intentional stylized game concept artwork, restrained material detail, clear hierarchy and broad restful surfaces, rich depth in embossing without noisy micro-ornament. No text, letters, numbers or watermark. Teal industrial space cargo aesthetic: central ivory ringed-planet orbital seal, teal enamel broad field, dark steel frame with four purposeful inset screws and slim orange warning accents, subtle technical grid.

## couriers

Path: `dist/assets/v11/couriers-back.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-bb9d6665-3a82-4184-b314-8c3c6891018a.png`

Prompt:

Use case: stylized-concept. Premium collectible trading card BACK illustration, portrait aspect ratio exactly 5:7, full bleed opaque artwork. Perfectly front-on flat card graphic, not a physical tilted card or mockup, no surroundings. Purpose-built symmetrical strong frame and single readable central emblem, beautiful intentional stylized game concept artwork, restrained material detail, clear hierarchy and broad restful surfaces, rich depth in embossing without noisy micro-ornament. No text, letters, numbers or watermark. Teal and brass clockwork dispatch aesthetic: central winged envelope seal framed by a circular brass clock mechanism, art deco corner shapes, rich teal leather field, beautifully balanced meaningful gears rather than visual noise.

## moonlit

Path: `dist/assets/v11/moonlit-back.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-abd3a349-3cbf-471d-95b1-aa4e94a43b15.png`

Prompt:

Use case: stylized-concept. Premium collectible trading card BACK illustration, portrait aspect ratio exactly 5:7, full bleed opaque artwork. Perfectly front-on flat card graphic, not a physical tilted card or mockup, no surroundings. Purpose-built symmetrical strong frame and single readable central emblem, beautiful intentional stylized game concept artwork, restrained material detail, clear hierarchy and broad restful surfaces, rich depth in embossing without noisy micro-ornament. No text, letters, numbers or watermark. Indigo velvet and silver moonflower midnight hotel aesthetic: central elegant crescent moon and one star, silver arched ornamental frame, moonflowers curving at lower corners, deep restful indigo velvet field, refined magical elegance.


---

# Original file: docs/ART_ASSETS_V13.md

# Edition 13 immersive room experiments

Two original scene illustrations generated with built-in image_gen. Both inspected: clear center tabletop, physically consistent seated perspective, side props, no UI/text/people. These are integrated scene experiments for Dungeon and Moonlit only.

## donjon

Path: `dist/assets/v13/donjon-scene.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-703f0e81-13d8-4379-bd56-bbbc1b3fd82b.png`

Prompt:

Use case: stylized-concept. Original high-end fantasy game environment illustration, widescreen 16:9, designed as an immersive collectible card opening room. View from a seated collector, eye level, not overhead. Foreground lower 38 percent is a broad clean UNOBSTRUCTED burgundy leather tabletop inset in beautifully aged dark walnut, its near edge cropped by image bottom. All center tabletop area must stay calm and empty for playable card interface. Beyond the desk: a collector's tavern vault carved into a vast cavern, arched stone opening overlooking a still dark turquoise underground lake and distant ruined castle lit by scattered amber windows. Warm brass lamps and carved woodwork at far sides. At extreme left only, a candle and purple potion bottle; tiny tasteful duck-shaped brass motifs integrated in side rail corners, not central ornaments. Rich architectural depth, inviting amber foreground against cool blue cavern distance, purposeful readable silhouettes and refined materials, polished intentional game concept painting, detailed focal architecture with calmer surfaces. Beautiful atmospheric depth without fog hiding everything. No cards, books, words, letters, UI, people, logos, watermark, excessive tiny ornaments, grit or grain. Table and background must belong to same perspective and scene, no pasted prop look.

## moonlit

Path: `dist/assets/v13/moonlit-scene.webp`

Original: `/workspace/scratch/9f8298f0e77d/generated_images/exec-5a49093f-b2d4-44c8-a6bd-af565a45e3b5.png`

Prompt:

Use case: stylized-concept. Original high-end fantastical midnight hotel game environment illustration, widescreen 16:9, designed as an immersive collectible card opening room. View from a seated collector on a grand moonlit hotel terrace, eye level, not overhead. Foreground lower 38 percent is a broad clean UNOBSTRUCTED deep indigo velvet tabletop with elegantly thin silver crescent-patterned perimeter, near edge cropped by image bottom. Center tabletop area calm and empty for playable card interface. Beyond it an elegant arched stone and silver balustrade, luminous moonflower garden, reflected moonlight in garden pools, and graceful fantastical hotel towers with inviting warm windows among indigo trees. Side curtains and ornamental arch frame view but central vista open. At extreme sides a few white moonflowers and small candles; no central props. Refined silver, indigo and violet with restrained warm gold windows. Beautiful composition and architectural depth, intentional polished game concept painting, strong clear forms, gorgeous atmospheric lighting and believable materials, details concentrated at edges and distant hotel rather than uniform noise. Integrated perspective table and surroundings. No cards, books, people, words, letters, UI, logos, watermark, excessive tiny ornament, grit or grain.

## Composition notes

Dungeon tabletop begins at approximately 58% image height; Moonlit tabletop begins at approximately 64%. Keep the lower foreground visible when fitting the scene to a viewport. Card UI may rise above the horizon while its base rests on the surface. Avoid adding duplicate large prop sprites over the already integrated side details. Both scenes retain open central lower surfaces.

---

# Original file: docs/ART_ASSETS_V5.md

# Card Atlas v5 artwork provenance

Created 2026-10-10 with the built-in `image_gen.imagegen` tool. These are original AI-generated prototype assets, not commissioned artist work or official franchise imagery. The fictional artist names in the demo catalog must not be presented as real authors of these generated illustrations.

All six results were visually inspected. Heroes use a 16:9 composition with darker left-hand space for copy. Portraits use 2:3 composition and darker lower areas for text. Images have no intended lettering, card frame or UI. Original outputs are copied unchanged to `dist/assets/v5`; `dist/premium-art.js` supplies stable mappings.

| Asset | Catalog mapping | Visual intent |
| --- | --- | --- |
| chaos-hero.png | recrues | Purple gaming squad, unplugged controller, toaster repair, pigeon on headset |
| dungeon-hero.png | donjon | Mage with empty purse, overloaded goblin, knight in sandals, mimic chest |
| orbital-hero.png | orbital | Self-repairing robot, oversized delivery, cat piloting ship |
| last-brain-cell.png | recrues-20 | Exhausted brain on controller throne holding last idea |
| dark-duck.png | donjon-19 | Harmless yellow duck in intimidating crown and cape |
| cosmic-rubber-duck.png | orbital-19 | Golden bath duck, astronaut helmet, halo and soap bubbles |

## Generation prompts

### Chaos Crew hero

Use case: stylized-concept. Create a polished wide 16:9 game universe showcase illustration for an original collectible card universe called Chaos Crew. No lettering. An absurd but charismatic squad of three young adult gaming scavengers wearing improvised purple tactical streetwear in a neon-lit gaming den, one triumphantly holding a completely unplugged controller, one repairing a toaster as if it were critical military hardware, one distracted by a pigeon perched on their headset. Painterly premium game concept art, expressive believable faces, mature graphic-novel proportions, strong silhouette and composition, purple and restrained acid teal highlights, richly modeled props and dramatic light, calm shadow areas, no grain or excessive microdetail, no logos or interface or borders. Left third mostly atmospheric darker room for webpage copy; characters grouped center-right. Full-bleed artwork.

### Discount Dungeon hero

Use case: stylized-concept. Wide 16:9 premium fantasy game showcase artwork for original humorous collectible universe Discount Dungeon. A mismatched adventuring party in an ancient treasure vault: weary elegant mage inspecting a tiny empty coin purse, green goblin intern hauling a ridiculously large stack of treasure, proud knight with battered armor and sandals, a suspicious treasure chest with small teeth in foreground. Beautiful painterly fantasy concept illustration, expressive believable anatomy, clever visual comedy in a serious dramatic world, warm amber torchlight against plum shadows, ornate weathered stone arches and distant torchlit passages. Strong clear composition and calm shadow surfaces, no excessive grain or microdetail. Left third mostly darker architecture with heroes center-right to allow webpage copy. No words, logos, interface, frames or watermark. Full bleed artwork.

### Orbital Oddjobs hero

Use case: stylized-concept. Wide 16:9 premium retro science fiction game universe showcase for an original humorous collectible card universe Orbital Oddjobs. Three scrappy space salvagers on a battered orbital delivery dock: a copper maintenance robot attempting to repair itself with a spanner, a tired astronaut wheeling a huge parcel on an impractically tiny trolley, and an orange cat proudly occupying a spacecraft pilot chair in the background. A glowing planetary crescent outside immense bay doors. Teal industrial lighting, copper metal, warm cabin light, textured but clean painterly mature game concept art, dramatic depth, readable clear silhouettes, believable machinery with restrained detail. Keep left third dark atmospheric with the action center-right for webpage copy. No text, logos, interface, borders or watermark, full bleed illustration.

### The Last Brain Cell

Create a premium portrait 2:3 collectible card illustration, full bleed with no lettering or card frame. Original character 'Last Brain Cell': a small pink anthropomorphic brain with expressive exhausted eyes, wearing a crooked purple gaming headset, sitting alone on an enormous battered tactical throne made of unplugged game controllers inside a neon gaming command room. It guards a single glowing idea light bulb as if it were the universe's last precious resource. Humor in the contrast between tiny tired brain and monumental heroic staging. Painterly mature video game concept art with crisp focal shape, purple shadows, pink skin, restrained electric teal and warm golden light, tactile materials, beautiful depth, restrained detail, no emoji/flat vector style, no gore, no words/logos. Subject centrally staged upper two thirds; darker atmospheric lower section for card text overlay.

### The Dark Duck

Create a premium portrait 2:3 full bleed fantasy collectible card illustration, no text and no frame. Original character 'Dark Duck': an ordinary small yellow rubber duck wearing an intimidating dark iron crown and enormous dramatic black-purple royal cape, perched on a monumental obsidian throne in a ruined gothic dungeon. The duck's tiny orange beak and harmless dot eyes contrast with the serious ominous royal setting; a tiny wet footprint trail approaches the throne. Warm amber candles, deep violet shadow, exquisite painterly premium fantasy game concept art, high material quality, clean readable focus, controlled detail and no grain. Centered heroic upper two thirds composition, dark atmospheric lower area for card text overlay. No logos, lettering, border, interface, or watermarks.

### Cosmic Rubber Duck

Create a premium portrait 2:3 full bleed science-fiction collectible card illustration, no text and no frame. Original character 'Cosmic Rubber Duck': a glorious golden rubber bath duck inside a round clear astronaut helmet with a copper collar, floating weightlessly before the curved blue horizon of a planet. A luminous thin gold orbital ring forms a halo behind its helmet; a few ordinary soap bubbles float around as though this divine cosmic being took the bath with it. Epic astronaut composition contrasted with wonderfully mundane toy duck, tasteful visual comedy. Mature painterly retro science fiction game concept art, teal space shadow, burnished copper, radiant warm gold, beautiful glass reflections and controlled rich details, strong silhouette, no grain, no emoji style. Subject centered upper two thirds; lower third darker cosmic atmosphere for card text overlay. No logos lettering border or UI.

## Inspection limits

The six standalone images were inspected visually; browser cropping and integration remain the responsibility of the consuming UI. The duck portrait is slightly more characterful than a strictly molded bath toy, and intentionally remains clearly comedic. Fine background props are illustrative, not engineering diagrams.


Delivery assets are optimized WebP derivatives in `dist/assets/v5/`; generated PNG intermediates were removed from the published bundle. Illustrations are generated prototype concepts, not commissions by the fictional studio credits.


---

# Original file: docs/ART_ASSETS_V6.md

# Card Atlas v6 artwork provenance

Generated 2026-10-10 using built-in image_gen.imagegen. These are AI-generated original prototype illustrations, not commissioned or licensed franchise art. Ten generations provide 60 dedicated card scenes, three pack illustrations, and three distinct page environments. All outputs were visually reviewed. Sheets are rendered directly via CSS atlas positions; no image cropping or recomposition was performed. WebP is a format-only encoding at quality90, without resizing. Returned dimensions are approximately1620x972 for card sheets (each portrait cell324x486), despite higher requested generation resolution. Do not claim print-resolution production artwork.

## Mapping

Card sheets use five equal columns and two equal rows, read left-to-right then top-to-bottom. Each cell is2:3. All60 have dedicated scenes; v5 premium portraits may be optionally retained at their existing IDs. The new LastBrainCell cell depicts a tired human with a floating brain rather than an anthropomorphic brain; v5 is a closer match to the earlier canonical design. Some tiny incidental prop marks appear although text was excluded from prompts.

- recrues-01: sheet0.webp, row1, column1: Cardboard Carry
- recrues-02: sheet0.webp, row1, column2: Loot Rat
- recrues-03: sheet0.webp, row1, column3: Open Mic
- recrues-04: sheet0.webp, row1, column4: Tactical Pigeon
- recrues-05: sheet0.webp, row1, column5: Friendship Grenade
- recrues-06: sheet0.webp, row2, column1: RGB Toaster
- recrues-07: sheet0.webp, row2, column2: Respawn Coffee
- recrues-08: sheet0.webp, row2, column3: Competitive Chair
- recrues-09: sheet0.webp, row2, column4: Ghost Ping
- recrues-10: sheet0.webp, row2, column5: Innocent Controller
- recrues-11: sheet1.webp, row1, column1: Sofa Coach
- recrues-12: sheet1.webp, row1, column2: Angry Keyboard
- recrues-13: sheet1.webp, row1, column3: Camo Duck
- recrues-14: sheet1.webp, row1, column4: Volunteer Bug
- recrues-15: sheet1.webp, row1, column5: Foam Shield
- recrues-16: sheet1.webp, row2, column1: AFK Hero
- recrues-17: sheet1.webp, row2, column2: Short-Sighted Sniper
- recrues-18: sheet1.webp, row2, column3: Battle Chicken
- recrues-19: sheet1.webp, row2, column4: King of Excuses
- recrues-20: sheet1.webp, row2, column5: The Last Brain Cell
- donjon-01: sheet2.webp, row1, column1: Intern Goblin
- donjon-02: sheet2.webp, row1, column2: Lukewarm Slime
- donjon-03: sheet2.webp, row1, column3: Flip-Flop Knight
- donjon-04: sheet2.webp, row1, column4: Expired Potion
- donjon-05: sheet2.webp, row1, column5: Suspicious Chest
- donjon-06: sheet2.webp, row2, column1: Accountant Rat
- donjon-07: sheet2.webp, row2, column2: Union Candle
- donjon-08: sheet2.webp, row2, column3: Passive Mushroom
- donjon-09: sheet2.webp, row2, column4: Busy Skeleton
- donjon-10: sheet2.webp, row2, column5: Cardboard Shield
- donjon-11: sheet3.webp, row1, column1: Tech Support Wizard
- donjon-12: sheet3.webp, row1, column2: HR Bat
- donjon-13: sheet3.webp, row1, column3: Dragon on Leave
- donjon-14: sheet3.webp, row1, column4: Axe on Finance
- donjon-15: sheet3.webp, row1, column5: Shy Ghost
- donjon-16: sheet3.webp, row2, column1: Parking Paladin
- donjon-17: sheet3.webp, row2, column2: Paperwork Lich
- donjon-18: sheet3.webp, row2, column3: Gourmet Mimic
- donjon-19: sheet3.webp, row2, column4: The Dark Duck
- donjon-20: sheet3.webp, row2, column5: The Monday Boss
- orbital-01: sheet4.webp, row1, column1: Junior Space Janitor
- orbital-02: sheet4.webp, row1, column2: Express Delivery Pod
- orbital-03: sheet4.webp, row1, column3: Emotional Support Drone
- orbital-04: sheet4.webp, row1, column4: Lunchbox Reactor
- orbital-05: sheet4.webp, row1, column5: Warranty Void Bot
- orbital-06: sheet4.webp, row2, column1: Space Traffic Cone
- orbital-07: sheet4.webp, row2, column2: Moon Roomba
- orbital-08: sheet4.webp, row2, column3: Definitely Not an Egg
- orbital-09: sheet4.webp, row2, column4: Emergency Pizza
- orbital-10: sheet4.webp, row2, column5: Budget Jetpack
- orbital-11: sheet5.webp, row1, column1: Clipboard Commander
- orbital-12: sheet5.webp, row1, column2: Unionised Loader
- orbital-13: sheet5.webp, row1, column3: Asteroid Hamster
- orbital-14: sheet5.webp, row1, column4: Sentient Vending Machine
- orbital-15: sheet5.webp, row1, column5: Lost Probe
- orbital-16: sheet5.webp, row2, column1: Captain Overtime
- orbital-17: sheet5.webp, row2, column2: Cat in the Cockpit
- orbital-18: sheet5.webp, row2, column3: The Spare Parts Titan
- orbital-19: sheet5.webp, row2, column4: Cosmic Rubber Duck
- orbital-20: sheet5.webp, row2, column5: The Final Coffee

Pack atlas has three equal portrait columns: recrues,donjon,orbital. Page backgrounds: binder(private archive),community(collector lounge),printing(artisan atelier).

## Exact prompts

### sheet0

Create a high resolution 3840x2304 illustration atlas with EXACTLY FIVE equal columns and TWO equal rows, exactly TEN independent full-bleed portrait illustrations. Every cell has aspect ratio 2:3. No gaps, no gutters, no dividing border, no text, no numbers, no lettering, no card frames. Each cell is a separate scene and must stay wholly within its own rectangle; no elements cross cells. Consistent premium detailed painterly collectible game card art. Purple neon gaming comedy with tactical streetwear and inventive gaming props, mature graphic novel painterly concept art. Purple/teal lighting. Strong distinct focal subjects, physical depth and lighting, rich scenes, clean readable silhouettes, humorous visual storytelling, no flat vector or emoji art. The ten cells in strict reading order LEFT TO RIGHT across TOP row then LEFT TO RIGHT across BOTTOM row depict:
1. Cardboard Carry: The headset is premium. The armour came with free shipping.
2. Loot Rat: Came for the loot. Left with your cheese and a suspiciously full inventory.
3. Open Mic: Built like a microphone. Somehow still mainly broadcasts chewing.
4. Tactical Pigeon: Excellent reconnaissance. Has already reported your car to every other pigeon.
5. Friendship Grenade: That little spark is the group chat ending.
6. RGB Toaster: Runs hot. Supports bread tracing.
7. Respawn Coffee: Two eyes. One cold stare. Zero concern for your sleep schedule.
8. Competitive Chair: The chair has better support than your entire team.
9. Ghost Ping: Three perfect bars. That cross underneath says otherwise.
10. Innocent Controller: Those colourful buttons have heard some very uncolourful language.
Render the subject of every title literally and make its associated visual joke visible. No written jokes; everything through image. Each illustration independently composed with subject centered upper-middle and supporting environment. This is ten finished artworks arranged as a precise uniform grid, not a contact sheet of cards or a screenshot.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-f0b69019-6ecb-42a5-b383-cb8fff1eec97.png

### sheet1

Create a high resolution 3840x2304 illustration atlas with EXACTLY FIVE equal columns and TWO equal rows, exactly TEN independent full-bleed portrait illustrations. Every cell has aspect ratio 2:3. No gaps, no gutters, no dividing border, no text, no numbers, no lettering, no card frames. Each cell is a separate scene and must stay wholly within its own rectangle; no elements cross cells. Consistent premium detailed painterly collectible game card art. Purple neon gaming comedy with tactical streetwear and inventive gaming props, mature graphic novel painterly concept art. Purple/teal lighting. Strong distinct focal subjects, physical depth and lighting, rich scenes, clean readable silhouettes, humorous visual storytelling, no flat vector or emoji art. The ten cells in strict reading order LEFT TO RIGHT across TOP row then LEFT TO RIGHT across BOTTOM row depict:
1. Sofa Coach: A full headset and a front-row seat to someone else doing the work.
2. Angry Keyboard: The missing key is patience.
3. Camo Duck: A camouflage hat. An enormous orange beak. Flawless concealment.
4. Volunteer Bug: Six legs. Still only needs one to trip up the whole game.
5. Foam Shield: A big shiny cross. Mostly marks where the damage will go.
6. AFK Hero: Headset on. Eyes closed. Contribution complete.
7. Short-Sighted Sniper: A crosshair this large should make missing harder. It does not.
8. Battle Chicken: The comb is natural. The military authority is self-appointed.
9. King of Excuses: All those points. Still none aimed at personal responsibility.
10. The Last Brain Cell: Every wrinkle is another reason not to join the voice chat.
Render the subject of every title literally and make its associated visual joke visible. No written jokes; everything through image. Each illustration independently composed with subject centered upper-middle and supporting environment. This is ten finished artworks arranged as a precise uniform grid, not a contact sheet of cards or a screenshot.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-1def889c-0a68-40c3-8c8f-c26317cd935c.png

### sheet2

Create a high resolution 3840x2304 illustration atlas with EXACTLY FIVE equal columns and TWO equal rows, exactly TEN independent full-bleed portrait illustrations. Every cell has aspect ratio 2:3. No gaps, no gutters, no dividing border, no text, no numbers, no lettering, no card frames. Each cell is a separate scene and must stay wholly within its own rectangle; no elements cross cells. Consistent premium detailed painterly collectible game card art. Fantasy dungeon comedy, amber torches violet shadow, mature painterly fantasy game illustration, weathered stone and rich fabrics. Strong distinct focal subjects, physical depth and lighting, rich scenes, clean readable silhouettes, humorous visual storytelling, no flat vector or emoji art. The ten cells in strict reading order LEFT TO RIGHT across TOP row then LEFT TO RIGHT across BOTTOM row depict:
1. Intern Goblin: The ears hear every instruction. The face suggests none were understood.
2. Lukewarm Slime: Looks like it wants a hug. Feels like a wet sock.
3. Flip-Flop Knight: Steel on top. Annual leave on the bottom.
4. Expired Potion: The bubbles are reassuring. The missing label is less reassuring.
5. Suspicious Chest: Teeth are generally a poor sign in furniture.
6. Accountant Rat: That cheese wedge is a deductible business expense.
7. Union Candle: A tiny flame. A heroic amount of wax on the table.
8. Passive Mushroom: Under that enormous hat is absolutely no intention to help.
9. Busy Skeleton: No brain, no skin, no free slots on the calendar.
10. Cardboard Shield: The wooden cross is load-bearing optimism.
Render the subject of every title literally and make its associated visual joke visible. No written jokes; everything through image. Each illustration independently composed with subject centered upper-middle and supporting environment. This is ten finished artworks arranged as a precise uniform grid, not a contact sheet of cards or a screenshot.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-5b65997a-3f8a-4ea8-8415-9d98eb7629be.png

### sheet3

Create a high resolution 3840x2304 illustration atlas with EXACTLY FIVE equal columns and TWO equal rows, exactly TEN independent full-bleed portrait illustrations. Every cell has aspect ratio 2:3. No gaps, no gutters, no dividing border, no text, no numbers, no lettering, no card frames. Each cell is a separate scene and must stay wholly within its own rectangle; no elements cross cells. Consistent premium detailed painterly collectible game card art. Fantasy dungeon comedy, amber torches violet shadow, mature painterly fantasy game illustration, weathered stone and rich fabrics. Strong distinct focal subjects, physical depth and lighting, rich scenes, clean readable silhouettes, humorous visual storytelling, no flat vector or emoji art. The ten cells in strict reading order LEFT TO RIGHT across TOP row then LEFT TO RIGHT across BOTTOM row depict:
1. Tech Support Wizard: The beard is long because he is still waiting for your system to restart.
2. HR Bat: The wings say vampire. The expression says mandatory training.
3. Dragon on Leave: One little flame. He is doing the absolute contractual minimum.
4. Axe on Finance: The shiny bit is yours. The handle still belongs to the bank.
5. Shy Ghost: Two worried eyes and a sheet. Somehow you are the awkward one.
6. Parking Paladin: That shield protects a sacred, completely free parking space.
7. Paperwork Lich: Two empty eye sockets. Still spots the missing signature.
8. Gourmet Mimic: Polished wood. Sharp teeth. Terrible restaurant seating.
9. The Dark Duck: A terrifying dark crown. Still fundamentally a duck.
10. The Monday Boss: A crown heavy enough to make any morning someone else’s problem.
Render the subject of every title literally and make its associated visual joke visible. No written jokes; everything through image. Each illustration independently composed with subject centered upper-middle and supporting environment. This is ten finished artworks arranged as a precise uniform grid, not a contact sheet of cards or a screenshot.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-decda5c9-6209-41ee-83f2-9d309cadb650.png

### sheet4

Create a high resolution 3840x2304 illustration atlas with EXACTLY FIVE equal columns and TWO equal rows, exactly TEN independent full-bleed portrait illustrations. Every cell has aspect ratio 2:3. No gaps, no gutters, no dividing border, no text, no numbers, no lettering, no card frames. Each cell is a separate scene and must stay wholly within its own rectangle; no elements cross cells. Consistent premium detailed painterly collectible game card art. Retro science fiction salvage comedy, teal/copper/gold palette, mature painterly space game illustration, detailed machinery and atmospheric starlight. Strong distinct focal subjects, physical depth and lighting, rich scenes, clean readable silhouettes, humorous visual storytelling, no flat vector or emoji art. The ten cells in strict reading order LEFT TO RIGHT across TOP row then LEFT TO RIGHT across BOTTOM row depict:
1. Junior Space Janitor: A broom in space. Finally, a job where sweeping things under the rug is physically impossible.
2. Express Delivery Pod: The parcel has rockets. Your missing package has officially escalated.
3. Emotional Support Drone: Those bright little eyes care about you. Until the battery hits three percent.
4. Lunchbox Reactor: The sandwich is cold. The warning light is doing its best.
5. Warranty Void Bot: A screwdriver for an arm. A warranty sticker already in the bin.
6. Space Traffic Cone: Four billion stars. Somehow this orange cone has closed your lane.
7. Moon Roomba: All those wheels, and it still found the one cable on the moon.
8. Definitely Not an Egg: The crack is glowing. The clipboard says this is probably normal.
9. Emergency Pizza: Perfectly round. Mostly edible. Currently achieving escape velocity.
10. Budget Jetpack: Two tanks, one taped hose, and absolutely no return policy.
Render the subject of every title literally and make its associated visual joke visible. No written jokes; everything through image. Each illustration independently composed with subject centered upper-middle and supporting environment. This is ten finished artworks arranged as a precise uniform grid, not a contact sheet of cards or a screenshot.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-f4e2f82d-2110-4998-9f2f-a48eda026f86.png

### sheet5

Create a high resolution 3840x2304 illustration atlas with EXACTLY FIVE equal columns and TWO equal rows, exactly TEN independent full-bleed portrait illustrations. Every cell has aspect ratio 2:3. No gaps, no gutters, no dividing border, no text, no numbers, no lettering, no card frames. Each cell is a separate scene and must stay wholly within its own rectangle; no elements cross cells. Consistent premium detailed painterly collectible game card art. Retro science fiction salvage comedy, teal/copper/gold palette, mature painterly space game illustration, detailed machinery and atmospheric starlight. Strong distinct focal subjects, physical depth and lighting, rich scenes, clean readable silhouettes, humorous visual storytelling, no flat vector or emoji art. The ten cells in strict reading order LEFT TO RIGHT across TOP row then LEFT TO RIGHT across BOTTOM row depict:
1. Clipboard Commander: The helmet is sealed. The clipboard is somehow still more important.
2. Unionised Loader: Huge hydraulic arms. A tiny mug. A legally protected tea break.
3. Asteroid Hamster: That enormous helmet contains one hamster and several bad decisions.
4. Sentient Vending Machine: It has eyes now. Your snack has been judged and withheld.
5. Lost Probe: Two solar panels and a map. Both facing the wrong way.
6. Captain Overtime: The gold visor says captain. The clock says he missed dinner again.
7. Cat in the Cockpit: Both paws on the controls. Neither eye on the destination.
8. The Spare Parts Titan: One colossal arm, two different knees, and a receipt no one can find.
9. Cosmic Rubber Duck: A golden halo and an astronaut helmet. Still squeaks when you press it.
10. The Final Coffee: The cup floats. The spoon floats. The entire station waits for its owner to wake up.
Render the subject of every title literally and make its associated visual joke visible. No written jokes; everything through image. Each illustration independently composed with subject centered upper-middle and supporting environment. This is ten finished artworks arranged as a precise uniform grid, not a contact sheet of cards or a screenshot.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-307525d4-83b8-44b2-a4ce-13865a3bc54d.png

### packs_v6

Create a premium illustrated packaging art atlas in THREE EXACT EQUAL VERTICAL COLUMNS with no gutters. Overall landscape2:1, each individual panel portrait2:3. No lettering, no words, no logos, no photographed wrapper: actual full-bleed artwork designed to print on card pack foil. LEFT: Chaos Crew, neon purple/teal street gaming heroes, heroic headset wearer with improvised cardboard armor and tactical pigeon and electric circuitry, dynamic angular graphic composition. MIDDLE: Discount Dungeon, amber/violet painterly fantasy, ominous magical treasure chest wrapped in enchanted golden chains with a large ornate key floating above, dungeon arches and curling magical smoke. RIGHT: Orbital Oddjobs, teal/copper retro science fiction, battered rocket delivery capsule falling toward an orbital space station, luminous orbital rings and stars. Highly detailed premium game concept art and strong original distinct symbols, polished materials and epic lighting, no text/frame/UI. Each composition independent and centered wholly in its equal panel.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-db021fa1-52ed-47fe-81be-73af16d1d6a7.png

### binder_v6

Create a wide16:9 detailed atmospheric premium game illustration of a private collector's archive, no text/UI. Elegant dark plum wood and leather study with tall cabinets of beautiful binders on both sides, glass display alcoves holding rare glowing fantasy relics, large rich burgundy leather card collecting desk in foreground and gold brass fittings. Cozy amber desk lamps, violet ambient light, rain on distant windows. Mature painterly game environment concept art, sophisticated tactile materials, believable depth, no characters, no lettering. Strong unique luxurious archive identity, middle area relatively calm for webpage content overlay.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-8e8964da-7e10-4f46-be5b-9c48d2b91afc.png

### community_v6

Create a wide16:9 detailed atmospheric premium game illustration of a social gaming lounge, no text/UI. Stylish dark teal and indigo futuristic cafe, curved comfortable booths, warm copper hanging lamps, several young adult collector friends in distant background exchanging trading cards and laughing at a table, a panoramic night city window, plants and shelves of board games with unmarked spines. Mature painterly game environment concept art, cozy social energy, beautiful reflections and tactile materials, not corporate office. Foreground and center calm dim surfaces for webpage content overlay, no readable lettering, no logos.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-574af342-7efe-4920-b28f-67adde5b1519.png

### printing_v6

Create a wide16:9 detailed atmospheric premium game illustration of a boutique physical card printing and packing atelier, no text/UI. Beautiful warm cream paper stock, olive metal vintage-modern precision printing press, brass rollers, color ink jars, neatly stacked card sheets, craft tools, open cardboard mailers, cotton gloves on wooden workbench. Sunlit amber workshop with teal shadow, elegant tactile paper and leather materials, mature painterly game environment art. No characters, no lettering/logos. This is a warm artisan studio distinctly different from a dark gamer room, central region softly calm for webpage overlay.

Source: /workspace/scratch/9f8298f0e77d/generated_images/exec-65bf1763-af55-487e-8478-cc9b965d5ab5.png



---

# Original file: docs/ART_ASSETS_V7.md

# Edition 7 artwork

Generated with the built-in image generation tool, 10 October 2026. These are original prototype illustrations, not licensed franchise artwork or commissioned final production art. All nine outputs were visually inspected. PNG outputs were encoded as WebP using Sharp, quality 90 (91 for card sheets); no compositing or destructive cropping.

## Assets and layout

- `dist/assets/v7/couriers-1.webp`, `couriers-2.webp`, `moonlit-1.webp`, `moonlit-2.webp`: 1619 × 971; each is a five-column, two-row atlas of portrait art. CSS background size 500% 200%; cell positions x=0/25/50/75/100%, y=0/100%. Each sheet maps ten consecutive cards. All subjects and visual jokes inspected in source images.
- `packs.webp`: 1448 × 1086; two equal portrait panels: couriers then moonlit. Background size 200% 100%.
- `discovery.webp`: 1672 × 941; purpose-composed collector observatory, portal to right, atmospheric left-side space for UI.
- `couriers-hero.webp`: 1672 × 941; purpose-composed copper postal hall, robots and parcels right, quiet teal architecture left.
- `moonlit-hero.webp`: 1672 × 941; purpose-composed nocturnal animal hotel, fox reception right, quiet indigo architecture left.
- `binders.webp`: 2172 × 724; five equal art-insert panels in order recrues, donjon, orbital, couriers, moonlit. Background size 500% 100%. Inserts should preserve original colours; user-selected colours should affect surrounding binder parts.

## Prompt set

Card sheets requested exactly five columns × two rows without gaps or text, each cell portrait 2:3, polished clean detailed painterly game illustration and readable visual jokes. Couriers palette copper/teal/amber, whimsical steampunk delivery city. Menagerie palette indigo/rose/silver with warm hotel candlelight. Each card scene appears in the mapping below. Card order is row-major.

Packs prompt: two portrait flat printed artworks side-by-side, no labels or borders; left copper robot riding winged clock delivering an envelope over clockwork city, right regal black cat in crescent crown with owl and fox at enchanted midnight hotel.

Discovery prompt: widescreen purpose-composed collector observatory at twilight, navy/purple left-side negative space for text, right-side glowing circular display portal, floating crystal relic cards and universe windows, architectural storytelling, no people or text.

Couriers hero prompt: widescreen grand copper clockwork postal sorting hall, teal glass windows, mail tubes and little delivery robots carrying oversized parcels toward the right; left 45% calm teal architecture and empty desk for headline.

Menagerie hero prompt: widescreen indigo velvet rose-gold hotel lobby, crescent window and moon, fox concierge right, owl on lamp, cat asleep on chair, garden beyond; left 45% quiet indigo architectural space.

Binder inserts prompt: five equal vertical panels in one 3:1 atlas, no cover edges/spines/text; Chaos masked gaming squad and foam shield (purple/lime), Dungeon goblin and crowned dark duck beside treasure (amber/emerald), Orbital astronaut and cat in cockpit (teal/navy), Couriers ornate robot with envelope and clockwork city (copper/teal), Menagerie regal black cat among flowers and hotel (indigo/rose/silver).

## Card mapping and visual joke copy

- **couriers-01 Oversized Delivery** — The parcel has hired a robot to carry itself.
- **couriers-02 Return to Sender** — The letter goes in. The same pigeon comes out.
- **couriers-03 Magnetic Personality** — His compass has followed the magnet for three districts.
- **couriers-04 Boiling Point** — He needs a quiet moment. And a mug.
- **couriers-05 Fragile Confidence** — Handled with confidence. Unfortunately, it needed care.
- **couriers-06 Express Snail** — Even the organic competition is pulling ahead.
- **couriers-07 Parcel First** — The box stays dry. Employee maintenance is another department.
- **couriers-08 Tailspin Terrier** — That suspicious key has followed him all morning.
- **couriers-09 Out of Office** — Every envelope is marked urgent. The pillow wins.
- **couriers-10 Small Maintenance** — Polishing the tool is his entire apprenticeship.
- **couriers-11 Square Wheel Special** — Every revolution is a workplace incident.
- **couriers-12 Dragon Mail** — Your parcel arrived toasted on both sides.
- **couriers-13 Nested Luggage** — One more suitcase and he qualifies for overtime.
- **couriers-14 Screw Feeder** — Please do not feed the birds imperial fittings.
- **couriers-15 Eight-Handed Sorting** — Eight arms. Not one correct address.
- **couriers-16 Rocket Butler** — Tea will be served shortly. Somewhere.
- **couriers-17 Walking Inbox** — He has forty unread letters and several on his face.
- **couriers-18 Daylight Savings** — He saved some daylight. Nobody mentioned a container.
- **couriers-19 The Last Postwyrm** — An entire dragon protects your invitation to a dentist.
- **couriers-20 Midnight Dispatch** — The clocktower flies because the coffee cannot be late.
- **moonlit-01 Overnight Baggage** — One guest. Twelve suitcases. No visible limbs.
- **moonlit-02 Upside-Down Owl** — Your booking exists. He is simply reading it from Australia.
- **moonlit-03 Marshmallow Hedgehog** — The hotel buffet has developed legs.
- **moonlit-04 Suitcase Concierge** — Your luggage now belongs to management.
- **moonlit-05 Moon Tea** — Decaffeinated. Still causes tides.
- **moonlit-06 Teacup Spa** — Five stars. Slightly herbal.
- **moonlit-07 Sheet Bat** — The ghost is included in the cleaning fee.
- **moonlit-08 Lamp Romance** — He requested a room with a view of the lamp.
- **moonlit-09 Rabbit Recursion** — The assistant has hired an assistant.
- **moonlit-10 Crescent Disaster** — Tonight the croissants match the dark side of the moon.
- **moonlit-11 Glitter Snail** — His entrance lasts longer than the event.
- **moonlit-12 Cheese Knight** — He will secure the perimeter. Then eat it.
- **moonlit-13 Grand Entrance** — The entrance is grand. Entering is another matter.
- **moonlit-14 Piano Otter** — Tonight: an uninterrupted performance in D-sleep.
- **moonlit-15 Dramatic Possum** — The room service charge was too much to bear.
- **moonlit-16 Backward Stargazer** — After years of research, the moon appears to be a paw.
- **moonlit-17 Antler Florist** — He cannot clock out until the flowers stop blooming.
- **moonlit-18 Formal Jellyfish** — Black tie mandatory. Skeleton optional.
- **moonlit-19 Moon Dragon** — No vacancies. The dragon is using the entire hotel as a pillow.
- **moonlit-20 The Night Manager** — Your complaint has been placed in the universe-containing teacup.


---

# Original file: docs/ART_ASSETS_V8.md

# Edition 8 — dedicated opening environments

Six original widescreen interface backgrounds generated with the built-in imagegen tool, 10 October 2026. All source images visually inspected and converted to WebP quality 88 using Sharp. All 1672 × 941. No cropping, compositing, or source-art reuse. Intended as decorative full-bleed backgrounds; layer UI above them. Tables intentionally keep their central/lower area clear. These are generated illustrations, not commissioned production artwork.

## Assets and prompt set

Shared table direction: seated collector perspective across a broad tabletop, central and lower 70% quiet space for cards and controls. World atmosphere visible at upper sides and corners. No foreground characters, cards, text or logos. Widescreen 16:9, clean shapes and purposeful art style rather than uniform glossy hyperdetail.

- `dist/assets/v8/recrues-table.webp`: Chaos Crew — bold cel-shaded violet/acidic-green gaming team workshop, angular acoustic panels, neon light bars, headphones and soda at side corners. Matte charcoal tabletop. Graphic confident shapes and restrained detail.
- `dist/assets/v8/donjon-table.webp`: Discount Dungeon — handpainted storybook gouache, broad brush shapes, candlelit stone-and-timber tavern, treasure chest and mushroom at upper corners, broad wooden tabletop. Amber/moss palette.
- `dist/assets/v8/orbital-table.webp`: Orbital Oddjobs — clean retro science-fiction concept illustration, spaceship panoramic docking-bay windows and ringed planet, tactical desk with blue-grey surface, orange hazard trim, teal strip lights. Purposeful simple industrial shapes.
- `dist/assets/v8/couriers-table.webp`: Clockwork Couriers — architectural ink and paint, brass/teal postal sorting desk, pneumatic tubes and envelopes at outer corners, clockwork-city bridges beyond windows. Broad dark-teal leather desktop with copper edging.
- `dist/assets/v8/moonlit-table.webp`: Moonlit Menagerie — dreamy illustrated watercolor, indigo/rose conservatory, moonlit garden windows and roses, porcelain teacup at outer corner. Broad empty indigo velvet table with sparse celestial corner decoration.
- `dist/assets/v8/arrivals.webp`: editorial announcement banner, two contrasting portal doorways on right 60%: copper clockwork postal city and indigo crescent magical hotel garden. Dark quiet left 40% for headline text. Ink-and-paint architectural treatment with readable forms and subtle light spill.

## Inspection

All five table images keep a clear central foreground and visually distinct materials/palettes. The announcement places both portals to the right with useful dark text space to the left. Generated background quality does not by itself establish the quality of the integrated UI; responsive crops and text contrast require interface validation.


---

# Original file: docs/ART_ASSETS_V9.md

# Edition 9 — prestige opening rooms

Five original widescreen backgrounds generated with the built-in imagegen tool, 10 October 2026. All source images were visually inspected and converted to WebP quality 88 using Sharp. All are 1672 × 941. No cropping or compositing, no reuse of card artwork. These are generated art assets, not commissioned final franchise artwork.

## Prompt set and assets

Shared direction: purpose-composed 16:9 collectible-site opening-room background, seated collector perspective across broad empty tabletop, calm central foreground for card UI, grand world architecture above and around it. No characters, cards, text, numbers or logos. Clean intentional shapes, varied illustrated styles rather than generic glossy noise.

- `dist/assets/v9/recrues-prestige.webp`: Chaos Crew neon tournament command booth, cel-shaded comic game style, angular violet/acid-green holographic rails, distant arena with floating blank geometric display panels. Broad matte midnight desk.
- `dist/assets/v9/donjon-prestige.webp`: Discount Dungeon dragon treasure vault, handpainted storybook gouache, stone columns shaped as folded dragon wings, gilded side alcoves, warm braziers and moss-green shadow. Broad dark carved-stone tabletop with gold scroll fittings at side edges.
- `dist/assets/v9/orbital-prestige.webp`: Orbital Oddjobs captain’s bridge, clean retro sci-fi concept illustration, panoramic ringed blue planet and fleet, circular tactical console, orange side fittings and teal rim lighting. Quiet blue-grey center surface.
- `dist/assets/v9/couriers-prestige.webp`: Clockwork Couriers observatory postal engine, architectural ink and paint, brass orrery, pneumatic tubes, teal arches and skybridges, outer brass drawer stacks. Broad dark teal leather postal desk.
- `dist/assets/v9/moonlit-prestige.webp`: Moonlit Menagerie floating greenhouse observatory, dreamy illustrated watercolor, glass dome, hanging gardens, enormous crescent moon and floating hotel towers. Deep indigo crescent-edged desk with pale floral edge filigree.

## Inspection notes

All five outputs keep the foreground unobstructed and provide stronger architectural world identity than the base rooms. Moonlit has more visible architecture and a slightly smaller clear tabletop fraction, but its central lower area remains available for UI. Integrated responsive cropping and contrast still require site-level verification; asset inspection alone does not prove the interface is release-ready.


---

# Original file: docs/EDITION_05_BRIEF.md

# Edition 05 — user annotations and delivery scope

The user explicitly authorized implementation of all 25 annotations plus coherent improvements on 2026-10-10, after asking us to wait while collecting batches. All written comments arrived; annotation image files were unavailable. Preserve this list as the review checklist.

1. Social features.
2. Richer Print Studio.
3. Discovery carousel with arrivals, recommended packs, social highlights, franchise merch and combined shipping concept.
4. Social content lower on discovery.
5. Missing-card stats scoped to selected/favourite franchises, with per-franchise drilldown.
6. Illustrated page backgrounds.
7. Free layout customization plus earned cosmetics; a rare bonus sixth card can unlock a franchise binder.
8. More manageable, visually interesting binders.
9. Allow recycling the last owned copy behind two warnings; protect valuable cards from accidental recycling.
10. Fix missing card text in detail view.
11. Clickable artist credit in card/details leading to all the artist's work.
12. Bulk recycling with filters.
13. Main catalog navigation is franchise-based; artists remain discoverable through credits.
14. Multiple packs in sequence, boxes with their own themed opening and a pack count.
15. More impressive franchise opening effects.
16. One coherent illustrated card-back design per franchise.
17. Open another pack from the reveal screen.
18. Rarity-scaled card reveals; legendary theatrical animation.
19. Stronger franchise frames and premium artwork.
20. Illustrated opening table and physical drag to reveal/file; invalid drops spring back.
21. Global Back.
22. Match interactions to object/franchise; dungeon chest uses key, not arbitrary breaking.
23. Clear insufficient-credit feedback at purchase.
24. Direct foil tearing on pack; inspect/rotate packs and cards with light-reactive foil.
25. Next plays transition faster.

## Product choices for this pass
- Retain original 60-card catalog and stable IDs, existing ownership, economy, orders and custom content.
- Fictional social demo with local follows/likes/profile/showcase; no messages sent to other people.
- Merchandise and combined print quote/order are simulated and labelled. No payment or shipping data.
- Persist paid pack queue and reveal position; refresh cannot lose a purchased box.
- Cosmetic bonus is additional to normal cards, explicitly stated chance, no paid advantage. Free customization always available.
- Protect print entitlements, queued print copies and manually locked cards when recycling. Preview exactly what will be removed. Last-copy removal requires a second confirmation.
- Add favourites, wishlisting, folder sort/order/skin, profile showcase, search, responsive controls, reduced motion and keyboard alternatives.
- Work remains browser-local and private. Browser QA unavailable unless the supported control-browser skill becomes available.

## Delivery status
Implemented all 25 items as browser-local prototype interactions. Site renamed Astra Tessera. Social and fulfillment remain explicitly simulated. Six generated paintings supplement 60 stable card entries. Domain and DOM-stub tests cover the principal flows; real-browser visual verification is unavailable in this environment.


---

# Original file: docs/EDITION_06_BRIEF.md

# Astra Tessera — round 6, 40 written annotations
1 Live customization preview beside controls.
2 Auto discovery carousel with unboxed edge arrows.
3 News/editorial and other carousel content.
4 Actual card illustrations for all cards; substantive franchise borders.
5 Larger universe introduction and pack CTA; cards lower down.
6 Dedicated pack artwork; physical manipulation on store.
7 Remove universe selector within its pack store.
8 Visual pack quantity options.
9 Multiple singles visually grouped; actual box with visible packs/lid.
10 Automatically advance successive packs.
11 Improve seal-tear animation.
12 Directional bend/foil on special card drag; dragging hidden card must NOT reveal.
13 Next beneath stack; top corner open-all.
14 Manipulate pack during opening.
15 Remove redundant Tear seal/autoplay controls.
16 Stronger artwork-related card entrances.
17 Exposed lower cards use actual shared franchise back art.
18 Retain cursor shine.
19 Unique colourful binder shapes.
20 Holographic sci-fi binder / fantasy scroll variants.
21 Correct foil pointer coordinate offset.
22 Artist Back restores prior card detail, filters, scroll and reveal position.
23 Larger recycling control.
24 Sleeve animation when protecting card.
25 Showcase preview / reversible popup from detail.
26 Free six-part binder colours; earned cosmetics change structure.
27 Visible Cover control.
28 Distinct illustrated backgrounds per space.
29 Showcase picker modal: universe then owned card, no detour.
30 Profile customizations, favourites/games/Steam profile showcase (manual demo, no implied integration).
31 Opening table above Universes.
32 Smooth pack manipulation.
33 Same physical interaction during opening.
34 Fix wrong-universe box queue; franchise box ceremonies.
35 Remove duplicate key; smooth lock interaction.
36 Smooth accurate shine.
37 Smooth directional card angle.
38 Visible key-turn animation.
39 Manipulate sealed pack directly on pack store.
40 Same arrow design for code and controls.

Scope: preserve inventory and print entitlements, local-only social/commerce, private access. Add natural finishing touches without fake live news, external posts or connected Steam claims. Existing screenshot attachments unavailable; written targets/comments authoritative. Validate code/domain and event flows; supported browser QA unavailable.

## Implementation and verification
All40 written items are implemented as local prototype behavior. The art package maps60 dedicated paintings plus3 existing premium overrides,3 dedicated pack illustrations and3 distinct room illustrations. Full2:3 card windows retain visual punchline props. No external daily-news feed or Steam integration is claimed; studio updates and manually entered Steam profile links are explicitly identified.

Pointer gestures are frame-scheduled, with foil coordinates measured on the foil surface. Hidden drags do not flip. Batch metadata separates newly purchased universes, protects old queued packs and enables automatic continuation. Older contiguous waiting packs acquire compatible batch metadata without changing inventory. The test suite verifies these states and event wiring, not actual browser layout or animation feel. Supported browser QA remains unavailable.


---

# Original file: docs/EDITION_07_BRIEF.md

# Astra Tessera — Edition 07

User authorized two new worlds, all pending feedback, a self-directed defect review and a substantial polish pass. Preserve original sets, ownership, quantities, print entitlements, saved queues and custom content. Keep private audience.

## Annotation ledger

1. Purpose-composed page backgrounds instead of repeated universe images.
2. Clear spaced pause bars.
3. More appearance colour choices.
4. Preview different page layouts and density modes.
5. Binder structure, artwork and editable material colours are separate.
6. Drag binders into preferred shelf positions; retain keyboard ordering.
7. Larger recycling and wishlist controls.
8. Whole pack-display interaction area, shorter display, return object to rest on release.
9. Proper illustrated box geometry; keep loose pack bundles.
10. Packs should feel three-dimensional.
11. Inspect-to-open action preserves selected quantity and displays price.
12. Repair seal drag regression.
13. Tear should visibly open wrapper.
14. Standard whole-card proportions, not portrait plus oversized text panel.
15. Stable corner hover, no twitching.
16. Cleaner franchise-specific frames; current concept shapes are not final art direction approval.
17. Protective sleeve follows actual card outline and dimensions.
18. Showcase order and a stronger presentation for favourite pulls.
19. More accessible showcase entry point.
20. Profile atmosphere previews.
21. Franchise-specific opening tables and atmosphere.

## New worlds

Clockwork Couriers (`couriers`) and Moonlit Menagerie (`moonlit`), 20 cards each. Do not use `clockwork`: that ID belongs to a legacy archived collection. Each receives its own art, frames, opening ritual, binder style, and collecting surface.

## Quality boundary

Implemented is not synonymous with finished. This is a local-state prototype; community, purchases and shipments are demonstrations. Generated art is concept artwork, not a claim of commissioned or licensed production art. Material and motion work brings the prototype closer to the intended experience but does not establish final visual approval.

Browser QA is unavailable because the supported browser-control skill is absent. Source checks, state-machine tests and DOM stubs cover behaviour and accounting; they do not certify layout, animation smoothness, or physical input hit-testing in a real browser. Avoid claiming those are fully verified.


---

# Original file: docs/EDITION_08_BRIEF.md

# Astra Tessera — Edition 08

Requested: latest fourteen comments, the new-universe announcement, and an independent usability/polish sweep. Existing ownership, print entitlements, saved openings and working foil lighting must survive.

## Delivered changes

- Actual current-page HTML and styles in a sandboxed preview, with Discover/Binder/Cards/Profile and desktop/phone modes. Preview rendering does not mutate navigation, inventory or openings.
- Lounge starts with the owner's showcase, collection milestones and illustrated favourites. Local guestbook follows; collector browsing, sample standout pulls and a clearly marked sample completion board follow below.
- Showcase drag ordering on the profile, lounge and detail popover, with keyboard-friendly arrow alternatives. Local shared posts remain accessible.
- Favourite games get known Steam header art, a graceful monogram fallback and official links. An exact/known-alias match to a real catalogue collection enables collection navigation; unrelated demo sets are never presented as licensed game sets.
- Sticky top navigation, scroll-to-top after scrolling, and opening-page entry reset to top. Artist return context remains unchanged.
- Pack interaction surface fills the full store column. Packs have separate front/back/edge planes; boxes have front/sides/floor/hinged lids with contained packs.
- Clockwork rebuilt as a pneumatic dispatch machine with pressure gauge, wheel, shutters and steam. Moonlit rebuilt as an ordered constellation under a lifting glass dome, with fireflies and emerging cards. Progress updates preserve live controls rather than restarting their animation on each click.
- Five independently generated world environments for the opening tables and rituals. Graphic cel shading, gouache tavern painting, retro sci-fi, architectural ink/paint and watercolor garden directions. Existing card shine preserved.
- New arrivals is the first Discover slide, featuring Clockwork Couriers and Moonlit Menagerie. A What's new entry is available in the top bar.

## Verification and remaining boundary

51 automated tests cover state/accounting, legacy migrations, pack queue isolation, manual rituals, ordered Moonlit input, preview state isolation, drag showcase ordering, game resolution, comment round-tripping and quantity-preserving milestones. JavaScript and local asset references checked. Generated environments inspected separately.

No supported browser-control skill is available in this environment. These are source/DOM-stub tests, not a claim of real-browser visual or animation QA. Geometry, responsive previews and gesture smoothness require a browser verification pass when available. Do not label this visually final or release-ready solely because tests pass.

Community comments, likes, profiles and purchases remain browser-local prototype data. Sample collectors/rankings are labelled fictional. Live social accounts, moderation, authoritative ownership, checkout and fulfilment are still future production work. Generated art remains concept artwork, not commissioned/licensed production art. Favourite-game header images are external Steam store assets and may fall back if unavailable.


---

# Original file: docs/EDITION_09_REVIEW.md

# Astra Tessera — Edition 09

## Intent

Ravn requested one substantial update combining the latest annotation fixes, six collector features, a first-visit review, and a noticeable step toward finished visual quality. “Implemented” does not mean approved final art. Preserve the physical collecting feel, English art-specific humour, ownership, printing limits and working card shine.

## Delivered

- Contextual showcase navigation; compact favourite-game tiles whose dimensions do not depend on quantity.
- Card filing uses the actual tray rectangle in viewport coordinates and snaps into the tray; no arbitrary horizontal-distance threshold.
- Open-all results include bonus cosmetics. Closing the results returns to the completed opening table.
- Removed the redundant pack angle reset control.
- Opening environments change materials, frames, rails, controls, shapes and surrounding navigation per universe while retaining the neutral currency/back bar.
- Five purpose-made prestige-room artworks. New table cosmetics are extra collectibles, not replacements for the five regular cards.
- Deterministic collection milestones, claimable display objects, ornate and prestige tables, pinned completion goals, missing-card wishlisting and exact crafting costs.
- Collector room combining binders, favourite pulls, earned objects and two display arrangements; image export for sharing.
- Card memories, private notes and acquisition journal. Earlier ownership is explicitly undated; no invented historic dates.
- Four arrangeable nine-pocket print pages, quantity enforcement, downloadable page proof and an explicit review before replacing parcel card quantities.
- Local spectator window with revealed-card-only updates and reactions, intended for screen sharing. No remote social backend is claimed.
- Global search, a short first-visit path, help, update announcements and an in-site Design review.

## Latest annotation disposition

1. Showcase highlight: active only in its own view.
2–3. Favourite games: fixed-size wrapping tiles.
4. Dragging past pulls: actual target geometry and automatic filing.
4–5. Whole universe opening space: distinct furniture and structural styling, not only a background swap.
6. Open-all dismissal: stays on the completed table.
7. Reset angle: removed.
8. Clockwork mechanism: retained; praised direction is not discarded.
9. Elaborate unlockable tables: additional collectible rewards and collection milestones.

## Design decisions awaiting Ravn's judgment

| Area | Current decision | What remains uncertain or provisional |
|---|---|---|
| Card art | Preserve existing paintings and the working shine | Existing paintings are concept art. Each card still needs individual composition, anatomy, detail and consistency review; not all art is declared final. |
| World identity | Five distinct visual languages, materials and control furniture | Whether the user wants stronger divergence in card illustration styles too. |
| Prestige environments | Rich architecture surrounds a quieter card-handling area | Whether they are elaborate enough; responsive crops and readable contrast need visual approval. |
| Physicality | Layered illustration/CSS furniture, tilt, spring-back and tray snapping | These are not full 3D spaces. Exact weight, tilt limits, clipping and animation smoothness need real browser evaluation. |
| Collector room | Curated gallery/study layouts with movable collection items | A fully free room editor, arbitrary object placement and more showcase slots are not included. |
| Rewards | Predictable milestones alongside extra table collectibles | Exact progression thresholds and duplicate cosmetic treatment need product tuning. |
| Print proof | Editable nine-pocket page with owned-copy checks | This is a visual planning export, not printer-ready colour-managed artwork or a physical fulfilment integration. |
| Social | Local spectator screen and local prototype social features | Real remote rooms, accounts, moderation, cloud ownership and cross-device syncing require a backend phase. |
| Commerce | Existing simulated parcel flow | No real payment, shipping, licensed franchise partnership or production service is represented as active. |

## Verification

59 automated tests pass, including the expanded app smoke journey: collector routes, milestone selection, print planning, batch-result return, physical tray filing and spectator privacy. Asset paths, module syntax and package contents are checked separately before publication.

Supported browser automation is unavailable in this environment. DOM stubs exercise actions and state transitions; they do not establish pixel-perfect responsive layout, animation smoothness, real pointer capture, popup behaviour or export appearance. The artwork was visually inspected as individual assets. Those are distinct levels of evidence.

## Reference research

- Steam Trading Cards: collections can lead to visible profile expression and completion rewards. https://steamcommunity.com/tradingcards/?l=english
- Steam Trading Cards FAQ: readable collection progress. https://steamcommunity.com/tradingcards/faq/I?l=english
- Discogs collection/wantlist notes: give collectors a personal record beside ownership. https://support.discogs.com/hc/en-us/articles/360007425393-How-Can-I-Add-Collection-Wantlist-Notes
- TCGplayer saved/shared lists: reduce the friction between collecting intentions and a reusable list. https://help.tcgplayer.com/hc/en-us/articles/115009506287-Saving-and-Sharing-Lists

These informed interaction patterns. No page, brand identity or proprietary artwork was copied. Speculation, card-market prices, artificial urgency and daily streak pressure were deliberately not added.


---

# Original file: docs/EDITION_10_REVIEW.md

# Astra Tessera — Edition 10 review

2026-10-10. A substantial collecting-room and interaction pass, preserving the existing local collection and private site audience.

## What changed

- Original physical binder illustrations for the five worlds plus three basic covers; a purpose-made collector gallery; five transparent foreground prop arrangements. The opening environments combine scene art, foreground objects, furniture edges, materials and restrained parallax.
- Collection grids use album pages of at most three rows. This applies to franchise folders, universe catalogues, artist catalogues and wishlists. Filter changes reset the relevant page.
- Dragging a revealed card into the filing area shows a release guide. Only release commits the move. Dragging stays within the usable table and hidden cards remain hidden. Binder and showcase neighbours move aside during reorder previews; ownership/order saves only on release.
- Compact desktop opening layouts use available viewport space. Pack selection keeps purchase controls together; detailed odds and cosmetic rules are available in a dedicated panel.
- Repeat purchase remembers the previous quantity, including boxes, with a separate single-pack action.
- Cosmetic duplicates automatically become 40 fragments each. Per-pack processing means a batch can unlock a binder, then a room, then recycle subsequent duplicates. Existing queued rewards are not retroactively credited.
- Collector shelves can hide chosen binders and use three, four or five columns. Smaller physical covers allow more items per row.
- Card stories sit beneath the card, showcase controls expand in place, and protection has a more visible fitted sleeve animation.
- Merchandise uses physical product imagery, layered sleeves, stitched mats and matching concepts for the two newer worlds. The existing simulated print/merch flow remains intact.
- Customizer previews use the actual rendered page and device-specific pagination; new binder previews reflect their physical forms. Cover trim colours do not tint the illustration.
- Edition 10 appears in What's new. Reduced-motion preferences disable the new scene movement.

## Latest annotation checklist

| Batch / note | Disposition |
| --- | --- |
| A1 | Subtle slower background parallax with reduced-motion support; gallery art made for the collecting space. |
| A2–3 | Illustrated merch products and physical miniature binders. |
| A4 | Neighbour displacement while dragging binders or showcase cards. |
| A5 | Full mobile design pass remains a separate phase; responsive fallbacks retained. |
| A6 | Existing print and merch workflow preserved and visually improved. |
| A7–8 | Smaller binder objects, configurable shelf columns and visible-binder selection. |
| A9 | Reduced repeated interaction instructions; essential accessible labels retained. |
| A10 | Cross-site pass through collecting room, store, detail, cosmetics, previews and opening environments. |
| A11 | Three-row album pages across collection-oriented grids. |
| A12 | Story moved under the card to compact the detail layout. |
| A13 | Native expanding showcase section in card details. |
| A14 | Stronger sleeve entrance, sheen and protection badge. |
| A15 | What's new retained and updated for this edition. |
| B1 | Universe catalogues share the same pagination component as binders. |
| B2 / B8 | Layered foreground props and furniture/material treatments move rooms toward an in-world 2.5D scene. Final art-direction approval remains open. |
| B3 | Filing occurs on release; proximity shows an insertion guide only. |
| B4 | Full card bounds constrained to the usable table, excluding the heading. |
| B5–7 | Desktop opening scene sized against viewport with reduced margins and rail slots sized to pack contents. Requires visual browser verification at actual viewport sizes. |
| B9 | Store essentials compacted; secondary odds content moved to an explicit panel. |
| B10 | Room choices preview scene props and differentiated ornamental/prestige furniture treatments. They are not yet wholly separate 3D rooms. |
| B11 | Repeat original pack quantity / box with separate single-pack option. |
| B12 | Duplicate binder/room cosmetics convert to fragments automatically; shared reward presentation supports the same duplicate receipt. Future trinkets are not implemented yet. |
| B13 | Extra cosmetic chance remains visible, with full odds explanation accessible. |

## Decisions for Ravn to judge

1. **Room composition:** deliberately layered 2.5D, rather than a live 3D engine. Does the scale and placement of props feel like occupying the world? This needs your visual review. It is a substantial step, not a claim that the final environment is achieved.
2. **Binder colour customisation:** free colours currently affect the mounting/trim elements. The illustration keeps its authored colours. Independently recolouring six physical parts of an illustrated binder needs authored masks or modular artwork and remains unfinished.
3. **Cosmetic duplicates:** 40 fragments per duplicate is an explicit prototype economy choice, not a balanced production value.
4. **Prestige rooms:** richer trim/structure and scene props distinguish them, but fully bespoke prestige compositions and additional unlockable trinkets remain future work.
5. **Art quality:** new binder and prop assets have been inspected independently. The complete composition and every older card illustration have not been certified as final art. Do not treat this update as completion of all art direction.
6. **Mobile:** the dedicated phone interface redesign is still needed after desktop interaction and art direction settle.
7. **Scope:** this remains a local-state proof of concept. Community content, merchandise and checkout remain simulated; production accounts, server-backed inventory, real payments, shipping and moderation are not introduced here.

## Validation

- Full automated suite: 66 passing tests, including batch rewards, duplicate conversion, legacy queue compatibility, shelf preferences, pagination, bounded drag and reorder geometry.
- DOM-stub smoke tests verify release-only filing, neighbour movement before saved reorder, collection page changes, repeated pack quantity, odds panel, compact detail and news entry.
- DOM-stub tests do not prove browser rendering, animation smoothness or pixel-perfect viewport fit.
- The supported browser-control capability is unavailable in this managed environment. No substitute preview server or unsupported browser automation was used. A real desktop and phone browser pass remains outstanding.

Asset prompts and provenance: `docs/ART_ASSETS_V10.md`.


---

# Original file: docs/EDITION_11_REVIEW.md

# Edition 11 — Craft and feel

## Agreed direction
- A 2D interface with depth and in-world materials, not a navigable 3D videogame.
- Shared interaction structure; distinct world atmosphere and object details.
- Neighbours lean progressively away from dragged objects and return when the object retreats. Do not jump immediately into a new slot.
- Strong binder art takes priority over recolouring. Selective recolouring requires layered/masked artwork and is deferred rather than degrading the designs.
- Modest vertical scrolling is preferable to cramped controls. Phone-specific redesign and economy balancing remain separate phases.
- Fake currency, fictional cards and simulated merchandise remain the prototype's scope. Real commerce is not required.

## This release
- Smaller opening cards with restored movement room, continuous eased boundary resistance and restrained tilt.
- Earlier release guide based on the card's leading edge. Filing remains release-only; dragging hidden cards does not reveal them.
- Gentle distance-based neighbour displacement and tilt; order only saves on release.
- Width-filling opening environment, more comfortable header, vertically stacked actions.
- Five distinct structural frame treatments: squad hardware, fantasy brass/leather, industrial cargo fittings, clockwork brass and lunar silver. Ornate/prestige levels receive greater ornament and material emphasis.
- Five purpose-built card-back illustrations, also used for earned completion emblems.
- Side page-turn controls across album-based collections.
- Smaller binder design tiles, ownership/world filters, bounded scrolling inside the design list, independent preview, optional trim controls. Preview cannot be dragged or reorder the real collection.
- World-specific completion honours on the profile; distinct small completion emblems in the lounge.
- What's new and the in-site design review updated to distinguish settled decisions from open questions.

## Latest annotations
1. Smaller card, fluid movement: implemented; tactile quality still requires human browser review.
2. Earlier insertion marker: implemented and shares release geometry.
3. Existing table composition: retained.
4. In-world edge detail: five distinct crafted frame systems.
5. Fill table width: outer opening margins removed.
6. Three stacked end actions: restored.
7. Rarity/tier detail: expanded frame fittings and prestige crowns.
8. Less cramped header: relaxed viewport-only constraint.
9. Side pagination: implemented.
10–12. Compact binder chooser, fixed selection area and filters: implemented.
13. Non-draggable preview: pointer gesture removed and native image dragging blocked.
Additional three: side controls also in binders; illustrated part recolouring deferred by agreement; profile completion honours added.

## Still provisional
- Two art-direction folders have not been supplied yet. New backs fit the current five worlds; this is not a claim that all existing card art has reached final quality.
- New frame composition, card movement speed and neighbour hesitation need real visual/interaction review.
- Colour controls explicitly change display trim only. They do not recolour the illustrated binder.
- Phone UI still needs its own design pass.
- No new actual payments, external social service, cloud inventory or shipment functionality.

## Validation
69 tests pass, including geometry for progressive yielding, early filing-zone detection, and bounded continuous movement. DOM-stub smoke tests cover actual application flows but cannot verify browser rendering or animation feel. Supported browser-control tooling is unavailable in the managed environment, so full browser QA remains outstanding.


---

# Original file: docs/EDITION_12_REVIEW.md

# Edition 12 — Design Lab and handling repair

## What changed
- Restored the earlier card-drag rotation from source revision 09d685a: sideways bend, vertical lean and in-plane rotation. Pack-preview rotation remains separate. Modern bounds and release-only filing retained.
- Increased neighbour repulsion from 28px/3 degrees to a middle-ground 58px/5 degrees, retaining gradual proximity response and return.
- Opening-table entry scrolls the currency/back bar just above the viewport; sidebar and end actions remain accessible. The top bar is no longer sticky on the active opening screen.
- Fixed card and action layout slots, with a consistent card footprint face-up or face-down, so the first reveal does not change the button position.
- Fixed a CSS naming collision between table-frame corners and card-frame corners.
- Binder-customizer dimensions and design-list allocation stay stable through filters; reduced wasted space and kept trim controls independent.
- Removed redundant bottom pagination controls, retained top count and sticky side arrows, strengthened the page-turn transition.
- Protected cards show a fitted sleeve throughout the binder. Decorative sleeve rewards remain future work; the Lab previews their visual possibilities.
- Collector directory links now navigate to full fictional visitor profiles, with showcase and featured-world binder.
- Long print/merch page receives a second layered background treatment.
- Table previews include a miniature card/tray layout and distinct base, milestone and prestige structure.

## Design Lab
Accessible in the sidebar. This is an isolated in-site experimental area, not a separate deployment or Git branch. It deliberately does not write inventory, credits, rewards or normal room selections.
- Four table compositions per world: current baseline, museum vitrine, world window, collector's atelier.
- Four sleeve studies: crystal, gilded, moon garden, holographic.
- Three motion studies: calm, balanced, lively, with replay.
- Favourite table direction stored under a separate localStorage key. It is a preference for comparison, never automatic adoption.
- Experiments are intentionally bolder than the normal site; approved directions can be brought across later.

## Validation and limits
69 automated tests passed. An additional application smoke pass exercises Lab variants, sleeve/motion selection, preference saving and visitor profiles, checking that collection inventory is unchanged. These are DOM-stub checks, not real-browser visual verification. Supported browser tooling remains unavailable, so handling feel, viewport alignment and art composition still need user review.

The two art-reference folders are still pending. No claim that existing artwork is final. The requested phone redesign, illustrated-binder per-part recolouring and real decorative-sleeve unlock system remain deferred. Currency and commerce remain fictional.


---

# Original file: docs/EDITION_13_REVIEW.md

# Edition 13 — Two worlds at the table

## Scope
Only two new high-detail scene artworks: Discount Dungeon and Moonlit Menagerie. Both are Lab-only studies, not replacements for normal opening rooms. Current franchise art references are still pending.

## Detailed experiments
- Dungeon: warm candlelit leather desk, carved duck ornaments and a cavern lake/castle beyond.
- Moonlit: indigo velvet/silver terrace table, flowers and a moonlit hotel landscape.
- The illustrated table is in the foreground. A sample stack starts resting on it, lifts to eye level, then can be revealed and filed to the right. It uses five sample cards without changing ownership, currency or progression.
- Independent toggles for frame, extra props, glass, ambient lighting and particles. Four architectural treatments retained as compositional options.
- Save and restore a combination using a separate Lab preference key. It does not apply to normal rooms.
- Sleeve studies now live inside the card element, following its tilt and movement. Added gilded sheen, leaf glow and holographic material lighting, rather than edge decoration alone.
- Larger hands-on motion area with calm/balanced/lively sideways-bend presets. Drag, pause, reverse and release to compare. Keyboard/button alternatives for the sample sequence.

## Repairs
- Pointer gesture detection now uses actual pointer travel. Previously, boundary correction could falsely classify a stationary click as a drag. Pointer release explicitly handles a tap once and suppresses its duplicate synthetic click.
- Stack, completion message and action controls have explicit centred grid positions. Existing working drag rotation retained.
- Removing card protection now animates the sleeve sliding off. Reduced-motion preference bypasses it.
- Neighbour yielding increased to 85px maximum with a restrained six-degree lean, still dependent on proximity.

## Verification
The full automated suite includes a regression case that places the card outside the available boundary, then performs a stationary pointer down/up and asserts one reveal without filing. Hidden-card dragging, release filing and saved inventory are still checked. Lab actions test lifting, revealing, filing, reset, detail toggles and save without collection mutation.

Art assets were visually inspected independently. Full browser rendering and subjective motion feel remain unverified because supported browser-control tooling is unavailable. This release does not claim final placement or tactile quality is approved.

## User review
- Does the seated foreground table and eye-level lift establish the desired connection between world and cards?
- Does removing the glass panel give enough clarity with the richer scenery?
- Which combination of framing, props, light and atmosphere feels best?
- Is neighbour movement strong enough now, without the immediate slot-jumping from earlier versions?
- Check stationary click, drag, return and completion centering together in the normal opening screen.

Decorative sleeves are still Lab materials, not a real reward/unlock system. Normal protected cards use the existing clear sleeve.


---

# Original file: docs/EDITION_14_REVIEW.md

# Edition 14 — Repair and comparison pass

## Repairs
- One shared opening-controls renderer serves full page and local reveal updates. Reveal, Next and repeat purchase occupy the same first control slot. Secondary completion actions sit below it.
- Completion uses the same width and height as the card; controls are card-width, without an active-stage panel.
- Upper drag boundary reaches the progress-caption line. Side and lower bounds, original fluid drag rotations, hidden-card behaviour and release-only filing remain.
- Reordering previews the intervening items moving toward the held item's vacant slot, in either direction and across rows. Displacement grows on approach and reverses on retreat. Unrelated items remain stationary; order saves only on release.
- Lab manual pickup leaves the stack at eye level without revealing. First reveal is explicit, subsequent sample cards remain face-up.

## Lab
Only Dungeon and Moonlit scenes are affected. Cabinet adds posts, canopy and sill; desk adds a curved working surface and inset writing plate; classic uses a distinct framed presentation surface; open scene retains the landscape composition.
Twelve independently combinable, saveable layers: frame, foreground objects, glass, ambient light, motes, inlay, drapes, hanging lights, mist, stars, inscribed trim and display ledge. Selected controls have checkmarks and an enabled count. The previous toggle logic already merged options; the expanded tests verify simultaneous choices and persistence rather than assuming an unproven cause.
Approved attached sleeve materials and balanced default motion are preserved. No currency or collection mutation comes from experiments.

## Verification and limits
73 automated checks passed, including domain tests and a DOM-stub application flow. Added bidirectional and multirow vacancy tests; sample drag pickup, sample face-up continuation, concurrent detail toggles, and saved combination assertions. Existing stationary click, hidden drag, release filing, purchases and inventory preservation checks remain passing.
No supported browser QA tooling is available in this environment. These are not screenshot or real pointer rendering tests. Exact visual placement, layering and motion feel still need user review. Current Lab designs remain experiments, not approved final art. The separate reference folders and final mobile design remain pending.


---

# Original file: docs/EDITION_15_REVIEW.md

# Edition 15 — Interaction repairs and world frames

## Addressed feedback
1. Binder dragging swaps the held and targeted binder only. Intervening rows stay still. The progressive motion curve is preserved. Showcase insertion remains unchanged.
2–3. Reveal, Next and repeat-purchase controls are now absolutely anchored within a full-height stage, independent of card/back content. This supersedes the earlier grid-only repair.
4. Upper card travel increased by another 16 pixels; other boundaries retained.
5. Accurate opening-room previews remain a requirement for the final chosen scenes, deferred as requested.
6. Completion says “1 new card” and pluralizes other counts.
7. Lab stack uses the normal stage/back/card hierarchy and normal pull-slot renderer. After pickup: explicit first reveal, face-up continuation, bounded dragging, tray hit detection, release-only filing, rightward animated filing, Next, and reset. Hidden cards do not file. A receiver box sits below the pull panel. Normal collection state is untouched.
8–11. Rejected cabinet/desk/classic options removed. Open scene and Original table retained alongside world-specific carved/celestial portals and alcove/pavilion studies. Two-dimensional SVG architecture follows the existing illustrated scene. All twelve detail layers now have native checkboxes, checked-state feedback and incremental updates; changing one does not rebuild the controls. Open scene permits all layers. Fireflies and twinkling lights replace uniform dot patterns; trim/inlay/props perspective adjusted to the illustrated desk.
12. Stationary showcase pointer release explicitly opens card details, independent of a browser-generated click following prevented pointerdown. Dragging still reorders.

## Verification
76 automated checks passed (domain tests and DOM-stub interaction flow, not browser QA). New coverage: two-item binder swap across rows, unchanged unrelated slots, progressively animated swap offsets, stationary showcase tap, native checkbox multi-selection across architecture switches. Existing click/reveal, hidden drag, release-only filing, sample pickup, sample face-up continuation, save/restore, inventory and currency checks remain passing.
User screenshots were available and inspected, including the misplaced Reveal button. Supported browser automation is unavailable, so actual rendering, pointer feel, CSS compositing and visual quality are not certified by these tests.

## Still provisional
Architectural studies and the physical receiver are comparison concepts, not a final approved aesthetic. Final preview fidelity is deferred until the scene is chosen. Art reference folders and dedicated mobile redesign remain later phases. The supplied two scene paintings are retained; no new raster painting was needed for these structural variants.


---

# Original file: docs/PRODUCT_PLAN.md

# Astra Tessera: first prototype plan

Working title and visuals are temporary. This plan reconstructs the Nyx discussion retrieved on 9 October 2026; it does not claim a complete transcript.

## Confirmed vision
A digital-first collecting platform spanning multiple licensed franchises. Customers pull cards in affordable randomized digital packs and own the exact quantities pulled. Physical cards are optional: customers pay manufacturing and delivery, rather than a rarity markup. Only owned quantities may be printed. Batch orders, optional premium binders, artist recognition and fewer unwanted physical duplicates matter. Commercial art would come from paid artists, with distinct styles and officially allowed collaborations. The initial prototype is free; actual physical fulfillment is later scope. Content, economy, rules and UI must be easy to change. The user supervises visual direction. Additional product proposals are not approved business decisions.

## Product and experience
The first loop is browse a collection, inspect pack odds, open a pack, see each pull, review a saved binder and work toward missing cards. Ownership quantities must be visible; rarity must never imply an extra physical purchase fee. Browsing should connect collection and artist metadata. A future print flow needs a clear distinction between digital copies, printable entitlements, queued items and fulfilled items.

Prototype routes: discover collections; pack opening with individual reveal; binder with collection, rarity, artist, ownership and name filters; card details; artists; simulated print basket/history; workshop for configurable economy and content; a planning/readme screen. Persistent browser-local state with export/import. No real accounts, transactions, fulfillment or copyrighted franchise content.

## Collecting proposals for evaluation
All numerical defaults below are prototype choices, not user-approved rules.
- Five cards per pack; 100 demo credits; 1,000 starting credits and a free refill button.
- Common 70%, uncommon 23%, rare 6%, legendary 1% per ordinary slot.
- Every tenth pack without a rare-or-better guarantees rare-or-better in its final slot. A qualifying pull resets the counter. The guarantee's rare/legendary split follows their relative base weights.
- Optional duplicate protection redirects the first slot to an unowned card of its rolled rarity in that collection, if one exists. It does not alter rarity odds.
- Recycling converts only surplus, unprinted copies into fragments; at least one digital copy remains. Optional crafting lets fragments obtain a specific missing card. This is a completion mechanism to evaluate, not a finalized commercial economy.
- Physical simulation consumes one printable entitlement per owned copy, while preserving digital ownership. This is a conservative provisional interpretation: it prevents printing the same entitlement repeatedly. Real redemption semantics remain an open decision.
- No trading, cash-out, marketplace, blockchain, scarcity claims or purchases in this prototype. These are not implicit requirements.

## Economy and business viability
The user's target is packs roughly five times cheaper than physical packs, far below physical €5–8 prices. The demo uses credits, not a claimed feasible euro price. Scale and batching are hypotheses, not proof of margins. Before commercial launch, model licensing royalties/minimum guarantees, art fees, payments, VAT, hosting, support, refunds, fraud, moderation, printing/finishing, packaging, damaged delivery, shipping, warehousing and customer acquisition. Compare revenue against these costs at low/medium/high volume; do not assume a large audience will materialize. Rarity must not change the per-card print price for the same format/finish. Premium finishes or binders could carry actual product cost differences, to be approved separately.

## Architecture and modularity
Buildless ES modules. catalog.js contains independently identified artists, collections, cards and pack definitions; core.js handles pure transactional rules and validation; app.js renders and connects interactions; styles.css controls presentation. Tests call the core without a browser. Stable IDs protect saves when titles/art change. Removed cards remain archived when copies are owned or previously printed. A configurable workshop can add content, edit economy, disable collection sales and export the catalog. Deleting unowned content is separate from archiving owned content. No paid library/runtime is required.

Production evolution: authoritative server-owned inventory ledger; authentication; transaction idempotency; cryptographically secure server draws; versioned rule snapshots; durable database, migrations, backup/recovery; order reservation and fulfillment state machine; payment integration and abuse defenses; operational audit trail. Browser-local state is intentionally editable and is unsuitable for money or rare assets. A production account/backend and cross-device saves are outside this first slice.

## Licensing, legal and operations planning
Commercial use of third-party franchises requires licenses with approved territories, mediums, artwork and redemption rights. Artist agreements should specify compensation, attribution and digital/physical usage. Do not represent placeholder art as a real commission or collaboration. Before monetization, obtain jurisdiction-specific advice on randomized purchases, minors, consumer disclosures, refunds, digital rights and privacy; verify applicable law rather than treating this outline as advice. Publish honest odds and protection rules. No monetization is enabled now.

Operations need a supported printer and proofs, color/finish standards, minimum order quantities, shipping quotes, batch cutoffs, tracking, returns/defects policy, customer support, rights takedown handling and accessibility. The simulated print flow does not place orders or collect delivery details.

## Open decisions
Exact prices/pack sizes/rarities, duplicate and completion mechanisms, changing odds over time, card transferability, redemption semantics, publisher/artist terms, permitted visual style, commercial regions/age policy, supported print formats/binders and backend stack. Temporary choices can be replaced without making them approved policy.

## Completion checks for this slice
A user can open packs, inspect exact quantities, reload and retain the binder, filter content, recover a save through export/import, use optional completion mechanics, and simulate a print order without exceeding entitlements. Invalid imports must leave the existing save untouched. State-changing operations must be transactional; invalid inputs cannot charge credits or delete cards. Configuration/content changes must validate before use. Automated tests verify these behaviors. A private hosted build is the reviewable result; browser visual QA may be unavailable in this runtime.

## Edition 02: requested design iteration (10 October 2026)
The user requested effects on card opening, two fake 20-card collections, light absurd humour and a UI restyled using their preferences. Edition two initially used French text; edition three uses English following the user’s correction. Added Les Recrues du Chaos and Donjon Discount: original names, roles, flavour text and code-made vector portraits. These are collectible demo sets, without combat stats or gameplay rules. The interface uses readable bolder text, dark plum surfaces, purple accents, rounded controls and explicit dropdown arrows. Opening effects have skip/motion controls; system reduced-motion is respected, and synthesized sound is opt-in. No external creator’s character, identity or text is copied.

First-edition inventory is preserved through a versioned content migration. Old collections/cards are archived rather than deleted; custom content and economy settings remain. Tests cover migration and opening skip/double-click behavior. Browser layout/animation timing requires real browser verification when that capability is available.

## Previous collection experience (edition 03)
Chaos Crew and Discount Dungeon contain 20 original cards each, with English names and jokes referring to visible illustration details. Examples include RGB Toaster (bread tracing), Cardboard Carry (taped cardboard armour under a gaming headset), Flip-Flop Knight (helmet plus visible sandals), and Parking Paladin (a P-marked shield). Translation upgrades retain stable IDs and preserve deliberate custom text edits.

The binder home contains chosen franchise folders. Owned cards appear by default inside a folder, with an explicit missing-card toggle. Opening a pack or crafting a card adds its franchise folder; removing a folder hides it without deleting cards, print entitlements or history. Older saves infer folders from ownership until the user makes a folder selection.

Pack openings are interactive: click the pack or its button, then break the seal. Chaos has a purple neon theme; Dungeon has warm ember/gold effects. The results are saved before animation. Presentation sorting puts lower rarities first and rare/legendary pulls at the end, preserving the exact draw result and unchanged odds. The initial offset stack has a face-down top card and visible rarity-coloured edges. The first reveal click flips it; later clicks animate it into a tidy vertical right-hand column and reveal the next card. Multiple legendaries occupy the final slots. The final click files the last card. Skipping animations/results and system reduced-motion remain supported. This is presentation, not a new guarantee that every pack contains a rare.

## Current collection experience (edition 04)
Three original demo universes contain 60 cards in total. Orbital Oddjobs adds 20 sci-fi crew, robots, delivery hardware and oddities, with English visual jokes. Existing saves receive the new content without replacing customised titles, archived cards, paused collections, balances, quantities or economy rules.

Card frames differ by universe and rarity. Environmental SVG artwork and extra costume/prop details accompany faint artwork behind text. Discovery is an illustrated storefront, the binder a warm textured album, openings a dark collecting table, artists a gallery and printing a proof studio. These are original demo universes, not third-party franchise implementations.

Openings have brief manual interactions: slide/tear a foil seal, strike three chest seals, or enter a five-arrow delivery code. Autoplay (button, S or Escape) performs the input sequence and runs the same animation. The first two openings in each universe play at full pace; the third offers normal or 1.6× speed. The choice is saved locally and can be changed in Workshop. Motion reduction still bypasses animation.

Filed cards remain in stable right-column slots. Advancing animates the top card and inserts one new arrival without rebuilding the rail or replaying previous arrivals. The advance label is Next. Lower rarities precede higher rarities, with equal-rarity draw order retained. Presentation does not change the pack distribution or guarantees.

Checks cover accounting, all migrations, opening commands/preferences, sequential reveals, retained rail nodes and app workflows using DOM stubs. Art samples were inspected from an SVG rendering. Real browser layout, touch interaction and animation timing still need browser verification when that capability is available.


## Edition 05 implementation update
Astra Tessera is the chosen name. The prototype now includes illustrated discovery, franchise catalogs and binder shelves, custom covers and spacing, local collector profiles/showcases, fictional social activity, protected bulk recycling, saved pack boxes, gesture-based reveals, and simulated shared parcels for prints and merchandise. Generated premium concept portraits supplement the existing vector demo catalog. Artist studio names and community identities are fictional; commercial artist credits and IP partnerships remain future integrations.

All balances and ownership still live in the browser. Export/import carries the catalog, inventory, print reservations, preferences, cosmetic unlocks, local social data, paid pack queue and reveal position. This is not a production ownership ledger or a real store.


## Edition06 review batch
The collecting interface now includes full-catalog paintings, dedicated pack illustrations, distinct collector-room art, free six-part binder colours, collectible binder structures, direct pack/card manipulation, automatic batch sequencing, correct franchise purchase ordering, context-preserving artist navigation and modal showcase selection. Local profiles can display favourite-game tags and a manually added Steam profile link. Studio news is editorial prototype content; no live news service or account linking is connected.


## Edition 07 checkpoint

Five original universes, 100 cards. Clockwork Couriers and Moonlit Menagerie join the existing three with new visual concepts, rituals and covers. The current feedback ledger is docs/EDITION_07_BRIEF.md. Functional completion and visual approval are distinct: purpose-made concepts and refined geometry are implemented, while final art direction and browser-measured motion remain unapproved. The live application remains a local prototype, not a payment or social backend.

## Edition 08 checkpoint
Actual-page appearance previews, a showcase-first lounge, visual game favourites, local guestbook, drag ordering, dimensional pack/box planes, sticky navigation and five purpose-composed opening worlds. Discovery leads with the two new universes. Clockwork and Moonlit rituals are now distinct mechanisms. See EDITION_08_BRIEF.md for coverage and explicit production/verification limits.


<!-- END HISTORICAL_PROJECT_DOCUMENTS.md -->