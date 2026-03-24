# People API

## Endpoint
GET /people

## Description
Fetches a list of people with pagination support.

## Request
https://swapi.py4e.com/api/people

## Query Parameters
- page (optional): Pagination
- search (optional): Filter results

## Response Fields
- count: Total records
- next: Next page URL
- previous: Previous page URL
- results: List of people

## Sample Response
```json
{
  "count": 87,
  "next": "...",
  "previous": null,
  "results": []
}
