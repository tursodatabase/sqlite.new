# [sqlite.new](https://sqlite.new)

Create a new database from scratch, or an existing SQLite dump using the Create Database Button.

## Snippets

[![Create a database with Turso](https://sqlite.new/button)](https://sqlite.new)

### Markdown

```markdown
[![Create a database with Turso](https://sqlite.new/button)](https://sqlite.new)
```

### HTML

```html
<a href="https://sqlite.new">
    <img src="https://sqlite.new/button" alt="Create a database with Turso" />
</a>
```

### URL

```bash
https://sqlite.new
```

## Query Parameters

### `type`

Specify `schema` as the `type` if you want to use multi-db schemas!

* `schema` - Create a database with multi-db schema support

```markdown
[![Create a database with Turso](https://sqlite.new/button)](https://sqlite.new?type=schema)
```

### `dump`

If you set `dump` to an existing SQLite dump file you host, you can seed the new database using this:

```markdown
[![Create a database with Turso](https://sqlite.new/button)](https://sqlite.new?dump=https%3A%2F%2Fmysite.com%2Ffile.db)
```

### `name`

You can set the name of the database using this parameter:

```markdown
[![Create a database with Turso](https://sqlite.new/button)](https://sqlite.new?name=my-new-database)
```

### `location`

You can select the primary location for your database using the `location` paerameter:

```markdown
[![Create a database with Turso](https://sqlite.new/button)](https://sqlite.new?location=lax)
```

You can see a full list of `location` codes [here](https://docs.turso.tech/concepts#locations).
