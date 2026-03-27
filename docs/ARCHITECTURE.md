# Architecture

## Capsule Structure

* payload (base64)
* payload_sha256
* capsule_id
* author
* created_at
* parent_id (optional)
* public_key_pem
* signature
* signature_over

---

## Verification Flow

1. Decode payload
2. Recompute SHA-256
3. Recompute capsule ID
4. Validate signed fields
5. Verify signature using public key

---

## Properties

* deterministic
* offline-verifiable
* self-contained
* lineage-aware
