# utils.func
`utils.func` is an utility library for FunC.
> Note: This library requires [math.func](https://github.com/TonoxDeFi/math.func)
## Usage
```c

() main(){
    int n1 = to_ton(2); ;; or 2.to_ton()
    n1~dump(); ;; 2000000000
}
```

## Functions
- `(slice) get_serialized_address(int workchain, int address)`
- `(slice) get_contract_address(int workchain, cell state_init)`
- `(int) get_workchain(slice address)`
- `(int) get_query_id()`
- `(int) to_ton(int amount)` 
- `(int) from_ton(int amount)` 
- `() force_chain(int workchain, slice address, int error_code)`