# Deployment Guide

## GitHub Pages Setup

1. Create a public repository on GitHub
2. Push the code to the repository
3. Go to repository **Settings** → **Pages**
4. **Source**: Select `Deploy from a branch`
5. **Branch**: Select `main`, folder: `/ (root)`
6. Click **Save**
7. Wait for deployment (2-3 minutes)

## Usage

Dashboard requires authentication via query parameter.
Contact the administrator for access credentials.

## Notion Embedding

1. In Notion page: `/embed`
2. Paste the dashboard URL (with authentication)
3. Press Enter

Dashboard automatically adapts to Notion's dark/light mode.

## Security

- Encrypted endpoint
- Authentication required
- No sensitive data in repository
