# DNS

![#f03c15](https://placehold.it/15/f03c15/000000?text=+) 通过自定义 DNS 来快速、正确的获取 Domain 的IP。Loon 会根据用户自行设置的 DNS 并发请求，使用响应最快的结果，并且使用 LRU 缓存最近的100个结果。