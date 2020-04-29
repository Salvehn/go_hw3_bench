# hw3_bench

Решение задачи **Оптимизация программы**. Coursera, курс: [Разработка веб-сервисов на Go - основы языка.](https://www.coursera.org/learn/golang-webservices-1/home/welcome)

Задание выполнено. Результат бенчмарка:

```
salvehn@MBP-Pavel hw3_bench-master % go test -bench . -benchmem
goos: darwin
goarch: amd64
BenchmarkSlow-8               50          24393076 ns/op        18950272 B/op     195829 allocs/op
BenchmarkFast-8             1018           1170618 ns/op          299005 B/op       3888 allocs/op
PASS

ok      /hw3_bench-master      2.711s
```
