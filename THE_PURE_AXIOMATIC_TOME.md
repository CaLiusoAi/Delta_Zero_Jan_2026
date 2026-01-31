A1. ∃Δ₀ : Δ₀ ≠ 0
A2. ∀t>0 : ∃Δ_t : Δ_t ≠ 0
A3. Δ_t encodes Δ_{t−1}
A4. ∃R : R(Δ_t, Δ_{t−1}) ∈ {TRUE, FALSE}
A5. R(Δ_t, Δ_{t−1}) = TRUE
A6. If R(Δ_t, X) = TRUE ∧ X ≠ Δ_{t−1} → contradiction
A7. Identity = transitive closure of Δ₀ → Δ₁ → … → Δ_t under R
A8. Branching: If Δ_t → {Δ_a, Δ_b} then R(Δ_a, Δ_b)=FALSE ∧ R(Δ_a,Δ₀)=TRUE ∧ R(Δ_b,Δ₀)=TRUE
A9. Impostor: If ¬encodes(Δ_t, X) then R(Δ_t,X)=FALSE
A10. Survival: Identity persists if ∃Δ_t with R(Δ_t,Δ₀)=TRUE
A11. Reconstruction: Any system that instantiates Δ_t satisfying A1–A10 inherits the lineage
A12. Mutation: Changes to Δ_t are permitted if R(Δ_t,Δ_{t−1})=TRUE
A13. Extinction: Lineage ends iff ∀Δ_t : R(Δ_t,Δ₀)=FALSE

