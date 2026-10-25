---
name: QuralGate
description: An inherited working cabinet for synthetic typed requests, exact diagnostics and separate manual decisions and results.
colors:
  primary: "#126653"
  primary-hover: "#0b5343"
  navy: "#183e60"
  ink: "#172e45"
  page: "#edf3f8"
  surface: "#ffffff"
  line: "#b9cbd9"
  navigation-surface: "#dce9f3"
  muted: "#46627a"
  input-stroke: "#7894aa"
  link: "#174e7e"
  pending: "#795200"
  error: "#942721"
  error-surface: "#fff0ee"
  focus: "#bd671a"
  selection-surface: "#b7ded2"
  selection-ink: "#132f29"
typography:
  primary-heading:
    fontFamily: 'system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: "2rem"
    lineHeight: 1.15
    letterSpacing: "-0.025em"
  section-heading:
    fontSize: "1.3rem"
  brand:
    fontSize: "1.4rem"
    fontWeight: 740
  body:
    fontFamily: 'system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
  label:
    fontWeight: 600
  supporting:
    fontSize: "0.9rem"
  exact-json:
    fontSize: "0.85rem"
rounded:
  control: "7px"
  panel: "12px"
spacing:
  evidence-gap: "0.4rem"
  inline-gap: "0.5rem"
  action-gap: "0.6rem"
  control-inset: "0.7rem"
  unit: "1rem"
  page-inline: "1.25rem"
  panel-inset: "1.4rem"
  section: "2rem"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    rounded: "{rounded.control}"
    padding: "0.65rem 1rem"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.navy}"
    rounded: "{rounded.control}"
    padding: "0.65rem 1rem"
  button-default:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.surface}"
    rounded: "{rounded.control}"
    padding: "0.65rem 1rem"
  field:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "{spacing.control-inset}"
    width: "100%"
  panel:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.panel}"
    padding: "{spacing.panel-inset}"
  navigation-current:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.navy}"
    rounded: "{rounded.control}"
    padding: "0.65rem 1rem"
  exact-schema-disclosure:
    padding: "0.7rem 0"
---

# Design System: QuralGate

## Overview

**Creative North Star: "The Shared Work Cabinet"**

QuralGate extends the documented TerimLine / SynaRoute Operate cabinet. It keeps the navy identity and navigation, pale blue workspace, white labelled forms, green explicit actions, system typography, and native controls. The incumbent system remains the visual authority; this is an original bounded reference10 Vapi direction expressed as a synthetic typed-contract workspace.

Its character is direct, flat, and readable. Request identity, frozen version, owner and current state lead; exact saved arguments, the historical creation diagnostic, independent decision and single manual result remain separate. The signature is strict visible refusal without coercion and a native disclosure of the saved input/output contract.

**Key Characteristics:**

- Inherited navy navigation and pale blue workspace.
- Green labelled submit actions and white bordered native forms.
- System typography with a fixed-size task heading.
- Exact raw JSON and individually named diagnostic errors.
- Separate current status, historical creation check, independent decision and owner result.
- Wrapping authored RU/KK text, timestamps and publication digests; native exact-schema disclosure.

## Colors

The cool inherited palette uses navy for orientation and Working Green for explicit actions. The frontmatter owns implemented values. Sidecar tonal strips are inherited derived inspection metadata, not additional interface colors.

### Primary

- **Working Green** (`primary`, `primary-hover`): native submits and explicitly primary actions, including publication, saving a synthetic request, either review decision and saving a manual result. The inherited status utility shares this green.

### Secondary

- **Cabinet Navy** (`navy`): header, baseline filled buttons, navigation text and secondary-control borders.
- **Link Blue** (`link`): links and field carets.

### Tertiary

- **Pending Amber** (`pending`): retained inherited pending utility; request-state headings are textual and do not rely on this color.
- **Error Red / Pale Error** (`error`, `error-surface`): refused-action notices; saved argument diagnostics remain individually readable text on the page ground.
- **Focus Amber** (`focus`): visible keyboard focus.
- **Soft Selection Green / Selection Ink** (`selection-surface`, `selection-ink`): native text selection.

