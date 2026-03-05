# Exercise 2 — Transforming Between Collection Types in Kotlin

A Kotlin program that demonstrates how to transform a `List` into a `Map` using `associateWith`, then filter and process the map entries.

## What it does
- Converts a `List<String>` into a `Map<String, Int>` where values are word lengths
- Filters map entries where length is greater than 4
- Applies different threshold filters on the same map
- Uses `mapValues` to classify words as Short / Medium / Long
- Real-world extension: applies the same concept to a Book Library (word count per title, char length filtering)

## How to Run
1. Open the project folder in **IntelliJ IDEA**
2. Wait for Gradle to sync
3. Open `src/main/kotlin/Main.kt`
4. Click the green ▶ **Run** button next to `fun main()`

## Sample Output
```
Input list: [apple, cat, banana, dog, elephant]

Filtered (length > 4):
  apple has length 5
  banana has length 6
  elephant has length 7
```

## Tech Stack
- Kotlin 1.9.24
- Gradle 8.8
- JDK 17
