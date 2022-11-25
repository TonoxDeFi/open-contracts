# curve_math.func
`curve_math.func` is a library that provides operations on (some elliptic curves).
Parameters for secp256k1 is included.

## Note
`curve_math::ecMul` will reach gas limit if the scalar is too large.

## Functions
- `(int, int) curve_math::ecInv(int _x, int _y, int _pp)`
- `(int, int) curve_math::ecSub(int _x1, int _y1, int _x2, int _y2, int _aa, int _pp)`
- `(int, int) curve_math::ecMul(int _k, int _x, int _y, int _aa, int _pp)`
- `(int, int) curve_math::derivePubKey(int privKey)`
- `(int) curve_math::verify(int h, int r, int s, int pubx, int puby)`