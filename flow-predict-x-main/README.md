# TrafficIQ

TrafficIQ is a smart city traffic intelligence dashboard built with TanStack Start, React, TypeScript, and Tailwind CSS. It simulates a traffic operations center with live KPIs, model outputs, traffic analytics, scenario prediction, model comparison, dataset inspection, feature engineering, recommendations, reporting, and system settings.

## What This Project Does

- Shows a command-center style dashboard for monitoring congestion, model health, and live predictions.
- Lets you run what-if traffic forecasts from an input form and view predicted volume, delay, confidence, and recommendations.
- Compares multiple machine learning models and highlights XGBoost as the selected production model.
- Explains the dataset, engineered features, and model inputs used by the system.
- Surfaces operational recommendations, reports, and configuration controls for the traffic platform.

## Main Pages

- Dashboard: live KPIs, actual vs predicted traffic, weekly traffic, heatmap, live corridor status, and recent predictions.
- Analytics: hourly, weekly, monthly, congestion distribution, model accuracy, and feature importance views.
- Live Prediction: interactive inference studio with scenario inputs and AI recommendation output.
- ML Models: trained model registry with training time, validation score, hyperparameters, and training pipeline.
- Model Comparison: side-by-side benchmark of the candidate models.
- Dataset Explorer: dataset summary, feature distribution, correlation matrix, and sample rows.
- Feature Engineering: engineered feature breakdown with importance and explanation.
- Recommendations: suggested operational actions with severity and impact.
- Reports: downloadable report catalog.
- Settings: toggles and controls for inference, alerts, and feature-store behavior.

## Tech Stack

- TanStack Start and TanStack Router
- React 19 and TypeScript
- Tailwind CSS v4
- Recharts for charts
- Framer Motion for animation
- Radix UI primitives and Lucide icons

## Local Development

```sh
npm i
npm run dev
```

## Attribution

Created and maintained by Reva Pande.
