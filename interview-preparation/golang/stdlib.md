# 📌 Go Standard Library Cheatsheet

A collection of the most popular and frequently useful functions/methods from Go's standard library.  

---

## ✅ `strings` package

```go
strings.ToUpper("go")              // "GO"
strings.ToLower("HELLO")           // "hello"
strings.TrimSpace("  hi  ")        // "hi"
strings.HasPrefix("gopher", "go")  // true
strings.HasSuffix("gopher", "er")  // true
strings.Contains("hello", "ll")    // true
strings.Count("banana", "a")       // 3
strings.Repeat("na", 3)            // "nanana"
strings.ReplaceAll("foo bar foo", "foo", "baz") // "baz bar baz"
strings.Split("a,b,c", ",")        // []string{"a","b","c"}
strings.Join([]string{"a","b"}, "-") // "a-b"
strings.Fields("a b   c")          // []string{"a","b","c"}
```


## ✅ `strconv` package
```go
strconv.Itoa(123)                  // "123"
strconv.Atoi("456")                // 456
strconv.FormatInt(15, 2)           // "1111"
strconv.ParseInt("1111", 2, 64)    // 15
```

## ✅ `fmt` package
```go
fmt.Println("Hello", "Go")         // Hello Go
fmt.Printf("Pi: %.2f\n", 3.14159)  // Pi: 3.14
msg := fmt.Sprintf("Hi %s", "Bob") // "Hi Bob"
```

## ✅ `math` package
```go
math.Max(10, 20)   // 20
math.Min(10, 20)   // 10
math.Abs(-42)      // 42
math.Pow(2, 3)     // 8
math.Sqrt(16)      // 4
math.Round(2.7)    // 3
math.Floor(2.9)    // 2
math.Ceil(2.1)     // 3
```

## ✅ `time` package
```go

```

## ✅ `sort` package
```go

```

## ✅ `bytes` package
```go

```

## ✅ `io\os` package
```go

```


## ✅ `bufio` package
```go

```


## ✅ `unicode` package
```go

```


## common Go format specifiers:


    %d → Integer (decimal)

    %f → Floating point

    %s → String

    %v → Default format (any value)

    %t → Boolean

    %x → Hexadecimal

    %T → Type of value
