
<!DOCTYPE html>
<html>
<head>
<title>订单详情</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 20px;
  }
  .container {
    width: 80%;
    margin: auto;
    border: 1px solid #ddd;
    padding: 20px;
  }
  .header {
    text-align: center;
    margin-bottom: 20px;
  }
  .item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 10px;
  }
  .item img {
    width: 50px;
    height: 50px;
    margin-right: 10px;
  }
  .item-details {
    flex-grow: 1;
  }
  .item-price {
    font-weight: bold;
  }
  .summary {
    margin-top: 20px;
    text-align: right;
  }
  .total {
    font-size: 1.2em;
    font-weight: bold;
  }
  .button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    font-size: 1em;
    margin-top: 20px;
  }

  /* 支付方式样式 */
  .payment-methods {
    text-align: center;
    margin-top: 20px;
  }
  .payment-methods img {
    width: 80px; /* 调整图片大小 */
    height: auto;
    margin: 5px;
  }
  .payment-methods p {
    margin-bottom: 10px;
  }
</style>
</head>
<body>

<div class="container">
  <div class="header">
    <h2>订单总结</h2>
  </div>

  <div class="item">
    <img src="test.png" alt="Priority Signature">
    <div class="item-details">
      <div>Priority Signature</div>
      <div>Chicken         x1</div>
    </div>
    <div class="item-price">RM18.00</div>
  </div>

  <div class="item">
    <img src="test.png" alt="Melted Goods">
    <div class="item-details">
      <div>Melted Goods</div>
      <div>Chicken     x1</div>
    </div>
    <div class="item-price">RM18.00</div>
  </div>

  <div class="item">
    <img src="test.png" alt="Melted Goods">
    <div class="item-details">
      <div>Melted Goods</div>
      <div>Chicken     x1</div>
      
    </div>
    <div class="item-price">RM18.00</div>
    <div></div>
  </div>

  <div class="summary">
    <div>小计 (包含税额): RM54.00</div>
    <div>配送费: RM10.00</div>
    <div class="total">总价: RM64.00</div>
  </div>

  <div style="text-align: center;">
   <!-- 订单序列号 -->
  <div class="order-id">
    订单序列号: 1234567890
  </div> 
    
  </div>

  <!-- 支付方式 -->
  <div class="payment-methods">
    <p>我们接受所有主流信用卡以及一系列地区性支付方式。</p>
    <img src="logo-Visa.png" alt="Visa">
    <img src="logo-MasterCard.png" alt="Mastercard">
    <img src="logo-GCash_0.png" alt="GCash">
    <img src="logo-TouchNGo_0.png" alt="Touch 'n Go eWallet">
    <img src="logo-GrabPay_0.png" alt="GrabPay">
    <img src="logo-FPX_0.png" alt="FPX">
    <img src="logo-PromptPay2.png" alt="PromptPay">
    <img src="logo-PayPal_0.png" alt="PayPal">
    <img src="logo-Boost_0.png" alt="Boost">
    <img src="logo-ApplePay_0.png" alt="Apple Pay">
    <img src="logo-GooglePay_0.png" alt="Google Pay">
  </div>
</div>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>支付方式</title>
<style>
  .payment-options {
    width: 80%;
    margin: 20px auto;
    border: 1px solid #ddd;
    padding: 10px;
  }

  .payment-option {
    display: flex;
    align-items: center;
    padding: 10px;
    border-bottom: 1px solid #eee;
    text-decoration: none; /* 移除链接的下划线 */
    color: inherit; /* 继承父元素的颜色 */
  }

  .payment-option:last-child {
    border-bottom: none;
  }

  .payment-option img {
    width: 30px;
    height: 30px;
    margin-right: 10px;
  }

  .payment-option-details {
    flex-grow: 1;
  }

  .payment-option-arrow {
    margin-left: auto;
  }
</style>
</head>
<body>

<!-- 您的网页内容 -->

<div class="payment-options">
  <a href="112233.html" class="payment-option">
    <img src="logo-linepay.png" alt="GX 1256">
    <div class="payment-option-details">
      <div>LINE Pay</div>
    </div>
    <div class="payment-option-arrow">&gt;</div>
  </a>

  <a href="grabpay_page.html" class="payment-option">
    <img src="logo-grabpay.png" alt="GrabPay Wallet">
    <div class="payment-option-details">
      <div>GrabPay</div>
      <div></div>
    </div>
    <div class="payment-option-arrow">&gt;</div>
  </a>

  <a href="grabcoins_page.html" class="payment-option">
    
    <img src="logo-TouchNGo_0.png" alt="充值">
    <div class="payment-option-details">
      <div>TouchNGo</div>
    </div>
    <div class="payment-option-arrow">&gt;</div>
  </a>

  <a href="card_page.html" class="payment-option">
    <img src="logo-gx.png" alt="卡片">
    <div class="payment-option-details">
      <div>Bank Tranfer</div>
    </div>
    <div class="payment-option-arrow">&gt;</div>
  </a>

  <a href="alipay_page.html" class="payment-option">
    <img src="Logo-支付宝.png" alt="支付宝">
    <div class="payment-option-details">
      <div>支付宝</div>
    </div>
    <div class="payment-option-arrow">&gt;</div>
  </a>

  <a href="alipayhk_page.html" class="payment-option">
    <img src="logo-MasterCard.png" alt="AlipayHK">
    <div class="payment-option-details">
      <div>行用卡/借记卡</div>
    </div>
    <div class="payment-option-arrow">&gt;</div>
  </a>

  <a href="kakaopay_page.html" class="payment-option">
    <img src="logo-usdt.png" alt="Kakao Pay">
    <div class="payment-option-details">
      <div>USDT</div>
    </div>
    <div class="payment-option-arrow">&gt;</div>
  </a>
</div>

</body>
</html>


