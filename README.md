# Search Engine with Inverted Index, Web Crawler, and Cosine Similarity

This project implements a lightweight search engine capable of crawling webpages, building an inverted index, and returning ranked search results using cosine similarity. It includes two versions of the system:

Synchronous Version — simple and easier to understand.

Asynchronous Version — faster, scalable, and suited for large crawls.

## 🚀 Features

### Web Crawler

- Extracts text content from web pages.

- Follows hyperlinks up to a configurable depth.

- Prevents repeated crawling using visited‑URL tracking.

### Inverted Index

- Maps each unique term to the documents (URLs) that contain it.

- Stores term frequency for each document.

- Used for efficient query processing.

### Two Implementations

- sync/ — Synchronous, single‑threaded crawler and index builder.

- async/ — Asynchronous version using asyncio and aiohttp for high concurrency.

### Cosine Similarity Ranking

- Queries are vectorized using TF‑IDF.

- Each document is scored based on similarity to the query.

- Results returned in descending score order.
