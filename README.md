# indexdatabase

Structured JSON databases migrated from indexbox/chinese/ placeholder .md files (2026-10-12).

- `ChineseWord/chinese_word.json`: 10,850 Chinese single-character records (workspace for future definitions/zhuyin input).
- `Zhuyin/zhuyin.json`: 1,331 zhuyin syllable records (parsed from ␢-symbol filenames; the .md workspace files remain in indexbox/chinese/).

## JSON Relationship type

| Type | Description |
|------|-------------|
| One-to-One | A single object is linked to another single object. |
| One-to-Many | 	A single object can be linked to multiple objects. |

### O2O

```
{"name": "Alice"}
```

### O2M

```
{
  "books": [
    {"title": "Devil may cry", "year": 2015, "author_id": 1},
    {"title": "Beautiful ones are not yet born", "year": 2016, "author_id": 1},
    {"title": "The rich also cry", "year": 2016, "author_id": 2}
  ],
  "authors": [
    {"author_id": 1, "author_name": "Jack Sparrow"},
    {"author_id": 2, "author_name": "Stephen Ambrose"}
  ]
}
```

## Relationship among JSON files

### M2M stands for Many-to-Many

JSON Relationship Map: https://hashitosystem.com/en/tools/jsonmap/

