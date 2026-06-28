# Native Source

The initial source snapshot was copied from `db/postgres.rs` in the desktop app.

Source SHA-256: `a1ef241ff26bbc84d50bc0888c01c280d09f4f058cb05a27f2dc974bd5adf7d9`.


This directory is a migration staging area for `irodori.questdb`. The active native
ABI shim lives in `src/lib.rs`; engine-specific connect/query/metadata behavior
should move here as the connector runtime contract is wired into the desktop app.

Engine status from `knowledge/engines.json`: `wired`.
