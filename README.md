## CLExpr ##

AviSynth Expr filter implemented in OpenCL.

Provides three functions:

* cl_expr - analogue of mt_lut
* cl_exprxy - analogue of mt_lutxy
* cl_exprxyz - analogue of mt_lutxyz

All expressions are calculated in runtime. 16-bit stacked clips are supported with the *lsb* parameter. Full set of masktools lut operators and functions is supported.