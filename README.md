# Krishna Sanjay Vaddi — Portfolio

A fast, accessible static portfolio for machine learning engineer and data scientist Krishna Sanjay Vaddi.

**Live site:** [krishnasanjay21.github.io/portfolio](https://krishnasanjay21.github.io/portfolio/)

## What the site highlights

- Edge computer vision and TensorRT validation
- LLM-powered analytics products with working demos
- Forecasting, causal inference, and statistical modeling
- Professional experience and education
- Peer-reviewed publications with publisher links

## Featured live projects

- [TaxiBot](https://taxibot-3bq2vahloszdn7mbrjkh8u.streamlit.app/) — natural-language-to-SQL business-intelligence copilot
- [ShopGenie-E](https://shopgenie-38esar44rpqhmaz9r3it3b.streamlit.app/) — multi-agent product research, requirements scoring, and comparison dashboard
- [DataLens](https://datalens-x4seve4uqecrujmqwmzoth.streamlit.app/) — zero-configuration exploratory data analysis

Each featured project links to its public source code. The homicide-clearance project also links directly to its formal report.

Every featured card includes an expandable architecture breakdown covering data flow, model or analysis components, validation, outputs, and deployment boundaries.

The portfolio also includes dedicated, evidence-based case studies for the YOLOv11 TensorRT audit suite, TaxiBot, and ShopGenie-E, plus a downloadable ML Engineer résumé.

## Local development

No build step is required.

```bash
python -m http.server 4173
```

Then open `http://localhost:4173`.

## Structure

```text
portfolio/
├── index.html
├── krishna_vaddi.webp
├── sitemap.xml
├── projects/
│   ├── yolov11-int8.html
│   ├── taxibot.html
│   └── shopgenie.html
└── assets/
    ├── css/custom.css
    ├── documents/
    ├── images/
    └── js/main.js
```

## Accessibility and performance

- Responsive navigation with keyboard and Escape-key support
- Visible focus styles and a skip link
- Reduced-motion support
- Accessible project-filter state
- Persistent light/dark theme preference
- Semantic headings, landmarks, and descriptive external-link labels
- Optimized WebP portrait

## Contact

- [LinkedIn](https://www.linkedin.com/in/krishna-sanjay-vaddi)
- [GitHub](https://github.com/KrishnaSanjay21)
- [Email](mailto:krishnasanjayvaddi2@gmail.com)
