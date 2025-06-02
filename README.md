# Grafana Dashboards

A collection of Grafana dashboards for monitoring and observability.

## 📊 Available Dashboards

| Dashboard | Description | Grafana Labs | Documentation |
|-----------|-------------|--------------|---------------|
| [HLF SmartBFT](./dashboards/hlf-smartbft/) | Hyperledger Fabric SmartBFT consensus monitoring | [TBD] | [📖 Docs](./dashboards/hlf-smartbft/README.md) |

## 🚀 Quick Start

### Import from Grafana Labs
1. Go to [Grafana Labs Dashboards](https://grafana.com/grafana/dashboards/)
2. Search for the dashboard name
3. Copy dashboard ID and import in your Grafana instance

### Import from Repository
1. Navigate to the dashboard folder
2. Download the `dashboard.json` file
3. Open Grafana → Dashboards → Import
4. Upload the JSON file or paste the content
5. Select your data source and configure variables

## 📋 General Requirements

### Data Sources
- **Prometheus**: Required for most dashboards
- Ensure your monitoring stack scrapes the necessary metrics


## 📁 Repository Structure

```
grafana-dashboards/
├── README.md                    # This file
├── LICENSE                      # Apache 2.0 License
└── dashboards/                  # Dashboard collection

```

## 🤝 Contributing

We welcome contributions! Please follow these guidelines:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/new-dashboard
   ```
3. **Add your dashboard**
    - Create a new folder in `dashboards/`
    - Include `dashboard.json` and `README.md`
    - Add screenshots in `screenshots/` subfolder
4. **Update main README** (add entry to the table above)
5. **Submit a pull request**

### Dashboard Guidelines
- Use descriptive panel titles and descriptions
- Follow consistent naming conventions
- Include template variables for filtering
- Test with different data sources
- Provide comprehensive documentation
- Include screenshots showing key features

### File Naming
- Dashboard files: `dashboard.json`
- Documentation: `README.md`
- Screenshots: `overview.png`, `details.png`, etc.


## 📝 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.


---

**Maintained by:** ATME

**Last Updated:** 02.06.2025