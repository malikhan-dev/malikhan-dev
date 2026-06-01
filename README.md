# Mohammadreza Malikhan

Backend developer specializing in **Go (Golang)** and **C#**, focused on building efficient systems, reusable libraries, and clean backend architectures.

<p align="center">
  <img width="500" height="400" alt="zenq-logo" src="https://github.com/user-attachments/assets/6f0da9a5-bddb-4622-b914-54f2cbdb9b21" />
</p>

<h1 align="center">🌐 Project ZenQ</h1>

<p align="center">
  <em>Expressive, Polymorphic Queries with Streaming Capabilities and a User-Friendly API, inspired by LINQ.</em>
</p>

<p align="center">
  <a href="https://github.com/malikhan-dev/zenq"><strong>Explore the Repository »</strong></a>
</p>

---

## 📖 About ZenQ
**ZenQ** is an open-source Go DSL inspired by LINQ. It brings expressive querying, streaming, and pipeline execution to slices and various async data sources (such as CSV or JSON Files, MySql Or Postgres databases and etc...). ZenQ enables efficient processing for high-throughput workloads and large datasets.

The goal is to make data querying in Go more powerful and readable while staying aligned with Go's design principles.

### ✨ Key Features
*   **Fluent & Expressive:** A clean, LINQ-like query syntax.
*   **Performance-Aware:** Designed for high-throughput and efficiency.
*   **Versatile:** Seamlessly works with slices and external data sources.
*   **Developer Experience:** Clean, intuitive, and easy to maintain.
*   **Data Streaming:** Optimized for handling large datasets without overhead.

---

## 🚀 Developer Friendly

```go
ctx, cancel := context.WithCancel(context.Background())
defer cancel()

var CsvStreamConfig contracts.CsvStreamConf[customer]

if stream:= streams.FromCsv(ctx,CsvStreamConfig);stream.Initiated{
	data := stream.FilterStream(func(c customer) bool {return c.Index > 0}).TakeAll()
} else {
	fmt.Println(stream.err)
}

res := collections.From(UserList).
					Where(func(user Users) bool {
						return collections.From(user.Addr).Any(func(address Address) bool {
							return address.City == "Karaj"}).Assert()}).Collect()

```

---


## 💻 About Me

- Backend developer with a focus on DDD, Microservices,TDD
- Working primarily with **Go**, **.NET / C#** and **Blazor WebAseembly** 
- Interested in **systems design, performance optimization, and library development**
- Creator and main developer of the **Zen-Q** Go package


## 🛠 Tech Stack

### Languages
Go, C#

### Technologies & Tools
Golang, Gin, .NET, Asp.Net, Blazor WebAseembly,Linux ,PostgreSQL, Mongodb, Redis, REST APIs and etc


## 💡 Development Principles

- Write **tested,documented, clear and maintainable code**
- Prefer **simple and meaningful designs**
- Optimize **performance where it matters**
- Build tools that improve the **developer experience**


## 📫 Contact

GitHub: https://github.com/malikhan-dev 

email: malikhan.dev2020@gmail.com

