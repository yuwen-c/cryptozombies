# smart contract 功能

- 每個 user 可以養自己的殭屍軍隊
- user 可以藉由原有的殭屍，去吃 cryptoKitten 得到新的殭屍
- user 的殭屍可以藉由攻擊別人的殭屍獲得升級
- user 可以付錢讓殭屍升級
- user 可利用 MetaMask 登入

# 特點

- 建立符合 ERC-721 非同質化代幣標準的 token
- 與其他以太坊區塊鏈上的 smart contract 互動
- 將一個大型合約依照功能區分，劃分為多個小合約
- 合約擁有者可修改合約
- gas 優化，避免不必要的儲存
- user 可支付費用、owner 可提款
- 使用者可用 Metamask 管理的帳號與合約互動
- 監聽殭屍產生的事件，並通知 current user

# 技術

- 使用 solidity 撰寫以太坊區塊鏈的 smart contract
- 使用 web3.js，使 user 可以由前端介面與合約互動
- 引入 OpenZeppelin 的 Ownable contract 來確保合約 Owner 的權限，避免 function 被濫用
- 引入 SafeMath 避免 uint overflow 和 underflow
- 撰寫符合 natspec 格式的註解
- 支援 MetaMask 擴充工具，user 可以選定的帳戶和 DApp 互動。
