# indexdatabase

Structured JSON databases migrated from indexbox/chinese/ placeholder .md files (2026-10-12).

- `ChineseWord/chinese_word.json`: 10,850 Chinese single-character records (workspace for future definitions/zhuyin input).
- `Zhuyin/zhuyin.json`: 1,331 zhuyin syllable records (parsed from ␢-symbol filenames; the .md workspace files remain in indexbox/chinese/).

## Relationship among JSON files

| Type | Description |
|------|-------------|
| One-to-One | A single JSON is linked to another single JSON. |
| One-to-Many | 	A single JSON can be linked to multiple JSONs. |

### O2O

{"name": "Alice"}

### O2M

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
