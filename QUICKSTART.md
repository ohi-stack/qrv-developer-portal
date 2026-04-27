# QR-V Developer Quickstart

## Base URL
`https://api.qrv.network`

## Verify a Record
`GET /api/v1/verify/{qrvid}`

Example:
`GET /api/v1/verify/QRV-CERT-000001`

## Create a Record
`POST /api/v1/registry/create`

## Expected Statuses
- VERIFIED
- REVOKED
- EXPIRED
- NOT_FOUND
- INVALID_SIGNATURE
- ERROR
