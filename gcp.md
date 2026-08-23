# Google Cloud — secretary habits

**Default secret:** `REI_GCP_CREDENTIALS_CONFIG` (base64 service-account JSON).
The env **name** still says REI — that is the live secret. Do not prefer
`SHEETS_MCP_CREDENTIALS_CONFIG` (deprecated).

- SA email: `rei-kessler-sa-1@rei-sa-20260721.iam.gserviceaccount.com`
- GCP project: `rei-sa-20260721` (numeric `574173090707`)
- Use `google-api-python-client` / `google-auth` (baked by Cloud install)

Sheets / Drive / Calendar / Docs → this SA first. Never commit the raw JSON.

Personal Bryan Google OAuth (BRY-155) is separate — this SA is not Bryan’s
user login.

## Live rule

`.cursor/rules/bryanverse/rei-gcp-credentials-default.mdc`
(filename kept so existing pointers and muscle memory don’t break; content
is secretary-only).
