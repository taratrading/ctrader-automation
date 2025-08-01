https://github.com/taratrading/ctrader-automation
# cTrader Algorithmic Trading Framework

[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue)](https://python.org)
[![Flask](https://img.shields.io/badge/flask-2.3%2B-lightgrey)](https://flask.palletsprojects.com)
[![cTrader API](https://img.shields.io/badge/ctrader%20api-v3-green)](https://connect.spotware.com/docs/ctrader/open-api)
[![License: MIT](https://img.shields.io/badge/license-MIT-purple)](LICENSE)

Professional-grade algorithmic trading framework for cTrader platform using Spotware Open API

```bash
├── README.md                 # Project documentation (you are here)
├── LICENSE                   # MIT License
├── requirements.txt          # Python dependencies
├── .gitignore                # Standard Python gitignore
├── src/
│   ├── main.py               # Main application entrypoint
│   ├── auth.py               # OAuth2 authentication module
│   ├── api_client.py         # cTrader API wrapper
│   ├── webhook_handler.py    # Webhook processing logic
│   ├── strategies/           # Trading algorithms
│   │   ├── mean_reversion.py
│   │   └── trend_following.py
│   └── utils/
│       ├── config_loader.py  # Environment configuration
│       └── logger.py         # Logging setup
├── tests/                    # Unit and integration tests
│   ├── test_api_client.py
│   └── test_webhooks.py
└── samples/                  # Usage examples
    ├── docker-compose.yml    # Production deployment
    └── ngrok_setup.md        # Local testing guide
