Modular Caching Layer with Dependency Injection

✅ Task:

Build a small FastAPI module that demonstrates a custom in-memory caching layer using dependency injection.

Requirements:

Create a Cache class that supports:
get(key), set(key, value, ttl=None), and delete(key).
TTL-based auto-expiry of items.
Use this cache as a dependency injected into routes.
Create a /products/{id} endpoint that:
Returns cached data if available.
If not, simulates fetching product details (with async sleep) and caches the result.
Demonstrate cache invalidation via a /cache/clear endpoint.
