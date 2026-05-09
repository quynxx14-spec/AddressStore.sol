# AddressStore.sol
AddressStore.sol
pragma solidity ^0.8.20;
contract AddressStore {
    address public user;

    function set(address _u) public {
        user = _u;
    }
}
