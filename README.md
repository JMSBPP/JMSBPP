
<h3>Toolkit</h3>
<p>
  <img alt="Solidity" src="https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />
  <img alt="Huff" src="https://img.shields.io/badge/-Huff-0A0A0A?style=flat-square&logo=ethereum&logoColor=white" />
  <img alt="PlankEVM" src="https://img.shields.io/badge/-PlankEVM-FF8C00?style=flat-square&logoColor=white" />
  <img alt="GAMS" src="https://img.shields.io/badge/-GAMS-FFD700?style=flat-square&logoColor=black" />
  <img alt="Haskell" src="https://img.shields.io/badge/-Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white" />
</p>

```solidity

function build(address clmm) public {
    if (!IERC165(clmm).supportsInterface(type(ICLMM).interfaceId)) {
        revert(); 
    }
}

```

<!--
**JMSBPP/JMSBPP** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
