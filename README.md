
<h3>Toolkit</h3>
<p>
  <img alt="Solidity" src="https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />
  <img alt="Haskell" src="https://img.shields.io/badge/-Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white" />
  <img alt="GAMS" src="https://img.shields.io/badge/-GAMS-005DAA?style=flat-square&logo=gams&logoColor=white" />
</p>


EVM-based DEX AMM protocol Hooks/Plugins applications.

```solidity

function build(address amm) public {
    if (!IERC165(amm).supportsInterface(type(IAMM).interfaceId)) {
        revert(); 
    }
}

```

<!--
**JMSBPP/JMSBPP** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


