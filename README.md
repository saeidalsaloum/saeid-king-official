# Saeid KING Official Website

Official static website for the Saeid KING Arabic media channel.

## Purpose

This repository contains the public GitHub Pages-ready website for a calm, professional, Arabic-first brand presence. The site introduces the channel, provides a serious collaboration page, and publishes a short privacy note for visitors.

## Public contact

Use the official channel email only: [saeidkingofficial@gmail.com](mailto:saeidkingofficial@gmail.com).

## Site principles

- Static HTML, CSS, and SVG assets served from the repository root.
- Arabic pages use `lang="ar"` and `dir="rtl"`.
- No forms, tracking, cookies, analytics, external scripts, remote fonts, or third-party embeds.
- No phone numbers, private personal data, legal case material, or sensitive administration content.
- No fake sponsor logos, testimonials, press mentions, video links, audience metrics, or unverifiable claims.

## Required public files

- `index.html`
- `media-kit.html`
- `privacy.html`
- `404.html`
- `robots.txt`
- `sitemap.xml`
- `assets/css/styles.css`
- `assets/img/saeid-king-mark.svg`

## Checks

The GitHub Actions workflow in `.github/workflows/static-check.yml` verifies required files, forbidden files, legacy contact strings, suspicious public-risk patterns, and local HTML link and asset references. For local work, run equivalent shell and Python checks before committing.
