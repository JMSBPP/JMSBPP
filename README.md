
<h3>Toolkit</h3>
<p>
  <img alt="Solidity" src="https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />
  <img alt="Huff" src="https://img.shields.io/badge/-Huff-0A0A0A?style=flat-square&logoColor=white" />
  <img alt="Lean4" src="https://img.shields.io/badge/-Lean4-4B0082?style=flat-square&logoColor=white" />
  <img alt="edge-rs" src="https://img.shields.io/badge/-Edge_(EVM)-1C1C1C?style=flat-square&logo=rust&logoColor=white" />
</p>

```solidity

function build(address amm) public {
    if (!IERC165(amm).supportsInterface(type(IAMM).interfaceId)) {
        revert(); 
    }
}

```

<!--
**JMSBPP/JMSBPP** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


