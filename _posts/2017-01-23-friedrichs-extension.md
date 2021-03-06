---
title: "The Friedrichs Extension of an Unbounded Operator"
categories:
  - Functional Analysis
tags:
  - friedrichs
  - linear-operators
  - unbounded-operators
---

**Definition 1.** Let \\(\mathcal{H}_0\\) and \\(\mathcal{H}_1\\) be Hilbert spaces. An *unbounded operator* \\(\mathcal{H}_0 \to \mathcal{H}_1\\)
is a linear map
<div class="mathjax">\begin{equation*}
  T ~\colon \mathrm{dom}(T) \longrightarrow \mathcal{H}_1
\end{equation*}</div>
where \\(\mathrm{dom}(T) \subseteq \mathcal{H}_0\\) is required to be a dense subspace. Since an operator of this form
can be constructed by simply restricting a bounded operator on \\(\mathcal{H}_0\\) to \\(\mathrm{dom}(T)\\), we also require that \\(T\\) not
be such a restriction. ∎

**Definition 2.** Let \\(T\\) and \\(S\\) are unbounded operators \\(\mathcal{H}_0 \to \mathcal{H}_1\\). If 
\\(\mathrm{dom}(T) \subseteq \mathrm{dom}(S)\\) and \\(S| \_ {\mathrm{dom}(T)} \equiv T\\) then we say that \\(S\\) is an *extension* of \\(T\\).
For short we often write this as \\(T \subset S\\).∎

**Definition 3.** Let \\(T \colon \mathcal{H}_0 \to \mathcal{H}_1\\) and \\(S \colon \mathcal{H}_1 \to \mathcal{H}_0\\) be unbounded operators. 
We say that \\(S\\) a *sub-adjoint* to \\(T\\) if, for all \\(v \in \mathrm{dom}(T)\\) and \\(w \in \mathrm{dom}(S)\\), we have
<div class="mathjax">\begin{equation*}
  \langle Tv, w \rangle = \langle v, Sw \rangle
\end{equation*}</div>∎

If \\(\mathcal{H}_0\\) and \\(\mathcal{H}_1\\) are Hilbert spaces, then the direct sum \\(\mathcal{H}_0 \oplus \mathcal{H}_1\\) is also a
Hilbert space. The inner product on the direct sum is given by
<div class="mathjax">\begin{equation*}
  \langle v_0 \oplus v_1 , w_0 \oplus w_1 \rangle = \langle v_0, w_0 \rangle + \langle v_1, w_1 \rangle
\end{equation*}</div>
