# Examples

This folder contains working examples of Artifct Capsules.

---

## Files

* `example.cap`
  A basic standalone capsule

* `example_artifact.html`
  A browser-viewable artifact

* `root_example.cap`
  Root of a lineage

* `branch_example.cap`
  Derived capsule referencing the root

* `archive/`
  Generated lineage explorer

---

## Try it instantly

### 1. Open artifact

Open in your browser:

* `example_artifact.html`

No setup required.

---

### 2. Verify capsule

```bash
python ../cli/capsule.py verify example.cap
```

---

### 3. Explore lineage

```bash
python ../explorer/capsule_lineage_explorer.py .
```

Then open:

* `archive/index.html`
* `archive/lineage.html`

---

## What this demonstrates

These examples show:

* self-verifying artifacts
* offline cryptographic verification
* authorship and identity
* lineage (parent → child relationships)

---

## Why this matters

Most files can be copied and altered without context.

Capsules preserve:

* origin
* integrity
* continuity

They do not depend on external systems to prove validity.
