# Go Concurrency Patterns

This repository collects common concurrency patterns in Golang


## Materials
- [Concurrency is not parallelism](https://blog.golang.org/waza-talk)
- [Go Concurrency Patterns](https://talks.golang.org/2012/concurrency.slide#1)
and [source](https://talks.golang.org/2012/concurrency/support/)
- [Advanced Go Concurrency Patterns](https://talks.golang.org/2013/advconc.slide)
- [Rethinking classical concurrency pattern](https://www.youtube.com/watch?v=5zXAHh5tJqQ)
- [Go Concurrency Patterns: Pipelines and cancellation](https://blog.golang.org/pipelines)
- [Go Concurrency Patterns: Timing out, moving on](https://blog.golang.org/concurrency-timeouts)
- [Complex Concurrency Patterns with Go](https://www.youtube.com/watch?v=2HOO5gIgyMg)

## Context:
- [Go Concurrency Patterns: Context](https://blog.golang.org/context)
- [How to correctly use package context](https://www.youtube.com/watch?v=-_B5uQ4UGi0)
- [justforfunc #9: The Context Package](https://www.youtube.com/watch?v=LSzR0VEraWw)
- [Contexts and structs](https://blog.golang.org/context-and-structs)

| Name                                                      | Description                                         | Playground                                    |
|-----------------------------------------------------------|-----------------------------------------------------|-----------------------------------------------|
| [01-boring](/01-boring/main.go)                             | A hello world to goroutine                          | [play](https://play.golang.org/p/ienqr4bKGQ6) | 
| [02-chan](/02-chan/main.go)                                 | A hello world to go channel                         | [play](https://play.golang.org/p/amazakVmwFy) |
| [03-generator](/03-generator/main.go)                       | A python-liked generator                            | [play](https://play.golang.org/p/9ykTDe7qLSw) |
| [04-fanin](/04-fanin/main.go)                               | Fan in pattern                                      | [play](https://play.golang.org/p/mw_29ibv0bh) |
| [05-restore-sequence](/05-restore-sequence/main.go)         | Restore sequence                                    | [play](https://play.golang.org/p/aV43DEmNZBz) |
| [06-select-timeout](/06-select-timeout/main.go)             | Add Timeout to a goroutine                          | [play](https://play.golang.org/p/WIqNvmxiYvn) |
| [07-quit-signal](/07-quit-signal/main.go)                   | Quit signal                                         | [play](https://play.golang.org/p/rKYKqMeoFDq) |
| [08-daisy-chan](/08-daisy-chan/main.go)                     | Daisy chan pattern                                  | [play](https://play.golang.org/p/1y-4ERc3Xv4) |
| [09-google1.0](/09-google1.0/main.go)                       | Build a concurrent google search from the ground-up | [play](https://play.golang.org/p/xMhEBlcYkfz) |
| [10-google2.0](/10-google2.0/main.go)                     | Build a concurrent google search from the ground-up | [play](https://play.golang.org/p/-J5C9McGG9t) |
| [11-google2.1](/11-google2.1/main.go)                     | Build a concurrent google search from the ground-up | [play](https://play.golang.org/p/hNc_HStC2BT) |
| [12-google3.0](/12-google3.0/main.go)                     | Build a concurrent google search from the ground-up | [play](https://play.golang.org/p/uE82kcSDkSJ) |
| [13-adv-pingpong](/13-adv-pingpong/main.go)               | A sample ping-pong table implemented in goroutine   | [play](https://play.golang.org/p/hT6knhJjBXY) |
| [14-adv-subscription](/14-adv-subscription/main.go)       | Subscription                                        | [play](https://play.golang.org/p/J5cjAV-qtaR) |
| [15-bounded-parallelism](/15-bounded-parallelism/main.go) | Bounded parallelism                                 | [play](https://play.golang.org/p/j_aq1dcGkGr) |
| [16-context](/16-context/main.go)                         | How to user context in HTTP client and server       | [play](https://play.golang.org/p/ZKZfKtpEJqH) |
| [17-ring-buffer-channel](/17-ring-buffer-channel/main.go) | Ring buffer channel                                 | [play](https://play.golang.org/p/aeUeCTWhgJ2) |
| [18-worker-pool](/18-worker-pool/main.go)                 | worker pool pattern                                 | [play](https://play.golang.org/p/CxKoTnzb9Mx) |
