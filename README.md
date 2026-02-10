# Optics Lab — Motion Induced Blindness Experiment

A web-based experiment demonstrating **Motion Induced Blindness**, an optical illusion where stationary visual stimuli disappear when surrounded by moving patterns.

## 🔗 Live Link

**Access the experiment here:** [https://Soumik969.github.io/optics_lab/](https://Soumik969.github.io/optics_lab/)

## How It Works

The experiment page is split into two panels:

- **Left panel** — A Google Form for participant responses and data collection.
- **Right panel** — An interactive Motion Induced Blindness demonstration (from [michaelbach.de](https://michaelbach.de/ot/mot-mib/index.html)).

## Deployment

This project is automatically deployed to **GitHub Pages** via the workflow in `.github/workflows/static.yml`. Any push to the `main` branch triggers a new deployment.

### First-Time Setup (Required)

Before the workflow can deploy, you **must** configure two settings in your repository:

#### Step 1 — Enable GitHub Pages

1. Go to **Settings** → **Pages**
2. Under **Build and deployment** → **Source**, select **GitHub Actions**

#### Step 2 — Grant workflow permissions

1. Go to **Settings** → **Actions** → **General**
2. Scroll down to **Workflow permissions**
3. Select **Read and write permissions**
4. Click **Save**

#### Step 3 — Trigger a deployment

Push a commit to `main` or go to **Actions** → **Deploy static content to Pages** → **Run workflow** to trigger the first deployment.

### Troubleshooting

| Error | Fix |
|---|---|
| `Get Pages site failed. Error: Not Found` | Complete **Step 1** above — Pages is not enabled |
| `Resource not accessible by integration` | Complete **Step 2** above — workflow doesn't have write permissions |
