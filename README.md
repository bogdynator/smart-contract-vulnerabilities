# Smart Contract Vulnerabilities

- [Forcibly Sending Ether to a Smart Contract](/vulnerabilities/forcibly-sending-ether.md) -> DONE 
- [Insufficient Gas Griefing](/vulnerabilities/insufficient-gas-griefing.md) -> DONE
- [Reentrancy](/vulnerabilities/reentrancy.md) -> reentrancy-no-eth
- [Integer Overflow and Underflow](/vulnerabilities/overflow-underflow.md) -> FOR < 0.8 AND THE USE OF UNCEHCKED > 0.8
- [Timestamp Dependence](/vulnerabilities/timestamp-dependence.md) -> timestamp
- [Authorization Through tx.origin](/vulnerabilities/authorization-txorigin.md) -> tx-origin
- [Floating Pragma](/vulnerabilities/floating-pragma.md) -> pragma
- [Function Default Visibility](/vulnerabilities/function-default-visibility.md) -> TO DO
- [Outdated Compiler Version](/vulnerabilities/outdated-compiler-version.md) -> solc-version
- [Unchecked Call Return Value](/vulnerabilities/unchecked-call-return-value.md) -> unchecked-lowlevel
- [Unprotected Ether Withdrawal](/vulnerabilities/unprotected-ether-withdrawal.md) -> arbitrary-send-eth ??
- [Unprotected Selfdestruct Instruction](/vulnerabilities/unprotected-selfdestruct.md) -> suicidal
- [State Variable Default Visibility](/vulnerabilities/state-variable-default-visibility.md) -> DONE
- [Uninitialized Storage Pointer](/vulnerabilities/uninitialized-storage-pointer.md) -> NOT
- [Assert Violation](/vulnerabilities/assert-violation.md) -> DONE
- [Use of Deprecated Functions](/vulnerabilities/use-of-deprecated-functions.md) -> deprecated-standards
- [Delegatecall to Untrusted Callee](/vulnerabilities/delegatecall-untrusted-callee.md) -> controlled-delegatecall
- [Signature Malleability](/vulnerabilities/signature-malleability.md) -> DONE
- [Incorrect Constructor Name](/vulnerabilities/incorrect-constructor.md) -> NOT
- [Shadowing State Variables](/vulnerabilities/shadowing-state-variables.md) -> shadowing-state
- [Weak Sources of Randomness from Chain Attributes](/vulnerabilities/weak-sources-randomness.md) -> smth this is intended
- [Missing Protection against Signature Replay Attacks](/vulnerabilities/missing-protection-signature-replay.md) -> DONE
- [Requirement Validation](/vulnerabilities/requirement-violation.md) -> NOT
- [Write to Arbitrary Storage Location](/vulnerabilities/arbitrary-storage-location.md) -> array length can't be modified in the new versions of solidity
- [Incorrect Inheritance Order](/vulnerabilities/incorrect-inheritance-order.md) -> can't see a detector for this
- [Arbitrary Jump with Function Type Variable](/vulnerabilities/arbitrary-jump-function-type.md) -> ??
- [Presence of Unused Variables](/vulnerabilities/unused-variables.md) -> unused-state
- [Unexpected Ether Balance](/vulnerabilities/unexpected-ether-balance.md) -> DONE
- [Unencrypted Secrets](/vulnerabilities/unencrypted-secrets.md) -> ??
- [Faulty Contract Detection](/vulnerabilities/faulty-contract-detection.md) -> DONE
- [Unclogged Blockchain Reliance](/vulnerabilities/unclogged-blockchain-reliance.md) -> ??
- [Inadherence to Standards](/vulnerabilities/inadherence-to-standards.md) -> can't see a detector for this
- [Unprotected Callback](/vulnerabilities/unprotected-callback.md) -> reentrancy
- [Asserting EOA from Code Size](/vulnerabilities/asserting-eoa-from-code-size.md) -> DONE
- [Transaction-Ordering Dependence](/vulnerabilities/transaction-ordering-dependence.md) -> NOT
- [DoS with Block Gas Limit](/vulnerabilities/dos-gas-limit.md) -> calls-loop
- [DoS with (Unexpected) revert](/vulnerabilities/dos-revert.md) -> can't see a detector for this

## Further Reading

- https://github.com/ethereum/wiki/wiki/Safety
- https://swcregistry.io/
- https://eprint.iacr.org/2016/1007.pdf
- https://www.dasp.co/
- https://consensys.github.io/smart-contract-best-practices/
- https://github.com/sigp/solidity-security-blog
- https://solidity.readthedocs.io/en/latest/bugs.html

## Contributions

Submit a PR!
