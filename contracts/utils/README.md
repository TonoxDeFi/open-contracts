# utils.func
`utils.func` is an utility library for FunC.
## Usage
```c

() main(){
    int n1 = utils::to_ton(2); ;; or 2.utils::to_ton()
    n1~dump(); ;; 2000000000
}
```

## Functions
- `(slice) utils::get_serialized_address(int workchain, int address)`
- `(slice) utils::get_contract_address(int workchain, cell state_init)`
- `(int) utils::get_workchain(slice address)`
- `(int) utils::get_query_id()`
- `(int) utils::to_ton(int amount)` 
- `(int) utils::from_ton(int amount)` 
- `() utils::force_chain(int workchain, slice address, int error_code)`