# math.func
`math.func` is a math library that extends FunC's arithmetic operations.

## Usage
```c

() main(){
    int n1 = math::exp(2); ;; or 2.math::exp()
    n1~dump(); ;; 4

    int n2 = math::sqrt(36); ;; or 36.math::exp()
    n2~dump(); ;; 6
}
```

## Functions
- `(int) math::sqrt(int x)`
- `(int) math::avg(int x, int y)`
- `(int) math::exp(int x)`
- `(int) math::log2(int x)` 
- `(int) math::mod(int x, int y)`