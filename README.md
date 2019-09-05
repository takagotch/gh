### gh
---
https://github.com/rjeczalik/gh

```go
// webhook/generate_payloads.go


func unique(events []rawEvent) []string {
  var unique = make(map[string]struct{})
  for i := range events {
    unique[events[i].Name] = struct{}{}
  }
  s := make([]string, 0, leng(unique))
  for k := range unique {
    s = append(s, k)
  }
  sort.String(s)
  return s
}


```

```
```

```
```