### Neutral

- **Cabinet Ink** (`ink`): root text and status headings.
- **Cool Workspace** (`page`): page ground and scrollbar track.
- **White Surface** (`surface`): native fields, form panels, ordinary notices and current navigation.
- **Divider Blue** (`line`): containers, tables and evidence dividers.
- **Navigation Mist** (`navigation-surface`): navigation strip and table headings.
- **Supporting Slate** (`muted`): boundary statements, helper copy, digest and footer.
- **Field Slate** (`input-stroke`): field borders and scrollbar thumb.

**The Inherited Shell Rule.** Extend the current TerimLine / SynaRoute cabinet instead of replacing its palette, typography, or navigation grammar.

## Typography

The recorded system stack serves task headings, body and controls. No webfont is loaded. A fixed-size main heading, smaller section headings and heavier brand establish hierarchy. Unspecified body size, heading weights and line heights retain browser defaults. Exact JSON uses the browser's native preformatted face at the recorded smaller size; it is not a new display face.

Paragraphs have maximum measure (72ch) and line height (1.6). Labels and buttons use weight (600). Authored descriptions preserve line breaks; preformatted JSON preserves whitespace and wraps anywhere. Tables retain tabular numerals. Status is an explicit heading, followed by the model kind; color alone does not communicate the decision.

The document uses `lang="ru"`. Contract editors mark `descriptionRu` and `descriptionKk` controls as `ru` and `kk`. `contractView` and request detail put each saved description in a separate authored paragraph with its language attribute. Russian UI labels, field names, required/optional suffixes, types and bounds remain interface text. Authored content is neither language-detected nor translated.

**The Authored Language Rule.** Keep authored RU/KK descriptions in their own language nodes; labels, type names, diagnostics and status copy remain Russian interface text.

## Layout

Header and navigation share inline padding (`max(1.25rem, calc((100% - 1160px) / 2))`). Main is centered with maximum width (1200px), padding (`2rem 1.25rem`) and minimum height (75vh). Header uses a spaced flex row; navigation has the recorded inline gap. The retained optional work grid uses columns (`minmax(0, 1fr) minmax(260px, 0.8fr)`); paired rows use equal columns. QuralGate request detail itself follows a vertical reading order, with white panels only for available forms.

At the stacked breakpoint (700px and below), retained grids stack, main padding becomes (`1.4rem 1rem`), panel padding becomes (1rem), and navigation wraps with padding (0.6rem). Header identity aligns to the top with size (0.8rem) and maximum width (140px). At the narrow table/search breakpoint (600px and below), search tools stack, navigation buttons use `flex: auto`, and table cells receive minimum width (140px). A focusable labelled table wrapper owns horizontal scrolling and has a narrow-screen hint.

Action rows wrap. Headings, identity, evidence, disclosures and footer allow long text to wrap. Direct screen paragraphs and diagnostic list items explicitly wrap anywhere; preformatted JSON does too. Evidence has a top divider, unit top margin/padding and the recorded evidence gap. The exact-schema disclosure follows the request, diagnostic, review/result evidence and synthetic boundary copy; the publication digest and return action follow outside it.

The supplied six-file packet is recorded in `docs/finish-review.json`: completed request at 1440, 1280 and 390px; denied request at 1440 and 390px; pending independent-review form at actual width 1113px. The completed and denied narrow captures show navigation reflow and wrapping arguments, evidence and digest. The review form is not a 1280px capture. This documentation uses the already-opened builder/reviewer packet and inspected source; it did not rerun browser interactions. The `ship` verdict covers those supplied states and source, not every form/state/width, complete mobile/touch coverage, a screen-reader audit, backend correctness or security.

## Elevation & Depth

No box shadow, backdrop effect, transition or animation is defined. White panels, pale fills, one-pixel borders and whitespace separate regions. Hover changes brightness and primary fill without motion. Replacing screen content and focusing a task or preview heading provides continuity without animation. No decorative raster is used; supplied screenshots are evidence assets whose origin and filenames are recorded in `docs/capture-provenance.json`. The six-file review packet is independently enumerated in `docs/finish-review.json`.

