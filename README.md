*Note: Below solutions were found by me while learning the material. They are unchecked and many are likely incorrect. Final answers are underlined.*

# pset 1

## Problem 1

**a)** **A,B,C,D** = <u>(+1,+1,+1), (+1,-1,-1), (-1,+1,-1), (-1,-1,+1)</u>

**b)** **A** ⋅ **B** = A B cos(θ) = -1 ⟹ θ = acos(-1/3) ≈ <u>109°</u>

**c)**
  -  **AB** ⋅ **AC** = 8 cos(θ) = 4 ⟹ θ = acos(1/2) = π/3 = <u>60°</u>
  -  **AB** ⋅ **CD** = 8 cos(θ) = 0 ⟹ θ = acos(0) = π/2 = <u>90°</u>

**d)** (1/2) * 2√2 * 2√2 * sin(π/3) = <u>2√2</u>

## Problem 2

**a)** v₁ ⋅ (v₂-v₃) = 0

**b)**
  -  P lies on the altitude from P₁ ⟺ v₁ ⋅ (v₂-v₃) = 0 ⟺ v₁⋅v₂ - v₁v₃ = 0 ⟺ v₁⋅v₂ = v₁v₃
  -  P lies on the altitude from P₂ ⟺ v₂ ⋅ (v₁-v₃) = 0 ⟺ v₁⋅v₂ - v₂v₃ = 0 ⟺ v₁⋅v₂ = v₂v₃

**c)** v₁v₃ = v₂v₃ ⟺ v₁v₃ - v₂v₃ = 0 ⟺ v₃ ⋅ (v₁-v₂) ⟺ P lies on the altitude from P₃

## Problem 3

The tetrahedron has rotational symmetry in 3 dimensions, so the vectors must also have rotational symmetry in 3 dimensions. Any symmetrical set of vectors sums to 0.

## Problem 4

**a)** u: /, v: \

**b)** *For clarity, let a=θ_1 and b=θ_2*

A₁A₂ = 

	cos(a)cos(b)-sin(a)sin(b)  -cos(a)sin(b)-sin(a)cos(b)
	sin(a)cos(b)+sin(b)cos(a)  -sin(a)sin(b)+cos(a)cos(b)

	=

	cos(a+b)  -sin(a+b)
	sin(a+b)   cos(a+b)

A rotation of a degrees followed by a rotation of b degrees is the same as a rotation of a+b degrees.

**c)**

A^-1 = 1/(cos²(θ)+sin²(θ)) ⋅

	cos(θ)   sin(θ)
	-sin(θ)  cos(θ)

= A^T

*cos²(θ)+sin²(θ) = 1*

A^T⋅A =

	cos²(θ)+sin²(θ)            sin(θ)cos(θ)-sin(θ)cos(θ)
	sin(θ)cos(θ)-sin(θ)cos(θ)  cos²(θ)+sin²(θ)

	=

	1  0
	0  1

sin(-θ) = -sin(θ),  cos(-θ) = cos(θ). Rotation by -x is rotation in the opposite direction.

**d)**

	-1/√2      √(1-1/√2)      -1/√2       √(1+1/√2)      -1/√2      √(1+1/√2)      -1/√2       √(1-1/√2)
	√(1-1/√2)  1              -√(1+1/√2)  1              √(1+1/√2)  -1             -√(1-1/√2)  -1

**e)**
