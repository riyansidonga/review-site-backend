

# Review Site Backend

## Group Members
- Riyansi Donga
- Edward Owusu Boafo
- Antonio Fernando

## Project Overview
This is the backend for our Movie Review Site group assignment. It uses Strapi as the Headless CMS to store, manage, and deliver movie review data through a REST API. The frontend consumes this data and displays it on the review site.

## Review Type
Movie Review

## Headless CMS
Strapi

## Frontend Tool
Vue 3 + Vite + Vue Router

## Features
- Stores and manages movie review content in Strapi
- Provides review data through a REST API
- Includes at least 10 movie reviews
- Supports title, slug, category, rating, summary, body, author, release date, cover image, and featured status
- Public API permissions enabled for fetching reviews
- Works with a Vue frontend that consumes the API data

## Project Structure
The Strapi backend project is located inside the `app` folder.

## Content Type

### Review
Fields used in the Review collection type:
- `title`
- `slug`
- `category`
- `rating`
- `summary`
- `body`
- `author`
- `releaseDate`
- `coverImage`
- `featured`

## Live Site
https://review-site-headless-cms.netlify.app/

## API Endpoints

### Get all reviews
```bash
http://localhost:1337/api/reviews