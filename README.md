vn-stock-ai-trading/
├── .claude/
│   └── skills/
│       ├── vn-analyze/       # Flagship: phân tích toàn diện
│       ├── vn-technical/     # Kỹ thuật via TradingView
│       ├── vn-fundamental/   # Cơ bản via vnstock
│       ├── vn-market/        # Tổng quan thị trường
│       └── vn-report/        # Xuất báo cáo HTML
├── vendor/
│   └── vnstock-agent/           # Source vnstock-agent (MIT, mrgoonie) — vendored
├── config/
│   └── claude-desktop-config-template.json   # Template cấu hình MCP
├── scripts/
│   ├── setup-mcps.sh          # Cài đặt tự động (macOS/Linux)
│   ├── launch-tv-msix.ps1     # Khởi động TV bản Store (Windows Admin)
│   └── launch_tv_debug.bat    # Khởi động TV bản .exe (Windows)
└── README.md
