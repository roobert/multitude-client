# Multitude CLI

See [Multitude](https://github.com/roobert/multitude) for more info.

## Example Output

```
╒═════════════════════╤══════════════╤═══════════╤══════════════════╤══════════════╤═══════════════════╕
│ timestamp           │ app          │ version   │ build pipeline   │ image repo   │ deployment        │
╞═════════════════════╪══════════════╪═══════════╪══════════════════╪══════════════╪═══════════════════╡
│ 2020-03-22 14:57:26 │ company/app0 │ 0.0.3     │ SUCCESS          │ UPLOADING    │ --                │
├─────────────────────┼──────────────┼───────────┼──────────────────┼──────────────┼───────────────────┤
│ 2020-03-22 14:56:42 │ company/app1 │ 0.0.1     │ SUCCESS          │ SUCCESS      │ project1/cluster0 │
├─────────────────────┼──────────────┼───────────┼──────────────────┼──────────────┼───────────────────┤
│ 2020-03-22 14:56:42 │ company/app1 │ 0.0.1     │ SUCCESS          │ SUCCESS      │ project0/cluster0 │
╘═════════════════════╧══════════════╧═══════════╧══════════════════╧══════════════╧═══════════════════╛
```
