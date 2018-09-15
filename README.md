# cellpinda-token-contract
ERC20 contract source code of Cellpinda

Cellpinda
Cellpinda is a token following ERC-20 standard.

Constants
name: 'Cellpinda'
symbol: 'CPD'
decimals: 8
totalSupply: 10 bil.

Methods
balanceOf(address _addr) => (uint256)
transfer(address _to, uint256 _amt) => (bool)
transferFrom(address _from, address _to, uint256 _amt) => (bool)
approve(address _spender, uint256 _amt) => (bool)
allowance(address _owner, address _spender) => (uint256)
increaseApproval(address _spender, uint256 _addedAmt) => (bool)
decreaseApproval(address _spender, uint256 _subtrAmt) => (bool)
burn(uint _amt) => (bool)
burnFrom(address _from, uint256 _amt) => (bool)
mint(address _to, uint256 _amt) => (bool)
pause(bool newPausedPublic, bool newPausedOwnerAdmin)
transferOwnership(address newOwner)
finishMinting() => (bool)

Events
Transfer(address indexed _from, address indexed _to, uint256 _amt)
Approval(address indexed _owner, address indexed _spender, uint256 _amt)
Burn(address indexed _buraddr, uint _amt)
OwnershipTransferred(address indexed prevOwner, address indexed newOwner)
