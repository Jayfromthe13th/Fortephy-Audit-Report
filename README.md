# Fortephy-Audit-Report
![Screen Shot 2023-03-22 at 4 20 23 PM](https://user-images.githubusercontent.com/83922342/229944121-0192ac78-3ac1-48f9-988b-5075db77ec1c.png)

The Fortephy Audit Report, dated 1/11/23, presents a comprehensive security assessment of the Fortephy auditing tool, which is designed to detect vulnerabilities in smart contracts and blockchain networks. The evaluation involved testing the tool's ability to identify known vulnerabilities, including reentrancy, ERC20 approve race condition, no boolean transfer & transferFrom, and token deflationary exploits. Additionally, a hypothetical stress test was conducted to assess the robustness of the Fortephy API. The report documents the findings and offers recommendations for improvements to address the vulnerabilities and enhance the tool's performance.

### Findings:

Reentrancy: Undetected vulnerability
No Boolean Transfer & TransferFrom: Undetected vulnerability
Token deflationary exploits: Undetected vulnerability
ERC20 approve race condition: Undetected vulnerability
Fortephy API: Failed the hypothetical stress test.


**In total, 4 medium-to-high vulnerabilities were found, and the Fortephy API did not perform well under stress testing.**
