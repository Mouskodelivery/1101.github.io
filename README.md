<img width="240" height="140" alt="logo-TouchNGo_0" src="https://github.com/user-attachments/assets/57cdc3ed-03e9-4804-a12f-8c5fa6e73ddf" />
<img width="240" height="140" alt="logo-PromptPay2" src="https://github.com/user-attachments/assets/64e3828c-7375-4c29-ba85-4bf0dd494520" />
<img width="240" height="140" alt="logo-PayPal_0" src="https://github.com/user-attachments/assets/3c7f007e-48dc-46ee-8c10-9261b2b1d9cb" />
<img width="240" height="140" alt="logo-MasterCard" src="https://github.com/user-attachments/assets/85aa3b8c-d7b5-4cee-bd45-b8c3bd879927" />
<img width="225" height="225" alt="logo-linepay" src="https://github.com/user-attachments/assets/663a6d61-33ca-4b56-9b6e-69cd14f601d1" />
<img width="225" height="225" alt="logo-gx" src="https://github.com/user-attachments/assets/9a9c0147-86a0-4605-9f76-1ff43d4b824b" />
<img width="240" height="140" alt="logo-GrabPay_0" src="https://github.com/user-attachments/assets/c587eb00-ff61-4dda-8cb3-0d54dd9bf5b3" />
<img width="225" height="225" alt="logo-grabpay" src="https://github.com/user-attachments/assets/cb3005c7-9bd9-4b87-82c2-40b9d63a93cd" />
<img width="240" height="140" alt="logo-GooglePay_0" src="https://github.com/user-attachments/assets/5f8f44ca-c150-4374-b8b9-5d046c6e612e" />
<img width="240" height="140" alt="logo-GCash_0" src="https://github.com/user-attachments/assets/a515c99a-7f5e-4a48-bcb9-e0dd6e921ee7" />
<img width="240" height="140" alt="logo-FPX_0" src="https://github.com/user-attachments/assets/f1160f4d-9578-4a46-a3c7-e52ff75dc14c" />
<img width="240" height="140" alt="logo-Boost_0" src="https://github.com/user-attachments/assets/24fed53f-350d-42e7-95da-c4c99e21e630" />
<img width="240" height="140" alt="logo-ApplePay_0" src="https://github.com/user-attachments/assets/07f08d80-3291-4c38-a1dc-8a8943ef703b" />
<img width="225" height="225" alt="Logo-支付宝" src="https://github.com/user-attachments/assets/d1c5838b-f646-4e86-8528-4eccce8c261a" />
<img width="240" height="140" alt="logo-Visa" src="https://github.com/user-attachments/assets/aaf11fd1-0739-4a12-a593-986cdcf7f653" />
<img width="225" height="225" alt="logo-usdt" src="https://github.com/user-attachments/assets/7c509917-29d4-4040-8ed9-d908d2366f01" />[Untitled-1.html](https://github.com/user-attachments/files/23492100/Untitled-1.html)
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



