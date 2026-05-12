platform/
│
├── apps/
│   ├── web/                  # Customer frontend (Next.js)
│   ├── admin/                # Admin dashboard
│   └── api/                  # Backend service
│
├── packages/
│   ├── ui/                   # Shared UI components
│   ├── types/                # Shared TypeScript types
│   ├── config/               # Shared configs
│   ├── utils/                # Utility functions
│   └── eslint-config/        # Shared lint config
│
├── infrastructure/
│   ├── docker/
│   ├── nginx/
│   ├── terraform/
│   └── kubernetes/
│
├── docs/
│   ├── architecture/
│   ├── api/
│   └── database/
│
├── scripts/
│
├── .github/
│   ├── workflows/
│   ├── ISSUE_TEMPLATE/
│   └── pull_request_template.md
│
├── package.json
├── turbo.json
├── pnpm-workspace.yaml
├── README.md
└── .env.example


# Note
## Use pnpm first  
## Raise pr like this

  Example:
  
        feat(frontend): add login page UI
        fix(backend): resolve JWT validation issue