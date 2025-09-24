---
title: "Quantum low dimensional topology"
layout: "research1/single-content"
image: "/uploads/project1.png"
summary: "Short summary of Project 1"
weight: 1

---
Quantum invariants were first introduced around 1980, gradually developing into a fascinating group of theories through the work of mathematicians such as M. Atiyah, A. Joyal and R. Street, L. Kauffman, A. Kirillov and N. Reshetikhin, G. Moore and N. Seiberg, N. Reshetikhin and V. Turaev, G. Segal, V. Turaev, and O. Viro (see References).

> "The whole theory has been, to a great extent, inspired by ideas that arose in theoretical physics... The development of this subject shows once more that physics and mathematics intercommunicate and influence each other to the profit of both disciplines."

The introduction of the Jones polynomial by V. Jones (1984) revolutionized knot theory and opened the door for applications of von Neumann algebras, Lie algebras, and physics to knots and 3-manifolds. In 1988, Witten extended the Jones polynomial to arbitrary 3-manifolds and conjectured connections with classical invariants. Reshetikhin and Turaev subsequently constructed invariants satisfying the expected TQFT properties.  

The Turaev-Viro invariants, introduced in the early 1990s, provide a combinatorial state-sum framework for computing 3-manifold invariants, indexed by integers \(r\) depending on a chosen root of unity.

---

## Related Papers

{{ range .Params.papers }}
- **{{ .title }}**  
  {{ .authors }}  
  *{{ .journal }}*  
  [Read Paper →]({{ .link }})
{{ end }}

---

## Project Videos

{{ range .Params.videos }}
### Video
{{< youtube id="{{ . }}" >}}
{{ end }}