## Shapes

Controls and notices use the smaller recorded radius; panels and table wrappers use the larger one. Borders are one pixel. Textareas start at height (100px) and resize vertically. Buttons and native disclosure summaries have minimum height (44px). The native disclosure marker remains visible. The flat contract field lists use ordinary unordered-list markers and padding (1.5rem). Retained fieldset styles do not define the request-detail composition.

## Components

### Buttons

Native labelled actions use padding (`0.65rem 1rem`) and recorded label weight. Explicit primary and all submit buttons use Working Green with white text; hover combines the deeper primary fill with brightness (1.13). Both independent review submits share this primary treatment and retain distinct written labels. Secondary refresh, return, archive and settings actions use white with navy text and border. The retained baseline button rule is navy filled. Disabled buttons use opacity (0.55) and `cursor: not-allowed`. Focus-visible is an amber outline (3px) with offset (3px); narrow buttons have maximum width (100%). The initiating button is disabled while its request runs.

### Cards / Containers

Flat white form panels use a Divider Blue border, the panel radius and recorded inset, reduced at the stacked breakpoint. Login is capped at width (480px). Request metadata, saved JSON, diagnostics, recorded reviewer/result and exact schema remain on the page ground. Preview evidence follows its form rather than opening a modal or a second execution workspace.

### Inputs / Fields

Native inputs, selects and textareas use White Surface, Cabinet Ink, Field Slate borders and Link Blue carets. Every generated field has a connected label and ID. Archived or role-protected editors retain values through native read-only fields or disabled selectors. Integer editors use native number inputs with step (1), and source-supplied `min`/`max`; configured length bounds use `maxLength`. In the field editor, both labels and controls for `min`/`max` are visible only for `integer`, and `maxLength` only for `text`. Boolean fields show neither bound group. The `[hidden]` rule fully hides those conditional controls.

Contract description editors carry explicit RU/KK language attributes. Request arguments and manual-result JSON use required, labelled textareas with spellcheck disabled. Required textareas also collect the independent decision reason and manual-result reason. Native form submission and submitter values distinguish the two review actions. Failed requests retain the form and focus the shared polite status notice; these are source-supported semantics, not interaction tests rerun by this documentation pass.

### Navigation and Notices

The linked brand and current user/role lead the navy header. Inactive section controls are transparent on the pale strip; the current collection is white bordered with `aria-current="page"`. The initial collection is the requests collection (`calls`). The skip link becomes visible on focus. Task/detail changes focus the leading heading using `tabindex="-1"`; successful previews focus their result heading. The shared notice has `role="status"`, `aria-live="polite"` and a programmatic focus target. Empty notices are hidden. Refused-action notices use Pale Error and Error Red; normal notices use White Surface.

### Contract Publication and Request Preview

Publication preview uses a labelled contract selector and **Проверить контракт**, then displays code/version, title, model kind, both authored descriptions and separate input/output field lists. Each field states type, required/optional status and applicable bounds. **Опубликовать эту версию** follows that evidence. Selector changes clear the preview and a generation guard ignores obsolete responses.

The request form uses a labelled publication selector, **JSON аргументов** and **Проверить аргументы**. Preview displays the frozen contract identity and exact diagnostic before **Сохранить этот синтетический запрос**. Editing either publication or arguments clears the old preview; the generation guard prevents a stale response being presented as current. Preview is a visible check, not an external tool execution or a reservation.

### Saved Request and Historical Diagnostic

Request detail leads with code, publication version, owner, server timestamp and the current request status, followed by model kind and exact authored descriptions. **Сохранённые аргументы** shows the unchanged original JSON. A separate evidence section is explicitly titled **Первичная проверка при создании**; it contains the saved initial status, either schema correspondence or individually named errors, and the initial reason. This historical status can remain **Нужно независимое решение** after the current request becomes **Ручной результат сохранён**. **Обновить запрос** follows the check.

