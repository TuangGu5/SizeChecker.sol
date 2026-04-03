# SizeChecker.sol
SizeChecker.sol9
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SizeChecker {
    function check(uint x) public pure returns (string memory) {
        if (x > 10) return "Big";
        else return "Small";
    }
}
