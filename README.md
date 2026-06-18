# Bramble Kitchen 🍳

A full-stack recipe application built with Python, SQLite, FastAPI, React, and Bootstrap. </br>

<img width="1913" height="885" alt="Bramble Kitchen" src="https://github.com/user-attachments/assets/5da57fd8-d20b-4982-aa35-2d97cb05181f" /> 


## Live Demo

https://bramblekitchen.aslanyagmurr1.workers.dev/

## Project Overview

Bramble Kitchen is a recipe browsing application that extracts recipe data from HTML files, stores it in a SQLite database, exposes the data through a FastAPI backend, and displays recipes in a React frontend.

The project was created to practice web scraping, database management, API development, and frontend development in a single workflow.

## Features

* Parse recipe data from HTML files using BeautifulSoup
* Extract recipe title, description, ingredients, instructions, and images
* Store recipe information in SQLite
* Expose recipe data through a FastAPI REST API
* Display recipes dynamically in React
* Recipe detail modal
* Responsive card-based interface
* Local image fallback support

## Tech Stack

### Backend

* Python
* BeautifulSoup
* SQLite
* FastAPI

### Frontend

* React
* Vite
* Bootstrap
* React Bootstrap

### Deployment

* Cloudflare Workers / Pages
* GitHub

## Project Architecture

HTML Files
→ BeautifulSoup Parser
→ SQLite Database
→ FastAPI API
→ React Frontend
→ Cloudflare Deployment

## Challenges Faced

* Cloudflare protection blocked direct sitemap scraping
* Recipe images required fallback handling
* SQLite duplicate record prevention using UNIQUE constraints
* API integration between FastAPI and React
* Deployment configuration and dependency synchronization

## What I Learned

* HTML parsing with BeautifulSoup
* Data cleaning and transformation
* SQLite database design
* REST API development with FastAPI
* React state management and API consumption
* Frontend deployment using Cloudflare

## Future Improvements (V2)

* Direct sitemap parsing
* Automated recipe collection
* Search and filtering functionality
* Category-based navigation
* Better ingredient formatting
* Local image caching
* Improved responsive design

## Future Improvements (V3)

* AI-powered recipe recommendations
* Recipe similarity suggestions
* Nutritional analysis
* Meal planning assistant
* User favorites and saved recipes

## Source Code Access

This public repository is intended as a portfolio showcase and project overview.

Some implementation details, data collection scripts, and project assets are not included in this repository.

The complete source code can be presented and discussed during technical interviews upon request.
