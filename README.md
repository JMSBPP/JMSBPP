
<h3>Toolkit</h3>
<p>
  <img alt="Git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img alt="Solidity" src="https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />
  <img alt="Yul" src="https://img.shields.io/badge/-Yul-000000?style=flat-square&logo=ethereum&logoColor=white" />
  <img alt="Huff" src="https://img.shields.io/badge/-Huff-000000?style=flat-square&logo=ethereum&logoColor=white" />
</p>

EVM-based DEX AMM protocol Hooks/Plugins designs and implementations.

```solidity

function build(address amm) public {
    if (!IERC165(amm).supportsInterface(type(IAMM).interfaceId)) {
        revert(); 
    }
}

```

<!--
**JMSBPP/JMSBPP** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


