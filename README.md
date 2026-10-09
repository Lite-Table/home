# LiteTable Ecosystem

Welcome to **LiteTable** — a lightweight, high-performance database access toolkit designed for developers who prefer clean SQL and native maps over heavy, bureaucratic ORMs.

> 📖 **[Official Documentation](https://lite-table.github.io/docs/)**

## 🚀 The Philosophy

Traditional ORMs often introduce unnecessary overhead, hidden performance traps (like N+1 queries), and heavy change-tracking magic. **LiteTable** strips away the boilerplate while keeping safety and developer experience (DX) intact.

- **No Heavy Serialization:** Work directly with native arrays, maps, and primitive types.

- **SQL First:** Write your own queries or use simple CRUD wrappers without losing control.

- **Predictable & Fast:** Zero hidden magic. What you write is exactly what gets executed.


---

## 🌐 Multi-Language Ecosystem

The LiteTable philosophy isn't tied to a single language. We are building a consistent API and developer experience across multiple stacks, making it seamless for developers working in polyglot environments:

| Language | Package Status | Repository | Description |
| :--- | :--- | :--- | :--- |
| **PHP** | 🟢 Active | [litetable-php](https://github.com/ortizaad1994/litetable-php) | Native PDO wrapper, fast CRUD, and fluent query execution. |
| **Go** | 🚧 In Progress | [litetable-go](https://github.com/ortizaad1994/litetable-go) | High-performance implementation mirroring the same DX. |
| **.NET** | 🔜 Coming Soon | [litetable-dotnet](https://github.com/ortizaad1994/litetable-dotnet) | Lightweight data access mapping directly to dictionaries/structs. |
| **Python** | 🔜 Coming Soon | [litetable-python](https://github.com/ortizaad1994/litetable-python) | Clean, minimal database utility without heavy ORM bloat. |

---

## 📦 Core Components

Across all implementations, LiteTable provides three fundamental building blocks:

1. **`Connection / Database`**: A clean, streamlined database connection manager configured with safe defaults (prepared statements, secure character sets, and optimal error modes).

2. **`Table`**: A zero-boilerplate CRUD helper for standard table operations (`find`, `all`, `insert`, `update`, `delete`).
3. **`Query`**: A safe query executor for custom SQL statements with parameter binding returning raw objects or collections.

---

## 📄 License

Open-source software licensed under the [MIT license](LICENSE).
