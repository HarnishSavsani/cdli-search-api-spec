# CDLI Search API Specification

This repository provides the official **OpenAPI 3.0** specification and interactive developer documentation for the [Cuneiform Digital Library Initiative (CDLI)](https://cdli.earth).

The API allows researchers and developers to programmatically query the CDLI database, which contains metadata and transliterations for over 350,000 Mesopotamian artifacts.

## 🌐 Live Documentation

The interactive API explorer is hosted via GitHub Pages:
👉 **[https://harnishsavsani.github.io/cdli-search-api-spec/](https://harnishsavsani.github.io/cdli-search-api-spec/)**

---

## 🚀 Getting Started

### API Base URL
All production requests should be directed to:
`https://cdli.earth`

### Quick Example (cURL)
To search for artifacts from the **Uruk III** period:
```bash
curl -X GET "[https://cdli.earth/search?period=Uruk%20III&format=json](https://cdli.earth/search?period=Uruk%20III&format=json)"
