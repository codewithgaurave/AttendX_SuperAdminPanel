# AttendanceX - SuperAdmin Portal

SuperAdmin portal for managing admins and their accounts.

## Features
- Admin management (create, edit, deactivate)
- Demo/Paid account filtering
- Demo days tracking
- Renewal request management
- Help & Contact with Master Admin
- Account overview and statistics

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deployment
This app should be deployed to `superadmin.attendx.com` subdomain.

## Role Access
- Only SuperAdmin role users can access this portal
- Redirects to login if unauthorized