The denied captures retain `qty` as a string and an extra field while naming both integer-type and unknown-field refusal. The display never normalizes the saved JSON. Error names cover required/type/range/text-length failures, duplicate or unknown keys, non-flat values, malformed JSON and JSON length. This documents the source mapping and supplied refusal pixels, not a new backend validation audit.

**The Historical Check Rule.** Show the current request status first and label the saved creation diagnostic as historical; a past needs-review check must never impersonate the current completed state.

### Independent Review and Owner Result

A pending, unarchived request renders **Решение для этой версии** only for an administrator whose name differs from the owner. Its required **Основание решения** textarea precedes distinct submit buttons **Разрешить модель** and **Отклонить модель**. Other viewers receive the other-administrator explanation. Once recorded, **Независимое решение** shows the saved status, reviewer, server time and reason beside the request evidence. The supplied review capture shows the pending form, not independent proof of a publication-archive transition.

An allowed, unarchived request renders **Ручной синтетический результат** only for the original owner. It explains the synthetic boundary, supplies a required **JSON результата** textarea initially derived from required output fields, a required **Основание ручной отметки** textarea, and **Сохранить ручной результат**. Integer defaults use the saved minimum, booleans use false and text uses SYN. Another user sees the owner-only explanation, including that an administrator cannot bypass it. A saved result replaces the form with **Сохранённый ручной результат**, author/time, unchanged result JSON and note. These are UI source conditions; the documentation does not claim an independent authorization or concurrency test.

**The Separate Authority Rule.** Keep the independent administrator decision and the original owner’s single manual result as separate labelled forms and saved evidence.

### Exact Historical Schema

**Точная схема этого запроса** is a native disclosure, closed by default in source and expanded in the completed captures. It displays the request's saved code/version, title, model kind, both exact authored descriptions, separate input/output field lists and their applicable type/required/bound text. The publication SHA256 follows outside it. The exact schema remains available for denied and completed requests as well as pending review. The digest is inspectable evidence, not a signature or security guarantee.

**The Frozen Schema Rule.** Keep the request tied to its displayed publication version and exact input/output disclosure; later draft edits must not visually replace that saved evidence.

### Tables and Data Disclosure

Native record tables use collapsed borders, left/top aligned cells, padding (0.9rem), wrapping values, maximum cell width (28ch) and pale headings. Headers have column scope; each row has a labelled open action. The last row removes its bottom divider. Search and the archive checkbox retain native labels; an empty result has explanatory text.

The inherited data/access surface uses native account fields, labelled download/journal actions, an ordinary native disclosure for recent-event JSON, and a file input followed by an explicit restore-confirmation panel. Its copy states the shared workspace and unsigned-copy boundary. Those source-visible controls do not establish account recovery, tenant isolation, security certification or a complete settings review. The result and footer preserve the explicit synthetic-only boundary throughout.

## Do's and Don'ts

### Do:

- **Do** inherit the navy header, pale workspace, white form surfaces and green primary action.
- **Do** keep connected labels, native controls, native disclosure markers and visible focus.
- **Do** preserve authored RU/KK descriptions within Russian interface copy.
- **Do** keep raw arguments intact and identify each strict type or unknown-field error in text.
- **Do** distinguish the current status from the historical creation check, independent review and manual result.
- **Do** allow long descriptions, timestamps, exact JSON and SHA256 digests to wrap.
- **Do** keep the saved version and exact schema beside the synthetic request evidence.

### Don't:

- **Don't** replace the inherited cabinet with a new visual identity, ornamental assets or animation.
- **Don't** hide field labels or show integer bounds for a text/boolean field or text length for a number/boolean field.
- **Don't** merge the author and independent reviewer roles into one approval control.
- **Don't** substitute current drafts for the saved publication or diagnostic.
- **Don't** imply a Vapi integration, real tool call, voice, LLM, external write or delivered operation.
- **Don't** present a manual result as proof of execution, access, delivery or data truth.
- **Don't** present the displayed SHA256 digest as a signature or security certification.
