# curve_math.func
`curve_math.func` is a library that provides operations on (some elliptic curves).
Parameters for secp256k1 is included.

## Note
`secp256k1::ecMul` will reach gas limit if the scalar is too large.

## Functions
- `(int, int) secp256k1::ecInv(int _x, int _y, int _pp)`
- `(int, int) secp256k1::ecSub(int _x1, int _y1, int _x2, int _y2, int _aa, int _pp)`
- `(int, int) secp256k1::ecMul(int _k, int _x, int _y, int _aa, int _pp)`
- `(int, int) secp256k1::derivePubKey(int privKey)`
- `(int) secp256k1::verify(int h, int r, int s, int pubx, int puby)`