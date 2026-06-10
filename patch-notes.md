# TSBCPlay Manifest Patch Notes

## Verification + Repair Manifest

- Added dynamic games manifest format.
- Added SSIA Vanguard Chronicles as `ssiavc`.
- Added `repairUrl` for repair downloads.
- Added `repairSha256` field for optional repair package verification.
- Added `files` array for optional per-file verification.
- Current SHA-256 fields are blank for first testing.

## Notes

When SHA-256 is blank, TSBCPlay will still verify that the required files exist.
For stronger verification, calculate the SHA-256 hash of each file and paste it into the related `sha256` fields.
