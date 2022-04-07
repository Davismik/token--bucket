 As requests are consuming tokens, we also need to refill them at some fixed rate and time, such that we never exceed the capacity of the bucket. Let's consider an API that has a rate limit of 100 requests per minute. We can create a bucket with a capacity of 100, and a refill rate of 100 tokens per minute.

Please refer to the [Understanding Rate Limiting Algorithms](https://nataraj-srikantaiah.medium.com/understanding-rate-limiting-algorithms-2244c302025a) blog where the Token Bucket and other algorithms have been explained in detail.
Please refer to the [Understanding Rate Limiting Algorithms](https://bhargav-journal.blogspot.com/2020/12/understanding-rate-limiting-algorithms.html) blog where the Token Bucket and other algorithms have been explained in detail.

## Token Bucket Algorithm - RateLimiter Spring Boot Project

Refer to the [Rate Limiter Implementation - Token Bucket Algorithm](https://nataraj-srikantaiah.medium.com/rate-limiter-implementation-token-bucket-algorithm-636bb32741b2) for step by step implementation details.
Refer to the [Rate Limiter Implementation - Token Bucket Algorithm](https://bhargav-journal.blogspot.com/2020/12/rate-limiter-token-bucket.html) for step by step implementation details.
